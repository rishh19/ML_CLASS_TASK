# ML_CLASS_CSE11_Task5
Uploaded Jupyter Notebook for Multiple Linear Regression
# 📈 Multiple Linear Regression from Scratch

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Math](https://img.shields.io/badge/Focus-Mathematics-orange?style=flat)

## 📌 Project Overview
This repository contains a raw Python implementation of **Multiple Linear Regression** with two independent variables ($x_1, x_2$).

Instead of using libraries like `scikit-learn` or `numpy`, this script mathematically solves for the regression coefficients ($b_0, b_1, b_2$) using the **Least Squares Normal Equations**.

The model predicts $y$ based on the equation:
$$y = b_0 + b_1x_1 + b_2x_2$$

## ⚙️ How It Works
The script calculates the coefficients using the deviation method (solving the normal equations for 2 variables):

1.  **Calculate Means:** $\bar{x}_1, \bar{x}_2, \bar{y}$
2.  **Calculate Sums of Squares/Products of Deviations:**
    * $S_{11} = \sum(x_1 - \bar{x}_1)^2$
    * $S_{22} = \sum(x_2 - \bar{x}_2)^2$
    * $S_{12} = \sum(x_1 - \bar{x}_1)(x_2 - \bar{x}_2)$
    * $S_{1y} = \sum(x_1 - \bar{x}_1)(y - \bar{y})$
    * $S_{2y} = \sum(x_2 - \bar{x}_2)(y - \bar{y})$
3.  **Solve for Coefficients:**
    * $$b_1 = \frac{S_{22} S_{1y} - S_{12} S_{2y}}{S_{11} S_{22} - (S_{12})^2}$$
    * $$b_2 = \frac{S_{11} S_{2y} - S_{12} S_{1y}}{S_{11} S_{22} - (S_{12})^2}$$
    * $$b_0 = \bar{y} - b_1\bar{x}_1 - b_2\bar{x}_2$$

## 🛠️ Requirements
To run this code, you only need Python installed. No external libraries are required.
* **Python 3.x**
* **Standard Libraries:** `math` (optional, though basic arithmetic is used directly)

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/Multiple-Linear-Regression-From-Scratch.git](https://github.com/YOUR-USERNAME/Multiple-Linear-Regression-From-Scratch.git)
    cd Multiple-Linear-Regression-From-Scratch
    ```
2.  **Run the script:**
    ```bash
    python main.py
    ```
3.  **Enter Data:**
    The program will ask you to input the data manually.
    * First, enter the number of elements ($n$).
    * Then, enter values for $x_1$, $x_2$, and $y$ one by one as prompted.

## 📊 Example Output
```text
Enter the number of elements: 5
enter the x1 values:
10
12
...
enter the x2 values:
5
6
...
Enter y values:
100
120
...

b0 = -29.757383154144293
b1 = 0.11032880661014977
b2 = 50.18673852131021
