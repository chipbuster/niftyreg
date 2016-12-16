CVC NiftyReg Fork
======================

This is a fork of [NiftyReg from UCL](http://cmictig.cs.ucl.ac.uk/wiki/index.php/NiftyReg)
ntended for use with the Skull Atlas Project. It is mostly intended as a 
usable submodule repository for the main project where we can add several
tweaks to coax it to build on CVC systems.

The original README of this project is viewable in `README.txt`

NOTE: On newer systems, compilation needs to be done with GCC 5 or 
older, since nvcc does not support newer GCCs. Clang 3.9 is not
supported, but I don't know what the maximum version is for it.
