# MNIST Digit Classification using CNN in PyTorch

## small overview :
This project implements a Simple Convolutional Neural Network (CNN) using PyTorch to classify images from the Fashion-MNIST dataset.
The model learns to identify different types of clothing images such as shirts, shoes, bags, and dresses.

This project uses the MNIST handwritten digit dataset.

Dataset details:
- Total images: 60,000
- Images used: 48,000
- Testing images: 12,000
- Image size: 28 × 28 pixels
- Number of classes: 10 digits (0-9)
The dataset contains grayscale images of handwritten digits.

Classes:
- Digit 0
- Digit 1
- Digit 2
- Digit 3
- Digit 4
- Digit 5
- Digit 6
- Digit 7
- Digit 8
- Digit 9

## Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

## Training Details
- Framework: PyTorch
- Model: Convolutional Neural Network (CNN)
- Epochs: 50
- Dataset Used: 60,000 images
- Hardware: CPU (No GPU acceleration)

## Model Architecture
The CNN model contains:
- Convolutional layers
- ReLU activation
- Max pooling layers
- dropout layers
- Fully connected layers

## Project Workflow
1. Load MNIST dataset
2. Preprocess images
3. Build CNN model
4. Train the model
5. Evaluate performance

## Results
Final Training Loss: 0.00848
Testing Accuracy: 99.18%
