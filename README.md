# E-commerce Customer Sales Analysis

Business-driven customer analytics project using Python and RFM analysis to uncover customer behavior, sales trends, and actionable business insights.

**Capstone Project for Google Data Analytics Professional Certificate**

## 🛠 Tech Stack

Python • Pandas • NumPy • Matplotlib • Seaborn • Jupyter Notebook • Git • GitHub

## 📊 Analytics Skills 

Data Cleaning • Exploratory Data Analysis (EDA) • RFM Customer Segmentation • Customer Analytics • Business Intelligence • Data Visualization 

## 🔄 Project Workflow 
Dataset

↓

Data Quality Assessment

↓

Data Cleaning

↓

Exploratory Data Analysis

↓

RFM Customer Segmentation

↓

Business Recommendations


## 📌 Project Overview 

This project analyzes customer purchasing behavior and sales performance using the Online Retail II dataset. 

The objective is to identify purchasing patterns, evaluate sales trends, and generate actionable business insights that support revenue growth and improve customer retention.

## 🎯 Business Objective 

The primary objective of this project is to analyze customer purchasing behavior and sales performance to identify opportunities for increasing revenue and improving customer retention. 

The analysis aims to support data-driven business decision-making through meaningful insights derived from transaction data.

## ❓ Business Questions

This project seeks to answer the following business questions:

- Which products generate the highest revenue?
- Which customers contribute the most sales?
- How do sales change over time?
- Which countries generate the highest revenue?
- What purchasing patterns can improve customer retention?


## Project Summary

| Metric | Value|
|--------|------|
|Dataset| Onlie RetailⅡ|
|Analysis Period| Dec 2009 - Dec 2011|
|Original Transactions| 1,067,371|
|Transactions After Cleaning | 1,028,001|
|Customers Analyzed|5,878|
|Countries|43|

## 📂 Dataset Overview

This project uses the **Online Retail II** dataset, which contains transactional records from a UK-based online retail company.

The dataset includes customer purchases made between **December 2009 and December 2011**, making it suitable for sales trend analysis, customer segmentation, and purchasing behavior analysis.

### Source

- **Dataset:** Online RetailⅡ
- **Provider:** UCI Machine Learning Repository 
- **Access:** Kaggle
- **Link:** https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci

### Key Variables

| Column | Description |
|---------|-------------|
| Invoice | Invoice number |
| InvoiceDate | Transaction date |
| Customer ID | Unique customer identifier |
| StockCode | Product code |
| Description | Product description |
| Quantity | Quantity purchased |
| Price | Unit price |
| Country | Customer country |

### Data Cleaning Summary 

The following processing steps were applied before analysis:

- Removed duplicate records
- Removed cancelled transactions (Invoice starting with "C")
- Removed transactions with non-positive quantities
- Removed transactions with non-positive unit prices
- Converted InvoiceDate to datetime format
- Created Total Sales feature (Quantity * Price)

### Data Files

```text
data/
├── raw/
│   └── (download from Kaggle)
└── processed/
    └── online_retail_cleaned.csv
```

> The raw dataset is not included in this repository due to file size limitations. 
> Please download it from the Kaggle link above.

## 📊 Exploratory Data Analysis

### 1. Sales Performance

The sales analysis examined monthly revenue, order volume, and average order value to identify long-term business trends and seasonal patterns.
<img width="1190" height="490" alt="image" src="https://github.com/user-attachments/assets/4942b510-2e0c-446a-9655-900516c21220" />


**Key Findings**

- Sales showed a clear upward trend over the analysis period.
- Revenue increased significantly during the holiday season.
- Order volume and revenue generally moved together, indicating healthy business growth.

### 2. Customer Activity

Customer activity was analyzed by tracking the number of active customers over time.

**Key Findings**

- The number of active customers increased steadily.
- Customer growth closely followed revenue growth.
- The business expanded both in customer acquisition and purchasing activity.

### 3. Geographic Analysis

Sales performance was compared across different countries to identify major international markets.

**Key Findings**

- The United Kingdom generated the largest share of revenue.
- To improve readability, visualizations focused on the top 10 countries by sales.
- Several non-UK markets showed strong revenue potential.

### 4. Product Analysis

Product performance was evaluated using sales revenue, purchasing quantity, and cumulative contribution.

**Key Findings**

- A small number of products generated a large share of total revenue.
- Product demand was highly concentrated.
- Pareto analysis confirmed that a limited number of products contributed most of the sales. 


### License

This dataset is distributed through Kaggle for educational and research purposes. Please refer to the dataset page for the latest licensing and usage terms.

### Data Dictionary

| Variable | Description |
|----------|-------------|
| Invoice | Invoice number |
| StockCode | Product code |
| Description | Product description |
| Quantity | Quantity purchased |
| InvoiceDate | Date and time of purchase |
| Price | Unit price |
| Customer ID | Customer identifier |
| Country | Customer country |

## Project Workflow

This project follows the Google Data Analytics Process.

- Ask
- Prepare
- Process
- Analyze
- Share
- Act

## Tools

- Excel
- SQL
- Tableau
- GitHub

## Repository Structure
data/
excel/
sql/
tableau/
presentation/
report/
images/
docs/

