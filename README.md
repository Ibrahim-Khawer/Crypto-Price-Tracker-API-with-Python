# Crypto Price Tracker API with Python

## Business Problem
Investors and cryptocurrency traders need automated, real-time price tracking to make informed decisions in volatile markets. Manual monitoring is inefficient and prone to missed opportunities, while reliable data visualization is essential for identifying market trends.

## Technical Details

- **Data Source**: CoinMarketCap Professional API providing real-time cryptocurrency data
- **Methods**: Automated API data collection, pandas for data transformation, seaborn/matplotlib for interactive visualizations
- **Key Features**: 
  - Real-time price tracking for 15 major cryptocurrencies
  - Percentage change analysis across multiple timeframes (1h, 24h, 7d, 30d, 60d, 90d)
  - Automated data logging with timestamp tracking
  - Advanced visualizations including catplots and time-series line charts
- **Tools**: Python, pandas, seaborn, matplotlib, requests API
- **Data Collection**: Continuous monitoring at configurable intervals with persistent storage

## Key Findings
- Successfully automated cryptocurrency data pipeline from API ingestion to visualization
- Implemented robust error handling for API connectivity issues
- Created interactive visualizations showing price trends and percentage changes
- Built scalable data collection system capable of long-term tracking

## Tools
Python, pandas, seaborn, matplotlib, requests, Jupyter Notebook

## Code available in repository

## Recommendation
Deploy this automated tracking system for portfolio management to combine real-time market data with historical trend analysis. The solution provides actionable insights for cryptocurrency investment decisions and can be extended for automated trading alerts and portfolio rebalancing strategies.
