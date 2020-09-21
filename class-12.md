# summery
## EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS
![chart](https://www.webdesignerdepot.com/cdn-origin/uploads/2013/11/featured5.jpg)
### Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
### how to do it :
1. The first thing we need to do is download Chart.js. 
2. then create a new html page and import the script
3. To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. 
4.  we need to write a script that will retrieve the context of the canvas, 
5. Inside the same script tags we need to create our data,
### there another chart like 
- Drawing a line chart
- Drawing a pie chart
- Drawing a bar chart

## The ``<canvas>`` element
![canves](https://cdn.mos.cms.futurecdn.net/SbV7qwk7jkrfhey8wWZ4Mb.jpg)
### At first sight a ``<canvas>`` looks like the ``<img>`` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the ``<canvas>`` element has only two attributes, width and height. These are both optional and can also be set using DOM properties.
### The ``<canvas>`` element differs from an <img> tag in that, like for ``<video>``, ``<audio>``, or ``<picture>`` elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers.
#### Drawing rectangles
##### Unlike SVG, ``<canvas>`` only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths
#### Drawing paths
-  First, you create the path.
- Then you use drawing commands to draw into the path.
- Once the path has been created, you can stroke or fill the path to render it.
#### the functions used to perform these steps: ``beginPath()``
##### wa can also used it to draw :
1. Drawing a triangle
2. Moving the pen
3. Lines
4. Arcs
5. Bezier and quadratic curves
6. Making combinations

#### Drawing text
##### The canvas rendering context provides two methods to render text:``fillText(text, x, y [, maxWidth])``
#### A fillText example
``function draw() {
  var ctx = document.getElementById('canvas').getContext('2d');
  ctx.font = '48px serif';
  ctx.fillText('Hello world', 10, 50);
}``


##### Styling text
###### In the examples above we are already making use of the font property to make the text a bit larger than the default size. There are some more properties which let you adjust the way the text gets displayed on the canvas: ``font = value``
