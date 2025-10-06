# 🏦 Bank Customer Churn Analysis Dashboard
<img width="3275" height="1845" alt="image" src="https://github.com/user-attachments/assets/641080d3-e2be-4710-ac8d-cdbcd9c3f7a0" />

## Project Overview
This repository contains the files and documentation for a comprehensive Bank Customer Churn Analysis dashboard built using Power BI. The goal of this project is to analyze the underlying factors that contribute to customer attrition (churn) in a banking institution. By visualizing key metrics and demographic data, we can identify patterns, segment high-risk customers, and provide actionable insights to improve customer retention strategies.

Key Objective: To understand who is leaving the bank, why they are leaving, and what the bank can do to minimize future churn.

## 📊 Dashboard Preview

The dashboard is designed to be highly interactive, allowing users to slice and dice the data based on various dimensions like Country, Gender, and Credit Score.

Key Features and Visualizations
The dashboard focuses on several key areas of analysis:

### 1. High-Level Metrics
Total Customers: The overall count of customers in the dataset.

Customers Left (Churned): The total count of customers who have churned.

Overall Churn Rate: The percentage of customers who have churned, displayed prominently in a donut chart.

### 2. Demographic Analysis
Customers by Gender: Breakdown of churn and population by male and female customers.

Customers by Country: Analysis of churn rates across different geographical locations (country).

### 3. Account and Activity Analysis
Customers by Activity Status: Comparison between active_member and non-active members.

Customers by Credit Card Status: Breakdown of customers who own a credit card (credit_card = 1) versus those who do not.

Customers by Products Number: Visualization of churn based on the number of bank products (products_number) a customer holds.

### 4. Deep Dive Churn Drivers (Line & Bar Charts)
Churn Rate by Age Group: Identifying which age cohorts are most prone to leaving the bank.

Churn Rate by Credit Group: Analyzing how credit_score impacts the likelihood of churning.

Churn Rate by Account Balance: Investigating the relationship between the customer's balance and attrition.

### 💾 Data Source and Schema
The analysis is based on a single dataset containing customer demographic, account, and behavioral information, it is taken from Kaggle datasets.

## 🛠️ Tools and Technologies
1. Primary Tool: Microsoft Power BI Desktop
2. Data Modeling: Star Schema
3. Data Cleaning and Transformation : Power Query Editor
4. Analysis: Data Analysis Expressions (DAX) for calculating custom measures like Churn Rate, and various count metrics.

## 💡 Key Insights (Inferred/Expected)

Based on typical banking data and the visualizations present, the analysis is likely to reveal insights such as:
1. <u>Age Group Risk</u> : Customers in a specific age range (e.g., 40-60) may exhibit the highest churn rates, possibly due to retirement or seeking better rates elsewhere.
2. <u>Balance Dependency</u> : Customers with either very low (near zero) or extremely high balances might show differing churn patterns.
3. <u>Inactivity Penalty</u>: Customers marked as "Not Active Members" are significantly more likely to churn.
4. <u>Product Stickiness</u>: There may be a sweet spot for the number of products—customers with only 1 product are high-risk, while those with 3 or 4 products might be restricted from churn due to internal bank rules, or are simply already satisfied.

## 🚀 How to Use
To explore the interactive dashboard:

1. Clone the Repository:

git clone https://github.com/srishtirastogiwork23/Bank-Customer-Churn-Analysis.git

2. Install Power BI Desktop: Ensure you have Power BI Desktop installed on your machine.

3. Open the File: Navigate to the cloned folder and open the Bank_Churn_Analysis_Dashboard.pbix file (or similar named file).

4. Interact: The dashboard will open in Power BI Desktop. Use the filters (Country, Gender, etc.) and visual interactions to explore the data and derive your own conclusions.
