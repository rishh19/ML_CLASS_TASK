# 🧠 Neural Network – AND Gate

## 📌 Task Description

This task implements a simple neural network to learn the **AND gate logic** using Python.

The network uses sigmoid activation and gradient descent for training.

---

## 📁 Files Included

- 📓 **AND_NN.ipynb** → Jupyter Notebook implementation  
- 📄 **AND_NN_Algorithm.pdf** → Handwritten algorithm steps  

---

## 🧠 Model Overview

The neural network consists of:

- Input layer (2 neurons)
- Output layer (1 neuron)

It performs binary classification for AND logic.

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

$$
L = \frac{1}{n} \sum (y - \hat{y})^2
$$

---

## 🔁 Training Process

1. Initialize weights randomly  
2. Perform forward propagation  
3. Compute error  
4. Update weights using gradient descent  
5. Repeat for multiple epochs  

---

## 🎯 Output

- Predicted outputs for AND gate  
- Training loss graph  

---

## 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Lab Tasks