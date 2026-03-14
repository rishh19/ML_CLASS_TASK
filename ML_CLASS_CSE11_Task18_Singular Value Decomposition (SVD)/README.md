# 🔢 Singular Value Decomposition (SVD)

## 📌 Task Description

This task demonstrates the implementation of **Singular Value Decomposition (SVD)** using Python.

SVD is a **matrix factorization technique** that decomposes a matrix into three component matrices. It is widely used in **machine learning, signal processing, data compression, and recommendation systems**.

The decomposition helps reveal the **intrinsic structure of data** and is commonly used for **dimensionality reduction and noise filtering**.

---

# 📁 Files Included

| File | Description |
|-----|-------------|
| **SVD.ipynb** | Jupyter Notebook implementation of SVD |
| **SVD_Algorithm.pdf** | algorithm steps |

---

# 🧠 Concept of SVD

Singular Value Decomposition factorizes a matrix **A** into three matrices:

```
A = U Σ Vᵀ
```

Where:

- **U** → Matrix of **left singular vectors**
- **Σ** → **Diagonal matrix** containing singular values
- **Vᵀ** → Transpose of matrix containing **right singular vectors**

This decomposition allows the original matrix to be represented in terms of its **principal components and variance structure**.

---

# ⚙️ Mathematical Formulation

Given a matrix:

```
A ∈ R^(m × n)
```

SVD decomposes the matrix as:

```
A = U Σ Vᵀ
```

Where:

- **U ∈ R^(m × m)** → Orthogonal matrix containing left singular vectors  
- **Σ ∈ R^(m × n)** → Diagonal matrix containing singular values  
- **Vᵀ ∈ R^(n × n)** → Transpose of orthogonal matrix containing right singular vectors  

---

# 📊 Output

The SVD algorithm produces three matrices:

- **U** → Left singular vectors  
- **Σ** → Singular values matrix  
- **Vᵀ** → Right singular vectors  

These matrices can be multiplied together to **reconstruct the original matrix A**.

```
A = U Σ Vᵀ
```

---

# 📚 Applications of SVD

Singular Value Decomposition is widely used in:

- Dimensionality Reduction (PCA related techniques)
- Image Compression
- Recommendation Systems
- Latent Semantic Analysis (LSA)
- Noise Reduction in Data

---

# 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
