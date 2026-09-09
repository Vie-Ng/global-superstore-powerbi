# Global Superstore Power BI Analysis

Power BI analysis of global sales, customer performance, profitability, and operational efficiency using the Global Superstore dataset.

## Project Overview

This project analyzes global retail performance across sales, customers, products, markets, profitability, and operational efficiency.

The objective is to transform transactional sales data into an interactive business intelligence dashboard that supports management-level decision making.

The analysis focuses on three key areas:

- Executive Sales & Performance
- Sales & Customer Performance
- Profitability & Operations

---

## Dashboard

### 1. Executive Sales & Performance

Provides a high-level overview of revenue, profitability, customer segments, regional performance, and product contribution.

![Executive Overview](Executive%20overview.png)

### 2. Sales & Customer Performance

Analyzes monthly sales trends, market performance, customer contribution, customer segments, and the relationship between sales and profit across product categories.

![Sales Customer Performance](Sales%20customer%20perfomance.png)

### 3. Profitability & Operations

Examines profit contribution by category and sub-category, discount levels, shipping costs across markets, and lower-performing products.

![Profitability & Operations](Profitability%20operations.png)

---

## Data Model

The project uses a star-schema data model designed to separate transactional data from descriptive dimensions.

### Fact Table
- FactSales

### Dimension Tables
- DimDate
- DimProduct
- DimCustomer
- DimGeography

This structure supports consistent filtering, time-based analysis, customer analysis, product analysis, and geographical performance analysis.

![Data Model](Data%20model.png)

---

# Key Insights

## Executive Overview

- Total sales reached approximately **$12.64M**, generating approximately **$1.47M in profit** and an overall **11.61% profit margin**.
- **Technology** is the leading product category by sales, indicating strong revenue contribution from technology-related products.
- **Consumer customers account for approximately 51.48% of total sales**, making the Consumer segment the largest customer segment.
- The **Central region generates the highest profit contribution** among the regions shown in the dashboard.
- Revenue and profitability fluctuate over time, indicating differences in business performance across months and years.

## Sales & Customer Performance

- **APAC is the largest market by sales**, followed by the EU and US markets.
- The Consumer segment contributes approximately **51.48% of total sales**, while Corporate and Home Office contribute the remaining share.
- The largest customers contribute substantial individual sales volumes, highlighting the importance of key customer accounts.
- **Technology generates the highest sales among the three product categories**, followed by Furniture and Office Supplies.
- Sales and profit do not increase proportionally across categories, indicating that high revenue does not necessarily translate into equally high profitability.

## Profitability & Operations

- **Technology generates the highest total profit**, making it the strongest category from a profitability perspective.
- Within sub-categories, **Copiers generate the highest profit contribution**, followed by Phones and Bookcases.
- **APAC has the highest shipping cost**, among the markets, highlighting the need to monitor logistics efficiency alongside revenue performance.
- Total shipping costs are approximately **$1.35M**, representing a significant operational cost relative to total sales.
- Average shipping time is approximately **3.97 days**.
- Higher discount levels do not show a clear positive relationship with profit in the observed data, suggesting that aggressive discounting does not necessarily improve profitability.

---

# Business Insights

## 1. Technology is the strongest commercial and profitability driver

Technology is the leading category in both sales and profit contribution.

This indicates that Technology is not only generating high revenue but is also an important source of overall profitability. The strong performance of sub-categories such as Copiers and Phones further supports the importance of this product portfolio.

**Business implication:** Management should consider protecting and expanding high-performing Technology products while maintaining sufficient inventory availability and customer support.

---

## 2. Consumer customers are the largest revenue segment

Consumer customers contribute approximately **51.48% of total sales**, making them the largest customer segment.

This creates an opportunity to strengthen customer retention, personalized offers, and cross-selling strategies within the Consumer segment.

**Business implication:** Customer strategies should prioritize retention and lifetime value rather than relying only on acquisition.

---

## 3. APAC is the largest market by sales but also carries a significant cost burden

APAC generates the highest sales among the markets shown in the dashboard and also has the highest shipping cost.

This indicates that APAC is commercially important but may require closer monitoring of logistics and fulfilment costs.

**Business implication:** Revenue growth in APAC should be evaluated together with logistics efficiency and contribution margin rather than sales alone.

---

## 4. Revenue growth should not be evaluated without profitability

The category analysis shows that sales and profit are not proportional.

A category can generate substantial revenue without delivering the same level of profit contribution. This highlights the importance of monitoring profitability alongside revenue when evaluating product performance.

**Business implication:** Management should use profit margin and contribution profit as complementary KPIs to sales when making product and category decisions.

---

## 5. Discounting requires stronger profitability controls

The Discount vs Profit analysis does not indicate that higher discount levels consistently produce higher profit.

This suggests that discounting should be applied selectively rather than broadly across products.

**Business implication:** Discount policies should consider product profitability, customer value, and market conditions. High discounts should be justified by measurable commercial benefits such as increased volume, retention, or customer acquisition.

---

## 6. Shipping costs represent an important operational consideration

Total shipping costs are approximately **$1.35M**, while average shipping time is approximately **3.97 days**.

Given the scale of shipping expenditure, logistics performance can have a meaningful impact on overall profitability.

**Business implication:** The business should monitor shipping cost by market and evaluate opportunities to improve carrier selection, fulfilment processes, shipping modes, and regional logistics planning.

---

# Recommendations

### 1. Prioritize high-performing Technology products

- Protect inventory availability for high-profit Technology products.
- Identify opportunities for cross-selling complementary Technology products.
- Monitor product-level margins to avoid sacrificing profitability for additional revenue.

### 2. Strengthen Consumer customer retention

- Develop targeted promotions for high-value Consumer customers.
- Use customer purchase history to identify cross-selling opportunities.
- Monitor customer-level sales and profitability to identify valuable accounts.

### 3. Improve APAC logistics efficiency

- Review shipping costs by market and shipping mode.
- Evaluate alternative logistics providers where appropriate.
- Monitor shipping cost as a percentage of sales.
- Balance delivery speed against fulfilment cost.

### 4. Introduce profitability-based discounting

- Avoid applying high discounts uniformly across products.
- Set discount thresholds based on product margins.
- Evaluate whether discounts generate sufficient incremental sales or customer value.
- Monitor profitability before and after major promotional campaigns.

### 5. Manage products using both revenue and profit metrics

- Track sales, profit, profit margin, and quantity together.
- Identify products with high sales but relatively weak profitability.
- Review low-contributing products for pricing, discounting, shipping, or assortment decisions.

### 6. Build a balanced performance management framework

Management should monitor a combination of:

- Revenue growth
- Profit growth
- Profit margin
- Customer value
- Shipping cost
- Shipping time
- Product profitability

This provides a more complete view of business performance than relying on revenue alone.

---

# Conclusion

The analysis demonstrates that strong sales performance does not automatically translate into optimal business performance.

Technology is the strongest overall category, while the Consumer segment represents the largest customer group and APAC is the largest market by sales. At the same time, APAC carries the highest shipping cost, and higher discount levels do not consistently lead to higher profitability.

The key business opportunity is therefore to move from **revenue-focused decision making toward balanced performance management**, combining sales growth, profitability, customer value, and operational efficiency.

The Power BI dashboard provides an interactive framework for identifying these patterns and supporting data-driven decisions across products, customers, markets, and operations.

---

# Tools & Skills

## Tools

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **GitHub**

## Data Preparation

- Data type transformation
- Date and time transformation
- Calculated columns
- Data cleaning and preparation
- Fact and dimension table design

## Data Modeling

The project uses a **star schema** consisting of:

- `FactSales`
- `DimDate`
- `DimProduct`
- `DimCustomer`
- `DimGeography`

Relationships were designed using one-to-many relationships between dimension tables and the central sales fact table.

## DAX & Analytics

Key measures include:

- Total Sales
- Total Profit
- Total Quantity
- Total Orders
- Total Customers
- Profit Margin %
- Average Order Value
- Average Shipping Days
- Average Discount
- Sales YoY %
- Profit YoY %
- Sales per Customer
- Profit per Customer
- Total Shipping Cost
- Shipping Cost %

## Data Visualization

The dashboard uses:

- KPI Cards
- Line Charts
- Bar Charts
- Donut Charts
- Combo Charts
- Scatter Charts
- Slicers

The dashboard is designed to support executive-level performance monitoring and business analysis.

---

## Data Source

The analysis uses the Global Superstore dataset obtained from Kaggle.

Source: [Global Superstore Dataset](https://www.kaggle.com/datasets/fatihilhan/global-superstore-dataset)

The dataset contains approximately 51,000 order-line records covering sales, customers, products, geography, shipping, discounts, and profitability across multiple markets and regions.

---

# Project Objective

The main objective of this project is to demonstrate an end-to-end business intelligence workflow:

**Raw Data → Data Preparation → Data Modeling → DAX → Visualization → Business Insights → Recommendations**

The project demonstrates how Power BI can be used not only to visualize data, but also to translate operational data into actionable business insights.
