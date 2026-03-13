# RSI + EMA Strategy Backtest (NIFTY)

This project explores a simple quantitative trading strategy using RSI and EMA indicators on NIFTY index data.

## Strategy Logic

Buy when:
- RSI < 30
- Price > EMA20

Sell when:
- RSI > 70

## Tools Used

- Python
- pandas
- numpy
- matplotlib
- yfinance

## Metrics Evaluated

- Cumulative returns
- Sharpe ratio
- Maximum drawdown

## Visualization

The notebook plots buy and sell signals on the price chart and compares strategy performance against a buy-and-hold approach.

## Future Improvements

- Add stop-loss rules
- Optimize parameters
- Test multiple strategies
