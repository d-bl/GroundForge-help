---
layout: default
title: Modify stitches
---

Ignore/restore stitches
=======================

![](images/legend-and-ids.png)

How to modify stitches is explained in the getting started [tutorial](index#modify-stitches).
A more advanced subject is skipping/ignoring stitches and restore them.

Ignore stitches
-------------
To remove a stitch from the pair diagram, you can use `-` (a single dash and no other symbols) for the stitch.
If you delete all the text from a stitch field, the default value is used.  
The default stitch is `ctc`.

_Warning_: ignored stitches may cause weird thread diagrams
in which the pairs swap before a stitch is made.

Restore stitches
-------------
An explanation of a versatile [Binche](Binche) pattern still uses the old old method explained as stitches.
That method no longer.
When the address bars has `GroundForge/tile` please replace it to `GroundForge/stitches`.
Then you get subsection of a page with a button to restore ignored stitches.

Reconnected stitches
--------------------
When stitches are ignored, the algorithm has to reconnect the involved pairs with the adjacent stitches.

The green annotations in the screen shot below show how the remaining stitches reconnect in the pair diagram after an ignored stitch.
One case is straight forward. In the other case, because the GroundForge pair diagram treats stitch-pin-stitch as a single stitch, the stitches are merged two by two.

The ![animate](/GroundForge/images/animate.png) button simulates what the pattern looks like when the connections between stitches act like springs.
The same spring behaviour is used to create the thread diagrams.  Applying the animate button creates a pair diagram that can be used as a pricking for the thread diagram. 

You can [try](/GroundForge/tiles?patchWidth=12&patchHeight=13&g1=ctct&e1=ctct&c1=ctct&a1=ctct&f2=ctct&b2=-&g3=ctct&e3=ctct&c3=ctct&a3=ctct&h4=ctct&f4=-&d4=ctct&b4=ctct&g5=ctct&e5=ctct&c5=ctct&a5=ctct&f6=ctct&b6=ctct&g7=ctct&e7=ctct&c7=ctct&a7=ctct&h8=ctct&f8=ctct&d8=ctct&b8=ctct&tile=5-5-5-5-,-5---5--,B-C-B-C-,-5-5-5-5,5-5-5-5-,-5---5--,B-C-B-C-,-5-5-5-5,&footsideStitch=tctct&tileStitch=ctct&headsideStitch=tctct&shiftColsSW=0&shiftRowsSW=8&shiftColsSE=8&shiftRowsSE=8)
variations.

![](images/ignore-stitches.png)

