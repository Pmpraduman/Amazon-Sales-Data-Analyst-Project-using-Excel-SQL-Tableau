# 📦 Amazon Sales Dashboard

### 🔍 Optimizing Revenue Through Operational Efficiency

**Tools Used**: Microsoft Excel (Data Cleaning & Preprocessing), Tableau (Data Visualization)

## 🧭 Project Summary

This project analyzes Amazon’s historical sales data to uncover key business insights using Excel for data cleaning and Tableau for visualization. The primary objective was to evaluate how operational performance—especially shipping days—impacts revenue, and to make data-driven recommendations for improving business outcomes.

## 📌 Core Business Insight

### 🚚 Shipping Days Directly Impact Revenue

> A consistent and measurable **inverse relationship** was discovered between shipping days and revenue.

- 📉 When **shipping days increased**, **revenue dropped** significantly.
- 📈 When **shipping days decreased**, **revenue rose** across categories and regions.

This highlights the importance of operational efficiency in customer satisfaction, conversion rates, and repeat purchases.

## 📊 Metrics Explored

- Total Revenue
- Net Profit & Profit Margins
- Units Sold
- Shipping Days (Derived in Excel)
- Orders per Year
- Orders and Shipments by Priority
- Item-wise Sales & Operational Trends

## 🧼 Data Cleaning & Processing (Excel)

- Removed blanks, nulls, and duplicates
- Standardized date formats
- Derived custom columns:
  - `Shipping Days = Shipping Date – Order Date`
  - `Profit Margin = Profit / Revenue`
- Filtered and sorted data by Region, Category, Year, and Priority
- Exported cleaned dataset for Tableau analysis

## 📈 Tableau Dashboard Overview

The Tableau dashboard provides an interactive view of the business performance using maps, trend lines, KPI cards, and category filters.

### 🔑 Key Dashboard Components

- **Profit & Revenue by Region**  
  Visualize which regions contribute the most to the bottom line

- **Country-Level Profitability**  
  Compare profitability across countries to identify growth or risk zones

- **Shipping Days vs. Revenue Trends**  
  Analyze how delivery performance impacts customer purchasing behavior

- **Orders Over Time**  
  Identify trends and seasonality in yearly sales volume

- **Orders & Shipments by Priority**  
  Track operational responsiveness to customer urgency levels

- **Item & Category Analysis**  
  Evaluate revenue, profit margins, and shipping behavior at a SKU level

### 🧩 Interactivity Features

- Filters for Region, Country, Year, Category, and Priority
- Dynamic tooltips on hover
- Slicers for custom analysis and drilldowns

## 🎯 Strategic Recommendations

1. **Accelerate Shipping Operations**

   - Expand fulfillment centers in high-demand regions
   - Collaborate with faster last-mile delivery partners

2. **Promote Fast Shipping**

   - Display “Fast Delivery” tags on top-performing SKUs
   - Use shipping speed in marketing campaigns

3. **Monitor SLA Impact via Dashboards**

   - Build Tableau alerts to track delays affecting revenue
   - Benchmark performance across categories and time

4. **Focus on High-Impact Product Categories**
   - Prioritize Electronics and Home categories for logistics and marketing investment

---

## 📌 Business Impact

By optimizing shipping performance, the business can:

- Increase revenue
- Improve customer satisfaction
- Strengthen market competitiveness through faster delivery

> **Note:** This project demonstrates the value of aligning operational metrics with business performance through data visualization and cross-functional strategy.
