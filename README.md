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

1. Install git-lfs with the following commands, if not already installed (NOTE: this is required only if you want to download all the pre-trained models. It is ~50GB!. Skip this step to train the models or use the few trained models provided):

     `sudo apt-get install git-lfs`

     `git lfs install`

2. Clone this repository and go to the cloned directory.

3. Set the environment variable to point to your python executable:

   `export PYTHON=<path to python 3.9 executable>`

4. Run the following command to set up the environment:

   `make` on **Mac**
   
   `make -f Makefile.linux` on **Linux**


RUNNING JUPYTER NOTEBOOK for EXPERIMENTS
------------------------

1. Run the following script to start jupyter: 

   `./bin/run_notebooks.sh`

2. In the jupyter lab go to the notebooks folder which contains all the relevant notebooks 

3. Select the mnn kernel if not already selected.

4. You should now be able to run the notebooks.

5. The performance metrics reported in the paper are in the `results` folder in '*final_results.csv'.

6. The folder `models\pre_trained` has some pre_trained models to generate the expert selection tables shown in the paper.




