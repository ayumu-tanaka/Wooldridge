# HSEINV データセットの説明

**観測数（Obs）:** 42

## 変数一覧

| 変数名 | 説明 |
|------|------|
| year | 1947-1988 |
| inv | real housing invest., millions $ |
| pop | population, 1000s |
| price | housing price index; 1982 = 1 |
| linv | invの対数 |
| lpop | 人口の対数 |
| lprice | 価格の対数 |
| t | time trend: t=1,...,42 |
| invpc | per capita invest., inv/pop |
| linvpc | invpcの対数 |
| lprice_1 | lprice[t-1] |
| linvpc_1 | linvpc[t-1] |
| gprice | lprice - lprice_1 |
| ginvpc | linvpc - linvpc_1 |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/hseinv.des](http://fmwww.bc.edu/ec-p/data/wooldridge/hseinv.des)
