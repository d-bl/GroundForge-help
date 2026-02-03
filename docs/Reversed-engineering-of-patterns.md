---
layout: default
title: Advanced Design
---

Working with printed catalogues
=============================

Different methods allow to reproduce a pattern with GroundForge.

- [Recognize patterns](#recognize-patterns)
- [Matrix from pair diagram](#matrix-from-pair-diagram)
  * [Tiling](#tiling)
  * [With an SVG editor](#with-an-svg-editor)
- [Droste method](#droste-method)

Recognize patterns
------------------

The [gallery pages](/GroundForge) are the easiest way to start experimenting with grounds.

The generated pair diagrams don't care about plaits and something-pin-something
and draw them as plain cloth stitches.
Furthermore, the distances between stitches are optimized to some average.
So when trying to start with some familiar pattern to make variations,
you may have to simplify, mirror and distort it
to recognize it in the [TesseLace Index](/tesselace-to-gf)
or match up with the encoding system of GroundForge.

You can find examples on pages: 
* Preparations with a [bias](/GroundForge-help/transform/bias) ground.
* Definition phase with a [rose](/GroundForge-help/Advanced) ground.
* All phases with a [spider](/GroundForge-help/transform/spider).

### With an SVG editor

_Contents moved to [Use SVG to design a pattern](/GroundForge-help/transform/draw-with-svg)_

Droste method
-------------

The Droste method uses thread diagrams as pair diagram.

The image below tries to show how to dissect a pair diagram as if it is a thread diagram.
The blue shapes enclose stitches with two pairs alias threads.
The red shapes collect stitches into a repeat with three rows of the diagonal base pattern, its matrix:

    5-
    -5
    5-

The weaving base pattern has always a checkerboard tiling. The diagonal base pattern needs a brick tiling with an odd number of rows and a checkeboard tiling with an even number of rows.

![](images/disect-pairs-as-threads.png)


Pattern from download
---------------------

A different challenge is reconstructing a pattern definition from a downloaded SVG.
A possible step is filtering the tooltips out of the file with following unix command.

    egrep '[ctlr]+ - [^<]+' '/Users/jokep/Downloads/my problem(1)/3b2pair-diagram.svg'|sed 's!<.*!!'|sed 's!.*>!!'|sort|uniq>ids.txt

When one Droste level is involved, the resulting IDs will be some `xnm` where `xn` identify positions in the tile
and `m` identify a cross, left-twist or right-twist.
By drawing blobs around identical `xn` value you might be able to recognize the `ct` sequence.
When two Droste levels are involved there will be a third digit on the ID.
Then you will also have to draw blobs around identical `xnm` values. 