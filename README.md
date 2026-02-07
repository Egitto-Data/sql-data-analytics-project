# 💎 SQL Analytics & BI Toolbox

![SQL](https://img.shields.io/badge/Language-SQL-blue)
![Database](https://img.shields.io/badge/Compatibility-PostgreSQL%20|%20Snowflake%20|%20BigQuery-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A premium collection of high-performance SQL scripts meticulously crafted for **Data Exploration**, **Business Intelligence**, and **Advanced Analytics**. This repository is designed to bridge the gap between raw data and actionable insights using industry-standard best practices.

---

## 🎯 Project Mission
In modern data stacks, the ability to write clean, performant, and reusable SQL is a superpower. This project provides a "plug-and-play" library of queries that handle complex logic—like window functions and cohort analysis—so you can spend less time debugging and more time driving strategy.

---

## 📂 Analytical Modules

### 🔍 1. Data Exploration & Quality
*Ensure your foundation is solid before building reports.*
* **Schema Profiling:** Identify table sizes, column types, and primary key integrity.
* **Null Density:** Measure data completeness across critical dimensions.
* **Anomaly Detection:** Find outliers and extreme values using Z-score logic.

### 📈 2. Core Business Metrics
*Standardized logic for the KPIs that matter.*
* **Monetization:** Average Order Value (AOV), Revenue per User (ARPU).
* **Retention:** Churn rate calculations and active user counts (DAU/WAU/MAU).
* **Efficiency:** Lead-to-customer conversion rates.

### ⏳ 3. Time-Series & Trend Analysis
*Understand the rhythm of your business.*
* **Period-over-Period:** YoY, QoQ, and MoM growth comparisons.
* **Smoothing:** Moving averages (7-day/30-day) to eliminate weekend noise.
* **Seasonality:** Identifying peak performance days and hours.

### 🌊 4. Cumulative & Window Analytics
*Track progress over time.*
* **Running Totals:** Cumulative revenue and user acquisition.
* **Rankings:** Identifying top-performing products or sales reps using `RANK()` and `DENSE_RANK()`.
* **To-Date Reporting:** Year-to-Date (YTD) and Month-to-Date (MTD) logic.

### 🧩 5. Advanced Segmentation
*Break down the "Who" behind the "What".*
* **RFM Analysis:** Segmenting users by Recency, Frequency, and Monetary value.
* **Cohort Analysis:** Tracking behavior changes based on user sign-up date.
* **Bucket Analysis:** Grouping continuous data into discrete categories.

---

## 🛠️ Tech Stack & Compatibility
These scripts are optimized for **ANSI SQL**, making them highly portable across modern data warehouses:
* ❄️ **Snowflake**
* ☁️ **Google BigQuery**
* 🐘 **PostgreSQL**
* 🔴 **Amazon Redshift**
* 📊 **Azure Synapse**

---

## 🚀 How to Use

1. **Browse:** Select a module from the folder structure.
2. **Review:** Open the `.sql` file to see the query structure and logic comments.
3. **Customize:** * Look for the `-- CONFIG --` comments at the top of scripts.
   * Replace generic table names (`stg_orders`) with your actual table names.
4. **Execute:** Run the query in your favorite IDE (DBeaver, DataGrip, or Cloud Console).

---

## 💡 Pro-Tips Included
Every script in this repository follows a strict style guide:
* ✅ **CTEs over Subqueries:** For better readability and debugging.
* ✅ **Explicit Aliasing:** No more wondering what `col1` refers to.
* ✅ **Lowercase Keywords:** Standardized for modern formatting.
* ✅ **No `SELECT *`:** Optimized for column-store performance.

---

## 🤝 Contributing
Want to add a script? We love that! 
- 🌟 Star the repo.
- 🍴 Fork it.
- 📥 Submit a Pull Request with a brief description of the analysis.

---

## ⚖️ License
Distributed under the MIT License. See `LICENSE` for more information.

---
**📬 Connect with Me**
[Your Portfolio/Website] | [Your LinkedIn] | [Your Twitter/X]

*"In God we trust; all others must bring data." — W. Edwards Deming*
