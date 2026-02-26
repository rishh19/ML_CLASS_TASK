# ML_CLASS_CSE11_Task7
A simple Python implementation of the K-Nearest Neighbors (KNN) algorithm to predict loan default using age and loan amount. Built for beginners and academic projects without using external libraries.
# KNN Loan Default Prediction (Python)

A beginner-friendly implementation of the **K-Nearest Neighbors (KNN)** algorithm in Python to predict whether a customer will default on a loan based on **Age** and **Loan Amount**.

---

## Features
- Simple KNN from scratch  
- Euclidean distance  
- 2-class classification (Yes / No)  
- User input for new customer  
- No external libraries  

---

## Dataset
The model is trained on 11 customers with:
- Age  
- Loan Amount  
- Default Status  

Dataset is embedded inside the code.

---

## How It Works
1. Takes new customer details  
2. Calculates distance from all customers  
3. Sorts by distance  
4. Selects k nearest neighbors  
5. Majority voting gives prediction  

---

## How to Run
```bash
python knn.py

Enter NEW customer details
Enter Age: 36
Enter Loan Amount: 36000
Enter value of k: 3

Nearest neighbors: [[1500.2, 'No'], [1800.5, 'Yes'], [2100.7, 'No']]
Prediction: NEW customer will NOT DEFAULT
---
