# 🏏 IPL Analysis - P1

## Data Engineering & Sports Analytics

An end-to-end IPL data engineering and analytics project that uses Python,
Pandas, NumPy, MySQL and Matplotlib to clean, transform, store and analyze
Indian Premier League match data.

---

## 📌 Project Overview

The project collects IPL datasets in CSV format and processes them through
an ETL pipeline.

The cleaned data is stored in MySQL and analyzed using SQL queries.
Matplotlib is then used to generate dashboards and visualizations that
highlight team and match performance trends.

---

## 🎯 Objectives

- Perform ETL operations using Python, Pandas and NumPy.
- Clean and transform raw IPL datasets.
- Handle missing and duplicate records.
- Apply business rules to the data.
- Store cleaned data in MySQL.
- Apply database constraints.
- Perform analytical queries using SQL.
- Build visualizations using Matplotlib.
- Identify important IPL team and match trends.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- MySQL
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

## 🔄 Project Architecture

```text
Raw IPL CSV Files
        │
        ▼
Python ETL
(Pandas + NumPy)
        │
        ├── Data Profiling
        ├── Deduplication
        ├── Null Handling
        ├── Transformations
        ├── Business Rules
        └── Validation
        │
        ▼
Clean Data
        │
        ▼
MySQL Database
        │
        ├── DDL
        ├── Primary Keys
        ├── Foreign Keys
        └── Constraints
        │
        ▼
SQL Analytics
        │
        ▼
Matplotlib Dashboards
