# 📊 Single Linkage Hierarchical Clustering

## 📌 Task Description

This task demonstrates **Single Linkage Hierarchical Clustering**, an unsupervised machine learning technique used to group similar data points based on their distances.

Hierarchical clustering creates a **tree-like structure called a dendrogram**, which shows how clusters are formed by progressively merging the closest data points or clusters.

Single linkage specifically measures the distance between clusters using the **minimum distance between any two points in the clusters**.

---

# 🧠 Concept

In hierarchical clustering, each data point initially forms its own cluster.  
Clusters are then **iteratively merged** based on a linkage criterion until all data points belong to a single cluster.

In **single linkage**, the distance between two clusters is defined as the **minimum distance between any pair of points**, where each point comes from one of the two clusters.

---

# ⚙️ Mathematical Formulation

The distance between two clusters **A** and **B** is defined as:

```
D(A, B) = min d(x, y)
```

Where:

- **A** → first cluster  
- **B** → second cluster  
- **x ∈ A** → data point from cluster A  
- **y ∈ B** → data point from cluster B  
- **d(x, y)** → distance between the two points (commonly Euclidean distance)

---

# 📊 Output

The clustering process produces:

- A **hierarchical cluster structure**
- A **dendrogram visualization** showing how clusters are merged at different distance levels

The dendrogram helps identify the **optimal number of clusters** by cutting the tree at a specific distance threshold.

---

# 📚 Applications

Single Linkage Hierarchical Clustering is commonly used in:

- Bioinformatics and gene analysis
- Document clustering
- Image segmentation
- Exploratory data analysis

---

# 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
