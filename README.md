# Customer-Segmentation-Postgree-SQL

## Project Overview

This project focuses on analyzing sales, customer, and product data to gain insights into business performance and customer behavior. Through SQL queries, we extract valuable information that can help the company improve sales strategies, understand customer preferences, and track sales growth. The database consists of four tables: Customers, Products, Stores, and Sales. Each table provides crucial data for understanding the relationships between customers, products, and sales.

# Key Components

## Customers Table

This table contains information about customers, including:

customer_id: Unique identifier for each customer.
customer_name: Name of the customer.
gender: Gender of the customer.
age: Age of the customer.
location: Location of the customer.

## Products Table

This table stores product information such as:

product_id: Unique identifier for each product.
product_name: Name of the product.
category: Category to which the product belongs.
price: Price of the product.

## Stores Table

Contains data about the stores where sales take place:

store_id: Unique identifier for each store.
store_name: Name of the store.
location: Location of the store.

## Sales Table

This table records sales transactions, with the following columns:

sale_id: Unique identifier for each sale.
customer_id: Customer making the purchase.
product_id: Product being purchased.
store_id: Store where the sale took place.
quantity: Number of units purchased.
total_price: Total amount spent on the sale.
sale_date: Date and time when the sale occurred.

# SQL Queries and Business Insights

## Total Number of Customers

Get a count of all customers to understand the company's customer base.

## Customer Distribution by Gender

Analyze the customer base in terms of gender, providing insights for targeted marketing strategies.

## Customer Distribution Across Age Groups

Group customers by age ranges to understand which demographics make up the majority of the customer base.

## Top 5 Customers by Total Spending

Identify the highest-spending customers, allowing the company to focus on VIP customer retention.

## Customers with Multiple Purchases

Determine how many customers are repeat buyers, which helps assess customer loyalty.

## Average Order Value

Calculate the average revenue generated per order, providing insight into customer purchasing behavior.

## Total Sales by Customer Location

 Analyze sales distribution across different regions, helping the company identify key markets.

## Sales Revenue by Gender

Compare the spending patterns of male and female customers to help guide product offerings and marketing.

## Top 5 Products for Customers Aged 18-25

Discover the most popular products among young customers, enabling better product recommendations and promotions.

## Inactive Customers (No Purchase in 12 Months)

Identify customers who haven't made a purchase in the last year to target re-engagement campaigns.

## Year-over-Year Sales Growth

Track the company's sales growth over time, helping evaluate the success of sales strategies and market expansion.

# Conclusion

This project leverages SQL queries to extract key business insights from customer, product, and sales data. The analysis helps the company understand its customer base, improve sales performance, and optimize marketing efforts based on data-driven decisions.
