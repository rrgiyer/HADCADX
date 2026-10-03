# HADCADX
a stratgy that looks to select a basket of stocks with rebalancing based on trend strength measured under HA candle and technical indicators
technical indicators used - Donchian Channels, ADX, ATR
basket NSE universe with atleast daily turnover of INR 1 million for the past 30 days
weights for the basket capped at 28% per stock. max 10 stocks at any point of time. 
weights change on daily basis and are normalised subject to caps and available capital
long only
long condition are 2 in nature 3 consecutive green candles or close above the high of the candle making the DC low
initial stop loss @ 1.5 atr
inital target @ R:R os 1.5, trail sl to highest high since entry - 2*atr at entry or 3 consecutive red candles.
all entry exit at opening price based on the previous days indicators
targetting a sharpe of more than 1.5 and returns beating the nifty 750 index
