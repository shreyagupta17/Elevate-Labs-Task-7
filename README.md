# Elevate-Labs-Task-7
# 📊 Sales Summary Report – Task 7

This notebook was developed as part of the **Elevate Labs Data Analyst Internship** program. The task focuses on connecting Python with a SQLite database to perform data extraction, summarize product-level sales, and visualize the findings through simple bar charts.

---

## 🎯 Purpose of the Task

The main goals of this analysis were:

- Establish a connection between Python and an SQLite database
- Write and execute SQL queries to extract:
  - Total quantity sold for each product
  - Total revenue generated (calculated as `quantity × price`)
- Import the SQL output into a pandas DataFrame
- Display the data in the notebook
- Create a bar chart to visualize product-wise revenue

---

## 🧰 Technologies & Libraries

- Python (via Jupyter Notebook)
- SQLite (`sqlite3` module)
- pandas (for data handling)
- matplotlib (for visual output)

---

## 📂 Included Files

- `Task_7_sales_summary.ipynb`: Jupyter Notebook with all code, queries, and visualizations.
- `README.md`: This documentation file with an overview of the task.

---

## 📋 Sample Output Table

After running the SQL queries, the final output looked like:

| Product Name | Quantity Sold | Total Revenue |
|--------------|----------------|----------------|
| Product A    | 17             | 1700           |
| Product B    | 7              | 1400           |
| Product C    | 14             | 2100           |

---

## 📈 Visualization Snapshot

Using `matplotlib`, a bar chart was created to showcase the revenue generated by each product. This helped in quickly identifying the best-performing products in terms of sales.

---

## ✨ Skills & Takeaways

- Writing and executing SQL queries in Python
- Using `GROUP BY` to summarize data
- Performing basic calculations within SQL
- Working with SQLite databases programmatically
- Creating meaningful visualizations using matplotlib
- Understanding the integration of databases and data analysis tools

