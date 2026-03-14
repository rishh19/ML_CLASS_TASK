# ⚖️ Hard Margin Support Vector Machine (SVM)

## 📌 Task Description
Implementation of **Hard Margin Support Vector Machine (SVM)** for binary classification using Python.

Hard Margin SVM assumes that the dataset is **perfectly linearly separable**, meaning there is a hyperplane that can separate the two classes without any classification error.

The goal is to find the **optimal separating hyperplane** that maximizes the margin between the two classes.

---

## 📁 Files Included

- **HardMargin_SVM.ipynb** → Python implementation of Hard Margin SVM
-  **HardMargin_SVM.pdf** → AAlgorithm steps


---

## ⚙️ Mathematical Formulation

Given training data:

\[
D = \{(x_i, y_i)\}_{i=1}^{n}
\]

where:

- \(x_i\) = feature vector  
- \(y_i \in \{-1, +1\}\) = class labels  

---

### Objective Function

Hard Margin SVM tries to minimize:

\[
\frac{1}{2} ||w||^2
\]

where:

- \(w\) = weight vector

---

### Subject to Constraint

\[
y_i (w \cdot x_i + b) \ge 1
\]

where:

- \(b\) = bias
- \(w \cdot x_i\) = dot product

---

## ⚙️ Algorithm Steps

1. Input training dataset with features \(x_i\) and labels \(y_i\).
2. Initialize weight vector \(w\) and bias \(b\).
3. For each training sample compute:

\[
f(x) = w \cdot x + b
\]

4. Check margin condition:

\[
y_i (w \cdot x_i + b) \ge 1
\]

5. If condition is satisfied:

\[
w = w - \alpha (2w)
\]

6. Otherwise update:

\[
w = w - \alpha (2w - y_i x_i)
\]

\[
b = b - \alpha y_i
\]

7. Repeat updates until convergence.

---

## 📊 Decision Function

The classifier predicts using:

\[
f(x) = w \cdot x + b
\]

Prediction rule:

- If \(f(x) \ge 0\) → **Class +1**
- If \(f(x) < 0\) → **Class −1**

---

## 🎯 Output

- Optimal weight vector **w**
- Bias **b**
- Maximum margin separating hyperplane

---

## 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
