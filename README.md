# 📊 Web Scraping Project – Book Dataset Analysis

## 🔹 Overview
This project demonstrates web scraping using Python. Data is extracted from a public website and converted into a structured dataset for analysis and learning purposes.

The dataset contains approximately **200–300 book records**, including important details such as title, price, rating, availability, and product links.

---

## 🔹 Objective
- Extract data from a real website using web scraping
- Understand HTML structure and navigation
- Clean and transform raw data into structured format
- Build a dataset for analysis and portfolio use

---

## 🔹 Tools & Technologies
- Python
- Requests
- BeautifulSoup
- Pandas
- Google Colab

---

## 🔹 Dataset Features

The scraped dataset includes the following columns:

| Column Name     | Description                         |
|----------------|-------------------------------------|
| Title           | Name of the book                  |
| Price (£)       | Book price in numeric format      |
| Availability    | Stock status of the book          |
| Product Link    | Direct URL to book page           |

---

## 🔹 Project Workflow

1. Send HTTP requests to the website
2. Parse HTML content using BeautifulSoup
3. Extract required data fields
4. Clean and format data (e.g., price conversion)
5. Store data in a structured DataFrame
6. Export dataset as CSV file

---

## 🔹 How to Run This Project

### 1. Install required libraries
```bash
pip install requests beautifulsoup4 pandas
