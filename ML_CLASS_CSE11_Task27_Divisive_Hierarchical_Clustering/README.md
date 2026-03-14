# 📊 Divisive Hierarchical Clustering

## 📌 Task Description

This task demonstrates **Divisive Hierarchical Clustering**, an unsupervised machine learning technique that follows a **top-down approach** to cluster formation.

Unlike agglomerative hierarchical clustering, which merges smaller clusters, divisive clustering starts with **all data points grouped into a single cluster** and repeatedly **splits clusters into smaller sub-clusters** until a desired clustering structure is obtained.

The result is a **hierarchical representation of clusters**, which can be visualized to understand how the dataset is progressively divided.

---

# 🧠 Concept

Divisive hierarchical clustering begins with the entire dataset treated as one cluster.  
At each stage, the algorithm identifies a cluster and **splits it into smaller clusters** based on a distance measure or clustering criterion.

This process continues recursively, forming a **hierarchical tree structure** that represents how clusters are divided at different levels.

---

# ⚙️ Mathematical Concept

Distances between data points are commonly measured using **Euclidean distance**, defined as:

```
d(x, y) = √ Σ (xᵢ − yᵢ)²
```

Where:

- **x, y** → two data points  
- **xᵢ, yᵢ** → feature values of the data points  
- **d(x, y)** → Euclidean distance between the points  

This distance metric helps determine how clusters should be **split during the clustering process**.

---

# 📊 Output

The clustering process produces:

- A **hierarchical cluster structure**
- A **visual representation of clusters** showing how the dataset is progressively divided

This hierarchical structure helps analyze the **relationships between data points at multiple levels of granularity**.

---

# 📚 Applications

Divisive Hierarchical Clustering is commonly used in:

- Document and text clustering
- Image segmentation
- Bioinformatics and gene analysis
- Customer segmentation
- Exploratory data analysis

---

# 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
