# Stock Market Data Analysis and VWAP Prediction

This project focuses on analyzing stock market data to predict the **Volume Weighted Average Price (VWAP)** using Python. VWAP is an important metric used to evaluate the price at which a stock has traded throughout the day, weighted by volume. The aim of the project is to forecast future VWAP values and understand market sentiment.

## Key Features:

- **Data Preprocessing:** Cleaned and preprocessed stock market data, handling missing values and setting the 'Date' column as the index.
- **Feature Engineering:** Created lag-based features such as rolling means and standard deviations for key metrics like high, low, volume, and trades.
- **ARIMA Model:** Applied the ARIMA model for time series forecasting, considering autocorrelations in the data.
- **Model Evaluation:** Evaluated the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.

## Steps in the Project:

1. **Data Import & Cleaning:** Loaded and cleaned the stock market data, ensuring no missing values.
2. **Feature Engineering:** Added lag-based features to capture trends and volatility.
3. **ARIMA Model:** Built and trained an ARIMA model for forecasting VWAP.
4. **Model Evaluation:** Assessed the model's accuracy and performance using MAE, MSE, and R-squared.

## Technologies Used:

- **Python**
  - Libraries: `Pandas`, `NumPy`, `Seaborn`, `sklearn`
- **ARIMA for time-series forecasting**

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-market-vwap-prediction.git
## Install the required packages:

bash


Copy code

  ```pip install -r requirements.txt  ```

Run the script:

  ``` python .py  ```   
 

## Evaluation Metrics:
Mean Absolute Error (MAE): Measures the average absolute difference between predicted and actual values.
Mean Squared Error (MSE): Squares the error to penalize large deviations.
R-squared: Represents the proportion of variance explained by the model, with values close to 1 indicating good model performance.
Insights:
The ARIMA model performs well with an R-squared of 0.93, meaning it explains 93% of the variance in VWAP.
MAE and MSE suggest room for improvement, particularly in reducing larger prediction errors.
Future Work:
Tune ARIMA parameters to optimize prediction accuracy.
Explore other time-series models (e.g., SARIMA, Prophet) for better forecasting.
Add more features, such as sentiment analysis from news articles, for enhanced predictions.
