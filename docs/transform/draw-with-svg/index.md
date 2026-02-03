---
layout: default
title: Use SVG to design a pattern
---

# Use SVG editor to design a pattern

Contents
---------------------

- [Edit pattern with SVG](#edit-pattern-with-svg)
- [Pattern from download](#pattern-from-download)

Edit pattern with SVG
---------------------

You can also use a general purpose editor like Adobe-Illustrator, CorelDraw or the free InkScape
and the [SVG version] (right click to download) of the template.

![](matrix-template-object.png)

The symbol in each template object has six free snapping points,
two of them should be connected with other objects.
Copy-paste these objects to define a pattern without changing the length or directions of lines connecting the symbols. It might need some out-of-the-box thinking: the Binche snow flake example above has horizontal connections and the vertical connection is reduced to a single stitch. Stretching the stitch into a kind of plait with a hole (`ctcttctc`) reveals traditional connections in the thread diagram.

[SVG version]: template.svg

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