---
layout: article
title:  "Password"
menutitle:
logo:
date:  2017-11-06 00:00:00 +0100
short:
categories: knowhow
toc: true
---
## In brief
The password, a basic element of IT security, authenticates and grants access to a resource or staff service.

In order to reduce the risk of identity fraud, you should choose your password very carefully and stick to some simple rules.

## At least 10 characters
A good password contains at least 10 characters. To make the password more complex, it is advisable to use a combination of numbers, capital and lower-case letters, as well as punctuation marks, for example.

## Easy to remember, difficult to guess
The chosen password must be memorable without having to be written down, while at the same time being difficult to guess by others, including someone who knows you well (see Social Engineering).

**Under no circumstances** should you use:

* a word that can be found in the dictionary (even if taken from a foreign language dictionary),
* a first name,
* your login,
* any information related to yourself (first name, birth date, etc.).

A weak password is often made up of a simple phrase. You can add prefixes, suffixes or symbols to increase its complexity. Password example: ```...:::two cows on the roof:::...```.

If your password needs to be a specific length, create it using the first letters of each word in a sentence. This means that in the example given above, a 9-character password would be:  ```.:tcotr:.```

## Dedicated passwords
Each password must only be used for a specific access. Use separate passwords for different logins or, in the event of theft (by phishing or shoulder surfing), the cybercriminal will have access to several online services.

The more regularly you use your passwords, the easier it will be to remember them. So we recommend you don’t let your browser remember them for you. For infrequently used services, you can always save your passwords in encrypted files created with a program such as *keepass*, for example.

## Change passwords regularly
Changing your passwords regularly is good practice. It’s up to you how often you change them. We think it’s a good idea to allocate one day each year or every two years to changing all your passwords.

Of course, you should also change them immediately if you think they’ve been compromised or someone else has guessed them.

## Personal use
Password access is attributed to a single user. A password should not be shared by several people and you should never disclose it to anyone, regardless of the circumstances.

Don’t forget that trustworthy organisations will never ask you for your password.

## Exchanging passwords
Passwords are used to authenticate an individual and grant them access to specific resources. For this reason, it is inadvisable to exchange passwords with colleagues. If, for organisational reasons (special software installed on a single device), it is necessary to give the password to a specific person during a prolonged absence (holidays, illness), we recommend you proceed in the following way:

1. the password is written on a piece of paper, sealed in a signed envelope and given to the manager.
2. if an authorised person needs access to the password, the opening of the envelope containing it is documented on paper, noting the name of the person who reads the password, along with the date and time.
3. as soon as the person whose password has been revealed returns to work, they must change their password and once again give it to the manager as described in 1)

In this way, the person whose password has been revealed cannot be held responsible for any actions carried out in their absence. Additionally, it is always clear who has access to what resources.

## Frequent vulnerabilities
Authentication is required for all *user* and *administrator* access to servers and software. It is important not to forget about access to the network elements comprising the IT system, such as routers, switches, etc.

The *user name and password* solution is the most widely used. This common solution bases authentication on a combination of user name provided by the administrator and a password that the end user will create. It is important to note that this solution has various recurrent vulnerabilities:

### Accounts with weak or non-existent passwords
When creating a password, some quality criteria should be respected in order to prevent specialised software from being able to guess it in a short amount of time.

### Accounts installed by default when setting up software
During the installation of software such as operating systems, accounts are created by default. These accounts use a password known to all experts. These accounts are obviously the first to be targeted by ill-intentioned people. It is therefore necessary to protect this account with a reliable password.

### Passwords that are no longer private
A password is a confidential element used to identify the user of an account. It falls under the same logic as a PIN code used to withdraw money from ATMs. Unfortunately, it is all too common to see passwords displayed on screens or known by multiple people.

### Software creating users for internal use
Some software creates accounts used internally to converse with other parts of the IT system. These login details and their password, often weak or even non-existent, are documented and obviously known to all the experts.

### Unreliable or non-existent password hashing formulae
Passwords must be saved in the form of the result of an irreversible function, such as the hash function. It is equally important to ensure that a strong hash system is used, in addition to other measures, such as the addition of a salt and stretching

### Memorising computer passwords
Some software, such as the browser, that uses passwords offers users the option of saving their password so they no longer have to enter it every time. Despite the practicalities of this, it is inadvisable for obvious reasons.

### System vulnerabilities
Vulnerabilities in software may allow newcomers to access the system without a password. It is therefore important to keep all software updated and to carry out penetration tests on software developed within the organisation.

### No monitoring or locking in the event of erroneous access attempts
The occurrence of multiple incorrect password entries for the same account should clearly sound very strong alarm bells for an administration manager.

While most IT systems allow you to lock an account after a certain number of erroneous attempts, this feature is not often used, which opens the door to the password cracking software described in this document.

## Password cracking
Authentication mechanisms have long been included in the list of most commonly exploited vulnerabilities.

To perpetrate this type of attack, offenders use specialised decryption software, which relies on two separate technologies:

### “Brute force” or exhaustive password cracking
In this case, the decryption software is going to try all the different combinations of both hybrid characters and alphanumeric characters. This method is effective, but takes an enormous amount of time to decipher complex chains of characters.

Some of the cracking tools are specially designed for a specific software program, such as Microsoft Word, or others.

It should be noted that even under the best circumstances, this technique cannot be used on passwords of around more than 10 characters.

### Dictionary word attack
In this case, the decryption software will try all terms from a specific list, also known as a “dictionary”. Often, the software used to carry out this type of attack will also submit transformations to words from this list, e.g. replacing an “e” by a “3”, or adding numbers to the end. This method is much faster than the exhaustive method, but can only discover common passwords.

## Additional advice
The advice given below applies to the use of authentication by account/password. These rules will need to be configured by you in the administration software, in such a way as to make them automatically applicable to all accounts created.

### Control the IT architecture
It is very important to regularly analyse the logs in order to detect any potential fraudulent access attempts.

Likewise, it is crucial to keep the list of users, their profiles and their IT system rights updated, taking into account the classification of data.

### Limit accounts
“Administrator” accounts, which have a lot of permissions, are the attackers’ preferred target. It is inadvisable to share this account between the whole IT team, but rather to create profiles corresponding to the exact needs of each of the team members.

In the Microsoft Windows platform, it may even be a good idea to limit all the powers of the “administrator” account and to give it a highly complex password. Then all that is needed is to redistribute the tasks to other less visible accounts. By doing so, the potential pirate/cracker will spend their time concentrating on a decoy, since the account won’t allow them to access any information. Unfortunately, this is not possible on the root account on the Unix platform.

### Alternatives
More robust authentication solutions, such as those offered by LuxTrust (based on key public infrastructures) or biometrics are available. The advantage of these solutions is that they do away with the problem of password disclosures or the transmission of critical data on the network. Unfortunately, they can be costly and complex to set up.
