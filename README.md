This program allows you to input a list of stock and ETF ticker symbols into a Google Sheet. For each ticker entered the program 
will calculate the annualized percentage price changes over the previous 1, 3, 6 and 12 months. 

The program uses closing prices for those dates, these prices are not dividend-adjusted. The prices may be correctly split-adjusted, but I recommend you verify 
this in every case where a stock split has occured.

If you optionally also input a purchase date for a ticker, the program will calculate the annualized percentage price change since the purchase date.

This gives a handy, colour-coded overview of stocks that have a positive price trend over time, versus stocks whose prices are turning negative or have mixed results. 
I think of these results as a momentum dashboard for stock prices.

The dashboard uses Google Sheets for easy input of the ticker symbols and easy display of the annualized percentage price changes over the above time periods. The program 
runs in a Google Sheet script. Using the program assumes you have some knowledge of using Google Sheets and have a Google account.

You can copy the required Google Sheet and script into your Google drive using a link provided to my Google Drive. The link and full instructions on how to load the program, 
modify the stock tickers to those that interest you, and how to run the program are provided in the Github file "the stock momentum dashboard v5 - how to load and use.pdf"

