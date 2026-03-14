# 📊 Average Linkage Hierarchical Clustering

## 📌 Task Description

This task demonstrates **Average Linkage Hierarchical Clustering**, an unsupervised machine learning technique used to group similar data points into a hierarchical structure of clusters.

Hierarchical clustering constructs a **tree-like representation called a dendrogram**, which illustrates how clusters are progressively merged based on a specific linkage criterion.

In **average linkage**, the distance between two clusters is calculated as the **average distance between all pairs of points belonging to the two clusters**.

---

# 🧠 Concept

Hierarchical clustering begins by treating **each data point as its own cluster**.  
Clusters are then iteratively merged based on a linkage rule until all data points belong to a single cluster.

Average linkage considers **all pairwise distances between points in two clusters** and computes their average. This approach provides a balance between **single linkage** (minimum distance) and **complete linkage** (maximum distance).

---

# ⚙️ Mathematical Formulation

The distance between two clusters **A** and **B** is defined as:

```
D(A, B) = (1 / (|A| × |B|)) Σ Σ d(x, y)
```

Where:

- **A** → first cluster  
- **B** → second cluster  
- **|A|, |B|** → number of points in clusters A and B  
- **x ∈ A** → data point from cluster A  
- **y ∈ B** → data point from cluster B  
- **d(x, y)** → distance between the two points (commonly Euclidean distance)

This formula calculates the **average pairwise distance between all points in the two clusters**.

---

# 📊 Output

The clustering process produces:

- A **hierarchical cluster structure**
- A **dendrogram visualization** that shows how clusters merge at different distance levels

The dendrogram helps determine the **optimal number of clusters** by selecting a suitable distance threshold.

---

# 📚 Applications

Average Linkage Hierarchical Clustering is commonly used in:

- Bioinformatics and gene expression analysis
- Document and text clustering
- Image segmentation
- Market segmentation
- Exploratory data analysis

---

# 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Lab Tasks