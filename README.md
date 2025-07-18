# 🔢 MNIST Digit Classifier

This project builds a deep learning model to classify handwritten digits (0–9) using the MNIST dataset.

## 🧠 Project Objective
Train a simple neural network to recognize and classify digits from grayscale images of handwritten numbers.

## 📊 Dataset
- **Source**: [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)
- 60,000 training images, 10,000 test images
- Each image is 28x28 pixels in grayscale

## 🧱 Model Architecture
- **Input Layer**: 784 units (28x28 pixels)
- **Hidden Layer 1**: 128 neurons with ReLU
- **Hidden Layer 2**: 64 neurons with ReLU
- **Output Layer**: 10 neurons (one for each digit class)

## 🧪 Evaluation
- **Loss Function**: CrossEntropyLoss
- **Optimizer**: Adam
- **Accuracy Achieved**: ~97% on test data

## ⚙️ Technologies Used
- Python
- PyTorch
- torchvision
- matplotlib

---

> One of my foundational deep learning projects focused on supervised learning and image classification using neural networks.
