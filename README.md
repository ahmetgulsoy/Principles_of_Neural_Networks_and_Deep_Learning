# Principles of Neural Networks and Deep Learning

This repository contains two Jupyter notebooks implementing autoencoders on the MNIST dataset:

1. **autoencoder.ipynb**  
   - Fully connected autoencoder
   - Uses MSE loss and optimizers like Adam
   - Encodes 28x28 images into a lower-dimensional latent space

2. **conv_autoencoder.ipynb**  
   - Convolutional autoencoder
   - Encoder uses Conv2d layers
   - Decoder uses linear layers
   - Trains with MSE loss

## Usage
- Install requirements:  
  ```bash
  pip install torch torchvision matplotlib
