# E-Commerce Sales Analysis & Dashboard | Python

An end-to-end **E-commerce Sales Analysis project using Python**, focused on analyzing sales performance, profitability, returns, products, regions, sales representatives, and sales patterns over time.

The project combines **data preprocessing, KPI analysis, exploratory data analysis, visualization, and an interactive Dash dashboard** to transform raw transaction data into business insights.

---

## 📊 Dashboard

The project includes an interactive dashboard built with **Dash and Plotly**, allowing users to filter the analysis by:

- Region
- Sales Representative
- Product

The dashboard dynamically updates the visualizations based on the selected filters.

![E-Commerce Sales Dashboard](Dashboard.png)

---

## 📌 Project Overview

The dataset contains **2,000 e-commerce transactions** with information about:

- Orders
- Products
- Sales Representatives
- Regions
- Quantity Sold
- Unit Price
- Total Sales
- Profit
- Returns
- Order Date
- Time of Sale

The analysis focuses on understanding the company's overall sales performance and identifying patterns that can support better **sales, product, regional, and operational decisions**.

---

## 🎯 Business Objectives

The project addresses several important business questions:

### Sales Performance
- What is the total sales revenue?
- How does sales performance change over time?
- Which products generate the highest sales?
- Which regions contribute the most revenue?
- Which sales representatives generate the highest sales?

### Profitability
- What is the total profit?
- How does profit change over time?
- What is the profit margin?
- How does profitability vary across the business?

### Returns
- What percentage of orders are returned?
- Which regions have higher return rates?
- How do returns relate to business performance?

### Time Analysis
- Which days of the week generate the most sales?
- Which hours generate the highest sales?
- Which time periods of the day have the strongest performance?

---

## 📊 Key Performance Indicators

The analysis calculates the following core KPIs:

| KPI | Result |
|---|---:|
| **Total Sales** | 3,805,363 |
| **Total Profit** | 808,656 |
| **Total Quantity Sold** | 10,822 |
| **Average Order Size** | 352.42 |
| **Return Rate** | 19.45% |

These metrics provide a high-level view of the company's sales volume, profitability, customer transaction value, and returns.

---

## 📈 Key Analysis

### 1. Sales Trend Analysis

Sales were analyzed by month and year to identify changes in business performance.

Annual sales:

| Year | Total Sales |
|---|---:|
| 2022 | 391,707 |
| 2023 | 1,894,036 |
| 2024 | 1,519,620 |

The analysis also calculates:

- Month-over-Month (MoM) growth
- Year-over-Year (YoY) growth
- Monthly sales trends
- Annual sales trends

---

### 2. Product Performance

Products were ranked based on total sales.

The highest-performing products in the analysis were:

| Product ID | Total Sales |
|---|---:|
| **202** | 811,738 |
| **204** | 765,043 |

This analysis helps identify products that contribute significantly to overall revenue.

---

### 3. Regional Performance

Sales were grouped by region to identify the strongest geographic markets.

Top-performing regions:

| Region ID | Total Sales |
|---|---:|
| **105** | 790,387 |
| **101** | 776,335 |

Regional analysis can support sales planning, resource allocation, and performance monitoring.

---

### 4. Sales Representative Performance

Sales were also analyzed by `Sales_Rep_ID` to compare representative performance.

Top sales representatives:

| Sales Rep ID | Total Sales |
|---|---:|
| **303** | 847,197 |
| **304** | 777,659 |

This provides a way to compare sales contribution across representatives.

---

### 5. Sales by Day of Week

Sales were analyzed across the seven days of the week.

The highest sales were recorded on:

1. **Thursday** — 593,086
2. **Wednesday** — 582,667
3. **Saturday** — 572,165

This analysis helps identify weekly sales patterns.

---

### 6. Sales by Time of Day

The `Time` field was transformed into four periods:

- Night
- Morning
- Afternoon
- Evening

Sales performance by period:

| Time of Day | Total Sales |
|---|---:|
| **Afternoon** | 972,846 |
| **Morning** | 964,234 |
| **Night** | 940,774 |
| **Evening** | 927,509 |

The project also analyzes sales at the individual **hour level**.

---

### 7. Return Rate Analysis

Returns are tracked using the `Return_Flag` field.

The overall return rate is:

**19.45%**

Return rates are also analyzed by region to identify geographic differences in return behavior.

---

### 8. Profitability Analysis

Profitability is analyzed using:

- Total Profit
- Profit Margin
- Monthly Profit Margin

This helps evaluate whether changes in sales volume are accompanied by changes in profitability.

---

## 🔄 Data Analysis Workflow

The project follows a complete Python data analysis workflow:

```text
Raw CSV Data
     ↓
Data Loading
     ↓
Data Inspection
     ↓
Data Cleaning & Preprocessing
     ↓
Feature Engineering
     ↓
KPI Calculation
     ↓
Exploratory Data Analysis
     ↓
Data Visualization
     ↓
Interactive Dash Dashboard
     ↓
Business Insights
