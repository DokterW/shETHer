# coinbash

Get the current rate for BTC, ETH & LTC from [Coinbase](https://www.coinbase.com).

### Roadmap

* Coins will be saved to file instead of memory.
* Improved menu system.

### Changelog

#### 2017-05-07
* Changed the name from shETHer to coinbash as I will be including all three currencies from Coinbase -- BTC, ETH & LTC.
* Removed currency change indicator till I can find a good way to make it work for all currency without adding too much lines of code than necessary.

#### 2017-04-27
* To calculate if the rate had gone up or down, for the comparison to work I had to remove the decimals, which didn't look so well if it indicated no change but new rate is 400.54 and old rate was 400.45. Now it removes the decimal separator.

#### 2017-04-26
* Show how much ETH you have
* Show the previous rate, and if the rate has gone Up, Down or hasn't changed
