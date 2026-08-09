# Retail Store Sales Analysis

## Project Overview

This project analyzes retail store sales data to understand sales performance, customer transactions, products, payment methods, locations, and discount information.

## Dataset

The dataset contains 12,575 retail transactions from January 2022 to January 2025.

### Main Columns

- Transaction ID
- Customer ID
- Category
- Item
- Price Per Unit
- Quantity
- Total Spent
- Payment Method
- Location
- Transaction Date
- Discount Applied

## Data Cleaning

The dataset was analyzed and cleaned by:

- Checking missing values
- Checking duplicate records
- Converting data types
- Checking numerical outliers
- Validating total spending
- Investigating unknown product records
- Analyzing missing discount information

## Key Insights

- Total Sales: 1,637,367
- Total Transactions: 12,575
- Total Customers: 25
- Total Quantity Sold: 69,900
- Top Category: Butchers
- Top Category Sales: 218,153
- Top Known Item: Item_25_FUR
- Top Location: Online
- Online Sales: 831,922
- Most Used Payment Method: Cash
- Best Year: 2024
- Best Year Sales: 554,296
- Lowest Category: Milk Products
- Lowest Category Sales: 189,892

## Data Quality Issues

The `Discount Applied` column contains 4,199 missing values. These values were not automatically treated as False because there was not enough information to determine their actual status.

The `Item` column also contains 1,213 records labeled as `Unknown`.

## Tools

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Streamlit
