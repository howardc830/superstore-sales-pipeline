# superstore-sales-pipeline

## Overview
Built a complete data analytics pipeline analyzing 9,800 retail 
transactions from the Superstore Sales dataset. The pipeline covers 
the full analytics workflow: data cleaning in Python, database storage 
in PostgreSQL, business intelligence queries in SQL, and an interactive 
3-page executive dashboard in Power BI.

## Tools & Technologies
- **Python** (pandas, SQLAlchemy) — data cleaning and pipeline
- **PostgreSQL** — database storage and SQL analysis
- **Power BI** — interactive executive dashboard
- **SQL** — business intelligence queries

## Dataset
- **Source:** Superstore Sales Dataset by Rohit Sahoo (Kaggle)
- **Link:** https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting
- **Size:** 9,800 transactions, 18 columns

## Pipeline Architecture
Raw CSV → Python Cleaning → PostgreSQL Database → SQL Queries → Power BI Dashboard

## SQL Business Queries
1. Total sales by Region
2. Top 10 products by revenue
3. Sales by Category
4. Monthly sales trend
5. Sales by Customer Segment

## Key Findings
- **West region leads** with $710K in total sales — 30% more than South
- **Technology is the top category** at $827K, narrowly ahead of Furniture ($729K)
- **Consumer segment dominates** at $1.14M — 50.76% of total revenue
- **Canon imageCLASS 2200 Copier** is the #1 product at $61.6K — nearly double #2
- **November is peak sales month** — likely driven by Black Friday promotions
- **Total revenue: $2.26M** across all regions, categories and segments

## Dashboard Screenshots
### Sales Overview
<img width="974" height="542" alt="Sales Overview Dashboard" src="https://github.com/user-attachments/assets/f9eb8611-06b6-4822-b2d2-f6b56199ddf7" />


### Product Analysis
<img width="971" height="545" alt="Product Analysis" src="https://github.com/user-attachments/assets/001992dc-6773-4327-876e-89e0c6a64018" />



### Sales Trend
<img width="973" height="544" alt="Monthly Sales Trend" src="https://github.com/user-attachments/assets/141f9e5b-6a24-4fda-b117-4e5e796e8971" />


## What I Learned
- How to build an end-to-end analytics pipeline connecting Python, 
  PostgreSQL and Power BI
- How to load and query data from PostgreSQL using SQLAlchemy
- How PostgreSQL requires quoted column names for case-sensitive fields
- How to build a multi-page executive dashboard in Power BI
- How to identify seasonal sales patterns using time series visualization
