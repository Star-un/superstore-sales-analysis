# Sales Data Analysis Project

## Overview
This project performs an end‑to‑end sales data analysis using the Superstore dataset. The goal is to understand sales trends, profit margins, and regional/business‑level performance using Python and data visualization.

## Dataset
- Source: [Sample Superstore Dataset - Kaggle](https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset)
- Description: Transaction‑level sales data from a retail superstore, including columns like `Sales`, `Profit`, `Region`, `Category`, `Sub‑Category`, `Customer Name`, and `Order Date`.

## What I Did
- Loaded and cleaned the dataset (handled duplicates and structured datetime columns).
- Calculated key business KPIs: total sales, total profit, overall profit margin, number of customers, and number of orders.
- Explored patterns through visualizations:
  - Monthly sales trends.
  - Sales by region.
  - Profit by category.
  - Top customers by sales.

## Tools Used
- Python
- Pandas (data cleaning and KPIs)
- Matplotlib / Seaborn (visualizations)
- Jupyter Notebook

## How to Run
1. Clone this repository.
2. Place the `SampleSuperstore.csv` file in the `data/` folder (or update the path in the notebook).
3. Open `sales_analysis_project.ipynb` in Jupyter and run the cells.
