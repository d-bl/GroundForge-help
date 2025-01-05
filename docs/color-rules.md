---
layout: default
title: 4 colors per stitch
---

Color codes
===========

Various dialects of color codes for pair diagrams are used by bobbin lace designers:
There is at least a [Belgian] version, a simplified [Danish] version and a [red-blue] version and perhaps more.
These dialects use just one color per stitch what accommodates at most about half a dozen of stitches.

These systems have in common that only one color represents a stitch.
These are easy to draw by hand and sufficient for traditional styles of bobbin lace.
When experimenting with unorthodox stitches and grounds we need to distinguish more than those half a dozen of colors.

[Belgian]: https://www.mail-archive.com/lace@arachne.com/msg51345.html
[Danish]: https://www.mail-archive.com/lace@arachne.com/msg51355.html
[red-blue]: https://susanroberts.info/wp-content/uploads/2019/08/Working-diagrams-part-2.pdf

[2x2swatches](/GroundForge/images/to-color-rules.png)  serves as a reminder:
the color numbers are arranged in a clockwise order
starting with red (=danger alias unusual) as zero.

4 colors per stitch
===================

This page explains how GroundForge uses up to four colors per stitch to
distinguish up to four crosses per stitch and up to three twists
between those crosses, as well as tallies and plain plaits.
If we count mirrored versions of stitches, the color code can distinguish over 4K
separate stitches. It does have one drawback: the approach may be too elaborate to 
draw accurately by hand.


Twists
------

| none| one | two | more | |
| :---: | :---: | :---: | :---: | :--- |
| ~~&nbsp;&nbsp;&nbsp;&nbsp;~~ | ~~&nbsp; ! &nbsp;~~ | ~~&nbsp; !! &nbsp;~~ | ~~&nbsp; !!! &nbsp;~~ | twists between stitches |
| {% include circle.svg color="#CA0020" %}  | {% include circle.svg color="#0571B0" %} | {% include circle.svg color="#F4A582" %} | {% include circle.svg color="#92C5DE" %} | twists between crosses |

Colors for the twists fill blank shapes in the following table.

Crosses
-------

| | |
| :---: | :--- |
| {% include circle.svg color="black" %} | 1. just a single cross |
| {% include polyline.svg points="14,4 4,4 4,24 24,24 24,4 14,4 14,24" %} | 2. cross - twist(s) - cross |
| {% include polyline.svg points="14,4 4,14 14,24 24,14 14,4 14,24 24,14 4,14" %} | 3. cross - twist(s) - cross - twist(s) - cross |
| {% include 4c.svg width="22" height="22" %} | 4. cross - twist(s) - cross - twist(s) - cross - twist(s) - cross; e.g. brussels stitch: ctct-pin-ctct or winkie pins |
| {% include rectangle.svg width="7" height="14" %} | `ctctctc` and longer plaits |
| {% include rectangle.svg width="14" height="14" %} | `cllcrrcllc` and longer or mirrored tallies |
| ![](images/other-stitches.png) | none of the above |

Examples
--------

The following examples combine the color rules relating to _twists_ with the shapes representing the _crosses_.
Note that each `t` of the captions is translated into an `l` plus `r` in the drawings.

![](images/examples.svg)

With [B3.24](GroundForge/droste?source=mix4snow&source=mix4snow&tile=17-w,rx-x,rx-x,rx31,-w17,-xrx,-xrx,31rx,17-w,rx-x,rx-x,rx31,-w17,-xrx,-xrx,31rx&f8=llttcrr&f16=llttcrr&footside=-----x,-----x,-----x,-----x,-----4,-----r,-----r,-----r,-----x,-----x,-----x,-----x,-----4,-----r,-----r,-----r&=undefined&u8=rrttcll&u16=rrttcll&headside=x,x,x,8,r,r,r,r,x,x,x,8,r,r,r,r&shiftColsSW=0&shiftRowsSW=16&shiftColsSE=4&shiftRowsSE=8&patchWidth=14&patchHeight=35&i1=rc&h1=ctc&g1=lcr&h2=crclcr&n5=llctt&i5=lc&g5=ct&j9=lc&h9=ctc&j13=ctc&g13=lc&g16=ctc&h16=lcr&h4=ct&h8=cr&g8=ctc&g9=lc&g12=lc&i12=ctc&j12=lcr&i13=lcr&j16=lc&j4=cr&i4=ctc&j5=ctc&i8=lc&j8=lc&i16=lcr&g4=lcr&droste2=h160=g42=j120=i162=cttc,g160=h161=g41=h13=g80=h80=g121=h93=i120=j121=i161=j133=i140=i40=i81=j53=j40=c,i122=g162=i42=g82=tctc,j131=h11=j51=h91=ctct,h162=h12=h81=h92=g83=g163=j122=j132=i123=j52=i43=j41=crc,g161=g40=h10=g81=g120=h90=i121=i160=j130=i41=i141=i80=j50=clc,i123=i43=g163=g83=lcrcl,j130=j50=h10=h90=rclcr,h13=j133=j53=h93=crr,i161=i81=g41=g121=cll,h161=h80=j40=j121=rrc,i120=i40=g160=g80=llc,u82=u162=ctc,u81=u161=tttttttctctttttt,u83=u163=tttttctc,u80=u160=tttctc#)
from [Viele Gute Gründe](MAE-gf/docs/literature)
we compare another solution for unorthodox stitches with the system developed for GroundForge.

![](images/B3-24.svg)

The example below is a variation of 
[E12](/GroundForge/stitches?whiting=E12_P167&patchWidth=20&patchHeight=20&h1=ct&c1=ctctt&a1=ctctt&i2=ctrct&h2=ct&g2=ct&f2=ct&e2=ctlct&h3=ct&g3=ct&f3=ct&b3=ctctt&i4=ctrct&h4=ct&g4=ct&f4=ct&e4=ctlct&f5=ct&c5=ctct&a5=ctct&j6=ctrct&i6=ct&h6=ct&g6=ctct&f6=ct&e6=ct&d6=ctlct&i7=ct&e7=ct&j8=ct&i8=ct&h8=ctlct&f8=ctrct&e8=ct&d8=ct&c8=ctlct&a8=ctrct&j9=ct&d9=ct&j10=ct&i10=ctlct&e10=ctrct&d10=ct&c10=ct&b10=ctct&a10=ct&tile=7-4----7--,x-xwaaa1cy,-5-x-788-x,y-wxa111cx,7-4--7----,x-x2a1cdd6,x-x-7---4-,8-1a1c-b8d,---7-x-x-4,d3a1cx-xb8&footsideStitch=ctctt&tileStitch=ct&headsideStitch=ctctt&shiftColsSW=-5&shiftRowsSW=10&shiftColsSE=5&shiftRowsSE=10),
[A2](/GroundForge/stitches?whiting=A2_P71&tile=831,4-7,-5-&headside=d,-,c,-&footside=b,-,a,-&footsideStitch=ctctt&patchWidth=9&patchHeight=10&k1=lctctt&d1=ct&c1=ctct&b1=ct&a1=rctctt&d2=ctct&b2=ctct&k3=lctctt&c3=ctct&a3=rctctt&tileStitch=ctct&headsideStitch=ctctt&shiftColsSW=-2&shiftRowsSW=2&shiftColsSE=2&shiftRowsSE=2) and
[F9](/GroundForge/stitches?whiting=F9_P185&patchWidth=26&patchHeight=26&m1=ctc&e1=ctc&o3=llcttctt&k3=cttctt&g3=ctcrrrctc&e3=ctc&c3=ctcllctc&g4=ctc&e4=ctc&i5=llctctt&g5=ctc&e5=ctc&c5=ctc&a5=rrctctt&e6=ctc&c6=ctc&o7=cttctt&k7=cttctt&g7=ctcrrctcrr&e7=ctc&c7=ctcllctcll&tile=--x-5-x---x-c-x-,-----w-----y-w--,--g-g-c---b---c-,---w8-mv-yx---xw,h-g-f-f-5-x---x-,-w8-mv---w-----y,--f-f-c---c---b-,--xw--x---xw-yx-&footsideStitch=ctctt&tileStitch=ctc&headsideStitch=ctctt&shiftColsSW=-8&shiftRowsSW=8&shiftColsSE=8&shiftRowsSE=8) 
from the sampler by [Gertrude Whiting](gw-lace-to-gf).
It shows the difference between the tick marks for double and triple twists. The pattern shows also variations of winkie pins.

![](images/F9-variation.png) ![GW sampler F9](images/gw-F9.png)

Notes
-----

The color scheme was selected from [colorbrewer](https://colorbrewer2.org/?type=diverging&scheme=RdBu&n=5)
because of its color-blind friendly properties.

Not having twists between stitches encoded in the colors of the stitches, 
makes the diagrams agnostic to the open (start with twist) and close (end with twist) method.
The tooltip when hovering over a stitch may have the twist one either one of the stitches. 
