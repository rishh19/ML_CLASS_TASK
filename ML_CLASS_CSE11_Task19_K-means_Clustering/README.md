# 📊 K-Means Clustering

## 📌 Task Description

This task demonstrates **K-Means Clustering**, a widely used **unsupervised machine learning algorithm** for partitioning a dataset into **k distinct clusters**.

K-Means groups data points such that points within the same cluster are **more similar to each other** than to points in other clusters. The algorithm iteratively updates cluster assignments and centroids until the clustering structure stabilizes.

---

# 🧠 Concept

K-Means clustering represents each cluster using a **centroid**, which is the mean position of all points belonging to that cluster.

The algorithm repeatedly performs two main operations:

- Assign each data point to the **nearest centroid**
- Update each centroid as the **mean of the points in its cluster**

This process continues until the centroids **no longer change significantly**, indicating that the algorithm has converged.

---

# ⚙️ Mathematical Formulation

K-Means aims to minimize the **within-cluster sum of squared distances (WCSS)**, defined as:

```
J = Σ Σ ||xᵢ − μⱼ||²
```

Where:

- **xᵢ** → data point  
- **μⱼ** → centroid of cluster *j*  
- **||xᵢ − μⱼ||²** → squared Euclidean distance between the data point and centroid  
- **k** → number of clusters  

The objective is to minimize the total distance between data points and their corresponding cluster centroids.

---

# 📊 Output

The K-Means algorithm produces:

- **Clusters of grouped data points**
- **Final centroid positions** representing each cluster

These centroids serve as the **representative centers of their clusters**.

---

# 📚 Applications

K-Means clustering is widely used in:

- Customer segmentation
- Image compression and segmentation
- Document clustering
- Market analysis
- Pattern recognition

---

# 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
