# Data-Analysis-using-Python_SQL

1. **Setup**:
   - Imports necessary libraries: `sqlite3`, `pandas`, and `matplotlib.pyplot`.
   - Creates a SQLite database named `sales_data.db`.

2. **Data Initialization**:
   - Creates a table named `sales` with columns for `id`, `product`, `quantity`, and `price`.
   - Inserts sample data into the `sales` table.

3. **Data Analysis**:
   - Executes an SQL query to calculate total quantity sold (`SUM(quantity)`) and total revenue (`SUM(quantity * price)`) for each product, grouped by the product name.
   - Loads the query result into a Pandas DataFrame and prints it.

4. **Visualization**:
   - Uses Matplotlib to visualize the sales data.

---


# Sales Data Analysis using Python and SQL

## Overview
This project demonstrates how to integrate SQL with Python for basic data analysis. It creates a small SQLite database, analyzes sales data using SQL queries, and visualizes the results using Python libraries like Pandas and Matplotlib.

## Features
- Create and initialize an SQLite database with sample sales data.
- Perform SQL queries to calculate:
  - Total quantity sold per product.
  - Total revenue generated per product.
- Visualize the results using charts.

## Technologies Used
- **Python**: Core programming language.
- **SQLite**: Database for storing and querying sales data.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib**: Data visualization.

## Output
- **Sales Summary Table**: Displays total quantity and revenue for each product.
- **Visualizations**: Generates charts for better insights into the data.

## Sample Data
The sample sales data includes the following products:
- Product A
- Product B
- Product C

## Results
- Total quantity and revenue calculated for each product.
- Bar charts and other visualizations for better understanding.

---

Let me know if you’d like any modifications or additional sections in the README!
