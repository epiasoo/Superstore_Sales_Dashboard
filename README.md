# Superstore Sales Performance Dashboard

An interactive Power BI dashboard analysing sales, profit, and order trends for a retail superstore dataset — built to surface revenue drivers across product category, region, and customer segment.

![Dashboard Preview](screenshots/dashboard-overview.png)

## Business Problem

Retail businesses need visibility into revenue performance, customer behaviour, and profitability drivers. This dashboard was developed to help stakeholders identify high-performing categories, regions, products, and customer segments.

## Overview

This report answers three core business questions:
- **Where is revenue coming from?** — by product category, region, and customer segment
- **What's driving profitability?** — profit margin, top and bottom performing products
- **How is performance trending?** — monthly revenue trend over time

## Key Metrics
| KPI | Value |
|---|---:|
| Total Sales | $2.30M |
| Total Profit | $286.40K |
| Total Orders | 5,009 |
| Profit Margin | 12.5% |

## Key Features
- KPI summary cards: Total Sales, Total Profit, Total Orders, Profit Margin
- Monthly revenue trend line chart with year/quarter/month drill
- Revenue breakdown by Product Category and Region
- Top 10 Products by Revenue
- Revenue share by Customer Segment (donut chart)
- Interactive slicers: Year, Category, Region
- Custom navy/teal color styling with a branded header banner and card-style visuals with drop shadows

## Data
- **Source:** Superstore Sales dataset (Order ID, Order Date, Sales, Profit, Category, Region, Product Name, Segment)
- **Rows:** *9,994 transactions*
- **Date range:** *2019 - 2022*

## Key Insights

- Technology generated the highest revenue among product categories.
- The West region was the strongest revenue contributor.
- Consumer customers represented the largest customer segment.
- Canon products appeared among the top revenue-generating products.
- Overall profit margin was 12.5%.

## Tools & Skills

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Data Modelling
- Data Visualisation
- Business Intelligence Reporting

## Key DAX Measures
```dax
Total Sales = SUM(Sales_Data[Sales])
Total Profit = SUM(Sales_Data[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
```

## Screenshots
See `/screenshots` for full-page exports of the dashboard.

## How to Use
1. Download `Superstore_Sales_Model.pbix`
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows) or import into [Power BI Service](https://app.powerbi.com) (works on Mac/browser)
3. Data will refresh automatically if the source file path is available, or you can point it to your own copy of the dataset

## Author

**Ei Phyu Sin Oo**

MSc Applied Data Science graduate specialising in data analytics, business intelligence, and data visualisation.
