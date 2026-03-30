# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using a transactional dataset of 3,900 records to uncover patterns in spending, customer segmentation, and product preferences. The goal is to convert raw data into actionable insights for improving business performance.


## 🎯 Business Problem

A retail company wants to understand how customer behavior varies across demographics, product categories, and purchasing patterns to improve sales, customer engagement, and retention.

**Key Question:**
How can customer shopping data be used to identify trends, improve engagement, and optimize marketing strategies?

## 📊 Dataset Details

* **Total Records:** 3,900 transactions
* **Features:** 18 columns

### Key Data Includes:

* Customer demographics (Age, Gender, Location)
* Purchase details (Item, Category, Amount, Season)
* Behavioral data (Discount, Review Rating, Frequency, Subscription)

### Data Processing:

* Missing values handled using median imputation
* Column names standardized
* Feature engineering applied:
* Age groups
* Purchase frequency

## ⚙️ Tools & Technologies

* **Python (Pandas)** → Data cleaning & preprocessing
* **PostgreSQL** → Data storage & SQL analysis
* **Power BI** → Data visualization & dashboard

  
## 🗄️ Database Design

The dataset is stored in PostgreSQL using a structured table:

**Table: customer**

Includes fields such as:

* customer_id, age, gender
* item_purchased, category, purchase_amount
* subscription_status, shipping_type, discount_applied
* age_group, purchase_frequency_days

**🔍 Analysis Performed**

1. Data Preparation (Python)

* Data cleaning and preprocessing
* Handling missing values
* Feature engineering

**2. SQL-Based Analysis**

Key business queries:

* Revenue comparison by gender
* High-spending discount users
* Top-rated products
* Customer segmentation (New, Returning, Loyal)
* Subscription vs non-subscription analysis
* Revenue by age group
* Shipping type impact on spending

**3. Power BI Dashboard**

An interactive dashboard was created to visualize:

* Revenue by category
* Sales trends
* Customer distribution
* Age-group analysis

**📈 Key Insights**

* Male customers generate higher total revenue compared to female customers
* Discounts do not reduce spending — high-value customers still use discounts
* Loyal customers form the largest segment
* Express shipping users tend to spend slightly more
* Certain product categories consistently perform better

**💡 Business Recommendations**

* Implement loyalty programs to retain customers
* Optimize discount strategies to maintain profitability
* Focus marketing on high-performing products
* Promote subscription-based benefits
* Target high-value customer segments

**📁 Project Structure**

Customer-Shopping-Behavior-Analysis/
│
├── customer_behavior.sql
├── customer_shopping_behavior.csv
├── Customer_Behavior_Dashboard.pbix
├── Customer_Shopping_Behavior_Analysis.ipynb
├── Business Problem Document.pdf
├── Customer Shopping Behavior Analysis.pdf
└── README.md

**🚀 How to Use**

1. Import the `.sql` file into PostgreSQL
2. Load the dataset and run SQL queries
3. Open the Power BI dashboard (`.pbix`)
4. Refer to the notebook for data preprocessing


**📊 Outcome**

This project demonstrates how data can be cleaned, analyzed, and visualized to generate meaningful insights that support business decision-making.
