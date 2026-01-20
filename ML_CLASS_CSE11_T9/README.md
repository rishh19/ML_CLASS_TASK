## 📂 KNN Classification (From Scratch)

### 📝 Description
This notebook demonstrates the mathematical implementation of **K-Nearest Neighbors (KNN)** without relying on pre-built machine learning model classes. It builds the algorithm logic entirely using `NumPy` to understand the underlying mechanics of distance-based classification.

### 🔧 Key Features
- **Custom Algorithm:** Implements a `KNN_Scratch` class with:
  - Euclidean Distance calculation (`sqrt(sum(diff^2))`).
  - Neighbor sorting and Majority Voting.
- **Manual Metrics:** explicitly calculates True Positives (TP), False Positives (FP), True Negatives (TN), and False Negatives (FN) to derive Precision, Recall, Specificity, and NPV.
- **Visualization:** Plots the manually generated Confusion Matrix using Seaborn.

### 📦 Dependencies
- `pandas` (for data loading)
- `numpy` (for matrix operations)
- `matplotlib` & `seaborn` (for plotting graphs only)
