## Ordered lists
Ordered lists are lists where each item in the list is
numbered. For example,
```html
<ol>
<li>First order</li>
<li>Second order</li>
<li>Therd order</li>
<li>Fourth order</li>
</ol>
```
the result of the code:
1-First order
2-Second order
3-Therd order
4-Fourth order

## Unordered lists
Unordered lists are lists that begin with a bullet point
```html
<ul>
<li>First order</li>
<li>Second order</li>
<li>Therd order</li>
<li>Fourth order</li>
</ul>
```
the result of the code:
+ First order
+ Second order
+ Therd order
+ Fourth order
## Definition Lists
there are three iteams:
`<dl>` consists of a series of terms and their definitions.
`<dt>` This is used to contain the termbeing defined (the definitionterm).
`<dd>`
This is used to contain the
definition.

```html
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
```

## Border, Margin and Padding
### Border
Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.
### Margin
Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.
### Padding
Padding is the space between the border of a box and any content contained within it. Adding padding can increase the  readability of its contents.
```css
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```
![photo](https://s1.o7planning.com/en/12495/images/51081143.gif)

### border style
+ solid a single solid line
+ dotted a series of square dots
+ dashed a series of short lines
+ double two solid lines 
+ ridge appears to stick out from the page
+ inset appears embedded into the page
+ outset looks like it is coming out of the screen
+ hidden / none no border is shown
### border color
border-top-color
border-right-color
border-bottom-color
border-left-color
![photo2](https://miro.medium.com/max/2732/1*MBmEamfzUMue7NDdqNQdVQ.png)

### Display
#### inline
This causes a block-level element to act like an inline element.
block
This causes an inline element to act like a block-level element.
#### inline-block
This causes a block-level element to flow like an inline element, while retaining other features of a block-level element
#### none
This hides an element from the
page.