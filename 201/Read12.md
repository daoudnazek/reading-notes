# Chart.Js

**Charts** are used to present data visually in a better way than tables. They are easier get data.

**Chart.js** is a javaScript plugin that uses HTML5 to draw the graph on the page.

![chart.js](https://www.wysiwygwebbuilder.com/images/ChartJS_large.jpg)

**Installation**
You can download the latest version of Chart.js from the [GitHub releases](https://github.com/chartjs/Chart.js/releases/tag/v2.9.3). Detailed installation instructions can be found on the [installation](https://www.chartjs.org/docs/latest/getting-started/installation.html) page.


## The canvas Element 

Canvas element is like image element but has no src and alt attributes, it has only width and height elements.

### The rendering context

var canvas = document.getElementById('tutorial'); .. retrives the node in the DOM.
var ctx = canvas.getContext('2d'); ..drawing context.

### Drawing Shapes With Canvas 

- **Drawing Recatangles** 

 - fillRect(x, y, width, height)
 - strokeRect(x, y, width, height)
 - clearRect(x, y, width, height)

- **Drawing Paths**

 - beginPath()
 - Path methods
 - closePath()
 - stroke()
 - fill()

### Colors 

 - fillStyle = color (Filling Shapes)
 - strokeStyle = color (Shapes Outlines)

### Line Styles 

 - lineWidth = value
 - lineCap = type
 - lineJoin = type
 - miterLimit = value
 - getLineDash()
 - setLineDash(segments)
 - lineDashOffset = value


### Drawing text

 - fillText(text, x, y [, maxWidth]) .. Fills a given text at the position (x,y) with maximum width
 - strokeText(text, x, y [, maxWidth]) .. Strokes a given text at the position (x,y) with maximum width
