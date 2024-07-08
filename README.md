# Retail Sales Analysis and Customer Churn Prediction

## Overview

This project demonstrates an integrated approach to analyzing retail sales data and predicting customer churn using both Power BI for visual analytics and Python for machine learning. The project is divided into two main sections:

1. **Power BI Dashboards**: Visualizing product analysis and retailer performance.
2. **Python Jupyter Notebook**: Implementing churn prediction and price optimization using logistic regression and linear regression.

## 1. Power BI Dashboards

### Retailer Performance Dashboard

This dashboard provides insights into the performance of different retailers, helping to identify top-performing retailers and understand sales distribution across various channels.

#### Key Features:
- **Retailer Comparison**: Comparative analysis of sales performance across different retailers.
- **Sales Channels**: Breakdown of in-store and online sales for each retailer.

### Product Analysis Dashboard

This dashboard focuses on product sales, allowing for an in-depth analysis of various product categories and identification of top-selling products.

#### Key Features:
- **Product Categories**: Bar charts comparing sales across different product categories (e.g., Men's Footwear, Women's Apparel).
- **Top Products**: Identification and highlighting of top-selling products.
- **Price vs. Volume**: Scatter plot showing the relationship between price per unit and units sold.

## 2. Python Jupyter Notebook

### Overview

The Python Jupyter Notebook covers two main analyses: churn prediction and price optimization. These analyses are essential for understanding customer behavior and optimizing pricing strategies to maximize revenue.

### Churn Prediction

#### What is Churn Prediction?

Churn prediction involves identifying customers who are likely to stop using a product or service. This is crucial for businesses to proactively address customer retention and reduce turnover.

#### Logistic Regression

Logistic regression is a statistical method used for binary classification problems. It predicts the probability of an event occurring, such as whether a customer will churn or not, based on input features.

#### Project Implementation

- **Data Preprocessing**: Cleaning and preparing the data for analysis.
- **Model Training**: Using logistic regression to train the churn prediction model.
- **Evaluation**: Assessing the model's performance using accuracy, precision, recall, and other metrics.
- **Results Interpretation**: Understanding which factors influence customer churn the most.

### Price Optimization

#### What is Price Optimization?

Price optimization involves determining the best pricing strategy to maximize revenue and profitability. This analysis helps businesses set prices that balance demand and profitability.

#### Linear Regression

Linear regression is a method to model the relationship between a dependent variable and one or more independent variables. It is used to understand how changes in price impact demand.

#### Project Implementation

- **Data Preprocessing**: Cleaning and preparing the data for regression analysis.
- **Model Training**: Using linear regression to analyze the relationship between price and demand.
- **Evaluation**: Assessing the model's accuracy and goodness of fit.
- **Results Interpretation**: Determining optimal pricing strategies based on the model.

## Results

- **Power BI Dashboards**: Provide an intuitive interface to analyze sales data, compare product categories, and evaluate retailer performance.
- **Machine Learning Models**: The churn prediction model accurately identifies customers at risk of churning, and the price optimization analysis provides actionable insights for setting optimal prices.

## Getting Started

### Prerequisites

- **Power BI**: To view and interact with the dashboards, you will need Power BI Desktop installed.
- **Python**: Ensure you have Python 3.x installed along with the necessary libraries (e.g., pandas, scikit-learn, matplotlib).



### Usage

1. **Power BI Dashboards**:
    - Open the `US_Sales_data_dashboard.pbix` file in Power BI Desktop.
    - Interact with the visualizations to explore the sales data.

2. **Python Notebook**:
    - Open the `sales_data_analysis.ipynb` file in Jupyter Notebook or JupyterLab.
    - Run the cells to see the data analysis, model training, and results.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.



## Acknowledgements

- Thanks to the data science and business intelligence communities for their valuable resources and inspiration.
