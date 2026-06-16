# 🛍️ Retail Customer Behavior Analysis using Python, SQL, PostgreSQL & Power BI

## 📌 Project Overview

This project explores customer shopping behavior using a retail transaction dataset containing 3,900 purchase records. The objective was to gain hands-on experience in data cleaning, exploratory data analysis, SQL-based business analysis, and dashboard development.

The project focuses on understanding customer purchasing patterns, subscription behavior, product performance, and revenue trends using Python, PostgreSQL, SQL, and Power BI.

---

## 🎯 Business Problem

A retail company wants to better understand its customers and identify factors that influence purchasing behavior.

Key questions explored:

* Which customer groups contribute the most revenue?
* How do purchasing patterns vary across demographics?
* What impact do discounts and subscriptions have on customer spending?
* Which products and categories perform best?
* How can customer insights support better business decisions?

---

## 📊 Dataset Information

### Dataset Summary

* Total Records: 3,900
* Total Features: 18
* Dataset Type: Retail Customer Transactions

### Key Attributes

#### Customer Information

* Customer ID
* Age
* Gender
* Location
* Subscription Status

#### Purchase Information

* Item Purchased
* Category
* Purchase Amount
* Season
* Size
* Color

#### Behavioral Information

* Discount Applied
* Review Rating
* Shipping Type
* Previous Purchases
* Frequency of Purchases

---

## ⚙️ Data Cleaning & Preprocessing

The following preprocessing steps were performed using Python and Pandas:

* Loaded and inspected the dataset
* Checked data types and summary statistics
* Identified missing values
* Imputed missing review ratings using median values
* Standardized column names using snake_case formatting
* Created age group categories for customer segmentation
* Created purchase frequency features for analysis
* Removed redundant fields where appropriate
* Prepared cleaned data for database integration

---

## 🛠️ Tools & Technologies

### Programming & Analysis

* Python
* Pandas
* NumPy

### Database

* PostgreSQL
* SQL

### Visualization

* Power BI

### Development Environment

* Jupyter Notebook

### Version Control

* GitHub

---

## 🗄️ Database Integration

The cleaned dataset was loaded into PostgreSQL for structured querying and business analysis.

### Main Table

customer

Key fields include:

* customer_id
* age
* gender
* category
* purchase_amount
* subscription_status
* shipping_type
* discount_applied
* age_group
* purchase_frequency_days

---

## 🔍 Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand customer behavior and transaction patterns.

Areas explored:

* Customer demographics
* Revenue distribution
* Product category performance
* Subscription behavior
* Review ratings
* Purchase frequency
* Discount usage patterns
* Shipping preferences

---

## 📈 SQL Analysis Performed

Several SQL queries were written to answer business-related questions.

### Analysis Topics

1. Revenue by Gender
2. High-Spending Customers Using Discounts
3. Top Rated Products
4. Shipping Type Comparison
5. Subscribers vs Non-Subscribers
6. Discount-Dependent Products
7. Customer Segmentation
8. Top Products by Category
9. Repeat Buyers and Subscription Trends
10. Revenue Contribution by Age Group

---

## 📊 Power BI Dashboard

An interactive dashboard was developed in Power BI to visualize business insights.

### Dashboard Highlights

* Total Customers
* Average Purchase Amount
* Average Review Rating
* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Customer Distribution by Subscription Status

### Dashboard Preview

(Add dashboard screenshots here)

---

## 📈 Key Insights

### Customer Revenue

* Male customers contributed a higher share of total revenue compared to female customers.

### Customer Loyalty

* Loyal customers represented the largest customer segment.

### Discount Usage

* Customers using discounts still demonstrated strong purchasing activity.

### Subscription Trends

* Subscription behavior showed opportunities for customer retention programs.

### Shipping Preferences

* Customers using express shipping showed slightly higher spending patterns.

---

## 💡 Business Recommendations

Based on the analysis:

* Strengthen customer loyalty programs.
* Promote subscription-based benefits.
* Use customer segmentation for targeted marketing.
* Focus campaigns on high-performing product categories.
* Monitor discount strategies to balance customer engagement and profitability.

---

## 📁 Project Structure

Customer_Shopping_Behavior_Analysis/

│

├── customer_shopping_behavior.csv

├── customer_behavior.sql

├── Customer_Shopping_Behavior_Analysis.ipynb

├── Customer_Behavior_Dashboard.pbix

├── Business Problem Document.pdf

├── Customer Shopping Behavior Analysis.pdf

├── README.md

└── LICENSE

---

## 🚀 Skills Demonstrated

### Technical Skills

* Python
* SQL
* PostgreSQL
* Power BI
* Pandas
* Data Visualization

### Data Analytics Skills

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Business Analysis
* Dashboard Development

### Professional Skills

* Problem Solving
* Analytical Thinking
* Data Interpretation
* Reporting & Presentation

---

## 📚 Learning Outcomes

This project provided practical experience in:

* Working with real-world retail datasets
* Cleaning and preparing data for analysis
* Writing SQL queries for business insights
* Building interactive Power BI dashboards
* Communicating findings through reports and visualizations

---

## 📌 Conclusion

This project demonstrates an end-to-end data analytics workflow using Python, SQL, PostgreSQL, and Power BI. Through customer behavior analysis, the project highlights how transactional data can be explored, analyzed, and visualized to support business understanding and informed decision-making.


