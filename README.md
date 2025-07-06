# Basic Sales Summary using SQLite and Python

## Objective
This project demonstrates how to connect a SQLite database with Python, execute simple SQL queries, and visualize a sales summary using pandas and matplotlib.

## Tools and Technologies Used
- Python
- SQLite (via sqlite3)
- pandas
- matplotlib
- Jupyter Notebook

## Dataset
The dataset is stored in a SQLite database file named `sales_data.db`, which contains one table called `sales`.

### sales table columns:
- product (TEXT)
- quantity (INTEGER)
- price (REAL)

## What This Project Does
- Connects to the SQLite database using sqlite3
- Executes a SQL query to calculate total quantity and total revenue for each product
- Loads the result into a pandas DataFrame
- Prints the sales summary table
- Creates a bar chart to visualize revenue by product
- Saves the bar chart as `sales_chart.png`

## How to Run
1. Ensure Python is installed along with the following libraries:
   - sqlite3 (comes pre-installed with Python)
   - pandas
   - matplotlib
2. Place `sales_data.db` in the same folder as the notebook.
3. Open and run the Jupyter Notebook.
4. The chart and summary output will be generated, and the chart will be saved.

## Output
- A printed table showing each product's total quantity sold and total revenue
- A bar chart representing revenue by product

## Author
[SHIEK NOOR AAFREEN]