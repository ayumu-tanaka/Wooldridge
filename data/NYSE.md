# NYSE データセットの説明

**観測数（Obs）:** 691

## 変数一覧

| 変数名 | 説明 |
|------|------|
| price | ニューヨーク証券取引所株価指数 |
| return | 100*(p - p(-1])/p(-1)) |
| return_1 | lagged return |
| t | time trend:  1 to 691 |
| price_1 | price(-1) |
| price_2 | price(-2) |
| cprice | price - price_1 |
| cprice_1 | cprice(-1) |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/nyse.des](http://fmwww.bc.edu/ec-p/data/wooldridge/nyse.des)
