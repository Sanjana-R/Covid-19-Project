src -- has the wrappers required to use the models or functionalities
models -- holds the trained models
pipeline_ui -- hold the GUI for data_pipeline
figures -- output directory
data -- input directory and may hold raw/processed/interim data

requirements.txt -- holds the packages to be installed to execute the pipeline
run.py -- program to call the UI


=============================================================================================================================================


**** Create miniconda environment(to enable single project based environment that doesn't mix up with other project environments) ****
Miniconda steps:
Install miniconda

Then do the following
======================

cd <drive_name>:

cd python

md <project_folder_name>

cd <project_folder_name>

conda create --prefix ./env pandas numpy matplotlib scikit-learn

To activate the environment
===========================

conda activate <dive_name>:\Python\<project_folder_name>\env

To install jupyter
==================

conda install jupyter

Test Jupyter
============

jupyter notebook


Testing existence of the packages that we installed.
====================================================
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import sklearn


To close the environment
========================
ctrl+c

To deactivate the project environment
=====================================
conda deactivate



=======================================================================================================================


**** To install requirements after pulling updated repo use->> pip isntall -r requirements.txt ****



**** Use google colaboratory for training for large datasets that requires lot of GPU ****
