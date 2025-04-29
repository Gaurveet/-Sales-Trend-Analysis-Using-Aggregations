Sales Trend Analysis Using SQL
This project performs a monthly sales trend analysis on an `online_sales` dataset using SQL aggregation techniques. It demonstrates how to group data by year and month to calculate revenue and order volume.

Tools Used
- PostgreSQL (syntax used)
- Python (to simulate sample data)
- CSV files for data and results

Dataset
The dataset `online_sales_sample.csv` contains:
- `order_date`: Date of order
- `amount`: Transaction amount
- `order_id`: Unique identifier for each order
- `product_id`: Identifier for product

Analysis Performed
The SQL query:
- Extracts **year** and **month** from `order_date`
- Calculates **total revenue** using `SUM(amount)`
- Calculates **order volume** using `COUNT(DISTINCT order_id)`
- Groups and sorts results by year and month

Files Included
| File | Description |
|------|-------------|
| `sales_trend_analysis.sql` | SQL script to run the analysis |
| `online_sales_sample.csv` | Sample dataset used for querying |
| `monthly_sales_trend_results.csv` | Output of the SQL query |

How to Use
1. Load the dataset into your SQL database as a table named `online_sales`.
2. Run the SQL script `sales_trend_analysis.sql`.
3. Review the monthly trend in the output or compare with `monthly_sales_trend_results.csv`.

Outcome
This task helps you understand:
- SQL date functions (EXTRACT)
- Aggregations (SUM, COUNT)
- GROUP BY and ORDER BY clauses
