# msrresearch Documentation

This is a documentation of code produced by msrresearch. You can find it online at [https://msrresearch.github.io/documentation/build/html/index.html](https://msrresearch.github.io/documentation/build/html/index.html).

## Cloning

Since this repository uses submodules to import the code to be documentated, just cloning the repository won't do. You either have to clone the repository and then initiate the submodules:

```
git clone git@github.com:msrresearch/documentation.git
git submodule init
git submodule update
```
or clone the repository recursively:
```
git clone --recursive git@github.com:msrresearch/documentation.git
```
