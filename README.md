# Final-Project

Author: Emmanuel Amekudzi.

### My end of term project for 454

### Project Goal: 
Explore the significance of magnetic characteristics in geological and environmental contexts by developing an overview of the geophysical inversion of magnetic susceptibility data. Through exploring the fundamentals, strategies, and uses of inversion technique, we may unlock the abundance of data hidden beneath the surface of the Earth and advance our knowledge of the dynamic processes sculpting it.

### Project Objectives

The main objective of this process is to:
1.	Estimating a model for predicting data TMI data
2.	outline a suitable misfit by comparing data from the field survey to the predicted data.
3.	Produce an optimal model by constraining the infinite number of solutions to information that are already known.

### Today's Goal
For today we will work on the first part of our project objectives. This will include:
1. Creating a synthetic magnetic susceptibility data
2. creating a function and a model to predict TMI data and then
3. creating a forward simulation of a TMI data.

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

    conda env create --file=environment.yml
    conda activate my_magsusinv

 ### Documentation 
A Step by step guideline is provided in codes that is provided in this repository. Incase you want to know more about SimPEG you can visit the link below

https://docs.simpeg.xyz/content/user_guide.html

