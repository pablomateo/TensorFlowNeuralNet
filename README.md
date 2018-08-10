# TensorFlowNeuralNet
**Udacity - Artificial Intelligence Nanodegree Program**

AI - Intro to Tensor Flow

# Neural Network in TensorFlow

![ImageDataset](image/notmnist.png)

This project is part of **Udacity´s Artificial Intelligence Nanodegree Program**. Here you will find my personal solution to the challenge. The following project can be run using a Local Machine or using an external GPU (Solution provided by **Amazon Web Services** is recommended). Next, you can follow Udacitys instructions to install the necessary dependencies on a local machine or on AWS.

In this project, we train a **Neural Network** using **TensorFlow**.

Follow the instructions to install the required environment and check them both:

	(dlnd-tf-lab)$ jupyter notebook intro_to_tensorflow.ipynb
	
--------------------------------------------------------------------------------------------------------

### Instructions - Udacity Project

## Tensor Flow Lab

We've prepared a Jupyter notebook that will guide you through the process of creating a single layer neural network in TensorFlow. You'll implement data normalization, then build and train the network with TensorFlow.

## Getting the Notebook
The notebook and all related files are available from this GitHub repository. Either clone the repository or download it as a Zip file.

Use Git to clone the repository.

    $ git clone github.com/pablomateo/TensorFlowNeuralNet.git
    
If you download the Zip file, be sure to extract it (usually just double clicking). The most recent versions of all the code will be available from the repository, so it's the best place to get up-to-date files.

Once you have the repo cloned or downloaded, change directories into the repo. In there you'll find the lab notebook, as well as Conda environment files for installing all the necessary packages.

### Windows Instructions
We've provided a Conda environment file for you to easily install all the necessary packages. In the **TensorFlowNeuralNet directory**, enter:

    $ conda env create -f environment_win.yml
    
This will create an environment called dlnd-tf-lab. You can enter the environment with the command:

    $ activate dlnd-tf-lab
    
All the necessary packages should be installed for you.

### OS X and Linux Instructions

We've provided a Conda environment file for you to easily install all the necessary packages. In the intro-to-tensorflow directory, enter:

	$ conda env create -f environment.yml

This will create an environment called dlnd-tf-lab. You can enter the environment with the command

	$ source activate dlnd-tf-lab
	
All the necessary packages should be installed for you.

### View The Notebook
In the directory with the notebook file, start your Jupyter notebook server

	jupyter notebook intro_to_tensorflow.ipynb

This should open a browser window for you. If it doesn't, go to [http://localhost:8888/tree](http://localhost:8888/tree). Although, the port number might be different if you have other notebook servers running, so try 8889 instead of 8888 if you can't find the right server.

You should see the notebook intro_to_tensorflow.ipynb, this is the notebook you'll be working on. The notebook has 3 problems for you to solve:

***Problem 1:*** Normalize the features.  
***Problem 2:*** Use TensorFlow operations to create features, labels, weight, and biases tensors.  
***Problem 3:*** Tune the learning rate, number of steps, and batch size for the best accuracy.  
This is a self-assessed lab. Compare your answers to the solutions here. If you have any difficulty completing the lab, Udacity provides a few services to answer any questions you might have.
