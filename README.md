Geobook - an open sandbox
===============================

This Notebook and included sample data is intented to be used via
**mybinder.org** as a fast, simple sandbox environment for exploring the
Jupyter Notebook interface. Commonly-used geospatial and data science Python
libraries are included. 

Requirements
--------------

This repo is optimized for use within a **mybinder.org** environment, and
assumes a Python 3 kernel is available. 

Installation
-------------

Requires Python 3. To install Python dependencies _(for local
development, a virtualenv is strongly recommended)_:

    $ pip install -r requirements.txt

Running Locally
----------------

If using mybinder, there's no need to run a Jupyter server directly. For
local development, however, it can be useful to run Jupyter from within a 
project virtualenv.

To set up the kernel with virtualenv packages, run the following within the
virtualenv:

    (venv) $ python -m ipykernel install --user --name <venv name>
    

After that, start Jupyter:
    
    $ jupyter notebook

From within the Notebook interface, change the kernel (`Kernel --> Change
Kernel --> <name of venv>`) to use the newly created project kernel.
