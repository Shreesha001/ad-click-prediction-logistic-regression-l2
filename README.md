# Ad Click Prediction using Logistic Regression (from Scratch)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg" />
  <img src="https://img.shields.io/badge/No%20Scikit--Learn-%2300C853.svg" />
  <img src="https://img.shields.io/badge/Logistic%20Regression-L2%20Regularized-yellow" /> 
</p>

## 🚀 Project Overview

This project implements a **binary classifier** from the ground up to predict whether a user will click on an advertisement, based on features like age, daily internet usage, time spent on site, and more.

---

## 🧠 Key Machine Learning Concepts Used

- **Logistic Regression** (Binary Classification)
- **Sigmoid Activation Function**
- **Gradient Descent Optimizer**
- **L2 Regularization** (Ridge)
- **Feature Scaling (Standardization)**
- **Decision Boundary Visualization** 

---

## 📂 Dataset Overview

The dataset includes the following features:

- `Daily Time Spent on Site`
- `Age`
- `Area Income`
- `Daily Internet Usage`
- `Male` (binary gender flag)
- `Clicked on Ad` (target label: 0 or 1)

🧾 Format: CSV  
📦 Size: Small (for binary classification)

---

## 📊 Results

- Achieved **94% accuracy** on the test dataset.
- Trained using **gradient descent** from scratch.
- **Decision boundary** visualized.

---

## 📌 Highlights

- 📦 No external ML libraries (e.g., scikit-learn, TensorFlow, PyTorch)
- 🧠 Gradient Descent implemented manually
- 💡 Includes **L2 Regularization** to prevent overfitting
- 📉 Cost function and gradients calculated for every iteration
- 📐 Feature mapping for **non-linear** decision boundaries
- 🎯 Predicts user behavior in a real-world ad-clicking scenario

---

## 🔧 How It Works

1. **Load and preprocess data** (`pandas`, `numpy`)
2. **Initialize weights and bias** (zeros or small random)
3. **Apply sigmoid function** to compute probability
4. **Compute cost with regularization**
5. **Compute gradients manually**
6. **Update weights via gradient descent**
7. **Track cost and visualize training**
8. **Evaluate model on test set**
9. **Plot decision boundary**

---


## 💡 Why No Scikit-Learn?

This project is built for **deep understanding of the mathematics and logic** behind logistic regression, not just using high-level APIs. By avoiding `scikit-learn`, the implementation focuses on:

- Manual cost and gradient derivation
- Numerical stability (e.g., sigmoid overflow)
- Regularization from first principles
- Building intuition behind optimization techniques

---

