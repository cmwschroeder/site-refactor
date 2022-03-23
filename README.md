Project: Site Refactor

This readme will go over the changes made to the Horiseon site. The first change was the title,
to make it descriptive I changed the title to Horiseon Home. The second change was for the semantics.
I started off with changing the header and the footer divs to header and footer tags. They now describe
their exact purpose with the tag, being the head and foot of the page. Next I changed the buttons in the
header into a nav tag instead of a div tag. Since these buttons would navigate the page. Next I changed the 
div's that contained the info, first being the bigger text fields into a main tag, and the side box into
an aside tag. Then I changed all of the div tags inside the main and aside tags into section tags, to 
describe that these are all sections of information, and not just random blocks like a div tag would
imply. The last tag I changed was the div classed as hero. I changed this to a figure tag and put an img
between the fig tabs as I could not figure out how to put just an image tag and still keep the width of the
img as flexible with the size of the browser, and figure tag explains that this is a picture describing
the page. Lastly for semantics I added a class descriptor for the span tag in order to explain exactly what
it does.

After the semantic changes I added alt attributes to all the images to explain exactly what it is if 
someone clicks the page and cannot see the images for whatever reason. Then I changed the h3 tag in the
footer to better follow a heading structure into an h4 tag, as it was the fourth different type of heading.

Lastly I consolodated all of the css elements so that there was no unneccessary writting in the css file, as
multiple elements had the same changes done to them.

Technology used:

HTML and CSS