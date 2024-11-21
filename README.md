# Autoencoder on the Fashion MNIST Dataset Using PyTorch

An autoencoder is an unsupervised machine learning algorithm. In this project, it takes an image as input and reconstructs that image using less information.

Autoencoders achieve this by projecting high-dimensional data to a lower-dimensional space (similar to Principal Component Analysis) while retaining the most important features. This lower-dimensional space is called the **latent space**.

![Autoencoder Diagram](http://res.cloudinary.com/dyd911kmh/image/upload/f_auto,q_auto:best/v1522830223/AutoEncoder_kfqad1.png)

---

## Overview

An autoencoder consists of two main components:

- **Encoder**: Compresses or downsamples the input image into a lesser number of bits. This reduced representation is called the **latent space** or **bottleneck**.
- **Decoder**: Attempts to reconstruct the input using only the encoding. If the decoder reconstructs the input accurately, the encoder-decoder system is functioning effectively.

This repository demonstrates how to create an autoencoder using PyTorch and applies it to the Fashion MNIST dataset.



## Requirements

To run the notebook, ensure you have the following installed:

- Python 3.7+
- PyTorch
- torchvision
- matplotlib
- numpy
- Jupyter Notebook or Jupyter Lab

You can install the dependencies using:

```bash
pip install torch torchvision matplotlib numpy jupyter
```

## Results

The model learns to compress the images into a latent space and reconstructs them with minimal loss of information. Check the notebook for visualizations of input vs. reconstructed images.

---

## Contribution

Feel free to fork this repository, make improvements, and submit pull requests!
