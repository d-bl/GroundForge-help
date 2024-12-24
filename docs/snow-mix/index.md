---
layout: default
title: mix snowflakes
---

Toc
===
* [Mix snowflakes into new Grounds](#mix-snowflakes-into-new-grounds)
  * [Recipes for the mixer](#recipes-for-the-mixer)
    * [Modify a given recipe](#modify-a-given-recipe)
    * [Even numbers of stitches](#even-numbers-of-stitches)
    * [Blob analysis](#blob-analysis)
    * [Try step by step](#try-step-by-step)
  * [Stitches for six pair snowflakes](#stitches-for-six-pair-snowflakes)
    * [Collapsed stitches](#collapsed-stitches)
    * [Footsides](#footsides)
  * [Save and recall a pattern](#save-and-recall-a-pattern)


Mix snowflakes into new Grounds
===============================

On the [snow mixer] you can create diagrams for (new) grounds with a mix of 2x2 snowflakes.

![sample](sample.png?align=left)
On the left a sample of lace by Babette.
She invented a double hexagonal ring pair around a snowflake.
The intersections of the double ring pairs are in fact compact snowflakes.
This inspired to explore a mix of snowflakes in general.

The pair diagram of a 6-pair snowflake can be interpreted
as a thread diagram of a 3-pair connection.
Each 3-pair connection can be composed with a group of 2-pair stitches.
The mixer starts with the last step as building blocks alias recipes for a combination of 2x2 snowflakes.


[snow mixer]: /GroundForge/mix4snow/

Recipes for the mixer
---------------------

The [snow mixer] shows a few recipes with thumbnails.
This is just a start as a collection with recipes can barely scratch the surface of the possibilities.
In [counting snow families](https://d-bl.github.io/MAE-gf/docs/counting-snow/)
we have 230 families for the type of snowflakes for the mixer.
About half of the _B3_ samples in [Viele gute Gründe](/MAE-gf/docs/literature)
are members of only 2 families and need only 17 recipes.
We have a few more [recipes](/MAE-gf/docs/snow-stitches/563412-145236.svg) beyond the thumbnails for only two families.

### Modify a given recipe

The following list of steps shows some hover actions.
A mobile device does not support hovering, it requires a little more trial and error without.
Click the blue hexagon again when you guessed wrong with removing the color.

Suppose we want to remove the center of a spider. 

* Click the spider below the form.
* Click the dark blue hexagon.
* Hover over the center of the spider as shown in figure (a).
* Hover over the stitches in the plait until you see the start of the id shown in figure (b).
* Click the stitch to check the color disappears from the desired stitch in the thread diagram.
* In this case we clicked the fourth stitch of the plait.
* Figure (a) adds a two to the id in figure b, as the application starts with zero that means the third action.
* The recipe was _lc,crc,ctc,lcrcl,ctc,crc,c,r_, the fourth stitch is _lcrcl_ as we saw on the tooltip.
  We have to remove the third action which is the _r_.
  Note that a _t_ counts as two actions: twist left plus twist right.

|    figure (a)    |    figure (b)    |      figure (c)       |
|:----------------:|:----------------:|:---------------------:|
| ![](show-id.png) | ![](decolor.png) | ![](white-stitch.png) |

### Even numbers of stitches

Note figure (c) above: the last "stitch" of the plait is white, the "stitch" is just a right twist.
To get an even number of stitches, we had to separate it from the preceding stitch which now is just a cross. 
For technical reasons the mixer template does not support odd numbers of stitches, see this [workaround].
The mixer can handle up to 10 stitches. That is an arbitrary but hard coded limit.

[workaround]: https://github.com/d-bl/GroundForge/blob/master/docs/_includes/mix4snow/README.md#odd-number-of-stitches

### Blob analysis

![](blobs.svg?align=left)

To start from scratch, we need to interpret a six-pair diagram as a thread diagram.
On the left an arbitrary example.

The stitches composing the three pair stitch are marked with blobs.
The blobs are numbered in working order.
The caption enumerates the stitches in working order, one per blob.
The R prefix means we start on the right.

It helps to trace the pair diagram with the proper alternating over-under effects of the threads.
Another color for each thread helps to recognize when to start a new stitch:
A stitch worked with the middle and right pair can't use the left pair and vice versa.

![](too-complicated-blobs.svg?align=right)
The too complicated example on the right illustrates requirements for the blobs:
* Span 4 threads.
* The threads flow two by two into adjacent blobs. For example red and orange flow from two to three and blue and purple from two to four.
  This can be deceptive: five may seem to receive black from one while it actually goes via three.
* Not all threads in a blob need to have an interaction with other threads.
  For example: the black and blue pairs in the third blob do nothing, like the green pair in the fifth.


### Try step by step

The double ring pair of the default pattern is a nice environment to explore or troubleshoot a new recipe.
The following table explains by example.

| recipe                                  | result                  |                                                          |
|:----------------------------------------|:------------------------|:---------------------------------------------------------|
| Right "r,t,t,l" <br> or: Left "l,t,t,r" | ![](simple-content.png) | Start simple with three pairs twisted twice              |
| crc,t,l,l (Right)                       | ![](step2.png)          | Start to feed the first thread on the right to the left. |
| crc,crc,l,l                             | ![](step3.png)          | Go all the way                                           |
| crc,crclc,r,r                           | ![](step4.png)          | Feed the originally first pair on the left to the right. |
| crc,crclcr,cr,r                         | ![](step5.png)          | Go all the way                                           |
|                                         |                         | Etcetera                                                 |

Stitches for six pair snowflakes
--------------------------------

The mixer generates thread diagrams for three pair stitches.
Using these thread diagram as a pair diagram,
allows to assign stitches for six pair snowflakes,
spiders or whatever needing six pairs.

![](default-pattern.png?align=right)

On the right you see the default pattern of the [snow mixer].

* Click the button _pairs from threads_ on the mixer page,
  and you will see the screenshot below with empty diagrams.
* Click the wands to generate the diagrams.
* [Play](/GroundForge-help/Icons)
  with the size of the panels and move the content as you see convenient.
* The mouse in the screenshot points to the stitch that is highlighted with green in the stitches panel.
* When you change the content of the stitches panel and go to this page,
  the diagrams are cleared to avoid confusion about inconsistencies.

See also the _show help links_ button of this _pairs from threads_ page.
 
When you changed the pattern on the snow mixer,
some stitches might have their ID changed, or they are no longer applicable at all.

![img_1.png](default-droste.png)

The twist marks in the pair diagram are not reliable.

### Collapsed stitches

We might encounter repeated actions in a stitch. Repeated twists are the most common.
The sample on the left below shows a repeated cross on both sides.
For GroundForge anything done with the same two pairs is a single stitch.
We see that below in the middle with the pair diagram created from the thread diagram.
We can counteract that effect with a _ctctttctc_ as shown on the right. 

![](double-cross.png) &nbsp; ![](un-doubled.png) &nbsp; ![](re-doubled.png)

![](footsides.png?align=right)

### Footsides

Footsides direct contrasting threads back into the ground in a specific order.
On the right a simplified pattern (blue) with two different footsides
each with their own consequences for the thread sequence.
The footsides are based on a _tct_ give or take a twist.
Following the link-button _tweak footsides_ in the mixer,
you can apply any other stitch, like _tcrct_, _tclct_ or _tctct_ to the footsides
before you go to the _pairs from threads_ page.
See the _show help links_ button on both pages.


Note that footside twists may [collapse](#collapsed-stitches) with ground twists or vice versa.

A passive more or less is not significant to control the thread flow,
but you might want half snowflakes that match the ground.
For that purpose, there is room for five more pairs using this [advanced] technique.

<!-- TODO develop recipes from simplified  -->
[simplified]: /GroundForge/droste?patchWidth=1?patchWidth=1&patchHeight=15&footside=4,x&tile=-,5&headside=7,x&shiftColsSW=0&shiftRowsSW=2&shiftColsSE=1&shiftRowsSE=2&c1=lctrr&a1=rctll&b2=ctc&droste2=c10=c11=c12=tctctct,c13=rrtctctct,a10=tctctctc,a11=ctctctc,a13=ctctct,a12=lllctctctctc#
[advanced]: /GroundForge-help/Advanced#footside-tutorial

Save and recall a pattern
-------------------------

The print function of your browser can save the diagrams [as PDF](/GroundForge-help/clips/print-as-pdf).
The document has a link back to the interactive page,  unless you opted for a selection in the print dialog.

When on a _pairs from thread_ page, make sure the stitches panel is big enough to accommodate all stitches.
Open the document in your browser, and you can copy the content of the stitches panel
in case the link in the document does not restore the content properly.
