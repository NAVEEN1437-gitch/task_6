# 📊 Task 6: Get Basic Sales Summary from a SQLite Database using Python
## 🎯 Objective

The goal of this task is to connect Python with a  SQLite database, pull out sales information (like total quantity sold and total revenue), and visualize the results in a simple bar chart.

## 🛠 Tools Used

- Python (for data processing and visualization)

- SQLite (lightweight database, used here in-memory for safety)

- Pandas (to handle data and run SQL queries easily)

- Matplotlib (to create bar charts)

## 📂 Dataset

 - **sales_data :** [sales_data.csv](https://github.com/user-attachments/files/22251994/sales_data.csv)

The dataset (sales_data.csv) contains sales transactions with columns:

InvoiceNo, StockCode, Product, Quantity, InvoiceDate, UnitPrice, CustomerID, Country, TotalPrice 

## 🔎 Steps Performed

- Loaded the CSV file into Python using Pandas.

- Stored the dataset inside a fresh SQLite (in-memory) database.

- Ran an SQL query to calculate:

   - Total quantity sold per product

   - Total revenue per product

- Sorted the results by revenue and displayed the Top 10 products.

- Created a bar chart to visualize product revenues.

- Saved that bar chart as sales_data.png

## 📈 Output

- Chart: A bar chart showing the Top 5 Products by Revenue.
  
- File : Saved the out put bar chart as sales_data.png
