# Gold Futures Historical Data Analysis and Prediction

This project analyzes historical gold futures data and builds a predictive model to forecast future prices. It uses various machine learning techniques, including Linear Regression, Random Forest, XGBoost, and ARIMA, to achieve this goal.

## Project Overview

The project is structured into the following steps:

1. **Data Acquisition:** Loads historical gold futures data from a CSV file.
2. **Data Cleaning and Preprocessing:** Cleans and prepares the data for analysis, including handling missing values, converting data types, and formatting.
3. **Exploratory Data Analysis (EDA):** Explores the data through visualizations and statistical analysis to understand trends, patterns, and relationships.
4. **Feature Engineering:** Creates new features from existing data to improve model accuracy. This includes technical indicators like moving averages, RSI, and Bollinger Bands.
5. **Data Preparation for Modeling:** Splits the data into training and testing sets, scales the features, and prepares the target variable.
6. **Model Building and Evaluation:** Builds and evaluates multiple predictive models (Linear Regression, Random Forest, XGBoost).
7. **Time Series Forecasting with ARIMA:** Builds an ARIMA model for time series forecasting.
8. **Future Price Prediction:** Uses the best performing model to generate predictions for future gold prices.
9. **Trading Strategy Simulation:** Simulates a simple trading strategy based on moving average crossovers.
10. **Conclusion and Recommendations:** Provides conclusions based on the analysis and makes recommendations for future actions.
11. **Model and Results Saving:** Saves the best performing model and the results for future use.
12. **Function for Reusing the Model:** Provides a function to load the saved model and make predictions on new data.

## Getting Started

To run this project, you will need:

- Python 3.x
- Jupyter Notebook or Google Colab
- Required libraries (pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, statsmodels)

**Steps:**

1. Clone this repository to your local machine.
2. Install the necessary libraries.
3. Open the Jupyter Notebook or Google Colab and run the cells in order.
4. You can modify the input data, model parameters, and trading strategy as needed.

## Results

The project provides:

- Visualizations of historical gold prices, trends, and technical indicators.
- Evaluation metrics for the different predictive models.
- Predictions for future gold prices.
- Simulation results of a trading strategy.
- Conclusions and recommendations based on the analysis.

## Disclaimer

This project is for educational and informational purposes only. The predictions and trading strategy should not be considered financial advice. Invest at your own risk.
