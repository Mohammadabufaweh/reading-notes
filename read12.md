
# CREATE ANIMATED CHARTS WITH JS
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
First we link it:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>
```

+ Drawing a line chart
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:

```html
<canvas id="buyers" width="600" height="400"></canvas>
```
Next, we need to write a script that will retrieve the context of the canvas

+ Drawing a pie chart:

Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:

```html
<canvas id="countries" width="600" height="400"></canvas>
```
Next, we need to get the context and to instantiate the chart:

```js
var countries= document.getElementById("countries").getContext("2d");
new Chart(countries).Pie(pieData, pieOptions)
```

+ Drawing a bar chart:

Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element:

```html
<canvas id="income" width="600" height="400"></canvas>
```

Next, we retrieve the element and create the **graph**:

```js
var income = document.getElementById("income").getContext("2d");
new Chart(income).Bar(barData);
```

# The `<canvas>` element
At first sight a `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the `<canvas>` element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.
Fallback content



The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`,` <audio>`, or `<picture>` elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

Providing fallback content is very straightforward: just insert the alternate content inside the `<canvas>` element. Browsers that don't support `<canvas>` will ignore the container and render the fallback content inside it. Browsers that do support `<canvas>`will ignore the content inside the container, and just render the canvas normally.

Required `</canvas> `tag:
As a consequence of the way fallback is provided, unlike the `<img>` element, the` <canvas>` element requires the closing tag `(</canvas>)`. If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed


# Drawing shapes with canvas

+ The grid:
Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we'll see how we can translate the origin to a different position, rotate the grid and even scale it, but for now we'll stick to the default.
Drawing rectangles:
Unlike SVG, `<canvas>` only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.

+ Drawing text:
The canvas rendering context provides two methods to render text:

fillText`(text, x, y [, maxWidth])`
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
strokeText`(text, x, y [, maxWidth])`
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.


+ Styling text
In the examples above we are already making use of the font property to make the text a bit larger than the default size. There are some more properties which let you adjust the way the text gets displayed on the canvas:

+ `font = value`

The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
+ `textAlign = value`

Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
+ `textBaseline = value`

Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
+ `direction = value`

Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.
These properties might be familiar to you, if you have worked with CSS before.
