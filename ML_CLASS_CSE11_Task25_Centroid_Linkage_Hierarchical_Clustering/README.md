# 📊 Centroid Linkage Hierarchical Clustering

## 📌 Task Description

This task demonstrates **Centroid Linkage Hierarchical Clustering**, an unsupervised machine learning technique used to group similar data points into a hierarchical structure.

Hierarchical clustering builds a **tree-like representation called a dendrogram**, which shows how clusters are progressively merged based on a linkage criterion.

In **centroid linkage**, clusters are merged according to the **distance between their centroids**, where the centroid represents the **mean position of all data points within a cluster**.

---

# 🧠 Concept

In hierarchical clustering, each data point initially forms its own cluster.  
Clusters are then iteratively merged based on a defined linkage rule until all data points belong to a single cluster.

Centroid linkage determines cluster similarity by computing the **distance between the centroids of clusters**. After merging two clusters, a **new centroid is calculated** for the combined cluster.

---

# ⚙️ Mathematical Formulation

### Centroid of a Cluster

The centroid of a cluster is calculated as the mean of its data points:

```
C = (1 / n) Σ xᵢ
```

Where:

- **C** → centroid of the cluster  
- **n** → number of data points in the cluster  
- **xᵢ** → data points belonging to the cluster  

### Distance Between Two Clusters

The distance between clusters **A** and **B** is defined as the distance between their centroids:

```
D(A, B) = ||C_A − C_B||
```

Where:

- **C_A** → centroid of cluster A  
- **C_B** → centroid of cluster B  
- **|| · ||** → Euclidean distance between the centroids  

---

# 📊 Output

The clustering process produces:

- A **hierarchical cluster structure**
- A **dendrogram visualization** showing how clusters merge at different distance levels

The dendrogram helps determine the **optimal number of clusters** by selecting an appropriate distance threshold.

---

# 📚 Applications

Centroid Linkage Hierarchical Clustering is commonly used in:

- Data exploration and pattern discovery
- Image segmentation
- Document clustering
- Market segmentation
- Scientific data analysis

---

# 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
