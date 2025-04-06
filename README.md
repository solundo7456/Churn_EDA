# Churn_EDA
Exploratory Data Analysis (EDA) for Customer Churn
This repository contains the code and visualizations for conducting Exploratory Data Analysis (EDA) on a customer dataset to understand the factors influencing customer churn. The analysis focuses on key variables such as price sensitivity, electricity consumption, and customer behavior.

Project Overview
The goal of this project is to explore the relationship between various factors and customer churn, with an emphasis on price sensitivity across different time periods (e.g., off-peak, peak, and mid-peak pricing). The analysis leverages customer data, consumption history, and pricing data to visualize and identify trends and patterns that may indicate a higher likelihood of churn.

Key Features:
Churn Analysis: Identifying customers who have churned and comparing them with those who have not.

Price Sensitivity: Investigating how different price periods (off-peak, peak, mid-peak) relate to customer churn.

Consumption Patterns: Exploring the relationship between electricity consumption and customer churn.

Churn Predictors: Analyzing which factors (e.g., pricing, consumption, contract length) may predict customer churn.

Dataset Description
This analysis uses two datasets:

1. Client Data (client_data.csv)
Contains information on client company identifiers, contract details, consumption history, and churn status.

id: Client company identifier

activity_new: Category of the company’s activity

channel_sales: Sales channel code

cons_12m: Electricity consumption over the past 12 months

forecast_cons_12m: Forecasted electricity consumption for the next 12 months

forecast_discount_energy: Forecasted energy discount

has_gas: Indicates if the client is also a gas client

churn: Whether the client churned (1) or not (0)

2. Price Data (price_data.csv)
Contains price information for energy and power during different periods (off-peak, peak, and mid-peak).

id: Client company identifier

price_off_peak_var: Price of energy during the off-peak period

price_peak_var: Price of energy during the peak period

price_mid_peak_var: Price of energy during the mid-peak period

price_off_peak_fix: Fixed price of power during the off-peak period

price_peak_fix: Fixed price of power during the peak period

price_mid_peak_fix: Fixed price of power during the mid-peak period

Setup and Installation
