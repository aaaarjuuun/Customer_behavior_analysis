# Customer_behavior_analysis
Data Analytics project showcasing customer behavior analysis using python, sql  and power BI

🛍️ Customer Shopping Behavior Analysis
📌 Overview

This project analyzes 3,900 customer purchase transactions to uncover insights into shopping behavior, revenue trends, product performance, and subscription impact.

The workflow combines Python (EDA & Cleaning), PostgreSQL (SQL Analysis), Power BI (Dashboarding), and reporting tools to simulate a real-world end-to-end data analytics pipeline.

The objective is to support data-driven business decisions through structured analysis and visualization.

📊 Dataset

Total Records: 3,900

Total Columns: 18

Key Features:

Customer demographics (Age, Gender, Location, Subscription Status)

Purchase details (Item, Category, Amount, Season, Size, Color)

Behavior metrics (Discount Applied, Previous Purchases, Review Rating, Shipping Type)

Data Cleaning

37 missing values in review_rating handled using median imputation by category

Column names standardized to snake_case

Removed redundant column (promo_code_used)

Created new features:

age_group

purchase_frequency_days

🛠️ Tools & Technologies

Python – Pandas, NumPy (EDA & Data Cleaning)

PostgreSQL – Business query analysis

Power BI – Interactive dashboard

MySQL/SQL Server (optional compatibility)

Gamma – Presentation (PPT) creation

⚙️ Project Workflow
1️⃣ Data Loading & Cleaning (Python)

Imported dataset using pandas

Used .info() and .describe() for structural inspection

Handled missing values

Performed feature engineering

Exported cleaned dataset to PostgreSQL

2️⃣ Business Analysis (SQL)

Key business queries included:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Rating

Shipping Type Comparison

Subscribers vs Non-Subscribers Revenue

Discount-Dependent Products

Customer Segmentation (New / Returning / Loyal)

Top 3 Products per Category

Repeat Buyers vs Subscription Correlation

Revenue by Age Group

📈 Power BI Dashboard

An interactive dashboard was created to visualize:

Revenue distribution

Customer segments

Age group contribution

Shipping preference impact

Subscription revenue comparison

Top-performing products

The dashboard enables business stakeholders to quickly interpret trends and KPIs.

📊 Key Results

Subscribers generated higher average revenue than non-subscribers

Loyal customers contribute significantly to total revenue

Certain products are highly discount-dependent

Express shipping customers tend to spend more

Specific age groups dominate revenue contribution

💡 Business Recommendations

Introduce stronger loyalty programs

Promote subscription benefits

Optimize discount strategy

Highlight top-rated products in marketing campaigns

Focus marketing efforts on high-revenue segments

▶️ How to Run
1. Clone Repository
git clone <your-repo-link>
cd customer-shopping-analysis
2. Install Dependencies
pip install pandas numpy psycopg2
3. Run Python Script
python data_cleaning.py
4. Load into PostgreSQL

Create database

Run provided SQL schema file

Execute analysis queries

5. Open Power BI

Load exported dataset or connect to PostgreSQL

Open .pbix dashboard file

📂 Project Structure
customer-shopping-analysis/
│
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── report/
├── presentation/
└── README.md
🎯 Project Type

End-to-End Data Analytics | Business Intelligence | SQL + Python Integration
