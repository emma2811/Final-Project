# Final-Project

## Topic
#### INVERSION OF TOTAL MAGNETIC INTENSITY (TMI) DATA: AN APPLICATION FOR MINERAL EXPLORATION 

Author: Emmanuel Amekudzi.

### My end of term project for 454

### Project Goal: 
The goal of this project is to use some traditional approaches which will include:
1.	The introduction of an appropriate weighting function which counteracts the field decay by formulating an inverse problem as an iteratively re-weighted least-squares (IRLS) optimization problem and 
2.	using Tikhonov regularization to introduces a quadratic penalty related to the solution norm, which can help stabilize the solution and reduce ambiguity, stabilize the solution and improve its accuracy by restricting it to a subspace of models with specific characteristics


### Project Objectives

The main objective of this process is to:
1.	1.	Create a model for predicting TMI magnetic data
2.	Inverse the data obtained to generate a magnetic susceptibility model of the subsurface.

### Step to help achieve our goals
To help achieve our goals and abjectives, our main focus will include:
1. Creating a synthetic magnetic data
2. creating a function and a model to predict susceptibility data
3. creating a forward simulation of a data and then
4. inverting the data obtained to get a subsurface susceptibility model.

### Software Installation
For the purpose of this project, we will be working in SimPEG.

 I assume, that you already have conda set up and running. please clone or download this repository to get started.

 #### Installation of SimPEG

 Guidelines on the installation of SimPEG can be found in the SimPEG Documentation using the link below.

 https://docs.simpeg.xyz/

 #### Packages needed
 Numpy
 Scipy
 Matplotlib
 Matplotlib.pyplot
 Discretize
 Discrtize.utils
 SimPEG.utils
 SimPEG.potential_fields

 ### Conda Environment
 incase you don't have all of this installed, a .yml environment file attached to this repository. I provide a conda environment with all needed dependencies for this tutorial.
 Just create and activate it with:

    conda env create --file environment.yml
    conda activate my_environment

 ### Documentation 
A Step by step guideline is provided in codes that is provided in this repository. Incase you want to know more about SimPEG you can visit the link below

https://docs.simpeg.xyz/content/user_guide.html


