This project examines the ways in which trader behavior and performance on the Hyperliquid trading platform are influenced by the sentiment of the Bitcoin market (Fear vs. Greed).
The objective is to use data analysis and a basic machine learning model to find behavioral patterns and extract useful trading insights.

The project blends:

Data on market sentiment (Fear & Greed Index)

Transaction history at the trader level

Predictive modeling and behavioral metrics


Goals :-->

Examine trader performance under Fear vs. Greed regimes (PnL, win rate).

Examine shifts in behavior (leverage, frequency of trades, long/short bias).

Divide traders into groups according to their actions.

Provide practical trading techniques.

Create a baseline forecasting model for the profitability of traders.


---------------------------------------------------------------------------------------------------------------------------------------------
How to Run This Project : -->

--> Clone the project using link at top-right

--> Move both the datasets into this folder which we downloaded from the given link:
1) Bitcoin Market Sentiment (Fear/Greed)
Columns: Date, Classification (Fear / Greed)
Link: https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

2) Historical Trader Data (Hyperliquid)
Includes fields like: account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage, etc.
Link: https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing
Please check for the download symbol in the left link 


--> install required libraries:
pip install pandas numpy matplotlib scikit-learn

--> run task.ipynb cell by cell
