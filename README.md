# TradeMatrix

A trading journal web app built using PHP for keeping track of and analyzing your trades in stocks, F&O, forex, crypto etc. MySQL is used for storing data.

## Features (Planned)

### Trade Log:
- Add each trade with Entry, Exit, Status, Target, Stoploss, Remarks, Chart pic, Strategy, Direction (Bullish/Bearish), tags etc
- Filter and sort trades or charts by date, profit or loss % etc
- Gallery view for charts and table view for trades

### Statistics:
- Capital Growth (with graph)
- Global P&L (with graph)
- P&L by trade direction
- P&L ratio
- Sharpe ratio
- R ratio
- Batting Average
- Strategy use frequency

#### Filters:
- Time period
- Number of trades
- P/L value
  
### Calculators:
- Position sizing based on risk and stoploss
- Stoploss based on R ratio or risk appetite
- Compounded returns for long term investments
  
### Other Features:
- Profile section with trading goals etc
- Multiple tags can be associated for multiple brokers, instruments, paper trades etc. Everything can be filtered by tags
- Algo trading, data feed, live updates on open trades, CMP/LTP updates, FA and TA screeners etc
- Option to include/exclude paper trades in global statistics
- Create view-only links to share certain parts of the journal with anyone
- Export/import JSON/XML/CSV/PDF trade log
- Printable view
