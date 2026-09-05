Snowflake Sales Analytics
=========================

A cloud-based sales analytics project built using Snowflake, SQL,
Power BI, and DAX.

Project Objective
-----------------
Build a sales analytics pipeline that transforms raw retail sales
data into analysis-ready datasets and an interactive Power BI dashboard.

Architecture
------------
Kaggle Dataset
      ↓
Snowflake Internal Stage
      ↓
RAW Layer
      ↓
CLEAN Layer
      ↓
ANALYTICS Layer
      ↓
Power BI + DAX

Technologies
------------
- Snowflake
- SQL
- Power BI
- DAX

Dataset
-------
Superstore retail sales dataset containing 9,800 transactions.

Snowflake Implementation
------------------------
1. Created Snowflake warehouse and database
2. Created RAW, CLEAN and ANALYTICS schemas
3. Created CSV file format and internal stage
4. Loaded raw sales data into Snowflake
5. Converted string dates into DATE fields
6. Calculated shipping duration
7. Created analytical views for sales reporting
8. Connected the ANALYTICS layer to Power BI

Power BI Dashboard
------------------
The dashboard provides:
- Total Sales
- Total Orders
- Total Customers
- Average Order Value
- Sales trends
- Regional sales performance
- Category performance
- Customer segment performance
- Top 10 products
- Shipping analysis

Key Snowflake Concepts
----------------------
- Warehouses
- Databases
- Schemas
- Tables
- File Formats
- Internal Stages
- COPY INTO
- SQL transformations
- Analytical Views

Project Structure
-----------------
sql/        → Snowflake SQL scripts
powerbi/    → DAX measures and dashboard
screenshots/ → Project screenshots
data/       → Dataset information

Note
----
The dataset was sourced from Kaggle. The raw CSV is not included
in this repository; the SQL scripts document the complete Snowflake
loading and transformation process.
