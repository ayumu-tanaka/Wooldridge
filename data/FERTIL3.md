# FERTIL3 データセットの説明

**観測数（Obs）:** 72

## 変数一覧

| 変数名 | 説明 |
|------|------|
| gfr | births per 1000 women 15-44 |
| pe | real value pers. exemption, $ |
| year | 1913 to 1984 |
| t | time trend, t=1,...,72 |
| tsq | tの二乗 |
| pe_1 | pe[t-1] |
| pe_2 | pe[t-2] |
| pe_3 | pe[t-3] |
| pe_4 | pe[t-4] |
| pill | year >= 1963 の場合1 |
| ww2 | =1, 1941 to 1945 |
| tcu | t^3 |
| cgfr | gfr:  gfr - gfr_1の変化 |
| cpe | pe - pe_1 |
| cpe_1 | cpe[t-1] |
| cpe_2 | cpe[t-2] |
| cpe_3 | cpe[t-3] |
| cpe_4 | cpe[t-4] |
| gfr_1 | gfr[t-1] |
| cgfr_1 | cgfr[t-1] |
| cgfr_2 | cgfr[t-2] |
| cgfr_3 | cgfr[t-3] |
| cgfr_4 | cgfr[t-4] |
| gfr_2 | gfr[t-2] |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/fertil3.des](http://fmwww.bc.edu/ec-p/data/wooldridge/fertil3.des)
