# 🖋️ Handwritten Digit Recognition with PyTorch

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

This project is a **Neural Network classifier** that recognizes handwritten digits (0–9) from the famous [MNIST dataset](http://yann.lecun.com/exdb/mnist/).  
Built with **PyTorch**, it demonstrates the basics of deep learning — from preprocessing images to training a model and making predictions.

---

## 🚀 Features
- Input: 28x28 grayscale images of digits
- Model: Fully Connected Neural Network (MLP)
- Training on MNIST dataset
- Accuracy visualization (loss/accuracy plots)
- Predict digits from custom images

---


## 🧠 Model Architecture

- **Input Layer**: 784 features (28×28 pixels)
- **Hidden Layer 1**: Linear (784 → 128) + ReLU
- **Hidden Layer 2**: Linear (128 → 64) + ReLU
- **Output Layer**: Linear (64 → 10) → Logits
