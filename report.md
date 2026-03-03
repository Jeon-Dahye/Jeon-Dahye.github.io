# Crypto Price Dashboard Project

## 1. Static Table
I manually fetched Bitcoin and Ethereum prices from CoinGecko
and created a static HTML table.

## 2. Live Version
I used the CoinGecko API to fetch real-time prices.

The page:
- Automatically refreshes every 10 seconds
- Displays the last updated time from CoinGecko
- Keeps the last known price if a request fails

## 3. Technical Notes
CoinGecko provides aggregated data and does not update at tick-level.
Therefore, prices may not change every second.
