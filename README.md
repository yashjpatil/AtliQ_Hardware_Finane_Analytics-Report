AtliQ_Hardware_Finane_Analytics-Report

PROJECT OVERVIEW

AtliQ Hardware is a global manufacturing company specializing in computer hardware products such as mice, PCs, keyboards, and related accessories.

This project focuses exclusively on the Financial Analytics phase of the business. By analyzing raw transactional data against cost structures, it provides a clear view of the company’s financial health, including:

Net Sales
Cost of Goods Sold (COGS)
Gross Margin (GM)
Gross Margin % (GM%)

The analysis helps evaluate profitability across global markets and sub-zones, enabling better financial decision-making.

STAR FRAMEWORK

SITUATION

AtliQ Hardware experienced strong global expansion, reaching $598.9M in revenue (2021). However, leadership observed that revenue growth did not always translate into profitability. Rising operational and supply chain costs were affecting margins, but there was no structured visibility into where and why profits were leaking.

TASK

The objective was to design a financial intelligence dashboard that could:

Present a Profit & Loss (P&L) Statement by Market
Track Net Sales, COGS, and Gross Margin %
Analyze Quarterly GM% trends across sub-zones (2019–2021)

ACTION

Data Cleaning & ETL (Power Query)
Cleaned and standardized large fragmented datasets
Aligned regional, calendar, and cost data structures
Data Modeling (Power Pivot – Star Schema)
Built a robust data model
Connected fact table (fact_sales) with dimension tables (dim_customer, dim_market, dim_date)
Financial Calculations
Created calculated columns and measures for:
Net Sales
COGS
Gross Margin
GM%
Dashboard Design & UX
Built a corporate-style financial dashboard
Applied conditional formatting for margin analysis
Highlighted high-profit and low-margin regions for quick insights

RESULT & KEY BUSINESS INSIGHTS

High-Volume vs Thin-Margin Risk
India was the largest revenue contributor ($161.26M) but operated at a lower 32.0% GM%, driven by higher operational costs.

Profit Margin Compression
India: 42.4% → 32.0% (2019–2021)
ANZ: 42.6% → 38.3%

Top Profitable Markets
New Zealand: 48.2% GM% ($5.5M margin)
Japan: 46.5% GM%
United Kingdom: 45.1% GM%

High-Risk Market
Germany: 26.2% GM% ($3.1M margin on $12.01M sales)
Indicates cost inefficiency and need for operational restructuring

Quarterly GM% Trends by Sub-Zone


TOOLS & TECHNOLOGIES USED

Microsoft Excel (Advanced)
Power Query (ETL)
Power Pivot (Data Modeling)
Star Schema Design
Financial Analysis Techniques

KEY LEARNING

This project demonstrates how raw sales data can be transformed into executive-level financial intelligence, enabling businesses to identify profit leakage, optimize markets, and improve decision-making.
