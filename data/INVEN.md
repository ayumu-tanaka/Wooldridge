# INVEN データセットの説明

**観測数（Obs）:** 37

## 変数一覧

| 変数名 | 説明 |
|------|------|
| year | 1959-1995 |
| i3 | 3 mo. T-bill rate |
| inf | CPI inflation rate |
| inven | inventories, billions '92 $ |
| gdp | GDP, billions '92 $ |
| r3 | real interest: i3 - inf |
| cinven | inven - inven[t-1] |
| cgdp | gdp - gdp[t-1] |
| cr3 | r3 - r3[t-1] |
| ci3 | i3 - i3[t-1] |
| cinf | inf - inf[t-1] |
| ginven | inven) - log(inven[t-1]の対数 |
| ggdp | gdp) - log(gdp[t-1]の対数 |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/inven.des](http://fmwww.bc.edu/ec-p/data/wooldridge/inven.des)
