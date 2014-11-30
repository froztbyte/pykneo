pykneo
======

The purpose of this project started as extracting libykneo from the code at [Yubico/yubioath-desktop](https://github.com/Yubico/yubioath-desktop) and attempt to make it into a mildly reusable set of code, but I found that there's too much baggage there. Now I think I'll roughly aim for a standalone implementation myself.

Motivation
----------

I couldn't find anything that'll allow me generalized access to the Yubikey NEO, so I set out to start with it myself.

Requirements
------------

 * pyscard
 * swig

Notes
-----

The pypi release of `pyscard` does not appear to build cleanly on OSX Yosemite. I found [this post](http://ludovicrousseau.blogspot.com/2014/07/pyscard-unofficial-version-1616.html) which provides a tarball that does appear to build on OSX Yosemite.

On Yosemite I installed `swig` from homebrew (before I could build `pyscard`).

Licensing
---------

See the `LICENSE` file for info.
