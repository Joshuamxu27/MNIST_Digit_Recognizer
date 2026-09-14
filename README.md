# MNIST Digit Classifier

A beginner deep learning project built with PyTorch to gain hands-on experience with neural networks, using the classic MNIST handwritten digit dataset.

## Overview

This project implements a simple feedforward neural network to classify handwritten digits (0–9) from the MNIST dataset. The goal was to build the full pipeline from scratch — data loading, model architecture, training loop, and evaluation — to build intuition for how PyTorch models are structured and trained.

## Model Architecture

The network is a fully connected feedforward neural network:

- **Input layer:** 784 neurons (flattened 28×28 pixel images)
- **Hidden layer 1:** 100 neurons, ReLU activation
- **Hidden layer 2:** 50 neurons, ReLU activation
- **Output layer:** 10 neurons (digit classes 0–9)

## Training

- **Loss function:** Cross-Entropy Loss
- **Optimizer:** Stochastic Gradient Descent (SGD)
- **Epochs:** 20

## Results

- **Test Accuracy:** 97.35%

## Tech Stack

- Python
- PyTorch
- NumPy
- Matplotlib (for visualizing predictions)

## What I Learned

- Building custom `Dataset` and `DataLoader` classes in PyTorch
- Structuring a neural network with `nn.Module`
- Writing a training loop with manual gradient updates
- Evaluating model performance on unseen test data