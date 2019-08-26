# Self-Driving-Simulation
Description

GOAL

The goal of the project was to train a Deep Learning to replicate the human steering behaviour while driving, thus being able to drive autonomously on a simulator provided by Simulator (Udacity). 
 - Use the simulator to collect data of good driving behaviour
 -  Design, train and validate a model that predicts a steering angle from image data
 -  Use the model to drive the vehicle autonomously around the first track in the simulator.
	

Language: Python

Environment: Keras With Theano (TensorFlow)

Optional : Anaconda Package (Recommended)

I. Installation 
Anaconda Distribution -  Windows
https://www.anaconda.com/distribution/#download-section

Create a Python environment and automatically download the required Python packages.

> conda env create -f environment.yml 

Structure 





Code descrition

model.py: model definition and training

model.h5 (a trained Keras model) model weights

drive.py: interaction with the simulator (actually drive the car)

Environments.yml: conda environment (Use TensorFlow without GPU)

utils.py: The script to provide useful functionalities (image pre-processing and augmentation)



