# Cryptocurrency-Price-Predictor
Analyze cryptocurrency time-series data and make price predictions. Below is the model for Ethereum with predictions for the next 15 days as of 3/24/18 (See notebook comments for specific values and caveats).
![picture](ether_prediction.png)

# Features
- MAE Reporting in Dollars
- No need to input data yourself, gets data from CoinMarketCap
- Works with any cryptocurrency on CoinMarketCap

# Tools
- Uses pandas to read historical data from CoinMarketCap and for data manipulation
- Uses Facebook Prophet to fit data and predict trends
