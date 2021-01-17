Charts is the best way to display visually data

we can  use Java and HTML5 to drawing charts

there is a plugin in javascript for charts (Chart.js).

Drawing a line, pie or  bar  chart   firestly we need to make a canvas and identify the height and width of canvas and make for it ID

using js to draw line by gitting the id and changing a context and make a method for it

< canvas > element is used to draw graphics , we have use JS to draw 

< canvas id="myid"  width="XX" height="XX" >
 
Canvas can be styled .

getContext () method for rendering context  after git element id (canvas)

canvas grid have  two-dimensional grid.

canvas support just two shaprs :

-rectangles

-paths

fillRect() function draws a large black square 100 pixels on each side

clearRect() function then erases a 60x60 pixel square from the center

strokeRect() is called to create a rectangular outline 50x50 pixels within the cleared square.

drawing paths:

-beginPath()

-Path methods

-closePath()

-stroke()

-fill()

if canvas initialized or invoke beginPath() we have to use moveto() to change starting point .

To draw arcs or circles, we use the arc() or arcTo() methods

quadraticCurveTo(cp1x, cp1y, x, y) and bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y) for draw complex shapes.

Path2D.addPath( path [ , transform]  ) Adds a path to the current path with an optional transformation matrix.

fillText (text , x , y [ ,  maxWidth ] ) , strokeText (text, x, y [ ,  maxWidth ] ) two methods to render text .

there is styling for text like font - > size , textAlign - > to change position of text 

fillStyle property sets the color or gradient used to fill the drawing , ex ctx.fillStyle = "#FF0000";

 strokeStyle property sets  the color or  gradient used for strokes . like border 

globalAlpha property set alpha value (opacity).

rgba like css


-lineWidth *property sets the current line width in pixels.*

-lineCap *sets the style of the end caps for a line.*

-A lineJoin *connicting segments*

-line dashes *to make dashes line*

-Patterns *to make patterns image*

-shadows









