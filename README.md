# Commercial-Performance-Profitability-Dashboard
Interactive Power BI dashboard built on the Brazilian Olist E-Commerce dataset featuring advanced DAX, star schema modeling, Power Query ETL, custom Deneb (Vega) visuals, profitability analysis, revenue trends, delivery performance, KPI tracking, and commercial business intelligence.
Commercial Performance & Profitability Dashboard
Project Overview

This project presents an interactive Commercial Performance & Profitability Dashboard developed in Power BI using the Brazilian Olist E-Commerce dataset. The objective is to transform transactional sales data into meaningful business insights through advanced data modeling, DAX calculations, custom visualizations, and interactive report design.

The dashboard enables business users to monitor sales performance, profitability, customer purchasing behavior, payment methods, delivery efficiency, and product category performance through a single analytical interface.

Dataset

Source

Brazilian E-Commerce Public Dataset (Olist)

The dataset contains:

Orders
Customers
Sellers
Products
Payments
Reviews
Delivery information
Product translations

Multiple fact and dimension tables were modeled into a star schema for optimized reporting performance.

Data Modeling

The report was built using a relational star schema.

Fact Tables
FactOrders2
FactPayments
FactReviews
Dimension Tables
DimDate
DimCustomers
DimProducts
DimSellers

Relationships were optimized using one-to-many relationships and a centralized Date dimension for time intelligence.

Data Preparation

The dataset underwent several transformation steps including:

Data cleaning
Null value handling
Duplicate removal
Data type conversion
Product category translation
Date normalization
Delivery bucket generation
Revenue share calculation

Power Query was used for ETL before loading the data model.

DAX Measures

More than 40 reusable DAX measures were created, including:

Revenue
Total Revenue
Revenue YTD
Revenue Last Month
Revenue Growth %
Revenue Variance
Revenue Share %
Profitability
Total Profit
Profit Margin
Profit Variance
Profit Growth
Customers
Total Customers
Average Order Value
Orders
Revenue per Customer
Delivery
Average Delivery Days
On-Time %
Delivery Speed Buckets
Time Intelligence
Month-over-Month Growth
Year-over-Year Growth
Previous Month Comparison
Previous Year Comparison
Dashboard Sections
Executive KPI Cards

These KPI cards provide an executive overview of business performance.

Displayed KPIs include:

Total Profit
Revenue
Profit Margin
Average Order Value

Each KPI also displays:

Previous Month comparison
Previous Year comparison
Conditional formatting
Directional indicators

The cards allow executives to evaluate overall business performance within seconds.

Profit by Order Status

This visualization analyzes order fulfillment status.

Business questions answered:

Which order status generates the highest revenue?
What percentage of orders have been delivered?
How many orders are canceled?
What proportion of orders remain unavailable?

This helps identify operational bottlenecks.

Payment Type Distribution

The donut chart analyzes customer payment preferences.

Metrics include:

Revenue by payment method
Payment distribution
Share of each payment type

Used to identify dominant payment channels and customer purchasing behavior.

Profit by Month

One of the primary analytical visuals.

Features include:

Monthly profit trend
Month-over-month growth %
Dynamic growth labels
Conditional up/down indicators
Time intelligence measures
Interactive year selection

Statistical analysis performed:

Profit MoM %
Profit Growth %
Previous Month comparison
Trend analysis
Peak and low performance identification
Profit by Category

Ranks product categories based on profitability.

Includes:

Top-performing categories
Dynamic ranking
Pagination
Cross-filtering

Business insights:

Highest profit contributors
Product portfolio performance
Revenue concentration
Delivery Speed Analysis

A custom Deneb visualization.

Business metrics displayed:

Profit by delivery speed
Average delivery days
Bubble size indicators
Delivery performance
Profit contribution

Additional tooltip metrics:

Revenue
Profit
Orders
On-Time %
Profit Margin

This visualization was developed using Vega.

Category Slicer

Interactive category filtering enables:

Drill-down analysis
Cross-highlighting
Dynamic KPI updates
Geographic Analysis

Interactive Brazilian state selector allows comparison between different regions.

Supports:

Regional sales analysis
Geographic profitability
State-level performance
Advanced Features

The dashboard incorporates several advanced Power BI techniques.

Time Intelligence
Previous Month calculations
Previous Year calculations
Month-over-Month Growth
Year-over-Year Growth
Advanced DAX

Complex measures were implemented using:

CALCULATE
FILTER
DIVIDE
DATEADD
PREVIOUSMONTH
PREVIOUSYEAR
SWITCH
VAR
SUMX
Custom Visuals

Developed using Deneb (Vega), including:

Profit by Delivery Speed
Interactive tooltips
Bubble overlays
Cross-filter support
User Experience
Bookmarks
Reset button
Dynamic visual switching
Interactive slicers
Conditional formatting
Custom icons
Professional color theme
Business Insights

This dashboard enables organizations to:

Monitor commercial performance
Evaluate profitability
Compare monthly growth
Analyze customer purchasing behavior
Optimize delivery operations
Understand payment preferences
Identify profitable product categories
Track operational efficiency
Technologies Used
Power BI Desktop
Power Query
DAX
Deneb (Vega)
Data Modeling
Star Schema Design
Key Skills Demonstrated
Data Modeling
ETL using Power Query
Advanced DAX
Time Intelligence
Financial KPI Design
Business Performance Analysis
Custom Vega Visual Development
Interactive Dashboard Design
Commercial Analytics
Profitability Analysis
Executive Reporting
Dashboard UX Design
A few recommendations before publishing

Your dashboard is already impressive, but for GitHub I would make these small refinements:

Replace the title "Commerical Performance & Profitability Dashboard" with "Commercial Performance & Profitability Dashboard" (correct the spelling of Commercial).
Add a License section (MIT is common for portfolio projects).
Include a short Future Improvements section, such as adding forecasting, RLS, or live data integration.
Add a few screenshots or a GIF showing interactions (filters, bookmarks, hover tooltips) so visitors immediately see the dashboard in action.

This level of documentation makes the project look much more like a professional portfolio piece rather than just a Power BI file.
