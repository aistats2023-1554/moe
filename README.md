Code to reproduce results in paper 8604, AAAI 2023
=======================================================================================================

REQUIREMENTS
------------

1. ``Python 3.9`` 
2. ``Pytorch 1.11.0, optionally with Cuda 10.1`` 
3. Linux Operating System. It has been tested on Ubuntu and MacOS. 
4. Additional modules listed in ``requirements.txt``

INSTALLATION 
------------

In order to install the code locally please follow the steps below:

1. Clone this repository and go to the cloned directory.

2. Set the environment variable to point to your python executable:

   `export PYTHON=<path to python 3.9 executable>`

3. Run the following command to set up the environment:

   `make` on **Mac**
   `make -f Makefile.linux` on **Linux**

4. Uncompress the pre-trained models:

   `cd models/pre_trained`
   `tar -xvzf pre_trained_models.tar.gz`

RUNNING JUPYTER NOTEBOOK for EXPERIMENTS
------------------------

1. Run the following script to start jupyter: 

   `./bin/run_notebooks.sh`

2. In the jupyter lab go to the notebooks folder which contains all the relevant notebooks 

3. Select the mnn kernel if not already selected.

4. You should now be able to run the notebooks.


