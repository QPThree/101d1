# Main Head

## Chart.js

[Chart.js Basics](#topic1)

[Basic Usage](#topic2)

[Drawin with Canvas](#topic3)

---

<a name="topic1"></a>

## Chart.js Basics

Chart.js is a plugin that allows us to display data in charts on our web pages.  Charts are an incredibly effective, stylish way to display data.

Chart.js is first downloaded and unzipped.  A copy is then made in the directory of our project, and imported into our HTML file via a script tag.

A canvas element is then used in our HTML and will be where the chart will be rendered.

Using our chart object, we can pass in data via a script and use a method (e.g. .line()) to render our data.  Our data can be sotred as an object containing labels and arrays of values as our data.

Pie and bar methods can also be called to render our data as the respective kind of chart.

<a name="topic2"></a>

## Basic Usage

### Canvas Element

The canvas element doesn't need a *src* or *alt* property.  Typically it is passed the height and width properties, making it similar to an image tag in that regard.

An ID property and value is typically places inside our canvas element to make it easy to identify when writing our script.

**Fallback** content can be placed inside of the canvas tags. In older browsers the canvas tag will be ignored and the fallback content will be rendered.  If the chart is able to be rendered, however, then the fallback content will be irrelevant to the canvas tags.

Unlike our IMG tags, the canvas element requires a closing < / canvas> tag.

<a name="topic3"></a>

## Drawing with Canvas

Rectangles and paths (lines) can be drawn with canvas. We can use functions such as *fillRect(x,y, width, height)* to make our life easier when making shapes.

*Paths* are a list of points that canvas connects to make custom lines. There is a long list of path drawing functions used.  The basic gist of path creation, though, is to begin the path *beginPath()*, connect the last point to a new (x,y) coordinate *lineTo()*, and move the point of our pen to the start of the current sub-path with *closePath()*. The *fill()* function makes a solid shape by filling in the path's area. 

~ QP3

[Home](../README.md)

Information put into my own words came from *MDN Web Docs* by on Web and Canvas API's
