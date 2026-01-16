# CIFAR-10 Image Classification – Level 1 (Baseline)

## Overview
This project implements a baseline image classification model on the CIFAR-10 dataset
as part of a multi-level ML hiring challenge.

## Dataset
- CIFAR-10
- 60,000 images
- 10 classes:
  Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

## Model
- ResNet-18 (pre-trained on ImageNet)
- Transfer learning approach
- Final classification layer modified for 10 classes

## Training Setup
- Framework: PyTorch
- Dataset split:
  - Training: 80%
  - Validation: 10%
  - Testing: 10%
- Optimizer: Adam
- Loss Function: Cross Entropy Loss
- Training performed on Google Colab (GPU)

## Results
- Test Accuracy: **92.16%**
- Training and validation accuracy curves are available in the notebook

## Files
- `level_1_cifar10.ipynb`
  - Contains all code for data loading, training, evaluation, and visualization

## How to Run
1. Open the notebook in Google Colab
2. Enable GPU runtime
3. Run all cells from top to bottom

## Notes
- Dataset is loaded automatically using torchvision
- No dataset files are stored in this repository
