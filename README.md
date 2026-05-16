# MNIST Digit Classification using CNN (Deep Learning Project)

## 📌 Problem Statement
Handwritten digit classification using Deep Learning Convolutional Neural Networks (CNN) on the MNIST dataset.

---

## 📊 Dataset
- Dataset: MNIST
- Source: Built-in dataset from TensorFlow / PyTorch
- 60,000 training images + 10,000 test images
- Image size: 28×28 grayscale digits (0–9)

---

## 🧹 Data Preprocessing
- Normalization: Pixel values scaled to range [0, 1]
- Reshaping: (28, 28, 1) for CNN input
- Train/Validation split (used for monitoring training performance)

---

## 🧠 Model Architectures

### 🔹 Model A: Basic CNN
- Convolutional layers (Conv2D)
- ReLU activation
- MaxPooling layers
- Fully connected Dense layers

---

### 🔹 Model B: Improved CNN
- Convolutional layers
- Batch Normalization
- Dropout regularization
- Fully connected Dense layers

---

## ⚙️ Training Setup
- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Metrics: Accuracy, Loss
- Epochs: 5
- Batch Size: 64

---

## 🧪 Experimentation
Two experiments were conducted:
- Model A: Basic CNN architecture
- Model B: CNN + BatchNorm + Dropout

---

## 📈 Results Comparison

| Model     | Accuracy | Loss   |
|-----------|----------|--------|
| Model A   | 98.97%   | 0.0339 |
| Model B   | 99.11%   | 0.0334 |

---

## 📊 Evaluation Metrics
- Accuracy
- Loss
- Validation Accuracy
- Validation Loss

---

## 📉 Visualizations
The project includes:
- Training vs Validation Accuracy curves
- Training vs Validation Loss curves

---

## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Open Google Colab
2. Upload the notebook
3. Run all cells

### Option 2: Local Environment
```bash
pip install torch torchvision matplotlib pandas
python main.py
