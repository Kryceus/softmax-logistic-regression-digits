Softmax Logistic Regression on Handwritten Digits

A from-scratch implementation of multiclass logistic regression (softmax regression) in Python for handwritten digit classification using the Scikit-learn Digits dataset.

Overview

This project explores the theoretical and practical foundations of softmax regression by implementing the model manually without using high-level machine learning frameworks.

The system performs:

Forward propagation
Softmax probability prediction
Cross-entropy loss computation
Backward propagation
Mini-batch gradient descent
L2 regularisation
Hyperparameter tuning

The model classifies handwritten digits (0–9) from 8×8 grayscale images.

Dataset

The project uses the Scikit-learn Digits dataset:

1797 samples
10 digit classes
64 input features per sample

Dataset split:

70% training
15% validation
15% testing
Technologies Used
Python
NumPy
Scikit-learn
Matplotlib
Features
Multiclass softmax regression from scratch
One-hot encoding
Feature scaling with StandardScaler
Mini-batch gradient descent
L2 regularisation
Hyperparameter tuning
Confusion matrix and ROC evaluation
Results

Final model performance:

Test Accuracy: 98.1%
Validation Accuracy: 96.7%
Stable convergence with low final loss

The model achieved strong classification performance despite using a simple linear architecture.

