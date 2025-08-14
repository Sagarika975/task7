Task Overview
This project demonstrates how to extract basic sales summary from a SQLite database using Python, including data analysis and visualization.
 Objective

Connect to SQLite database using Python
Run SQL queries to summarize sales data
Display results using print statements and matplotlib charts
 Tools Used

Python: Main programming language
sqlite3: Database connectivity
pandas: Data manipulation and analysis
matplotlib: Data visualization
SQLite: Lightweight database

 Dataset Description
Created a simple SQLite database (sales_data.db) with one table:
Sales Table Structure:

id: Primary key
product: Product name (Laptop, Mouse, Keyboard, Monitor, Headphones)
quantity: Number of items sold
price: Unit price
sale_date: Date of sale
Overall Summary:

Total Transactions: 10
Total Items Sold: 142 units
Total Revenue: $22,708.58
Average Transaction Value: $2,270.86

📊 Visualizations
The script generates bar charts showing:

Revenue by Product
Total Quantity Sold by Product

🎯 Key Learning Outcomes
✅ SQL Skills:

Basic SELECT statements
GROUP BY clause usage
Aggregate functions (SUM, COUNT, AVG)
ORDER BY for sorting results

✅ Python-Database Integration:

sqlite3 module usage
pandas.read_sql_query() for data import
Database connection management

✅ Data Visualization:

matplotlib bar chart creation
Chart customization and labeling
Saving plots to files

✅ Data Analysis:

Revenue calculation (quantity × price)
Product performance comparison
Sales summary statistics
