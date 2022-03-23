# Site Refactor

## Description

This readme will go over the changes made to the Horiseon site. The first change was the title,
to make it descriptive it was changed to Horiseon Home. The second change was for the semantics.
The first removals were the div with tags, header and footer. This was changed to regulare header and footer tags. They now describe
their exact purpose with the tag, being the head and foot of the page. The next change was the buttons in the
header into changed to a nav tag instead of a div tag. Since these buttons would navigate the page. The next change was the 
div's that contained the info, first being the bigger text fields into a main tag, and the side box into
an aside tag. Then all of the div tags inside the main and aside tags were changed into section tags, to 
describe that these are all sections of information, and not just random blocks like a div tag would
imply. The last tag changed was the div classed as hero. This changed into a figure tag and and img was put
in the fig block. Lastly the span was given a better descriptor for its class.

After the semantic changes alt attributes were added to all the images to explain exactly what it is if 
someone clicks the page and cannot see the images for whatever reason. Then the h3 tag was changed into the
an h4 tag in the footer to bettwer follow an order with the header tags.

Lastly all the CSS files were consolodated so that there were no unncessary descriptors that could have
already been stated with less lines of code. This makes the css file much shorter.

## Table of Contents

* [Technologies](#technologies)
* [Link](#link)
* [Screenshots](#screenshots)

## Technologies

 HTML and CSS

## Link

https://cmwschroeder.github.io/site-refactor/

## Screenshots

![Top of page](https://github.com/cmwschroeder/site-refactor/blob/main/assets/images/screenshot-one.png?raw=true)

![Bottom of page](https://github.com/cmwschroeder/site-refactor/blob/main/assets/images/screenshot-two.png?raw=true)