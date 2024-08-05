# Project title: Interactive Sales Dashboard for Superstore Using Excel

# Table of content
- Introduction
- Objective
- Tools and Technologies
- Data Analysis 
- Analysis and Visualizations
- Project Insights

# Introduction:
The Superstore Sales Data Analysis project involves analyzing a comprehensive dataset from a retail superstore. This dataset includes information on orders, customer demographics, product categories, shipment details, and sales channels. 

# Objective:
The primary objective of the Superstore Sales Data Analysis project is to derive actionable insights from the superstore's sales data using Excel's powerful data analysis and visualization tools to understand sales performance, customer behavior, and product distribution.

# Tools and Technologies
- Excel
- Pivot table

# Data Analysis:
Data Import and Cleaning:

1. Import the dataset into Excel.
  - Clean the data by removing any duplicates and handling missing values.
  - Ensure all data fields are correctly formatted, especially dates and numerical values.

2. Data processing
  - Adding 'Age Group' Column: To understand the purchasing behavior across different age segments, we created an 'Age Group' column.
    ```
    =IF(Age>=50,"Senior",IF(Age>=30,"Adult","Teenager"))
    ```
  - Adding 'Month' Column: To analyze the sales data on a monthly basis, we extracted the month from the 'Date' column. This helps in identifying seasonal trends and monthly sales    
    performance.
    ```
    =TEXT(Date, "mmmm")
    ```
3. Creating Pivot Tables:
   - Create pivot tables to summarize data for different analysis requirements.
   - Use pivot tables to analyze sales performance, order distribution, and customer demographics.

# Data Analysis and Visualization 
![Superstore Analysis](https://github.com/prajaktakadu11/Interactive_Sales_Dashboard_for_Superstore_Using_Excel/blob/main/Superstore%20analysis.PNG?raw=true)

# Project Insights and Finding 
- Sales Performance:
  The combo chart revealed the monthly sales trends and the corresponding count of orders.<br>
  The analysis showed peak sales in march month.

- Gender-Based Sales Comparison:
  Analyze the sales distribution between male and female customers to understand gender-based purchasing behavior.<br>
  Women are more likely to buy compared to men (~ 65%).

- Regional Sales Analysis:
  Determine the top-performing states in terms of sales to focus marketing efforts and optimize inventory management.
  Maharashtra, Karnataka and Uttar Pradesh are the top 3 performing states in terms of sales.

- Channel Performance Evaluation:
  Compare the performance of various sales channels to identify the most popular and least popular channels.<br>
  Amazon, Flipkart, and Myntra channels are maximum contributing in sales(~ 80%).

  Target Women customers of age group (30-49)yrs living in Maharashtra, Karnataka and Uttar pradesh by showing ads/offers/coupons available on Amazon, Flipkart and Myntra.

