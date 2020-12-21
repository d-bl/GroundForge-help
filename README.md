[Contribute](https://github.com/d-bl/GroundForge#contribute-to-documentation)
to the family of repositories.

License
-------

The code repository has a [GPL-v3](https://github.com/d-bl/GroundForge/blob/master/LICENSE)
license. The repositories with help pages and examples have a 
[CC-BY](http://creativecommons.org/licenses/by/4.0/) license. 
See [details](https://github.com/d-bl/GroundForge#licenses)
for diagrams you made with GroundForge: in short, what you made is yours.

Pruned repository
-----------------

This repository has the help files previously part of the [GroundForge](https://github.com/d-bl/GroundForge)
repository.
Separating help pages from the code allows more appropriate licenses.

The original repository keeps the original history of the pages in its context.
The following script extracted the help pages. 

    rm -rf GroundForge-help
    git clone --no-hardlinks GroundForge GroundForge-help
    cd GroundForge-help
    git filter-branch -f --tree-filter "rm -rf README.md .travis.yml build.sbt pom.xml project src toJS.* *.md *.html docs/*.html docs/*.md API _config.yml docs/API docs/css docs/images docs/js docs/_includes/README.md *.js colorpicker *.png target patterns images js debugD3js-v4 move-nodes docs/thumbs docs/D3jsForces thumbs .github/PULL* .github/ISSUE* tl wiki* docs/help/TesseLace-Index.* docs/_includes/tesselaceSample.html docs/help/Whiting-index.md css" --prune-empty HEAD
    git reset --hard
    git gc --aggressive
    git prune
 