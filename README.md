# PyTorch Guide

PyTorch is an open source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing, primarily developed by Facebook's AI Research lab. In this expo you will learn how to build a basic fully connected neural network. This is an excellent introduction to a difficult topic to understand. PyTorch was created to offer production optimizations similar to TensorFlow while making models easier to write.

### PyTorch compared to TensorFlow

- Better memory and optimization
- More sensible error messages
- Finer-grained control of model structure
- More transparent model behavior
- Better compatibility with NumPy

That means you can write highly customized neural network components directly in Python without having to use a lot of low-level functions.

### Important topics to understand before starting

Nueral networks are designed to mimic how a brain works. There are neurons in your brain that are either "On" or "Off". Neural networks use things activation functions to create these "On" or "Off" decisions. When the model gets to a decision output it is not cut and dry "This is a dog" or "This is a cat." It would be more like 80% sure it is a cat and 20% sure it is a dog, leading it to claim "This is a cat." To create a neural network you must first train it to understand the data and what desired output you want. Data splitting is essential in this process so you do not overfit the model. 

A model is trained by passing batches of input through the network created to begin to teach it. This "pass" is through the hidden layer of the network is where the program is assigning weights to each variable in the input. These weights determine how much emphasis should be applied to each given input. For example color would have a certain amount weight in determining if a picture of a fruit was a banana or an apple.

We want our model to be accurate but accuracy is not a function we use to train the model. Let's say 99% of people have hair on their arms. If we trained the model to be accurate at determining if a person has hair on their arms, we will think it is accurate because the model can say yes everytime and it will be 99% accurate. This does not mean it is a good model. 

This is where the idea of Loss comes in. Loss is measuring how far off was the model when predicting in each variable it used. The model knows exactly how to change the weights assigned to each variable so was 100% correct.

### Install the package [here](https://pytorch.org/get-started/locally/)

Get started with the package by choosing your local system requirements. It is important to note that all of the processing will be done on your CPU. The CPU is not able to handle large amounts of fast computations like the GPU is. For simply learning and expirementing with PyTorch, this should not be an issue. However, if you plan to do large amounts data then you need to switch your system to process with its GPU when computing. 

## Check out the YouTube presentation [here](https://www.youtube.com/watch?v=nPDomZQ8jI4)


### To follow along use the supported resources in the github
- PyTorch Installation
- PyTorch Database Extension
- ExpoProject Markdown Code
