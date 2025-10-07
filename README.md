# 🛍️ eCommerce Data Analysis — Exploratory Data Analysis (EDA) Project

## 📄 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a real-world eCommerce transactional dataset from a UK-based online retail company. The dataset contains customer transactions over a one-year period (from 1st Dec 2010 to 9th Dec 2011) and includes information such as invoice numbers, product details, quantities, prices, and customer locations.

The goal of this project is to extract meaningful business insights, understand customer purchasing behavior, and identify sales trends across different countries and time periods.

## 🎯 Objectives

Understand the dataset structure and clean missing or invalid data.

Identify top-performing countries and products based on orders and revenue.

Analyze customer purchasing trends across months, days, and hours.

Detect sales patterns — increase/decrease in orders over time.

Summarize key statistics and visualize trends for data-driven decisions.

## 🧠 Key Insights from EDA

Highest number of orders and revenue are from a specific country (UK).

Top 5 countries contribute the most to total sales and order volume.

Identified best-selling months and low-activity periods.

Detected missing transaction days and sales fluctuation periods.

Analyzed hourly order trends, showing peak sales hours.

## 📊 Dataset Description
Column Name	Description
InvoiceNo	Unique invoice number for each transaction
StockCode	Product code
Description	Product name
Quantity	Number of products purchased
InvoiceDate	Timestamp of each transaction
UnitPrice	Price per product unit
CustomerID	Unique ID for each customer
Country	Country name of the customer

## 🧰 Tools & Libraries Used

Python

Pandas – for data cleaning and manipulation

NumPy – for numerical computation

Matplotlib & Seaborn – for data visualization

Jupyter Notebook – for step-by-step analysis and visualization

## 📈 Steps Performed

Data Loading & Cleaning – handled missing values, duplicates, and invalid records.

Data Exploration – examined structure, data types, and statistical summary.

Feature Engineering – derived new time-based features like Month, Day, and Hour.

Univariate & Bivariate Analysis – identified top products, customers, and regions.

Visualization – plotted trends in sales and revenue using bar, line, and heat maps.

Insights & Conclusions – summarized findings to support data-driven business strategy.

## 💡 Business Impact

The analysis helps the company understand:

Which countries and customers drive the majority of revenue.

When (time/day/month) to expect peak sales.

How to plan marketing and stock management based on demand patterns.
