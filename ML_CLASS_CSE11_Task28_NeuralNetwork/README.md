# 🧠 Basic Neural Network

## 📌 Task Description

This task implements a **basic neural network** for binary classification using Python and NumPy.

The model consists of a simple structure with:

- Input layer
- Output layer (no hidden layer)

It uses **sigmoid activation** and is trained using **gradient descent**.

---

## 📁 Files Included

- 📓 **BasicNN.ipynb** → Jupyter Notebook implementation  
- 📄 **BasicNN_Algorithm.pdf** → Handwritten algorithm steps  

---

## 🧠 Model Overview

The neural network learns a mapping between input features and output labels using weights and bias.

It performs:

- Forward propagation
- Error computation
- Backpropagation (weight update)

---

## ⚙️ Mathematical Formulation

### Activation Function

$$
\sigma(x) = \frac{1}{1 + e^{-x}}
$$

---

### Model Equation

$$
y = \sigma(w \cdot x + b)
$$

---

### Loss Function

Mean Squared Error:

$$
L = \frac{1}{n} \sum (y - \hat{y})^2
$$

---

## 🔁 Training Process

1. Initialize weights and bias randomly  
2. Perform forward propagation  
3. Compute prediction error  
4. Update weights using gradient descent  
5. Repeat for multiple epochs  

---

## 🎯 Output

- Predicted values for input data  
- Training loss curve  

---

## 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
