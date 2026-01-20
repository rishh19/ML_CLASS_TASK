# 📊 Student Data Analysis using Pandas

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Library](https://img.shields.io/badge/Library-Pandas-150458?style=flat&logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Project Overview
This project demonstrates the fundamentals of **Data Manipulation** and **Exploratory Data Analysis (EDA)** using the Python `pandas` library.

The script loads a dataset of student records (`Student.csv`) and performs basic operations to understand the data structure, data types, and statistical properties.

## 📂 Dataset
The project uses a sample dataset (`Student.csv`) containing **20 records** with the following attributes:

| Column Name | Description | Data Type |
| :--- | :--- | :--- |
| **Stud_Id** | Unique identifier for each student | `int64` |
| **Name** | Name of the student | `object` (String) |
| **Age** | Age of the student | `int64` |
| **RollNo** | Roll number assigned to the student | `int64` |
| **Section** | Class section (A-T) | `object` (String) |

## ⚙️ Features & Operations
The notebook performs the following key operations:

1.  **Data Loading:** Reads the raw CSV file into a Pandas DataFrame.
2.  **Data Inspection:**
    * `df.head()`: Displays the first 5 rows to verify data loading.
    * `df.info()`: Checks for null values and data types.
3.  **Statistical Summary:**
    * `df.describe()`: Generates summary statistics (count, mean, std, min, max) for numerical columns like Age and RollNo.

## 📊 Key Insights (from Output)
* **Total Records:** 20 Students.
* **Average Age:** 20.5 years.
* **Age Range:** Minimum 19 years, Maximum 22 years.

## 🛠️ Dependencies
To run this code, you need the following libraries:
* `pandas`
* `numpy`

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/Student-Data-Analysis-Pandas.git](https://github.com/YOUR-USERNAME/Student-Data-Analysis-Pandas.git)
    cd Student-Data-Analysis-Pandas
    ```
2.  **Install requirements:**
    ```bash
    pip install pandas numpy
    ```
3.  **Run the script/notebook:**
    * If using a script: `python main.py`
    * If using Jupyter: Open the notebook and run all cells.
