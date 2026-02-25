# MNIST Deep Learning Model Comparison

## Overview
This project implements and evaluates multiple deep learning architectures on the MNIST handwritten digit dataset using PyTorch. The goal was to compare neural network architectures and optimizers while benchmarking against a classical machine learning baseline.

---

## Models Implemented
- Multi-Layer Perceptron (MLP)
  - ReLU + Adam
  - Sigmoid + Adam
  - ReLU + SGD
  - 5-layer MLP (Best MLP)

- Convolutional Neural Networks (CNN)
  - Custom 4-layer CNN (Best Overall Model)
  - LeNet-5

- Classical Baseline
  - XGBoost (from previous assignment)

---

## Dataset
- MNIST (28x28 grayscale handwritten digits)
- 60,000 training samples
- 10,000 test samples

---

## Performance Comparison

| Model | Accuracy | Training Time |
|--------|----------|---------------|
| XGBoost | 97.2% | 30s |
| Best MLP | 98.2% | 65s |
| LeNet-5 | 98.3% | 40s |
| 4-layer CNN | **98.6%** | 55s |

---

## Key Insights
- CNNs significantly outperform classical ML models on image data.
- ReLU activation consistently outperformed Sigmoid.
- Adam optimizer converged faster and achieved higher accuracy than SGD.
- Deeper MLP improved performance but CNN architectures were superior overall.

---

## Technologies Used
- Python
- PyTorch
- NumPy
- Matplotlib
- Scikit-learn

---

## How to Run
1. Install dependencies:
