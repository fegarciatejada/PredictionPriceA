# Predicting Avocado Prices Using Facebook Prophet

## Project Overview

This project aims to forecast weekly avocado prices using historical retail scan data. By leveraging Facebook's Prophet forecasting tool, we aim to model the price trends of Hass avocados in various regions, considering factors like sales volume and type (conventional or organic).

### Problem Statement

The dataset encompasses weekly retail scan data for 2018, detailing national retail volume (units) and price for Hass avocados. The data, reflecting actual sales from retailers’ cash registers, provides insights into the average price per unit, sales volume by PLU codes, and the distinction between conventional and organic types.

### Dataset Summary

Key columns in the dataset include:
- **Date**: The observation date.
- **AveragePrice**: The average price of a single avocado.
- **Type**: Whether the avocado is conventional or organic.
- **Year**: The observation year.
- **Region**: The city or region of the observation.
- **Total Volume**: Total avocados sold.
- **4046, 4225, 4770**: Sales volume for avocados with specific PLU codes.

## Technologies Used

- Python 3.x
- Pandas: For data manipulation.
- NumPy: For statistical analysis.
- Matplotlib & Seaborn: For data visualization.
- Facebook Prophet: For time series forecasting.
