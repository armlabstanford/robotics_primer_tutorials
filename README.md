# Robotics Primer Tutorials
This repo holds a few robotics related primer tutorials

## Machine Learning Primer
This is a primer if you are brand-new to machine learning, you can play with the scripts online here:
https://nbviewer.jupyter.org/github/armlabstanford/robotics_primer_tutorials/blob/master/Machine_Learning_Primer.ipynb

## Variational Auto-Encoder (VAE) Tutorial
This is a tutorial for the variatoinal autoencoder. We provide three examples. First, we learn a simple bivariate Gaussian distribution. Second, we learn a data distribution drawn from two separate bivariate Gaussians. Third, we learn to reconstruct data from the MNIST dataset. Along the way, I hope to highlight some relevant implementation details.
- You should be running this notebook with a Python 3 kernel. 
- You also need to make sure that whatever environment you're using has installed the dependencies in the imports section (numpy and torch). 
- There is no GPU support for this code, since it should comfortably run on your personal CPU, but note that any serious attempt at modeling large models using high-dimensional data will need to contend with device management.

