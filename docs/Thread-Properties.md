---
layout: default
title: Thread properties
---

Toggle thread colors
====================
You may have to scroll/drag the thread diagram (or increase the panel size)
to make the squares at the start or bobbins ate the end of the threads visible.  
![](images/toggle-thread.png)
Click these squares or bobbins to browse through a few colors.
A tooltip shows a thread number when your mouse hovers over a square.  
![](images/toggle-hover.png)  
Too tiny squares or too close together? Use the zoom function of your browser.
Usually control-shift-plus to zoom in, control-zero to reset,
on a mac use command for control.

More thread colors and/or widths
================================
The print/PDF friendly page allows you to choose any color you like.
Downloaded a diagram and a vector capable editor (SVG) allows even other thread properties such as width. 

When 4 variants is enough: your SVG editor might allow to select all threads
with one of the predefined colors and subsequently change them.

Grouping thread segments simplifies the procedure to apply more thread colors and widths.
The feature did not mary well with the Droste patterns and is only available for laptops and desktops:
* [download](https://github.com/d-bl/GroundForge/archive/thread-props.zip) and unzip
* select/tweak your pattern on the [web site](/GroundForge/tiles)
* click ![](/GroundForge/images/link.png)
* in the address bar of your browser
  * replace `https://github.com/d-bl/tiles.html` (as far as there is a `.html`)
  * with `file:///PATH/TO/UNZIPPED/GroundForge-thread-props/docs/tiles.html`
* click ![](/GroundForge/images/download.jpg)
* open the download with a [tool of your choice](Reshape-Patterns#evaluated-editors)

The next procedure may vary between the tools.
* Select the diagram.
* Ungroup it (this main group serves a proper scale on the web page but is annoying when editing)
* Select a thread.
* Change the properties of the paths in the group.


Simplify editing
================

Each thread is a group of paths. This might cause elaborate editing.

* Select all paths in a group composing a thread.
* Combine the paths into a single one.
* The group now contains a single object: ungroup.

Smooth bends
============

InkScape has a plugin to combine the nodes of adjacent path segments.
This prepares to make the sharp bends smooth.

To install:
* on a Mac: InkScape -> preferences -> system -> user extensions -> open  
  other systems: File -> preferences -> system -> user extensions -> open
* Download two files into this folder:
  [chain_paths.py](https://raw.githubusercontent.com/fablabnbg/inkscape-chain-paths/master/chain_paths.py)
  and
  [chain_paths.inx](https://raw.githubusercontent.com/fablabnbg/inkscape-chain-paths/master/chain_paths.inx)
* Restart InkScape

To apply
* Select all threads (after _simplify editing_)
* menu on all systems: extensions -> modify path -> chain paths
* set the max. distance to something like 0.01
* apply button

Finally, use the built in tools bar:
* Join selected nodes.
* Make selected nodes smooth.
