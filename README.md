# EMNIST-Handwritten-Character-Recognition

## Overview
This project develops a deep learning model capable of recognizing handwritten characters, extending beyond digits to include both uppercase and lowercase letters, using the Extended MNIST (EMNIST) dataset. By leveraging PyTorch, the project showcases the creation of a custom neural network from scratch, emphasizing data handling, model optimization, and performance analysis.

## Features
- **Custom Neural Network**: Utilizes a bespoke architecture designed for the complexities of the EMNIST dataset.
- **Data Augmentation**: Implements preprocessing techniques to enhance model accuracy and robustness.
- **Dynamic Learning**: Features dynamic resizing, normalization, and the application of the Adam optimizer for effective learning.
- **Accuracy Analysis**: Includes detailed performance analysis through training and validation phases, highlighting the model's efficiency in character recognition.

## Technologies Used
- Python
- PyTorch
- Torchvision
- Matplotlib
- NumPy

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- PyTorch
- Torchvision
- Matplotlib
- NumPy

## Dataset
The EMNIST dataset is automatically downloaded when you run the training script. It includes a wide range of handwritten digits and letters, which the model uses for training and validation.

## Model Architecture
The model consists of four linear layers with ReLU activations, concluding with a softmax layer for classification. It is designed to efficiently process the flattened input images into 62 possible classes (digits and letters).

## Performance
The model achieves significant accuracy on the EMNIST dataset, demonstrating its capability to generalize well across a diverse set of handwritten characters. Detailed performance metrics are provided after each training epoch, including loss and accuracy rates.
