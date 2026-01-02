# 🏦 Banking Risk Analytics Dashboard

## 📌 Project Overview

This project presents an end-to-end **banking risk analytics solution** designed to analyze customer financial behavior and support **data-driven lending and risk management decisions**. The focus is on understanding customer risk profiles, loan exposure, deposits, and savings patterns using interactive dashboards.

---

## 🎯 Problem Statement

Banks face significant risk while lending to customers. The goal of this project is to analyze banking customer data to:

* Identify **high-risk customers**
* Understand **loan vs deposit exposure**
* Support informed **loan approval decisions**

---

## 🗂️ Dataset

The dataset contains structured banking and customer information across multiple related tables, including:

* Client-Banking details
* Banking relationships
* Gender and investment advisor data
* Account balances, loans, and savings

---

## 🔧 Data Processing & Feature Engineering

Key transformations and engineered features include:

* **Engagement Days** – Calculated using joining date
* **Engagement Timeframe** – Customer tenure buckets
* **Income Band** – Low, Medium, High income segmentation
* **Joined Year** – Year extracted from joining date
* **Gender Labels** – Converted numeric codes to readable categories
* **Processing Fees** – Derived from fee structure

---

## 📊 Tools & Technologies

* **MySQL** – Data storage and relational structure
* **Python (Pandas, Matplotlib, Seaborn)** – Data extraction and EDA
* **Power BI** – DAX calculations, KPIs, and dashboards

---

## 📈 KPIs & Dashboards

Key metrics built using DAX:

* Total Clients
* Total Loan Exposure
* Total Deposits
* Total Savings Amount
* Total Fees

Dashboards include:

* Loan Analysis
* Deposit Analysis
* Risk Summary Dashboard

Interactive slicers allow filtering by **Year of Joining, Gender, Income Band, and Engagement Timeframe**.

---

## ✅ Conclusion

This project demonstrates how banking data can be transformed into actionable insights using modern analytics tools. The dashboards help identify risk patterns and support strategic decision-making in financial services.

---

## 🚀 Future Enhancements

* Predictive risk modeling using machine learning
* Customer segmentation and cohort analysis
* Real-time dashboard integration
