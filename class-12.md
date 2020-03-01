# The `<canvas>` element
* the only clear difference between imag and canvas is being that it doesn't have the src and alt attributes.The canvas element has only two attributes, width and height.
* The `<canvas>` element can be styled just like any normal image (margin, border, background…).
# Drawing shapes with canvas
* Drawing rectangles
* Unlike SVG, <canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. 
### Drawing paths
 A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths, we take some extra steps:

1. First, WE create the path.
Then you use drawing commands to draw into the path.
Once the path has been created, you can stroke or fill the path to render it.
Here are the functions used to perform these steps:

beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
Methods to set different paths for objects.
closePath()
Adds a straight line to the path, going to the start of the current sub-path.
stroke()
Draws the shape by stroking its outline.
fill()
Draws a solid shape by filling the path's content area.
# The lineJoin property determines how two connecting segments (of lines, arcs or curves) with non-zero lengths in a shape are joined together (degenerate segments with zero lengths, whose specified endpoints and control points are exactly at the same position, are skipped).

There are three possible values for this property: round, bevel and miter. By default this property is set to miter. Note that the lineJoin setting has no effect if the two connected segments have the same direction, because no joining area will be added in this case.
