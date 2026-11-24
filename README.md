# MNIST Handwritten Digit Classification using CNN in PyTorch

## Overview

This project implements a simple Convolutional Neural Network (CNN) using PyTorch to classify handwritten digit images from the MNIST dataset.

The model learns to recognize handwritten digits from 0 to 9 using grayscale images of size 28 × 28 pixels.

The dataset contains 60,000 images, which are divided into training and testing sets using an 80:20 split.

## Dataset Details

**Dataset:** MNIST Handwritten Digit Dataset

| Property | Details |
|---|---|
| Total Images | 60,000 |
| Training Images | 48,000 |
| Testing Images | 12,000 |
| Image Size | 28 × 28 pixels |
| Image Channels | Grayscale |
| Number of Classes | 10 |
| Classes | Digits 0–9 |

### Dataset Classes

The dataset contains 10 handwritten digit classes:

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

| Parameter | Value |
|---|---|
| Framework | PyTorch |
| Model | Convolutional Neural Network (CNN) |
| Epochs | 50 |
| Total Dataset | 60,000 images |
| Training Images | 48,000 |
| Testing Images | 12,000 |
| Hardware | CPU (No GPU acceleration) |

## Model Architecture

The CNN model consists of:

- Convolutional layers
- ReLU activation functions
- Batch Normalization
- Max Pooling layers
- Dropout layers
- Fully Connected layers

## Project Workflow

1. Load the MNIST handwritten digit dataset.
2. Preprocess and normalize the images.
3. Split the dataset into training and testing sets.
4. Create a custom PyTorch Dataset and DataLoader.
5. Build the CNN architecture.
6. Train the model using PyTorch.
7. Evaluate the model on the testing dataset.

## Results

The model achieved the following results after training:

| Metric | Result |
|---|---:|
| Final Training Loss | 0.00848 |
| Testing Accuracy | 99.18% |

The model successfully classifies handwritten digits into their corresponding classes (0–9).

## Hardware Requirements

- CPU
- No dedicated GPU required.
- Python environment with the required dependencies.

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Tharunteja1820/MNIST-Digit-Classification-CNN-PyTorch_tt.git
```

### 2. Navigate to the Project Directory

```bash
cd MNIST-Digit-Classification-CNN-PyTorch_tt
```

### 3. Install Dependencies

```bash
pip install torch torchvision numpy pandas matplotlib scikit-learn jupyter
```

### 4. Run the Notebook

```bash
jupyter notebook MNIST_CNN.ipynb
```

Execute the notebook cells sequentially to train and evaluate the CNN model.

**Note:** The dataset must be available in the format and location expected by the notebook.

## Key Learning Outcomes

- Understanding Convolutional Neural Networks.
- Implementing CNN architectures using PyTorch.
- Working with image preprocessing and normalization.
- Creating custom PyTorch Dataset and DataLoader classes.
- Understanding model training and backpropagation.
- Evaluating deep learning model performance.
