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

Project Structure
softmax-logistic-regression-digits/
│
├── README.md
├── logistic_regression_digits.py
├── logistic_regression_digits.ipynb
├── requirements.txt
└── report/
    └── logistic_regression_report.pdf
Installation

Clone the repository:

git clone https://github.com/yourusername/softmax-logistic-regression-digits.git

Install dependencies:

pip install -r requirements.txt

Run the project:

python logistic_regression_digits.py
Future Improvements
Adam optimizer
Cross-validation
Weighted loss functions
Neural network comparison
Vectorised optimisation
Acknowledgement

ChatGPT was used for theoretical clarification, implementation guidance, and code scaffolding.

License

Educational project.
