---
layout: default
title: Color code rules
---

Color code rules
================

The Belgian color code and similar systems are sufficient for traditional styles of bobbin lace and easy to draw by hand.
When experimenting with unorthodox stitches and grounds we need to distinguish more stitches possible than possible with half a dozen of colors.

This page explains the general rules for a completely different system applied to one of the pair diagrams in GroundForge.
This new approach can distinguish 147 stitches: Anything up to three crosses
and up to three twists between those crosses. As extra also tallies and plain plaits.
One drawback though: this approach may be too elaborate to draw accurately by hand.

The ![swatches](/GroundForge/images/swatches.png) icon in the caption of the pair diagrams
provide enumerations of the stitches applied in the corresponding pair diagram. 
For publishing purposes, you can use third party software to merge
the downloads of the pattern and the enumeration.

Twists
------

| none| one | two | more | |
| :---: | :---: | :---: | :---: | :--- |
| ~~&nbsp;&nbsp;&nbsp;&nbsp;~~ | ~~&nbsp; ! &nbsp;~~ | ~~&nbsp; !! &nbsp;~~ | ~~&nbsp; !!! &nbsp;~~ | twists between stitches |
| {% include circle.svg color="#CA0020" %}  | {% include circle.svg color="#0571B0" %} | {% include circle.svg color="#F4A582" %} | {% include circle.svg color="#92C5DE" %} | twists between crosses |

The colors for the twists are poored into the empty spaces of the shapes in the following table.

Crosses
-------

| | |
| :---: | :--- |
| {% include circle.svg color="black" %} | 1. just a single cross |
| {% include polyline.svg points="14,4 4,4 4,24 24,24 24,4 14,4 14,24" %} | 2. cross - twist(s) - cross |
| {% include polyline.svg points="14,4 4,14 14,24 24,14 14,4 14,24 24,14 4,14" %} | 3. cross - twist(s) - cross - twist(s) - cross |
| {% include rectangle.svg width="7" height="14" %} | ctctctc and longer plaits |
| {% include rectangle.svg width="14" height="14" %} | cllcrrcllc and longer or mirrored tallies |

Examples
--------
![](images/examples.svg)

Notes
-----

The color blind friendly color scheme was provided by [colorbrewer](https://colorbrewer2.org/?type=diverging&scheme=RdBu&n=5)

We have some options left for other purposes
by tilting the shapes and/or divide them in another direction.
Larger or more complex symbols would become illegible or could cause collisions
in animated versions of pair diagrams, such as the centre of large 
[spiders](https://jo-pol.github.io/GroundForge/tiles.html?patchWidth=20&patchHeight=20&g1=tc&a1=ctctctcttt&l2=crcrcrclll&k2=ctctc&j2=cttcttc&i2=ctttctttc&h2=crcrc&g2=cttc&f2=clclc&e2=ctttctttc&d2=cttcttc&c2=ctctc&b2=clclclcrrr&l3=ctc&k3=ctc&j3=clllc&i3=crrcrrc&h3=clcrc&g3=cttcttc&f3=crclc&e3=cllcllc&d3=crrrc&c3=ctc&b3=ctc&a3=cc&l4=ctc&k4=cllc&j4=crrrcrrrc&i4=cllcrc&h4=cllcrrc&g4=ctttc&f4=crrcllc&e4=crrclc&d4=clllclllc&c4=crrc&b4=ctc&a4=ccc&l5=clc&k5=rctct&j5=clllcrc&i5=clllcrrc&h5=ctc&g5=ctttctttc&f5=ctc&e5=crrrcllc&d5=crrrclc&c5=lctct&b5=crc&a5=ctc&l6=rctct&k6=ctc&j6=ctc&i6=clcrclc&h6=c&f6=c&e6=clclcrc&d6=ctc&c6=ctc&b6=lctct&a6=cc&tile=5-----5-----,-CDDD632AAAB,566666322222,566666322222,566666322222,566666-22222&shiftColsSW=-6&shiftRowsSW=6&shiftColsSE=6&shiftRowsSE=6).
N.B: shapes with all sections the same colors would be duplicates of the sets in the tables above. 
