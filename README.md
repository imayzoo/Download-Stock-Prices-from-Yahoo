# Download Stock Prices from Yahoo
This script downloads historical daily price data from Yahoo Finances, and makes a csv file. Since Yahoo changed its API is dificult to dowload data, this is a simple script that allows to dowload historical data automatically with Python.

## Example:
You need to change the next values 
```
nombre = 'AAPL'
inicial = '2017-9-1'
final = '2018-12-31'
```
* nombre = name of stock, Apple Inc = APPL
* inicial = start date
* final = end date

### Prerequisites
libraries
```
requests
re
json
time
```

