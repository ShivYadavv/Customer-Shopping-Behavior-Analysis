# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover customer purchasing patterns, product preferences, subscription behavior, and revenue-driving factors to support data-driven business decisions.

## Business Problem
Retail businesses generate large amounts of customer transaction data, but valuable insights often remain hidden. This project leverages Python, PostgreSQL, and Power BI to transform raw customer data into actionable business intelligence.

## Dataset Information
- Records: 3,900
- Features: 18
- Data Categories:
  - Customer Demographics
  - Purchase Details
  - Shopping Behavior
  - Subscription Information
  - Product Reviews
  - Shipping Preferences

## Technology Stack
- Python
- Pandas
- NumPy
- PostgreSQL
- SQL
- Power BI
- Git & GitHub

---

## Project Workflow

### 1. Data Cleaning & Preparation (Python)
- Imported and explored data using Pandas
- Handled missing values in Review Rating using category-wise median imputation
- Standardized column names using snake_case convention
- Performed feature engineering:
  - Age Group Segmentation
  - Purchase Frequency Features
- Removed redundant columns
- Validated data quality and consistency

### 2. Database Integration (PostgreSQL)
- Connected Python with PostgreSQL
- Loaded cleaned dataset into PostgreSQL
- Performed SQL-based business analysis

### 3. Business Analysis Using SQL

Key business questions answered:

#### Revenue Analysis
- Revenue by Gender
- Revenue by Age Group

#### Customer Analysis
- Customer Segmentation (New, Returning, Loyal)
- Repeat Buyers vs Subscription Status

#### Product Analysis
- Top 5 Highest Rated Products
- Top 3 Products per Category
- Discount-Dependent Products

#### Sales Analysis
- High-Spending Discount Users
- Shipping Type Comparison
- Subscribers vs Non-Subscribers Revenue Comparison

---

## Dashboard Development (Power BI)

An interactive Power BI dashboard was created to visualize:

### KPIs
- Total Customers
- Average Purchase Amount
- Average Review Rating

### Visualizations
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Distribution
- Customer Filters
- Shipping Type Analysis

---

## Key Insights

- Male customers generated significantly higher revenue than female customers.
- Clothing category contributed the highest revenue and sales volume.
- Loyal customers represented the largest customer segment.
- Express shipping users showed slightly higher average purchase amounts.
- Subscription adoption remains relatively low, presenting growth opportunities.
- Certain products showed strong dependency on discounts for sales.

---

## Business Recommendations

### Increase Subscription Adoption
Offer exclusive discounts and loyalty rewards to encourage subscription enrollment.

### Strengthen Customer Loyalty Programs
Reward repeat customers and incentivize long-term engagement.

### Optimize Discount Strategy
Balance promotional discounts with profitability goals.

### Improve Product Positioning
Highlight top-rated and best-selling products in marketing campaigns.

### Target High-Value Segments
Focus marketing efforts on high-revenue age groups and loyal customers.

---


## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Querying
- PostgreSQL Integration
- Business Intelligence
- Dashboard Design
- Data Visualization
- Business Insight Generation

---

## Author

**Shiv Yadav**
MBA (Data Science)

If you found this project useful, feel free to star ⭐ the repository.
