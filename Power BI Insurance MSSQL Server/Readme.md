🛡️ Prism Insurance BI & Sentiment Analysis
An end-to-end Business Intelligence solution for an insurance reporting use case — combining executive KPI dashboards, role-based data governance, and customer sentiment analysis into a single Power BI platform.


📌 Problem Statement
Insurance companies deal with large volumes of claims data, regional performance metrics, and customer feedback — often managed in disconnected systems. Decision-makers lack a unified, secure dashboard that shows both operational KPIs and customer satisfaction trends in real time. This project builds that solution using on-premises SQL Server as the data source and Power BI as the reporting layer.


🎯 Business Objective
Give regional managers a real-time view of claims exposure and performance KPIs by segment
Enforce data governance so each user only sees data relevant to their role (RLS)
Surface customer sentiment trends to help the CX team prioritize complaint resolution


🛠️ Tech Stack
Layer
Tools Used
Data Source
SQL Server (on-premises)
Data Transformation
Power Query (M Language)
Data Modeling & Measures
DAX (calculated columns, measures, KPIs)
Security
Row-Level Security (RLS)
Deployment
Power BI Service, On-premises Data Gateway
Refresh
Scheduled Data Refresh (gateway-backed)
Text Analytics
Sentiment Analysis via Power Query Editor



🏗️ BI Pipeline
SQL Server (On-Premises) → Power Query Transformations → Data Model (DAX) → Power BI Dashboard → Power BI Service (RLS + Scheduled Refresh)

Ingestion — Connected on-premises SQL Server to Power BI via Data Gateway
Transformation — Power Query used for data shaping, type casting, and null handling
Modeling — Star schema data model with DAX measures for KPIs and trend analysis
Security — RLS roles defined in Power BI Desktop, validated post-deployment in Service
Sentiment Analysis — Customer feedback text analyzed in Power Query Editor for tone classification
Deployment — Published to Power BI Service workspace with Scheduled Refresh configured


📊 Dashboard Overview
8 visuals across dedicated report pages:

Visual
Purpose
KPI Cards
Claims volume, approval rate, avg settlement time
Ribbon Chart
Segment performance trends over time
Matrix
Regional claims breakdown by category
Drill-through Page
Individual claim deep-dive by region/segment
Donut Chart
Claims distribution by policy type
Sentiment Dashboard
Positive/Neutral/Negative feedback breakdown
Trend Line
Customer satisfaction score over time
Score Cards
Net Promoter insights by region


📸 Screenshot: (Add your Power BI dashboard screenshot here)


🔐 Row-Level Security (RLS)
Defined RLS roles in Power BI Desktop restricting data access by region
Each regional manager sees only their territory's claims data
Validated RLS post-deployment in Power BI Service using "View as role" feature
Gateway-backed Scheduled Refresh keeps the live report in sync with source SQL Server


🔍 Key Insights
Region X had 28% higher claims volume than average — flagged for underwriting review
Sentiment analysis revealed 34% of customer feedback was negative, with billing complaints as the top driver
Average claim settlement time exceeded SLA by 12 days in Q2 — surfaced via KPI card alert


📁 Project Structure
prism-insurance-bi-sentiment/

│

├── data/                  # Sample anonymized dataset

├── sql/                   # SQL Server query scripts

├── powerbi/               # Power BI .pbix file

├── screenshots/           # Dashboard screenshots

└── README.md


💡 Business Impact
This solution consolidates fragmented claims data and customer feedback into a single secure BI platform — enabling regional managers to monitor exposure in real time and the CX team to prioritize complaint resolution based on sentiment trends, rather than manual feedback review.


👤 Author
Dnyaneshwar Singh MSc Computer Applications | MIT ACSC Pune LinkedIn | GitHub

