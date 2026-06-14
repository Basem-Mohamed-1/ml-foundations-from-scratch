# ML Foundations From Scratch

A foundational machine learning repository implementing core algorithms from scratch using Python and NumPy. The main goal of this project is to build a deep understanding of the mathematical intuition, optimization techniques, and learning process behind machine learning models without relying on high-level libraries like scikit-learn.

This repository focuses on learning how things work under the hood*, not just how to use them.

---

## 📌 Contents

This repository currently includes the following implementations:

### 1. Linear Regression (Gradient Descent)
A supervised learning algorithm used to model the relationship between input features and a continuous target variable.

- Implemented from scratch using NumPy
- Uses Gradient Descent for parameter optimization
- Minimizes Mean Squared Error (MSE)
- Includes visualization of fitted line and convergence of the cost function

---

### 2. Polynomial Regression
An extension of linear regression that allows modeling non-linear relationships by transforming input features.

- Feature expansion using polynomial terms
- Still trained using Linear Regression framework
- Helps capture non-linear patterns in data
- Includes visualization of curve fitting results

---

### 3. Normal Equation
An analytical solution for linear regression that computes optimal parameters directly without iterative optimization.

- No need for Gradient Descent
- Uses matrix operations to solve for weights
- Provides exact solution (when invertible)
- Useful for small to medium-sized datasets

---

### 4. Circle Fitting
A non-linear optimization problem where the goal is to fit a circle to a set of 2D data points.

- Optimizes circle parameters (center and radius)
- Uses numerical optimization techniques
- Demonstrates application of least squares in geometric fitting
- Includes visualization of fitted circle vs data points

---

## 📊 Visualizations

Each implementation includes visualizations to help understand:

- Model predictions vs actual data
- Optimization convergence (loss reduction over iterations)
- Geometric interpretation of fitted models (especially for circle fitting)

---

## 🧠 Key Learning Outcomes

By exploring this repository, you will gain understanding of:

- How machine learning models are trained from scratch
- The role of optimization in model fitting
- The difference between analytical and iterative solutions
- How feature engineering enables non-linear modeling
- Geometric interpretation of regression problems

---

## 🛠️ Tech Stack

- Python
- NumPy
- Matplotlib (for visualization)

---

## 🚀 Future Improvements

Planned additions:

- Logistic Regression
- Regularization (L1 / L2)
- Gradient Descent variants (Momentum, Adam)
- Neural Network from scratch
- Real-world datasets applications

---

## 📂 Project Goal

The goal of this repository is not just implementation, but building intuition — understanding what happens behind the scenes when a model "learns" from data.

---
