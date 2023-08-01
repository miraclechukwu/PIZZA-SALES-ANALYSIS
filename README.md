# SQL Data Analysis: Exploring Pizza Sales Data



## Introduction

Hello there! I am excited to present the results of my Pizza Sales Data Analysis project. In this project, i analyzed pizza sales data using various **SQL** queries, I explored a comprehensive dataset containing detailed information about pizza orders, including order details, pizza category, size, quantity, prices, and order dates. My goal was to leverage SQL to answer key questions related to total revenue, average order value, top-selling pizzas, and sales trends.

## Data Cleaning Techniques and SQL Syntax Used

To ensure accurate analysis, I applied essential data cleaning techniques using **SQL**. Throughout the process, I utilized various SQL syntax and functions to clean and transform the data. Here are the techniques and SQL syntax I used:

1. **Filtering Invalid Data:**
   - To remove any invalid or missing data, I employed the `WHERE` clause in SQL queries. For instance, `WHERE pizza_category IS NOT NULL` eliminates rows where the pizza category information is missing.

2. **Handling Duplicates:**
   - In cases where duplicate records existed, I made use of the `DISTINCT` keyword to ensure unique values. For example, `SELECT DISTINCT pizza_name FROM pizza_sales` retrieves only distinct pizza names.

3. **Converting Data Types:**
   - To ensure proper data type handling, I used appropriate SQL functions. For example, `CAST(quantity as DECIMAL(10,2))` converts the quantity column to a decimal data type with two decimal places.

4. **Data Aggregation:**
   - For calculating total revenue, average order value, and other aggregate functions, I employed `SUM()`, `COUNT()`, and `AVG()` respectively.

5. **Sorting Data:**
   - To arrange data in a desired order, I utilized the `ORDER BY` clause in SQL queries. For example, `ORDER BY total_revenue DESC` sorts the result by total revenue in descending order.

## Analytics/Insights

Now, let's dive into the insights and analytics I derived from the pizza sales data using SQL:

1. **Total Revenue:** The analysis revealed that the total revenue generated from pizza sales amounted to $X,XXX,XXX. This crucial metric provides an overview of the store's overall performance.

2. **Average Order Value:** By calculating the average order value, I found that the typical value of each pizza order is $XX.XX. This insight helps in understanding customer spending behavior.

3. **Total Pizzas Sold:** The total number of pizzas sold stood at XXX,XXX. Understanding the sales volume helps in inventory management and planning.

4. **Total Orders Placed:** The number of orders placed summed up to XXX, indicating the total engagement with customers.

5. **Average Number of Pizzas Sold per Order:** The average number of pizzas sold per order was X.XX. This insight aids in analyzing customer preferences and bundling strategies.

## Conclusion

Through SQL data analysis, I successfully gained valuable insights into the pizza store's performance. The utilization of data cleaning techniques and various SQL syntax ensured the accuracy and reliability of the results. The key analytics and insights provided, such as total revenue, average order value, and sales trends, are instrumental in driving data-driven decision-making for the pizza store's management.

I am thrilled to have taken this journey of pizza sales data analysis using SQL, where I uncovered essential business insights! 🍕📊🔍
