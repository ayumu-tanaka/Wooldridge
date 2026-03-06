# MURDER データセットの説明

**観測数（Obs）:** 153

## 変数一覧

| 変数名 | 説明 |
|------|------|
| id | state identifier |
| state | postal code |
| year | 87, 90, or 93 |
| mrdrte | murders per 100,000 population |
| exec | total executions, past 3 years |
| unem | annual unem. rate |
| d90 | year == 90 の場合1 |
| d93 | year == 93 の場合1 |
| cmrdrte | mrdrte - mrdrte[t-1] |
| cexec | exec - exec[t-1] |
| cunem | unem - unem[t-1] |
| cexec_1 | cexec[t-1] |
| cunem_1 | cunem[t-1] |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/murder.des](http://fmwww.bc.edu/ec-p/data/wooldridge/murder.des)
