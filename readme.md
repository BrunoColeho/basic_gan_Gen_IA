# Basic GAN with PyTorch

This project implements a basic Generative Adversarial Network (GAN) using PyTorch. The GAN is trained on the MNIST dataset to generate images of handwritten digits.

## Project Contents

- **Main Files:**
  - `basic_gan.ipynb`: Jupyter Notebook containing the GAN implementation.

- **Dependencies:**
  - PyTorch
  - Torchvision
  - Matplotlib

## How to Run

1. Open the `basic_gan.ipynb` notebook in a Jupyter environment.
2. Execute each cell in the notebook sequentially to train the GAN.
3. Observe the generated images and training statistics during the process. (it may take a while)

## GAN Architecture

- **Generator:**
  - Feedforward neural network transforming noise vectors into simulated MNIST images.
  
- **Discriminator:**
  - Feedforward neural network classifying whether an image is real or fake.

## Results

GAN-generated images will be displayed during training, providing a comparison with real samples from the MNIST dataset.
