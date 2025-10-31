Customer_Shopping_Behavior_Analysis/
│
├── data/                  # Raw and cleaned datasets
├── notebooks/             # Python EDA notebooks
├── sql_queries/           # SQL scripts for business questions
├── powerbi_dashboard/     # Power BI .pbix file
├── reports/               # Summary reports / insights
└── README.md              # Project documentation
🛍️ Customer Shopping Behavior Analysis
📄 Overview

This project explores customer purchasing patterns and spending behavior using transactional data from 3,900+ purchases across various product categories. The goal is to uncover insights that help improve customer retention, marketing strategy, and revenue optimization.

🎯 Business Objective

To analyze how demographic and behavioral factors (like gender, age, subscription, and discounts) influence purchase decisions and revenue, and to present actionable insights through an interactive Power BI dashboard.

⚙️ Project Workflow

1. Data Exploration (Python)

Loaded and cleaned raw CSV data using Pandas and NumPy.

Handled missing values and standardized columns for consistency.

Engineered new features such as age_group and purchase_frequency_days.

2. SQL Analysis (PostgreSQL)

Wrote 10+ analytical SQL queries to extract insights:

Revenue by Gender & Age Group

Discount Effectiveness

Subscription vs Non-Subscription Spend

Top Products by Rating

Customer Segmentation (New, Returning, Loyal)

Applied CTEs and window functions for advanced KPI calculations.

3. Power BI Dashboard

Connected PostgreSQL database to Power BI for live data visualization.

Created DAX measures for KPIs: Average Revenue, Discount Rate, Total Orders, Customer Loyalty Index.

Built interactive visuals with filters for category, age group, and shipping type.

📊 Key Insights

Subscribers spent ~25% more than non-subscribers.

Loyal customers contributed the majority of total revenue.

Discounts increased short-term sales but had limited long-term ROI.

Age group 25–40 generated the highest overall revenue.

🚀 Business Impact

The dashboard enabled stakeholders to make data-driven decisions in pricing, discount strategy, and customer retention programs, improving visibility across sales and engagement performance metrics.

🧰 Tech Stack

Languages: Python, SQL

Libraries: Pandas, NumPy, Matplotlib

Database: PostgreSQL

Visualization: Power BI

Tools: Excel, DAX
