# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes **3,900 customer transactions** to identify key patterns in purchasing behavior, customer segmentation, and product performance.

The objective is to transform raw transactional data into **actionable business insights** that can improve marketing strategies, customer retention, and revenue growth.

## 🎯 Business Problem

A retail business wants to understand how customer behavior varies across demographics, product categories, and purchasing patterns.

**Key Question:**
How can customer shopping data be used to:

* Increase revenue
* Improve customer engagement
* Optimize marketing strategies

## 📊 Dataset Details

* **Total Records:** 3,900 transactions
* **Features:** 18 columns

### Key Data Includes:

* Customer demographics (Age, Gender, Location)
* Purchase details (Item, Category, Amount, Season)
* Behavioral data (Discount usage, Ratings, Frequency, Subscription)

## ⚙️ Data Processing

* Handled missing values using median imputation
* Standardized column names
* Performed feature engineering:

  * Age groups
  * Purchase frequency

## 🛠️ Tools & Technologies

* **Python (Pandas)** → Data cleaning & preprocessing
* **PostgreSQL** → Data storage & SQL analysis
* **Power BI** → Data visualization & dashboard

## 🗄️ Database Design

The dataset is stored in PostgreSQL as a structured table.

**Table: `customer`**

Includes:

* customer_id, age, gender
* item_purchased, category, purchase_amount
* subscription_status, shipping_type, discount_applied
* age_group, purchase_frequency_days

## 🔍 Analysis Performed

### 1. Data Preparation (Python)

* Data cleaning
* Handling missing values
* Feature engineering

### 2. SQL-Based Analysis

Key queries:

* Revenue comparison by gender
* High-spending customers using discounts
* Top-performing product categories
* Customer segmentation (New, Returning, Loyal)
* Subscription vs non-subscription behavior
* Revenue distribution by age group
* Impact of shipping type on spending

## 📊 Power BI Dashboard

An interactive dashboard was built to visualize:

* Revenue by category
* Sales trends over time
* Customer distribution
* Age group analysis

## 📈 Key Insights

* Male customers contribute a higher share of total revenue compared to female customers
* Discount usage does not reduce spending — high-value customers still utilize discounts
* Loyal customers form the largest and most valuable segment
* Express shipping users tend to spend slightly more
* Certain product categories consistently outperform others

## 💡 Business Recommendations

* Implement loyalty programs to retain high-value customers
* Use targeted discounts without fear of reducing revenue
* Focus marketing on high-performing product categories
* Promote subscription-based benefits
* Prioritize high-value customer segments

## 📈 Business Impact

* Enables better customer segmentation for targeted marketing
* Improves decision-making for product and inventory strategies
* Helps identify revenue-driving customer groups
* Supports data-driven business growth

## 🚀 How to Use

1. Import the `.sql` file into PostgreSQL
2. Load the dataset and execute SQL queries
3. Open the Power BI dashboard (`.pbix`)
4. Review analysis using the notebook (if included)

## 📁 Project Structure

* `customer_behavior.sql` → Database schema & data
* `customer_shopping_behavior.csv` → Raw dataset
* `Customer_Behavior_Dashboard.pbix` → Power BI dashboard
* `Business Problem Document.pdf` → Problem definition
* `Customer Shopping Behavior Analysis.pdf` → Detailed report
* `README.md` → Project documentation

## 🚀 Skills Demonstrated

* Data Cleaning & Preprocessing (Python)
* SQL Querying & Data Analysis (PostgreSQL)
* Data Visualization (Power BI)
* Business Insight Generation

## 📌 Conclusion

This project demonstrates how raw customer data can be transformed into meaningful insights that drive **better business decisions, improved customer engagement, and increased profitability**.

