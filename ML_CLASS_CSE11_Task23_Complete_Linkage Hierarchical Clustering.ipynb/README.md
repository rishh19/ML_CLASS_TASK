# 📊 Complete Linkage Hierarchical Clustering

## 📌 Task Description

This task demonstrates **Complete Linkage Hierarchical Clustering**, an unsupervised machine learning technique used to group similar data points by building a hierarchical structure of clusters.

Hierarchical clustering produces a **tree-like representation called a dendrogram**, which illustrates how clusters are merged step-by-step based on a defined linkage criterion.

In **complete linkage**, the distance between two clusters is defined using the **maximum distance between any pair of points belonging to the two clusters**.

---

# 🧠 Concept

Hierarchical clustering begins by treating **each data point as an individual cluster**.  
Clusters are then progressively merged based on a linkage rule until all points belong to a single cluster.

Complete linkage focuses on the **farthest pair of points between clusters**, which generally results in **more compact and tightly bound clusters** compared to single linkage.

---

# ⚙️ Mathematical Formulation

The distance between two clusters **A** and **B** is defined as:

```
D(A, B) = max d(x, y)
```

Where:

- **A** → first cluster  
- **B** → second cluster  
- **x ∈ A** → data point from cluster A  
- **y ∈ B** → data point from cluster B  
- **d(x, y)** → distance between the two points (commonly Euclidean distance)

This formulation ensures that the **largest pairwise distance between clusters** determines the merging criterion.

---

# 📊 Output

The clustering process produces:

- A **hierarchical cluster structure**
- A **dendrogram visualization** showing how clusters merge at different distance levels

The dendrogram can be used to determine the **optimal number of clusters** by selecting an appropriate distance threshold.

---

# 📚 Applications

Complete Linkage Hierarchical Clustering is commonly used in:

- Bioinformatics and gene clustering
- Image segmentation
- Document clustering
- Market segmentation
- Exploratory data analysis

---

# 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
