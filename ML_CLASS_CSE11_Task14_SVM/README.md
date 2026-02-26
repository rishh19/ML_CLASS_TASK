# ⚖️ Support Vector Machine (Linear Classification)

## 📌 Task Description
Implementation of a **Linear Support Vector Machine (SVM)** from scratch using Python in Jupyter Notebook.

The model finds the optimal separating hyperplane by **maximizing the margin** between two classes.

---

## 📁 Files Included
- 📓 **SVM_Linear.ipynb** → Python implementation of Linear SVM from scratch  
- 📄 **Support Vector Machine (Linear Classification).pdf** → Handwritten algorithm steps  

---

## ⚙️ Algorithm Steps

1️⃣ Input training dataset \((x_i, y_i)\) where  
\[
y_i \in \{-1, +1\}
\]

2️⃣ Initialize weight vector **w** and bias **b**

3️⃣ Define objective function to maximize margin  

\[
\text{Minimize } \frac{1}{2} ||w||^2
\]

Subject to:

\[
y_i (w \cdot x_i + b) \ge 1
\]

4️⃣ Optimize parameters using gradient-based updates  
   (hinge loss + regularization)

5️⃣ Obtain optimal values of **w** and **b**

6️⃣ Construct decision function  

\[
f(x) = w \cdot x + b
\]

7️⃣ Classify a new sample:

- If \(f(x) \ge 0\) → assign class **+1**  
- Otherwise → assign class **−1**

---

## 🎯 Output
✔ Maximum-margin separating hyperplane  
✔ Binary classification prediction  
✔ Decision boundary visualization  

---

## 👨‍💻 Author
**Rishav Kumar Shrivastava**  
Machine Learning Lab Task Submission
