# CONSUMP データセットの説明

**観測数（Obs）:** 37

## 変数一覧

| 変数名 | 説明 |
|------|------|
| year | 1959-1995 |
| i3 | 3 mo. T-bill rate |
| inf | inflation rate; CPI |
| rdisp | disp. inc., 1992 $, bils. |
| rnondc | nondur. cons., 1992 $, bils. |
| rserv | services, 1992 $, bils. |
| pop | population, 1000s |
| y | per capita real disp. inc. |
| rcons | rnondc + rserv |
| c | per capita real cons. |
| r3 | i3 - inf; real ex post int. |
| lc | cの対数 |
| ly | yの対数 |
| gc | lc - lc[t-1] |
| gy | ly - ly[t-1] |
| gc_1 | gc[t-1] |
| gy_1 | gy[t-1] |
| r3_1 | r3[t-1] |
| lc_ly | lc - ly |
| lc_ly_1 | lc_1 - ly_1 |
| gc_2 | gc[t-2] |
| gy_2 | gy[t-2] |
| r3_2 | r3[t-2] |
| lc_ly_2 | lc_2 - ly_2 |
| i3_1 | i3[t-1] |
| t | 時間トレンド |
| ly_1 | ly[t-1] |
| lrcons | rconsの対数 |
| lrnondc | rnondcの対数 |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/consump.des](http://fmwww.bc.edu/ec-p/data/wooldridge/consump.des)
