# Ticker-symbol-typer
A program that allows users to navigate through a stock watchlist using the up and down arrow keys. When a key is pressed, the program types the current stock ticker symbol and quickly updates to type the next stock in the chosen direction. This feature significantly speeds up the process of reviewing a watchlist.


- Close the GUI tab to terminate
- Press “arrow down & up” keys to navigate the watchlist
- You can add or remove stocks by pressing either respective button


To build the project, run:
```python
pyinstaller --onefile --noconsole stocks.py
```
Then move the `ticker_symbols.txt` to the directory with the application.


You can also run `watcher.py` to recreate the app whenever you save backend changes in `stocks.py`.
