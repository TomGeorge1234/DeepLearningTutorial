# Deep Learning Tutorial 

In this tutorial ([deeplearning.ipynb](deeplearning.ipynb)) we will get hands on building deep neural networks and training them via backproagation. Initially the goal is to **avoid autograd packages**, such as `pytorch` or `jax` at all costs. Coding a deep neural network by hand this will help us gain an understanding of the mathematics going on behind the scenes. At the end we will use `pytorch` to build a much deeper network and see how it performs. Here's the plan: 

Topics: 

0. **Set-up**: Generate some data for a neuroscience-inspired task our networks will try to learn
1. **Linear regression**: A simple model with an analytic solution. We'll use this as a comparison later on. 
2. **Deep Neural Networks (by hand)**: Derive the learning rules for a deep neural network with two hidden layers and code this by hand.
3. **Deep neural networks (by `pytorch`)**: Using an autograd package to show how these models can be scaled efficiently.

We recommend cloning and running on your local IDE (it isn't compute heavy and won't require GPUs), but you can also run remotely on Google colab here [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TomGeorge1234/DeepLearningTutorial/blob/main/deeplearning.ipynb).