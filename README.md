# web-scrapping
# 🕷️ Web Scraping & Data Analysis

A Python-based project that demonstrates how to **collect, clean, analyze, and visualize web data** using modern Python data-processing libraries.

The project extracts product information from a public/demo webpage, processes the collected data, performs statistical analysis, and generates meaningful visualizations.

---

## 📌 Project Overview

**Web Scraping & Data Analysis** automates the process of collecting structured product information from a webpage.

The project follows this workflow:

```text
Web Page
   ↓
Web Scraping
   ↓
Raw Data
   ↓
Data Cleaning
   ↓
Data Analysis
   ↓
Visualization
   ↓
CSV Reports
```

This project is suitable for **BCA/MCA students, Python internships, data-analysis beginners, and GitHub portfolios**.

---

## ✨ Features

* 🌐 Scrape product information from a webpage
* 📦 Extract product name, price, rating, and category
* 🧹 Clean and preprocess collected data
* 📊 Perform statistical analysis
* 💰 Calculate average, minimum, and maximum prices
* ⭐ Analyze product ratings
* 🗂️ Perform category-wise analysis
* 📈 Generate data visualizations
* 💾 Export data to CSV
* 📑 Generate analysis results
* 🐍 Built entirely with Python

---

## 🛠️ Technologies Used

| Technology    | Purpose                     |
| ------------- | --------------------------- |
| Python        | Main programming language   |
| Requests      | Send HTTP requests          |
| BeautifulSoup | Parse HTML and extract data |
| Pandas        | Data cleaning and analysis  |
| NumPy         | Numerical operations        |
| Matplotlib    | Data visualization          |
| Seaborn       | Statistical visualization   |
| CSV           | Data storage                |

---

## 📂 Project Structure

```text
web-scraping-data-analysis/
│
├── main.py
├── scraper.py
├── data_analysis.py
├── visualizations.py
├── requirements.txt
├── README.md
│
├── data/
│   └── products.csv
│
├── output/
│   ├── price_distribution.png
│   ├── rating_distribution.png
│   ├── category_analysis.png
│   └── analysis_report.csv
│
└── report/
    └── Project_Report.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/web-scraping-data-analysis.git
```

### 2. Open the project directory

```bash
cd web-scraping-data-analysis
```

### 3. Create a virtual environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

Linux/macOS:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

Run the main Python program:

```bash
python main.py
```

The program will:

1. Send a request to the target webpage.
2. Parse the HTML content.
3. Extract product information.
4. Clean the collected data.
5. Save the dataset as CSV.
6. Perform statistical analysis.
7. Generate visualization charts.

---

## 📊 Data Fields

The collected dataset contains fields such as:

| Field    | Description             |
| -------- | ----------------------- |
| Product  | Name of the product     |
| Price    | Product price           |
| Rating   | Customer/product rating |
| Category | Product category        |

Example:

```text
Product              Price      Rating      Category
-----------------------------------------------------
Laptop               55000      4.5         Electronics
Headphones            2500      4.2         Electronics
Backpack              1200      4.0         Accessories
Smart Watch            3500      4.4         Electronics
```

---

## 📈 Analysis Performed

The project performs several types of analysis.

### Price Analysis

Calculates:

* Average price
* Minimum price
* Maximum price
* Price distribution

### Rating Analysis

Analyzes:

* Average rating
* Rating distribution
* Products with high/low ratings

### Category Analysis

Compares:

* Number of products by category
* Average price by category
* Category-level statistics

---

## 📉 Visualizations

The project generates charts such as:

### Price Distribution

Shows how product prices are distributed across the dataset.

### Rating Distribution

Shows the distribution of product ratings.

### Category Analysis

Compares average product prices across different categories.

Generated charts are stored in:

```text
output/
```

---

## 🧹 Data Cleaning

Before analysis, the project performs basic preprocessing:

* Removes unwanted currency symbols
* Converts prices into numerical values
* Converts ratings into numerical values
* Handles missing values
* Removes invalid records
* Standardizes data formats

---

## 📄 Sample Output

After running the project, the terminal displays information similar to:

```text
Starting Web Scraping...

===== DATA ANALYSIS =====

Basic Statistics:

             Price    Rating
count       20.00     20.00
mean       8450.25      4.20
min         999.00      3.50
max       55000.00      4.90

Average Price:
8450.25

Average Rating:
4.20

Most Expensive Product:
...

Cheapest Product:
...

Category Analysis:
...

Project completed successfully!
Data saved in data/products.csv
Charts saved in output/
```

---

## 🔐 Responsible Web Scraping

This project is intended for **educational purposes**.

When adapting the scraper to a real website:

* Respect the website's `robots.txt`.
* Follow the website's Terms of Service.
* Avoid excessive requests.
* Use reasonable delays between requests.
* Do not collect private or sensitive information.
* Prefer public/demo websites designed for scraping.
* Do not bypass authentication, CAPTCHAs, or technical restrictions.

---

## 🚀 Future Improvements

Possible improvements include:

* Add a graphical user interface
* Add automated scheduled scraping
* Store data in MySQL/SQLite
* Add interactive dashboards
* Add Excel export
* Add automatic email reports
* Add more advanced statistical analysis
* Add machine-learning-based price prediction
* Add support for multiple websites

---

## 🎓 Learning Outcomes

By completing this project, you can learn:

* Python programming
* HTTP requests
* HTML parsing
* Web scraping
* Data cleaning
* Pandas DataFrames
* Statistical analysis
* Data visualization
* CSV data handling
* Project organization
* Git and GitHub basics

---

## 👨‍💻 Author

**Priyanshu Kumar**

BCA Student

Academic Session: **2025–26**

---

## 📜 License

This project is intended for **educational and learning purposes**.

You are free to modify and improve the project for your own learning and academic work.

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.

**Happy Coding! 🐍📊**
