# ML_CLASS_CSE11_Task2
Demonstration of Web Scraping, API, and Manual data collection
# 📥 Data Collection Techniques in Python

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458?style=flat&logo=pandas)
![BeautifulSoup](https://img.shields.io/badge/Library-BeautifulSoup-green?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This repository demonstrates three fundamental methods of collecting data for Data Science and Machine Learning projects. The provided Jupyter Notebook (`Data_Collection_Task2.ipynb`) executes pipelines to acquire data from different sources and save them as CSV files.

## ⚙️ Data Collection Methods

### 1. ✍️ Manual Data Entry
* **Description:** creating a dataset from scratch using Python dictionaries.
* **Data:** A simple survey of "Study Hours vs Marks" for 5 students.
* **Output:** `manual_data.csv`

### 2. 🕷️ Web Scraping
* **Description:** Extracting information from a website HTML structure.
* **Target:** [Books to Scrape](http://books.toscrape.com/) (A sandbox website for scraping).
* **Tool:** `BeautifulSoup` & `requests`.
* **Data Extracted:** Book Titles from the main page.
* **Output:** `scraped_data.csv`

### 3. 🌐 API Integration
* **Description:** Fetching live data from a public REST API.
* **Target:** [Open-Meteo Weather API](https://open-meteo.com/).
* **Data Extracted:** Current weather conditions (Temperature, Wind Speed, etc.) for specific coordinates (Latitude: 20.296, Longitude: 85.824).
* **Output:** `api_data.csv`

## 🛠️ Tech Stack
* **Python 3.x**
* **Pandas** (Data manipulation & CSV export)
* **Requests** (HTTP requests for Web & API)
* **BeautifulSoup4** (HTML Parsing)

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/Data-Collection-Methods-Python.git](https://github.com/YOUR-USERNAME/Data-Collection-Methods-Python.git)
    cd Data-Collection-Methods-Python
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas requests beautifulsoup4
    ```
3.  **Run the Notebook:**
    Open `Data_Collection_Task2.ipynb` in Jupyter Notebook or VS Code and execute all cells.

## 📂 Generated Outputs
After running the code, the following files will be created in your directory:

| File Name | Content | Source |
| :--- | :--- | :--- |
| `manual_data.csv` | Student names, study hours, and marks | Manual Python Dict |
| `scraped_data.csv` | List of book titles | Books.toscrape.com |
| `api_data.csv` | Real-time weather data | Open-Meteo API |

## 📜 License
This project is open-source and available for educational purposes.
