# Machine Learning Models

This repository contains a small set of core machine learning models that I implemented using NumPy.

I built these notebooks to develop a deep, hands-on understanding of the mathematics and optimization logic behind how machine learning models learn, from defining loss functions to computing gradients and updating parameters.

The goal of this work is to understand what happens inside a model during training.

---

## What this repository demonstrates

Through these notebooks, I focused on building intuition for:

- How loss functions are defined mathematically and what they measure  
- How gradients are derived and used to update model parameters  
- How gradient descent behaves during training and convergence  
- How vectorization connects linear algebra to efficient computation  
- How regression and classification models differ at a mathematical level  

Each notebook includes a full training loop, explicit gradient computation, and prediction logic.

---

## Models included

### 1. Linear Regression
Implemented to understand:
- Mean Squared Error (MSE) as an optimization objective  
- Gradient derivation with respect to weights and bias  
- How gradient descent minimizes error over iterations  
- The effect of learning rate on convergence and stability  

---

### 2. Multivariate Linear Regression
An extension of linear regression to multiple features, focusing on:
- Matrix-based representations of data  
- Fully vectorized gradient computation  
- How dimensionality influences learning dynamics  


---

### 3. Logistic Regression
Implemented from first principles to understand classification:
- Sigmoid function as a probability mapping  
- Binary cross-entropy loss and its mathematical motivation  
- Gradient computation for probabilistic models  
- How decision boundaries emerge from linear combinations of features  

---

## Implementation details

- Language: Python  
- Libraries: NumPy for numerical computation.

---

## Notes

These notebooks prioritize clarity and mathematical understanding.  
They are intended for learning, experimentation, and building strong foundations.

