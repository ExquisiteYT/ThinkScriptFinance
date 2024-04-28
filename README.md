# ThinkScriptFinance
Using mathematics for active financial analysis w/ various data points.
# ThinkScriptFinance
Using mathematics for active financial analysis w/ various data points.

252D Historical Volatility SD Pivot Point Movements: 
TastyTrade, at tastylive.com has documented Implied Volatility moves via Standard Deviation using the following formula known as 1SD Expected Move: 

Close Price x IV x (SQRT(DTE/365))
Close Price: Closing price of the previous data at the end of NYSE market hours. 
IV: 252 Day Historical Volatility Figure. In this case, using the Historical Volatility metric in thinkorswim and specifically using 252 will calculate the moving 252 day HV. 
DTE: Days to Expiration of your Option Contract

Additional Resource for EM: https://www.tastylive.com/concepts-strategies/standard-deviation

The code is to be only used when the candles are 1 Day in size. You can use other charting platforms; Webull, TradingView, Quantower, TrendSpider to Look on lower timeframes. 

Link to the chart on TOS: https://tos.mx/OI3ylW5
I'll attach a few pictures. The script includes boxes at the top of the chart to show the Standard Deviation Moves up to 3 SD. This can be applied to any security, but has currently only been tested on SPX and the the Top 10 highest weighted stocks within the S&P500. ![image](https://github.com/ExquisiteYT/ThinkScriptFinance/assets/58378760/9020086d-0b16-4c98-b84c-ed458e2495fb)


To change the ticker for the script, you will need to enter study settings in thinkorswim to change the ticker, along with the ticker for the charts on TOS. ![image](https://github.com/ExquisiteYT/ThinkScriptFinance/assets/58378760/a2b1a086-f919-41a0-ad3d-5866035e8f36)

MSFT: ![image](https://github.com/ExquisiteYT/ThinkScriptFinance/assets/58378760/da7f9199-568d-40f3-89b3-5e3f94a9078f)

SPX on Webull: ![image](https://github.com/ExquisiteYT/ThinkScriptFinance/assets/58378760/1f66d53e-1e88-48f8-aa99-ddcbe7d7a7de)

MSFT on Webull: ![image](https://github.com/ExquisiteYT/ThinkScriptFinance/assets/58378760/c216e394-6a24-43db-a539-af051c6b7694)
