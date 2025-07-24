# DataWarehouseAnalytics Project

## Overview
This project implements a data warehouse analytics solution for customer and product analysis. It includes SQL scripts for database initialization, data exploration, segmentation, and reporting, as well as datasets in CSV format for ETL operations.

## Folder Structure

- `scripts/`  
  Contains SQL scripts for:
  - Database setup (`00_init_database.sql`)
  - Data exploration and analysis (`01_database_exploration.sql` to `13_report_products.sql`)
- `datasets/csv-files/`  
  Contains raw and processed CSV files for customers, products, and sales.

- `analysis.ipynb`  
  Jupyter notebook for interactive data analysis and visualization.

## Key Features

- **Database Initialization:**  
  Creates schemas and tables, and loads data from CSV files.
- **Exploratory Analysis:**  
  Scripts for exploring tables, columns, and data ranges.
- **Segmentation & Reporting:**  
  Customer and product segmentation, performance analysis, and report generation.
- **Magnitude & Trend Analysis:**  
  Aggregates and benchmarks sales, orders, and other KPIs.

## Getting Started

1. Run `scripts/00_init_database.sql` to set up the database and import data.
2. Use other scripts in `scripts/` for analysis and reporting.
3. Open `analysis.ipynb` for further exploration and visualization.

## Requirements

- SQL Server (or compatible RDBMS)
- Python (for Jupyter notebook)
- Pandas, SQLAlchemy (recommended for notebook analysis)

## Data Sources

- All CSV files are located in `datasets/csv-files/`.

## License

This project is for educational and
