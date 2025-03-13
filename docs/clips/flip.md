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
It subsequently assigns the text value to stitches in the pair diagram.

Symmetry
--------

Table of contents

* [Symmetry introduction](#symmetry-introduction)
* [Symmetry on a diagonal net](#symmetry-on-a-diagonal-net)
  * [What the flip buttons do](#what-the-flip-buttons-do)
  * [Internal symmetry](#internal-symmetry)
--* [Symmetry on a horizontal net](#symmetry-on-a-horizontal-net)
* [Wrapping up](#wrapping-up)

Symmetry on a diagonal net
--------------------------

Just an example of mirrored stitches placed on a diagonal net.
The diagram on the right shows the working directions of the stitches.

![](external-symmetry.png)

### What the flip buttons do

Mirrored representation: b ⇔ d, p ⇔ q

a. Replace each R in the with L and each L with R

    CTCRC ⇒ CTCLC

Mirrored representation: b ⇔ p, d ⇔ q

a. Read backwards  

    CTCRC ⇒ CRCTC
    CTRCTLC ⇒ CLTCRTC  

How to make the quartet of stitches

a. Apply mirror b ⇒ d  
b. Apply mirror d ⇒ q  
c. Apply mirror q ⇒ p  

    CTCRC ⇒ CTCLC  
    CTRCLC ⇒ CTLCRC  

### Internal symmetry

The following examples produce less than four different stitches by mirroring.

![](internal-symmetry.png)

The mirrored representations of b and d are identical if b has no left or right twist actions (only T, no R and no L). b=d in the picture above.
The mirrored representations of b and p are identical if b is a palindrome. b=p in the picture above.
All mirrored representations d, q, p, b are identical if b has no left or right twist and is a palindrome. b=d=p=q in the picture above.

Symmetry on a horizontal net
------------------------

The working directions in a horizontal net cause challenges when flipping stitches.

![](horizontal-symmetry.png)

In the diagrams above, b and q can only be executed on a left to right row, 
d and p on a right to left row.
Compare b of the left diagram with p of the right diagram:
only changing the working direction rotates the stitch by 45 degrees in a clockwise direction.
Compare both b's, and we see that reading the stitch instructions backwards has the same effect.

The algorithm for the flip buttons assumes stitches are placed on diagonal rows.
Applied in horizontal rows we need the following rules to avoid rotations:
* After the _both_ button: apply in a row with the same direction.
* After a `↔` or `↕`: apply in a row in opposit direction.


Wrapping up
-----------

The stitches above were drawn manually. 
Below screenshots of GroundForge annotated with dashed lines. 

You can reproduce the thread diagrams B and D on this [nets](/GroundForge/nets.html?b=crcllc&colors)
page with stitch _crcllc_: click/tap _horizontal: b+d+p+q_ and _diagonal: b+d+p+q_.
We are talking about the first diagram in each group.
For the pair diagrams A and C you need to click the links in the diagram captions.

Direct links for the pair diagrams:
[A+B](/GroundForge/stitches?e1=crcllc&g1=clcrrc&e3=cllcrc&g3=crrclc&patchWidth=11&patchHeight=14&footside=----,---b,&tile=5-5,-5-,5-5&headside=-,c,&shiftColsSW=-4&shiftRowsSW=2&shiftColsSE=3&shiftRowsSE=1)
and
[C+D](/GroundForge/stitches?e1=crcllc&g1=clcrrc&e3=cllcrc&g3=crrclc&patchWidth=16&patchHeight=18&footside=--r-,----,--g-,--r-&tile=n-n-,---,g-g,---&headside=n,r,r,-&shiftColsSW=0&shiftRowsSW=4&shiftColsSE=4&shiftRowsSE=4).

![](cllcr-bdpq.svg)

The fat arrow heads indicate working directions.
Each blue dashed line indicate flip axis.
A red dashed line in D is not a flip axis.
From this we see that de vertical mirror in pair diagram C is deceptive.
The pinkish arrows show how the stitches in B rotate by 45 degrees in D.