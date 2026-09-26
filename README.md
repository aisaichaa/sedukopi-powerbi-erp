# SEDukopi Business Intelligence Dashboard

## Project Purpose

This project analyzes SEDukopi's sales and operational performance using Microsoft Power BI with an ERP-oriented data analysis approach. The dashboard integrates sales, product, outlet, staff, cost, and transaction data to support business performance analysis.

## Objectives

- Analyze revenue and sales performance.
- Identify revenue trends by time, outlet, and category.
- Analyze menu and quantity performance.
- Analyze payment method and order type.
- Analyze staff and outlet distribution.
- Analyze menu cost, selling price, and availability.
- Monitor gross profit and profit margin.

## Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX
- ERP-oriented Data Analysis

## Data Model

The dashboard uses related data for:

- Outlets
- Menu Items
- Staff
- Orders
- Order Details
- Date

The data model connects sales transactions with product, outlet, staff, cost, and date information for integrated analysis.

## Dashboard

### Executive Overview

Provides an overview of revenue, orders, profit margin, gross profit, average order value, revenue trends, outlets, and categories.

### Sales Analysis

Analyzes total revenue, quantity sold, average order value, gross profit, top 10 menus, product categories, payment methods, and order types.

### Operational & ERP Analysis

Analyzes staff, salary, menu costs, gross profit, outlet performance, staff distribution, selling price versus cost, and menu availability.

## Key DAX Measures

```DAX
Total Revenue = SUM(orders[total_amount])

Total Orders = DISTINCTCOUNT(orders[order_id])

Total Quantity = SUM(order_details[quantity])

Gross Profit = [Total Revenue] - [Total Cost]

Average Order Value = DIVIDE([Total Revenue], [Total Orders])

Profit Margin = DIVIDE([Gross Profit], [Total Revenue])

# Dashboard Preview

## Skills Demonstrated

Power BI
Power Query
DAX
Data Modeling
Data Visualization
KPI Development
Business Intelligence
Sales Analysis
Operational Analysis
ERP-oriented Data Analysis

## Author

Aisha Patricia Sekar Ayu
