[Contribute](https://github.com/d-bl/GroundForge#contribute-to-documentation)
to the family of repositories.

Pruned repository
-----------------

This repository has the help files previously part of the [GroundForge](https://github.com/d-bl/GroundForge)
repository.
Now the help pages and the code can each have their license.

The following script extracted the help pages. 
The original repository only removed the files but kept their history.

    rm -rf GroundForge-help
    git clone --no-hardlinks GroundForge GroundForge-help
    cd GroundForge-help
    git filter-branch -f --tree-filter "rm -rf README.md .travis.yml build.sbt pom.xml project src toJS.* *.md *.html docs/*.html docs/*.md API _config.yml docs/API docs/css docs/images docs/js docs/_includes/README.md *.js colorpicker *.png target patterns images js debugD3js-v4 move-nodes docs/thumbs docs/D3jsForces thumbs .github/PULL* .github/ISSUE* tl wiki* docs/help/TesseLace-Index.* docs/_includes/tesselaceSample.html docs/help/Whiting-index.md css" --prune-empty HEAD
    git reset --hard
    git gc --aggressive
    git prune
 