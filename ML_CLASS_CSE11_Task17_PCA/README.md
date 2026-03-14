# 📊 Principal Component Analysis (PCA)

## 📌 Task Description
This task implements **Principal Component Analysis (PCA)** from scratch using Python.

PCA is a **dimensionality reduction technique** used to transform a dataset with many correlated features into a smaller set of **uncorrelated variables called principal components**, while preserving maximum variance in the data.

---

## 📁 Files in this Task

- **PCA.ipynb** → Jupyter Notebook implementation of PCA
- **PCA_Algorithm.pdf** → Handwritten algorithm (if required by instructor)

---

## 🧠 Concept of PCA

PCA projects the original data onto a new coordinate system such that:

- The **first principal component** captures the maximum variance.
- The **second principal component** captures the next highest variance.
- Each component is **orthogonal** to the previous one.

This helps in reducing dimensionality while keeping important information.

---

## ⚙️ Mathematical Formulation

### 1️⃣ Mean Centering

Compute the mean of each feature:

\[
\mu = \frac{1}{n} \sum_{i=1}^{n} x_i
\]

Center the dataset:

\[
X_{centered} = X - \mu
\]

---

### 2️⃣ Covariance Matrix

Compute the covariance matrix:

\[
C = \frac{1}{n-1} X_{centered}^T X_{centered}
\]

---

### 3️⃣ Eigen Decomposition

Find eigenvalues and eigenvectors:

\[
C v = \lambda v
\]

Where:

- \(v\) = eigenvector  
- \(\lambda\) = eigenvalue  

---

### 4️⃣ Sort Eigenvalues

Sort eigenvalues in descending order:

\[
\lambda_1 \ge \lambda_2 \ge ... \ge \lambda_n
\]

---

### 5️⃣ Select Principal Components

Choose the top **k eigenvectors** corresponding to the largest eigenvalues.

\[
W = [v_1, v_2, ..., v_k]
\]

---

### 6️⃣ Transform the Dataset

Project the data onto the new feature space:

\[
Z = X_{centered} W
\]

Where:

- \(Z\) = reduced dimensional dataset

---

## 🎯 Output

- Reduced dimensional dataset
- Principal components capturing maximum variance
- Visualization of transformed data

---

## 📚 Applications of PCA

- Data compression
- Noise reduction
- Feature extraction
- Visualization of high-dimensional datasets

---

## 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Lab Tasks
