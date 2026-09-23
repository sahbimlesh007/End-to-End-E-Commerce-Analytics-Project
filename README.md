# 🛒 End-to-End E-Commerce Analytics Project

## 📌 Project Overview

This project is an end-to-end E-Commerce Analytics solution built using **PostgreSQL** and **Power BI**. The objective is to transform raw e-commerce transactional data into actionable business insights that support strategic decision-making.

## Dataset: https://www.kaggle.com/datasets/bimleshkumarsah/olist-store-dataset

Using the **Olist Brazilian E-Commerce Dataset**, the project covers the complete analytics workflow including:

* Database Design
* Data Loading & Transformation
* SQL Analytics
* Data Modeling
* Business KPI Development
* Power BI Dashboarding
* Business Insights & Recommendations

The solution enables stakeholders to monitor sales performance, customer behavior, product trends, logistics efficiency, payment preferences, seller performance, and customer satisfaction from a single analytical platform.

---

# 🚀 Business Problem

E-commerce organizations generate large volumes of data from multiple sources such as:

* Customers
* Orders
* Products
* Sellers
* Payments
* Reviews
* Logistics

Without a centralized analytics solution, it becomes difficult to answer key business questions such as:

* What are the top-performing products and categories?
* Which customers generate the highest revenue?
* How efficient is the delivery process?
* Which sellers contribute the most revenue?
* How does customer satisfaction impact sales?
* What are the sales trends over time?

This project addresses these challenges through a robust analytical reporting system.

---

# 🛠️ Technology Stack

### Database

* PostgreSQL

### Data Processing

* SQL
* Views
* Indexing
* Query Optimization

### Business Intelligence

* Power BI
* DAX

### Dataset

* Olist Brazilian E-Commerce Dataset

---

# 📂 Project Architecture

```text
Raw CSV Files
       │
       ▼
 PostgreSQL Database
       │
       ▼
 Data Cleaning & Validation
       │
       ▼
 Relational Data Modeling
       │
       ▼
 SQL Views & Analytics
       │
       ▼
 Power BI Data Model
       │
       ▼
 DAX Measures
       │
       ▼
 Interactive Dashboards
       │
       ▼
 Business Insights
```

---

# 🗄️ Database Design

The project follows a relational database design using multiple interconnected tables.

### Core Tables

* Customers
* Orders
* Order Items
* Products
* Sellers
* Payments
* Reviews
* Geolocation
* Product Category Translation

### Relationships

```text
Customers
    │
    ▼
 Orders
    │
    ├────────► Payments
    │
    ├────────► Reviews
    │
    ▼
Order Items
    │
    ├────────► Products
    │
    └────────► Sellers
```

---

# 🔍 Data Preparation

The following steps were performed before analysis:

### Data Loading

* Imported CSV files into PostgreSQL using COPY commands

### Data Validation

* Row count verification
* Null value checks
* Duplicate record checks
* Primary key validation

### Performance Optimization

* Index creation on:

  * order_id
  * customer_id
  * seller_id
  * product_id
  * order_purchase_timestamp

---

# 📊 Power BI Dashboard Pages

## Executive Overview

Provides a high-level summary of business performance.

### KPIs

* Total Revenue
* Total Orders
* Total Customers
* Average Order Value
* Revenue Growth %
* Total Sellers

---

## Sales Analytics

Analyzes sales performance over time.

### Metrics

* Monthly Revenue Trend
* Revenue by Category
* Revenue by State
* Top Products
* Top Categories

---

## Customer Analytics

Provides customer behavior insights.

### Metrics

* Customer Growth
* Repeat Customers
* Customer Distribution
* Customer Lifetime Contribution

---

## Product Analytics

Evaluates product performance.

### Metrics

* Best-Selling Products
* Category Revenue
* Product Popularity
* Revenue Contribution %

---

## Logistics Performance

Measures operational efficiency.

### Metrics

* Delivery Time
* Shipping Duration
* Delayed Orders
* On-Time Delivery %

---

## Seller Performance

Analyzes marketplace sellers.

### Metrics

* Revenue by Seller
* Seller Ratings
* Seller Order Volume
* Top Performing Sellers

---

## Payment Analytics

Provides payment behavior insights.

### Metrics

* Payment Type Distribution
* Installment Analysis
* Payment Trends

---

## Review Analytics

Measures customer satisfaction.

### Metrics

* Average Rating
* Review Distribution
* Customer Sentiment Trends

---

# 📈 DAX Measures

Key business measures developed in Power BI:

```DAX
Total Revenue
Total Orders
Total Customers
Average Order Value

Revenue LY
Revenue YTD

YoY Growth %

On Time Delivery %

Average Review Score

Repeat Customer Rate
```

### Functions Used

```DAX
CALCULATE()
SUMX()
AVERAGEX()
DIVIDE()
SELECTEDVALUE()
DATESINPERIOD()
SAMEPERIODLASTYEAR()
GENERATESERIES()
```

---

# 🔎 SQL Analytics Performed

The project includes analytical SQL queries for:

* Sales Trend Analysis
* Customer Segmentation
* Revenue Analysis
* Product Performance
* Seller Performance
* Payment Behavior
* Delivery Performance
* Customer Reviews Analysis

Techniques Used:

* JOINs
* CTEs
* Window Functions
* Aggregate Functions
* CASE Statements
* Date Functions
* ARRAY_AGG()
* DATE_TRUNC()

---

# 💡 Key Business Insights

### Sales

* Certain product categories contribute the majority of revenue.
* Revenue shows seasonal purchasing patterns.

### Customers

* Repeat customers generate significantly higher revenue.
* Customer concentration exists in specific states.

### Logistics

* Delivery delays negatively impact customer ratings.
* Faster deliveries are associated with higher satisfaction scores.

### Payments

* Credit card payments dominate transactions.
* Installment purchases represent a significant share of revenue.

### Sellers

* A small group of sellers contributes a large percentage of total revenue.

---

# 🎯 Business Impact

This analytics solution enables organizations to:

* Monitor business performance in real time
* Improve customer experience
* Optimize delivery operations
* Identify high-performing products
* Evaluate seller performance
* Increase profitability through data-driven decisions

---



# 📦 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/end-to-end-ecommerce-analytics.git
```

### Navigate to Project

```bash
cd end-to-end-ecommerce-analytics
```

### Create Database

```sql
CREATE DATABASE ecommerce_analytics;
```

### Execute SQL Scripts

```sql
-- Create Tables
create_tables.sql

-- Load Data
load_data.sql

-- Create Views
views.sql
```

### Connect Power BI

1. Open Power BI Desktop
2. Connect to PostgreSQL Database
3. Import BI Views
4. Refresh Data
5. Explore Dashboards

---

# 📚 Skills Demonstrated

* PostgreSQL
* SQL Analytics
* Data Modeling
* Database Design
* Data Cleaning
* Query Optimization
* Business Intelligence
* Power BI
* DAX
* Dashboard Development
* KPI Design
* Business Analytics
* Data Storytelling

---

# 👨‍💻 Author

**Bimlesh Sah**

Data Analyst | Business Intelligence Developer | Data Science Enthusiast

GitHub:
https://github.com/sahbimlesh007

LinkedIn:
https://linkedin.com/in/bimlesh-sah

---

# ⭐ Project Highlights

✔ End-to-End Analytics Solution

✔ PostgreSQL Database Design

✔ Advanced SQL Analytics

✔ Query Optimization & Indexing

✔ Power BI Dashboard Development

✔ Business KPI Tracking

✔ Real-World E-Commerce Use Case

✔ Recruiter-Friendly Portfolio Project

---

### © 2026 Bimlesh Sah

### End-to-End E-Commerce Analytics Project
