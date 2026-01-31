# SaaS Subscription Metrics Analysis 

## 📌 Project Overview
This project demonstrates the ability to transform raw subscription data into high-level business intelligence metrics.
The primary focus is on **advanced SQL data transformation** and interactive Power BI dashboarding. 
By calculating key SaaS performance indicators, this project showcases technical proficiency in data engineering.

## :bar_chart: Data Source

The analysis is based on the SaaS Subscription & Churn Analytics Dataset, which is a simulated SaaS business dataset. It offers a realistic environment to practice SQL joins, cohort analysis, etc.

**Dataset Origin:** [SaaS Subscription & Churn Analytics Dataset](https://www.kaggle.com/datasets/rivalytics/saas-subscription-and-churn-analytics-dataset)


## 📈 Key Performance Indicators (KPIs)
The following metrics were calculated using SQL and visualized in Power BI:

* **Revenue**: Total realized income from active subscriptions.

* **ARPPU** (Average Revenue Per Paying User): Average revenue generated per subscriber.

* **Revenue Churn**: The percentage of revenue lost due to cancellations or downgrades.

* **Logo Churn**: The rate at which individual customers (logos) cancel their subscriptions.

* **User Growth**: Breakdown of Paying Users vs. Total Users.

* **Trial-to-Paid Conversion**: The efficiency of converting trial users into recurring revenue.

## ⚙️ Data Transformation (SQL)

CTEs & Subqueries: To transform subscription (start_date, end_date) to monthly billing table and mrr table for optimized Power BI performance.

Window Functions: Used SUM() OVER() and LAG() to calculate monthly user growth and churn rates.

## 📂 How to View
* Review the `sql_queries/load/04_pbi.sql` file to see the logic behind the KPI calculations. 

## 📸 Dashboard Preview
![Dashboard Screenshot Page1](https://github.com/yunwe/data_projects/blob/main/ravenstack/power_bi/screenshots/pg1.png)

![Dashboard Screenshot Page2](https://github.com/yunwe/data_projects/blob/main/ravenstack/power_bi/screenshots/pg2.png)

