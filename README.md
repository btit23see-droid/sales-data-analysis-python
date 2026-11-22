# Sales Data Analysis

### Exploratory Data Analysis (EDA) Using Python

## Project Overview

This project focuses on analyzing the Sample Superstore dataset to understand sales performance, profitability, discount impact, product category performance, and regional business trends.

The analysis was performed independently using Python libraries to extract meaningful business insights and support data-driven decision-making.

## Project Objectives

- Analyze overall sales and profit performance.
- Identify the most profitable product categories and sub-categories.
- Compare sales and profit across different regions.
- Understand the impact of discounts on profitability.
- Analyze customer segment and shipping mode performance.
- Explore relationships between numerical variables.
- Create meaningful visualizations to communicate business insights.

## Dataset Information

- **Dataset Name:** Sample Superstore
- **Source:** Kaggle
- **Original Records:** 9,994
- **Records After Cleaning:** 9,977
- **Original Columns:** 13

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

1. Data Loading
2. Data Understanding and Inspection
3. Data Cleaning
4. Duplicate Removal
5. Exploratory Data Analysis (EDA)
6. Statistical Analysis
7. Feature Engineering
8. Data Visualization
9. Correlation Analysis
10. Business Insights and Conclusion

## Data Cleaning and Preparation

- Loaded the dataset using Pandas.
- Inspected dataset structure and data types.
- Checked for missing values.
- Identified and removed 17 duplicate records.
- Detected outliers using the IQR method.
- Retained potential valid outliers to avoid removing meaningful business transactions.
- Created additional features such as Profit Margin, Sales Category, and Profit Status.
- Applied one-hot encoding to selected categorical variables.

## Key Business Insights

- **Technology Category:** Generated the highest total sales and profit.
- **Regional Performance:** The West region recorded the highest sales and profit.
- **Furniture Category:** Generated comparatively lower profit despite substantial sales.
- **Top Profitable Sub-Category:** Copiers generated the highest profit.
- **Customer Segment:** Consumer customers contributed the highest sales.
- **Shipping Mode:** Standard Class recorded the highest sales.
- **Discount Analysis:** Higher discount levels were generally associated with lower average profit.
- **Overall Profit Margin:** Approximately 12.47%.

## Data Visualizations

The project includes the following visualizations:

1. Sales by Product Category
2. Profit by Product Category
3. Sales by Region
4. Profit by Region
5. Average Profit by Discount
6. Most Profitable Sub-Categories
7. Sales by Shipping Mode
8. Sales by Customer Segment
9. Correlation Heatmap

## Project Structure

```text
Sales-Data-Analysis/
│
├── Dataset/
│   └── SampleSuperstore.csv
│
├── Notebook/
│   └── Sales_Data_Analysis.ipynb
│
├── Visualizations/
│   ├── Category_Sales.png
│   ├── Category_Profit.png
│   ├── Region_Sales.png
│   ├── Region_Profit.png
│   ├── Discount_Analysis.png
│   ├── Sub_Category_Profit.png
│   ├── Ship_Mode_Sales.png
│   ├── Segment_Sales.png
│   └── Correlation_Heatmap.png
│
└── README.md
```

## Conclusion

This project helped identify important patterns in sales, profitability, discounts, product categories, and regional performance.

The findings provide useful insights into business performance and demonstrate practical skills in data cleaning, exploratory data analysis, statistical analysis, and data visualization using Python.

## Author

**Seema Chaudhary**

Aspiring Data Analyst

**Skills:** Python | Pandas | NumPy | SQL | Power BI | Data Visualization