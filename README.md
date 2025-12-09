# Ecommerce-Dashboard

### 1. E-Commerce Analytics:
 US Sales & Profit Insights Dashboard. A dynamic, interactive Power BI dashboard designed to analyze end-to-end e-commerce sales performance—focusing on Year-to-Date (YTD) metrics, regional trends, product performance, and customer segmentation.

### 2. Purpose:
This dashboard provides a comprehensive overview of sales activities for a US-based e-commerce company. It tracks key performance indicators (KPIs) like Sales, Profit, Quantity, and Profit Margin, comparing current performance against the previous year (YoY). The tool is intended for sales managers and stakeholders to identify best-performing regions, optimize product inventory, and uncover profitable customer segments.

### 3. Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – The primary tool for data visualization and report design.

🛢️ Microsoft SQL Server – Used as the database backend to import and manage the raw data before connecting to Power BI.

🧠 DAX (Data Analysis Expressions) – Extensive use of time-intelligence functions (e.g., TOTALYTD, SAMEPERIODLASTYEAR) to calculate YTD Sales, YoY growth percentages, and dynamic conditional formatting (Green/Red icons).

📂 Power Query – Used for data connectivity, transformation, and cleaning (ETL) to ensure data quality.

📅 Date Table – A custom calendar table created to support accurate time-intelligence calculations.

### 4. Data Source
Source: Kaggle (US E-commerce Dataset) 

The project utilizes two primary data tables:

E-commerce Data: Contains ~113k rows of transactional data including Order Date, Customer ID, Product Name, Category, Sales, Profit, Quantity, and Shipping Mode.
US State Lat/Long: A supplementary table containing latitude and longitude codes for US states to enable accurate map visualizations.

### 5. Features:
Business Problem Monitoring year-over-year growth in a fast-paced e-commerce environment is challenging without centralized data. 

Stakeholders need to quickly answer:

Is our profit margin increasing or decreasing compared to last year?
Which states drive the most revenue?
Which products are dragging down overall performance?

Goal of the Dashboard To provide a centralized view of sales health that enables:

Real-time monitoring of YTD Sales, Profit, and Quantity.
Identification of declining categories or regions.
Strategic decision-making regarding inventory and marketing focus.

#### Walkthrough of Key Visuals:

KPI Banner (Top):

Displays YTD Sales, YTD Profit, YTD Quantity, and YTD Profit Margin.
Includes Sparklines to show monthly trends and Dynamic Icons (Green/Red arrows) to indicate positive or negative YoY growth.

Sales by Category (Matrix):

A detailed breakdown of sales by category (e.g., Furniture, Office Supplies) with conditional formatting to highlight growth trends.

Sales by State (Map):

A bubble map visualization where bubble size represents sales volume. Includes a zoom feature and region-based color coding (West, East, Central, South).

Top 5 & Bottom 5 Products (Bar Charts):

Two bar charts side-by-side to instantly identify the best-selling products and the lowest-performing items to assist with inventory decisions.

Regional & Shipping Analysis (Donut Charts):

Sales by Region: Visualizes revenue distribution across the four main US regions.

Sales by Shipping Type: Analyzes the popularity of shipping classes (Standard, First Class, etc.).

Interactive Slicers:

Consumer Segment Slicer: Allows users to filter the entire dashboard by segment (Consumer, Corporate, Home Office).

Business Impact & Insights

Trend Analysis: The sparklines and YoY metrics allow for immediate detection of months where sales dipped, prompting investigation.

Product Strategy: "Bottom 5 Products" analysis helps in deciding whether to discontinue items or run promotions.

Regional Focus: The map highlights that states like California often drive the highest sales, suggesting where marketing budget should be allocated.

### 6. Screenshot:
![Dashboard Preview](https://github.com/chinmai-budati/Ecommerce-Dashboard/blob/main/Ecommerce%20Dashboard.png)
