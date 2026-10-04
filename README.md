# Power BI Sales & Inventory Analytics Dashboard

## Project Overview

This project presents an interactive Power BI dashboard developed to analyze sales performance, profitability, orders, product performance, and inventory for a fictional company named ABC Company.

The dashboard was created as a portfolio project to demonstrate practical skills in business intelligence, data analysis, data visualization, and Power BI.

> **Disclaimer:** ABC Company is a fictional company created for portfolio and learning purposes. The dataset used in this project is simulated and does not represent real company data.

---

## Business Objective

The main objective of this dashboard is to provide management with a clear view of business performance and help identify:

* Overall sales performance
* Profitability
* Sales trends
* Regional performance
* Outlet performance
* Product performance
* Inventory levels
* Low-stock products
* Products with no sales

---

## Dashboard Pages

### 1. Executive Dashboard

The executive dashboard provides a high-level overview of business performance.

Key KPIs:

* Total Sales
* Total Profit
* Total Orders
* Total Units Sold
* Average Order Value

Visualizations include:

* Monthly Sales Trend
* Sales by Region
* Sales by Product Category
* Top 10 Products
* Sales vs Target

### 2. Sales Analysis

This page provides detailed analysis of sales performance.

It includes:

* Sales by Month
* Sales by Day
* Sales by Region
* Sales by Outlet
* Sales by Salesperson
* Average Order Value
* Number of Orders

### 3. Inventory Analysis

The inventory dashboard focuses on stock and product performance.

Key metrics include:

* Current Stock
* Low-Stock Products
* Stock Value
* Products with No Sales
* Inventory by Outlet

---

## Key Power BI Features Used

* Power BI Desktop
* Data Modeling
* DAX Measures
* KPI Cards
* Interactive Charts
* Tables and Matrices
* Filters and Slicers
* Drill-down Analysis
* Conditional Formatting
* Top N Analysis

---

## DAX Measures

Examples of DAX measures created for the dashboard include:

```DAX
Total Sales =
SUM(FactSales[NetSales])
```

```DAX
Total Profit =
SUM(FactSales[Profit])
```

```DAX
Profit Margin =
DIVIDE([Total Profit], [Total Sales], 0)
```

Other measures were created for:

* Total Orders
* Quantity Sold
* Average Order Value
* Current Stock
* Stock Value
* Inventory analysis

---

## Skills Demonstrated

### Power BI

* Dashboard Development
* Data Visualization
* Data Modeling
* DAX
* KPI Development
* Interactive Reporting

### Data Analysis

* Sales Analysis
* Profitability Analysis
* Product Analysis
* Inventory Analysis
* Trend Analysis
* Regional Analysis

### Business Intelligence

* Management Reporting
* KPI Monitoring
* Business Performance Analysis
* Decision Support

---

## Project Structure

```text
ABC-Company-PowerBI-Dashboard
│
├── ABC_Company_Sales_Inventory_Dashboard.pbix
├── README.md
├── screenshots
│   ├── executive-dashboard.png
│   ├── sales-analysis.png
│   └── inventory-analysis.png
└── data
    └── sample_data.xlsx
```

---

## Dashboard Preview

### Executive Dashboard

![Executive Dashboard](screenshots/executive-dashboard.png)

### Sales Analysis

![Sales Analysis](screenshots/sales-analysis.png)

### Inventory Analysis

![Inventory Analysis](screenshots/inventory-analysis.png)

---

## Project Purpose

This project was developed as a practical Power BI portfolio project to demonstrate the ability to transform business data into interactive dashboards and actionable business insights.

**Tools:** Power BI Desktop, DAX, Excel

**Project Type:** Portfolio / Simulated Business Case
