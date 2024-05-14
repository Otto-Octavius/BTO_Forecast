# Forecasting for a Build-to-Order Model Business model

## Overview
I aimed to optimize inventory management for Nasu System, a Mumbai-based company specializing in Airfield ground lighting equipment. My focus was on predicting sales of their most frequently purchased product, Constant Current Regulators (CCRs). Nasu Systems operates on a made-to-order model, and accurately forecasting demand is crucial to prevent inventory shortages or overstocking.

## Techniques Employed
To simplify a complex dataset, I employed various techniques:

- Extracted data from PDFs using OCR.
- Extracted order dates from end-of-line strings.
- Utilized verbal information and KNN imputation for missing data.
- Disregarded customer names, focusing on the role of the buyer.
- Standardized installation site names.
- Split and processed ratings.
- Standardized dates to years.

## Notable Observations
I noted limitations such as historical data only from 1989 to 2018 and low sales to certain clients like IAF and ONGC. I also observed trends like increased sales in smaller airports due to the UDAN scheme and a rise in purchases from airports like Silchar and Raipur.

## Forecasting Models Considered
For forecasting, I considered several models:

- ARIMA (AutoRegressive Integrated Moving Average)
- Dynamic Optimized Theta (DOT)
- AutoETS (Automatic Exponential Smoothing)
- Theta/T2
- ETS (Error, Trend, Seasonality)
- Temporal Fusion Transformer (TFT)
- LSTM (Long Short Term Memory)

Each model has its unique approach to capturing time series data, offering flexibility in handling different patterns and complexities. My thorough analysis and selection of diverse forecasting methods demonstrate a comprehensive approach to address the challenges of demand forecasting for Nasu System's CCRs.
