# 📊 Sales Performance Dashboard – Power BI

## Overview

This project is an interactive **Sales Performance Dashboard** developed using Microsoft Power BI.

The dashboard analyses 500 fictional sales transactions across multiple South African regions, products, categories, and salespeople. The objective was to transform raw sales data into an interactive business intelligence dashboard that makes it easier to monitor revenue, profitability, sales trends, and product performance.

## Dashboard Preview

![Sales Performance Dashboard](dashboard-preview.png)

## Key Performance Indicators

The dashboard tracks four main KPIs:

- Total Revenue
- Total Profit
- Profit Margin
- Total Units Sold

## Dashboard Features

### Monthly Revenue Trend
Displays monthly revenue performance throughout 2025, allowing changes and patterns in sales performance to be identified over time.

### Revenue by Region
Compares revenue generated across:

- Gauteng
- Free State
- Western Cape
- KwaZulu-Natal
- Eastern Cape

### Top 5 Products by Revenue
Identifies the five products generating the highest total revenue.

### Interactive Filters
Users can dynamically filter the dashboard by:

- Region
- Product Category

The filters update the KPIs and visualisations automatically, allowing users to explore different segments of the sales data.

## Data Preparation

The dataset was reviewed and prepared using **Power Query** before analysis.

This included:

- Checking column data types
- Converting the Order Date field to the correct date format
- Validating numerical fields
- Preparing the dataset for reporting and analysis

## DAX Measures

Custom DAX measures were created to calculate key business metrics.

### Total Revenue

```DAX
Total Revenue = SUM(Sales_Data[Revenue])
```

### Total Profit

```DAX
Total Profit = SUM(Sales_Data[Profit])
```

### Profit Margin

```DAX
Profit Margin =
DIVIDE(
    [Total Profit],
    [Total Revenue],
    0
)
```

### Total Units Sold

```DAX
Total Units Sold = SUM(Sales_Data[Units Sold])
```

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Cleaning
- Data Visualisation
- Business Intelligence
- Data Analysis

## Skills Demonstrated

This project demonstrates practical experience with:

- Importing Excel data into Power BI
- Data preparation using Power Query
- Creating DAX measures
- KPI development
- Time-series analysis
- Product performance analysis
- Regional sales analysis
- Top N filtering
- Interactive slicers
- Cross-filtering
- Dashboard design
- Business data visualisation

## Dataset

The project uses a synthetic dataset containing **500 fictional sales transactions from 2025**.

The dataset includes:

- Order ID
- Order Date
- Region
- Salesperson
- Category
- Product
- Units Sold
- Unit Price
- Unit Cost
- Revenue
- Total Cost
- Profit

The data was created specifically for portfolio and educational purposes and does not represent a real company.

## Author

**Goodwill Louw**

BSc Information Technology (Data Science) – Eduvos

[LinkedIn](https://www.linkedin.com/in/goodwill-louw-data-science/) | [GitHub](https://github.com/louwgoodwill-sys)
