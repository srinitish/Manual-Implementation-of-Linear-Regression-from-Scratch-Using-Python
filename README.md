# 📊 Manual Implementation of Logistic Regression (From Scratch)

## 📌 Project Overview

This project demonstrates the complete manual implementation of **Logistic Regression** for binary classification without using machine learning libraries such as Scikit-learn.

The objective is to understand the mathematical and computational foundations of Logistic Regression by implementing:

- Sigmoid activation function  
- Cross-Entropy (Log Loss) cost function  
- Gradient Descent optimization  
- Parameter updates  
- Model evaluation metrics  

The algorithm is built entirely from first principles using core Python and NumPy.

---

## 🎯 Objectives

- Understand the mathematical intuition behind Logistic Regression  
- Implement binary classification without ML frameworks  
- Manually derive and implement cross-entropy loss  
- Optimize parameters using gradient descent  
- Evaluate classification performance  

---

## 🧠 Mathematical Background

### 1️⃣ Hypothesis Function (Sigmoid Function)

Logistic Regression uses the sigmoid function to map predictions to probabilities:

\[
h_\theta(x) = \frac{1}{1 + e^{-(\theta^T x)}}
\]

Where:
- \( \theta \) = model parameters  
- \( x \) = feature vector  

The output lies between 0 and 1, representing probability.

---

### 2️⃣ Cost Function (Binary Cross-Entropy)

\[
J(\theta) = -\frac{1}{m} \sum_{i=1}^{m} \left[ y^{(i)} \log(h_\theta(x^{(i)})) + (1 - y^{(i)}) \log(1 - h_\theta(x^{(i)})) \right]
\]

Where:
- \( m \) = number of training samples  
- \( y \in \{0,1\} \)

---

### 3️⃣ Gradient Descent Update Rule

\[
\theta := \theta - \alpha \frac{\partial J(\theta)}{\partial \theta}
\]

Where:
- \( \alpha \) = learning rate  

---

## 🛠️ Tech Stack

- Python 3.x  
- NumPy  
- Matplotlib (for visualization)  


---

## ⚙️ How It Works

1. Load and preprocess dataset  
2. Initialize parameters (θ)  
3. Compute linear combination (z = θᵀx)  
4. Apply sigmoid to obtain probabilities  
5. Compute cross-entropy loss  
6. Update parameters using gradient descent  
7. Repeat until convergence  
8. Evaluate model performance  


