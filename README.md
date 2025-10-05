# Task 7 - Sales Summary

## Objective
Get a basic sales summary from a small SQLite database using Python.  
- Total quantity sold per product  
- Total revenue per product  
- Daily revenue trend  
- Visualize results with bar and line charts  

## Tools Used
- Python 3  
- sqlite3  
- pandas  
- matplotlib  
- Jupyter Notebook  

## Steps
1. Created a SQLite database `sales_data.db` with a `sales` table.  
2. Inserted sample sales data (product, quantity, price, date).  
3. Queried the database using SQL inside Python to calculate:  
   - Total quantity sold per product  
   - Total revenue per product  
   - Daily revenue  
4. Loaded results into pandas DataFrames.  
5. Exported results to CSV files:
   - `sales_summary_by_product.csv`  
   - `daily_revenue.csv`  
6. Created visualizations and saved them as PNG files:
   - `revenue_by_product.png`  
   - `quantity_by_product.png`  
   - `daily_revenue.png`  

## Results
### Sales Summary
| Product     | Total Quantity | Revenue   |
|-------------|----------------|-----------|
| Laptop      | 8              | ₹560,000  |
| Mobile      | 17             | ₹425,000  |
| Tablet      | 10             | ₹300,000  |
| Headphones  | 35             | ₹52,500   |

### Daily Revenue
| Date       | Revenue   |
|------------|-----------|
| 2025-09-01 | ₹355,500  |
| 2025-09-02 | ₹460,000  |
| 2025-09-03 | ₹310,000  |
| 2025-09-04 | ₹175,000  |
| 2025-09-05 | ₹30,000   |

## How to Run
1. Clone the repo.  
2. Run the Jupyter notebook or `sales_summary.py`.  
3. Check console output, CSV files, and generated charts.
