---
layout: default
title: Flip stitches
---
Mirrored and rotated stitches.
==============================

Soundless video clip.

<video controls style="border: 1px solid; padding-top: 2px;">
    <source src="flip.mp4" type="video/mp4">
    Your browser does not support an inline <a href="flip">video</a>.
</video>  

The table below illustrates the implementation. This gives expected results in a diamond mesh.

<table>
    <tr>
        <td class="sn sw"><code id="mb">crcl</code></td>
        <td class="sn de"></td>
        <td class="sn dw"></td>
        <td class="sn se"><code id="md">clcr</code></td>
    </tr>
    <tr>
        <td class="ds sw"></td>
        <td class="ds de">b</td>
        <td class="ds dw">d</td>
        <td class="ds se"></td>
    </tr>
    <tr>
        <td class="dn sw"></td>
        <td class="dn de">p</td>
        <td class="dn dw">q</td>
        <td class="dn se"></td>
    </tr>
    <tr>
        <td class="ss sw"><code id="mp">lcrc</code></td>
        <td class="ss de"></td>
        <td class="ss dw"></td>
        <td class="ss se"><code id="mq">rclc</code></td>
    </tr>
</table>

With a working pair, we get less expected results. For example [qllcr] below.
Flipping a stitch below does not give the stitch with the same color in another quadrant,
but a stitch with another color in the same quadrant.

![](cllcr-bdpq.svg)

[qllcr]: https://d-bl.github.io/GroundForge/stitches.html?b1=cllcr&c1=crrcl&b2=rcllc&c2=lcrrc&tile=88,11&a1=rctctctctt&l2=lctctctctt&shiftColsSW=0&shiftRowsSW=2&shiftColsSE=2&shiftRowsSE=2&patchWidth=10&patchHeight=12&headside=x,7&footside=4,x