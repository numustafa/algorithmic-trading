# What is Unsupervised Learning in Trading?
Unsupervised learning in trading is meant to find hidden pattern from unlabeled data, such as clustering similar stocks or identifying anomalies in trading behavior. Unsupervised learning techniques explicitly extracts insights from the data without relying on predefined labels or outcomes, making it particularly useful for exploratory analysis and discovering new trading opportunities. How it is applied in trading:
- **Clustering**: Grouping similar stocks or assets based on their historical price movements or other features, which can help in portfolio diversification and risk management.
- **Dimensionality Reduction**: Techniques like PCA (Principal Component Analysis) are used to reduce the number of features while retaining the most important information, which can improve model performance and interpretability.
- **Anomaly Detection**: Identifying unusual patterns or outliers in trading data, which can signal potential trading opportunities or risks.
- **Market Regime Detection**: Unsupervised learning can be used to identify different market regimes or states, helping traders adapt their strategies to changing market conditions.
- **Portfolio Optimization**: Unsupervised learning techniques can be applied to optimize asset allocation by identifying clusters of assets that behave similarly, leading to more balanced and diversified portfolios.


# Objectives for Project - Unsupervised Learning Trading Strategy
- **Data Collection**: Gather historical SP500 data, including price, volume, and other relevant features.
- **Feature Engineering**: Create new features from the raw data, such as technical indicators, moving averages, and volatility measures.
- **Aggregation**: Combine features at different time intervals (e.g., daily, weekly or monthly) to capture different market dynamics, for each months, and for 150 top most liquid stocks.
- **Fama-French Factors**: Incorporate Fama-French factors to account for market risk, size, and value effects in the analysis.
- **Unsupervised Learning Techniques**: Apply clustering algorithms (e.g., K-means, hierarchical clustering) to identify patterns and relationships in the data.
- **Portfolio Optimization**: Use the identified clusters to optimize portfolio allocation, aiming for a balanced and diversified portfolio, based on Efficient Frontier max Sharpe Ratio.
- **Visualization**: Create visualizations to illustrate the clusters, portfolio allocations, and performance metrics.
- **Backtesting**: Implement a backtesting framework to evaluate the performance of the trading strategy based on the unsupervised learning insights. *


