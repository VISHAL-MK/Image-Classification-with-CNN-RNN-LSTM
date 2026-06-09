# Deep Learning Models using TensorFlow and PyTorch

## Overview

This repository contains implementations of various Deep Learning models using TensorFlow and PyTorch. The project demonstrates the fundamentals of Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), and Long Short-Term Memory (LSTM) networks for image classification and sequence learning tasks.

## Features

- CNN-based image classification on the CIFAR-10 dataset using TensorFlow.
- Custom implementation of a basic Recurrent Neural Network (RNN) using PyTorch.
- LSTM-based handwritten digit classification on the MNIST dataset.
- Training, validation, and evaluation workflows.
- Visualization of model performance and accuracy.

## Technologies Used

- Python
- TensorFlow
- PyTorch
- NumPy
- Matplotlib
- Torchvision

## Datasets

### CIFAR-10
- 60,000 color images across 10 classes.
- Used for CNN image classification.

### MNIST
- 70,000 handwritten digit images.
- Used for LSTM-based digit recognition.

## Models Implemented

### 1. Convolutional Neural Network (CNN)
- Built using TensorFlow/Keras.
- Multiple convolution and max-pooling layers.
- Trained on the CIFAR-10 dataset.

### 2. Basic Recurrent Neural Network (RNN)
- Implemented from scratch using PyTorch.
- Demonstrates sequence processing and hidden state computation.

### 3. Long Short-Term Memory (LSTM)
- Implemented using PyTorch.
- Applied to MNIST digit classification by treating images as sequential data.

## Results

The implemented models demonstrate:
- Effective image classification using CNNs.
- Sequence learning with RNNs.
- Improved long-term dependency handling using LSTMs.

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Deep-Learning-Models-TensorFlow-PyTorch.git
cd Deep-Learning-Models-TensorFlow-PyTorch
```

Install dependencies:

```bash
pip install tensorflow torch torchvision matplotlib numpy
```

## Usage

Run the notebook or Python script to train and evaluate the models:

```bash
python tensorflow.py
```

or open the notebook in Google Colab/Jupyter Notebook.

## Learning Outcomes

This project covers:
- Deep Learning fundamentals
- CNN architecture design
- RNN sequence modeling
- LSTM networks
- Model training and evaluation
- Image classification techniques

## Author

Vishal M

B.E. Artificial Intelligence and Machine Learning

## License

This project is created for educational and learning purposes.
