# Neural Networks from Scratch 🧠

This project demonstrates the manual implementation of a multilayer neural network using only **Python** and **NumPy**. It is designed to provide an educational and intuitive understanding of how neural networks work.

## 📁 Project Overview

The notebook `nnfs.ipynb` includes a complete implementation of a feedforward neural network trained on the **MNIST** dataset of handwritten digits.

### Features:

- Dense (fully connected) layers
- Multiple activation functions
- Forward and backward propagation
- Categorical cross-entropy loss
- Training loop with accuracy tracking

Achieved a **test accuracy of 93.59%** on the MNIST dataset.

## 🧠 Activation Functions Implemented

- **ReLU** (Rectified Linear Unit)
- **Leaky ReLU**
- **Tanh**
- **Sigmoid**
- **Softmax** (used in the output layer)

## 📦 Setup Instructions

1. Clone this repository:

   ```bash
   git clone <repository_name>
   cd nnfs-numpy
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook nnfs.ipynb
   ```

## 🗂️ Folder Structure

```
├── nnfs.ipynb          # Main notebook containing all the implementation
├── README.md           # Project overview and instructions
└── (Optional) data/    # MNIST dataset, if not loaded via script
```

## 📈 Performance

- **Dataset**: MNIST (60,000 training images, 10,000 test images of handwritten digits 0-9)
- **Test Accuracy**: **93.59%**
