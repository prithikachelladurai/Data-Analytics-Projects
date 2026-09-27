# Supply Chain & Delivery Performance Analytics

## Project Overview

This project focuses on analyzing supply chain orders and delivery performance using Python.

The main objective is to analyze order data, delivery status, delays, shipping costs, warehouses, carriers, and regions to identify delivery performance and operational issues.

Machine Learning models were also implemented as an additional part of the project to classify delivery performance.

## Objectives

- Analyze overall order and delivery performance
- Identify delayed and on-time deliveries
- Analyze warehouse and regional performance
- Study shipping cost and delivery delays
- Identify operational bottlenecks
- Generate meaningful KPIs and business insights
- Apply Machine Learning as an additional analysis

## Dataset

The dataset contains 2,000 order records with the following attributes:

- Order ID
- Order Date
- Warehouse
- Region
- Promised Date
- Delivered Date
- Carrier
- Shipping Cost
- Status
- Order Quantity
- Weight (kg)
- Delay

Additional features were created during the analysis, such as:

- Delivery Days
- Delay Days
- On-Time Flag
- Delivery Class

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Data Analysis

The project includes:

- Data loading and understanding
- Data cleaning
- Missing value analysis
- Duplicate checking
- Feature engineering
- KPI calculation
- Warehouse-wise analysis
- Region-wise analysis
- Carrier-wise analysis
- Monthly delivery analysis
- Delay analysis
- Shipping cost analysis
- Data visualization

## Key KPIs

The project calculates important KPIs such as:

- Total Orders
- Delivered Orders
- Cancelled Orders
- On-Time Orders
- On-Time Delivery Percentage
- Average Delay
- Average Shipping Cost

## Machine Learning

Machine Learning was implemented as an additional part of the Python project.

The objective was to classify delivery performance based on order-related features.

The following models were explored:

- Logistic Regression
- Decision Tree
- Random Forest

Model performance was evaluated using:

- Accuracy
- Classification Report
- Precision
- Recall
- Confusion Matrix

## Business Insights

The analysis helps identify:

- Delivery delay patterns
- Warehouse-level performance
- Regional delivery performance
- Carrier-related delivery issues
- Shipping cost patterns
- Orders requiring attention

## Project Structure

```text
Supply_Chain_Delivery_Performance_Analytics/
│
├── README.md
├── Supply_Chain_Delivery_Performance_Analytics.ipynb
└── supply_chain_orders.csv
