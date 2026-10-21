# E-Commerce Customer Insights Engine

## Overview
A beginner-friendly data science project that joins customer and order datasets using Pandas and calculates customer spending, average order value (AOV), city-wise sales, and a Top 5 customer leaderboard.

## Objectives
- Load `customers.csv` and `orders.csv`.
- Demonstrate Pandas inner join and left join using `customer_id`.
- Calculate total spend, order count, and average order value per customer.
- Summarize sales by city and region.
- Identify customers with zero purchases.
- Display the five highest-spending customers.

## Technology Stack
- Python 3
- Pandas
- NumPy
- Jupyter Notebook / Google Colab

## Project Files
- `E_Commerce_Customer_Insights.ipynb` — notebook with code and pre-rendered outputs.
- `customers.csv` — sample customer data.
- `orders.csv` — sample order data.
- `customer_spending_summary.csv` — customer-level metrics.
- `city_sales_summary.csv` — city-level sales metrics.
- `top_5_customers.csv` — Top 5 leaderboard.
- `requirements.txt` — required Python packages.

## Sample Top 5 Customers
| Customer ID | Name | City | Total Spend | Orders |
|---:|---|---|---:|---:|
| 101 | Ravi | Hyderabad | 7000 | 3 |
| 103 | Priya | Bangalore | 4900 | 2 |
| 108 | Rahul | Mumbai | 4500 | 1 |
| 104 | Arjun | Hyderabad | 4000 | 1 |
| 107 | Divya | Bangalore | 3500 | 1 |

## Sample Dataset Summary
- Total customers: 8
- Total orders: 12
- Total revenue: 31900
- Average order value: 2658.33

## Run the Project
1. Upload this repository to GitHub, or open the notebook in Google Colab.
2. Ensure `customers.csv` and `orders.csv` are in the same folder as the notebook.
3. Run notebook cells from top to bottom.
4. The notebook creates CSV summary files when the final cell is executed.

## Important Note
The included CSV files contain **sample demonstration data**, not official internship data. If GetIntern supplied its own datasets, replace these CSV files with the official files while keeping the required column names (`customer_id`, `order_id`, `order_amount`, etc.) consistent.
