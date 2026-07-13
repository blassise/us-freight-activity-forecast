# Forecasting U.S. Freight Activity

## Project Objective

This project uses the Bureau of Transportation Statistics Freight Transportation Services Index to forecast short-term U.S. freight activity.

The goal is to evaluate how accurately a SARIMA time series model can predict future freight activity using historical monthly data.

## Data Source and Preparation

The analysis uses the Freight Transportation Services Index from the U.S. Bureau of Transportation Statistics.

The dataset contains **317 monthly observations** covering **January 2000 through May 2026**. The analysis uses two fields:

- `OBS_DATE`: Monthly observation date
- `TSI_Freight`: Freight Transportation Services Index

The date field was converted to a datetime format and used as the time-series index. The dataset was also checked for missing values before beginning the analysis.

## Historical Freight Activity

The dataset contains monthly Freight Transportation Services Index observations from January 2000 through May 2026. The historical series shows long-term growth in U.S. freight activity, along with periods of significant disruption and recovery.

![Historical U.S. Freight Transportation Services Index](freight_tsi_history.png)
