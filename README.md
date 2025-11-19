### 🚗 Electric Vehicle Market Analysis (Web Scraping + Data Analytics Project)

A complete end-to-end data analysis project involving web scraping, data cleaning, EDA (Univariate, Bivariate, Multivariate), market segmentation, and business insights using real-world electric vehicle (EV) data.
📘 Project Overview

This project analyzes the electric vehicle (EV) market by collecting real-time specifications from an online EV database. The goal is to understand trends in:

- battery capacity,

- driving range,

- charging performance,

- efficiency,

- acceleration,

- and overall brand competitiveness.

The project demonstrates skills in scraping, cleaning, visualizing, analyzing, and deriving insights from real-world data.

### 🎯 Problem Statement

The electric vehicle market is rapidly expanding, with numerous brands offering different battery sizes, ranges, charging speeds, and performance characteristics. However, there is no single dataset that consolidates all these details.

#### Objective:
To collect EV data from the web, clean it, analyze it, and extract meaningful insights that help understand market trends and brand performance.

### 📂 Dataset Source

Data was extracted by scraping:

🔗 https://ev-database.org

This site provides EV specifications including:

Range

Battery capacity

Efficiency

Acceleration

Fast charging power

Body type

Brand & model

The scraped dataset contains 200+ electric vehicles.

### ⚙️ Tech Stack
Languages:	Python
Scraping:	Requests, BeautifulSoup, Regex
Data Processing:	Pandas, NumPy
Visualization:	Matplotlib, Seaborn
Notebook:	Jupyter Notebook

### 📥 Data Collection (Web Scraping)

Used requests to fetch the webpage HTML

Parsed using BeautifulSoup

Extracted EV details using tag-based search & regex

Stored data in lists → constructed into a pandas DataFrame

Scraped fields:

Brand

Model

Range (km)

Battery capacity (kWh)

Efficiency (Wh/km)

Fast charging speed

Acceleration (0–100 km/h)

Body type

Top speed

Price (if available)

### 🧹 Data Cleaning

Tasks performed:

Converted textual data (e.g., “Battery 60 kWh”) into numeric values

Removed extra characters (km, kWh, km/h)

Handled missing or inconsistent entries

Created segments for range analysis

Standardized column names

Result:
A clean, analysis-ready dataset.

### 📊 Univariate Analysis

Visualizations include:

Distribution of battery capacity

Distribution of range

Charging power distribution

Efficiency distribution

Body type countplot

Top brands by number of EVs

Purpose:
To understand the spread and frequency of individual attributes.

### 🔗 Bivariate Analysis

Analyzed relationships between two variables using:

Battery vs Range (scatter plot)

Efficiency vs Range

Price vs Range (if available)

Average Range by Brand (bar chart)

Average Battery by Brand

Purpose:
To identify trends like how battery size affects driving range.

### 📈 Multivariate Analysis

Includes:

Correlation heatmap of all numeric features

Boxplots comparing performance between brands

Multi-feature comparisons (e.g., charging + battery + range)

Purpose:
To understand deeper interconnections between variables.

### 💡 Key Insights

✔ Tesla, BMW, and Mercedes produce the highest-range EVs
✔ MG and BYD offer strong value-for-money electric cars
✔ Battery capacity strongly correlates with range
✔ Fast-charging power varies significantly by brand
✔ Sedans and SUVs dominate the EV market
✔ Most EVs fall in the 250–400 km range category
✔ Efficiency does not always correlate directly with price
✔ High-performance cars generally have better acceleration but lower efficiency

### 📌 Conclusion

The EV market shows strong differentiation between brands in terms of range, battery, and charging speed.
This analysis helps understand which manufacturers lead in technology, which segments dominate the market, and what factors influence EV performance.

### 📁 Project Structure

📦 EV-Market-Analysis
 ┣ 📜 Electric_Cars.ipynb
 ┣ 📜 README.md
 ┣ 📜 requirements.txt (optional)
 ┣ 📁 data/ (optional for CSV exports)

 ### 🔗 Repository Link

(Replace with your actual GitHub link)
👉 https://github.com/yourusername/ev-market-analysis
