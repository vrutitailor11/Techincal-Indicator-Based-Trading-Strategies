# Techincal-Indicator-Based-Trading-Strategies


📌Project Overview

This project evaluates the effectiveness of technical indicator–based trading strategies and compares their performance against a benchmark Canadian mutual fund (TD Canadian Balanced Fund – TD908). Using historical stock price data and systematic backtesting, the study investigates whether rule-based trading strategies can consistently outperform traditional, diversified investment vehicles over the long term.

The analysis was conducted as part of the MBAI 5300G – Programming and Data Processing course and focuses on combining financial theory, quantitative analysis, and Python-based backtesting.

📌Objectives

Implement and backtest multiple technical trading strategies across different market regimes
Compare risk-adjusted and absolute returns against a professional mutual fund benchmark
Evaluate performance using standard financial metrics such as CAGR, Sharpe Ratio, and Maximum Drawdown
Assess whether technical indicators are better suited for short-term trading or long-term investing

📌Data Sources

Stock Data:
Daily OHLCV data retrieved using yfinance
Time period: 2015–2025
Tickers analyzed:
AAPL, AMZN, GOOGL, META, MSFT, NVDA, NFLX, TSLA, AVGO, PLTR
Benchmark:
TD Canadian Balanced Fund (TD908)

📌Strategy Categories Implemented

1. Trend-Following Strategies
Moving Average (50/200) Crossover
Breakout Strategy (20-day highs/lows)
Donchian Channel Strategy

2. Momentum Strategies
Rate of Change (ROC)
52-Week High / Low Breakout
RSI Momentum

3. Mean Reversion Strategies
Bollinger Bands Reversal
RSI Overbought / Oversold Reversion
Moving Average Envelope Reversal

4. Hybrid (Multi-Indicator) Strategies
MACD Trend Filter + RSI Confirmation
Momentum + Mean Reversion Filter

📌Methodology
1. Data Collection & Cleaning
Retrieved historical price data using Python
Handled missing values and aligned trading periods

2.Indicator Computation
Calculated indicators such as MA, RSI, MACD, Bollinger Bands, ROC, and Donchian Channels

3.Signal Generation
Rule-based buy/sell logic
No look-ahead bias (signals executed on next trading session)

4.Backtesting
Strategy returns calculated per ticker
Portfolio-level averages computed for comparison

5.Performance Evaluation
CAGR
Total & Cumulative Return
Volatility
Sharpe Ratio
Maximum Drawdown
Win Rate
Profit Factor

📌Key Findings

No technical strategy consistently outperformed the mutual fund benchmark over the full period
Trend-following and momentum strategies performed well during strong bull markets, but suffered during sideways or bearish conditions
Mean-reversion strategies showed high win rates but limited long-term compounding
Hybrid strategies improved signal filtering but remained highly regime-dependent
The mutual fund delivered:
Higher CAGR
Better risk-adjusted returns
Lower volatility and drawdowns

📌Conclusion:

Technical indicators are useful for short-term opportunity identification, but are less reliable as standalone long-term investment strategies compared to diversified mutual funds.
