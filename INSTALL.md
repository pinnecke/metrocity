# Installation

To install this theme, the theme definition file `source/beamerthememetrocity.sty` and required image assets in `source/metrocity` must be copied to your project directory, and `\usetheme{metrocity}` must be added to the preamble of your presentation. 

To get the latest stable version for your project, navigate to your projects root, and type
```
wget https://github.com/pinnecke/metrocity/archive/master.zip
unzip master.zip
rm master.zip
cp metrocity-master/source/* .
rm -rf metrocity-master
```
Afterwards, `beamerthememetrocity.sty` should be stored in and a new directory called `metrocity`, which holds image assets, should be added to your projects root directory. Then, open your TeX presentation, and add `\usetheme{metrocity}`.

