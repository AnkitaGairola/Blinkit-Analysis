# Project Overview

This project delivers an end-to-end retail sales analytics solution for Blinkit, focusing on sales performance, customer preferences, and outlet-level insights.
Using MySQL for querying, Python for exploratory analysis, and Power BI for interactive dashboards, the project transforms raw transactional data into actionable business intelligence.

The analysis supports data-driven decisions related to product strategy, outlet optimization, and revenue growth.


# Dataset

The dataset contains 8,523 retail sales records with the following attributes:

Sales Metrics: Sales amount, item count, ratings

Product Details: Item type, item fat content (Low Fat / Regular)

Outlet Information:

Outlet size (Small, Medium, High)

Outlet type (Supermarket Type 1, Type 2, Grocery Store, etc.)

Outlet location tier (Tier 1, Tier 2, Tier 3)

Time Dimension: Outlet establishment year

Analysis Scope: Complete historical sales data available in the dataset


# Tools & Technologies


Database & Querying	: MySQL

Programming & EDA	 :  Python (Pandas, NumPy, Matplotlib, Seaborn)

Visualization  :      Power BI

Calculations	:       SQL Aggregations, DAX

Data Processing :    	Power Query


#  Project Workflow

## 1. Data Preparation & Cleaning

Imported raw sales data into MySQL and Python

Cleaned inconsistent values (e.g., Low Fat, LF, reg)

Standardized column names and data types

Validated missing values and corrected categorical fields

## 2.  SQL Analysis (MySQL)

## Built queries to calculate KPIs:

Total Sales

Average Sales

Number of Items Sold

Average Rating

## Performed aggregations by:

Item type

Fat content

Outlet size

Outlet type

Location tier

Used grouped queries and percentage calculations for performance comparison


## 3. Python Analysis (Jupyter Notebook)

Conducted Exploratory Data Analysis using Pandas & NumPy

Created business-driven visualizations using Matplotlib & Seaborn, including:

Sales by item type

Sales by fat content

Outlet size contribution

Outlet establishment trend over time

Verified KPI values before dashboard development


## 4. Power BI Dashboard Development

Designed an interactive dashboard with:

 KPI cards (Sales, Avg Sales, Items, Rating)

 Donut charts for fat content contribution

 Bar charts for item type and outlet performance

 Line chart for outlet establishment trends

 Slicers for outlet size, location tier, and item category

Focused on clean layout, consistent color theme, and storytelling


# Key Insights

Total Sales reached $1.20M, with an average sale of $141

Low Fat products contribute the majority of revenue compared to Regular items

Tier 3 locations outperform Tier 1 and Tier 2 in total sales

Medium-sized outlets generate higher revenue than small and large outlets

Sales grew rapidly in early outlet establishment years and later stabilized


# Business Impact

This analysis demonstrates how retailers can use analytics to:

Optimize product mix based on customer preferences

Identify high-performing outlet types and locations

Improve inventory planning and forecasting

Support strategic decisions using KPI-driven dashboards


# Skills Demonstrated

MySQL | SQL | Python | Pandas | Power BI | DAX | Data Cleaning | EDA | KPI Design | Retail Analytics | Dashboard Design | Business Intelligence



