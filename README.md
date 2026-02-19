# Trader Performance vs Market Sentiment

## Objective
Analyze how Bitcoin market sentiment influences trader behaviour and performance on Hyperliquid using Fear & Greed Index data.

## Datasets
1. Bitcoin Fear & Greed Index (daily market sentiment)
2. Hyperliquid Historical Trader Data (trade-level activity)

## Methodology
- Cleaned malformed CSV rows and handled timestamp inconsistencies
- Converted timestamps to daily format for alignment
- Merged sentiment and trading datasets on date
- Computed key metrics including daily PnL, trade frequency, and positioning bias
- Segmented traders into Frequent and Infrequent groups based on activity

## Key Insights
- Traders exhibit higher profitability during Fear and Extreme Fear periods
- Trading activity increases significantly during volatile sentiment regimes
- A mild short bias appears during Greed periods
- Infrequent traders achieve higher average profitability per trade compared to frequent traders

## Strategy Recommendations
- Increase participation during Fear-driven markets due to higher opportunity
- Avoid excessive trade frequency as overtrading reduces per-trade profitability
- Consider dip-buying strategies during Extreme Fear conditions

## How to Run
1. Open the notebook
2. Upload the datasets to the environment
3. Execute all cells sequentially
