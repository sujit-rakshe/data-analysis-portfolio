# 📊 Day 2 – Exploratory Data Analysis with Pandas

## 🗂 Dataset
Netflix Titles Dataset from Kaggle:  
[🔗 Kaggle Link](https://www.kaggle.com/datasets/shivamb/netflix-shows)

This dataset contains information about TV Shows and Movies available on Netflix as of 2021, including title, type, country, date added, release year, rating, duration, and more.

---

## 🔧 Tasks Performed

- Loaded dataset using `pandas`
- Inspected data with `.head()`, `.info()`, `.describe()`
- Checked and handled missing values in key columns like `director`, `cast`, `country`, `rating`, `duration`, and `date_added`
- Applied filters to:
  - Show only Indian Movies
  - Show titles rated “TV-MA”
  - Show content released after 2015
- Sorted data by `release_year`
- Grouped data by content `type` (Movie or TV Show)
- Created a basic bar plot of content type distribution using Matplotlib

---

## 🧠 Skills Practiced

- Data loading and inspection
- Handling missing data using `fillna()` and `dropna()`
- Logical filtering with multiple conditions
- Grouping and sorting data in pandas
- Basic plotting with Matplotlib

---

## 📁 Files Included

- `Day2_Pandas_EDA.ipynb` – The main notebook with all EDA steps
- `netflix_titles.csv` – Dataset used (from Kaggle)
- `README.md` – Summary of work and learning

---

## 💡 What I Learned

This exercise helped me understand how to:
- Work with real-world datasets that are messy and incomplete
- Clean and prepare data for analysis
- Extract insights using simple but powerful Pandas operations

---
