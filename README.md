# Algorithmic Trading BTC-USDT

This repository contains algorithmic trading agents designed for different time intervals, ranging from minutes to days. The project aims to implement and backtest various trading strategies using Jupyter Notebooks.

## Project Structure

The main folder contains the following files and directories:
- **agents folder/**: Contains the Jupyter Notebooks for different agents, each representing a trading strategy applied to different time intervals.

### Agents Description

All agents are written in Python, using various trading and financial libraries for backtesting, analysis, and decision-making. Below is a list of the agents and the time intervals they operate on:

- **agent_1m.ipynb**: This agent operates on 1-minute intervals, suitable for high-frequency trading.
- **agent_1h.ipynb**: This agent operates on 1-hour intervals, focusing on medium-frequency trading strategies.
- **agent_4h.ipynb**: This agent uses 4-hour intervals, allowing it to balance between intraday and swing trading.
- **agent_1d.ipynb**: This agent operates on daily intervals, ideal for longer-term swing trading strategies.
- **agent_All_Intervals_1m,1h,4h,1d.ipynb**: This comprehensive agent can operate across multiple time intervals (1 minute, 1 hour, 4 hours, 1 day), providing a holistic view of the market and allowing for multi-timeframe analysis.

## Setup Instructions

1. Clone the repository to your local machine:

    ```bash
    git clone <repository-url>
    ```

2. Install the required dependencies:

    - Jupyter Notebook
    - Python 3.x
    - Financial data libraries like `pandas`, `numpy`, and `matplotlib`

    Install the dependencies using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

3. Open any of the Jupyter Notebooks in the `agents folder/` to explore the different strategies:

    ```bash
    jupyter notebook agents/agent_1d.ipynb
    ```

## Usage

- **agent_1m.ipynb**: High-frequency trading with 1-minute candles.
- **agent_1h.ipynb**: Suitable for day traders looking for trades based on hourly trends.
- **agent_4h.ipynb**: Best for those seeking to capture intraday swings.
- **agent_1d.ipynb**: For longer-term swing traders using daily data.
- **agent_All_Intervals_1m,1h,4h,1d.ipynb**: A hybrid approach that combines signals from multiple timeframes.

## Report

Refer to the `report.pdf` for detailed insights into the performance of each agent and a breakdown of the strategies used.
