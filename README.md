# Business-insights-360

Power BI Project 

## Project Overview

 AtliQ Hardware, a rapidly expanding computer hardware company, initiated its first-ever Power BI analytics implementation to transition from static reporting to dynamic, data-driven decision-making.
The project delivers actionable insights across Finance, Sales, Marketing, and Supply Chain, empowering stakeholders to:

-  Monitor performance in real time
-  Identify growth opportunities
- Strengthen competitive positioning in the market.
##  Live Dashboard  
Link for the Business Insights 360 Dashboard - [Live Dashboard]( https://lnkd.in/d73TghAn)
## 📂Datasets
Before starting the analysis, it’s important to understand the structure of the data. The project uses two main types of tables:

-  **Dimension Table:** Contains static reference data such as customer information, product details.
-  **Fact Table:** Contains Transactional data.
 
  **gdb041:**

- dim_customer
- dim_market
- dim_product
- fact_forecast_monthly - This table is used to forecast the customer’s need in advance, which can help in Higher customer satisfaction and reduced cost in warehouses for storage purposes
- fact_sales_monthly - This table is more or less is same as the fact_forecast_monthly table, but the last column has the value of the sold quantity instead of the forecast value.
  
**gdb056:**

- freight_cost
- gross_price
- manufacturing_cost
- Pre_invoice_dedutions
- Post_invoice_deductions
 ## 🗂 Data modeling
 Data modeling in Power BI is the process of connecting and organizing tables with relationships so data can be analyzed effectively.
 In Power BI projects, data modeling defines how different tables relate to each other, which helps create accurate reports and visualizations.

**A good data model:**
- Separates facts (numbers or transactions) from dimensions (descriptive details)
- Uses relationships to connect tables
- Removes duplicate data for better efficiency
- Makes it easier to filter, group, and analyze information
  
 🔄 **Data Analyst Workflow**
  
A data analyst’s work usually follows these four main steps:

-  **Data Extraction** – Collecting data from different sources such as databases, Excel files, or online platforms.

-  **Data Cleaning** – Removing errors, filling missing values, and making sure the data is consistent.

-  **Data Modeling** – Organizing the data into connected tables so it’s easy to use for analysis.

-  **Data Analysis** – Studying the data to create clear reports, dashboards, and insights for decision-making.

This step-by-step approach helps keep the analysis accurate and meaningful.

  In this project, we used a Snowflake schema for data modeling, which keeps the data organized, easy to manage, and ready for creating clear and useful reports.
![Data modeling](https://github.com/Shahna-k25/Business-insights-360/blob/main/Data%20modeling.png.png)
 
 
## 🛠️Technologies Used

- **Power BI** – Interactive dashboards and data visualization

- **Excel** – Data preprocessing and basic analysis

- **SQL** – Data extraction and querying from databases

- **DAX** (Data Analysis Expressions) – Advanced calculations and custom measures in Power BI

- **Power Query** – Data transformation and shaping

- **MySQL** – Database for storing and managing raw data
  
 ## 📊Power BI Techniques Learned
 
 - **Data Import & Integration** – Connected to Excel, SQL, and web data sources; merged and appended datasets.

- **Data Transformation** (Power Query) – Cleaned, formatted, and prepared raw data; handled missing/inconsistent values.

- **Data Modeling** – Built relationships, used star/snowflake schemas, and created calculated columns/tables.

- **DAX** (Data Analysis Expressions) – Wrote measures for KPIs, dynamic calculations, and advanced analytics.

- **Visualization Design** – Created interactive dashboards with charts, slicers, maps, and tables.

- **Interactivity & Filtering** – Added slicers, drill-through, bookmarks, and synced filters.

- **Performance Optimization** – Reduced load time using optimized data models and aggregations.

- **Publishing & Sharing** – Published to Power BI Service, scheduled refreshes, and shared securely.

- **Advanced Features** – Applied Row-Level Security (RLS) and AI visuals for insights.

 ## 📁 Features & Views
  
 - **Executive View** – Overview of KPIs, profitability, and fiscal performance.

-  **Sales View** – Product sales trends, customer segments, and gross margin insights.

-  **Finance View** – Profit & Loss, Net Sales, Gross Price, COGS, and forecasts.

-  **Marketing View** – Product trends, region-wise analysis, and profitability metrics.

-  **Supply Chain View** – Forecast accuracy, quantity analysis, net error, and risk profile.

-  **Info & Support View** – Project guide and onboarding instructions.
  
  ## 📚 Business Terminology
  
- **Gross Price** – Total price before any deductions.

- **Pre-Invoice Deductions** – Discounts or allowances applied before invoicing.

- **Post-Invoice Deductions** – Adjustments made after the invoice is issued.

- **Net Invoice Sale** – Revenue after all deductions are applied.

- **Gross Margin** – Profit percentage after subtracting COGS from sales.

- **Net Sales** – Revenue after removing returns, discounts, and allowances.

- **Net Profit** – Actual profit after all expenses and taxes.

 - **COGS** (Cost of Goods Sold) – Direct cost of producing goods sold.

- **YTD** (Year to Date) – Period from the start of the year until today.

- **YTG** (Year to Go) – Remaining period left in the current year.

- **Direct Sales** – Sales made directly to customers without intermediaries.

- **Retailer** – A business selling goods directly to consumers.

- **Distributor** – Buys in bulk from manufacturers and sells to retailers or businesses.

- **Consumer** – The end user who purchases goods or services for personal use.


