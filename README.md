# SQL Data Analysis: Exploring Pizza Sales Data

![](/Image%20Folder/pizza_intro.png)

## Introduction

Hello there! I am excited to present the results of my Pizza Sales Data Analysis project. In this project, i analyzed pizza sales data using various **SQL** queries, I explored a comprehensive dataset containing detailed information about pizza orders, including order details, pizza category, size, quantity, prices, and order dates. My goal was to leverage SQL to answer key questions related to total revenue, average order value, top-selling pizzas, and sales trends.

## Problem Statement
The pizza store aims to understand key aspects of its sales data to optimize its business strategies. Some of the specific questions we seek to address are:

- What is the total revenue generated from pizza sales?
- What is the average order value for pizza purchases?
- How many pizzas have been sold in total?
- How many unique orders have been placed?
- What is the average number of pizzas sold per order?

Additionally, we will explore trends related to daily and monthly sales, sales distribution across different pizza categories and sizes, and identify the top and bottom performing pizzas based on revenue, quantity, and number of orders.

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

1. **Total Revenue:** The analysis revealed that the total revenue generated from pizza sales amounted to **$817,860**. This crucial metric provides an overview of the store's overall performance.

![](/Image%20Folder/total_revenue.JPG)

---

2. **Average Order Value:** By calculating the average order value, I found that the typical value of each pizza order is **$38.31**. This insight helps in understanding customer spending behavior.

![](/Image%20Folder/avg_order_value.JPG)

---

3. **Total Pizzas Sold:** The total number of pizzas sold stood at **49,574.** Understanding the sales volume helps in inventory management and planning.

![](/Image%20Folder/total_pizza_sold.JPG)

---

4. **Total Orders Placed:** The number of orders placed summed up to **21,350,** indicating the total engagement with customers.

![](/Image%20Folder/total_orders_placed.JPG)

---

5. **Average Number of Pizzas Sold per Order:** The average number of pizzas sold per order was **2.32.** This insight aids in analyzing customer preferences and bundling strategies.

![](/Image%20Folder/avg_pizza_per_order.JPG)

---

6. **Daily Trend:** We analyzed the daily sales trend to identify the number of orders placed on each day of the week.

![](/Image%20Folder/daily_trend.JPG)

---
7. **Monthly Trend:** We explored the monthly sales trend to understand the variation in sales over the months.

![](/Image%20Folder/monthly_trend.JPG)

---
8. **Percentage of Sales by Pizza Category:** We calculated the percentage of total sales for each pizza category and size to identify popular choices.

![](/Image%20Folder/percentage_sales_by_category.JPG)

---
9. **Percentage of Sales by Pizza Size:** We calculated the percentage of total sales for each pizza category and size to identify popular choices.

![](/Image%20Folder/percentage_sales_by_size.JPG)

---
10. **Top and Bottom Performing Pizzas:** We identified the top 5 pizzas based on revenue, quantity sold, and number of orders, as well as the bottom 5 pizzas in these categories.

Top Performing Pizza            |  Bottom Performing Pizza 
:------------------------------:|:--------------------:
![](/Image%20Folder/top_5_pizza_by_order.JPG)   |  ![](/Image%20Folder/bottom_5_pizza_by_order.JPG)
![](/Image%20Folder/top_5_pizza_by_quantity.JPG)   |  ![](/Image%20Folder/bottom_5_pizza_by_quantity.JPG)
![](/Image%20Folder/top_5_pizza_by_revenue.JPG)   |  ![](/Image%20Folder/bottom_5_pizza_by_revenue.JPG)
   
## Conclusion and Recommendation

In conclusion, this SQL-based Pizza Sales Data Analysis project has provided valuable insights into the store's sales performance and customer preferences. The analysis highlights opportunities to optimize sales strategies, promote popular pizza choices, and enhance the overall customer experience.

Based on the insights derived, we recommend the following actions:

- Promote Top-Performing Pizzas: Focus marketing efforts on the top-selling pizzas to capitalize on their popularity.
- Enhance Average Order Value: Implement strategies like bundle deals or promotions to increase the average order value.
- Explore Monthly Trends: Identify reasons behind fluctuations in sales across months and tailor marketing efforts accordingly.
- Improve Pizza Categories: Consider expanding or refining the pizza categories based on their sales performance.

By implementing these recommendations, the pizza store can optimize its operations, cater to customer preferences, and boost its overall sales and profitability.
