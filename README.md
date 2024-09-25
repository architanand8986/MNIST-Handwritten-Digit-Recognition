# MNIST Handwritten Digit Recognition

This project implements a handwritten digit recognition model using PyTorch, showcasing two architectures: an Artificial Neural Network (ANN) and a Convolutional Neural Network (CNN). The models are trained on the MNIST dataset, which consists of 70,000 grayscale images of handwritten digits (0-9).<br>For dataset details, [click here](https://pytorch.org/vision/0.19/generated/torchvision.datasets.MNIST.html#torchvision.datasets.MNIST).

## Features

- **ANN Model**: Achieved an accuracy of 91%.
- **CNN Model**: Improved accuracy to 98% using convolutional layers for feature extraction.

## Confusion Matrices

### ANN Confusion Matrix
![ANN Confusion Matrix](https://github.com/architanand8986/MNIST-Handwritten-Digit-Recognition/blob/main/Images/ANN%20Confusion%20matrix.png)

### CNN Confusion Matrix
![CNN Confusion Matrix](https://github.com/architanand8986/MNIST-Handwritten-Digit-Recognition/blob/main/Images/CNN%20Confusion%20matrix.png)

## Requirements

To run this project, you need to install the following Python libraries:

```bash
pip install torch torchvision mlxtend torchmetrics
