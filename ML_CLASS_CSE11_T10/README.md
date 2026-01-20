# ML_CLASS_CSE11_Task10Fish-Species-Weight-Prediction
A Machine Learning assignment analyzing the Fish Market dataset. Implements Classification models to predict fish species and Regression models to predict fish weight, comparing performance using Accuracy, R2 Score, and MAE.
# Fish Species and Weight Prediction 🐟

## Project Overview
This project applies **Machine Learning** techniques to the Fish Market dataset. It performs two distinct tasks:
1.  **Classification:** Predicting the species of a fish based on its physical measurements.
2.  **Regression:** Predicting the weight of a fish based on its dimensions and species.

## Dataset
The dataset used is the **Fish Market Dataset**.
* **Source:** [YBI Foundation / Kaggle](https://raw.githubusercontent.com/YBIFoundation/Dataset/main/Fish.csv)
* **Features:** Length1, Length2, Length3, Height, Width.
* **Targets:** Species (Classification), Weight (Regression).

## Models Implemented

### 1. Classification (Target: Species)
We compared the following models to classify fish into 7 species (Perch, Bream, Roach, etc.):
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes

**Metrics Used:** Accuracy, Precision, Recall, F1-Score.

### 2. Regression (Target: Weight)
We compared the following models to predict the continuous weight variable:
* Linear Regression
* Ridge & Lasso Regression
* Decision Tree Regressor
* Random Forest Regressor
* Support Vector Regressor (SVR)
* KNN Regressor

**Metrics Used:** R2 Score, Mean Absolute Error (MAE), Mean Squared Error (MSE).

## Results
The project includes a comparative analysis of all models. 
* **Visualizations:** Bar charts are generated to visually compare Accuracy (for Classification) and R2 Score/MAE (for Regression).
* **Best Performers:** The `Random Forest` and `Decision Tree` models generally performed best for this dataset due to the non-linear relationships in fish dimensions.

## How to Run
1.  Clone this repository.
2.  Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Run the Jupyter Notebook.
