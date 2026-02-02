# Sales_Profit_Intelligence_Dashboard
“Power BI dashboard analyzing Superstore sales, profit and margins by region, category, and segment.”

## Project Overview
Retail managers often struggle to see clearly where they make and lose money.
This project builds a Power BI dashboard using Superstore sales data to analyze
sales, profit and margins across regions, categories, and customer segments.

## Data
- Source: Superstore sample dataset (public practice data)
- Rows: ~[X] orders
- Key fields: Order Date, Region, State, City, Category, Sub-Category,
  Customer Segment, Sales, Quantity, Discount, Profit, Product Base Margin.

## Business Questions
- Which regions, categories, and segments drive the most sales and profit?
- Which products are most and least profitable?
- How do sales and profit trend over time?
- Where do we have high sales but low profit margins?

## Approach
- Loaded a single consolidated Superstore sheet into Power BI.
- Cleaned data types (dates, numeric fields) and removed unnecessary columns.
- Created DAX measures:
  - Total Sales
  - Total Profit
  - Profit Margin
  - Order Count
- Built an interactive dashboard with:
  - KPI cards (Sales, Profit, Margin, Orders)
  - Monthly sales & profit trend
  - Sales & profit by category, segment, and region
  - Top 10 and bottom 10 products by profit
  - Slicers for date, region, category, and segment

## Key Insights
- Technology category generated the highest revenue and profit, while Furniture
  had strong sales but significantly lower profit margins.
- The Central region and Corporate segment together contributed the largest share
  of both sales and profit.
- The South region, despite the lowest sales volume, delivered higher revenue
  than the East and West, suggesting a smaller but higher-value customer base.

## Recommendations
- Review pricing and discount strategy in the Furniture category to improve margins.
- Double down on the Central region & Corporate segment with targeted campaigns.
- Explore growth opportunities in the South region by expanding reach to similar
  high-value customers.

## Files in this Repository
- `pbix/Sales_Profit_Intelligence_Dashboard.pbix` – main Power BI report.
- `data/` – sample dataset or link to data source.
- `reports/` – dashboard screenshots.

## Tools Used
- Power BI Desktop
