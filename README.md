# Restaurant-Orders-Tracker
🍽 Restaurant Orders SQL Analysis Project
This SQL project showcases my ability to perform data analysis using structured queries on a restaurant's order dataset. The dataset consists of two main tables:

menu_items: Contains item details including name, price, and category.

order_details: Includes records of item purchases, order IDs, and timestamps.

## Key Questions Answered
(1) High-Priced Asian Dishes
Retrieved all Asian dishes from the menu and sorted them by price in descending order to identify premium items.

(2) Dish Count by Category
Counted the number of dishes available in each food category to understand the menu diversity.

(3) Purchase Frequency per Dish
Calculated how many times each dish was ordered by joining order_details with menu_items. The results were sorted to reveal the most popular items.

(4) Order Timeline
Identified the time range of the order dataset by extracting the earliest and latest order dates.

(5) Total Bill Per Order
Summed up item prices for each order_id to get the total bill amount per customer order.

(6) Bulk Buyers
Counted how many orders included more than 10 items, offering insights into large group orders or bulk purchases.

## Skills Demonstrated
SQL Joins (INNER and LEFT JOIN)

Aggregation functions (COUNT, SUM, MIN, MAX)

Grouping and filtering using GROUP BY and HAVING

Sorting results with ORDER BY

Subqueries for advanced filtering

## Dataset
The dataset used in this project includes:

menu_items.csv

order_details.csv

A data dictionary (restaurant_db_data_dictionary.csv) that explains the structure and columns of the data.
