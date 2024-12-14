# non_price_data_handling

# DataSource Site
## CryptoQuant
- All datasource with short description. [Full Catalog](https://cryptoquant.com/catalog?coin=BTC)
- Short Guides on some of the data. [User Guide](https://userguide.cryptoquant.com/quickstart/5-minute-data-guide)
- [API Docs](https://cryptoquant.com/docs)
  
## Coinglass
 - datasource is not so useful. [API Docs](https://docs.coinglass.com/reference/getting-started-with-your-api)
   
# DataSource Category
- Network Data
- Market Indicator
- Market Data
- Network Indicator
- Bank Flow
- Flow Indicator
- Inter Entity Flow
- Exchange Flow
- Fund Data
- Miner Flow
  
# DataSource Usage
 - Spot Whail (Find Trend)
 - Spot Retailer (For Mean Reversion)
 - No Idea for On-Chain Data
   
# Entry Method
## Mean Reversion
### No Stoploss
MR_NoStopLoss
![alt text](https://i.imgur.com/UFmH6jQ.png)

### Has Stoploss
MR_StopLoss
![alt text](https://i.imgur.com/YTNyWTS.png)

## Momentum (Trend Following)
### Exit at Threshold
Momentum_NotHold
![alt text](https://i.imgur.com/lybNSAR.png)

### Exit at 另一個Threshold
Momentum_Hold
![alt text](https://i.imgur.com/Lcuzxz2.png)

# Data Processing 
## Standardization
- Z-Score (Good for Normal Distributed Data, No Anomaly Data)
- Robust Scaling (Can make extreme data less extreme)

## Normalization
- Min-Max Scaling (Good for data with )
- Max-Abs Scaling
- Percentile (Got an Idea from BensonSun for a All coin Screener)
  
## Unknown Type For Now, Unknown Usage
- Rate of change
- Box Cox Transformation (將non normal distribution data轉成接近normal distributed) (Unknown Usage)
  
# Optimization Parameter
 - Sharpe Ratio (尋找同樣風險下的最大回報)
 - Calmar Ratio (尋找一個高回報同時低回撤)
 - Sharpe * Calmar (Risk adjusted Return and Lower MDD)
 - Sharpe^2 * Calmar (Leaned more to toward Risk adjusted Return side than MDD)
 Some more ideas maybe useful(?), Sortino Ratio, Sharpe × Calmar / Drawdown Duration, Equity Curve Slope

# Combination of data
TBC
