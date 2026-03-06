# EARNS データセットの説明

**観測数（Obs）:** 41

## 変数一覧

| 変数名 | 説明 |
|------|------|
| year | 1947 to 1987 |
| wkearns | avg. real weekly earnings |
| wkhours | avg. weekly hours |
| outphr | output per labor hour |
| hrwage | wkearns/wkhours |
| lhrwage | 時給の対数 |
| loutphr | outphrの対数 |
| t | time trend:  t=1 to 47 |
| ghrwage | lhrwage - lhrwage[t-1] |
| goutphr | loutphr - loutphr[t-1] |
| ghrwge_1 | ghrwage[t-1] |
| goutph_1 | goutphr[t-1] |
| goutph_2 | goutphr[t-2] |
| lwkhours | wkhoursの対数 |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/earns.des](http://fmwww.bc.edu/ec-p/data/wooldridge/earns.des)
