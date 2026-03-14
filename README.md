# customer_shopping_analysis
Customer Shopping Behavior Analysis
One-Line Summary

Analyzing retail customer purchasing behavior using Python, SQL, and Power BI to identify patterns that drive sales, customer loyalty, and business growth.

Project Overview

Retail companies generate large volumes of transactional data, but understanding customer behavior from this data is essential for improving sales performance and customer satisfaction.

This project analyzes customer shopping behavior to uncover insights related to demographics, purchasing patterns, discounts, product categories, and subscription status. The insights help businesses make data-driven decisions related to marketing strategies, pricing, and customer retention.

Problem Statement

Retail management wants to better understand customer purchasing patterns to improve revenue and customer loyalty. Key business questions include:

Which customer groups generate the most revenue?

Do discounts significantly influence purchasing behavior?

Which products receive the highest ratings?

Are subscription users spending more than non-subscribers?

Which demographics contribute the most to total revenue?

By analyzing these factors, the company can design targeted marketing strategies and improve product positioning.

Dataset

The dataset contains customer transaction and behavioral data.

Dataset Characteristics

Total Rows: 3,900

Total Columns: 18

Key Features

Customer Demographics

Age

Gender

Location

Subscription Status

Purchase Information

Item Purchased

Category

Purchase Amount

Season

Size

Color

Shopping Behavior

Discount Applied

Promo Code Used

Previous Purchases

Purchase Frequency

Review Rating

Shipping Type

Some missing values were identified in the Review Rating column and handled during data cleaning.

Tools and Technologies
Tool	Purpose
Python	Data cleaning, preprocessing, and feature engineering
Pandas	Data manipulation and analysis
PostgreSQL	SQL-based data analysis
SQL	Business query analysis
Power BI	Data visualization and dashboard creation
Methods
1. Data Cleaning (Python)

Loaded dataset using Pandas

Checked structure using .info() and .describe()

Handled missing values in Review Rating

Standardized column names

Performed feature engineering:

Created age_group

Generated purchase_frequency_days

2. Data Integration

Connected Python with PostgreSQL

Loaded cleaned dataset into database

3. SQL Analysis

Performed business-driven analysis such as:

Revenue by gender

High-spending discount users

Top-rated products

Shipping type spending comparison

Subscribers vs non-subscribers revenue

Customer segmentation

Repeat buyer analysis

Revenue by age group

4. Data Visualization

Built an interactive Power BI dashboard to present insights clearly and support decision-making.

Key Insights

Certain age groups contribute significantly to total revenue

Subscribers tend to spend more than non-subscribers

Some products rely heavily on discounts to drive purchases

Top-rated products are strong candidates for marketing campaigns

Express shipping users tend to have higher purchase amounts

Repeat buyers are more likely to become loyal customers

How to Run This Project
1. Clone Repository
git clone https://github.com/yourusername/customer-shopping-analysis.git
2. Install Required Libraries
pip install pandas numpy psycopg2
3. Run Python Data Cleaning Script
python data_cleaning.py
4. Load Data into PostgreSQL

Run the SQL scripts inside the /sql folder.

5. Open Power BI Dashboard

Open the .pbix file in Power BI Desktop to explore interactive visualizations.

Results and Conclusion

This project demonstrates how data analytics can transform raw retail data into actionable business insights.

By combining Python for data preparation, SQL for analytical queries, and Power BI for visualization, the project identifies key factors influencing customer purchases and revenue generation.

The findings help businesses:

Optimize marketing strategies

Improve customer retention

Promote high-performing products

Enhance subscription programs

Future Work

Possible improvements for this project include:

Building predictive models for customer purchase prediction

Implementing customer churn analysis

Creating customer lifetime value (CLV) models

Deploying the dashboard as a real-time analytics tool

Adding machine learning-based customer segmentation
