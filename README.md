# Robotics Primer Tutorials
This repo holds a few robotics related primer tutorials. For code examples in jupyter notebooks, the code can be examined online (limited interactive) with nbviewer: 
`https://nbviewer.jupyter.org/github/armlabstanford/robotics_primer_tutorials/blob/master/**notebook**`

## Machine Learning Primer
This is a primer if you are brand-new to machine learning, you can play with the scripts online here:
https://nbviewer.jupyter.org/github/armlabstanford/robotics_primer_tutorials/blob/master/Machine_Learning_Primer.ipynb

Tutorial Author: [Prof. Monroe Kennedy](https://github.com/orgs/armlabstanford/people/mdkennedy3)

## Variational Auto-Encoder (VAE) Tutorial
This is a tutorial for the variational autoencoder. There are four examples. First, we learn a simple bivariate Gaussian distribution. Second, we learn a data distribution drawn from two separate bivariate Gaussians. Third, we learn to reconstruct data from the MNIST dataset. Fourth, we learn the MNIST dataset again but using the labels as conditioning variables. Along the way, I hope to highlight some relevant implementation details.
- You should be running this notebook with a Python 3 kernel. 
- You also need to make sure that whatever environment you're using has installed the dependencies in the imports section (numpy and torch). 
- There is no GPU support for this code, since it should comfortably run on your personal CPU, but note that any serious attempt at modeling large models using high-dimensional data will need to contend with device management.
- If you aren't familiar with PyTorch, I would encourage you to quickly go through the tutorial on their website: https://pytorch.org/tutorials/.

*Tutorial Author*: [Albert Li](https://github.com/orgs/armlabstanford/people/alberthli)

## Convolutional Neural Network Tutorial

This is a tutorial for *CNN, Siren(sinusoidal representation networks), and transfer learning*. There are three examples. 

* In the first example, we learn how to train and evaluate simple convolutional neural network with Mnist dataset. 

* Next, we learn the structure of Siren from the example. Siren is a network that leverages periodic activation functions for implicit neural representations. 

* Finally, we learn a simple example of transfer learning. We will classify small dataset with pretrained ResNet18 via transfer learning. 

To learn these example, you need to implement those code on [Google Colab](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb). First, download examples in google drive. Next, if you right click the notebooks, you will see the tab 'open with'. Click Google Colaboratory to execute the notebook. Next, to ensure fast learning, make sure that you have enabled the GPU under Edit -> Notebook Settings.

Please let me know if you have further questions!


Tutorial Author: [Won Kyung Do](https://github.com/orgs/armlabstanford/people/?query=wonkyung+do)


