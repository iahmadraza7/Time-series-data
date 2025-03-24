# Time-series-data
You have been provided with a dataset containing historical stock prices of a company. Your task  is to build a machine learning model to predict the stock price of the company using Linear  Regression and ARIMA


Tasks1:  
1.  Load the dataset into a Pandas DataFrame. 
2.  Rename the column 'Close(t)' to 'Close'. 
3.  Display the first 5 rows using the head() function. 
4.  Display the last 5 rows using the tail() function. 
5.  Check the number of rows and columns using the shape function. 
6.  Print the column names. 
7.  Plot a Time Series chart for AAPL stock prices (line plot between time and price). 
8.  Remove unnecessary columns (e.g., 'Date'). 
9.  Define Close_forecast as the target variable, which is the price for the next day. 
10. Split the data into training, validation, and test sets. 
11. Apply linear regression using the LinearRegression function from the sklearn 
library. 
12. Print the linear regression coefficient and intercept. 
13. Evaluate the model’s performance on the training, validation, and test datasets 
using: 
●  Mean Absolute Percentage Error (MAPE] 
●  Mean Squared Error (MSE) 
●  Root Mean Squared Error (RMSE) 
●  R-Squared Score 
 
Tasks2(ARIMA):  
●  Import libraries: pandas, matplotlib, numpy, statsmodels, sklearn. 
●  Load stock data with pd.read_csv(). 
●  Rename columns as needed. 
●  Add titles, labels, and grid. 
●  Drop unnecessary columns (e.g., Date_col). 
●  Define target variable (Close). 
●  Split data chronologically: 88% for training, 10% for validation, 2% for test. 
●  Print dataset lengths. 
●  Define ARIMA model with parameters (e.g., p, d, q). 
●  Fit ARIMA model to training data. 
●  Print ARIMA summary. 
●  Generate predictions for training, validation, and test sets using arima_model.predict(). 
●  Calculate R-squared, MAPE, MSE, RMSE, and MAE. 
●  Use sklearn.metrics to evaluate performance. 
●  Plot actual vs predicted values for validation and test sets. 
●  Add legends, titles, and axis labels. 
●  Analyze residuals of the model. 
●  Adjust ARIMA parameters (p, d, q). 
●  Refit model and check predictions. 
●  Ensure the model performs well on test data. 
●  Review predictions and actual values. 
●  Optimize ARIMA parameters using grid search or other techniques (optional). 
●  Evaluate the final model on test data and ensure good generalization.
