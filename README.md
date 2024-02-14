# Prophet-Time-Series

# Predicting Avocado Prices using Meta Prophet

## Introduction
This project aims to predict avocado prices using Meta Prophet, an open-source forecasting tool developed by Meta's Core Data Science team. Avocado prices are influenced by various factors such as demand, supply, seasonality, and regional variations. By leveraging historical retail scan data for avocados, we can build a predictive model to forecast future prices.

## Dataset
The dataset used in this project is sourced from Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/konradb/tsdata-1?select=avocado.csv). It contains weekly retail scan data for avocados in 2018, including information such as average price, type (conventional or organic), region, and total volume sold.

The dataset includes the following relevant columns:
- **Date**: The date of the observation
- **AveragePrice**: The average price of a single avocado
- **Type**: Indicates whether the avocado is conventional or organic
- **Year**: The year of the observation
- **Region**: The city or region of the observation
- **Total Volume**: Total number of avocados sold
- **4046**: Total number of avocados with PLU 4046 sold
- **4225**: Total number of avocados with PLU 4225 sold
- **4770**: Total number of avocados with PLU 4770 sold

It's important to note that the dataset only includes data for Hass avocados and does not include other varieties.

## Meta Prophet
Meta Prophet is a forecasting procedure designed for time series data. It fits an additive model that includes non-linear trends, yearly, weekly, and daily seasonality, as well as holiday effects. Prophet is particularly effective for time series data with strong seasonal effects and multiple seasons of historical data.

## Conclusion
Predicting avocado prices using Meta Prophet can provide valuable insights for avocado growers, retailers, and consumers. By understanding price trends and seasonality patterns, stakeholders can make informed decisions related to production, marketing, and purchasing of avocados.
