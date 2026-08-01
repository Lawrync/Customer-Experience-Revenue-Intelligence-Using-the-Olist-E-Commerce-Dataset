# Customer-Experience-Revenue-Intelligence-Using-the-Olist-E-Commerce-Dataset

# Overview.
This dataset is based on Brazilian e-commerce transactions. The dataset contains 100000 orders made at the Olist store from 2016 to 2018 across multiple marketplaces in Brazil. The dataset was extracted from Kaggle https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce, comprising of different CSV files. The data captures the complete customer purchasing journey, from order placement to payment, delivery, and customer reviews.

 # Business Understanding
Olist operates a multi-vendor e-commerce marketplace where business success depends on increasing revenue, maintaining customer satisfaction, supporting seller performance, and ensuring efficient order fulfillment. To remain competitive, the company needs to understand the factors driving these outcomes. This project analyzes historical e-commerce data to identify opportunities for improving sales, customer experience, logistics, and operational performance through data-driven decision-making.
# Objectives 
1. Analyze sales performance to identify revenue trends, seasonal patterns, and top-performing product categories and sellers.
2. Evaluate customer purchasing behavior to understand buying patterns, customer distribution, and repeat purchase trends.
3. Assess customer satisfaction by examining review ratings and identifying factors that influence the customer experience.
4. Measure seller performance by comparing sales, order fulfillment, and customer ratings to identify high- and low-performing sellers.
5. Evaluate delivery and logistics efficiency by analyzing delivery times, shipping costs, and regional performance to identify operational bottlenecks.
6. Analyze payment behavior to understand customer payment preferences, installment usage, and their impact on sales.
7. Provide actionable business recommendations based on the findings to support strategic decision-making, improve operational efficiency, and enhance overall business performance.
   
# Tools & Libraries
Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly

Jupyter Notebook

 # Dataset

The analysis uses the Olist Brazilian E-commerce Public Dataset available on Kaggle.

The dataset contains approximately:

100,000 Orders
99,000 Customers
112,000 Order Items
32,000 Products
3,095 Sellers
100,000 Reviews
103,000 Payment Records

The project integrates multiple relational datasets including:

Customers

Orders

Order Items

Products

Sellers

Payments

Reviews

Geolocation

Product Category Translation

# Data Cleaning

## The following preprocessing steps were performed:

Removed duplicate geolocation records.

Handled missing values using appropriate techniques.

Filled missing product categories with "Unknown".

Imputed missing numerical values using the median.

Filled missing review comments with placeholder text.

Converted date columns to datetime format.

Renamed inconsistent column names.

Merged multiple datasets into one analytical dataset.

Created new features for business analysis.

# Feature Engineering

Several new variables were created to support the analysis, including:

Purchase Year

Purchase Month

Purchase Quarter

Day of Week

Delivery Time

Shipping Time

Approval Time

Order Status Indicators

Customer Lifetime Value (CLV)

Repeat Customer Indicator

Exploratory Data Analysis

The analysis is organized into the following business-focused sections.

# 1. Sales Performance

Total Revenue

Total Orders

Products Sold

Average Order Value

Monthly Sales Trends

Seasonal Sales Analysis

Best Performing Months

Worst Performing Months

3. Customer Analysis
Customer Distribution
Top Customer States
Top Customer Cities
Repeat Purchase Rate
Customer Lifetime Value
Highest Spending Customers
4. Product Analysis
Top Selling Products
Highest Revenue Products
Most Purchased Products
Product Category Performance
Average Selling Price
Product Ratings
Freight Cost by Category
5. Seller Analysis
Number of Sellers
Highest Revenue Sellers
Top Selling Sellers
Seller Distribution
Seller Ratings
Seller Revenue by State
6. Payment Analysis
Payment Method Distribution
Revenue by Payment Method
Installment Usage
Average Payment Value
Installment Distribution
7. Delivery Performance
Average Delivery Time
Average Shipping Time
Longest Delivery States
Late Deliveries
Early Deliveries
Fastest Sellers
Delivery Performance by Category
8. Customer Review Analysis
Average Review Score
Five-Star Review Percentage
Highest Rated Categories
Lowest Rated Categories
Delivery Time vs Reviews
Price vs Reviews
Seller Ratings
9. Geographic Analysis
Revenue by State
Revenue by City
Orders by State
Seller Distribution
Customer vs Seller Locations
Regional Shipping Costs
10. Freight Analysis
Average Freight Value
Freight by Category
Weight vs Freight
Freight by State
Freight vs Order Value
11. Order Status Analysis
Delivery Success Rate
Cancellation Analysis
Order Status Distribution
Monthly Cancellation Trends
Order Approval Time
12. Correlation Analysis

Relationships between:

Product Price & Freight Cost
Delivery Time & Review Score
Payment Value & Freight Cost
Product Weight & Freight Cost
Installments & Order Value
Key Insights

Some of the major findings include:

Sales increased steadily from 2016 to 2018, with clear seasonal peaks.
Revenue is concentrated within a relatively small number of product categories.
Only 3.12% of customers are repeat buyers, indicating an opportunity to improve customer retention.
The average Customer Lifetime Value (CLV) is R$148.54.
Credit cards are the dominant payment method.
Installment payments are widely used for higher-value purchases.
Most orders are delivered successfully and often before the estimated delivery date.
Delivery delays negatively affect customer review scores.
Marketplace revenue is concentrated among a relatively small number of sellers.
Business Recommendations

Based on the findings, the following recommendations are proposed:

Develop customer loyalty programs to increase repeat purchases. 
Expand high-performing product categories.
Reward top-performing sellers through incentive programs.
Improve delivery efficiency in slower regions.
Optimize freight costs through strategic warehouse placement.
Continue supporting flexible installment payment options.
Use customer reviews to improve products and seller performance.
Expand seller coverage in underserved regions.
