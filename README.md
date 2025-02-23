# Sales and Profitability Analysis

## Overview
This project analyzes sales performance, profitability, and regional disparities using a dataset provided for a **Business Analyst Intern assignment at JAR**. The analysis is performed using **Python (Pandas, Matplotlib, Seaborn)** for data processing and visualization.

## Datasets Used
The project utilizes the following datasets:
- **List_of_Orders.csv** – Contains details of customer orders (Order ID, City, State, etc.).
- **Order_Details.csv** – Includes item-wise details such as product category, amount, and profit.
- **Sales_Target.csv** – Contains monthly sales targets for different categories.

## Objectives
1. **Sales and Profitability Analysis**
   - Merge orders and order details datasets.
   - Compute total sales and profit margins by category.
   - Identify top-performing and underperforming categories.
   
2. **Target Achievement Analysis**
   - Analyze month-over-month percentage change in sales targets for the furniture category.
   - Identify months with significant target fluctuations.
   
3. **Regional Performance Insights**
   - Identify the top 5 states and cities by order count.
   - Calculate total sales and average profit for these regions.
   - Suggest strategies for improving low-performing regions.

## Methodology
1. **Data Cleaning & Preprocessing**: Handle missing values, merge datasets on Order ID.
2. **Exploratory Data Analysis (EDA)**: Identify trends in sales, profit, and targets.
3. **Visualization**: Use Matplotlib and Seaborn to plot trends, scatter plots, and bar charts.
4. **Insights & Recommendations**: Interpret results and provide strategic suggestions.

## Setup & Installation
To run the analysis, install the required dependencies:
```sh
pip install pandas matplotlib seaborn
```
Run the Python script:
```sh
python analysis.py
```

## Visualizations
- **Sales vs. Profitability Scatter Plot**: Highlights sales and profit differences by region.
- **Profitability Bar Chart**: Displays average profit per order for states and cities.

## Key Findings & Recommendations
- **New York & Los Angeles**: High sales & profitability → Maintain strategy.
- **Miami & Houston**: Low profitability → Reduce discounts, optimize pricing.
- **Chicago**: Needs bulk-order discounts to increase sales.
- **Furniture Sales Target**: Fluctuations indicate a need for improved forecasting.

## Future Scope
- Implement machine learning for sales forecasting.
- Automate reporting with dashboards (Power BI/Tableau).
- Expand analysis to include customer demographics.

## Contributors
- **[ABIR GHOSH]** – Data Analysis & Report

## License
This project is for educational purposes and follows an open-source approach.

