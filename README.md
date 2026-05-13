# Multi-Layer Perceptron (MLP) - MVC Project

## Overview
This project implements a Multi-Layer Perceptron (MLP) from scratch using NumPy.
The goal is to understand forward propagation, backpropagation, loss computation, and optimization techniques.
The model is trained on the MNIST handwritten digit dataset for multi-class classification (digits 0–9).

## Network Architecture
Layer        Type               Neurons    Activation
Input        Input Layer        784        -
Hidden 1     Fully Connected    128        Sigmoid
Hidden 2     Fully Connected    64         Sigmoid
Output       Fully Connected    10         Sigmoid

## Features Implemented
- Sigmoid activation and derivative
- Forward propagation
- Mean Squared Error (MSE) loss
- Backpropagation
- Mini-batch Gradient Descent
- Momentum and NAG optimizers
- Loss curve visualization
- Sample predictions
- Test accuracy evaluation

## Project Structure
```
mvc-mlp-25i-2617/
│
├── src/                          # Source files/implementation
│   ├── 25i_2617_mvc.ipynb        # Main Jupyter Notebook for training/testing
│   ├── loss.png                  # Loss Curve Image
│   └── predictions.png           # Model's predictions image
│
├── data/                         # Dataset files
│   └── mnist.npz                 # MNIST dataset
│
├── report/                       # Project documentation
│   └── MVC_REPORT_25i_2617_.pdf  # Final PDF report
│
└── README.md                     # Project overview and instructions
```


## How to Run

### 1. Install dependencies
pip install numpy matplotlib
### 2.Open Jupyter Notebook
Navigate to src/ and run:
jupyter notebook

## Results
- Loss decreases over epochs, showing learning.
- Momentum and NAG converge faster than plain GD.

Loss Curve: See report or generated plot
Sample Predictions: Model correctly predicts most digits

Test Accuracy: 95.54%

## Report
Available in the report/ folder. Includes:
- Theory
- Implementation
- Results
- Optimizer comparison

## Author
Name : Hammad Muddassir
Roll No: 25i-2617
BS Data Science 
Fast NUCES - Islamabad Campus

## Conclusion
This project demonstrates building a neural network from scratch using NumPy and highlights the importance of optimization techniques.
