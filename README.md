Task-7

Basic Sales Summary using SQLite and Python

---

Files Include:
 dataset.csv – The original sales data.
 dataset.db – SQLite database created from the CSV file.
 main.ipynb – Notebook with the code.
 sales_chart.png – Revenue bar chart with value labels.

---

Tools & Libraries Used:
 Python,
 SQLite (sqlite3),
 Pandas,
 Matplotlib.

---

Steps Taken:
 1.Loaded the dataset (dataset.csv) using pandas.
 2.Created a SQLite database (dataset.db) and inserted the data into a table named dataset.
 3.Wrote a SQL query to calculate:
   - Total quantity sold per product.
   - Total revenue per product (quantity * price).
 4.Loaded the query result into a pandas DataFrame.
 5.Printed the result using print().
 6.Plotted a bar chart with:
   - Products on the x-axis.
   - Revenue on the y-axis.
   - Labels showing exact revenue values on top of each bar.

---

Key Concepts:
 SQL querying (GROUP BY, SUM),
 Using SQLite inside Python,
 Data visualization with Matplotlib,
 Integrating pandas with SQL results.
