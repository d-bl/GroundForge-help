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

The table below illustrates the implementation.

<table>
    <tr>
        <td class="sn sw"><code id="mb">cllcr</code></td>
        <td class="sn de"></td>
        <td class="sn dw"></td>
        <td class="sn se"><code id="md">crrcl</code></td>
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
        <td class="ss sw"><code id="mp">rccl</code></td>
        <td class="ss de"></td>
        <td class="ss dw"></td>
        <td class="ss se"><code id="mq">lcrrc</code></td>
    </tr>
</table>

This gives expected results in a diamond mesh.
With a working pair, we get less expected results.
We see reflections when flipping along the green dashed lines but not with the red dashed line.

![](cllcr-bdpq.svg)


[diamond](https://d-bl.github.io/GroundForge/stitches.html?patchWidth=12&patchHeight=15&footside=4,x&tile=-5-5-,5-5-5,-5-5-,5-5-5&headside=x,7&shiftColsSW=0&shiftRowsSW=4&shiftColsSE=5&shiftRowsSE=1&e1=ctc&c1=ctc&a1=ctctctl&n2=ctctctr&f2=crrcl&d2=cllcr&b2=ctc&e3=ctc&c3=ctc&f4=lcrrc&d4=rcllc&b4=ctc)
/
[weaving](https://d-bl.github.io/GroundForge/stitches.html?b1=cllcr&c1=crrcl&b2=rcllc&c2=lcrrc&tile=88,11&a1=rctctctctt&l2=lctctctctt&shiftColsSW=0&shiftRowsSW=2&shiftColsSE=2&shiftRowsSE=2&patchWidth=10&patchHeight=12&headside=x,7&footside=4,x)