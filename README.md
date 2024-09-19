# Algorithmic Trading BTC-USDT

This project provides a set of algorithmic trading agents designed to operate across various time intervals. The agents are implemented using Python and Jupyter notebooks. The purpose of the project is to develop and test strategies that operate at different time intervals (1 minute, 1 hour, 1 day, etc.) to optimize trading decisions based on market data.

## Objective

Develop, backtest, and evaluate trading strategies for BTC/USDT using different time intervals. Implement strategies using the provided algorithmic trading simulation and agent templates. The intervals to be considered are: - 1 minute - 1 hour - 4 hours - 1 day

## Files in the Agents Folder

- **agent_1d.ipynb**: This agent operates using 1-day (daily) interval data.
- **agent_1h.ipynb**: This agent works with 1-hour interval data.
- **agent_1m.ipynb**: This agent is designed for high-frequency trading using 1-minute interval data.
- **agent_4h.ipynb**: This agent trades based on 4-hour interval data.
- **agent_All_Intervals_1m,1h,4h,1d.ipynb**: This is a multi-interval agent that integrates data from all intervals (1m, 1h, 4h, 1d) to make more informed trading decisions.

## Data Collection and Preprocessing

Before running the agents, data must be collected from a reliable financial market data source. The data is typically in the form of candlestick charts (OHLCV: Open, High, Low, Close, Volume). Data preprocessing steps such as handling missing values, scaling, and formatting the data to the required interval are essential.

Ensure that the data is clean and formatted correctly before passing it to the agents. If needed, custom preprocessing functions can be added in the notebooks.

## Agents Description

Each agent implements a unique trading strategy optimized for different timeframes. The strategies vary in their use of indicators, risk management techniques, and frequency of trades.

- **1 Minute Agent (agent_1m.ipynb)**: Ideal for high-frequency trading and making fast decisions based on short-term market movements.
- **1 Hour Agent (agent_1h.ipynb)**: Suitable for intraday trading, taking into account medium-term trends within a trading day.
- **4 Hour Agent (agent_4h.ipynb)**: A balanced agent for traders who want to capture larger movements without frequent trades.
- **1 Day Agent (agent_1d.ipynb)**: Designed for long-term traders, focusing on large market shifts over days.
- **All Intervals Agent**: This agent combines strategies across all intervals to create a more robust decision-making model.

# Disclaimer
This project is intended for educational purposes only. It is not financial advice and should not be used for live trading in financial markets. 
