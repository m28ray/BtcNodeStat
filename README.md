# BtcNodeStat

Display statistics for a bitcoin node

* Created by ma2thieu in 2014
* Re-written by Google AI in 2026
* Tested by m28ray



## cron
```
*/1 * * * * bitcoin-cli getblockchaininfo > /var/www/getblockchaininfo.json
*/1 * * * * bitcoin-cli getnetworkinfo > /var/www/getnetworkinfo.json
*/1 * * * * bitcoin-cli getnettotals > /var/www/getnettotals.json
*/1 * * * * bitcoin-cli getpeerinfo > /var/www/getpeerinfo.json
```
