# Binance-PHP-Trading-Bot
Binance PHP Trading Bot
- This bot is like market maker bot which provide liquidity to Binance Exchange.

Following PHP Scripts need to be coded:
1. Pull Price Feed (Best Bid/Ask Price & Volume, Last Transaction Price) from Binance. User can set the Currency Pair eg. NEO/BTC.
2. Get Account Data eg. Balance of Various Currency Pairs & Pending Orders
3. Open New Trade Order based on Bid/Ask Price +X% Premium eg. Best Bid Price is $1, Trader can set $1 + 1% = $1.01 or $1 - 1% = $0.99 .Trader also can set Max Quantity to Buy/Sell, but will depend on available balance. Cancel Pending Order Before Open New Trade Order.

Binance API Documentation: https://www.binance.com/restapipub.html

Register to Get API Key: https://goo.gl/p9fYm3
