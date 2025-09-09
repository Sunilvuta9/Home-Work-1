# CS5710 Machine Learning – Homework 1  

**Student Name:** Sunil Kumar Vuta
**University:** University of Central Missouri  
**Course:** CS5710 Machine Learning, Fall 2025  

## 📌 Assignment Overview  
This repository contains my solutions for **Homework 1** in CS5710 Machine Learning.  

The assignment covers the following:  
1. Function Approximation by Hand  
2. Random Guessing Practice  
3. First Gradient Descent Iteration  
4. Comparing Random Guessing vs Gradient Descent  
5. Recognizing Underfitting and Overfitting  
6. Comparing Models (Bias vs Variance)  
7. Programming Problem – Linear Regression using Closed-form and Gradient Descent  

### 1. Function Approximation by Hand  
- Compared two models θ=(1,0) and θ=(0.5,1).  
- Calculated predictions, residuals, squared residuals, and MSE.  
- **Result:** Model 1 fits better (MSE=0.5 < 1.125).  

---

### 2. Random Guessing Practice  
- Cost function: J(θ₁, θ₂)=8(θ₁−0.3)² + 4(θ₂−0.7)²  
- J(0.1,0.2)=1.32, J(0.5,0.9)=0.48 → (0.5,0.9) is closer to (0.3,0.7).  
- **Conclusion:** Random guessing is inefficient compared to systematic methods like gradient descent.  

---

### 3. First Gradient Descent Iteration  
- Dataset: (1,3), (2,4), (3,6), (4,5).  
- Started with θ=(0,0), α=0.01.  
- Computed predictions, residuals, gradient, updated θ, and compared J before/after.  
- Demonstrated the improvement after updates.  

---

### 4. Compare Random Guessing vs Gradient Descent  
- Dataset: (1,2), (2,2), (3,4), (4,6).  
- Random guesses:  
  - θ=(0.2,0.5) → J=??  
  - θ=(0.9,0.1) → J≈1.935  
- First GD step → J≈10.509.  
- **Observation:** Random guess was closer in this case, but GD systematically improves over iterations.  

---

### 5. Recognizing Underfitting and Overfitting  
- **Case:** High training error & high test error → **Underfitting**.  
- Fixes: Increase model complexity, train longer, add better features.  

---

### 6. Comparing Models  
- Model A: Overfitting (low bias, high variance).  
- Model B: Underfitting (high bias, low variance).  
- **Fixes:**  
  - For Model A → regularization, more data, early stopping.  
  - For Model B → increase complexity, more features, train longer.  

---

### 7. Programming Problem – Linear Regression  
- Implemented **Closed-form Normal Equation** and **Gradient Descent**.  
- Dataset: y=3+4x+ϵ (Gaussian noise).  
- Results:  
  - Closed-form: Intercept ≈ 3.105, Slope ≈ 3.984  
  - Gradient Descent: Intercept ≈ 3.105, Slope ≈ 3.984  
- Both methods converged to nearly the same solution.  
- Plotted regression lines and loss curve (MSE vs iterations).
  
How to Run the Code -->just click the gitup link and downlaod the python file and run in google colob : https://github.com/Sunilvuta9/Home-Work-1/tree/main
