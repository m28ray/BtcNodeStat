# BtcNodeStat

Display statistics for a bitcoin node

* Created by [ma2thieu](https://github.com/ma2thieu/BtcNodeStat) in 2014
* Re-written by Google AI in 2026
* Tested by m28ray

This rewrite completely removes **jQuery** and **Mustache**. Instead, it uses **Bootstrap 5.3** for layout and styling, and native modern JavaScript features: fetch() for API requests, Template Literals (backticks `) for UI templating, and modern array methods (for...of, Object.entries(), and .map()).

## cron
```
*/1 * * * * bitcoin-cli getblockchaininfo > /var/www/getblockchaininfo.json
*/1 * * * * bitcoin-cli getnetworkinfo > /var/www/getnetworkinfo.json
*/1 * * * * bitcoin-cli getnettotals > /var/www/getnettotals.json
*/1 * * * * bitcoin-cli getpeerinfo > /var/www/getpeerinfo.json
```

## Screenshots
![Web layout dark theme](/Screenshot1.png)
![Web layout light theme](/Screenshot2.png)
![Mobile layout dark theme](/Screenshot4.png)
![Mobile layout light theme](/Screenshot3.png)
