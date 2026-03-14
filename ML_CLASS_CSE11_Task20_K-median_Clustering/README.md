# 📊 K-Medians Clustering

## 📌 Task Description

This task demonstrates the implementation of **K-Medians Clustering**, an unsupervised machine learning algorithm used to partition a dataset into **k clusters**.

Unlike **K-Means**, which uses the **mean** of cluster points to update centroids, **K-Medians** uses the **median**.  
It typically relies on the **Manhattan distance (L1 distance)**, making it more robust to **outliers and noisy data**.

---

# 🧠 Concept

K-Medians clustering groups similar data points by minimizing the distance between each data point and the **median of its assigned cluster**.

The algorithm repeatedly:

- Assigns data points to the nearest cluster
- Updates cluster centers using the **median of the cluster points**

This process continues until the cluster centers **no longer change significantly**.

---

# ⚙️ Mathematical Formulation

K-Medians minimizes the following objective function:

```
J = Σ Σ ||xᵢ − mⱼ||₁
```

Where:

- **xᵢ** → data point  
- **mⱼ** → median of cluster j  
- **|| · ||₁** → Manhattan (L1) distance  
- **k** → number of clusters  

The Manhattan distance between two points is defined as:

```
d(x, m) = Σ |xᵢ − mᵢ|
```

---

# 🎯 Output

The algorithm produces:

- **Clustered data points**
- **Final cluster medians**

These medians represent the **center of each cluster**.

---

# 📚 Applications

K-Medians clustering is useful in:

- Data segmentation
- Image processing
- Robust clustering with outliers
- Spatial data analysis

---

# 👨‍💻 Author

**Rishav Kumar Shrivastava**  
Machine Learning Class Tasks
