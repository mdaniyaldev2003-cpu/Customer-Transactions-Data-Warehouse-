# Customer Transactions Data Warehouse

## Project Overview
This project is a mini **Data Warehouse** that demonstrates an **ETL (Extract, Transform, Load) pipeline** for customer transactions data. It involves:

- Loading raw transaction data from a CSV file.
- Cleaning and transforming the data (removing duplicates, handling missing values, standardizing dates, and calculating total transaction prices).
- Loading the cleaned data into a **SQLite database**.
- Performing SQL-based analytics to generate meaningful insights.

The project is designed for aspiring **Data Engineers** to showcase practical skills in Python, Pandas, SQL, and ETL workflows.

---

## Features
1. **Data Cleaning**
   - Removes duplicates and missing values.
   - Standardizes date formats.

2. **Data Transformation**
   - Calculates `TotalPrice` for each transaction (`Quantity × Price`).

3. **Data Loading**
   - Loads cleaned and transformed data into a SQLite database (`data_warehouse.db`).

4. **Analytics Queries**
   - **Customer-wise total spending:** Sum of total prices grouped by customer.
   - **Product-wise total sales:** Sum of total prices grouped by product.
   - **Daily sales summary:** Sum of total prices grouped by date.

---

## Project Structure
