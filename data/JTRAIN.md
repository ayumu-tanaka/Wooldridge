# JTRAIN データセットの説明

**観測数（Obs）:** 471

## 変数一覧

| 変数名 | 説明 |
|------|------|
| year | 1987, 1988, or 1989 |
| fcode | firm code number |
| employ | # employees at plant |
| sales | annual sales, $ |
| avgsal | average employee salary |
| scrap | scrap rate (per 100 items) |
| rework | rework rate (per 100 items) |
| tothrs | total hours training |
| union | unionized の場合1 |
| grant | received grant の場合1 |
| d89 | year = 1989 の場合1 |
| d88 | year = 1988 の場合1 |
| totrain | total employees trained |
| hrsemp | tothrs/totrain |
| lscrap | scrapの対数 |
| lemploy | employの対数 |
| lsales | 売上高の対数 |
| lrework | reworkの対数 |
| lhrsemp | 1 + hrsempの対数 |
| lscrap_1 | lagged lscrap; missing 1987 |
| grant_1 | lagged grant; assumed 0 in 1987 |
| clscrap | lscrap - lscrap_1; year > 1987 |
| cgrant | grant - grant_1 |
| clemploy | lemploy - lemploy[t-1] |
| clsales | lavgsal - lavgsal[t-1] |
| lavgsal | avgsalの対数 |
| clavgsal | lavgsal - lavgsal[t-1] |
| cgrant_1 | cgrant[t-1] |
| chrsemp | hrsemp - hrsemp[t-1] |
| clhrsemp | lhrsemp - lhrsemp[t-1] |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/jtrain.des](http://fmwww.bc.edu/ec-p/data/wooldridge/jtrain.des)
