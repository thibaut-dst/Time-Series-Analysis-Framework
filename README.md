# Time Series Analysis Framework - ETS decomposition for additive models


### Project Overview
This notebook provides a framework for performing time series analysis (TSA) on additive models/series. The notebook is designed as a guideline for anyone looking to apply TSA techniques to similar datasets. It showcases data preprocessing, exploration, model building, and compares the performance of a custom decomposition method to that of the built-in decomposition function from Statsmodels, providing insights into their respective effectiveness for time series analysis projects.

### Dataset
The analysis is based on a dataset from the U.S. Energy Information Administration (EIA), which tracks natural gas consumption from the 1990s to the present.

### Analysis Structure
This notebook outlines the following steps for conducting a time series analysis:
1. Data Import and Exploration: Loading the dataset and exploring its structure to understand the temporal trends.
2. Preprocessing: Cleaning and preparing the data for analysis.
3. Time Series Decomposition: Using statistical methods to decompose the time series into its core components: trend, seasonality, and residuals.
4. Comparison with statsmodels built-in decomposition to evaluate effectiveness in extracting trend, seasonality, and residuals.
5. Forecasting Models: Building predictive models like ARIMA and Holt-Winters to forecast future values based on historical data.
6. Visualization: Generating insightful plots to visualize the trends, seasonal patterns, and forecast results.

### Tools and Libraries Used
* Pandas: For data manipulation and preprocessing.
* Matplotlib & Seaborn: For creating visualizations of the time series and forecast.
* Statsmodels: For implementing time series models such as ARIMA and seasonal decomposition.
* Scipy: For statistical testing and model evaluation.

