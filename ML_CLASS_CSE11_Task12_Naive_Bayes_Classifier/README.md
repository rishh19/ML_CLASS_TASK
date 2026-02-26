# 🧠 Naive Bayes Classifier

## 📌 Task Description
Implementation of the **Naive Bayes Classifier** from scratch using Python in Jupyter Notebook.

This model applies **Bayes Theorem** assuming feature independence to perform classification.

---

## 📁 Files Included
- 📓 **Naive Bayes Classifier.ipynb** → Python implementation of the classifier  
- 📄 **Naive Bayes Classifier.pdf** → Handwritten algorithm steps  

---

## ⚙️ Algorithm Steps

1️⃣ Input training dataset with features **X** and labels **Y**  
2️⃣ Compute prior probability for each class  
\[
P(C_k) = \frac{\text{No. of samples in class } C_k}{\text{Total samples}}
\]

3️⃣ For a new sample, compute posterior probability using Bayes Theorem  

\[
P(C_k | X) \propto P(C_k)\prod P(x_i | C_k)
\]

4️⃣ Ignore denominator since it is constant for all classes  
5️⃣ For each feature and class, compute likelihood  
   - For continuous data → use **Gaussian distribution**

6️⃣ Assign the class with highest posterior probability  
7️⃣ Output predicted class  

---

## 🎯 Output
✔ Predicted class label for new input data  
✔ Probabilistic classification using Naive Bayes  

---

## 👨‍💻 Author
**Rishav Kumar Shrivastava**  
Machine Learning Lab Task Submission
