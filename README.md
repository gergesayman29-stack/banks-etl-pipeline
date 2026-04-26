# 🏦 Banks ETL Pipeline Project

## 📌 Overview
This project is an **ETL (Extract, Transform, Load) pipeline** that collects data about the world's largest banks, transforms it into multiple currencies, and stores it in both CSV and SQLite database formats.

---

## ⚙️ Technologies Used
- Python
- Pandas & NumPy
- BeautifulSoup (Web Scraping)
- SQLite
- API/Data Processing

---

## 🔄 ETL Process

### 1. Extract
- Scrapes bank data from a Wikipedia archived page

### 2. Transform
- Converts market capitalization from USD to:
  - GBP
  - EUR
  - INR

### 3. Load
- Saves data to:
  - CSV file
  - SQLite database

---

## 📊 Sample Queries
- Retrieve all banks
- Calculate average market cap in GBP
- List top 5 banks

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python banks_project.py
