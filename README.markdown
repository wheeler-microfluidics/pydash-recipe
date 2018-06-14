**This recipe is no longer maintained since pydash is included on [conda-forge](https://anaconda.org/conda-forge/pydash).**

Conda recipe to build [`pydash`][1] package.

**Note** Windows build only.

Build
=====

Install `conda-build`:

    conda install conda-build

Build recipe:

    conda build .


Install
=======

The [Windows 32-bit build][2] may be installed from the
[`wheeler-microfluidics`][3] channel using:

    conda install -c wheeler-microfluidics pydash


[1]: https://github.com/dgilland/pydash
[2]: https://anaconda.org/wheeler-microfluidics/pydash
[3]: https://anaconda.org/wheeler-microfluidics
