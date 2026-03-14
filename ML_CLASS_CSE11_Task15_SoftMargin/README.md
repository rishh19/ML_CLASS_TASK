# ⚖️ Soft Margin Support Vector Machine (SVM)

## 📌 Task Description
Implementation of **Soft Margin Support Vector Machine** for binary classification using Python.

Soft Margin SVM allows some misclassification and introduces a regularization parameter **C** to balance margin maximization and classification error.

---

## 📁 Files Included
- **SoftMargin_SVM.ipynb** → Python implementation of Soft Margin SVM


---

## ⚙️ Algorithm Overview

1. Input training dataset with feature vectors \(x_i\) and labels \(y_i\).
2. Initialize weight vector \(w\) and bias \(b\).
3. Define regularization parameter \(C\).
4. Compute decision function:

   f(x) = w·x + b

5. Check margin condition:

   y_i (w·x_i + b) ≥ 1

6. If satisfied, update weights using regularization term.
7. Otherwise update weights and bias using hinge loss.
8. Repeat updates until convergence.

---

## 🎯 Output
- Optimal weight vector **w**
- Bias **b**
- Decision boundary separating classes with maximum soft margin

---

## 👨‍💻 Author
**Rishav Kumar Shrivastava**  
Machine Learning Lab Tasks
