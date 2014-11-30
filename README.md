py-libykneo
===========

The purpose of this project is to extract libykneo from the code at [Yubico/yubioath-desktop](https://github.com/Yubico/yubioath-desktop) and attempt to make it into a mildly reusable set of code.

Motivation
----------

I couldn't find any references to this library being usable as a standalone thing to start with.

Requirements
------------

 * pyscard
 * swig

Notes
-----

The pypi release of `pyscard` does not appear to build cleanly on OSX Yosemite. I found [this post](http://ludovicrousseau.blogspot.com/2014/07/pyscard-unofficial-version-1616.html) which provides a tarball that does appear to build on OSX Yosemite.

I installed `swig` from homebrew.
