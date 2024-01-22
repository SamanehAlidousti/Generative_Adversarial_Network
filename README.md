# Generative Adversarial Network

This repository contains a Jupyter notebook implementing a Generative Adversarial Network (GAN). The GAN is trained on the MNIST dataset to generate realistic hand-written digit images.


![GAN](https://github.com/SamanehAlidousti/Generative_Adversarial_Network/assets/107434108/770c70ae-2fc6-4ff9-8915-f14f8ba1ac3d)



## Prerequisites

Before running the code, make sure you have the following dependencies installed:

```bash
pip install torch torchvision torchsummary tqdm matplotlib
```

## Load MNIST Dataset

The notebook includes code to download and load the MNIST dataset using PyTorch's DataLoader.

## Create Discriminator Network

The discriminator network is defined as a convolutional neural network (CNN) in the Discriminator class. It is designed to classify whether an input image is real or fake.

## Create Generator Network

The generator network is defined as a CNN in the Generator class. It takes random noise as input and generates synthetic images.

## Weight Initialization

A function weights_init is provided to initialize the weights of the discriminator and generator networks.

## Loss Function and Optimizer

The notebook defines the loss functions (real_loss and fake_loss) and sets up the Adam optimizers for both the discriminator and generator.

## Training Loop

The training loop iterates through the specified number of epochs, updating the discriminator and generator networks alternatively. It prints the average discriminator and generator losses for each epoch and displays a grid of generated images.



