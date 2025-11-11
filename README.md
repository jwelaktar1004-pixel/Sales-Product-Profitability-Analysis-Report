Sales & Product Profitability Analysis Report

Prepared by: [Your Name] Date: [Insert Date] Dataset: Sales transactions, product and customer details



Objective

The purpose of this analysis is to:

Evaluate how company revenue is distributed across products and product lines.

Assess profitability and pricing effectiveness.

Identify top-performing products and product lines.

Support data-driven decision-making for sales, marketing, and inventory planning.

Data Overview

Number of Orders:  (from Python EDA)

Time Period Covered: 2003–2005 (from YEAR_ID)

Number of Products: Y unique SKUs

Number of Customers: Z

Key Columns:

SALES: Total revenue per order line

PRODUCTLINE: Product category

PRICEEACH & MSRP: Selling price and manufacturer price

DEALSIZE: Small, Medium, Large deals

DISCOUNT_PERCENT: Derived from MSRP and PRICEEACH



Key Performance Indicators (KPIs) KPI Value Insight Total Revenue $X Overall business performance ~80% of revenue comes from few products (Pareto principle) Average Discount % 9.16% Measures pricing strategy and discount impact Total Orders W Total sales volume across the period

Tip: Use Card visuals in Power BI to show these KPIs at the top of your dashboard for quick insights.



Revenue Analysis 4.1 Revenue by Product Line

Highest revenue: [6.09]

Lowest revenue: [1.30]

Actionable insight: Focus marketing and inventory on high-revenue product lines.

Visual: Bar chart of total revenue per product line.

4.2 Revenue Trend Over Time

Revenue increased from 2003 to 2005, with seasonal peaks in [Months].

Certain product lines show growth, while others are flat or declining.

Visual: Line chart of total revenue per year.



Revenue Concentration (Pareto Analysis)

Top 3 products contribute ~80% of total revenue.

Dependency on few products highlights risk of revenue concentration.

Visual: Pareto chart (Top products revenue + cumulative %)

Recommendation: Consider diversifying product portfolio and promoting underperforming products.



Pricing & Discount Analysis

Average discount % varies across product lines:

High discounts do not always correlate with higher revenue.

Products with moderate pricing often achieve high revenue, suggesting pricing optimization opportunities.

Visual: Scatter plot of discount % vs total sales per product.

Action: Review discount strategies for low-performing products and top sellers.



Deal Size Insights

Large deals are concentrated in [ProductLineA, ProductLineB].

Small and medium deals occur across most product lines but contribute less to revenue.

Visual: Stacked bar chart of revenue by product line and deal size.

Recommendation: Focus on upselling and targeting potential large deals in top-performing product lines.



Time-Based Pricing Trends

Average selling price per product line remained stable for [ProductLine1].

Price fluctuations in other lines indicate potential seasonal promotions or discount campaigns.

Visual: Line chart of average price per year per product line.



Summary of Insights

Revenue Concentration: Few products drive majority of revenue → focus strategy on top SKUs.

Pricing Effectiveness: High discounts do not always lead to higher sales → optimize discounting strategy.

Deal Opportunities: Large deals are concentrated in specific product lines → target high-value deals.

Growth & Trends: Revenue trends identify high-performing lines and periods → informs inventory planning.

Recommendations

Prioritize inventory and marketing for top-performing product lines and products.

Review discount strategies for products with low revenue despite high discounts.

Explore promotional campaigns to increase medium and small deal sizes.

Monitor revenue concentration risk and diversify product offerings.



Next Steps

Implement Power BI dashboard with KPIs and visualizations for ongoing monitoring.

Set up alerts for revenue drops or high discount usage.

Combine sales insights with customer behavior analysis for targeted campaigns.

Visuals to Include in the Report

Card Visuals: Total Revenue, Top Product Revenue %, Average Discount %, Total Orders

Bar Charts: Revenue by Product Line

Line Charts: Revenue trends over time, average selling price trends

Pareto Chart: Top products vs cumulative revenue %

Scatter Plot: Discount % vs total sales per product

Stacked Bar: Revenue by product line and deal size
