# BIG-DATA-ANALYSIS

*COMPANY: CODTECH IT SOLUTIONS

*NAME: VEDIKA GUPTA

*INTERN ID: CT04DZ296

*DOMAIN:  DATA ANALYTICS

*DURATION: 4 WEEKS

*MENTOR: NEELA SANTOSH

## ✅ Task Description

> Perform a data analysis on a large dataset using PySpark and generate meaningful insights.

---

## 📂 Dataset Used
- Source: [cities.csv](https://people.sc.fsu.edu/~jburkardt/data/csv/cities.csv)
- Type: U.S. cities with geographical coordinates

---

## 🔧 Technologies Used
- Python 3.13
- Apache Spark (via PySpark)
- Jupyter Notebook

---

## 🔍 What’s Done

- Loaded `cities.csv` into a PySpark DataFrame
- Cleaned messy column names (quotes/spaces)
- Renamed `LatD → Latitude`, `LonD → Longitude`
- Printed schema and preview
- Filtered cities where `Latitude > 40`
- Sorted top 5 cities by decreasing `Longitude`

---

## 📈 Key Insights

1. Cities with `Latitude > 40` are mostly in northern U.S.
2. Westernmost cities have the lowest longitude values.
3. The dataset is clean and ideal for big data processing.
4. PySpark's DataFrame API is fast and readable.
5. Simple filtering and aggregation are easy to scale.

---
