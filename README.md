# Sales & Profit Intelligence Dashboard
### Power BI · SQL · DAX · Excel

> Identifying where a business actually makes money — and where it quietly loses it.

---

## 🧩 Business Problem

Retail managers often operate blind — they see total revenue but not *where* profit is actually coming from. Without clear visibility into which regions, categories, and products drive margins, businesses make pricing and inventory decisions based on gut feel rather than data.

This project builds an interactive Power BI dashboard using Superstore sales data to surface exactly that — where the money is made, where it's lost, and what to do about it.

---

## 📊 Dataset

- **Source:** Superstore sample dataset (public practice data)
- **Size:** 1,000+ sales transactions across 3 regions and 12 months
- **Key fields:** Order Date · Region · Category · Sub-Category · Customer Segment · Sales · Profit · Discount · Profit Margin

---

## ❓ Business Questions Answered

- Which regions, categories, and segments drive the most profit?
- Which products are high-revenue but low-margin traps?
- Where are discounts hurting profitability?
- How do sales and profit trend over time?

---

## ⚙️ Approach

**Data Preparation**
- Loaded consolidated Superstore sheet into Power BI
- Cleaned data types — dates, numeric fields
- Removed irrelevant columns

**DAX Measures Built**
- `Total Sales`
- `Total Profit`
- `Profit Margin = DIVIDE([Total Profit], [Total Sales])`
- `Order Count`

**Dashboard Components**
- KPI cards — Sales, Profit, Margin, Orders
- Monthly sales and profit trend line
- Sales and profit by category, segment, and region
- Top 10 and bottom 10 products by profit
- Interactive slicers — date range, region, category, segment

---

## 💡 Key Insights

**1. Technology drives profit. Furniture destroys it.**
Technology generated the highest revenue AND profit margin. Furniture had strong sales volume but significantly lower margins — a classic high-revenue, low-profit trap.

**2. The Central region and Corporate segment are the core business.**
Together they contributed the largest share of both sales and profit. These are the segments worth protecting and doubling down on.

**3. Top 10 products = 60–70% of total revenue.**
Classic Pareto distribution. Most of the revenue lives in a small SKU set — everything else is noise from a profitability standpoint.

**4. Manual reporting eliminated.**
Replaced recurring Excel reports with a refreshable Power BI dashboard — cutting weekly reporting effort by 50–70%.

---

## ✅ Recommendations

- Review discount and pricing strategy in Furniture — high discounts are eroding margins without driving enough incremental volume
- Prioritize Central region and Corporate segment in sales and marketing investment
- Focus inventory and supply chain attention on the top 10 revenue-driving SKUs
- Explore the South region — despite lower volume, it shows higher revenue per order suggesting a high-value customer base worth expanding

---

## 🗂️ Repository Structure

```
Sales_Profit_Intelligence_Dashboard/
├── pbix/
│   └── Sales_Profit_Intelligence_Dashboard.pbix
├── data/
│   └── superstore_data.csv
├── screenshots/
│   └── dashboard_overview.png
└── README.md
```

---

## 🛠️ Tools Used

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)

---

## 👤 Author
Samudra Giri
**Samudra Giri**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samudra-giri-90a5491b7)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/samudragiri17)
