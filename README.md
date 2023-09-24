# Forecasting Median House Sales in NJ, USA

## Overview

This project uses time series forecasting techniques to forecast the median house sales in New Jersey, USA. The data used in this project is obtained from Zillow's listing data for properties in New Jersey. The main objective is to identify the best forecasting method for the given time series data and accurately predict future median house prices.

## Data Source

The data used in this project can be found at [Zillow Research Data](https://www.zillow.com/research/data/#median-home-value). The dataset contains monthly median listing prices of properties in New Jersey from 1996 to the present.

## Data Dictionary

YYYY-MM: Year and Month during with the data was recorded
Value: Median Listing Price of properties in New Jersey, USA

## Hypothesis

The hypothesis is that house pricing increases with time, indicating a time series with an increasing trend. We will explore various forecasting methods and test their accuracy to identify the most suitable method for this data type. The Holt-Winters method is hypothesized to be the best for this data due to the observed increasing trend and possible seasonality.

## Analysis Steps

1. Data Preprocessing: Load and preprocess the dataset, handle missing values and convert the date column to a time series.
2. Data Visualization: Visualize the time series data to identify trends and seasonality.
3. Time Series Decomposition: Decompose the time series into trend, seasonality, and residual components.
4. Forecasting Models:
   - Naive Method: A baseline model to establish a benchmark.
   - Simple Moving Averages: Implement moving averages of different orders (3, 6, and 9) and compare the results.
   - Simple Exponential Smoothing: Apply simple exponential smoothing and evaluate its performance.
   - Holt-Winters Method: Implement the Holt-Winters method with additive seasonality and assess accuracy.
5. Model Evaluation: Compare the models' forecast accuracy and select the best-performing one.
6. Forecasting Future Values: Use the selected model to forecast future median house sales in New Jersey.

## Dependencies

The project uses the following libraries in R for data analysis and forecasting:

- `fpp`: Forecasting functions
- `fpp2`: Forecasting functions and datasets
- `TTR`: Technical Trading Rules
- `ggplot2`: Data visualization
- `readr`: Data reading
- `dplyr`: Data manipulation

## File Dictionary

- The Rmd file contains the code for the entire analysis
- The html and PDF give the code output
- A brief analysis report has also been included

## Authors

- Ajay Vishnu Addala

