# Monday Coffee Sales Data Analysis For Expantion



## Project Overview
This project aims to analyze the online sales data of **Monday Coffee**, a company that has been selling its products online since January 2023. The primary objective is to recommend the top three major cities in India for opening new coffee shop locations based on consumer demand and sales performance.

## Goals and Objectives
1. Analyze historical sales data to identify key trends and patterns.
2. Evaluate consumer demand across major cities in India.
3. Recommend the top three cities for new coffee shop locations based on:
   - Sales performance.
   - Market potential.

## Tools and Technologies
- **SQL**: The core technology used for data manipulation, analysis, and querying.
- **Database Management System (DBMS)**: A relational database such as PostgreSQL.
- **Spreadsheet Tools**: For initial data cleaning and exploration (MS Excel).
  
## Dataset Description
The dataset includes:
- **Order Details**:
  - Order IDs, dates, and customer information.
  - Product details such as items, quantity, and price.
- **Geographic Data**:
  - Customer location (city, state).
  - Shipping and delivery details.
- **Sales Metrics**:
  - Revenue, quantity sold, and discounts applied.

## Key Features
1. **Data Cleaning and Preparation**:
   - Imported raw sales data into a relational database.
   - Cleaned and preprocessed the data to ensure consistency and accuracy.
   - Created normalized tables to reduce redundancy.
   
2. **SQL Analysis**:
   - Conducted SQL queries to extract key insights:
     - City-wise sales performance.
     - Best-selling products and customer preferences.
     - Monthly and quarterly sales trends.
   - Used window functions, joins, and aggregations for advanced analysis.

3. **Recommendation Framework**:
   - Analyzed city-wise performance metrics.
   - Ranked cities based on total revenue, order frequency, and average order value.
   - Recommended the top three cities for opening new locations.

## Analysis Based on The Key Questions
1. Coffee Consumers Count

How many people in each city are estimated to consume coffee, given that 25% of the population does?

2. Total Revenue from Coffee Sales

What is the total revenue generated from coffee sales across all cities in the last quarter of 2023?

3. Sales Count for Each Product

How many units of each coffee product have been sold?

4. Average Sales Amount per City

What is the average sales amount per customer in each city?

5.City Population and Coffee Consumers

Provide a list of cities along with their populations and estimated coffee consumers.

6.Top Selling Products by City

What are the top 3 selling products in each city based on sales volume?

7. Customer Segmentation by City

How many unique customers are there in each city who have purchased coffee products?

8. Average Sale vs Rent

Find each city and their average sale per customer and avg rent per customer

9. Monthly Sales Growth

Sales growth rate: Calculate the percentage growth (or decline) in sales over different time periods (monthly).

10. Market Potential Analysis

Identify top 3 city based on highest sales, return city name, total sale, total rent, total customers, estimated coffee consumer

## Recommendations
After analyzing the data, the recommended top three cities for new store openings are:

**City 1: Pune**

- Average rent per customer is very low.
- Highest total revenue.
- Average sales per customer is also high.

**City 2: Delhi**

- Highest estimated coffee consumers at 7.7 million.
- Highest total number of customers, which is 68.
- Average rent per customer is 330 (still under 500).

**City 3: Jaipur**

- Highest number of customers, which is 69.
- Average rent per customer is very low at 156.
- Average sales per customer is better at 11.6k.



##  Set Up the Database:
Import the raw sales data into your DBMS.
Execute the `normalized_data.sql` script to create normalized tables.

## Insights and Highlights
- Identified the top-performing cities based on sales performance.
- Analyzed customer preferences for coffee types, items and quantity.
- Observed seasonal trends influencing consumer behavior.
