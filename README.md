# E-Commerce Sales Intelligence Dashboard — (Power BI)

The Flipkart Sales Intelligence Dashboard is an advanced Business Intelligence project developed using Power BI to analyze e-commerce sales performance, profitability drivers, discount impact, and regional demand patterns.
This project transforms raw transactional data into actionable business insights using structured data modeling, Power Query transformations, DAX-based KPI calculations, and interactive visual analytics.

# Business Objective

The primary objective of this project is to:
- Analyze overall sales and profit performance
- Identify category-level profitability drivers
- Evaluate discount impact on profit margins
- Understand regional demand variations
- Track payment method contribution trends
- Implement KPI target benchmarking for performance monitoring
- Enable data-driven business decisions through interactive reporting

# Data Source

- Source: Kaggle — Flipkart Sales Dataset
- Type: Structured e-commerce transaction dataset
- Format: CSV

# Dataset Includes:
- Order Date
- Product Category
- Region
- Customer Segment
- Payment Method
- Quantity Sold
- Total Sales (INR)
- Profit (INR)
- Discount (%)


# Data Cleaning & Transformation (Power Query)
Data preparation steps performed:
- Removed duplicate records
- Handled missing/null values
- Standardized categorical fields
- Converted data types (Date, Currency, Percentage)
- Created Month-Year hierarchy
- Built a dedicated Date Table for time intelligence
- Derived calculated columns where required


# DAX Measures Created
Key performance indicators (KPIs) were developed using DAX:

*Core KPIs*

- Total Sales
- Total Profit
- Profit Margin %
- YTD Profit

*Target & Benchmarking*

- Sales Target
- Profit Target 
- KPI Variance 



# Dashboard Features
The dashboard is designed as a single-page executive report with interactive drill-down capabilities.
Included Visuals:

- KPI Cards (Sales, Profit, Margin, Target Variance)
- Monthly Sales vs Profit Trend (Combo Chart)
- Category-wise Profit & Discount Impact Analysis (Funnel Chart)
- Region-wise Sales & Quantity Comparison (Column Chart)
- Payment Method Revenue Split (Donut Chart)
- Discount vs Profit Sensitivity (Scatter Chart)
- Interactive Slicers (Date, Category, Region, Segment)

The dashboard follows a professional Flipkart-inspired theme with clean contrast and performance-focused visual hierarchy.


# Key Insights

- Electronics category contributed the highest share of total profit.
- Profitability is highly sensitive to discount levels.
- Monthly fluctuations indicate seasonality and promotional impact.
- Regional demand varies significantly, suggesting need for localized strategies.
- Digital payment methods dominate revenue contribution.
- Target benchmarking highlights short-term performance gaps.


# Tools & Technologies Used

- Power BI
- DAX
- Power Query
- Kaggle Dataset
- Microsoft Excel (Data Handling)


# Skills Demonstrated

- Data Cleaning & Transformation
- Dimensional Data Modeling
- KPI Development & Benchmarking
- Time Intelligence (YTD Calculations)
- Business-Oriented DAX Logic
- Dashboard UI/UX Design
- Analytical Insight Generation

# Project Outcome

This project demonstrates the ability to, Convert raw e-commerce data into structured analytical models, Identify profitability drivers beyond basic revenue metrics, Implement dynamic KPI monitoring using DAX, Design executive-level dashboards for business decision-making. It showcases practical skills required for roles such as Power BI Developer, Business Intelligence Analyst, Data Analyst.


