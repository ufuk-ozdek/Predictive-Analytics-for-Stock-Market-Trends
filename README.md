# **Predictive Analytics For Stock Market Trends**

## **Project Description**

This project aims to build a predictive model for stock market trends using historical data. By leveraging Support Vector Regression (SVR) and advanced feature engineering, the project forecasts future stock prices for major companies like AAPL, MSFT, and GOOGL. The model is trained on data from 2020 to 2023 and incorporates features such as moving averages, momentum, and volatility.


## **Features**
+ **Data Collection:** Historical stock data fetched using the Yahoo Finance API.
+ **Preprocessing:** Handling missing data, outlier capping, and normalization.
+ **Feature Engineering:** Calculation of moving averages, momentum, volatility, and RSI.
+ **Modeling:** Tuning SVR with Grid Search for optimal performance.
+ **Evaluation:** Cross-validated RMSE, MSE, R-squared, and MAE metrics.
+ **Visualization:** Actual vs Predicted Prices, Residuals, and Feature Importance.

## Installation

To run this project locally, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/ufuk-ozdek/PredictiveAnalyticsForStockMarketTrends.git
cd PredictiveAnalyticsForStockMarketTrends
pip install -r requirements.txt
```

## **Requirements**
+ Python 3.x
+ pandas
+ numpy
+ matplotlib
+ scikit-learn
+ yfinance
+ shap

## **Results**

### - **AAPL**
  - Cross-Validated RMSE: 0.020787572189560993
  - MSE: 0.00047610138101505836
  - R-squared: 0.9410327633319528
  - MAE: 0.01619349333426411


<img src="https://github.com/user-attachments/assets/1fa2c057-382f-47d7-9bf7-28c69e60e105" alt="Residuals Over Time - APPL" width="500"/>

<img src="https://private-user-images.githubusercontent.com/70910355/366236168-04ada71e-a46a-49f1-92d5-c4bcb41534d6.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjYwMDc3NzksIm5iZiI6MTcyNjAwNzQ3OSwicGF0aCI6Ii83MDkxMDM1NS8zNjYyMzYxNjgtMDRhZGE3MWUtYTQ2YS00OWYxLTkyZDUtYzRiY2I0MTUzNGQ2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA5MTAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwOTEwVDIyMzExOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWJkMWUzMTE3NzVkYzZkZWMxZjM4YzBjOWEyZTMwYjEyMzFjMmQwMDUyZjA4OTI5NzljZDg2OTEzODdhODM0MmQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.xYF3MCyRhIW1MV77FWBjWm23tJgpdJXhfInBZOwCEYg" alt="Residuals Over Time - APPL" width="500"/>
<img src="https://github.com/user-attachments/assets/3553b856-b387-4fc6-95ae-04920944e4cc](https://private-user-images.githubusercontent.com/70910355/366236199-1862548d-c58d-4a63-8ae0-dde026841d8f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjYwMDc3NzksIm5iZiI6MTcyNjAwNzQ3OSwicGF0aCI6Ii83MDkxMDM1NS8zNjYyMzYxOTktMTg2MjU0OGQtYzU4ZC00YTYzLThhZTAtZGRlMDI2ODQxZDhmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA5MTAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwOTEwVDIyMzExOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTYwMjA1MjdhZDJhMjQwYzFjYTY1YWM0MzNlOTk5YjAyMWU3NjU5OGY1MjdiNGY0MmY2NGExZmZiZDcyZWQxZmMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0._nJtMAWnM5sZfYg9cjWh-NmhvVJPloD55liI4v9sR48" alt="SHAP Summary Plot for SVR Model Feature Importance - APPL" width="500"/>


### - **MSFT**
  - Cross-Validated RMSE: 0.02198693771508212
  - MSE: 0.000721419433017819
  - R-squared: 0.9011299167486935
  - MAE: 0.020551217144603215
 
<img src="https://github.com/user-attachments/assets/020741b1-976e-46d9-aab5-7800532081c9" alt="Actual vs Predicted Stock Prices - MSFT" width="500"/>
<img src="https://github.com/user-attachments/assets/f14458e2-bd40-4ba4-b607-c845dae96a2c" alt="Residuals Over Time - MSFT" width="500"/>
<img src="https://github.com/user-attachments/assets/560918dc-dc3e-4185-96d4-14d424c69aad" alt="SHAP Summary Plot for SVR Model Feature Importance - MSFT" width="500"/>


### - **GOOGL**
  - Cross-Validated RMSE: 0.020347820042779595
  - MSE: 0.0005246558453682764
  - R-squared: 0.9503088334942307
  - MAE: 0.018224233848984688
 
<img src="https://github.com/user-attachments/assets/d14dc0e3-3b2b-4eff-8200-6ec3c524f374" alt="Actual vs Predicted Stock Prices - GOOGL" width="500"/>
<img src="https://github.com/user-attachments/assets/f14458e2-bd40-4ba4-b607-c845dae96a2c" alt="Residuals Over Time - GOOGL" width="500"/>
<img src="https://github.com/user-attachments/assets/560918dc-dc3e-4185-96d4-14d424c69aad" alt="SHAP Summary Plot for SVR Model Feature Importance - GOOGL" width="500"/>



  
## Future Work
+ Integrate additional machine learning models like LSTM.
+ Extend the project to forecast multiple stocks simultaneously.
+ Deploy the model via a web application using Flask or Django.
