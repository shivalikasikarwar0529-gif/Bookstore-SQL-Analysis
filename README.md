# Bookstore SQL Analysis 📚

This repository contains a comprehensive SQL analysis of a Bookstore database. The project focuses on extracting meaningful insights such as sales trends, inventory management, and pricing analysis using PostgreSQL.

## 🚀 Project Overview
The goal of this project is to demonstrate SQL proficiency through various data retrieval tasks, including:
* **Inventory Tracking:** Calculating the total stock available across all titles.
* **Pricing Insights:** Identifying the most expensive books in the collection using advanced sorting and filtering.
* **Sales Analysis:** Monitoring transactions and book data within specific timeframes.

## 🛠️ Tech Stack
* **Database:** PostgreSQL
* **Tool:** SQL Shell / DBeaver / PGAdmin

## 📊 Key Queries & Insights
Some of the core analysis performed in the `Bookstore_queries.sql` file includes:
1. **Total Stock Calculation:** Using `SUM()` to find the total volume of inventory.
2. **Top Tier Pricing:** Using `ORDER BY` and `LIMIT` to isolate high-value items.
3. **Data Filtering:** Retrieving specific book details based on complex criteria.

## 📁 Repository Structure
* `Bookstore_queries.sql`: Contains the full SQL script with all analysis queries.
* `README.md`: Project documentation and summary.

---
**How to use:**
1. Clone the repository.
2. Run the `Bookstore_queries.sql` script in your preferred SQL environment.
3. Explore the insights!

## 🔍 Advanced Insights & Visuals

#### 1. Revenue by Category
This analysis identifies which genres are driving the most revenue by joining book data with orders.
![Revenue Analysis]  <img width="1365" height="715" alt="Revenue by category" src="https://github.com/user-attachments/assets/d0cbe3c3-4c8f-4b13-b5fd-65d8e77500c8" />

#### 2. Author Performance & Inventory
A deep dive into our inventory to see which authors have the highest presence and average book pricing.
![Author Analysis]   <img width="1365" height="721" alt="Average price of each author&#39;s book available in stock" src="https://github.com/user-attachments/assets/ad331ef1-0947-4b77-ba85-6c3a581c86e5" />



