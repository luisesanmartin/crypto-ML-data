# crypto-ML-data
Data download and wrangling for my crypto ML predictor

# Predictive features created in data wrangling

| N | Feature    | Description    | Type    |
| - | ---------- | -------------- | ------- |
|1 |`price_close_sd`|Standardized close price|Normalized (l2) with respect of training set|
|2 |`inc_price_last1`|Price increased in last 1 observation|Dummy 1/0|
|3 |`inc_price_last2`|Price increased in last 2 observations|Dummy 1/0|
|4 |`inc_price_last3`|Price increased in last 3 observations|Dummy 1/0|
|5 |`inc_price_last4`|Price increased in last 4 observations|Dummy 1/0|
|6 |`inc_price_last5`|Price increased in last 5 observations|Dummy 1/0|
|7 |`inc_price_last6`|Price increased in last 6 observations|Dummy 1/0|
|8 |`vol_sd`|Standardize volume traded|Normalized (l2) with respect of training set|
|9 |`inc_vol_last1`|Volume increased in last 1 observation|Dummy 1/0|
|10|`inc_vol_last2`|Volume increased in last 2 observations|Dummy 1/0|
|11|`inc_vol_last3`|Volume increased in last 3 observations|Dummy 1/0|
|12|`inc_vol_last4`|Volume increased in last 4 observations|Dummy 1/0|
|13|`inc_vol_last5`|Volume increased in last 5 observations|Dummy 1/0|
|14|`inc_vol_last6`|Volume increased in last 6 observations|Dummy 1/0|
|15|`trades_sd`|Standardized number of trades|Normalized (l2) with respect of training set|
|16|`inc_trades_last1`|Trades increased in last 1 observation|Dummy 1/0|
|17|`inc_trades_last2`|Trades increased in last 2 observations|Dummy 1/0|
|18|`inc_trades_last3`|Trades increased in last 3 observations|Dummy 1/0|
|19|`inc_trades_last4`|Trades increased in last 4 observations|Dummy 1/0|
|20|`inc_trades_last5`|Trades increased in last 5 observations|Dummy 1/0|
|21|`inc_trades_last6`|Trades increased in last 6 observations|Dummy 1/0|
|22|`max_price_is_open`|Maximum price in the observation is equal to open price|Dummy 1/0|
|22|`max_price_is_close`|Maximum price in the observation is equal to close price|Dummy 1/0|
|23|`min_price_is_open`|Minimum price in the observation is equal to open price|Dummy 1/0|
|24|`min_price_is_close`|Minimuim price in the observation is equal to close price|Dummy 1/0|
|25|`inc_price`|Price increased in this observation|Dummy 1/0|
|26|`inc_vol`|Volume increased in this observation|Dummy 1/0|
|27|`inc_trades`|Trades increased in this observation|Dummy 1/0|

# Predicted feature

The price will increase in the next observation.
