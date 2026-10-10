# Supermarket Sales Analysis – Week 3

## Project Overview

This project focuses on analyzing supermarket transaction data using Python. The objective is to understand sales performance, product demand, customer types, payment preferences, and sales trends through data analysis and visualization.

## Objectives

* Calculate total sales and average sales per transaction.
* Identify the highest and lowest transaction values.
* Analyze sales by product and product category.
* Examine sales across different payment methods.
* Understand customer type distribution.
* Analyze daily and monthly sales trends.
* Generate meaningful business insights.

## Dataset Description

The dataset contains **1,000 transactions and 9 columns**.

| Column        | Description               |
| ------------- | ------------------------- |
| Invoice ID    | Transaction identifier    |
| Date          | Transaction date          |
| Product       | Product name              |
| Category      | Product category          |
| Quantity      | Number of units purchased |
| Unit Price    | Price per unit            |
| Customer Type | Type of customer          |
| Payment       | Payment method            |
| Total         | Total transaction amount  |

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

## Project Workflow

1. Imported the required Python libraries.
2. Loaded and inspected the dataset.
3. Checked the number of rows, columns, and data types.
4. Checked for missing values and duplicate records.
5. Converted the Date column to datetime format.
6. Calculated total sales, average sales, highest and lowest sales, and total quantity sold.
7. Analyzed sales by product and payment method.
8. Created bar charts, a pie chart, and a line chart.
9. Analyzed product quantities and top-selling products.
10. Examined monthly and daily sales.
11. Generated business insights and a project conclusion.

## Key Results

* **Total Sales:** 81,902.28
* **Total Transactions:** 1,000
* **Average Sales per Transaction:** 81.90
* **Total Quantity Sold:** 5,525
* **Highest Transaction Value:** 799.80
* **Lowest Transaction Value:** 0.76

## Key Business Insights

* Electronics was identified as the best-selling category by revenue in the notebook's business insights.
* Cash was the most frequently used payment method.
* Members were identified as the customer type generating the highest revenue.
* Biscuits were identified as the best-selling product by quantity.
* Mouse generated the highest product-wise sales revenue, totalling 10,012.07.
* January recorded total sales of 81,902.28 in the dataset.

## Data Visualizations

The project includes the following visualizations:

* Total sales by product
* Sales by payment method
* Customer type distribution
* Daily sales trend
* Quantity sold by product
* Monthly sales analysis

## How to Run the Project

1. Download the Jupyter Notebook and `supermarket_sales.csv` dataset.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload the CSV file to the environment.
4. Update the dataset path if necessary.
5. Run the notebook cells in order to reproduce the analysis and visualizations.

## Conclusion

This project demonstrates the use of Python for data cleaning, exploratory data analysis, and visualization of supermarket transaction data. The analysis identifies sales patterns, product performance, payment preferences, and customer purchasing behaviour. These findings can help support data-driven business decisions.
