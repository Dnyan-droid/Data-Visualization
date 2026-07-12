
🌾 Agriculture Climate & Yield Analytics
A cloud-based end-to-end analytics pipeline built to help agricultural stakeholders understand how climate variables — rainfall, temperature, and humidity — impact crop yield across regions and seasons.


📌 Problem Statement
Agricultural planning is often reactive rather than data-driven. Farmers, policymakers, and agri-businesses lack a centralized, visual tool to understand how shifting climate patterns directly affect crop output. This project addresses that gap by building a scalable cloud analytics solution that connects raw climate data to yield outcomes.


🎯 Business Objective
Identify which climate variables have the highest correlation with crop yield
Enable regional comparison of yield performance across seasons
Support data-driven planning for crop selection, irrigation, and risk assessment


🛠️ Tech Stack
Layer
Tools Used
Cloud Storage
AWS S3
Data Warehouse
Snowflake
Access Control
IAM Roles
Data Wrangling
SQL (Snowflake), Feature Engineering
Visualization
Power BI (DAX, Power Query)
Connectivity
Power BI Live Connection to Snowflake



🏗️ Architecture
Raw Data → AWS S3 → Snowflake (via IAM) → SQL Wrangling → Power BI Dashboards

Ingestion — Raw agriculture datasets loaded into AWS S3 buckets
Integration — Snowflake connected to S3 via IAM-secured external stage
Transformation — SQL-based data wrangling, feature engineering, and categorical encoding in Snowflake
Modeling — Clean, analysis-ready data model linking climate variables to yield outcomes
Visualization — Live Power BI connection to Snowflake; 4 interactive dashboards built


📊 Dashboards
Dashboard
Key Visuals
Rainfall Analysis
Regional rainfall trends, seasonal patterns, anomaly detection
Temperature Analysis
Avg temperature by region, heat stress thresholds, YoY trends
Humidity Analysis
Humidity-yield correlation, monthly distribution
Yield Analysis
Crop output by region, climate-yield impact matrix, KPI cards


📸 Screenshot: (Add your Power BI dashboard screenshot here)


🔍 Key Insights
Regions with rainfall between 800–1200mm showed 23% higher average yield compared to lower rainfall zones
Temperature spikes above 35°C during flowering season correlated with a significant yield drop across 3 major crop types
Humidity levels above 75% during harvest months were associated with increased crop disease risk


📁 Project Structure
agriculture-climate-yield-analytics/

│

├── data/                  # Sample/raw dataset (anonymized)

├── sql/                   # Snowflake SQL scripts (wrangling, feature engineering)

├── powerbi/               # Power BI .pbix file

├── screenshots/           # Dashboard screenshots

└── README.md


💡 Business Impact
This solution enables agricultural planners to shift from manual, spreadsheet-based reporting to a real-time, self-serve analytics platform — reducing data-to-insight time and supporting proactive, climate-aware crop planning decisions.


👤 Author
Dnyaneshwar Singh MSc Computer Applications | MIT ACSC Pune LinkedIn | GitHub

