# Machine Learning Models — Built From Scratch

This repository contains a small set of core machine learning models that I implemented **from scratch using NumPy**.

I built these notebooks deliberately without using high-level ML libraries so I could develop a **deep understanding of the mathematics and optimization logic** behind how these models actually learn — rather than treating them as black boxes.

The focus here is on *how* and *why* the algorithms work, not just on getting predictions.

---

## What this repository demonstrates

Through these notebooks, I focused on understanding:

- How loss functions are mathematically defined and what they represent  
- How gradients are derived and used to update parameters  
- Why gradient descent converges (or fails) under certain conditions  
- How vectorization changes both performance and clarity  
- How linear models differ from probabilistic classification models at a mathematical level  

Every model is trained using manually written training loops, gradient calculations, and update rules.

---

## Models included

### 1. Linear Regression
Implemented to understand:
- Mean Squared Error (MSE) as a loss function  
- Derivation of gradients with respect to weights and bias  
- How gradient descent minimizes error over iterations  
- The relationship between learning rate, convergence, and stability  

This notebook helped build intuition around optimization and parameter updates.

---

### 2. Multivariate Linear Regression
An extension of linear regression to multiple features, focusing on:
- Vector and matrix representations of data  
- Fully vectorized gradient computation  
- How dimensionality affects gradients and learning dynamics  

This notebook emphasizes the math behind scaling linear models beyond a single feature.

---

### 3. Logistic Regression
Built from first principles to understand classification:
- Sigmoid function as a probability mapping  
- Binary cross-entropy loss and why it is used instead of MSE  
- Gradient computation for probabilistic models  
- How decision boundaries emerge from linear combinations  

This notebook connects linear algebra with probability and optimization.

---

## Implementation details

- Language: Python  
- Libraries used: NumPy (for numerical computation), Matplotlib (for visualization where needed)  

All learning logic — loss functions, gradients, and updates — is implemented manually.

---

## Why I built this

Writing these models from scratch helped me:
- Build strong intuition for ML optimization  
- Debug models more confidently when using real ML libraries  
- Understand why certain hyperparameters behave the way they do  
- Bridge the gap between mathematical theory and practical implementation  

This repo represents my effort to learn machine learning **from first principles** before applying it at scale.

---

## Notes

These implementations prioritize clarity and correctness over performance.  
They are meant for learning, experimentation, and understanding — not for production use.

