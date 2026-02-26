# 🌳 Decision Tree (ID3 – Classification)

## 📌 Task Description
Implementation of a **Decision Tree Classifier using the ID3 algorithm** from scratch in Python.

The model builds the tree using **Entropy** and **Information Gain** to select the best feature at each split.

---

## 📁 Files Included
- 📓 **Decision_Tree_ID3.ipynb** → Python implementation of the ID3 algorithm  
- 📄 **Decision Tree.pdf** → Handwritten algorithm steps  

---

## ⚙️ Algorithm Steps

1️⃣ Input training dataset with features **X** and class labels **Y**  

2️⃣ If all samples belong to the same class  
   → Create a leaf node with that class and stop  

3️⃣ If no features remain  
   → Create a leaf node with the majority class  

4️⃣ For each feature, compute **Entropy**  

\[
Entropy(S) = -\sum p_i \log_2 p_i
\]

5️⃣ Compute **Information Gain**  

\[
IG = Entropy(parent) - \sum \frac{|subset|}{|parent|}Entropy(subset)
\]

6️⃣ Select the feature with highest information gain  

7️⃣ Split dataset based on selected feature  

8️⃣ Recursively repeat steps for each subset  

9️⃣ Stop when nodes are pure or no further splitting is possible  

🔟 Output the constructed decision tree  

---

## 🎯 Output
✔ Constructed decision tree model  
✔ Classification predictions for input data  
✔ Tree visualization using Matplotlib  

---

## 👨‍💻 Author
**Rishav Kumar Shrivastava**  
Machine Learning Lab Task Submission
