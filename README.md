# ndf_reader
A pure-python module for reading .ndf binary files (open source instruments http://www.opensourceinstruments.com/).

This is the ndf converter from the pyecog repository, https://github.com/jcornford/pyecog, which is aimed at detection of seizures. 
## dependencies:
- numpy 
- scipy
- pandas
- h5py (for saving the files)

## installation:
can be installed via pip (not yet!) or 

## Issues/areas to contribute:
- glitch detection is weakest bit, hacky and currently relies on bindings between variables. 
- set up some tests
- bad messages within expected timewindow should both be deleted, currently ignoring this possibility
- can always be made faster...!
- only tested with python 3 
