# Data-Analysis-Cryptocurrency

A data analysis project utilising numpy, pandas, matplotlib and more to analyse historical cryptocurrency prices with respect to the Bitcoin halvings, cycle extrema, and sentimental indicators.

In the notebook (.ipynb file) we study Bitcoin (and other cryptocurrencies) price with respect to various factors, including stage in the cycle, and sentimental indicators. 

In part 1 we will analyse Bitcoin price at various points into each cycle, and try to spot any patterns between price and the stage in the cycle. 

In part 2 we will look at "altcoins" (cryptocurrencies other than Bitcoin) and assess their performance by measuring the price increase from the lowest to the highest point in the cycle. 

Finally, in part 3, we take a look at the relationship between Bitcoin price and the Fear and Greed Index, a sentimental indicator measuring how fearful or greedy investors are about the cryptocurrency market.

Techniques used in this project include working with .csv files, performing data analysis using numpy and pandas, and creating visualisations using matplotlib. Much of the data used was obtained by use of APIs, and the code used for this is included (but commented out, to avoid excessive calls).

## To run:

To run the contents of the notebook yourself in full, you will have to obtain CoinGecko and CryptoCompare API keys. These are both free. Once obtained, the keys should be added to the relevant row of the "APIkeys.csv" file. The packages/modules needed are fairly standard for data analysis and include csv, pandas, numpy, matplotlib, datetime, requests, scipy, and some others.


