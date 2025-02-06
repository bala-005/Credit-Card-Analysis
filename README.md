#Mitron Bank Credit Card Analysis

Project Overview

Mitron Bank, a legacy financial institution headquartered in Hyderabad, is planning to launch a new line of credit cards to expand its financial market reach. AtliQ Data Services proposed implementing this project and was given a pilot dataset of 4,000 customers across five cities to analyze their spending behavior and provide actionable recommendations.

This project aims to analyze customer spending patterns, identify key customer segments, and recommend suitable credit card features to maximize adoption and engagement.

Dataset Information

The project utilizes two primary datasets:

1. dim_customers.csv (Customer Demographics)

customer_id: Unique identifier for each customer.

gender: Male or Female.

age_group: Age categories (21-24, 25-34, 35-45, 45+).

marital_status: Single or Married.

city: Cities (Mumbai, Delhi-NCR, Chennai, Hyderabad, Bengaluru).

occupation: Job type (Salaried IT Employees, Business Owners, Freelancers, etc.).

avg_income: Monthly average income in INR.

2. fact_spends.csv (Customer Spending)

customer_id: Unique identifier (links to dim_customers).

month: Month of transaction (May–October).

category: Spending category (Entertainment, Apparel, Electronics, etc.).

payment_type: Payment method (Debit Card, Credit Card, UPI, Net Banking).

spend: Total amount spent per transaction.

Key Insights & Findings

Average Income Utilization %:

The average income utilization across all customers is 257.69%, indicating strong reliance on credit and other payment methods.

Top Spending Categories:

Bills: ₹104.91M

Groceries: ₹86.30M

Electronics: ₹79.56M

Health & Wellness: ₹65.59M

Travel: ₹59.22M

Top Spending Cities:

Mumbai: ₹172.04M

Delhi NCR: ₹111.45M

Bengaluru: ₹100.02M

Chennai: ₹79.87M

Hyderabad: ₹67.52M

Payment Preferences:

Credit Card Usage is highest (₹216.31M in transactions), followed by UPI (₹140.82M).

This suggests strong demand for credit cards, with potential to integrate UPI-based credit card payments.

Dashboard Design

A Power BI dashboard was created to visually present insights, covering:

Customer Demographics (Gender, Age Group, Occupation, City-wise Distribution).

Spending Trends (Top Categories, Monthly Spending Trends, Occupation-wise Spending).

Income Utilization % (Key Metric Analysis by City & Occupation).

Payment Type Insights (Preference for Credit Cards and UPI Growth).

Credit Card Feature Recommendations based on spending behaviors.

Credit Card Feature Recommendations

🔹 Cashback on Groceries & Bills (Top spending categories).
🔹 EMI & Rewards for Electronics & Travel (Significant spend in these sectors).
🔹 Higher Credit Limits for Mumbai & Delhi NCR users (Cities with highest spending).
🔹 UPI-Linked Credit Card (To tap into the growing UPI adoption).

Business Impact & Recommendations

Targeted marketing strategies identified, focusing on high-value customer segments.

Strategies proposed to increase spending by 15% in the 25-34 age group.

Engagement strategies suggested to boost IT professional card usage by 10%.
