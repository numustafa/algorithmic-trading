# What does intraday Strategy means?
This approach involves buying and selling financial instruments within the same trading day, aiming to capitalize on short-term price movements. Intraday trading strategies often rely on technical analysis, chart patterns, risk management and real-time data to make quick decisions. Traders typically use various indicators, such as moving averages, volume analysis, and volatility measures, to identify potential entry and exit points. The goal is to profit from small price fluctuations while minimizing exposure to overnight market risks.


# Objectives for Project - Intraday Trading Strategy using GARCH Model
- **Data Collection**: Load simulated daily data and simulated 5-min data for a specific stock (e.g., AAPL).
- **GARCH Model Implementation**: Apply the GARCH (Generalized Autoregressive Conditional Heteroskedasticity) model to forecast volatility based on the data 1-day ahead volatility in a rolling window fashion.
- **Calculate Signals**: Calculate prediction premiums and form a daily signal based on the GARCH model's volatility predictions.
- **Calculate Intraday signals**: Merge with intraday data and calculate intraday indicators to form the intraday signal.
- **Position**: Generate the position entry and hold until the end of the day.
- **Calculate Returns**: Calculate final stretegy returns.
