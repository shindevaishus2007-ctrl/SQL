## SQL

## 🌸 CHANEL Perfume Sales, Inventory and Customer Analysis System.

## Scenario

The CHANEL Perfume Sales, Inventory and Customer Analysis System is a database management project designed to manage perfume information, customer details, store locations, sales transactions, inventory levels, and customer reviews.

The system maintains information about different CHANEL perfumes, including their names, fragrance families, sizes, and prices.

It records sales transactions to analyze which perfumes sell the most and which products generate the highest revenue. It also helps monitor available stock at different stores and understand customer satisfaction through ratings and reviews.

## The system maintains information about the following 6 important tables:

* Stores
* Perfumes
* Customers
* Inventory
* Sales
* Reviews

## 1. 🌸 Stores

The system stores information about different store locations where perfume sales are recorded.

*The system stores the following information:*

* Store ID
* Store Name
* City
* Country

## 2. 🧴 Perfumes

The system maintains details about different perfumes, including their fragrance families, sizes, prices, launch years, and gender categories.

*The system stores the following information:*

* Perfume ID
* Perfume Name
* Fragrance Family
* Size in ML
* Price in INR
* Launch Year
* Gender Category

## 3. 👤 Customers

The system maintains customer information to understand customer segments and analyze purchasing activities.

*The system stores the following information:*

* Customer ID
* Customer Name
* City
* Age
* Customer Segment

## 4. 📦 Inventory

The system tracks the available stock of different perfumes at various stores. It helps identify products that need restocking.

*The system stores the following information:*

* Inventory ID
* Store ID
* Perfume ID
* Stock Quantity
* Reorder Level
* Last Restock Date

## 5. 💰 Sales

The system records perfume sales transactions to calculate revenue, analyze product performance, and identify sales trends.

*The system stores the following information:*

* Sale ID
* Sale Date
* Store ID
* Customer ID
* Perfume ID
* Quantity
* Unit Price in INR
* Discount Percentage

## 6. ⭐ Reviews

The system maintains customer ratings and feedback to analyze customer satisfaction with different perfumes.

*The system stores the following information:*

* Review ID
* Customer ID
* Perfume ID
* Rating
* Review Date
* Review Text

100)`.
40. Calculate monthly sales revenue.

## Table 6: Reviews — 
41. Display all records from the `Reviews` table.
42. Display reviews with a rating of 4.5 or higher.
43. Find reviews with a rating below 4.0.
44. Count the total number of reviews.
45. Calculate the average rating across all reviews.
46. Find the highest rating.
47. Count how many reviews each perfume has, grouped by `PerfumeID`.
48. Find the average rating for each perfume, showing only perfumes with an average rating of at least 4.5.

# 🌸 Chanel Perfume Sales and Inventory Analysis – SQL Business Analysis Question Bank

## 🏬 Stores Analysis

1. Display all records from the `Stores` table.
2. Find all stores located in Mumbai.
3. Display stores located in a particular city.
4. Count the total number of stores.
5. Find the number of stores in each city.
6. Display stores grouped by their store type.
7. Find the store with the highest sales, if sales information is available.
8. Display stores opened after a specified date.

## 🌺 Perfume Analysis

1. Display all records from the `Perfume` table.
2. Display all perfumes belonging to the Chanel brand.
3. Find perfumes priced above ₹10,000.
4. Find the most expensive perfume.
5. Find the least expensive perfume.
6. Count the total number of perfumes.
7. Calculate the average price of perfumes.
8. Display perfumes grouped by fragrance category.

## 👥 Customer Analysis

1. Display all records from the `Customers` table.
2. Find customers from Mumbai.
3. Count the total number of customers.
4. Display customers registered in 2026.
5. Find customers grouped by city.
6. Count the number of customers in each city.
7. Display customers whose names start with 'A'.
8. Find customers who have not provided an email address.

## 📦 Inventory Analysis

1. Display all records from the `Inventory` table.
2. Find perfumes with stock quantities below 10.
3. Find perfumes that are out of stock.
4. Calculate the total quantity of inventory available.
5. Find the perfume with the highest stock quantity.
6. Display inventory details for each store.
7. Count the number of perfumes available at each store.
8. Identify perfumes that need restocking.

## 💰 Sales Analysis

1. Display all records from the `Sales` table.
2. Display sales made during September 2026.
3. Find sales transactions where quantity is greater than 1.
4. Display sales with a discount of 10%.
5. Count the total number of sales transactions.
6. Calculate total units sold.
7. Calculate total sales revenue after discounts using `Quantity * UnitPriceINR * (1 - DiscountPercent / 100)`.
8. Calculate monthly sales revenue.

## ⭐ Reviews Analysis

1. Display all records from the `Reviews` table.
2. Display reviews with a rating of 4.5 or higher.
3. Find reviews with a rating below 4.0.
4. Count the total number of reviews.
5. Calculate the average rating across all reviews.
6. Find the highest rating.
7. Count how many reviews each perfume has, grouped by `PerfumeID`.
8. Find the average rating for each perfume, showing only perfumes with an average rating above 4.0.








## ✦Project Conclusion

The CHANEL Perfume Sales, Inventory and Customer Analysis System demonstrates how SQL can be used to organize, manage, and analyze retail business data. The project helps identify best-selling perfumes, calculate revenue, monitor stock levels, compare store performance, and evaluate customer satisfaction.

By using SQL queries, joins, and aggregate functions, meaningful insights can be extracted from the database. Connecting the database to Power BI further improves data presentation through interactive charts and dashboards.



















