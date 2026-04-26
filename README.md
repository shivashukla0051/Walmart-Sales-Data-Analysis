📊 Walmart Sales Data Analysis (SQL + Python)
🔍 Project Overview

This project focuses on performing end-to-end data analysis on Walmart sales data to derive actionable business insights. It combines Python (data processing) and SQL (analytical querying) to simulate real-world data analyst workflows.

The objective is to clean, transform, analyze, and extract meaningful patterns related to sales performance, customer behavior, and profitability.

⚙️ Tech Stack
Programming: Python (Pandas, NumPy)
Databases: MySQL, PostgreSQL
Libraries: SQLAlchemy, psycopg2, mysql-connector
Tools: VS Code, Jupyter Notebook
Data Source: Kaggle (Walmart Sales Dataset)
🚀 Project Workflow
1. Environment Setup
Structured project workspace using VS Code
Organized folders for data, SQL, and notebooks
2. Data Acquisition
Dataset downloaded using Kaggle API
Stored locally inside /data directory
3. Data Loading & Exploration
Loaded dataset using Pandas
Performed initial checks using:
.head()
.info()
.describe()
4. Data Cleaning
Removed duplicate records
Handled missing/null values
Standardized column data types
Cleaned and formatted currency-related fields
5. Feature Engineering
Created new metrics like:
Total Sales = Unit Price × Quantity
Enhanced dataset for deeper analysis
6. Database Integration
Connected Python with MySQL & PostgreSQL
Created tables using SQLAlchemy
Loaded cleaned dataset into databases
7. SQL-Based Analysis

Performed advanced SQL queries to solve business problems:

📈 Sales trends across branches and time
🏆 Top-performing product categories
💳 Payment method analysis
🕒 Peak sales hours identification
📊 Profitability analysis by location
8. Insights Generation

Key findings from the analysis include:

High-performing branches contribute significantly to overall revenue
Certain product categories consistently outperform others
Customer purchase patterns vary by time and payment method
Peak hours can be leveraged for targeted promotions
