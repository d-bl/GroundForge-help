---
layout: default
title: Advanced Design
---

Working with printed catalogues
=============================

Different methods allow to reproduce a pattern with GroundForge.

- [Recognize patterns](#recognize-patterns)
- [Droste method](#droste-method)
- [Pattern from download](#pattern-from-download)

Recognize patterns
------------------

The [gallery pages](/GroundForge) are the easiest way to start experimenting with grounds.

The generated pair diagrams don't care about plaits and something-pin-something
and draw them as plain cloth stitches.
Furthermore, the distances between stitches are optimized to some average.
So when trying to start with some familiar pattern to make variations,
you may have to simplify, mirror and distort it
to recognize it in the [TesseLace Index](/groundforge/tesselace-to-gf)
or match up with the encoding system of GroundForge.

You can find examples on pages: 
* Preparations with a [bias](/GroundForge-help/transform/bias) ground.
* Definition phase with a [rose](/GroundForge-help/Advanced) ground.
* All phases with a [spider](/GroundForge-help/transform/spider).

Help for using an SVG-editor to define a pattern can be found on page _[Use SVG to design a pattern](/GroundForge-help/transform/draw-with-svg)_.   
On this page you also find help for downloading a pattern that is created using an SVG-file.   

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

