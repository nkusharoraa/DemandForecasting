# Demand Forecasting Using Time Series Analysis and Exponential Smoothing

## Project Overview

Demand forecasting plays a critical role in supply chain management by predicting future demand patterns, optimizing inventory levels, and improving overall operational efficiency. This project aims to develop a demand forecasting model using time series analysis techniques and exponential smoothing methods, specifically focusing on Holt-Winters forecasting.

## Objectives

1. **Data Collection and Preparation**: Gather historical demand data for a specific product or product category.
2. **Time Series Analysis**: Perform exploratory data analysis (EDA) and visualize the demand data to understand trends, seasonality, and any patterns present.
3. **Exponential Smoothing Models**:
   - Implement Simple Exponential Smoothing (SES) to create a baseline forecast.
   - Apply Holt’s Linear Trend Model to incorporate trend components into the forecast.
   - Extend the model with Holt-Winters Seasonal Method to handle both trend and seasonal variations in the data.
4. **Model Evaluation**:
   - Evaluate the forecasting accuracy of each model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
   - Compare the performance of SES, Holt’s Linear Trend Model, and Holt-Winters Method in capturing demand variability.
5. **Forecasting and Visualization**:
   - Generate demand forecasts for future time periods using the best-performing model.
   - Visualize the forecasted values alongside historical data to assess the model's accuracy and reliability.
6. **Implementation and Documentation**:
   - Implement the selected forecasting model using Python, documenting the code, assumptions, and methodology used.
   - Prepare a detailed report summarizing the project, including data insights, model performance, and recommendations for operational decision-making.


## Skills Utilized

- Time series analysis
- Exponential smoothing techniques (SES, Holt’s Linear Trend Model, Holt-Winters Method)
- Data visualization for demand patterns and forecasts
- Model evaluation and performance metrics
- Python programming for data analysis and forecasting implementation

## Potential Impact

- Improved accuracy in demand forecasting leading to optimized inventory management and reduced stockouts.
- Enhanced decision-making capabilities for supply chain planning and resource allocation.
- Scalable model framework applicable to various product categories or markets within the organization.

## Example

![image](https://github.com/nkusharoraa/SCM/assets/59050030/4a96610b-39d2-4fdb-a1f3-216686a72256)
```
SES - MSE: 4685.333229537704, MAE: 59.130087580002304
Holt's Linear - MSE: 14436.43263139262, MAE: 120.05214670003323
Holt-Winters - MSE: 13515.621086377456, MAE: 116.2499829017769
```

## Visualization Insights

The visualization of the actual demand versus the forecasted values helps in assessing the model's performance visually.
SES Forecast: Shows how well the simple exponential smoothing captures the overall trend without considering seasonality.
Holt's Linear Forecast: Illustrates the trend component more accurately but may still miss seasonal patterns.
Holt-Winters Forecast: Typically provides the most accurate representation by accounting for both trend and seasonality, making it ideal for products with clear seasonal demand patterns.

### Prerequisites

Ensure you have the following libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `statsmodels`
- `sklearn`

You can install them using:
```bash
pip install pandas numpy matplotlib statsmodels scikit-learn
