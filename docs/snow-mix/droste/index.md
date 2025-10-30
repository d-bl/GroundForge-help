---
layout: default
title: snowflakes with 2 droste steps
---

Snow with two droste steps
==========================

* [Far from exhaustive](#far-from-exhaustive)
* [More freedom](#more-freedom)
* [How to](#how-to)
* [Double worker pairs](#double-worker-pairs)
* [Recipes](#recipes)

Far from exhaustive
-------------------

From [counting snow](/MAE-gf/docs/counting-snow/)
we know that six pair snowflakes can change the order of threads in 230 ways.
Each reordering can be achieved in multiple ways.
[Capturing](/GroundForge-help/Reversed-engineering-of-patterns#recognize-patterns)
them all is therefore impossible.
The [snow mixer](/GroundForge/mix4snow) provides a few dozen
and a tutorial to create variations and new ones.

More freedom
------------

With two [droste](Glossary#droste)  steps you have way more options
to combine snowflakes than with the mixer.
The mixer only allows to assign stitches to one or four snowflakes.
The price: more steps to apply a predefined recipe,
that takes only two clicks with the mixer.

How to
------

![](first-thread.png?align=right)
You can select any pattern from any catalogue and use plaits with three threads as stitches,
for example _lclc_ or _rcrc_ between other stitches (or not). This could look as shown on the right.

Let us take a mixer recipe from the table below as an example.  
![](321-a.png) which is:  _lclc; tc,rclcrc,clcrcl,ct_ and flipped: _rcrc; tc,lcrclc,crclcr,ct_    
Apply the _lclc_ and/or _rcrc_ stitches on the [stitches] page.
You can apply the recipes after following the link to _thread diagram as pair diagram_.
The first droste step then should look like below. 

[stitches]: /GroundForge/stitches?patchWidth=18&patchHeight=35&tile=5-5-5-,-5-5-5,5-5-5-,-5-5-5,5-5-5-,-5-5-5&shiftColsSW=0&shiftRowsSW=6&shiftColsSE=6&shiftRowsSE=6&e1=ctc&c1=ctc&a1=ctc&f2=ctc&d2=ctc&b2=ctc&e3=ctc&c3=crcr&a3=ctc&f4=ctc&d4=ctc&b4=ctc&e5=clcl&c5=ctc&a5=ctc&f6=ctc&d6=ctc&b6=ctc&&droste3=tc,lcrclc,crclcr,ct

![](first-step.png)  
[show](/GroundForge/droste?patchWidth=18&patchHeight=35&tile=5-5-5-,-5-5-5,5-5-5-,-5-5-5,5-5-5-,-5-5-5&shiftColsSW=0&shiftRowsSW=6&shiftColsSE=6&shiftRowsSE=6&e1=ctc&c1=ctc&a1=ctc&f2=ctc&d2=ctc&b2=ctc&e3=ctc&c3=crcr&a3=ctc&f4=ctc&d4=ctc&b4=ctc&e5=clcl&c5=ctc&a5=ctc&f6=ctc&d6=ctc&b6=ctc&&droste3=tc,lcrclc,crclcr,ct&droste2=,c30=tc,c31=rclcrc,c32=clcrcl,c33=ct,e50=tc,e51=lcrclc,e52=crclcr,e53=ct)

Compare the text box of the screenshot with the recipes.
You don't need to edit the bif text box, type the desired stitch 
in the little test box below the stitches gallery,
then click a stitch in the pair diagram to apply.
As this page can be very slow, the diagrams are only re-rendered
after you click the wand.
Changes are highlighted grey until you do. 

Note that for the second step, you need to re-render the pair diagram
before re-rendering the thread diagram. Otherwise, the changes don't appear. 

Double worker pairs
-------------------

Another example turns the worker pair of the initial pair diagram
into two workers going together from left to right, 
negotiate a footside and return together through the next row of snowflakes.

![](square.png)  
[show](https://d-bl.github.io/GroundForge/droste?b1=rcrc&b2=lclc&c1=rcrc&c2=lclc&g1=rcrc&g2=lclc&tile=8,1&shiftColsSW=0&shiftRowsSW=2&shiftColsSE=1&shiftRowsSE=2&footside=-5,b-&headside=-c,5-&a2=-&h1=-&patchWidth=4&patchHeight=6&droste2=b10=c10=g10=rclc,b11=c11=g11=ctc,b12=c12=g12=ctc,b13=c13=g13=crcl,b20=c20=g20=lcrc,b21=c21=g21=ctc,b22=c22=g22=ctc,b23=c23=g23=clcr&droste3=ctc,b133=b233=c133=c233=g133=33=g233=ctcttctc#)

Recipes
-------

See also [tweak recipces](../#recipes-for-the-mixer) for more variations.

**Under construction**  
With two droste steps, we should not need a leading dash
for an odd number of stitches to make it an even number.
The dash (meaning: skip a stitch) is an accidental feature
and can cause problems outside the mixer. 

| **3-pair thread diagram** | **recipe of the diagram**                     | **flipped recipe**            |
|---------------------------|:----------------------------------------------|:------------------------------|
| ![](123-a.png)            | rcrcrc <br> crc,crclctc,ctcrc,rcl,c,c         |                               |
| ![](123-b.png)            | lclclc <br> rcl,ctc,crcllc,crrclcr,ctc,cl     |                               |
| ![](132-a.png)            | rcrcrc <br> -,ctc,ctc,ctc,ctc,ctc             |                               |
| ![](312-a.png)            | lclc <br> tctc,rctcl,ctcl,ctct                |                               |
| ![](321-a.png)            | lclc <br> tc,rclcrc,clcrcl,ct                 | rcrc <br> tc,lcrclc,crclcr,ct |
| ![](321-b.png)            | rcrc <br> tcr,lctc,ctcr,lct                   |                               |
| ![](321-c.png)            | rcrc <br> tcl,lctc,ctcr,rct                   |                               |
| ![](321-d.png)            | rcrc <br> t,lctc,ctcr,ctct                    |                               |
| ![](126453-a.png)         | lclclc <br> -,c,ctctc,ctctc,ctctc,c           |                               |
| ![](153426-a.png)         | lclclc <br> t,rc,ctc,rclcr,ctcl,ct            |                               |
| ![](154326-a.png)         | lclc <br> t,rctc,ctctcl,ctct                  |                               |
| ![](156423-a.png)         | rcrcrc <br> -,cr,crcl,clcrclcr,rcrcl,c        |                               |
| ![](234561-a.png)         | lclclc <br> cr,crcl,clcr,crcl,clcr,c          |                               |
| ![](263451-a.png)         | rcrcrc <br> -,cr,crcl,clcr,crcl,cl            |                               |
| ![](321546-a.png)         | lclclc <br> -,cl,ctcl,crcrcr,rcr,c            |                               |
| ![](321654-a.png)         | lclclclc <br> -,lc,crc,clcrc,clcr,c,crc,cl    |                               |
| ![](321654-b.png)         | rcrcrc <br> -,cr,ctcr,clclc,lcl,c             |                               |
| ![](354612-a.png)         | rcrcrc <br> ctct,ct,ct,ct,cl,ctc              |                               |
| ![](426153-a.png)         | rcrc <br> lc,crclclc,crcrclc,cr               |                               |
| ![](426153-b.png)         | rcrcrc <br> cr,ctcl,ctcr,ctcl,ctc,c           |                               |
| ![](456123-a.png)         | rcrc <br> r,lrc,ctcr,lct                      |                               |
| ![](456123-b.png)         | rcrcrcrc <br> c,ctc,rclc,ctc,rc,rcl,ctc,c     |                               |
| ![](462513-a.png)         | lclc <br> rc,clcrc,clctc,rcl                  |                               |
| ![](564312-a.png)         | rcrc <br> lcrc,clcrc,clcrc,clcr               |                               |
| ![](563412-a.png)         | rcrcrc <br> -,c,ctctc,clcr,rctc,c             |                               |
| ![](623451-a.png)         | lclclclc <br> r,c,crc,ctc,lcrcl,ctc,crc,cl    |                               |
| ![](623541-a.png)         | lclclc <br> -,ctc,ct,crc,ctc,ctc              |                               |
| ![](623541-b.png)         | rcrcrc <br> -,cl,ctctcr,ct,ctc,c              |                               |
