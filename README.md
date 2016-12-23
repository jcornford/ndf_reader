# ndf_reader
pure-python module for reading .ndf open source instruments files

http://www.opensourceinstruments.com/

# dependencies:
- numpy 
- h5py
- scipy
- pandas

# installation:
can be installed via pip (not yet!) or 

# Issues/areas to contribute:
- glitch detection is weakest bit, hacky and currently relies on bindings between variables. 
- set up some tests
- bad messages within expected timewindow should both be deleted, currently ignoring this possibility
- can always be made faster...!
