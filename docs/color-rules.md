---
layout: default
title: 4 colors per stitch
---

Color codes
===========

The Belgian color code and [similar systems](Color-Code) are sufficient for traditional styles of bobbin lace and easy to draw by hand.
When experimenting with unorthodox stitches and grounds we need to distinguish more stitches than possible with half a dozen of colors.

4 colors per stitch
===================

This page explains how GroundForge uses up to four colors per stitch to
distinguish up to three crosses and up to three twists
between those crosses, as well as tallies and plain plaits.
If we count mirrored versions of stitches, the color code can distinguish over 4K
separate stitches. It does have one drawback: the approach may be too elaborate to 
draw accurately by hand.

The ![3x3swatches](/GroundForge/images/swatches.png) icon in the caption of a pair diagram
provides enumerations of the applied stitches. 
For publishing purposes, you can use third party software to merge
the downloads of the pattern and the enumeration.

Twists
------

![2x2swatches](/GroundForge/images/to-color-rules.png) The icon leading to this page serves as a reminder:
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
| {% include 4c.svg width="14" height="14" %} | 4. cross - twist(s) - cross - twist(s) - cross - twist(s) - cross; e.g. winkie pins: ctct-pin-ctct |
| {% include rectangle.svg width="7" height="14" %} | `ctctctc` and longer plaits |
| {% include rectangle.svg width="14" height="14" %} | `cllcrrcllc` and longer or mirrored tallies |
| ![](images/other-stitches.png) | none of the above |

Examples
--------

The following examples combine the color rules relating to _twists_ with the shapes representing the _crosses_.
Note that each `t` of the captions is translated into an `l` plus `r` in the drawings.

![](images/examples.svg)

The [Whiting catalogue](gw-lace-to-gf) has some interesting examples illustrating the _four colors per stitch_ in practice:
[E12](/GroundForge/tiles?whiting=E12_P167&patchWidth=20&patchHeight=20&h1=ct&c1=ctctt&a1=ctctt&i2=ctrct&h2=ct&g2=ct&f2=ct&e2=ctlct&h3=ct&g3=ct&f3=ct&b3=ctctt&i4=ctrct&h4=ct&g4=ct&f4=ct&e4=ctlct&f5=ct&c5=ctct&a5=ctct&j6=ctrct&i6=ct&h6=ct&g6=ctct&f6=ct&e6=ct&d6=ctlct&i7=ct&e7=ct&j8=ct&i8=ct&h8=ctlct&f8=ctrct&e8=ct&d8=ct&c8=ctlct&a8=ctrct&j9=ct&d9=ct&j10=ct&i10=ctlct&e10=ctrct&d10=ct&c10=ct&b10=ctct&a10=ct&tile=7-4----7--,x-xwaaa1cy,-5-x-788-x,y-wxa111cx,7-4--7----,x-x2a1cdd6,x-x-7---4-,8-1a1c-b8d,---7-x-x-4,d3a1cx-xb8&footsideStitch=ctctt&tileStitch=ct&headsideStitch=ctctt&shiftColsSW=-5&shiftRowsSW=10&shiftColsSE=5&shiftRowsSE=10),
[F9](/GroundForge/tiles?whiting=F9_P185&patchWidth=26&patchHeight=26&m1=ctc&e1=ctc&o3=llcttctt&k3=cttctt&g3=ctcrrrctc&e3=ctc&c3=ctcllctc&g4=ctc&e4=ctc&i5=llctctt&g5=ctc&e5=ctc&c5=ctc&a5=rrctctt&e6=ctc&c6=ctc&o7=cttctt&k7=cttctt&g7=ctcrrctcrr&e7=ctc&c7=ctcllctcll&tile=--x-5-x---x-c-x-,-----w-----y-w--,--g-g-c---b---c-,---w8-mv-yx---xw,h-g-f-f-5-x---x-,-w8-mv---w-----y,--f-f-c---c---b-,--xw--x---xw-yx-&footsideStitch=ctctt&tileStitch=ctc&headsideStitch=ctctt&shiftColsSW=-8&shiftRowsSW=8&shiftColsSE=8&shiftRowsSE=8)
and [A2](/GroundForge/tiles?whiting=A2_P71&tile=831,4-7,-5-&headside=d,-,c,-&footside=b,-,a,-&footsideStitch=ctctt&patchWidth=9&patchHeight=10&k1=lctctt&d1=ct&c1=ctct&b1=ct&a1=rctctt&d2=ctct&b2=ctct&k3=lctctt&c3=ctct&a3=rctctt&tileStitch=ctct&headsideStitch=ctctt&shiftColsSW=-2&shiftRowsSW=2&shiftColsSE=2&shiftRowsSE=2).

Notes
-----

The color scheme was selected from [colorbrewer](https://colorbrewer2.org/?type=diverging&scheme=RdBu&n=5)
because of its color-blind friendly properties.

The pair diagrams based on thread diagrams still apply a [variation](Color-Code) of the Belgian color-code with buggy numbers of twist marks. 
