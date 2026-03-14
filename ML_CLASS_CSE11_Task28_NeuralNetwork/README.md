# 🧠 Artificial Neural Network (XOR Problem)

## 📌 Task Description

This task demonstrates the implementation of a **Feedforward Artificial Neural Network (ANN)** using **Python and NumPy**.

The network is trained to solve the **XOR classification problem**, a classic example used to show that a **single-layer perceptron cannot model non-linearly separable data**.  
By introducing a **hidden layer**, the neural network learns the XOR relationship using **forward propagation and backpropagation**.

---

## 🏗 Neural Network Architecture

The neural network used in this task consists of:

- **Input Layer** → 2 neurons (two input features)  
- **Hidden Layer** → 2 neurons  
- **Output Layer** → 1 neuron (binary output)

Activation Function used:

- **Sigmoid Function**

This architecture allows the model to capture the **non-linear decision boundary required for XOR classification**.

---

## ⚙️ Mathematical Formulation

### Sigmoid Activation Function

```
σ(x) = 1 / (1 + e^(−x))
```

The sigmoid function maps any input value to a range between **0 and 1**, making it suitable for **binary classification problems**.

---

### Neuron Output

Each neuron computes a weighted sum of inputs followed by an activation function:

```
y = σ(w · x + b)
```

Where:

- **w** → weight vector  
- **x** → input vector  
- **b** → bias  
- **σ** → sigmoid activation function  

---

### Loss Function

The network is trained using **Mean Squared Error (MSE)**:

```
L = (1 / n) Σ (y − ŷ)²
```

Where:

- **y** → true output  
- **ŷ** → predicted output  
- **n** → number of samples  

The objective of training is to **minimize this loss function**.

---

## 🔁 Training Process

During training, the neural network performs the following operations:

- **Forward Propagation**  
  Inputs pass through the network to generate predictions.

- **Error Computation**  
  The difference between predicted and actual values is calculated.

- **Backpropagation**  
  Gradients are computed and propagated backward through the network.

- **Weight Update**  
  Weights and biases are updated using **gradient descent**.

This process is repeated for multiple **epochs** until the model converges.

---

## 📊 Visualization

The notebook includes visualizations to better understand the learning process:

- **Training Loss Curve** showing how the error decreases during training
- **Decision Boundary Plot** illustrating how the neural network separates XOR classes

These visualizations help demonstrate how the neural network learns a **non-linear classification boundary**.

---

## 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks