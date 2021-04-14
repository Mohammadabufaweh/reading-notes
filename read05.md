# Images

There are many reasons why you might want to add an image to a web page, you might want to include a logo, photograph, illustration, diagram, or chart.
First ,There are several factor you should consider to prepare the web page as profitional:
+ Pick which image format to use
+ Show an image at the right size
+ Optimize an image for use on the web to make pages load faster

![istockphoto](https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__340.jpg)

The important of a images on the site hidden by the amount od information and expritions that can abridgement by the images.
### Images should:
+ Be relevant
+ Convey information
+ Convey the right mood
+ Be instantly recognisable
+ Fit the color palette
and  we have alot of websites can help o find best image:

[istockphoto](www.istockphoto.com)

[gettyimages](www.gettyimages.com)

[veer](www.veer.com)

[sxc](www.sxc.hu)

[fotolia](www.fotolia.com)

this code how add images 
```css
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
```
### src
This tells the browser where it can find the image file.
### alt
This provides a text description of the image which describes the image if you cannot see it. 
### title
You can also use the title attribute with the `<img>` element to provide additional information about the image.

there ar three rules you should consider it:
1. Save images in the right format
1. Save images at the right size
1. Use the correct resolution
## Figure and Figure Caption:
Use a <figure> element to mark up a photo in a document, and a <figcaption> element to define a caption for the photo:
```html
<figure>
  <img src="pic_trulli.jpg" alt="Trulli" style="width:100%">
  <figcaption>Fig.1 - Trulli, Puglia, Italy.</figcaption>
</figure>
```
# color
There are three ways to specify colors in CSS:

RGB values

hex codes

color names.

### Rgb values

These express colors in terms of how much red, green and blue are used to make it up. For example:
```css
rgb(100,100,90)
```
### Hex codes
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example:
```css
#ee3e80
```
### color names
There are 147 predefined color names that are recognized by browsers. For example:
```css
DarkCyan
```
## background-color
You can specify your choice of background color in the same three ways:
```html
body {
  background-color: lightblue;
}
```

### Opacity opacity, rgba
Allow you to specify the opacity of an element and any of its child elements,and the fourth value to indicate opacity (a)

**rgba(red, green, blue, alpha)**
```html
<h1 style="background-color:rgba(255, 99, 71, 0);">rgba(255, 99, 71, 0)</h1>
```
the result of code:

<h1 style="background-color:rgba(255, 99, 71, 0);">rgba(255, 99, 71, 0)</h1>

## hsl, hsla
hsl(hue, saturation, lightness)
```html
<h1 style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</h1>
```
the result of code:

<h1 style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%)</h1>

##  hsla(hue, saturation, lightness, alpha)
```html
<h1 style="background-color:hsla(9, 100%, 64%, 0.2);">hsla(9, 100%, 64%, 0.2)</h1>
```
the result of code:
<h1 style="background-color:hsla(9, 100%, 64%, 0.2);">hsla(9, 100%, 64%, 0.2)</h1>

# Text
Specifying Typefaces (font-family) The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to
which a CSS rule applies.
and this website help you tto find best font style
[fonts.google](https://fonts.google.com/)
### Size of Type (font-size):
```css
h1 {
  font-size: 40px;
}

h2 {
  font-size: 30px;
}

p {
  font-size: 14px;
}
```

### Alignment(text-align)
```css
div.a {
  text-align: center;
}

div.b {
  text-align: left;
}

div.c {
  text-align: right;
}

div.c {
  text-align: justify;
}
```