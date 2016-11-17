## light.py
light.py is a simple project that is intended to compute lighting for minecraft. It started as a port from a light.c file written by electromatter, and now is currently being optimized. 

# Usage
light.py is a standalone scipt that only requires imports from the stanard library and no installation. The work is done by the `light`, `scan_seed`, `fill`, and `probe` functions. This program is only mean to be used with python3, but everything except for the print statements work in python2.

This code currently is optimized to be run with pypy3. If there is a patch that no longer works with pypy3, it should be significant enough that the new code can preform better than the pypy3 version.

The `main` function generates a random set of light sources and htings that block light.

# Preformance
At the current time the code can run in pypy3 and is able to get around 25% of the preformance of the C code after the JIT warmup.

# Contributing
Patches that increase the preformance are very welcome, just make a pull request.
