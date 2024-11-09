# Forex Price Prediction Using Machine Learning

## Objective
The goal of this project is to develop a machine learning model that can predict future forex (foreign exchange) prices based on historical data. The model aims to forecast future price movements, helping traders make informed decisions.

## Project Overview
1. **Data Collection:**
   - Data Source: Yahoo Finance
   - Data Collected: Historical forex data for a specific currency pair (e.g., EUR/USD) from January 2020 to December 2022.

2. **Data Preprocessing:**
   - Converting the 'Date' column to datetime format.
   - Setting the 'Date' column as the index of the DataFrame.
   - Handling missing values, if any.
   - Feature Engineering: Creating new features such as moving averages (e.g., 5-day MA, 10-day MA) to aid in prediction.

3. **Model Development:**
   - Splitting the data into training and testing sets.
   - Selecting and training machine learning models (e.g., Linear Regression, Random Forest, LSTM).
   - Hyperparameter tuning and model optimization.

4. **Model Evaluation:**
   - Evaluating the model’s performance using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared.
   - Comparing different models to choose the best performing one.

5. **Prediction and Visualization:**
   - Making predictions on the test set.
   - Visualizing the actual vs. predicted prices using matplotlib.
   - Plotting moving averages and buy/sell signals based on the model’s predictions.

