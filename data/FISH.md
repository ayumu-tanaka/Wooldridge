# FISH データセットの説明

**観測数（Obs）:** 97

## 変数一覧

| 変数名 | 説明 |
|------|------|
| prca | for Asian buyers |
| prcw | for white buyers |
| qtya | sold to Asians |
| qtyw | sold to whites |
| mon | if Monday |
| tues | if Tuesday |
| wed | if Wednesday |
| thurs | if Thursday |
| speed2 | past 2 days wind speeds |
| wave2 | max last 2 days wave height |
| speed3 | day lagged max windspeed |
| wave3 | max wave hghts of 3 & 4 day lagged hghts |
| avgprc | + (prcw*qtyw))/(qtya + qtyw) |
| totqty | + qtyw |
| lavgprc | 平均価格の対数 |
| ltotqty | 総漁獲量の対数 |
| t | trend |
| lavgp_1 | lavgprc[_n-1] |
| gavgprc | - lavgp_1 |
| gavgp_1 | gavgprc[_n-1] |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/fish.des](http://fmwww.bc.edu/ec-p/data/wooldridge/fish.des)
