# The <canvas> element :
At first sight a < canvas> looks like the < img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the < canvas> element has only two attributes, width and height .

The id attribute isn't specific to the < canvas> element but is one of the global HTML attributes which can be applied to any HTML element (like class for instance). It is always a good idea to supply an id because this makes it much easier to identify it in a script.

The < canvas> element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas. We'll see how this is done in a dedicated chapter of this tutorial. When no styling rules are applied to the canvas it will initially be fully transparent.


![image](https://miro.medium.com/max/1006/0*y7IF3MXZ0BjfUHp7)

# Drawing rectangles
Unlike SVG, <canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.

- fillRect(x, y, width, height)
Draws a filled rectangle.
- strokeRect(x, y, width, height)
Draws a rectangular outline.
-clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.

Drawing paths :
Here are the functions used to perform these steps:

- beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
- Path methods
Methods to set different paths for objects.
- closePath()
Adds a straight line to the path, going to the start of the current sub-path.
- stroke()
Draws the shape by stroking its outline.
- fill()
Draws a solid shape by filling the path's content area.

# Drawing text :
The canvas rendering context provides two methods to render text:

- fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.