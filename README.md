# Bitcoin Time Series Forecasting in R

This project replicates the Bitcoin price time series forecasting analysis originally done by Aditya Mandal in Python. The analysis has been re-implemented in R, leveraging various time series forecasting techniques to predict future Bitcoin prices.

## Overview

- **Data Preprocessing**
- **Visualization**
- **Forecasting Models**
  - ARIMA
  - Prophet
  - LSTM

## Dataset

The dataset used for this analysis can be found on Kaggle:
[Bitcoin Time Series Forecasting Dataset](https://www.kaggle.com/code/someadityamandal/bitcoin-time-series-forecasting/notebook)

## Requirements

To install the necessary R packages, run:

```R
install.packages(c("tidyverse", "plotly", "lubridate", "readr", "dplyr", "zoo", "ggplot2", "forecast", "stats", "tseries"))
