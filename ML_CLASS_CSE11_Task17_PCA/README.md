# 📊 Principal Component Analysis (PCA)

## 📌 Task Description
Implementation of **Principal Component Analysis (PCA)** from scratch using Python.

PCA is a dimensionality reduction technique used to transform high-dimensional data into a smaller number of principal components while preserving maximum variance.

---

## 📁 Files Included

- **PCA.ipynb** → Python implementation of PCA
- **PCA_Algorithm.pdf** → Handwritten algorithm steps

---

## ⚙️ Mathematical Formulation

Given dataset:

\[
X = \{x_1, x_2, ..., x_n\}
\]

Where each \(x_i\) is a feature vector.

---

### Step 1: Mean Center Data

\[
X_{centered} = X - \mu
\]

where \( \mu \) is the mean vector.

---

### Step 2: Compute Covariance Matrix

\[
C = \frac{1}{n-1} X^T X
\]

---

### Step 3: Eigen Decomposition

\[
C v = \lambda v
\]

where:

- \(v\) = eigenvector  
- \(\lambda\) = eigenvalue

---

### Step 4: Sort Eigenvectors

Eigenvectors are sorted according to decreasing eigenvalues.

---

### Step 5: Select Principal Components

Choose the top **k eigenvectors**.

---

### Step 6: Transform Data

\[
Z = X_{centered} W
\]

where \(W\) contains the selected eigenvectors.

---

## 🎯 Output

- Reduced dimensional dataset
- Principal components representing maximum variance

---

## 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Lab Tasks