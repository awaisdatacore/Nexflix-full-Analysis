---
name: Netflix Data Analysis Project
description: Exploratory Data Analysis (EDA) and data preprocessing on Netflix dataset using Python
---

# Netflix Data Analysis Project

## 📌 Overview
This project focuses on analyzing a Netflix dataset to extract meaningful insights using data preprocessing and exploratory data analysis (EDA) techniques.

The goal is to clean raw data, transform it into a usable format, and answer key analytical questions through visualization.

---

## 📂 Dataset
- Dataset: Netflix Movies/Shows Data
- Source: CSV file / GitHub raw link
- Contains information such as:
  - Title
  - Genre
  - Release Date
  - Vote Average
  - Vote Count
  - Popularity

---

## ⚙️ Steps Performed

### 1. Data Loading
- Loaded dataset using CSV file
- Also tested loading data from online source (GitHub)

### 2. Data Exploration
- Checked dataset structure using `.info()`
- Identified missing values
- Checked duplicates
- Used `.describe()` for statistical summary

### 3. Data Cleaning
- Handled missing values
- Removed or analyzed duplicate records
- Fixed incorrect data types
- Converted columns to appropriate formats

### 4. Feature Engineering
- Converted `Release_Date` to year format
- Created new feature: `rating_category`
  - Low
  - Average
  - High
- Cleaned and transformed numerical columns like:
  - Vote Average
  - Vote Count

### 5. Outlier Detection
- Identified outliers in release year
- Applied statistical methods (IQR concept)

### 6. Data Transformation
- Converted categorical columns to proper types
- Dropped irrelevant columns

---

## 📊 Key Questions Answered

1. What is the most frequent genre?
2. Which movies have the highest vote average?
3. Which movie has the highest popularity and its genre?

---

## 📈 Visualizations
- Bar plots
- Distribution analysis
- Count plots using Seaborn and Matplotlib

---

## 🔍 Key Insights
- Certain genres dominate the dataset
- Popularity and vote average vary significantly across movies
- Recent years show increased content production

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📌 Conclusion
This project demonstrates the importance of data preprocessing and feature engineering in real-world datasets.

Clean and well-structured data helps in extracting better insights and improves overall analysis quality.

---

## 🚀 Future Improvements
- Apply machine learning models
- Perform deeper statistical analysis
- Build dashboard (Power BI / Tableau)
