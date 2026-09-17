🛒 E-Commerce Sales Analytics
📌 Project Overview

This project focuses on analyzing e-commerce retail sales data to understand sales performance, customer behavior, product performance, and revenue trends.

The project follows an end-to-end data analytics workflow using Microsoft Excel, MySQL, SQL, and Power BI to transform raw sales data into meaningful business insights.

🎯 Project Objectives
Analyze overall sales performance
Identify high-performing product categories
Analyze customer purchasing behavior
Compare revenue by gender
Analyze revenue across different age groups
Identify top customers based on spending
Analyze monthly and yearly revenue trends
Analyze quantity sold by product category
Build an interactive Power BI dashboard
Generate business insights and recommendations
🛠️ Tools & Technologies
Tool	Purpose
Microsoft Excel	Data cleaning and preparation
MySQL	Data storage
SQL	Data analysis
Power BI	Data visualization and dashboard
GitHub	Project documentation and portfolio

📊 Dataset

The dataset contains 1,000 retail sales transactions.
Main Columns
Transaction ID
Date
Customer ID
Gender
Age
Product Category
Quantity
Price per Unit
Total Amount
Product Categories
Beauty
Clothing
Electronics

🧹 Data Cleaning
The dataset was cleaned and prepared using Microsoft Excel.
The cleaning process included:
Checking for missing values
Checking for duplicate records
Validating data types
Validating transaction amounts
Verifying total amount calculations
Creating Year and Month fields
Creating Age Groups

The cleaned dataset contains:
1,000 transactions
No missing values
No duplicate rows

The Total Amount column was validated using:
Total Amount = Quantity × Price per Unit

🗄️ SQL Analysis
The cleaned data was imported into MySQL for analysis.
SQL analysis included:

Total revenue
Total transactions
Average transaction value
Total quantity sold
Revenue by product category
Revenue by gender
Revenue by year and month
Quantity sold by category
Average price per unit
Highest revenue transaction
Top customers by spending
Revenue by age group
Customer spending analysis
Customer ranking
Product category analysis

Advanced SQL concepts used:
GROUP BY
HAVING
CASE
Subqueries
CTEs
Window Functions
ROW_NUMBER()
DISTINCT
Example SQL Query
SELECT
    product_category,
    SUM(total_amount) AS total_revenue
FROM sales
GROUP BY product_category
ORDER BY total_revenue DESC;

📈 Power BI Dashboard
The analyzed data was visualized using Microsoft Power BI.
Dashboard Pages
Home Page
Sales Analysis
Transaction Analysis
Product Analysis
Revenue Analysis
Business Insights
Dashboard Features
KPI cards
Revenue analysis
Transaction analysis
Product category analysis
Customer analysis
Gender analysis
Age-group analysis
Monthly and yearly trends
Interactive slicers and filters
Business insights and recommendations

🔑 Key Metrics
Metric	Value
Total Revenue	$456,000
Total Transactions	1,000
Total Quantity Sold	2,514
Average Transaction Value	$456
Product Categories	3

🔍 Key Insights

Product Performance
Electronics generated the highest total revenue among the three product categories.

Quantity Sold
Clothing recorded the highest total quantity sold.

Gender Analysis
Female customers generated higher total revenue than male customers.

Yearly Revenue
Most of the dataset's revenue was generated in 2023, while 2024 contains considerably fewer transactions.

Customer Analysis
Customer-level analysis was performed to identify high-spending customers and rank customers based on their spending.

Age Group Analysis
Revenue was analyzed across the following age groups:
18–25
26–35
36–45
46–55
56–64

💡 Business Recommendations
Based on the analysis:
Monitor high-performing product categories and maintain product availability.
Analyze customer purchasing behavior to identify opportunities for targeted promotions.
Use age-group analysis to understand different customer segments.
Monitor monthly revenue trends to identify high-performing periods.
Use customer spending analysis to identify valuable customer segments.

🚀 Project Workflow

Raw Dataset
     ↓
Excel Data Cleaning
     ↓
MySQL Database
     ↓
SQL Analysis
     ↓
Power BI Visualization
     ↓
Business Insights
     ↓
Recommendations

📚 Skills Demonstrated
Data Cleaning
Data Preparation
Excel
SQL
MySQL
Data Aggregation
Subqueries
CASE Statements
CTEs
Window Functions
Customer Analysis
Sales Analysis
Data Visualization
Power BI
Dashboard Development
Business Insights

👨‍💻 Author
Izaan Shaikh
BCS Student | Aspiring Data Analyst / Data Scientist

⭐ Project Status
Completed
