# LITA-CAPSTONE-PROJECT-2

### Introduction
In today's competitive landscape, understanding customer behavior is crucial for businesses to thrive. By analyzing customer data, we can identify trends, segment customers, and make data-driven decisions to optimize growth and retention.
### Project Overview
This project aims to analyze customer data for a subscription service to gain valuable insights into customer behavior, subscription patterns, and cancellation trends. By leveraging data visualization techniques and statistical analysis, we will identify key segments, track subscription types, and uncover opportunities for improvement.
### Problem Statement
As a data analyst for this subscription service, we are tasked with understanding the factors influencing customer behavior and identifying areas for growth. We aim to answer the following questions stated in Exploratory Data Analysis.

### Exploratory Data Analysis
How does revenue vary across different regions and subscription types?
What is the distribution of customers across different subscription types?
What is the cancellation rate for different subscription types?
How does revenue correlate with customer retention?

### Data Sources
---
CustomerData.xlsx is the primary source of data used. This is an open source dataset, given for the final capstone project
In the process of the analysis  metrics were added to the dataset using formula which added a column to the dataset given to solve problem they are:
1. Average Subscription Duratio

### Tools Used
---
- Microsoft Excel  [Download
   - [Download Here](https://Microsoft.com)
1. For Data cleaning
2. Use pivot tables to summarize total sales by product, region, and month.
3. Use Excel formulas to calculate metrics such as average sales per product and 
   total Sales
5. SQL Server For Analysis
6. Power BI For Visualization
7. For Creating reports
- GitHub for Portfolio Building
- 

### Data Cleaning and Preparations
---

In the early stage of cleaning and preparation of data,the following actions were performed:

- Loading/importing of data into excel and SQL Server
- Data Cleaning (Removing Duplicate data) and formatting of data.


### Data Analysis/Visualization
---
To solve the problem statement, simple visualizations that summarised the data using excel  SQL Server. Visualization using Power BI.

###  Revenue by Region and Subscription Type

![image](https://github.com/user-attachments/assets/6085d7d1-9f7a-4bac-b359-08dd4701b4ae)

The East region seems to be the top-performing region, generating the highest revenue, 16,958,763k.  The "Basic" subscription type appears to be the most popular, contributing significantly to the overall revenue. 

### CustomerID and Subscription Type

![image](https://github.com/user-attachments/assets/2603d42b-57b8-41c7-b2bf-ce66cfb14112)
 The "Basic" subscription type has the largest customer base with the value of 16,921k

### Cancellation Rate by Subscription Type

![image](https://github.com/user-attachments/assets/c9d79b3a-c4f5-46ed-834f-27eebca62dd8)
 The "Premium" and "Standard" subscription types have significantly higher cancellation rates compared to the "Basic" type with the value  60%,60%, and 29.9%.

Note: How cancellation rate was generated:
Using the given data, we can calculate the cancellation rate for each subscription type as follows:
Basic:
 * Total Basic Customers: 11,854 + 5,067 = 16,921
 * Cancellation Rate: (5,067 / 16,921) * 100% ≈ 29.9%
Premium:
 * Total Premium Customers: 3,382 + 5,064 = 8,446
 * Cancellation Rate: (5,064 / 8,446) * 100% ≈ 60%
Standard:
 * Total Standard Customers: 3,376 + 5,044 = 8,420
 * Cancellation Rate: (5,044 / 8,420) * 100% ≈ 60%

### Revenue by Customer Retention

![image](https://github.com/user-attachments/assets/2099181c-e682-45cf-8c2c-1f690fa5828d)
There appears to be a positive correlation between revenue and customer retention. Customer(Liam with the value 3,437,444k
), who generate higher revenue tend to be more loyal.
 

### Recommendations 
1. Focus on the East region and ensure that the "Basic" plan offers sufficient value to customers while maintaining profitability.
2. Consider cross-selling or upselling to premium plans to increase revenue.
3. Implement strategies to enhance customer satisfaction and reduce churn for these plans, Review the pricing and value proposition of these
   plans to ensure they meet customer expectations and Implement targeted retention campaigns for customers in these segments.
4. Prioritize high-value customers and provide tailored offers and discounts to retain valuable customers.


