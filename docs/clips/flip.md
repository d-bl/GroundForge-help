---
layout: default
title: Flip stitches
---
Mirrored and rotated stitches.
==============================

Soundless video clip.
---------------------

<video controls style="border: 1px solid; padding-top: 2px;">
    <source src="flip.mp4" type="video/mp4">
    Your browser does not support an inline <a href="flip">video</a>.
</video>   

The clip shows that the buttons `↔` and `↕` change the text field.
You can subsequently assign the text value to stitches in the pair diagram.

Symmetry on a diagonal net
--------------------------
Just an example of a stitch placed on a diagonal net.

![](external-symmetry.png)

### What the flip buttons do

Mirrored representation: b ⇔ d, p ⇔ q

a. Replace each R in the with L and each L with R

    CTCRC ⇒ CTCLC

Mirrored representation: b ⇔ p, d ⇔ q

a. Read backwards
b. Re-order twist groups: T < R < L

    CTCRC ⇒ CRCTC
    CTRCTLC ⇒ CLTCRTC ⇒ CTLCTRC

How to make the quartet of stitches

a. Apply mirror b ⇒ d
b. Apply mirror d ⇒ q
c. Apply mirror q ⇒ p

    CTCRC ⇒ CTCLC ⇒ CLCTC ⇒ CRCTC
    CTRCLC ⇒ CTLCRC ⇒ CLCTRC ⇒ CRCTLC

### Internal symmetry

The following examples produce less than four different stitches by mirroring.

![](internal-symmetry.png)

The mirrored representations of b and d are identical if b has no left or right twist actions (only T, no R and no L). b=d in the picture above.
The mirrored representations of b and p are identical if b is a palindrome. b=p in the picture above.
All mirrored representations d, q, p, b are identical if b has no left or right twist and is a palindrome. b=d=p=q in the picture above.

Symmetry on a square net
------------------------

The working directions in a square net cause complications when flipping stitches.

![](square-symmetry.png)

... TODO ...


Wrapping up
-----------

These 
[diamond](https://d-bl.github.io/GroundForge/stitches.html?patchWidth=12&patchHeight=12&footside=4,x&tile=-5-5,5-5-,-5-5,5-5-&headside=x,7&shiftColsSW=-4&shiftRowsSW=0&shiftColsSE=4&shiftRowsSE=4&e1=ctc&c1=cllcrc&a1=ctctctl&n2=ctctctr&d2=cllcrc&b2=cllcrc&e3=ctc&c3=cllcrc&d4=ctc&b4=ctc)
and
[square](https://d-bl.github.io/GroundForge/stitches.html?b1=cllcr&c1=crrcl&b2=rcllc&c2=lcrrc&tile=88,11&a1=rctctctctt&l2=lctctctctt&shiftColsSW=0&shiftRowsSW=2&shiftColsSE=2&shiftRowsSE=2&patchWidth=10&patchHeight=12&headside=x,7&footside=4,x)
patterns (with other stitches than the video demo at the start of this page) are used to
demonstrate details of the flip effects in the figures below.

![](cllcr-bdpq.svg)

Figure A and C are the [color coded](../color-rules.md) diagrams for B and D.
The fat arrow heads indicate working directions.
Each blue dashed line in A-E indicates a flip axis.
A red dashed line in C-D is not a flip axis.
Mixed dashes: flip axis for the pair diagram but not for the corresponding thread diagram.
The yellow dashed lines in B illustrate how the stitches rotate by 45 degrees to appear in C.

The small arrow heads in G show an impossible situation.
Two arrows meet one another, another goes up:
the direction of the worker pair should have flipped too.
The bright green stitch in F show the right part of G in context.
