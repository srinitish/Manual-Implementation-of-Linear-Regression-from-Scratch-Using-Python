# 📈 Manual Implementation of Linear Regression from Scratch

## 📌 Project Overview

This project demonstrates the manual implementation of **Linear Regression** using fundamental mathematical concepts without relying on machine learning libraries such as Scikit-learn.

The objective is to deeply understand how Linear Regression works internally by implementing:

- Hypothesis function  
- Cost function (Mean Squared Error)  
- Gradient Descent optimization  
- Parameter updates  
- Model evaluation  

This project focuses on building the algorithm from first principles using only basic Python libraries like `numpy`.

---

## 🎯 Objectives

- Understand the mathematical foundation of Linear Regression  
- Implement Linear Regression without using ML frameworks  
- Implement Gradient Descent manually  
- Visualize cost reduction over iterations  
- Evaluate model performance  

---

## 🧠 Mathematical Background

### 1️⃣ Hypothesis Function

For Simple Linear Regression:

h(x) = θ₀ + θ₁x

For Multiple Linear Regression:

h(x) = θᵀx

---

### 2️⃣ Cost Function (Mean Squared Error)

J(θ) = (1 / 2m) Σ (h(xᵢ) - yᵢ)²

Where:
- m = number of training examples  
- θ = model parameters  

---

### 3️⃣ Gradient Descent Update Rule

θⱼ := θⱼ - α * ∂J(θ) / ∂θⱼ

Where:
- α = learning rate  

---

## 🛠️ Tech Stack

- Python 3.x  
- NumPy  
- Matplotlib (for visualization)  

---

## ⚙️ How It Works

1. Load dataset  
2. Initialize parameters (θ)  
3. Compute predictions using hypothesis function  
4. Calculate cost using MSE  
5. Update parameters using gradient descent  
6. Repeat until convergence  
7. Plot cost vs iterations  
