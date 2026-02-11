# Customer Shopping Behavior Analysis

Transforming Retail Data into Business Intelligence

# Project Snapshot

This project explores 3,900 real-world customer transactions to uncover deep insights into purchasing behavior, customer loyalty, discount impact, and revenue drivers.

By combining Python for data processing, MySQL for structured analysis, and Power BI for visualization, this project demonstrates a complete end-to-end data analytics workflow.

# Business Objective

Retail businesses generate massive transaction data, but actionable insights drive real value.

This project answers critical business questions:

Who generates the most revenue?

Do discounts increase high-value purchases?

Are subscribers more profitable?

Which products depend heavily on discounts?

How does customer age influence revenue?

What factors drive repeat purchases?

# Dataset Overview

3,900 purchase records

18 analytical features

37 missing values handled in review ratings

Customer demographics + transactional behavior + subscription data

Core Data Categories

Customer Information
Age, Gender, Location, Subscription Status

Purchase Details
Item, Category, Amount, Season, Size, Color

Behavioral Indicators
Discount Applied, Purchase Frequency, Previous Purchases, Review Rating, Shipping Type

# End-to-End Workflow
1. Data Cleaning & Feature Engineering (Python)

Missing value treatment using category-wise median imputation

Standardized column names (snake_case format)

Created new features:

age_group segmentation

purchase_frequency_days

Removed redundant variables

Exported cleaned dataset to MySQL

2. Business Analysis (MySQL)

The cleaned dataset was loaded into MySQL to perform structured SQL analysis.

Key analytical insights include:

Revenue & Profitability

Revenue comparison by gender

Revenue contribution by age group

Subscriber vs Non-Subscriber revenue

Customer Behavior

Repeat buyers and subscription correlation

Customer segmentation: New, Returning, Loyal

Product Insights

Top 5 products by rating

Top 3 products per category

Discount-dependent products

Operational Insights

Shipping type impact on purchase amount

High-spending discount users

Power BI Interactive Dashboard

An executive-level dashboard was created to visually communicate insights.

# Dashboard KPIs:

Total Customers: 3.9K

Average Purchase Amount

Average Review Rating

Revenue by Category

Sales by Age Group

Subscription Distribution

Shipping Type Comparison

The dashboard allows dynamic filtering for deeper business exploration.

# Key Findings

Loyal customers form the largest customer segment.

Young Adults contribute the highest revenue share.

Express shipping customers show higher average spending.

Certain products rely heavily on discounts to drive sales.

Subscription does not always guarantee higher average spend — deeper targeting needed.

# Business Recommendations

Strengthen loyalty programs to retain high-value customers.

Optimize discount strategies to protect profit margins.

Promote high-rated products in marketing campaigns.

Personalize offers based on customer age segments.

Enhance subscription value proposition to increase adoption.

# Tech Stack

Python (Pandas, NumPy)
MySQL
SQL
Power BI
Data Cleaning & Feature Engineering
Business Analytics

# Project Architecture
Data Source → Python Cleaning → MySQL Database → SQL Analysis → Power BI Dashboard → Business Insights

What This Project Demonstrates

Strong data cleaning & preprocessing skills

Advanced SQL query writing in MySQL

Customer segmentation techniques

Business-focused analytical thinking

Data storytelling using Power BI

# Author

Pranav Bhagwat
Data Analyst | Business Intelligence Enthusiast
