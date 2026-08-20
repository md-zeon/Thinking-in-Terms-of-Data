# Data Files

This folder contains sample datasets for practice.

## Files

| File                  | Description                                 | Rows | Columns |
| --------------------- | ------------------------------------------- | ---- | ------- |
| `employees.csv`       | Clean employee data                         | 10   | 6       |
| `employees_messy.csv` | Messy employee data (for cleaning practice) | 15   | 6       |
| `sales_data.csv`      | Monthly sales transactions                  | 32   | 6       |
| `customers.csv`       | Customer information                        | 20   | 8       |
| `store_data.json`     | Nested JSON with products and customers     | -    | -       |

## How to Use

- **employees.csv** — Start here. Clean, well-structured data.
- **employees_messy.csv** — Practice data cleaning. Has duplicates, missing values, inconsistent formatting, and outliers.
- **sales_data.csv** — Good for analysis and visualization practice.
- **customers.csv** — Good for segmentation and customer analysis.
- **store_data.json** — Practice working with nested/JSON data.

## Data Cleaning Practice

The `employees_messy.csv` file contains these intentional issues:

1. **Missing values** — Some cells are empty
2. **Duplicates** — Same rows appear multiple times
3. **Inconsistent casing** — "new york", "NEW YORK", "New York"
4. **Inconsistent date formats** — "2020-01-15", "2019/03/22", "Nov 1 2020"
5. **Wrong values** — Age = -5, Age = 200
6. **Inconsistent department names** — "engineering", "Engineering", "ENGINEERING"
