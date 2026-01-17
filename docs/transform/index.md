---
layout: default
title: Transformations
---

Picking a pattern from a [gallery](/) and [changing stitches](/GroundForge-help/index#modify-stitches)
is the easiest way to start experiment with grounds.
For some more background and to help recognize patterns, this page shows how patterns are transformed.

![](gms-3086.png?align=left) In [literature](/MAE-gf/docs/literature), you may find patterns like
3086 of “Gründe mit System” by Uta Ulrich, similar to F4 (though no corner pins are used) in the gallery
created from the sampler of mrs Whiting. Please click the wand for the thread diagram of [F4].
See also the  [MAE-gf](/MAE-gf/docs/bias#bias-ground-crossed-rose-style) gallery.
<p style="clear: both"></p>

[F4]: /GroundForge/stitches?whiting=F4_P180&patchWidth=9&patchHeight=9&d1=ctc&c1=ctc&b1=ctc&a1=ctc&d2=ctc&c2=ctcllctc&a2=ctcrrctc&tile=1483,8-48&footsideStitch=ctctt&tileStitch=ctc&headsideStitch=ctctt&shiftColsSW=-2&shiftRowsSW=2&shiftColsSE=2&shiftRowsSE=2

![](plaits.png?align=left) GroundForge does not know how to draw pins, so stitch-pin-stitch becomes a kind of short plait.
Hence, the first transformation step is drawing straight lines from pin to pin.
<p style="clear: both"></p>

![](snap.png?align=left) GroundForge also wants stitches at grid positions. So we move some intersections to the nearest grid position.
<p style="clear: both"></p>

![](squeeze.png?align=left) An optional step is to squeeze the pattern to make it more compact.
<p style="clear: both"></p>

![](encoded.png?align=left) Then, we can [encode](/GroundForge-help/Advanced) the pattern in GroundForge and [assign stitches](/GroundForge-help/index#modify-stitches).
In this case cloth stitches and winkie pins: cloth stitch, twist one pair around a pin, cloth stitc.
Remember that GroundForge does not draw pins and treats the winkie pin as a single stitch.
<p style="clear: both"></p>

![](thread.png?align=left) This thread diagram is the result.
<p style="clear: both"></p>

![img.png?align=left](droste.png?align=left) Another option is to interpret the pair diagram as thread diagram.
A single unit of the ground uses four pairs. So we need only one stitch of four threaads: _clcrct_.
Again: click the wand for the [thread digarm](/GroundForge/droste.html?patchWidth=7&patchHeight=8&footside=----,---b&tile=5-&headside=-,c&shiftColsSW=-1&shiftRowsSW=1&shiftColsSE=1&shiftRowsSE=1&e1=clcrct&l2=ctctt&d2=ctctt&droste2=e15=e16=ctc,e11=ctcllctc,e13=ctcrrctc,l21=llctcll,d22=rrctcrr,d20=d21=d23=d24=l20=l22=l23=l25=ttctctt,).
We call this approach the [droste](/GroundForge-help/Droste-effect) technique.
<p style="clear: both"></p>
