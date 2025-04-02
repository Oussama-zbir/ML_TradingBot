# Cryptocurrency Trading Bot

## Overview
An algorithmic trading system for cryptocurrencies using LSTM neural networks and portfolio optimization. The bot analyzes multiple assets (BTC, ETH, BNB), implements Bollinger Bands strategy with dynamic take-profit/stop-loss levels, and optimizes portfolio allocation based on predicted returns and risk metrics.

## Features
- LSTM-based price prediction
- Multi-asset trading and portfolio optimization
- Bollinger Bands trading strategy
- Dynamic position sizing and risk management
- Backtesting framework with performance metrics
- Binance API integration

## Requirements
- Python 3.7+
- TensorFlow/Keras
- python-binance
- numpy, pandas
- scikit-learn
- cvxpy
- matplotlib

## Installation
```bash
pip install python-binance numpy pandas scikit-learn tensorflow keras cvxpy matplotlib
