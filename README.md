# London Skies - Air Quality Analysis

Time series analysis of NO2 (nitrogen dioxide) levels across London's top 5 monitoring sites, using data from 2010 to 2023.

## Article

For a detailed walkthrough of this analysis, see the accompanying Medium article: [A Foray Into Time Series](https://medium.com/@aliakil87/a-foray-into-time-series-4e22e51cd708)

## Dataset

The analysis uses `london_air_quality_2010_2023_top5_sites.csv` (not included in the repo due to size). The dataset contains hourly NO2 readings from sites including Camden - Bloomsbury.

## Analysis

- Exploratory data analysis of NO2 trends
- Daily resampling and seasonal decomposition
- Stationarity testing (Augmented Dickey-Fuller)
- ACF/PACF analysis
- AutoRegressive modelling
- Model evaluation (MAE, RMSE, MAPE)

## Requirements

- Python 3.11+
- pandas
- matplotlib
- seaborn
- statsmodels
- scikit-learn
