# Fashion-MNIST CNN Classification (PyTorch)

This project implements a **Convolutional Neural Network (CNN)** using **PyTorch** to classify images from the Fashion-MNIST dataset.

## Project Overview

The goal of this project is to build and train a deep learning model capable of classifying clothing images into 10 categories.

The Fashion-MNIST dataset contains **28x28 grayscale images** of clothing items.  
In this project, the images are resized to **16x16 pixels** before training.

## Dataset

Fashion-MNIST classes:

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

## Technologies Used

- Python
- PyTorch
- Torchvision
- Matplotlib
- Jupyter Notebook

## Model Pipeline

1. Load Fashion-MNIST dataset
2. Resize images to **16×16**
3. Convert images to tensors
4. Build a CNN architecture
5. Train the model using **CrossEntropyLoss**
6. Optimize using **SGD optimizer**
7. Evaluate validation accuracy
8. Plot training loss and accuracy

## Results

The CNN successfully learns to classify clothing images from the Fashion-MNIST dataset.  
The notebook achieved **100% completion score in the Deep Learning course final project**.

## Repository Structure

