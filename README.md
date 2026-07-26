# Fashion-MNIST CNN Classification using PyTorch

## small overview :
This project implements a Simple Convolutional Neural Network (CNN) using PyTorch to classify images from the Fashion-MNIST dataset.
The model learns to identify different types of clothing images such as shirts, shoes, bags, and dresses.

## Dataset
Fashion-MNIST dataset (downloaded from kaggle) contains:
- Original dataset size: 70,000 images
- Images used for training/testing: 48,000 images (selected due to no GPU availability)
- Image size: 28 × 28 pixels
- Number of classes: 10 clothing categories

Classes:
- T-shirt / Top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle Boot

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
- Dataset Used: 48,000 images
- Hardware: CPU (No GPU acceleration)

## Model Architecture
The CNN model contains:
- Convolutional layers
- ReLU activation
- Max pooling layers
- dropout layers
- Fully connected layers

## Project Workflow
1. Load Fashion-MNIST dataset
2. Preprocess and normalize images
3. Build CNN model
4. Train the model
5. Evaluate performance

## Results
Final Training Loss: 0.00848
Testing Accuracy: 99.18%
