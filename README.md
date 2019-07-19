# BioImagePy Tutorial

This package contains python notebooks tutorials to learn using the BioImagePy
library. 

# Installation

To run BioImagePy tutorials you need to install python3 and jupyter notebooks
using pip or conda.

Then you need to install bioimagepy, the serpico package and finally the tutorials.

## Create the working directory 

```shell
mkdir bioimagepy
cd bioimagepy
```

## install bioimagepy

```shell
git clone https://gitlab.inria.fr/serpico/bioimagepy.git
```

## install serpico package

```shell
git clone https://gitlab.inria.fr/serpico/serpico-package.git
cd serpico-package
chmod u+x ./package.sh
./package.sh
cd ..
```

If the package script runs correctly you should have the directory `toolshed` 
with all the needed serpico tools and wrappers

## install tutorials

```shell
git clone https://gitlab.inria.fr/serpico/bioimagepy-tutorial.git
```