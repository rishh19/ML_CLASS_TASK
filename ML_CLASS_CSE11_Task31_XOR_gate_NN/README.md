# 🧠 Neural Network – XOR Gate

## 📌 Task Description

This task implements a neural network to learn the **XOR gate logic**.

Unlike AND and OR, XOR is **not linearly separable**, so a hidden layer is required.

---

## 📁 Files Included

- 📓 **XOR_NN.ipynb** → Jupyter Notebook implementation  
- 📄 **XOR_NN_Algorithm.pdf** → Handwritten algorithm  

---

## 🧠 Model Overview

The neural network consists of:

- Input layer (2 neurons)
- Hidden layer (2 neurons)
- Output layer (1 neuron)

---

## ⚙️ Mathematical Formulation

### Activation Function

σ(x) = 1 / (1 + e^(-x))

---

### Model Equation

y = σ(w·x + b)

---

### Loss Function

L = (1/n) Σ (y - ŷ)²

---

## 🔁 Training Process

1. Initialize weights  
2. Forward propagation  
3. Compute error  
4. Backpropagation  
5. Update weights  
6. Repeat  

---

## 🎯 Output

- XOR predictions  
- Training loss graph  

---

## 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
