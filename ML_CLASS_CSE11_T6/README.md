# ML_CLASS_CSE11_Task6
A pure Python implementation of Linear Regression using Gradient Descent, built from scratch without using machine learning libraries like Scikit-Learn.

# 📉 Gradient Descent Step-by-Step

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Math](https://img.shields.io/badge/Focus-Mathematics-orange?style=flat)
![Status](https://img.shields.io/badge/Status-Educational-purple)

## 📌 Project Overview
This project provides a clear, manual implementation of **Gradient Descent** for Linear Regression.

Instead of using a "black box" library to train a model, this script performs a **single iteration** of the optimization loop. It prints a step-by-step table showing how predictions are made, how errors are calculated, and how the model parameters (slope and intercept) are updated using the learning rate.

## ⚙️ The Mathematics Used
The script implements the **Batch Gradient Descent** update rule manually:

### 1. Prediction
The model predicts $y$ using the linear equation:
$$y_{pred} = b_0 + b_1x$$

### 2. Error Calculation
For each data point, we calculate the difference (residual):
$$Error = y_{pred} - y_{actual}$$

### 3. Gradient Calculation
The code sums the gradients across all data points:
* **Gradient for Intercept ($b_0$):** $\sum (Error)$
* **Gradient for Slope ($b_1$):** $\sum (Error \times x)$

### 4. Parameter Update Rule
The weights are updated using a Learning Rate ($\alpha = 0.01$):
$$b_{new} = b_{old} - (\alpha \times Gradient)$$

## 📊 Example Output
The script generates a detailed table for the first iteration.

**Input Data:**
* **X:** `[1.0, 2.0, 3.0, 4.0, 5.0]`
* **Y:** `[6.0, 4.0, 3.0, 3.0, 6.0]`
* **Initial Params:** $b_0=1.0, b_1=1.0, \alpha=0.01$

**Console Output:**
```text
Initial Line: y = 1.0 + 1.0x

--- Calculation Step-by-Step ---
X     Y_act    Y_pred   Error    Error*X 
1.0   6.0      2.00     -4.00    -4.00   
2.0   4.0      3.00     -1.00    -2.00   
3.0   3.0      4.00     1.00     3.00    
4.0   3.0      5.00     2.00     8.00    
5.0   6.0      6.00     0.00     0.00    
-------------------------------------
Gradient for b_0 (Sum Error):    -2.0
Gradient for b_1 (Sum Error * X): 5.0

Final Result
Updated Intercept (b_0): 1.02
Updated Slope (b_1):     0.95
New Line Equation: y = 1.02 + 0.95x
