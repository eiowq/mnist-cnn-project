# MNIST Digit Classification using CNN

## Problem
Handwritten digit classification using Deep Learning (CNN)

## Dataset
MNIST dataset (loaded from TensorFlow)

## Preprocessing
- Normalization (0-1 scaling)
- Reshaping to (28,28,1)
- Train/Validation split

## Models
- Model A: Basic CNN
- Model B: CNN + BatchNormalization + Dropout

## Results

| Model | Accuracy | Loss |
|------|----------|------|
| Model A | 98.97% | 0.0339 |
| Model B | 99.11% | 0.0334 |

## How to run
- Open Google Colab
- Upload notebook
- Run all cells