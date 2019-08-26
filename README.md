# Self-Driving-Simulation


GOAL

The goal of the project was to train a Deep Learning to replicate the human steering behaviour while driving, thus being able to drive autonomously on a simulator provided by Simulator (Udacity). 
 - Use the simulator to collect data of good driving behaviour
 -  Design, train and validate a model that predicts a steering angle from image data
 -  Use the model to drive the vehicle autonomously around the first track in the simulator.
	

Language: Python

Environment: Keras With Theano (TensorFlow)

Optional : Anaconda Package (Recommended)

# I. Installation 
Anaconda Distribution -  Windows
https://www.anaconda.com/distribution/#download-section

Create a Python environment and automatically download the required Python packages.

> conda env create -f environment.yml 

#Self Driving Simulator diagram
 
![Main diagram](https://user-images.githubusercontent.com/53454881/63662526-be008500-c7f9-11e9-986a-06b1f7d68438.png)

Training set is constituted by 8036 samples. For each sample, two main information is provided:
- three frames from the frontal left and right camera respectively
- the corresponding steering direction



# Python Code description

model.py: model definition and training

model.h5 (a trained Keras model) model weights

drive.py: interaction with the simulator (actually drive the car)

Environments.yml: conda environment (Use TensorFlow without GPU)

utils.py: The script to provide useful functionalities (image pre-processing and augmentation)

CNN algoritm 
![Create model CNN](https://user-images.githubusercontent.com/53454881/63662618-15065a00-c7fa-11e9-96e7-8bb4a5ba3996.png)

Diagram of Self Driving car drive model 
![Model Drive](https://user-images.githubusercontent.com/53454881/63662621-18014a80-c7fa-11e9-8c1e-5c8c8ad4fff0.png)



# Precompiled builds of the simulator
Instructions: Download the zip file, extract it and run the executable file.


