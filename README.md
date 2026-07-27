Sales & Customer Churn Analysis Dashboard

An end-to-end data analytics project covering data cleaning in Excel, business-logic querying in MySQL, and interactive visualization in Power BI. The project analyzes sales performance, customer behavior, product profitability, and return patterns across 1,000+ transactions, replacing manual Excel-based reporting with a fully automated, real-time Power BI dashboard.

Overview
Businesses often rely on static Excel reports that take hours to update and fail to surface hidden patterns like recurring returns, declining customer segments, or seasonal dips in revenue. This project solves that by building a clean data pipeline — from raw Excel data, through SQL-based business logic, into a 3-page interactive Power BI dashboard that updates dynamically and lets stakeholders self-serve their own analysis using slicers and filters.

Dashboard Preview

**1. Sales Performance Dashboard
Gives a high-level view of overall sales, profit, and order volume. Includes monthly sales trend, yearwise sales & profit comparison, and quarterly sales distribution by year, helping track growth and seasonality at a glance.


2. Customer & Product Analysis
Focuses on which products, categories, and customer segments are driving revenue. Includes top 10 products by sales, category-wise sales split, profit by sub-category, and profit vs. sales by segment.


3. Return & Profitability Analysis
Analyzes how returns are eating into profit. Includes returns by category, top returned sub-categories, a regional profit map, monthly return trend, and a discount % vs. profit scatter plot to spot problematic discounting patterns.


Tech Stack
- Excel — Data cleaning, structuring, and initial exploration of raw sales data
- MySQL — Writing and executing queries for business logic, aggregation, and trend analysis
- Power BI — Building the interactive dashboard, data modeling, and relationships
- DAX — Writing custom calculated measures and KPIs for dynamic reporting

Process

1. Data Cleaning (Excel)
Cleaned and structured over 1,000 rows of raw sales data before it was ready for analysis. This included handling missing values, removing duplicate records, fixing inconsistent formatting across columns, and standardizing date, category, region, and segment fields so the data could be reliably modeled in Power BI.

2. SQL Analysis (MySQL)
Once the data was clean, it was loaded into MySQL to answer specific business questions using SQL queries, including:
- Top customer identification by revenue and order frequency
- Return rate analysis across categories and sub-categories
- Top 10 revenue-loss customers due to returns
- Shipping delay patterns and their effect on customer satisfaction
- Salesperson performance benchmarking
- Pareto (80/20) analysis to identify the customers/products driving most revenue
- Churn prediction based on order recency and frequency
- 30-day moving average of sales to smooth out daily fluctuations
- Month-over-Month (MoM) growth tracking to measure business momentum

3. Power BI Dashboard (3 Pages)
The cleaned and query-validated data was then modeled in Power BI to build a 3-page interactive dashboard:
Page 1 – Sales Performance:KPI cards for total sales, profit, orders, quantity, and profit margin, backed by monthly, yearly, and quarterly trend visuals.

Page 2 – Customer & Product Analysis: Deep dive into top-performing products, category-wise sales distribution, profit by sub-category, and profit/sales performance by customer segment.

Page 3 – Return & Profitability Analysis: Breakdown of returns by category and sub-category, a regional profit map, monthly return trends, and the relationship between discounting and profit erosion.

All three pages share consistent slicers (Region, Category, Sub-Category, Segment, Date Range) so users can filter across the entire report without switching pages.

DAX Measures
A set of custom DAX measures power the KPIs and dynamic visuals across the report:
- YoY Growth %
- Profit Margin %
- Return Rate %
- Average Order Value (AOV)
- Sales Contribution %
- Lost Sales Value
- 30-Day Moving Average

Key Insights
- Total sales crossed **2M** with **250K** in total profit across **5K orders**, reflecting a healthy overall profit margin.
- The **Technology category drove 27% of total sales** but also carried the **highest return rate** among all categories, flagging it as a priority for quality audits.
- The **overall return rate stood at 23.1%**, contributing to an estimated **150.95K in lost sales value** — a significant chunk of potential revenue.
- Sales showed a **consistent spike in Q4 every year**, pointing to strong seasonal demand that could be leveraged for targeted campaigns and inventory planning.
- With an **average order value of $397.08** across **793 unique customers**, the data also revealed clear opportunities to increase order frequency among mid-tier customers.

