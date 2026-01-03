# retail-sales-performance-analysis
End-to-end data analysis of retail sales data using Python, SQL, and Tableau, KPIs, and applicable business insights.
Istanbul Retail Malls Sales Analysis
Project Overview
This project analyzes retail transaction data from multiple shopping malls in Istanbul, Turky to uncover revenue drivers, customer spending behaviors, and category dependence. The objective is to transform raw transactional data into business insights using Python for analysis and Tableau for visualization.
Business Questions
This analysis focuses on answering the following questions:
1.	Which shopping malls generate the highest total revenue?
2.	Which product categories sell the most units and generate the most revenue?
3.	How concentrated is revenue among top spending customers?
4.	What is the relationship between sales quantity and revenue across categories?
5.	Are specific shopping malls overly dependent on particular product categories?

Dataset Description

The dataset contains transactional shopping records with the following fields:

•	customer_id – Unique customer identifier

•	shopping_mall – Shopping mall where the purchase occurred

•	category – Product category

•	quantity – Number of items purchased

•	price – Transaction valuex
Each row represents a single transaction.

Tools & Technologies

•	Python

o	pandas (data manipulation)

o	matplotlib (exploratory visualization)

•	Tableau

o	Interactive dashboards

o	KPI design

o	Revenue concentration analysis

Methodology

1. Data Preparation (Python)

•	Cleaned and validated transactional data

•	Aggregated revenue and quantity metrics by mall, category, and customer

•	Created derived metrics such as:

o	Revenue share by mall

o	Revenue share by category

o	Customer spending concentration

2. Exploratory Data Analysis (Python)

•	Identified top-performing malls and categories

•	Analyzed revenue vs quantity dynamics

•	Ranked customers by spending to evaluate concentration

3. Visualization & Dashboarding (Tableau)

•	Designed executive-level KPIs

•	Built interactive charts to explain revenue drivers

•	Applied filters for category and mall-level analysis

Key Metrics (KPIs)

•	Total Revenue

•	Revenue from Top Mall (%)

•	Revenue from Top Category (%)

•	Revenue from Top 20% of Customers (%)

Key Insights

•	The top shopping mall contributes approximately 20% of total revenue, indicating moderate location-based concentration.

•	The clothing category accounts for over 40% of total revenue, suggesting strong pricing power relative to volume.

•	The top 20% of customers generate about 26% of total revenue, showing partial customer concentration but not extreme dependency.

•	Categories with high quantity do not always correspond to high revenue, emphasizing the importance of unit pricing.

•	All malls show a similar pattern, with their top-performing category accounting for approximately 45–48% of total revenue, indicating moderate category 
dependence.

Business Implications

•	Mall operators can prioritize marketing and expansion strategies around high-performing locations.

•	Product managers may explore premium pricing strategies in dominant categories.

•	Customer retention programs can target high-value customers without over-reliance on a small group.








