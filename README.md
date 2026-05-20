# Banking Transaction Analysis Project

## Big Data Analytics Course Project
GROUP :
MAHEEN AZEEM (2023-ag-9575)
FARAH HAMIDA KHAN (2023-ag-9526)

### Technology Used
- PySpark
- Python 3
- Jupyter Notebook
- Apache Spark

### Dataset
50,000 Banking Transactions Dataset

---

# Project Overview

This project focuses on Banking Transaction Analysis using PySpark to process and analyze large-scale banking data efficiently.

The project helps in:
- Identifying transaction patterns
- Detecting suspicious transactions
- Finding active customers
- Calculating balances
- Generating visual insights

---

# Project Objectives

- Process large-scale banking transactions
- Detect fraud and suspicious activities
- Analyze customer transaction behavior
- Generate charts and analytics reports

---

# Dataset Information

The dataset contains:
- TransactionID
- AccountID
- TransactionAmount
- TransactionType
- TransactionDate
- Location
- CustomerAge
- AccountBalance
- LoginAttempts
- And other banking-related fields

---

# Spark Session Setup

![Spark Session](images/spark.png)

PySpark Spark Session was initialized successfully for distributed data processing.

---

# Dataset Preview

![Dataset](images/dataset.png)

The dataset was loaded into a PySpark DataFrame and displayed using `df.show()`.

---

# Dataset Schema

![Schema](images/schema.png)

The schema displays column names, data types, and nullability information.

---

# Data Cleaning

![Cleaning](images/cleaning.png)

Data cleaning operations included:
- Removing null values
- Removing duplicate records

---

# Highest Transactions

![Highest Transactions](images/highest.png)

Top 10 highest-value transactions were identified using descending transaction amount sorting.

---

# Average Transaction Amount

![Average](images/average.png)

Average transaction amount across all records was approximately **$297.87**.

---

# Suspicious Transactions

![Fraud Detection](images/fraud.png)

Transactions above the threshold of **$2000** were flagged as suspicious.

---

# Most Active Customers

![Active Customers](images/active.png)

Accounts with the highest transaction frequency were identified.

---

# Transaction Type Distribution

![Transaction Distribution](images/chart1.png)

Bar chart showing Debit vs Credit transaction distribution.

---

# Top Accounts by Total Balance

![Top Accounts](images/chart2.png)

Visualization of top customer accounts based on total transaction balance.

# Conclusion

This project demonstrates the power of PySpark for large-scale financial data analysis and fraud detection.

Key achievements:
- Big data processing using Spark
- Fraud transaction detection
- Customer activity analysis
- Data visualization and reporting

---

# Project Report

The complete project report is included in this repository.# Banking-Transaction-Analysis-Project
Big Data Analytics Course Project
