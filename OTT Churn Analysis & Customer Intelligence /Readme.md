
📉 Customer Churn Analysis
An end-to-end Python-based churn analysis project — connecting a SQL database, performing EDA, feature engineering, and delivering business-ready insights via Matplotlib and Seaborn visualizations, with key findings presented on a stakeholder-ready PowerPoint summary.


📌 Problem Statement
Customer churn is one of the most costly challenges for subscription-based and service businesses. Acquiring a new customer costs 5–7x more than retaining an existing one. Despite this, many businesses lack the analytical capability to identify at-risk customers before they leave. This project analyzes customer behavior data to uncover churn patterns and surface actionable retention insights.


🎯 Business Objective
Identify the key drivers of customer churn using exploratory data analysis
Segment customers by churn risk based on behavioral and demographic patterns
Deliver clear, actionable insights that a retention team can act on


🛠️ Tech Stack
Layer
Tools Used
Database
SQLite (via sqlite3)
Data Import
SQL queries executed in Python
Data Cleaning
Pandas, NumPy
Feature Engineering
Pandas, NumPy
Exploratory Analysis
Pandas (groupby, pivot tables, aggregations)
Visualization
Matplotlib, Seaborn
Reporting
PowerPoint (key insights summary)
Environment
Jupyter Notebook



🏗️ Project Workflow
SQLite Database → Python (sqlite3) → Data Cleaning → Feature Engineering → EDA → Visualizations → Insights (PPT)

Data Import — Connected SQLite database to Python using sqlite3; imported data via SQL queries directly into Pandas DataFrames
Data Cleaning — Handled missing/null values, fixed data types, renamed columns, removed duplicates, and performed quality checks
Feature Engineering — Created calculated columns (e.g., tenure buckets, usage ratios), applied data transformations and filters using NumPy and Pandas
EDA — Performed aggregation, group-by analysis, and pivot tables to surface churn patterns across customer segments
Visualization — Built charts using Matplotlib and Seaborn to communicate findings visually
Insights — Summarized key findings, next steps, and business impact on a PowerPoint presentation


📊 Analysis & Visualizations
Analysis
Visual Type
Business Question
Overall churn rate
Bar chart
What % of customers churned?
Churn by contract type
Grouped bar chart
Do month-to-month contracts churn more?
Churn by tenure
Histogram / KDE plot
When are customers most likely to leave?
Churn by payment method
Pie / bar chart
Does payment method affect churn?
Churn by monthly charges
Box plot
Do high-spend customers churn more?
Correlation heatmap
Seaborn heatmap
Which features correlate with churn?
Customer segment profile
Pivot table + bar
Who is the highest-risk customer segment?


📸 Screenshot: (Add your visualization screenshots here)


🔍 Key Insights
(Update these with your actual findings once the project is complete)

Customers on month-to-month contracts churned at X% — significantly higher than annual contract customers
The highest churn risk segment: tenure < 12 months + high monthly charges + electronic check payment
Top 3 churn drivers identified: contract type, tenure, and monthly charge level
Customers who churned had X% higher average monthly charges than retained customers


📋 How to Run
# 1. Clone the repository

git clone https://github.com/Dnyan-droid/customer-churn-analysis.git

# 2. Install dependencies

pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch Jupyter Notebook

jupyter notebook notebooks/churn_analysis.ipynb


💡 Business Impact
This analysis enables retention teams to move from reactive to proactive churn management — identifying high-risk customer segments before they leave and prioritizing targeted interventions (discounts, contract upgrades, outreach) based on data-driven risk profiles rather than guesswork.


👤 Author
Dnyaneshwar Singh MSc Computer Applications | MIT ACSC Pune LinkedIn | GitHub

