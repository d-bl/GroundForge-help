---
layout: default
title: Use SVG to design a pattern
---

# Download pattern created with SVG-editor

Suppose the following scenario:

I down-loaded a diagram from GroundForge, want to adjust it but don't have the link to the pattern anymore. 
Can I skip some capture phases?

A possible step is filtering the tooltips out of the file with following unix command.

    egrep '[ctlr]+ - [^<]+' '/Users/jokep/Downloads/my problem(1)/3b2pair-diagram.svg'|sed 's!<.*!!'|sed 's!.*>!!'|sort|uniq>ids.txt

When one Droste level is involved, the resulting IDs will be some `xnm` where `xn` identify positions in the tile
and `m` identify a cross, left-twist or right-twist.
By drawing blobs around identical `xn` value you might be able to recognize the `ct` sequence.
When two Droste levels are involved there will be a third digit on the ID.
Then you will also have to draw blobs around identical `xnm` values. 
