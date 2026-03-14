# 📊 DBSCAN Clustering

## 📌 Task Description

This task demonstrates **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**, an unsupervised machine learning algorithm used to identify clusters based on the **density of data points**.

Unlike centroid-based clustering methods such as **K-Means**, DBSCAN does not require specifying the number of clusters in advance. Instead, it groups together points that lie in **high-density regions** and labels points in **low-density regions as noise or outliers**.

---

# 🧠 Concept

DBSCAN forms clusters by analyzing the **local density of points**. Points that are close to each other form dense regions, which are identified as clusters.

The algorithm categorizes points into three types:

- **Core Points** → points that have a sufficient number of neighbors within a specified radius  
- **Border Points** → points that lie within the neighborhood of a core point but have fewer neighbors  
- **Noise Points** → points that do not belong to any cluster

This approach allows DBSCAN to detect clusters of **arbitrary shapes** and handle **outliers effectively**.

---

# ⚙️ Key Parameters

DBSCAN relies on two important parameters:

- **ε (epsilon)** → the radius that defines the neighborhood around a point  
- **MinPts** → the minimum number of points required to form a dense region

These parameters determine how clusters are detected within the dataset.

---

# 🔢 Mathematical Formulation

A point **p** is considered a **core point** if the number of points within its ε-neighborhood satisfies the condition:

```
|Nε(p)| ≥ MinPts
```

Where:

- **Nε(p)** → set of points within distance **ε** of point **p**  
- **|Nε(p)|** → number of points in the neighborhood  
- **MinPts** → minimum number of points required to form a dense region

This condition ensures that clusters are formed only in **regions with sufficient data density**.

---

# 📊 Output

The DBSCAN algorithm produces:

- **Clusters of densely connected data points**
- **Noise points (outliers)** that do not belong to any cluster

Clusters may have **arbitrary shapes**, making DBSCAN suitable for complex datasets.

---

# 📚 Applications

DBSCAN is commonly used in:

- Spatial data analysis
- Anomaly detection
- Image segmentation
- Geographic data clustering
- Noise filtering in datasets

---

# 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
