# MNIST Digit Classification using CNN (Deep Learning Project)

---

## 📌 Problem Statement
Handwritten digit classification using Deep Learning Convolutional Neural Networks (CNN) on the MNIST dataset.

---

## 📊 Dataset
- Dataset: MNIST
- Source: Built-in dataset (PyTorch / TensorFlow)
- 60,000 training images + 10,000 test images
- Image size: 28×28 grayscale (digits 0–9)

---

## 🧹 Data Preprocessing
- Normalization: Pixel values scaled to [-1, 1]
- Tensor conversion using ToTensor()
- Train/Validation split (83% / 17%)
- Data augmentation: Random rotation applied

---

## 🖼️ Data Visualization
- Sample MNIST images displayed from dataset
- Helps understand input data distribution before training

---

## 🧠 Model Architectures

### 🔹 Model A: Basic CNN
- Simple convolutional neural network
- ReLU activation
- MaxPooling layers
- Fully connected layers

---

### 🔹 Model B: CNN + BatchNorm + Dropout
- Convolutional layers
- Batch Normalization
- Dropout regularization
- Improved generalization

---

### 🔹 Model C: Deep CNN (Experimental)
- Deeper CNN architecture
- Additional convolutional layers
- Batch Normalization
- Dropout
- SGD optimizer instead of Adam
- Enhanced feature extraction

---

## ⚙️ Training Setup
- Loss Function: CrossEntropyLoss
- Batch Size: 64
- Epochs: 5

### Optimizers:
- Model A: Adam (lr = 0.001)
- Model B: Adam (lr = 0.001)
- Model C: SGD (lr = 0.01, momentum = 0.9)

---

## 🧪 Experimentation
Three experiments were conducted by varying:
- Model architecture (simple vs deep CNN)
- Regularization techniques (Dropout, BatchNorm)
- Optimizers (Adam vs SGD)

---

## 📈 Evaluation Metrics
- Accuracy
- Loss
- Validation Accuracy
- Validation Loss

---

## 📊 Results Comparison

| Model     | Accuracy | Loss   |
|-----------|----------|--------|
| Model A   | XX%      | XX     |
| Model B   | XX%      | XX     |
| Model C   | XX%      | XX     |

---

## 📉 Visualizations
The project includes:
- Training vs Validation Accuracy curves
- Training vs Validation Loss curves
- Sample MNIST image visualization

---

## 🚀 How to Run

### Option 1: Google Colab (Recommended)
1. Open Google Colab
2. Upload notebook
3. Run all cells

### Option 2: Local Machine
```bash
pip install torch torchvision matplotlib pandas
python main.py
