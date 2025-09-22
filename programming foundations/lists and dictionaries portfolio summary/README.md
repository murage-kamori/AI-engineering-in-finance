This script processes a list of crypto transactions (e.g., BTC and ETH buys/sells) to build a portfolio dictionary. It:

Extracts unique cryptocurrencies.
Computes net quantity (buys minus sells).
Calculates average purchase price and unrealized PNL based on current prices.
(Bonus) Filters buy quantities after a specific date using the datetime library.
Example output:

BTC: Net quantity 0.8, Avg price 
11,761.13
ETH: Net quantity 5.0, Avg price 
8,010.25
Current prices used: BTC $35,000, ETH $2,400.