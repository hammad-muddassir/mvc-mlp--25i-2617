# Multi-Layer Perceptron (MLP) - MVC Project

## Overview
This project implements a **Multi-Layer Perceptron (MLP)** from scratch using **NumPy**.  
The objective of this project is to understand the core concepts behind neural networks, including:

- Forward Propagation
- Backpropagation
- Loss Computation
- Gradient-Based Optimization

The model is trained on the **MNIST Handwritten Digit Dataset** for multi-class classification of digits from **0–9**.

---

# Network Architecture

| Layer      | Type             | Neurons | Activation |
|------------|------------------|----------|-------------|
| Input      | Input Layer      | 784      | -           |
| Hidden 1   | Fully Connected  | 128      | Sigmoid     |
| Hidden 2   | Fully Connected  | 64       | Sigmoid     |
| Output     | Fully Connected  | 10       | Sigmoid     |

---

# Features Implemented

- Sigmoid activation function and derivative
- Forward propagation
- Mean Squared Error (MSE) loss
- Backpropagation
- Mini-batch Gradient Descent
- Momentum Optimizer
- Nesterov Accelerated Gradient (NAG)
- Loss curve visualization
- Sample predictions visualization
- Test accuracy evaluation

---

# Project Structure

```text
mvc-mlp--25i-2617/
│
├── src/                          # Source files / implementation
│   ├── 25i_2617_mvc.ipynb        # Main Jupyter Notebook
│   ├── loss.png                  # Loss curve visualization
│   └── predictions.png           # Sample predictions
│
├── data/                         # Dataset files
│   └── mnist.npz                 # MNIST dataset
│
├── report/                       # Project documentation
│   └── MVC_REPORT_25i_2617.pdf   # Final project report
│
└── README.md                     # Project overview
```

---

# Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/hammad-muddassir/mvc-mlp--25i-2617.git
cd mvc-mlp-25i-2617
```

## 2. Install Dependencies

```bash
pip install numpy matplotlib
```

## 3. Run the Notebook

Navigate to the `src/` folder and launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
25i_2617_mvc.ipynb
```

---

# Results

- The loss decreases consistently over epochs, indicating successful learning.
- Momentum and NAG optimizers converge faster than standard Gradient Descent.
- The model correctly predicts most handwritten digits from the MNIST dataset.

## Final Test Accuracy

```text
95.54%
```

---

# Visual Results

## Loss Curve
See `loss.png`

## Sample Predictions
See `predictions.png`

---

# Report

The detailed project report is available in the `report/` folder and includes:

- Theoretical Background
- Mathematical Derivations
- Implementation Details
- Experimental Results
- Optimizer Comparison

---

# Author

**Hammad Muddassir**  
Roll No: **25i-2617**  
BS Data Science  
FAST NUCES – Islamabad Campus

---

# Conclusion

This project demonstrates the implementation of a neural network completely from scratch using NumPy. It highlights the importance of optimization techniques such as Momentum and NAG in improving convergence speed and overall performance.
