Documentation 

##Documentation of the website CASES

This is the new website of the company CASES.


##Languages

This website is developed in HTML/CSS, Markdown, Liquid, with the framework Jekyll and Bootstrap 3.3.7., and a bit of Javascript.

To install it, please visit this [page] (https://jekyllrb.com/docs/installation) 

To see more about [Liquid] : (https://shopify.github.io/liquid)

To see more about [Markdown] (https://blog.ghost.org/markdown/)

And finally to know more about [Boostrap] (https://getbootstrap.com/docs/3.3/)


##A new website, but what for ?

The old website hasn't an ergonomic design, now information (publications, articles, knowhow, services) 

are displayed in order to be easy to find.


##Summary

Step by step, we'll see the different folders, how this website works, where we need to go to update the content, etc.

1. [Layouts](###Layouts)

2. [Includes](###Includes)

3.

4.

5.

6.

<h3 id="layouts">Layouts</h3>

Folder : /_layouts/

This is the arborescence of the layouts. 

On the top we have "default", then every layouts add something to "default", in order to complete their design.


default
|
|------contact
|
|------home         
|                   
|------knowhow      
|                    
|------article                         
|                                                                          
|------legal
|
|------publication-list
|
|------page
|
|------post
|
|------index


####Default

The main design is the page "**default**".

On this page, we have the imports (The compiled and minified javascript) :

* jquery-1.12.4.min.js

* bootstrap.min.js

* jquery.touchSwipe.min.js

Under the imports, there is a **script** for the carousel on the homepage. Without this script, it won't swipe to the left or to the right.    

On this page, we have to include some other pages, "**head.html**", **header.html**" and "**footer.html**". 

On the page "head.html" there are a few imports :

* bootstrap.min.css

* bootstrap-theme.min.css


####Home

This layout is for the page "**Home**". This page displays a carousel, the list of the different categories, as 

Articles, Publications, Knowhow, and on the left we have a Twitter plugin. 

####Page

This layout is for the page "**Services**". This page displays the different services of CASES.

On the left, we have a **Table of Content** (**TOC**) composed by a few buttons. These buttons are on the this layout.

We loop through the folder "services" and link the buttons to the correct pages. 

On the right, we have another TOC, with all the titles and subtitles.


####Knowhow 

This layout is for the page "**Knowhow**".This page displays the knowhow of the company through a few articles.

Since there are articles once again, this page is also composed by a TOC on the left and on the right.

For the left TOC, if we want to add another category or page, we have nothing to change in the file "knowhow.html" 

because the file's addition is dynamic. 

There is also a script which change the bullet of the article's list.


####Post & index

These layouts are for the page "**Articles**".

The first one displays an complete article, the second one displays 4 articles with an extract under them. 
 
On the left we have a TOC with a list of all articles, from the most recent to the oldest. 

On the right, we have a TOC with the titles and subtitles. 

Besides, to see all articles, the framwework has a feature, a pagination. We display 4 articles per page.


####Publication-list

This layout is for the page "**Publications**". 

On the left we have a TOC with a list of all publications, they are sorted by categories. 

On the right, we have a TOC with the titles and subtitles. 

If we want to add a new category, we need to add a "tag" to "**list-cat**" and it's name to "**list-name**".

On this page there is also a script which change the bullet of the publication's list.


####Legal

This layout displays just a few lines about legal information, the protection of personal data and the law.


####Contact

This layout is for the page "**Contact**".

It displays a oogle Maps widget with the company's address and some information as Twitter or GitHub. 



###Includes

####Header


