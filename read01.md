In order to learn how to write web pages, it is very important to understand how to structure documents. In this chapter you will:
 + See how HTML describes the structure of a web page
 + Learn how tags or elements are added to your document
 + Write your first web page

HTML Describes the Structure of Pages
```html
<html>
<body>
<h1>This is the Main Heading</h1>
<p>This text might be an introduction to the rest of
the page. And if the page is a long one it might
be split up into several sub-headings.<p>
<h2>This is a Sub-Heading</h2>
<p>Many long articles have sub-headings so to help
you follow the structure of what is being written.
There may even be sub-sub-headings (or lower-level
headings).</p>
<h2>Another Sub-Heading</h2>
<p>Here you can see another sub-heading.</p>
</body>
</html>
```
The HTML code (in angle bracket) is made up of characters that live inside angled
brackets — these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and
closing tags.HTML Uses Elementsto Describe the Structure of Pages


![photo ](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png)

**The Evolution of HTML** Each new version was designed
to be an improvement on the last (with new elements and
attributes added and older code
removed).
### HTML4 Released 1997
HTML4 is the latest standard released by the World Wide Web consortium (www.w3.org) for web pages. Making sure that your pages comply with standards like HTML4 will allow your site to be viewed by the maximum number of visitors.

![photo2 ](https://coursework.vschool.io/content/images/2018/01/html5_sectioning_high_level.jpg)

### XHTML1.0 Released 2000
In 1998, a language called XML was published. Its purpose was to allow people to write new markup languages.

there some new, more **strict** rules about writing markup. For example:
+ Every element needed a closing tag (except for empty
elements such as <img />).
+ Attribute names had to be in lowercase.
+ All attributes required a value, and all values were to be placed in double quotes.
+ Deprecated elements shouldno longer be used.
+ Every element that was opened inside another element should be closed inside that same element.
### HTML5 Released 2000
HTML5 is a programming language whose acronym stands for Hyper Text Markup Language. It is a system that allows the modification of the appearance of web pages, as well as making adjustments to their appearance. It also used to structure and present content for the web

New Html 5 Layout Elements


![photo3 ](https://www.w3schools.com/html/img_sem_elements.gif)

## Header
```html
<article>
  <header>
    <h1>A heading here</h1>
    <p>Posted by John Doe</p>
    <p>Some additional information here</p>
  </header>
  <p>Lorem Ipsum dolor set amet....</p>
</article>
```
## Footer
```html
<footer>
  <p>Author: Hege Refsnes</p>
  <p><a href="mailto:hege@example.com">hege@example.com</a></p>
</footer>
```
## Navigation
```html
<nav>
  <a href="/html/">HTML</a> |
  <a href="/css/">CSS</a> |
  <a href="/js/">JavaScript</a> |
  <a href="/python/">Python</a>
</nav>
```
## Section

```html
<section class="popular-recipes">
<h2>Popular Recipes</h2>
<a href="">Yakitori (grilled chicken)</a>
<a href="">Tsukune (minced chicken patties)</a>
<a href="">Okonomiyaki (savory pancakes)</a>
<a href="">Mizutaki (chicken stew)</a>
</section>
<section class="contact-details">
<h2>Contact</h2>
<p>Yoko's Kitchen<br />
27 Redchurch Street<br />
Shoreditch<br />
London E2 7DP</p>
</section>
```

The new HTML5 elements i XX ndicate the purpose of
different parts of a web page and help to describe
its structure.
XX The new elements provide clearer code (compared
with using multiple <div> elements).
XX Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.
XX To make HTML5 elements work in Internet Explorer 8
(and older versions of IE), extra JavaScript is needed,
which is available free from Google.


**Javascript** is one of three main colum to build your webpage ,javascript able the user to interactive with the page access the content of the page ,modify the content of the page , responding and react to what the user does like:

A button is pressed.
A link is clicked or tapped on.
Information is added to a form.
A web page has finished loading.
alert("Hello");

so when we write this command the webpage onpen box show the messege “Hello”

## HOW HTML, CSS, and JAVASCRIPT FIT TOGETHER

![photo4 ](https://brytdesigns.com/wp-content/uploads/2019/12/html_css_javascript_infographic.png)

