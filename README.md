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

To learn these example, you need to implement those code on [Google Colab](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb). First, download examples in google drive. Next, if you right click the notebooks, you will see the tab 'open with'. Click Google Colaboratory to execute the notebook. If Google Colaboratory is not installed yet, search 'colab' and install it. 

Please let me know if you have further questions!

Tutorial Author: [Won Kyung Do](https://github.com/orgs/armlabstanford/people/?query=wonkyung+do)

## Temporal Networks Tutorial
This is a tutorial for temporal networks (i.e. generative models for sequence prediction). There are 2 examples that can be run with Jupyter Notebook. Overall, both examples use an encoder-decoder structure to predict points in a sinusoidal waves, given some previous/training data points in that sine wave.
- In the first example (LSTM Autoencoder), a LSTM-based encoder encodes the input points into hidden states; a LSTM-based decoder and an output layer generates the predictions.
- In the second example (LSTM-CVAE), a LSTM-based encoder encodes the input points into a latent space distribution; conditioned by certain variables, a LSTM-based decoder and an output layer generates the predictions.

*Tutorial Authors*: [Eley Ng](https://github.com/eley-ng) and [Junwu Zhang](https://github.com/junwuzhang)

## Reinforcement Learning Tutorial 
This is a tutorial for Reinforcement Learning. There are two examples, which are run using Google Colab. Please refer to the Convolutional Neural Network section for details on downloading Google Colab and running code within the program.

* The first example is a tutorial on Q-learning and can be implemented in two different games. In both games, we train an agent to navigate through a discrete state space.

* The second example is a tutorial on DQN and is also implemented in two different games. In the first game, we train an agent to navigate through a discrete state space. In the second game, we train an agent to balance a cart pole in an upright position. Before running this example, **make sure that you have enabled GPU under Edit --> Notebook Settings.**

Tutorial Author: [Aliyah Smith](https://github.com/orgs/armlabstanford/people/aliyah-smith)

## Imitation Reinforcement Learning
This repo allows you to train an agent via imitation learning or reinforcement learning. The three more important files are flappybird1.py, flappybird2.py, and  DAgger.py. The tutorial was based on the following online tutorial: https://automaticaddison.com/play-flappy-bird-using-imitation-learning/ 

- Create a python3 virtual environment following this [tutorial](https://docs.python.org/3/tutorial/venv.html)
- Activate your environment each time you use this repo with the following command:
 ```
source (env_name)/bin/activate
 ```
- Follow the dependencies installations in https://automaticaddison.com/play-flappy-bird-using-imitation-learning/
- Run the following command: 
 ```
pip3 install -r requirements.txt 
 ```
- In the first file, we are simply running the flappybird interface. Run it using:
 ```
python3 flappybird1.py
 ```
- Second, the next file is quite similar to the first one, but the agent takes random actions. Run it:
 ```
python3 flappybird2.py 
 ```
- The third and last file named Dagger.py uses the imitation learning data aggregation algorithm refer to ARM RL presentation and this [link](https://automaticaddison.com/play-flappy-bird-using-imitation-learning/) to learn more about the algorithm. Dagger is used to train the agent on playing the game with expert demonstration.  The algorithm helps the agent memorize the expert actions in different states. Run the file and fix any dependency related errors:
 ```
python3 DAgger.py 
 ```

Note: Make sure you have enough RAM in your ubuntu machine as tensorflow requires a significant amount of RAM to run. I use 4 GB to run my VM. 

*Tutorial Author*: [Manuel Retana](https://github.com/MRNAS)




