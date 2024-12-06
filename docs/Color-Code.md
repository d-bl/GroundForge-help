---
layout: default
title: Single color per sticth
---

Color Code
==========

- [Color code dialects](#color-code-dialects)
- [up to 4 colors per stitch](color-rules)
- 1 color per stitch by GroundForge for Droste diagrams
  - [Twist marks](#twist-marks)
  - [Colors](#colors-by-groundforge)
  - [Tweak Colors](#tweak-colors)


Color code dialects
===================

Various dialects of color codes for pair diagrams are used by bobbin lace designers:
There is at least a [Belgian] version, a simplified [Danish] version and a [red-blue] version and perhaps more.
These dialects use just one color per stitch what allows only about half a dozen of stitches.

These systems have in common that only one color represents a stitch.
These are easy to draw by hand and sufficient for traditional styles of bobbin lace.
When experimenting with unorthodox stitches and grounds we need to distinguish more than those half a dozen of colors.

One of the pair diagrams in GroundForge applies a completely different [approach](/GroundForge/images/stitches-legens.svg).
This approach uses up to four colors per stitch. 

The pair diagrams for the Droste patterns still apply a dialect of the [Belgian] code,
details in the following sections.
Due to technical complications the new approach is not applied.

[Belgian]: https://www.mail-archive.com/lace@arachne.com/msg51345.html
[Danish]: https://www.mail-archive.com/lace@arachne.com/msg51355.html
[red-blue]: https://susanroberts.info/wp-content/uploads/2019/08/Working-diagrams-part-2.pdf

For the Droste diagrams
=======================

Droste diagrams are thread diagrams used as pair diagrams to produce another thread diagram.

Twist marks
-----------

The _intention_ is a twist mark wherever there are multiple twists in a pair but the implementation is buggy.

The reason of this approach is the ability to apply and even mix 
open stitches (start with twist) and closed stitches (end with twists).
Hover over stitches to figure out the exact definition as shown below.

![](images/dialect.png)

[notify]: https://groundforge.wordpress.com/

Colors by GroundForge
---------------------

A plait in a pair diagram is not drawn as ">---<" but as "X" but still blue.
Same for "&#41289;" (pins are hardly supported anyway)
turquoise and brown represent this family of stitches.

stitch name             | color                                |           | examples and notes
:----------------------:|:------------------------------------:|:---------:|:-------------------------------------------
half stitch             | ![](images/color-code/green.png)     | green     | `ct`, `tc`, `ttc`, `tct` (just one time `c` and both pairs twisted at least once)
cloth stitch            | ![](images/color-code/purple.png)    | purple    | `ctc`, `ctcl`, `rctc` (just `ctc` and at most on pair twisted)
double stitch           | ![](images/color-code/red.png)       | red       | `ctct`, `tctc`, `tctct` (just `ctc` and both pairs twisted at least once)
plait                   | ![](images/color-code/blue.png)      | blue      | `ctctc` (a `ctc` followed by at least one `tc`)
turning stitch          | ![](images/color-code/turquoise.png) | turquoise | `cttc` (just two times `c` and both pairs twisted twice in between)
turning stitch variants | ![](images/color-code/brown.png)     | brown     | `cllc`, `crrc`, `ctlc`, `ctrc` (just two times `c` and in between both pair twisted more than twice or each pair another number of twists between the `c`'s)
tally                   | ![](images/color-code/yellow.png)    | yellow    | `cllcrrcllc`, `crrcllcrrc`, (at least four `c`'s alternating with `ll`/`rr`, in turn also alternating)
anything else           | ![](images/color-code/black.png)     | black     | e.g. `ctcttc`, `lcr`

The examples and notes are not exhaustive.
At least there can be additional twists (left, right or both pairs)
at the start and/or end of the examples.
The exact mathematical/functional definition can be found at the bottom of the class
[Stitches](https://github.com/d-bl/GroundForge/blob/master/src/main/scala/dibl/Stitches.scala).


Tweak Colors
------------

A pair diagram has a predefined palette of colors applied to stitches as shown with the following sample.

![](images/color-sample.jpg)

You can tweak the colors of a downloaded diagram to accommodate your monitor, printer or color-blindness. 
Open the downloaded `.svg` file with some plain text editor (or show it full screen and right click to show the page source), you will see a start/end marker definition for each color except black, something like:
```xml
<svg ...>
  <g>
    <defs>
      ...
      <marker id="start-red" ...><path ... stroke="#f00"></path></marker>
      ...
      <marker id="end-red" ...><path ... stroke="#f00"></path></marker>
      ...
    </defs>
  </g>
  ...
</svg>
```

Change the stroke value to adjust a color, several color choosers on the web can provide a RGB value. Save the changes and open the file again in your browser or SVG editor and you will see the adjusted colors all over the diagram.
