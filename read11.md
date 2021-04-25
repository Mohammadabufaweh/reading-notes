# Images

+ controlling sizes of images in CSS:

You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.

+ AligNi ng images Using CSS:

Rather than using the <img>
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:
1. The float property is added
to the class that was created to
represent the size of the image
(such as the small class in our
example).
2. New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.

+ Centering image USING CSS:

By default, images are inline
elements. This means that they
flow within the surrounding text.
In order to center an image, it
should be turned into a blocklevel
element using the display
property with a value of block.
Once it has been made into a
block-level element, there are
two common ways in which you
can horizontally center an image:
1. On the containing element,
you can use the text-align
property with a value of center.
2. On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.

+ Background Images
The background-image
property allows you to place
an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.
The path to the image follows
the letters url, and it is put
inside parentheses and quotes.
```css
p {
background-image: url("images/pattern.gif");}
```
+ Repeating Images:
1. repeat
The background image is
repeated both horizontally and
vertically
2. repeat-x
The image is repeated
horizontally only.
3. repeat-y
The image is repeated vertically
only.
4. no-repeat
The image is only shown once.
5. fixed
The background image stays in
the same position on the page.
6. scroll
The background image moves
up and down as the user scrolls
up and down the page.

+ Background Position:
When an image is not being
repeated, you can use the
background-position
property to specify where in the
browser window the background
image should be placed.
This property usually has a pair
of values. The first represents
the horizontal position and the
second represents the vertical.
+ **(horizontal vertical)**.
+ left top
+ left center
+ left bottom
+ center top
+ center center
+ center bottom
+ right top
+ right center
+ right bottom

+ IMAGE ROLLOVERS AND SPRITES:
Using CSS, it is possible to create
a link or button that changes to a
second style when a user moves
their mouse over it (known as a
rollover) and a third style when
they click on it.
This is achieved by setting a
background image for the link or
button that has three different
styles of the same button (but
only allows enough space to
show one of them at a time).

+ GRADIENTS:
CSS3 is going to introduce the
ability to specify a gradient for
the background of a box. The
gradient is created using the
background-image property
and, at the time of writing,
different browsers required a
different syntax.
Since it is not supported by all
browsers, it is possible to specify
a background image for the box
first (which would represent the
gradient) and then provide the
CSS alternatives for browsers
that support gradients.


# Practical Information
Search Engine Optimization (SEO)
SEO is a huge topic and several books have been written on the subject.
The following pages will help you understand the key concepts so you can
improve your website's visibility on search engines.
+ The Basics
Search engine optimization (or
SEO) is the practice of trying
to help your site appear nearer
the top of search engine results
when people look for the topics
that your website covers.
At the heart of SEO is the idea of
working out which terms people
are likely to enter into a search
engine to find your site and then
using these terms in the right
places on your site to increase
the chances that search engines
will show a link to your site in
their results.

+ On-Page Techniques
On-page techniques are the
methods you can use on your
web pages to improve their
rating in search engines.
The main component of this is
looking at keywords that people
are likely to enter into a search
engine if they wanted to find
your site, and then including
these in the text and HTML code
for your site in order to help the
search engines know that your
site covers these topics.
+ Off-Page Techniques
Getting other sites to link to you
is just as important as on-page
techniques. Search engines help
determine how to rank your
site by looking at the number of
other sites that link to yours.
They are particularly interested
in sites whose content is related
to yours. For example, if you
were running a website that
sold fish bait, then a link from
a hairdresser is not likely to be
considered as relevant as one
from an angling community.

+ On-Page SEO

1. Page Title
The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the `<title>` element which lives
inside the `<head>` element.
2. URL / Web Address
The name of the file is part of
the URL. Where possible, use
keywords in the file name.
3. Headings
If the keywords are in a heading
`<hn>` element then a search
engine will know that this page is
all about that subject and give it
greater weight than other text.
4. Text
Where possible, it helps to
repeat the keywords in the main
body of the text at least 2-3
times. Do not, however, over-use
these terms, because the text
must be easy for a human to
read.
5. Link Text
Use keywords in the text that
create links between pages
(rather than using generic
expressions such as "click here").
6. Image Alt Text
Search engines rely on you
providing accurate descriptions
of images in the alt text. This
will also help your images show
up in the results of image-based
searches.
7. Page Descriptions
The description also lives inside
the <head> element and is
specified using a <meta> tag.
It should be a sentence that
describes the content of the
page.
![p](https://raddinteractive.com/wp-content/uploads/2020/07/Content-Optimization-e1595864063599.png)















