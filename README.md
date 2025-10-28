# 🛒 Customer Behavior Analysis in E-Commerce

## 📘 Project Overview

This project focuses on analyzing **customer behavior in an e-commerce platform** using data-driven insights. The goal is to identify key trends in purchasing patterns, customer segmentation, product performance, and overall business metrics.
The analysis integrates **SQL** for data extraction, **Python (Jupyter Notebook)** for preprocessing and exploratory analysis, and **Power BI** for interactive dashboard visualizations.

---

## 🎯 Objectives

* Understand customer purchasing behavior and spending trends.
* Identify high-value customers and product categories.
* Analyze discounts, stock availability, and sales revenue.
* Visualize performance metrics using Power BI dashboards.
* Provide data-driven insights to support marketing and sales strategies.

---

## 🧩 Tools & Technologies

| Tool                            | Purpose                                                      |
| ------------------------------- | ------------------------------------------------------------ |
| **MySQL**                       | Data storage, cleaning, and transformation using SQL queries |
| **Python (Jupyter Notebook)**   | Data preprocessing, analysis, and integration with SQL       |
| **Pandas, Matplotlib, Seaborn** | Data manipulation and visualization in Python                |
| **Power BI**                    | Dashboard creation and interactive visualization             |
| **Excel/CSV**                   | Data import and initial exploration                          |

---

## 🗂️ Dataset

The dataset contains e-commerce transaction records, including:

* Customer demographics and IDs
* Product details (name, category, MRP, discount, stock status)
* Purchase quantities and prices
* Order dates and revenue metrics

> Example Table: `customer_behavior`
> Columns: `CustomerID`, `Name`, `Category`, `MRP`, `DiscountPercent`, `OutOfStock`, `Quantity`, `TotalPrice`, `OrderDate`

---

## 🔍 Steps Performed

### 1. **Data Extraction (SQL)**

* Imported dataset into **MySQL** database.
* Executed SQL queries to clean and filter data.
* Performed analysis such as:

  * Top 10 best-value products (by discount percentage)
  * Out-of-stock high-MRP items
  * Estimated revenue per category
  * Monthly sales trends

### 2. **Data Analysis (Python)**

* Connected MySQL database to Jupyter Notebook using `SQLAlchemy` and `PyMySQL`.
* Performed:

  * Data cleaning (handling missing values, duplicates)
  * Descriptive analysis and feature engineering
  * Visualization (sales trend, top customers, product distribution)

### 3. **Data Visualization (Power BI)**

* Connected Power BI to the MySQL database.
* Designed an **interactive dashboard** showing:

  * Revenue trends and category performance
  * Customer purchase frequency
  * Product sales by discount and availability
  * Top 5 customers and top 10 products by revenue

---

## 📊 Key Insights

* High discount percentages significantly boost purchase frequency.
* Electronics and fashion categories have the highest average order value.
* Certain high-MRP products are frequently out of stock, impacting sales potential.
* A small percentage of repeat customers contribute to the majority of revenue.

---



---

## 🏁 Conclusion

This project demonstrates how **data analysis using SQL, Python, and Power BI** can uncover valuable insights about customer behavior in e-commerce. The findings can help improve marketing strategies, optimize inventory, and enhance overall customer experience.
