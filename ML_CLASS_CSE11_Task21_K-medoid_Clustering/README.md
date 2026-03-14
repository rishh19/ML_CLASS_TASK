# 📊 K-Medoids Clustering

## 📌 Task Description

This task demonstrates the implementation of **K-Medoids Clustering**, an unsupervised machine learning algorithm used to partition a dataset into **k clusters**.

Unlike **K-Means**, which represents clusters using the **mean of points**, K-Medoids chooses **actual data points as cluster centers (medoids)**.  
Because medoids are real observations, the algorithm is generally **more robust to noise and outliers**.

---

# 🧠 Concept

K-Medoids clustering works by selecting representative data points (medoids) that minimize the total distance between the medoid and all other points within the cluster.

The algorithm iteratively:

- Assigns data points to the nearest medoid
- Updates medoids based on cluster distances
- Repeats until the medoids stabilize

---

# ⚙️ Mathematical Formulation

K-Medoids minimizes the following objective function:

```
J = Σ Σ d(xᵢ, mⱼ)
```

Where:

- **xᵢ** → data point  
- **mⱼ** → medoid of cluster j  
- **d(xᵢ, mⱼ)** → distance between data point and medoid  
- **k** → number of clusters  

A common distance metric used is **Euclidean distance**:

```
d(x, m) = √ Σ (xᵢ − mᵢ)²
```

---

# 🎯 Output

The algorithm produces:

- **Clustered dataset**
- **Final medoids representing each cluster**

These medoids act as **representative points of their clusters**.

---

# 📚 Applications

K-Medoids clustering is commonly used in:

- Data clustering with noisy datasets
- Bioinformatics and medical data analysis
- Market segmentation
- Spatial data analysis

---

# 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
