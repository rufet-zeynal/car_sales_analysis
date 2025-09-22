# Car Sales Data Analysis

## Overview
This project analyzes a car sales dataset to explore trends in price, mileage, engine size, fuel type, and manufacturer. The goal is to uncover insights and visualize patterns in car sales data using Python, Pandas, and Seaborn.

## Dataset
- File: `car_sales_data.csv`  
- Columns:
  - Manufacturer
  - Model
  - Engine size
  - Fuel type
  - Year of manufacture
  - Mileage
  - Price

## Tools / Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Workflow
1. Loaded and explored the dataset (`df.head()`, `df.info()`, `df.describe()`)  
2. Visualized distributions of numerical columns (Price, Mileage, Engine size)  
3. Analyzed categorical data (Manufacturer, Fuel type) using count plots and bar plots  
4. Explored relationships between variables (Price vs Mileage, Price vs Engine size) using scatter plots and boxplots  
5. Summarized key insights

## Key Insights
- Petrol cars are the most common fuel type in the dataset  
- Higher engine size generally correlates with higher price  
- Mileage negatively impacts price, but some luxury cars are outliers  
- Certain manufacturers have higher average car prices than others  

## How to Run
1. Open `car_sales_analysis.ipynb` in Jupyter Notebook or Google Colab  
2. Ensure `car_sales_data.csv` is in the same folder  
3. Run all cells to reproduce the analysis and visualizations

