This repository contains a [conda][conda] recipe for building
[ModRefiner][modrefiner], a tool for protein structure refinement.

This package does *not* include ModRefiner for dimers. This is because of
difficulties with the version of GSL. It is probably possible to fix this,
so please open an issue if you need this.

## Prerequisites

1. You will need an installation of [conda][miniconda].

2. Your root conda installation must have the `conda-build` installed.

## Building

You should be able to build this package by simply running `conda build .`.

Data files will be written to `$CONDA_PREFIX/share/modrefiner/data`.

[conda]: https://conda.io
[modrefiner]: https://zhanglab.ccmb.med.umich.edu/ModRefiner/
[miniconda]: https://conda.io/miniconda.html
