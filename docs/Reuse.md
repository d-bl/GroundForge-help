---
layout: default
title: Share
---

{% include toc.md %}


Reuse on 3rd party pages
========================

Third party webmasters can reuse smaller or larger portions of the GroundForge website.
The following suggestions assume a proficient knowledge of html.
Option 2 and 3 even require the possibility to deploy your own custom JavaScripts,
and knowledge how to write them.

### 1. Just a link
The most simple option is a screen shot snippet, description or name of a specific pattern 
(or your own diagram) and the corresponding link.
Remember to use the ![link](/GroundForge/images/link.png) button before you 
copy-paste the address of a specific pattern.

### 2. Convenience forms
A convenience form can create a dynamic link to a base pattern.
Thus visitors can make variations on a family of patterns by choosing stitches or other properties.
Known examples:
* [valenciennes] used on the [Whiting-Index]
* [wobble.html] used on [MAE-gf/droste]

[MAE-gf/droste]: /MAE-gf/docs/droste#wobble
[wobble.html]: https://github.com/MAETempels/MAE-gf/blob/master/_includes/wobble.html
[valenciennes]: https://github.com/d-bl/gw-lace-to-gf/blob/master/docs/_includes/val-variants.html
[Whiting-Index]: /gw-lace-to-gf#val
[woble.html]: https://github.com/MAETempels/MAE-gf/blob/master/_includes/wobble.html

### 3. Embedded diagrams
You can even embed one or more of the dynamic diagrams on your pages.
The [API](/GroundForge/API) explanation should get you started.

Batch or server side
====================
A Java library is also available for batch processing or server side processing.
This library provides the same classes as called form the `load` function in the JavaScript. 
The `jar` file is available between the assets of the [latest release],
it might be behind on the API web page.
Sadly no known java equivalent for the force graphs of the D3js library called in the `showGraph` function. 
Without applying force graphs, the thread diagrams are of no use
and after all generating thread diagrams from pair diagram is the core of GroundForge.

[latest release]: https://github.com/d-bl/GroundForge/releases/latest
[number]: https://github.com/d-bl/GroundForge/commits/master/docs/js/GroundForge-opt.js
[docs/API]: https://github.com/d-bl/GroundForge/tree/master/docs/API
[API page]: /GroundForge/API
