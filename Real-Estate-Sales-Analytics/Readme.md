
🏠 Real Estate Sales Analytics
A cloud-powered sales analytics solution connecting Google BigQuery (GCP) to Power BI — delivering advanced DAX-driven insights on property pricing, regional sales trends, and market performance for real estate investment decision-making.


📌 Problem Statement
Real estate investors and market analysts often rely on static spreadsheets or delayed reports to make pricing and investment decisions. This project builds a live, interactive analytics platform that connects directly to a cloud data warehouse — enabling self-serve access to YoY growth, regional pricing trends, and AI-powered market influencer analysis.


🎯 Business Objective
Analyze year-over-year sales growth and rolling revenue trends across regions
Identify key factors influencing property prices using AI-powered visuals
Enable data-driven pricing strategy and market positioning decisions


🛠️ Tech Stack
Layer
Tools Used
Cloud Data Warehouse
Google BigQuery (GCP)
SQL Exploration
BigQuery SQL Editor
Data Shaping
Power Query Editor (M Language)
Advanced Measures
DAX (DATESINPERIOD, TOTALYTD, ALLEXCEPT, MEDIANX)
AI Visual
Key Influencers Visual (Power BI)
Deployment
Power BI Service (Dedicated Workspace)
Connectivity
Live Connection — BigQuery → Power BI



🏗️ Architecture
Google BigQuery (GCP) → Live Power BI Connection → Power Query Shaping → DAX Measures → Multi-Page Report → Power BI Service

Connection — Google BigQuery connected as a live data source to Power BI Desktop
Exploration — SQL used in BigQuery to explore schema, validate data types, and filter records
Shaping — Power Query Editor used for additional transformations and column profiling
Modeling — Advanced DAX measures created for time intelligence and regional analysis
Visualization — Multi-page interactive report with AI-powered visuals
Deployment — Published to Power BI Service in a dedicated workspace


📐 Advanced DAX Measures
Measure
DAX Function
Business Use
YoY Sales Growth
CALCULATE, SAMEPERIODLASTYEAR
Compare current vs. prior year performance
Rolling 12-Month Sales
DATESINPERIOD
Smooth seasonal fluctuations in trend analysis
Year-to-Date Revenue
TOTALYTD
Track cumulative sales against annual targets
Regional Distribution
ALLEXCEPT
Remove all filters except region for comparison
Median Price by Region
MEDIANX
Surface typical (not average) pricing per market



📊 Dashboard Overview
Multi-page interactive report:

Page
Visuals
Insight
Sales Overview
KPI cards, clustered bar chart
Total revenue, transaction volume, YoY growth
Regional Analysis
Donut chart, scatter plot
Regional price distribution, volume vs. price
Trend Analysis
Line chart (rolling 12M, YTD)
Seasonal patterns, revenue trajectory
AI Insights
Key Influencers Visual
Top factors driving property price changes


📸 Screenshot: (Add your Power BI dashboard screenshot here)


🔍 Key Insights
Properties in urban tier-1 regions showed 18% higher YoY price growth compared to suburban zones
The Key Influencers visual identified property size and proximity to transit as the top 2 price drivers
Rolling 12-month analysis revealed Q3 as the peak sales season — accounting for 34% of annual transaction volume


📁 Project Structure
real-estate-sales-analytics/

│

├── sql/                   # BigQuery SQL exploration scripts

├── powerbi/               # Power BI .pbix file

├── dax/                   # DAX measure documentation

├── screenshots/           # Dashboard screenshots

└── README.md


💡 Business Impact
This solution replaces static, delayed market reports with a live cloud-connected analytics platform — giving real estate analysts and investors self-serve access to pricing trends, regional comparisons, and AI-driven market insights for faster, more confident investment decisions.


👤 Author
Dnyaneshwar Singh MSc Computer Applications | MIT ACSC Pune LinkedIn | GitHub

