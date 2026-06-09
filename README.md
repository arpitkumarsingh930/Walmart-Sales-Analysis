

# Walmart Sales Analysis using SQL & Power BI

## Project Overview

This project analyzes Walmart sales transaction data using SQL to uncover insights into customer behavior, product performance, branch profitability, and sales trends.

The objective is to transform raw transactional data into actionable business insights through data cleaning, feature engineering, exploratory data analysis (EDA), and interactive dashboarding.

### Key Goals

* Identify top-performing product lines
* Analyze branch-wise sales performance
* Understand customer purchasing behavior
* Evaluate revenue and profitability trends
* Generate business insights for decision-making

---

## Project Architecture

```text
Walmart-Sales-Analysis/
│
├── Dataset/
│   └── WalmartSalesData.csv
│
├── SQL/
│   └── SQL_queries.sql
│
├── Dashboard/
│   └── Walmart_PowerBI.pbix
│
├── Images/
│   └── Dashboard_Screenshot.png
│
└── README.md
```

---

## Tools & Technologies

| Tool         | Purpose                      |
| ------------ | ---------------------------- |
| MySQL        | Data Cleaning & Analysis     |
| SQL          | Querying & Business Insights |
| Power BI     | Data Visualization           |
| Git & GitHub | Version Control              |

---

## Dataset Information

The dataset contains **1,000 sales transactions** from Walmart branches located in:

* Yangon
* Mandalay
* Naypyitaw

### Dataset Summary

| Metric        | Value |
| ------------- | ----- |
| Records       | 1000  |
| Columns       | 17    |
| Branches      | 3     |
| Cities        | 3     |
| Product Lines | 6     |

---

## Data Preparation

### Data Cleaning

* Checked for missing values
* Validated data types
* Removed inconsistencies
* Ensured data integrity

### Feature Engineering

Three new analytical columns were created:

| Feature     | Description                 |
| ----------- | --------------------------- |
| time_of_day | Morning, Afternoon, Evening |
| day_name    | Day of Week                 |
| month_name  | Month Name                  |

These features enabled time-based sales analysis.

---

## Business Questions Solved

### Product Analysis

* Which product line generates the highest revenue?
* Which product line sells the most units?
* Which product line receives the highest customer ratings?
* Which product lines perform above average?

### Sales Analysis

* Which branch generates the most revenue?
* What are the monthly revenue trends?
* Which customer segment contributes the most revenue?
* What is the busiest time of day?

### Customer Analysis

* Which customer type is most common?
* What is the gender distribution?
* Which customer segment spends the most?
* When are ratings highest?

---

## Key Insights

### Revenue Performance

* Electronic Accessories and Food & Beverages were among the strongest revenue-generating categories.
* Branch performance varied significantly across cities.

### Customer Behavior

* Member customers generated a substantial portion of revenue.
* Female and male purchasing behavior showed noticeable differences across product categories.

### Sales Trends

* Evening hours recorded the highest transaction volume.
* Certain weekdays consistently outperformed others in revenue generation.

---

## Power BI Dashboard

The SQL analysis was transformed into an interactive Power BI dashboard featuring:

### KPI Cards

* Total Revenue
* Total Transactions
* Total Quantity Sold
* Average Rating
* Gross Income

### Visualizations

* Revenue by Product Line
* Revenue by Branch
* Monthly Revenue Trend
* Sales by Time of Day
* Customer Type Distribution
* Average Rating by Product Line

### Interactive Filters

* Branch
* City
* Customer Type
* Gender
* Product Line

---

## SQL Concepts Demonstrated

```sql
SELECT
GROUP BY
ORDER BY
HAVING
CASE WHEN
SUBQUERIES
AGGREGATE FUNCTIONS
DATE FUNCTIONS
ALTER TABLE
UPDATE
```

---

## Results

| KPI            | Value   |
| -------------- | ------- |
| Total Revenue  | 322,967 |
| Transactions   | 1,000   |
| Quantity Sold  | 5,510   |
| Average Rating | 6.97    |
| Gross Income   | 15,379  |

---

## Learning Outcomes

Through this project, I gained practical experience in:

* SQL data analysis
* Data cleaning and transformation
* Feature engineering
* Business intelligence reporting
* Power BI dashboard development
* Converting raw data into actionable insights

---

## Author

**Arpit Kumar Singh**

