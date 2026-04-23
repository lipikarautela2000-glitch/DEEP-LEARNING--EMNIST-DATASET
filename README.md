# 🧠 Deep Learning on EMNIST Dataset

A deep learning project built step-by-step in PyTorch that classifies 
handwritten letters from the EMNIST dataset.

## 📌 Project Overview

This project progressively builds from a single neuron to a full 
Convolutional Neural Network (CNN) to classify all 26 English letters.

## 🚀 Stages Covered

| Stage | Description |
|-------|-------------|
| Stage 1 | Single Neuron (Perceptron) — Binary classification (is it 'A' or not?) |
| Stage 2 | Gradient Descent — Manual backpropagation & weight updates |
| Stage 3 | Feedforward Neural Network (FFNN) — 784 → 256 → 128 → 26 |
| Stage 4 | Convolutional Neural Network (CNN) — Conv layers + MaxPooling |

## 🗂️ Dataset

- **EMNIST Letters** — Extended MNIST with handwritten A–Z characters
- 26 classes (one per letter)
- 28×28 grayscale images

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- Matplotlib
- Google Colab

## 🏗️ Model Architectures

**FFNN:**  
Input (784) → Hidden (256, ReLU) → Hidden (128, ReLU) → Output (26)

**CNN:**  
Conv1 (16 filters) → MaxPool → Conv2 (32 filters) → MaxPool → FC (128) → Output (26)

## ▶️ How to Run

1. Open `DL_PROJECT (1).ipynb` in Google Colab
2. Run all cells from top to bottom
3. Dataset downloads automatically

## 📊 Results

| Model | Epochs | Test Accuracy |
|-------|--------|---------------|
| FFNN  | 5      | ~85%          |
| CNN   | 5      | ~90%+         |

