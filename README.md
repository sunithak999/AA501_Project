#### Data Collection
[Data Collection](https://github.com/sunithak999/AA501_Project/blob/main/AAI_501_stock_predict.ipynb)


Description below for the data collection based on selected stock symbol. 
When you run the code, program will ask for stock symbol. Enter for example "goog"
Next it will ask for what type of data is required. Select any of the choices below. Omce the choice is selected, csv file for each 
catagory is created.

Before running the program, Make sure you update the path to you local path for saving the csv file "mypath"

Choice 1 - Intraday (5-minute interval)
You are correctly fetching intraday data at 5-minute intervals. The relevant time series data will be in the 'Time Series (5min)' key in the response.

Choice 2 - Daily
Fetches daily data from Alpha Vantage, located in the 'Time Series (Daily)' key.

Choice 3 - Daily Adjusted
Fetches daily adjusted data, but based on your test and feedback earlier, you might need to check that the correct data is being returned in 'Time Series (Daily Adjusted)'. This should now be correctly handled in the code.

Choice 4 - Weekly
Fetches weekly data from the 'Time Series (Weekly)' key in the response.

Choice 5 - Weekly Adjusted
Fetches weekly adjusted data from the 'Weekly Adjusted Time Series' key in the response.

Choice 6 - Monthly Adjusted
Retrieves monthly adjusted data from the 'Monthly Adjusted Time Series' key in the response.

Choice 7 - Global Quote
Fetches the latest global quote data for the symbol, which contains information like current price, open, high, low, and volume. This data is stored in the 'Global Quote' key.

Choice 8 - Insider Transactions
Retrieves insider transactions data (if available) under the 'data' key in the response. If no data is available, it will notify the user.

Choice 9 - Earnings
Handles both quarterly and annual earnings, which are stored in the 'quarterlyEarnings' or 'annualEarnings' keys. It saves the corresponding data into CSV files if available.

Choice 10 - Overview
Fetches the overview data of a company (e.g., name, sector, industry, market cap) under the 'Overview' key. It saves this data into a text file.
##### Data
 * All data download are present under ./data folder in csv format

##### Exploratory Analysis

##### SARIMA Model

##### LSTM
[LSTM Model](https://github.com/sunithak999/AA501_Project/blob/main/AA501_LSTM.ipynb)

####  Presentation Link


