# Customer Behavior Analysis

## Overview

Customer Behavior Analysis is an end-to-end Data Analytics project focused on understanding customer purchasing patterns and shopping behavior. The project follows a complete analytics workflow, starting from data collection and preprocessing in Python, performing Exploratory Data Analysis (EDA), executing business-driven SQL queries in PostgreSQL, and finally creating an interactive Power BI dashboard for visualization and decision-making.

The goal of this project is to transform raw customer transaction data into actionable business insights that can help organizations improve customer engagement, sales strategies, and overall business performance.

---

## Dataset

The dataset contains customer shopping and transaction-related information, including:

* Customer ID
* Age
* Gender
* Product Category
* Purchase Amount
* Payment Method
* Discount Applied
* Review Rating
* Subscription Status
* Frequency of Purchases
* Shipping Type
* Location

The dataset was analyzed to identify customer trends, spending behavior, and purchasing patterns.

---

## Tools & Technologies

### Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

### Database

* PostgreSQL

### Visualization

* Power BI

### Development Environment

* Jupyter Notebook
* VS Code

---

## Project Workflow

### 1. Data Loading

* Imported dataset using Python.
* Inspected data structure and column information.
* Checked data types and dataset dimensions.

### 2. Exploratory Data Analysis (EDA)

* Analyzed customer demographics.
* Identified purchasing trends.
* Examined product category performance.
* Visualized customer spending behavior.
* Generated statistical summaries and charts.

### 3. Data Cleaning

* Handled missing values.
* Removed duplicates.
* Corrected inconsistent data formats.
* Prepared data for SQL analysis and dashboard reporting.

### 4. SQL Analysis (PostgreSQL)

Business questions were answered using SQL queries, including:

* Total revenue by gender
* Top-performing product categories
* Average customer spending
* Impact of discounts on purchases
* Customer subscription behavior
* Payment method analysis
* Regional sales performance
* Customer purchase frequency insights

### 5. Power BI Dashboard

Created an interactive dashboard to visualize:

* Total Revenue
* Total Customers
* Purchase Distribution
* Revenue by Gender
* Revenue by Category
* Discount Impact Analysis
* Customer Segmentation
* Location-wise Performance
* Customer Purchase Trends

---

## Dashboard Features

* Interactive Filters and Slicers
* Dynamic KPI Cards
* Revenue Analysis
* Customer Insights
* Product Performance Tracking
* Regional Analysis
* Business Trend Visualization

---

## Key Insights

* Identified high-revenue customer segments.
* Discovered top-performing product categories.
* Analyzed the influence of discounts on customer spending.
* Evaluated customer purchasing frequency patterns.
* Identified preferred payment methods.
* Revealed demographic trends affecting sales performance.

---

## Project Structure

```text
Customer-Behavior-Analysis/
│
├── Dataset/
│   └── customer_data.csv
│
├── Python/
│   └── EDA_and_Data_Cleaning.ipynb
│
├── SQL/
│   └── analysis_queries.sql
│
├── PowerBI/
│   └── Customer_Behavior_Dashboard.pbix
│
├── Images/
│   └── dashboard_screenshot.png
│
└── README.md
```

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/usmanali35549/Custoer-Behavior-analysis.git
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn psycopg2
```

### Run Python Analysis

```bash
jupyter notebook
```

Open the notebook and execute all cells.

### Run SQL Queries

1. Import the dataset into PostgreSQL.
2. Execute queries from the `SQL` folder.
3. Review the generated insights.

### Open Power BI Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Refresh data connections if required.
3. Explore the dashboard using interactive filters.

---

## Results

This project demonstrates a complete Data Analytics workflow by integrating Python, PostgreSQL, and Power BI. The analysis provides valuable customer insights that support data-driven business decisions and showcase practical skills in data cleaning, SQL querying, visualization, and business intelligence.

---

## Author

**Usman Ali**

MCA Student | Data Analyst Enthusiast | Front-End Developer

GitHub: https://github.com/usmanali35549
