# ML_CLASS_CSE11_Task4
Uploaded Jupyter Notebook which contains the Linear Regression code in python without libraries.
# 🧮 Linear Regression from Scratch

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Math](https://img.shields.io/badge/Focus-Mathematics-orange?style=flat)

## 📌 Project Overview
This repository contains a raw Python implementation of **Simple Linear Regression**. Instead of using "black box" libraries like Scikit-Learn, this project solves for the **Slope ($m$)** and **Intercept ($b$)** using two fundamental mathematical approaches:
1.  **The Summation Method** (Algebraic formula)
2.  **The Mean Method** (Statistical deviations)

This demonstrates the core logic behind how regression models actually "learn" from data.

## 📂 Dataset
The model is trained on the following small sample dataset:

| X (Independent) | Y (Dependent) |
| :---: | :---: |
| 11 | 2 |
| 13 | 5 |
| 4 | 8 |
| 10 | 7 |
| 11 | 3 |
| 2 | 20 |

## ⚙️ Methods Implemented

### 1. The Summation Method
Calculates the slope and intercept using direct summations of $X$ and $Y$ terms.
* **Formula for Slope ($m$):**
    $$m = \frac{n(\sum xy) - (\sum x)(\sum y)}{n(\sum x^2) - (\sum x)^2}$$
* **Formula for Intercept ($b$):**
    $$b = \frac{\sum y - m(\sum x)}{n}$$

### 2. The Mean Method
Calculates the slope based on the deviations from the means ($\bar{x}, \bar{y}$).
* **Formula for Slope ($m$):**
    $$m = \frac{\sum(x - \bar{x})(y - \bar{y})}{\sum(x - \bar{x})^2}$$
* **Formula for Intercept ($b$):**
    $$b = \bar{y} - m\bar{x}$$

## 📊 Results
Both methods yield identical results, verifying the mathematical accuracy of the code.

| Parameter | Calculated Value |
| :--- | :--- |
| **Slope ($m$)** | `-1.2359` |
| **Intercept ($b$)** | `18.0051` |
| **Prediction (for X=15)** | `-0.5333` |

## 🛠️ Requirements
* **Python 3.x**
* *(No external libraries required. Uses standard Python lists and loops.)*

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/Linear-Regression-From-Scratch-Python.git](https://github.com/YOUR-USERNAME/Linear-Regression-From-Scratch-Python.git)
    ```
2.  **Run the script:**
    ```bash
    python main.py
    ```

## 📜 License
This project is open-source and available for educational purposes.
