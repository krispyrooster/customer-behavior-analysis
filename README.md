Customer Shopping Behavior Analysis

Overview
This project demonstrates an end-to-end data analytics workflow focused on understanding customer shopping behavior and generating actionable business insights. The analysis covers data loading, exploratory data analysis (EDA), data cleaning, SQL-based querying, and interactive visualization using Power BI. Final insights are summarized in a business report and presentation.

The goal of the project is to showcase practical skills in Python, SQL, and Business Intelligence, while translating data findings into clear, business-oriented recommendations.

Dataset
Records: 3,900 rows
Features: 18 columns
Key Data Areas:
Customer Demographics (Age, Gender, Location)
Purchase Details (Item, Category, Amount, Season, Size, Color)
Shopping Behavior (Discounts, Purchase Frequency, Review Ratings, Shipping Type)
Missing values in the review rating column were handled during data cleaning.

Tools & Technologies
Python: Pandas, NumPy (Data loading, EDA, data cleaning, feature engineering)
SQL: PostgreSQL / MySQL / SQL Server (KPI calculations, business queries)
Power BI: Interactive dashboard and visual analytics
Gamma: Business presentation (PPT)
Jupyter Notebook / VS Code: Development environment

Project Steps
Load dataset in Python using Pandas
Perform exploratory data analysis (EDA)
Clean data (handle missing values, standardize columns, remove redundancy)
Feature engineering (age groups, purchase frequency mapping)
Load cleaned data into SQL database
Run SQL queries to calculate KPIs and analyze trends
Build an interactive Power BI dashboard
Create a business report and presentation (Gamma)

Dashboard
The Power BI dashboard provides:
Revenue and KPI tracking
Customer segmentation analysis
Product and category performance
Discount and shipping behavior insights
The dashboard is designed for non-technical stakeholders and supports data-driven decision-making.

Results & Insights
Revenue is driven primarily by loyal and high-frequency customers
Subscription adoption is low among repeat buyers
Clothing and Accessories are top-performing categories
Discounts increase average order value
Shipping reliability impacts customer satisfaction
Seasonal and regional demand patterns are significant

How to Run
Clone this repository
Open the Python notebook and install required libraries
Run data cleaning and feature engineering scripts
Load the cleaned dataset into your SQL database
Execute SQL queries provided in the /sql folder
Open the Power BI file to explore the dashboard
