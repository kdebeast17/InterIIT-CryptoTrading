# InterIIT-CryptoTrading

## How to run backtesting.ipynb for your signals

- Open the python notebook in VS Code
- Scroll down to reach the below snippet
```py
hist = pd.read_csv('/Users/parthajit/Desktop/InterIIT/ZeltaLab_InterIIT/InterIIT-CryptoTrading/btcusdt_1h.csv')
strat = pd.read_csv('/Users/parthajit/Desktop/InterIIT/ZeltaLab_InterIIT/InterIIT-CryptoTrading/outputtttt.csv')
```
- Replace `hist` with `btcusdt_1h.csv` file location
- Replace `strat` with `signals.csv` file location
- Make sure `signals.csv` has a column named `signals`
- Start a python environment in VS Code
- Press `Restart` and `Run ALL`
