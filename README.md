# 📊 SQL Data Analyst Portfolio Project

Welcome to my SQL Data Analyst Portfolio Project!  
This project showcases core analytical techniques and reporting skills used in real-world business intelligence work, covering everything from trend analysis to customer and product reporting.

---

## 📁 Project Overview

This project is a comprehensive SQL-based analysis that demonstrates the use of various analytical techniques and reporting formats using structured business data (such as sales, transactions, and customer profiles).

The goal is to derive actionable insights that help drive decisions across marketing, operations, and sales.

---

## 🧠 Key Analytical Techniques Used

## 🔍 Part 1: Exploratory Data Analysis (EDA)

This section focuses on uncovering initial patterns, trends, and summary insights from the data using foundational SQL techniques.

### 1️⃣ Database Exploration
- Explored the overall structure of the database.
- Identified all tables and their relationships using schema inspection queries.
- Reviewed columns, data types, and constraints to understand the dataset context.

### 2️⃣ Dimensions Exploration
- Focused on analyzing dimension tables (e.g., Customers, Products, Categories).
- Verified the uniqueness and completeness of primary key columns.
- Checked for hierarchical or categorical groupings used for segmentation.

### 3️⃣ Date Range Exploration
- Determined the earliest and latest dates available in transactional or event-based tables.
- Helped define the time span of data availability for accurate trend analysis.
- Identified gaps or irregularities in temporal data.

### 4️⃣ Measures Exploration (Key Metrics)
- Calculated key aggregated values such as totals, averages, and counts.
- Provided quick insights into volume and central tendencies of business activities.
- Useful for detecting high-level patterns and anomalies.

### 5️⃣ Magnitude Analysis
- Quantified and grouped data across dimensions such as region, category, and customer type.
- Helped understand which segments contribute most to key measures like sales or quantity.
- Used `GROUP BY`, `ORDER BY`, and aggregate functions (`SUM()`, `COUNT()`, `AVG()`).

### 6️⃣ Ranking Analysis
- Ranked entities such as products or customers by performance metrics like sales or frequency.
- Identified top performers and underperformers.
- Applied window functions like `RANK()`, `DENSE_RANK()`, and `ROW_NUMBER()` for detailed sorting.


## 📈 Part 2: Advanced Analytics

This section includes deep-dive analyses designed to answer strategic business questions, track KPIs, and produce detailed performance reports.

Advanced analytics includes:

### 1️⃣ Change Over Time
- Analyzed how a measure (e.g. sales, orders) evolves over time.
- Used to identify trends, patterns, and seasonality in the business.
- Enables better forecasting and capacity planning.

### 2️⃣ Cumulative Analysis
- Aggregated metrics progressively over time (e.g. cumulative sales).
- Helps understand long-term business growth or decline.
- Useful for measuring momentum or identifying plateaus.

### 3️⃣ Performance Analysis
- Compared current values to target benchmarks.
- Used to measure success against business goals.
- Supported performance reviews and operational feedback loops.

### 4️⃣ Part-to-Whole Analysis
- Evaluated how individual components (e.g. categories, products) contribute to the overall.
- Helps identify which areas have the most impact on revenue or performance.
- Drives strategic focus on high-impact segments.

### 5️⃣ Data Segmentation
- Grouped data based on defined ranges (e.g. age groups, spending bands).
- Allowed identification of patterns and correlations between two or more variables.
- Key to personalizing campaigns and strategies.

---

## 📈 Report Highlights

### 📋 Customer Report
A comprehensive report aggregating customer-level behavior and performance.

**Key Features:**
- Captures basic fields: name, age, transaction history.
- Segments customers into categories: **VIP**, **Regular**, and **New**.
- Segments customers by age group for demographic analysis.

**Aggregated Metrics:**
- Total orders  
- Total sales  
- Total quantity purchased  
- Total products bought  
- Lifespan (months since first to last purchase)

**Calculated KPIs:**
- **Recency**: Months since last order  
- **Average Order Value (AOV)**  
- **Average Monthly Spend**

---

### 📦 Product Report
A detailed breakdown of product performance across multiple metrics.

**Key Features:**
- Captures essential fields: product name, category, subcategory, and cost.
- Segments products based on revenue:
  - **High-Performers**
  - **Mid-Range**
  - **Low-Performers**

**Aggregated Metrics:**
- Total orders  
- Total sales  
- Total quantity sold  
- Unique customers  
- Lifespan (months since first to last sale)

**Calculated KPIs:**
- **Recency**: Months since last sale  
- **Average Order Revenue (AOR)**  
- **Average Monthly Revenue**

---

## 🛠️ Tools & Technologies

- **SQL** (MySQL/PostgreSQL)
- **CTEs**, **window functions**, **aggregate functions**
- `FILTER`, `CASE WHEN`, `crosstab()` (for pivoting)
- Strong focus on **clean, readable, and efficient SQL**

---

## 🧾 Learnings and Takeaways

- Built end-to-end SQL logic for business-critical reports.
- Learned how to apply different types of analytical methods to solve practical problems.
- Practiced translating raw data into strategic insights.
- Gained confidence with advanced SQL features like window functions, conditional aggregation, and data segmentation.


---

## 📬 Contact

If you have any feedback or would like to collaborate, feel free to connect with me!

- 📧 Email: Yraaj2002@gmail.com  
- 💼 LinkedIn: [Yash Raj LinkedIn](https://www.linkedin.com/in/yash-raj-46a024242/)
