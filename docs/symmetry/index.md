---
layout: default
title: edit symmetries
---

Edit symmetries
===============

Browse through dozens of pattern variations created from a single template.

The [editor](GroundForge/symmetry) is inspired by Veronika Irvine's course on [DFZ] in 2021.
The course teaches a pencil and tracing paper method to combine copies of tiles into arrangements with a variety of symmetries.

Currently, it is not possible to generate thread diagrams from the generated patterns.

[DFZ]: https://doily-free-zone.namastream.com/product/26887/about


Download / Browse
-----------------
Other GroundForge pages use address bar components to define a pattern.
With the symmetry editor you start with init, can save your work
with a download and browse your saved files to reload.
When editing a downloaded diagram with some SVG editor,
it can still be reloaded, but editing might no longer work.

After reloading you might have to manually adjust the width and height
for a new template to make other changes to the reloaded patterns work.

New template
------------
Explanation of the form fields.

The bottom line in the following image shows how the tile dimensions are expressed with number of stitches.
Note that large dimensions can make the page slow and vieuwing all the patterns will 
require scrolling or zooming out (ctrl-minus on Windows, cmd-minus on Mac) by your browser.

![](tile-size.png)

Note the corners in variant 1 and 2 below.
For those who followed the DFZ course: the frame of the template is not rendered.

![](variant-1.png)
![](variant-2.png)

The text field should contain a 4x4 sequence defining a custom pattern.

Patterns, constructed with the template
---------------------------------------
Patterns are constructed by reflections, rotations and glides of the template.
The letters `bdpq` are used to illustrate these transformations,
`x` stands for any of the four letters.
The predefined patterns have the four letter arranged in diagonals, columns, rows and squares.
A text field is available to define a custom pattern as the last of all pattern variations.

    bx bx bb    bdpq bbbb    dbdb bpbp bpbp ....
    xb bx xx    bdpq dddd    qpqp qpqp dqdq ....
                bdpq dddd    bdbd dbdb bpbp ....
                bdpq dddd    pqpq qpqp dqdq ....


Edit a template with mouse actions
------------------------------------

### Click

A form specifies how many twist are set when you click a pair
and whether a clicked stitch is deleted or gets its color code changed.

![](twists.png) &nbsp; &nbsp;
![](delete-color-code.png)

Note that the color codes are reflected with the rest of the tiles,
but the tool-tips are not.

Stitches along the edges of the template are projected on top of one another
when repeated in mirrored and rotated copies.
It is not possible to delete these stitches.
Stitches along the top and bottom are kept identical, black in the illustration below.
This also happens with the stitches along the sides, red in the illustration below.

![](edge-stitches.png)

### Drag

#### Stitches

Moving stitches is pretty trivial.
Stitches along the edges can not be moved.
The algorithm does not enforce any limits on moving stitches,
so it is your own responsibility to avoid crossing lines.

#### Center of pairs

Moving the center of a pair is a kind of pinching action to create a new stitch.
On mouse down you will see two highlighted pairs kissing the selected pair,
interrupted by some segments that should not make a connection
because they touch the selected segment.

![](kissing.png)

Without these highlights you might be tempted
to make a connection with one of the grey lines at the bottom of the big hole.
That would create an impossible loop in a pair.
When you release the mouse after dragging, the algorithm creates a new stitch
with the green segment whose center is closest to the mouse position.
In the example, the connection could easily be made with the wrong highlighted pair.
Make sure to move close enough to the desired pair.

Third party editors
-------------------

After download you can customize the generated patterns with a third party editor.
For example indent the patterns that don't react to the indent form field.
To improve performance you might want to remove the patterns you are not interested in. 

Note that these customisations get lost after reloading and making other adjustments.
It is also possible that other customisation break functionality.