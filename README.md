# customer360-azure-snowflake-project
## AI-Powered Customer 360 Analytics Platform
![Architecture Diagram](images/customer360_architecture.png)

## Project Overview

### Built an end-to-end Customer 360 analytics platform using Azure, Snowflake, SQL, and Power BI to centralize customer, orders, website, support, and marketing data for business insights, customer segmentation, churn analysis, and AI-ready analytics.

Architecture
Source Data
     ↓
Azure Data Factory
     ↓
ADLS Gen2
(Bronze / Silver / Gold)
     ↓
Snowflake
(RAW / SILVER / GOLD)
     ↓
Power BI Dashboard
Tools Used
Azure Data Factory
ADLS Gen2
Snowflake
SQL
Power BI
GitHub

# Day 1 — Azure Project Setup
## Objective

Set up the complete Azure cloud environment and project structure.

Architecture Setup
Azure Resource Group
        ↓
ADLS Gen2 Storage
        ↓
Bronze / Silver / Gold Containers
        ↓
Azure Data Factory
        ↓
Snowflake Database
Tasks Completed
Created Azure Resource Group
Created ADLS Gen2 Storage Account
Created Bronze, Silver, Gold containers
Created Azure Data Factory
Created Snowflake database and schemas
Organized GitHub project structure
Key Outcome

Established the foundational cloud infrastructure for the Customer 360 analytics platform.

# Day 2 — Dataset Creation & Bronze Upload
## Objective

Create customer analytics datasets and upload them into the Bronze layer.

Dataset Flow
CSV Files
(customers, orders, clicks)
          ↓
ADLS Bronze Layer
          ↓
Organized Folder Structure
Datasets Created
customers.csv
orders.csv
website_clicks.csv
support_tickets.csv
marketing_campaigns.csv
Key Outcome

Prepared the raw ingestion layer for pipeline processing.

# Day 3 — Azure Data Factory Pipelines
## Objective

Build ingestion pipelines using Azure Data Factory.

Pipeline Flow
Bronze Layer
      ↓
ADF Copy Pipeline
      ↓
Silver Layer
Tasks Completed
Configured Linked Services
Created datasets
Built Copy Data pipelines
Triggered and monitored pipelines
Key Outcome

Successfully automated cloud data ingestion workflows.

# Day 4 — Snowflake Setup & RAW Layer
## Objective

Set up Snowflake environment and create RAW tables.

Snowflake Architecture
CUSTOMER360_DB
       ↓
RAW Schema
SILVER Schema
GOLD Schema
Tasks Completed
Created Snowflake warehouse
Created CUSTOMER360_DB database
Created RAW, SILVER, GOLD schemas
Created RAW ingestion tables
Key Outcome

Built the cloud data warehouse foundation.

# Day 5 — Load Data into RAW Tables
## Objective

Load Bronze layer data into Snowflake RAW tables.

Data Loading Flow
ADLS Bronze
      ↓
Snowflake External Stage
      ↓
COPY INTO Command
      ↓
RAW Tables
Tasks Completed
Created file formats
Created external stages
Connected ADLS to Snowflake
Loaded data using COPY INTO
Key Outcome

Successfully ingested cloud storage data into Snowflake.

# Day 6 — SILVER Layer Transformations
## Objective

Clean and standardize data into analytics-ready SILVER tables.

Transformation Flow
RAW Tables
     ↓
SQL Cleaning Logic
     ↓
Remove Nulls & Duplicates
     ↓
SILVER Tables
SQL Concepts Used
DISTINCT
CASE WHEN
DATEDIFF
LOWER / UPPER
Key Outcome

Built trusted and clean business-ready datasets.

# Day 7 — GOLD Analytics Layer
## Objective

Create business KPI and Customer 360 analytics tables.

GOLD Layer Flow
SILVER Tables
      ↓
Business Aggregations
      ↓
KPI Tables
      ↓
CUSTOMER360_MASTER
GOLD Tables Created
CUSTOMER_LIFETIME_VALUE
REPEAT_CUSTOMERS
REVENUE_BY_SEGMENT
SUPPORT_ANALYTICS
MARKETING_CONVERSION
Key Outcome

Built enterprise analytics and reporting layer.

# Day 8 — AI Customer Features
## Objective

Create AI-ready customer features and churn analytics.

AI Analytics Flow
GOLD Layer
     ↓
Feature Engineering
     ↓
Customer Scores
Churn Risk
Engagement Levels
AI Features Created
customer_score
churn_risk
engagement_level
support_risk_flag
Key Outcome

Prepared AI-ready customer analytics datasets.

# Day 9 — Power BI Dashboard
## Objective

Build an interactive Customer 360 dashboard in Power BI.

Dashboard Flow
Snowflake GOLD Tables
          ↓
Power BI Connection
          ↓
KPIs + Charts + Filters
          ↓
Customer 360 Dashboard
Dashboard KPIs
Total Revenue
Total Customers
Customer Score
High-Risk Customers
Dashboard Features
Revenue analytics
Customer segmentation
Churn analytics
Interactive filters
Key Outcome

Built a complete end-to-end business intelligence dashboard.
