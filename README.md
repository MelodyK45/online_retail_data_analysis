This project analyzes an online retail dataset to uncover sales trends, customer behavior, and business insights. Using Python, the dataset was cleaned, explored, and analyzed to support data-driven decision-making.

The analysis focuses on:

Sales performance over time

Customer segmentation

Product and country performance

Actionable business recommendations

Objectives

Clean and prepare raw retail transaction data

Perform exploratory data analysis (EDA)

Analyze monthly sales trends (time series)

Segment customers using RFM analysis

Visualize key business metrics

Generate insights and recommendations

Dataset

Source: Online Retail Dataset

Records: ~541,000 (before cleaning)

Final Records: ~392,000 (after cleaning)

Key Features:

InvoiceNo

StockCode

Description

Quantity

InvoiceDate

UnitPrice

CustomerID

Country

Data Cleaning Steps

Removed duplicate records

Dropped rows with missing CustomerID and Description

Removed cancelled transactions

Filtered out negative or zero quantities and prices

Converted date columns to datetime format

Created a new feature: TotalPrice

Analysis Performed
1. Descriptive Statistics

Summary statistics for quantity, price, and total sales

Dataset structure and unique counts

2. Time Series Analysis

Monthly aggregation of sales

Identification of seasonal trends

3. Customer Segmentation (RFM)

Recency: Days since last purchase

Frequency: Number of purchases

Monetary: Total customer spend

Customer segments such as:

Champions

Loyal Customers

At Risk

Hibernating

4. Visualizations

Monthly sales trend

Top products by revenue

Sales by country

Customer segment distribution

🔍 Key Insights

Sales show strong seasonal patterns

A small number of products generate most revenue

The UK dominates total sales

High-value customers contribute disproportionately to revenue

A large segment of customers is at risk of churn

Recommendations

Leverage peak sales periods with targeted marketing

Focus on high-performing products

Introduce loyalty and retention strategies

Expand marketing efforts to international markets

Use customer segmentation to personalize campaigns

🛠 Tools & Technologies

Python

Pandas

Matplotlib

Jupyter Notebook
├── data/
│   └── online_retail_cleaned.csv
├── notebooks/
│   └── online_retail_analysis.ipynb
├── README.md
