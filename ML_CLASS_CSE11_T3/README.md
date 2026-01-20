# ML_CLASS_CSE11_Task3
Uploaded Jupyter NOtebook for data colllection from these methods : SQL, Excel, JSON, Image, Audio, IoT, Text, Logs, and Video.

# 📡 Comprehensive Data Collection & Simulation in Python

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Selenium](https://img.shields.io/badge/Library-Selenium-43B02A?style=flat&logo=selenium)
![SQL](https://img.shields.io/badge/Database-SQLite-003B57?style=flat&logo=sqlite)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458?style=flat&logo=pandas)

## 📌 Project Overview
This repository contains a collection of Python scripts/notebooks that demonstrate **12 different methods** of acquiring data for Machine Learning and Data Science. It moves beyond simple CSV loading to cover complex scenarios like SQL querying, dynamic web scraping, and simulating multimedia data (Audio/Video/IoT).

## 📂 Methods & Techniques

### 🗄️ Structured Data
| Method | Description | Output File |
| :--- | :--- | :--- |
| **SQL Database** | Simulates a database connection (`sqlite3`), inserts dummy inventory data, and queries it back. | `sql_data.csv` |
| **Excel & JSON** | Converts a Pandas DataFrame into standard simulation formats used in business and web apps. | `employee_data.xlsx`, `employee_data.json` |

### 🖼️ Multimedia Data
| Method | Description | Output File |
| :--- | :--- | :--- |
| **Image Collection** | Downloads an image from a URL using `requests`. | `dataset_image.png` |
| **Audio Generation** | Uses `numpy` and `scipy` to mathematically generate a 1-second sine wave (beep) at 440Hz. | `beep.wav` |
| **Video Acquisition** | Downloads a sample testing video file for Computer Vision tasks. | `sample_video.mp4` |

### 📡 Streams & Sensors
| Method | Description | Output File |
| :--- | :--- | :--- |
| **IoT Sensor Data** | Simulates a temperature sensor generating data every second with timestamps. | `sensor_data.csv` |
| **Log Data** | Generates fake server logs (Login/Logout events) with timestamps for security analysis. | `server.log` |

### 🕸️ Advanced Web Scraping
| Method | Description | Output File |
| :--- | :--- | :--- |
| **Dynamic Scraping** | Uses **Selenium** to scrape a website that renders content via JavaScript (which standard BeautifulSoup cannot handle). | `dynamic_data.csv` |
| **Text Data** | Simulates collecting raw text (e.g., customer reviews) for NLP. | `review.txt` |

## 🛠️ Tech Stack & Dependencies
* **Core:** `pandas`, `numpy`, `requests`
* **Database:** `sqlite3` (Built-in)
* **Multimedia:** `scipy` (for Audio), `IPython` (for display)
* **Web Automation:** `selenium` (Chrome WebDriver)

## 🚀 How to Run

### 1. Prerequisites
Ensure you have Python installed. You will need the following libraries:
```bash
pip install pandas numpy scipy requests selenium openpyxl
### 2. Selenium Setup
Method 12 requires Google Chrome. The script uses webdriver.Chrome() in headless mode.

Ensure you have Google Chrome installed.

The code is compatible with modern Selenium (v4+), which handles driver management automatically.

### 3. Execution
Run the Jupyter Notebook or Python script. The code will generate 9 different files in your directory corresponding to the data collected.

📂 Output Manifest
After execution, your directory will contain:

store_inventory.db (SQLite Database)

sql_data.csv

employee_data.xlsx / .json

dataset_image.png

beep.wav

sensor_data.csv

review.txt

server.log

sample_video.mp4

dynamic_data.csv

📜 License
This project is open-source and available for educational purposes.
