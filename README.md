# stock-prediction
ML algorithms:

python/ML-algorithms-stock-prediction.ipynb

Cods Rational: 
The cods are based on indicators such as  Bollinger Bands, Relative Strength Index(RSI which are technical analysis tools that investors and traders use .  The indicators analyze the historic data in order to draw patterns and forecast future price trends. The followings lines elaborate the above-mentioned indicators. 

The Relative Strength Index (RSI)
This indicator measures the fluctuations of recent price changes to evaluate overbought or oversold conditions for a particular stock of choice. 
Conventionally,  the RSI are at that values of 70 or above are seen as overbought, suggesting that a stock may be ready for a corrective pullback or a reversal in price, and should be sold.  In contrary, values of 30 or below suggest an oversold/undervalued stocks, and should be purchased. 
Traders use these bands along with the constructed trend-based indicator to identify the market state and make potential to buy and sell stocks. Oscillators are usually used for short-term trading purposes, but there are no restrictions on using them for long-term investments.
RSI can be used in the construction of a portfolio. It accurately predicts the buy and sell signals for various stocks. RSI usually predicts the future trend of the stocks successfully. Below is the link to the reference paper.
https://www.ripublication.com/ijaer17/ijaerv12n19_124.pdf
There are three steps of calculation of RSI.
•	Calculating the Exponential Moving Average (EMA) of the gain and loss of an asset: EMA is a type of Moving Average (MA) that automatically allocates more weighting to the most recent data point and lower weighting to data points in the distant past. In this step, we will first compute the returns of the asset and separate the gains from losses. The two EMAs for a defined number of periods are calculated by these separated values.
•	Calculating the Relative Strength of an asset: It is calculated by dividing the Exponential Moving Average of the gain of an asset by the Exponential Moving Average of the loss of an asset for a determinate number of periods. 
•	Calculating the RSI values: the RSI is calculated by making use of the Relative Strength values which was calculated in the previous step.  

Bollinger bands:
Bollinger Bands is a type of technical indicator that helps traders to analyze the volatility of a stock and whether the price is high or low on a relative basis. The top band is usually two standard deviations above the SMA, and the bottom band is usually two standard deviations below the SMA. 
There are three steps of calculation of Bollinger Bands:
•	Calculating the SMA (Simple Moving Average) of a stock.
•	Calculating two standard deviations away from the SMA
•	Creating Bollinger Bands



