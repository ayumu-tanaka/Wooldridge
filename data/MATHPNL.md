# MATHPNL データセットの説明

**観測数（Obs）:** 3850

## 変数一覧

| 変数名 | 説明 |
|------|------|
| distid | 識別子 |
| intid | 学区 |
| lunch | 無料給食の対象となる場合 |
| enrol | 在籍者数 |
| ptr | 1995〜1998年 |
| found | 補助金（ドル、1995〜1998年） |
| expp | 生徒一人当たり |
| revpp | 生徒一人当たり |
| avgsal | 教員給与 |
| drop | 退学率（%） |
| grad | 卒業率（%） |
| math4 | 4年生数学で合格した割合 |
| math7 | 7年生数学で合格した割合 |
| choice | 選択スクールの生徒数 |
| psa | 公立スクールアカデミーの学生数 |
| year | 1992〜1998年 |
| staff | 生徒1000人当たり |
| avgben | 教員の福利厚生 |
| y92 | 1992年の場合 |
| y93 | 1993年の場合 |
| y94 | 1994年の場合 |
| y95 | 1995年の場合 |
| y96 | 1996年の場合 |
| y97 | 1997年の場合 |
| y98 | 1998年の場合 |
| lexpp | exppの対数 |
| lfound | foundの対数 |
| lexpp_1 | lexpp（1期ラグ） |
| lfnd_1 | lfnd（1期ラグ） |
| lenrol | enrolの対数 |
| lenrolsq | lenrolの二乗 |
| lunchsq | lunchの二乗 |
| lfndsq | lfndの二乗 |
| math4_1 | math4（1期ラグ） |
| cmath4 | - math4_1 |
| gexpp | - lexpp_1 |
| gexpp_1 | gexpp（1期ラグ） |
| w1 | - gexpp |
| gfound | - lfnd_1 |
| gfnd_1 | gfound（1期ラグ） |
| clunch | - lunch[t-1] |
| clnchsq | - lunchsq[t-1] |
| genrol | - lenrol[t-1] |
| genrolsq | genrolの二乗 |
| expp92 | 1992年 |
| lexpp92 | expp92の対数 |
| math4_92 | 1992年 |
| cpi | 価格指数 |
| rexpp | 生徒一人当たりの支出（1997年ドル） |
| lrexpp | rexppの対数 |
| lrexpp_1 | lrexpp（1期ラグ） |
| grexpp | - lrexpp_1 |
| z1 | - lrexpp |
| grexpp_1 | grexpp（1期ラグ） |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/mathpnl.des](http://fmwww.bc.edu/ec-p/data/wooldridge/mathpnl.des)
