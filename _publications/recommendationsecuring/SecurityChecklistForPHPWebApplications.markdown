---
layout: publication-list
title:  "Security checklist for PHP web applications"
menutitle: "Security checklist for PHP web applications"
logo:
date:   2017-11-06 00:00:00 +0100
short: "the most common vulnerabilities of web applications and applicable PHP solutions and best practices"
categories: securing
toc: true
---
## In brief

A short checklist outlining the most common vulnerabilities of web applications and applicable PHP solutions and best practices. Although focused on PHP, this checklist can be extended to all programming languages.

## Validation of inputs
Advice:

* during development the configuration ```error_reporting = E_ALL``` (without removing the ```E_NOTICE```) is used to recognise uninitialised variables; in production, errors should not be displayed in the web interface;
* ```filter_var ()``` and ```filter_input ()``` statements are very useful for filtering and validating inputs;
* the use of content equality and ```===``` type avoids errors during comparison with Booleans. The expression ```(0 == false)``` is *true* while ```(0 === false)``` is *false*;
* casting can be faster than testing (compare the ```is_numeric``` function to a (int) $value type conversion);
* beware of the ```$_REQUEST``` global super variable because it may contain values from many different sources;
* check for different inputs using ```isset```, for example ```isset ($ _ GET ['id']);```
* also pay attention to some fields in ```$_SERVER``` such as ```$_SERVER ['HTTP_REFERER'];```
* as we cannot trust browsers, pass ```$_FILES ['file'] ['name']``` through the ```basename``` function when uploading files; (imagine ```$_FILES ['file'] ['name'] = '../../../etc/passwd'```)
* check the content of uploaded files. Images must be checked with the ```getimagesize()``` function, which returns *false* when the file is not of this type. Think also about the fileinfo extension;
* do not accept serialised objects as input.

In general it is advisable to use the concept of a whitelist for many cases of validation.

An extra layer of protection or protection of an already existing application can be provided by adding "PHP Input Filter" and "PHPIDS" or "mod_security" if you use Apache

## SQL injection
Using raw SQL queries by concatenating variables to the query string is bad practice that can easily lead to unwanted SQL injection.

Advice:

* Use prepared statements. In PHP the easiest way to handle escaping variables is to use an abstraction layer such as PDO.
* Parameterised queries are also accessible for some databases through basic PHP functions (e.g. postgresql or pg_prepare) or with extended libraries such as mysqli.
* If concatenation cannot be avoided, it is imperative to escape the variables using functions of the type "(real_) escape_string". For mysql, for example, find out about the ```mysql_real_escape_string``` function. It is useful to add that the PHP manual advises against using this function, but it can be useful for quick securing of an old application.
* Avoid at all costs automatic techniques such as ```magic_quotes``` and/or generic ```add_slashes```. Each database will react differently to these escape methods.

## Cross-site scripting (XSS)
Consists of the use of javascript as input to be executed during display. This is a very common and dangerous vulnerability, although it is easy to avoid in many cases.
You will find a fairly complete list of possible attacks on the OWASP website.

* transform all characters of displayed variables into html entities. In PHP it is therefore often enough to pass all the variables displayed by the ```htmlentities``` function. Some "templating systems" such as "flexy" make an automatic escape;
* if you need to pass HTML in the variables, the strip_tags function can be used to filter permitted tags. However, this function is dangerous because of the javascript injection in the permitted arguments; e.g.: ```<img onmouseover="alert(‘XSS’);" src="" /> or <a href="javascript:alert(‘XSS’);">link</a>```. It is, therefore, usually necessary to create your own filter function in addition to ```strip_tags```;
* a good way to filter html is the "html purifier" class (http://htmlpurifier.org/, LGPL license).

In general, a generic display function must be written and used during any display.

## Code injection
Injection of malicious code that will be executed by the application.

* avoid using variables in the ```include``` or ```require``` instructions. If it cannot be avoided, the use of whitelist filters is important;
* avoid the "eval" instruction at all costs or treat it with the utmost care; (alternatives (http://www.php.net/manual/de/language.variables.variable.php), closures (http://www.php.net/manual/de/functions.anonymous.php) and the ```call_user_func()```) function
* in php.ini, set ```allow_url_fopen``` to ```off``` if the function is not required.
* avoid variables in ```preg_replace``` type functions.

## Injection of instructions
Some functions can be used to run system instructions.

* avoid variables in instructions such as ```shell_exec```, ```exec```, ```system```, ```passthru```, ```popen```;
* if they cannot be avoided, the ```escapeshellarg()``` and ```escapeshellcmd()``` functions must be used;
* use whitelists and the ```basename``` function in filenames.

## Session security
By stealing the session identifier, other users' sessions can be used. See "firesheep", for example.

* avoid using the session identifier in the URL because another site could steal the identifier by checking the "referer" or might even set your session identifier (imagine a link to a site such as ```link?PHPSESSID=123```). So set ```use_only_cookies``` to ```1``` or ```On``` in ```php.ini```;
* only use SSL (TLS) communications, otherwise the session cookie may be intercepted on hostile networks. Require the session cookie to be communicated only in SSL: ```session.cookie_secure=1;```
* set an expiration time for sessions
* associate visitor IP addresses with their sessions.

## Cross-Site Request Forgery (XSRF)
Involves the use of the open session in another browser tab by a malicious web page. Most often the vulnerable parts will be forms, which could be completed by a malicious site. In this case it is easy to avoid this type of attack by creating a unique identifier for the form and checking it during form submission. It is good practice to use a nonce created by a function such as **uniqid** or pseudo random hash with a secret code by using the ```hash_hmac``` function, which is placed in a **hidden** field on the form and in session, to be checked during submission.

To protect non-form functionalities, case-by-case analysis is required.

## Best practices for storing user passwords in the database
Passwords must be stored in the database in hashed form. To do this, it is important, above all, not to use *md5* or *sha1* type algorithms, for which there are "rainbow tables", which can be used to obtain the password quickly from the hash.

In addition, specifically to avoid the use of *rainbow tables*, and to hide identical hashes from the same password, it is important to use a salt. This salt will be determined randomly and concatenated to the password before hashing. The salt and the hash will therefore be stored in the database.

It is also important to add a secret salt constant that would be stored somewhere other than in the database, for example in a configuration file.

The use of a concatenated **salt** can be usefully replaced by a ```hash_hmac``` hash function, but we recommend the use of the ```crypt``` function ([http://php.net/manual/en/function.crypt.php](http://php.net/manual/en/function.crypt.php)) which enables a cost factor to be added to the calculation when using ```CRYPT_BLOWFISH```, ```CRYPT_SHA256``` or ```CRYPT_SHA512``` (see [key stretching](-)).

The hash calculation will then have the following form, for example:

```php
$hash=crypt(hash_hmac('sha512','secret password',$saltsecretconfig), '$2y$’.$cost.'$randomsaltDB$') ;
```

The variable $cost will need to be set to a number such that the duration of the operation is viable for your application, but prohibitive for a brute-force attack (1/100 seconds for example).

PHP 5.5 introduces new hash functions that enable secure storage of passwords (see http://www.php.net/manual/en/function.password-hash.php).

The function above becomes:

```php
$hash = password_hash(hash_hmac(‘sha512’, ‘secret password’, $saltsecretconfig), PASSWORD_BCRYPT, ['cost'=>$cost]); // from PHP 5.5
```

## Use of countermeasures

In general, a web application will be scanned with an automatic tool by an attacker before compromise. It is therefore possible to place cyber traps or other "tar pits" on the application. A practical example called "weblabyrinth" can be downloaded from http://www.mayhemiclabs.com/content/new-tool-weblabyrinth. But useless scripts containing "sleep" functions or other false authentications can already perform this function.

## Webroot! = Approot
Placing libraries and other scripts in places that cannot be accessed directly from the Internet is a definite advantage. It means that libraries with vulnerabilities cannot be exploited directly.

## Denial of service
It is not possible to defend entirely against denial of service type attacks. However, it is possible to optimise applications so that they respond better. Although this is beyond the scope of this document, the following are some concepts that can be explored:

* use "foreach" only for associative arrays and generally avoid any unbounded iteration on data from databases;
* use a compiled code cache engine (memcache, eaccelerator, Zend Platform, ...);
* some debugging tools can report bottlenecks to you (xdebug, yslow, firebug, ...)
* compress your javascript;
* check for slow queries (```mysql_slow_query```);
* possibly compress server-client communication (only for heavy traffic and where the server CPU is sufficiently powerful);
* if you use Apache consider using the mod_evasion module.

## Frameworks
Many frameworks are written by experienced developers and benefit from their extensive security experience and good programming practices. They often, therefore, include many of the techniques outlined above and enable web applications to be developed more quickly and securely. Examples: Zend, Symfony…

## Advice for php.ini
The ```open_basedir``` configuration function is used to define the directories to which the application has access and therefore offers higher security.

The following php.ini parameters should be set to the needs of your application while trying to keep them as low as possible. In general it is advantageous to set these parameters on the fly with ```ini_set``` in scripts that need more resources than the bulk of the application:

* ```max_execution_time```
* ```memory_limit```
* ```post_max_size```
* ```upload_max_filesize```

Check this value in the production environment:

* ```display_errors = Off```
