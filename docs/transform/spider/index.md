---
layout: default
title: How to transform a spider
---

# How to transform a spider

## Introduction

![][snab3-00]
So, we have this fancy ground. We wish to define it in GroundForge to play with the stitches.   

This page shows you how you can do this. The procedure has three phases, each phase has several steps.
<p style="clear: both"></p>

## Phase 1: Prepare your pattern

### Step 1.1

![][snab3-01]
Start with a pairs-diagram drawing of the ground you wish to use (a "technical" drawing).
<p style="clear: both"></p>

### Step 1.2

![][snab3-02]
In the drawing of the ground, replace all  

- "stitch-pin-stitch" with "stitch";
- plaits with "stitch";
- tallies with "stitch".

Please note: GroundForge does not support sewings. If your ground has them, please see if they can be replaced with a regular stitch. This includes sewn-in beads.
<p style="clear: both"></p>


### Step 1.3

![][snab3-03]
Straigthen curved lines and put the figure on a square grid.
<p style="clear: both"></p>

### Step 1.4

![][snab3-04a]
Adjust pattern:

- make sure all stitches (where two lines connect) are in the middle of a square on the grid;
- use only allowed "connecting" lines (horizontal, vertical down, diagonal down);
- make sure that stitches have two lines comming in and two lines going out.
<p style="clear: both"></p>

![][snab3-04b]
Allowed connections between the middles:    

In each square there are: 

- 0 incoming and outgoing lines, or
- 1 incoming and 1 outgoing line, or
- 2 incoming and 2 outgoing lines
<p style="clear: both"></p>

Please note:

- There can be other solutions.
- Arrows are not drawn.
- We have put the stitches in the middle of the squares. If it is easier for you to place the stitches on e.g. the upper left corner, that is of course oké.

### Step 1.5

![][snab3-05]
Check if the adjusted pattern still repeats.
<p style="clear: both"></p>

### Step 1.6

![][snab3-06]
Draw a rectangle around a repeating area, here indicated in <span style="color:blue">blue</span>.    
The rectangle with contents is called a “tile”. 

Please note:

- There are several possible solutions. 
- The tile does not have to be the smallest one. 
- Holes between the tiles are allowed. 
- Tiles may overlap, but this is not recommended.

<p style="clear: both"></p>

You now are ready to define your pattern in GroundForge.

## Phase 2: define pattern in Groundforge

### Step 2.1

![][snab3-07a]
Go to the [_page Patterns_](/GroundForge/pattern.html) and fill in the __pattern-definition__, translating the squares of your grid to GF-numbers and letters. 
You have to type the characters in. You can ignore the half-circles that appear in the first collumn.
<p style="clear: both"></p>

![][snab3-07b]
<p style="clear: both"></p>

### Step 2.2

![][snab3-08]
You have to tell GroundForge how the pattern repeats. GroundForge uses two parameters for the __tile-layout__.    
Some lay-outs are predefined: click on one of these. The parameters will be filled in for you. 

Please note: This pattern is quite straightforward, as the "bricks" are neatly placed. There are examples that are more complicated. 
<p style="clear: both"></p>

___Here is how this works___:  

Look at your tiles and select one: the <span style="color:blue">blue</span> box in the picture. 
This tile has the upper left corner on postition <span style="color:blue">(0,0)</span>. Indicated with a <span style="color:blue">blue</span> dot.   

First, tell GF where the south-east diagonal of the pattern is, indicated in <span style="color:purple">purple</span>. 
Count how many squares to the right and how many down you have to step from the <span style="color:blue">blue</span> to the <span style="color:purple">purple</span> dot. 
You will find that the <span style="color:purple">purple</span> dot is on position <span style="color:purple">(4,3)</span>. 
We now know how to build the <span style="color:purple">purple</span> diagonal.    

Next, find where the next diagonal on the __left__ side is. Indicated in <span style="color:green">green</span>. Counting to the left gives negative numbers. 
The <span style="color:green">green</span> dot is on position <span style="color:green">(-4,3)</span>.     

These values go in the sections with the <span style="color:green">green</span> and <span style="color:purple">purple</span> border on page Patterns.   
Note: <span style="color:green">green: (0,6)</span> also works, however, we recommend selecting the green dot in south-west direction.

### Step 2.3 

Check in the “pattern”-panel if your definition is correct  You can ignore the half-circles that appear in the first collumn. 
If you see half-circles in an other than the first collumn, there is a problem with your definition.

### Step 2.4

Adjust the pattern size by filling in columns and rows in the “swatch size”-panel.   

The definition-phase is now finished.

## Phase 3: Fill in stitches

### Step 3.1

You can now click on the blue underlined “stitches and threads” to go to page Stitches to see what you have created and play with your ground.  

[the spider][t-snab3]


[snab3-00]: SNAB3-00.svg?align=left
[snab3-01]: SNAB3-01.svg?align=right
[snab3-02]: SNAB3-02.svg?align=right
[snab3-03]: SNAB3-03.svg?align=right
[snab3-04a]: SNAB3-04a.svg?align=right
[snab3-04b]: SNAB3-04b.svg?align=right
[snab3-05]: SNAB3-05.svg?align=right
[snab3-06]: SNAB3-06.svg?align=right
[snab3-07a]: SNAB3-07a.svg?align=right
[snab3-07b]: SNAB3-07b.svg?align=left
[snab3-08]: SNAB3-08.svg?align=right

[t-snab3]: /GroundForge/stitches.html?patchWidth=24&patchHeight=24&tile=8-4-,x5-5,4-5-,7-15,-5x-,5-73&shiftColsSW=-4&shiftRowsSW=3&shiftColsSE=4&shiftRowsSE=3&c1=ctc&a1=ctc&d2=ctctc&b2=rrctctcrr&c3=ctc&a3=ctc&d4=ctc&c4=ctc&a4=ctc&b5=llctctcll&d6=ctc&c6=ctc&a6=ctc

