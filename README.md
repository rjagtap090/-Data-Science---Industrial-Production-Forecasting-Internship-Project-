Project Title: Industrial Production Forecasting using ARIMA and SARIMA
Project Overview
This project aims to develop and evaluate time-series forecasting models to predict industrial production for the next two years. The models used include ARIMA and SARIMA, and the best model is selected based on mean squared error.

Dataset
The dataset consists of monthly industrial production data. It is assumed to be in a CSV file named industrial_production.csv with two columns: Date and Production.

Steps Involved
Data Preprocessing:

Load the dataset and visualize the time-series data.
Check for stationarity using the Augmented Dickey-Fuller test.
Perform differencing if necessary to make the data stationary.
Train-Test Split:

Split the data into training (80%) and testing (20%) sets.
Modeling:

Fit an ARIMA model to the training data.
Fit a SARIMA model to the training data.
Forecasting:

Use both ARIMA and SARIMA models to forecast the testing set.
Calculate and compare the mean squared error of both models to determine the best one.
Future Forecast:

Use the best model to forecast industrial production for the next two years (24 months).
Requirements
Python 3.x
Libraries: pandas, numpy, matplotlib, statsmodels, sklearn
Installation
Install the required libraries using pip:

bash
Copy code
pip install pandas numpy matplotlib statsmodels sklearn
Usage
Load the dataset:
Ensure your dataset (industrial_production.csv) is in the same directory as the script or provide the correct path.

Run the script:
Execute the Python script to perform the analysis and generate forecasts.

Visualize Results:
The script will display various plots showing the train-test split, model forecasts, and future predictions.
