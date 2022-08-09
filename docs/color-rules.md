---
layout: default
title: Color code rules
---

Color code rules
================

The Belgian color code and [similar systems](Color-Code) are sufficient for traditional styles of bobbin lace and easy to draw by hand.
When experimenting with unorthodox stitches and grounds we need to distinguish more stitches than possible with half a dozen of colors.

This page explains how GroundForge uses up to four colors per stitch to
distinguish up to three crosses and up to three twists
between those crosses, as well as tallies and plain plaits.
If we count mirrored versions of stitches, the color code can distinguish 147 total
separate stitches. It does have one drawback: the approach may be too elaborate to 
draw accurately by hand.

The ![swatches](/GroundForge/images/swatches.png) icon in the caption of a pair diagram
provides enumerations of the applied stitches. 
For publishing purposes, you can use third party software to merge
the downloads of the pattern and the enumeration.

Twists
------

![nrs](/GroundForge/images/to-color-rules.png) The icon leading to this page serves as a reminder:
the color numbers are arranged in a clockwise order starting with red (=danger alias unusual) as zero.

| none| one | two | more | |
| :---: | :---: | :---: | :---: | :--- |
| ~~&nbsp;&nbsp;&nbsp;&nbsp;~~ | ~~&nbsp; ! &nbsp;~~ | ~~&nbsp; !! &nbsp;~~ | ~~&nbsp; !!! &nbsp;~~ | twists between stitches |
| {% include circle.svg color="#CA0020" %}  | {% include circle.svg color="#0571B0" %} | {% include circle.svg color="#F4A582" %} | {% include circle.svg color="#92C5DE" %} | twists between crosses |

Colors for the twists fill shapes in the following table.

Crosses
-------

| | |
| :---: | :--- |
| {% include circle.svg color="black" %} | 1. just a single cross |
| {% include polyline.svg points="14,4 4,4 4,24 24,24 24,4 14,4 14,24" %} | 2. cross - twist(s) - cross |
| {% include polyline.svg points="14,4 4,14 14,24 24,14 14,4 14,24 24,14 4,14" %} | 3. cross - twist(s) - cross - twist(s) - cross |
| {% include rectangle.svg width="7" height="14" %} | `ctctctc` and longer plaits |
| {% include rectangle.svg width="14" height="14" %} | `cllcrrcllc` and longer or mirrored tallies |

Examples
--------

The following examples combine the color rules relating to _twists_ with the shapes representing the _crosses_.
Note that each `t` of the captions is translated into an `l` plus `r` in the drawings.

![](images/examples.svg)

The [Whiting catalogue](gw-lace-to-gf) has real life examples. 
Some interesting ones in the context of _four colors per stitch_ are
[E12](/GroundForge/tiles?whiting=E12_P167&patchWidth=20&patchHeight=20&h1=ct&c1=ctctt&a1=ctctt&i2=ctrct&h2=ct&g2=ct&f2=ct&e2=ctlct&h3=ct&g3=ct&f3=ct&b3=ctctt&i4=ctrct&h4=ct&g4=ct&f4=ct&e4=ctlct&f5=ct&c5=ctct&a5=ctct&j6=ctrct&i6=ct&h6=ct&g6=ctct&f6=ct&e6=ct&d6=ctlct&i7=ct&e7=ct&j8=ct&i8=ct&h8=ctlct&f8=ctrct&e8=ct&d8=ct&c8=ctlct&a8=ctrct&j9=ct&d9=ct&j10=ct&i10=ctlct&e10=ctrct&d10=ct&c10=ct&b10=ctct&a10=ct&tile=7-4----7--,x-xwaaa1cy,-5-x-788-x,y-wxa111cx,7-4--7----,x-x2a1cdd6,x-x-7---4-,8-1a1c-b8d,---7-x-x-4,d3a1cx-xb8&footsideStitch=ctctt&tileStitch=ct&headsideStitch=ctctt&shiftColsSW=-5&shiftRowsSW=10&shiftColsSE=5&shiftRowsSE=10),
[F9](/GroundForge/tiles?whiting=F9_P185&patchWidth=26&patchHeight=26&m1=ctc&e1=ctc&o3=llcttctt&k3=cttctt&g3=ctcrrrctc&e3=ctc&c3=ctcllctc&g4=ctc&e4=ctc&i5=llctctt&g5=ctc&e5=ctc&c5=ctc&a5=rrctctt&e6=ctc&c6=ctc&o7=cttctt&k7=cttctt&g7=ctcrrctcrr&e7=ctc&c7=ctcllctcll&tile=--x-5-x---x-c-x-,-----w-----y-w--,--g-g-c---b---c-,---w8-mv-yx---xw,h-g-f-f-5-x---x-,-w8-mv---w-----y,--f-f-c---c---b-,--xw--x---xw-yx-&footsideStitch=ctctt&tileStitch=ctc&headsideStitch=ctctt&shiftColsSW=-8&shiftRowsSW=8&shiftColsSE=8&shiftRowsSE=8)
and [A2](/GroundForge/tiles?whiting=A2_P71&tile=831,4-7,-5-&headside=d,-,c,-&footside=b,-,a,-&footsideStitch=ctctt&patchWidth=9&patchHeight=10&k1=lctctt&d1=ct&c1=ctct&b1=ct&a1=rctctt&d2=ctct&b2=ctct&k3=lctctt&c3=ctct&a3=rctctt&tileStitch=ctct&headsideStitch=ctctt&shiftColsSW=-2&shiftRowsSW=2&shiftColsSE=2&shiftRowsSE=2).

Notes
-----

The color scheme was selected from [colorbrewer](https://colorbrewer2.org/?type=diverging&scheme=RdBu&n=5)
because of its color-blind friendly properties.

We have some options left for other purposes
by tilting the shapes and/or divide them in another direction.
Larger or more complex symbols would become illegible or could cause collisions
in animated versions of pair diagrams, such as the centre of large 
[spiders](https://jo-pol.github.io/GroundForge/tiles.html?patchWidth=20&patchHeight=20&g1=tc&a1=ctctctcttt&l2=crcrcrclll&k2=ctctc&j2=cttcttc&i2=ctttctttc&h2=crcrc&g2=cttc&f2=clclc&e2=ctttctttc&d2=cttcttc&c2=ctctc&b2=clclclcrrr&l3=ctc&k3=ctc&j3=clllc&i3=crrcrrc&h3=clcrc&g3=cttcttc&f3=crclc&e3=cllcllc&d3=crrrc&c3=ctc&b3=ctc&a3=cc&l4=ctc&k4=cllc&j4=crrrcrrrc&i4=cllcrc&h4=cllcrrc&g4=ctttc&f4=crrcllc&e4=crrclc&d4=clllclllc&c4=crrc&b4=ctc&a4=ccc&l5=clc&k5=rctct&j5=clllcrc&i5=clllcrrc&h5=ctc&g5=ctttctttc&f5=ctc&e5=crrrcllc&d5=crrrclc&c5=lctct&b5=crc&a5=ctc&l6=rctct&k6=ctc&j6=ctc&i6=clcrclc&h6=c&f6=c&e6=clclcrc&d6=ctc&c6=ctc&b6=lctct&a6=cc&tile=5-----5-----,-CDDD632AAAB,566666322222,566666322222,566666322222,566666-22222&shiftColsSW=-6&shiftRowsSW=6&shiftColsSE=6&shiftRowsSE=6).
N.B: shapes with all sections the same colors would be duplicates of the sets in the tables above. 
