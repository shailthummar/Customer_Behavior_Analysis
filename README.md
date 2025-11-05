
📊 Customer Shopping Behavior Analysis
A Data + SQL + BI Project

🧩 Overview
This project provides an end-to-end analysis of customer shopping patterns using a dataset of 3,900 purchases and 18 features. The goal is to uncover insights related to spending behavior, product performance, subscription value, customer segmentation, and revenue drivers.
The workflow integrates Python, PostgreSQL SQL queries, and an interactive dashboard (Tableau/Power BI) to produce actionable business recommendations.
 
✅ Project Components

1️⃣ Python Data Preparation & Exploratory Analysis
Performed in a Jupyter Notebook (customer_shopping_behavior_analysis.ipynb) using pandas, numpy, and matplotlib.

Key steps included:
  •	Data loading and exploration using df.info() and df.describe()
  •	Standardizing column names to snake_case
  •	Handling missing values (imputed median review ratings per category)
  •	Feature engineering:
  o	age_group buckets
  o	purchase_frequency_days
  •	Dropping redundant columns (promo_code_used)
  •	Exporting cleaned data to PostgreSQL for SQL-based analytics
 
2️⃣ SQL Business Analysis (PostgreSQL)
SQL queries were created to answer critical business questions using the customer table.

Insights extracted:
  •	Revenue by gender
  •	High-value discount users (spent above average even with discounts)
  •	Top-rated products
  •	Shipping type comparison (Standard vs Express)
  •	Subscriber vs Non-subscriber spending patterns
  •	Products with highest discount dependency
  •	Customer segmentation (New, Returning, Loyal)
  •	Top 3 products per category
  •	Subscription likelihood among frequent buyers
  •	Revenue contribution per age group
   
3️⃣ Interactive Dashboard
A BI dashboard was built to visualize the insights extracted from Python and SQL.

Includes interactive visuals for:
•	Revenue trends
•	Demographic breakdowns
•	Category & product performance
•	Subscription impact analysis
•	Customer segment distributions


🧠 Key Business Findings
  •	Subscribers spend more and contribute higher revenue overall.
  •	Repeat buyers show higher likelihood of subscribing.
  •	Top-rated products align strongly with high purchase frequency.
  •	Express shipping users demonstrate higher average spend.
  •	Younger to mid-aged groups contribute the majority of revenue.
  •	Certain products rely heavily on discount-driven purchases, requiring margin management.
   
🚀 Recommendations
  •	Strengthen loyalty programs to shift “Returning” users into the “Loyal” tier.
  •	Promote subscription-only perks to boost long-term value.
  •	Optimize discount strategy for high-discount-dependent products.
  •	Prioritize marketing budgets toward high-revenue age groups & express shippers.
  •	Highlight top-rated products in advertising & merchandising.
   
🛠️ Tech Stack
  Languages: Python, SQL
  Libraries: pandas, numpy, psycopg2
  Database: PostgreSQL
  BI Tools: Power BI 
  Environment: Jupyter Notebook, VS Code



 

