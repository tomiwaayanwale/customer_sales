# Customer Sales Analysis Project

## Project Overview
This project involves the analysis of customer sales data to derive insights that can drive business decisions. The primary goal is to explore the data, identify key metrics, and provide actionable recommendations based on the findings. The analysis includes evaluating total sales, understanding sales drivers, identifying high-performing customer segments and stores, and analyzing sales trends over time.
## Data Description
The project uses two primary datasets:
1. Transaction Data: Contains detailed records of individual transactions, including product names, quantities, prices, and store information.
2. Customer Data: Contains customer information, including loyalty card numbers, lifestage classifications, and whether the customer is a premium customer.

## Installation
To run this project, you need the following software and libraries:
- Python 3.7 or higher
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - plotly
  - openpyxl (for Excel file handling)

You can install the required libraries using:
```bash
pip install pandas numpy matplotlib seaborn plotly openpyxl
```

## Project Structure
- /data: Contains the datasets used in the analysis.
  - `QVI_transaction_data.xlsx`: The transaction data.
  - `QVI_purchase_behaviour.csv`: The customer data.
- /notebooks: Contains the Jupyter Notebooks with the analysis.
  - `Customer_Sales_Analysis.ipynb`: The main notebook with the data exploration, analysis, and visualization.

## Exploratory Data Analysis (EDA)
The project begins with an EDA process, which includes:
- Data Cleaning: Handling missing values, correcting data types, and dealing with outliers.
- Descriptive Statistics: Summarizing key metrics such as total sales, average sales per transaction, and sales distribution.
- Visualization: Using `matplotlib`, `seaborn`, and `plotly.express` to create visualizations that help in understanding the data.

## Key Metrics and Findings
The analysis focuses on the following key metrics:
- Total Sales: The overall revenue generated.
- Sales by Product: Identifying top-selling products.
- Sales by Customer Segment: Analyzing sales based on customer demographics (`LIFESTAGE`, `PREMIUM_CUSTOMER`).
- Sales by Store: Understanding which stores contribute the most to sales.
- Average Sales per Transaction: Analyzing customer spending behavior.
- Sales Trends Over Time: Identifying patterns and seasonality in sales.

## Visualizations
The project includes interactive visualizations created using `plotly.express`, such as:
- Sales by Customer Segment: A bar chart showing sales across different customer segments.
- Sales Trends Over Time: A line chart visualizing how sales have evolved over time.


## How to Run the Project
1. Clone this repository.
2. Ensure the datasets are in the `/data` folder.
3. Open the `Customer_Sales_Analysis.ipynb` notebook in Jupyter.
4. Run the cells in the notebook sequentially to perform the analysis.

## Future Work
- Advanced Modeling: Implement predictive models to forecast future sales and customer behavior.
- Detailed Segment Analysis: Further break down customer segments to provide more granular insights.
- Marketing Strategy Development: Use the insights gained to design targeted marketing strategies.

## Contributors
- Tomiwa Oluwaferanmi: Lead Analyst
