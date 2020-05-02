# Stock-Evaluator
This is a basic program that recommends a buy, sell, or hold based on the ticker data. 

## Pseudocode

Import historical stock data organized by ticker

Improt ticker profile data

Ask the user what stock ticker they want to evaluate via an inport box

Sett the ticker input as a variable

Identify is the ticker data matches with any ticker information in the historical data

    if the ticker data is available
        find the name of the company
        find the exchange the stock is trading on
        find the provide the market cap
        
        tell the user the name of the company
        tell the user the exchange the stock is traded on
        tell the user the market cap
    
    if the ticker is not there
        tell the user that the data is not available


program will calculate the weekly change in the stock ticker

find the closing price of the last day of the week
find the closing price of the first day of the week

calculate the percentage change in stock price based on the closing prices in the data

evaluate the performance of the stock by determining if it is a sell, hold, or buy

If the stock price increases 10%
    
    print the stock is a buy
    
else if the stock price remains between 0% and 10%

    print the stock is a hold

else 

    print the stock is a sell

    indicate that the stock should be sold
