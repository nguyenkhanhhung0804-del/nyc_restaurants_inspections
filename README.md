# NYC Restaurant Inspections Analytics (Python, SQLite & Exploratory Data Analysis)

This repository contains a comprehensive data analytics project focused on restaurant inspection outcomes, food safety compliance, and violation trends across New York City. It utilizes a relational **SQLite** database (`restaurant_data.db`) together with **Python** to extract, transform, analyze, and visualize inspection data, generating actionable insights through exploratory data analysis and statistical reporting.

---

## 📊 Dataset Overview

The project analyzes the **NYC Restaurant Inspections** database, which stores inspection records collected by the New York City Department of Health.

The database consists of several related tables containing:

1. **Restaurant Information**
  * Includes restaurant names, boroughs, ZIP codes, cuisine descriptions, and establishment identifiers.

2. **Inspection Records**
  * Contains inspection dates, inspection types, inspection scores, and letter grades (A, B, C).

3. **Violation Information**
  * Stores violation codes, violation descriptions, and critical/non-critical violation indicators.

Together, these datasets provide a comprehensive view of restaurant performance, inspection history, and food safety compliance across New York City.

---

## 🐍 Python Analytics & SQLite Skills

In addition to SQL querying, this project demonstrates a complete **Python-based analytics workflow** that transforms relational database records into meaningful business insights. This component highlights several core data analytics capabilities:

* **SQLite Database Integration:** Connected Python to a relational SQLite database using the `sqlite3` library, executing SQL queries to retrieve and combine inspection data from multiple related tables.
* **Data Wrangling with pandas:** Cleaned and transformed raw inspection records using **pandas**, including filtering observations, handling missing values, creating derived variables, aggregating statistics, and preparing datasets for analysis.
* **Exploratory Data Analysis (EDA):** Leveraged **NumPy** and **pandas** to summarize inspection scores, analyze restaurant grades, identify violation patterns, and compare food safety performance across cuisines and boroughs.
* **Statistical Visualization:** Developed informative visualizations using **Matplotlib** and **Seaborn** to communicate inspection trends, violation frequencies, score distributions, and geographic patterns.
* **Business Insight Generation:** Combined SQL extraction with Python analytics to convert raw inspection data into actionable insights supporting food safety monitoring and restaurant performance evaluation.

---

## 🛠️ Analytical Tasks & Business Questions

The repository includes Python notebooks and SQL queries designed to answer critical food safety and operational questions, structured into the following analytical themes:

### 1. Restaurant Performance Analysis

* **Top Performing Restaurants:** Identifies restaurants consistently achieving the highest inspection grades and lowest inspection scores.
* **Cuisine Performance Comparison:** Evaluates inspection performance across different cuisine categories using descriptive statistics.
* **Restaurant Compliance History:** Examines establishments with repeated inspections and recurring violations.

### 2. Food Safety & Violation Analysis

* **Most Common Violations:** Determines the most frequently reported violation codes and descriptions.
* **Critical Violation Trends:** Analyzes recurring critical food safety violations across restaurants.
* **Violation Frequency Analysis:** Identifies establishments requiring additional regulatory attention due to repeated violations.

### 3. Geographic Analysis

* **Inspection Results by Borough:** Compares inspection performance across New York City's boroughs.
* **Restaurant Grade Distribution:** Examines how inspection grades vary by geographic region.
* **Regional Food Safety Patterns:** Identifies boroughs with higher concentrations of inspection failures and critical violations.

---

## 🚀 Technical Highlights & Python/SQLite Skills Used

The project demonstrates practical data analytics, database, and visualization techniques:

* **SQLite Database Querying:** Wrote SQL queries involving filtering, aggregations, joins, subqueries, and sorting to efficiently retrieve inspection data.
* **Python Data Analysis:** Utilized **pandas** and **NumPy** for data cleaning, transformation, aggregation, and statistical analysis.
* **Exploratory Data Analysis (EDA):** Applied descriptive statistics and comparative analysis to identify trends, anomalies, and restaurant performance patterns.
* **Data Visualization:** Created clear and informative charts using **Matplotlib** and **Seaborn** to communicate analytical findings effectively.
* **End-to-End Analytics Workflow:** Integrated SQL querying, Python programming, and data visualization into a complete analytical pipeline from raw database records to actionable insights.

## Author

**Hung Khanh Nguyen**
