# Forms
The best known form on the web is probably
the search box that sits right in the middle of
Google's homepage.[Google](www.google.com)

Form Controls
1. ADDING TEXT
+ Text input
+ Password input
+ Text area

2. Making Choices:
+ Radio buttons
+ Checkboxes
+ Drop-down boxes

3. Submitting Forms:
+ Submit buttons
+ Image buttons
4. Uploading Files:
+ File upload


### How Forms Work
![p](https://img.webnots.com/2014/01/How-HTML-Form-Works.png)

Form Structure `<form>`:

Form controls live inside a
`<form>` element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.

### action
Every `<form> `element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.
method

Forms can be sent using one of
two methods: get or post.
### id
We look at the id attribute on
page 183, but the value is used to
identify the form distinctly from
other elements on the page (and
is often used by scripts — such
as those that check you have
entered information into fields
that require values).



### Text Input type="text"

When the type attribute has a
value of text, it creates a singleline
text input.
### name
When users enter information
into a form, the server needs to
know which form control each
piece of data was entered into.
### size
The size attribute should not
be used on new forms. It was
used in older forms to indicate
the width of the text input
(measured by the number of
characters that would be seen).
maxlength
You can use the maxlength
attribute to limit the number
of characters a user may enter
into the text field.


### Password Input `<input>` type="password"

When the type attribute has
a value of password it creates
a text box that acts just like a
single-line text input, except
the characters are blocked out.
### name
The name attribute indicates
the name of the password input,
which is sent to the server with
the password the user enters.
size, maxlength
It can also carry the size and
maxlength attributes like the
the single-line text input.



### Text Area `<textarea>`
The `<textarea>` element
is used to create a mutli-line
text input. Unlike other input
elements this is not an empty
element. It should therefore have
an opening and a closing tag.
### Radio Button `<input>` type="radio"

### name
The name attribute is sent to
the server with the value of the
option the user selects.
### value
The value attribute indicates
the value that is sent to the
server for the selected option.
The checked attribute can be
used to indicate which value (if
any) should be selected when
the page loads.


Checkbox `<input>` type="checkbox"

### name
The name attribute is sent to
the server with the value of the
option(s) the user selects.
### value
The value attribute indicates
the value sent to the server if this
checkbox is checked.
### checked
The checked attribute indicates
that this box should be checked
when the page loads. If used, its
value should be checked.


### Submit Button `<input>` type="submit"
### name
It can use a name attribute but it
does not need to have one.
value
The value attribute is used to
control the text that appears
on a button.


### Labelling Form Controls
`<label>`
When introducing form controls,
the code was kept simple by
indicating the purpose of each
one in text next to it. However,
each form control should have
its own `<label>` element as this
makes the form accessible to
vision-impaired users.
The `<label>` element can be
used in two ways. It can:
1. Wrap around both the text
description and the form input
(as shown on the first line of the
example to your right).
2. Be kept separate from the
form control and use the for
attribute to indicate which form
control it is a label for (as shown
with the radio buttons).
#### for
The for attribute states which
form control the label belongs to.
Note how the radio buttons use
the id attribute. The value of the
id attribute uniquely identifies an
element from all other elements
on a page.



# Lists, Tables and Forms
### Table Properties
**width** to set the width of the
table

**padding** to set the space
between the border of each table
cell and its content

**text-transform** to convert the
content of the table headers to
uppercase

**letter-spacing, font-size**
to add additional styling to the
content of the table headers

**border-top, border-bottom**
to set borders above and below
the table headers

**text-align** to align the writing
to the left of some table cells and
to the right of the others

**background-color** to change
the background color of the
alternating table rows
**:hover** to highlight a table row
when a user's mouse goes over it

#### Gaps Between Cells
#### collapse
Borders are collapsed into a
single border where possible.
(border-spacing will be
ignored and cells pushed
together, and empty-cells
properties will be ignored.)
#### separate
Borders are detached from each
other. (border-spacing and
empty-cells will be obeyed.)



Styling Forms
It is most common to style:
+ Text inputs and text areas
+ Submit buttons
+ Labels on forms, to get the
form controls to align nicely

# Events
When you browse the web, your browser registers different
types of events. It's the browser's way of saying, "Hey, this
just happened." Your script can then respond to these events.

Scripts often respond to these events by updating the content of the web page (via the
Document Object Model) which makes the page feel more interactive. like:
+ INTERACTIONS CREATE EVENTS
+ EVENTS TRIGGER CODE 
+ CODE RESPONDS TO USERS

THREE WAYS TO BIND AN
EVENT TO AN ELEMENT:
+ HTML EVENT HANDLERS
+ TRADITIONAL DOM EVENT HANDLERS
+ DOM LEVEL 2 EVENT LISTENERS

+ Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).

this is more importants point :
+ Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.

+ When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.

+ You can use event delegation to monitor for events
that happen on all of the children of an element.

+ The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.
