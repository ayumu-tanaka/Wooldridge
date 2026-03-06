# CEMENT データセットの説明

**観測数（Obs）:** 312

## 変数一覧

| 変数名 | 説明 |
|------|------|
| year | 1964〜1989年 |
| month | 1〜12 |
| prccem | BLSのセメントPPI |
| ipcem | セメントの産業生産指数 |
| prcpet | 原油のPPI（生産者物価指数） |
| rresc | 実質住宅建設 |
| rnonc | 実質非住宅建設 |
| ip | 産業生産指数（集計） |
| rdefs | 実質国防費 |
| milemp | 軍事雇用 |
| gprc | prccem) - log(prccem[t-1]の対数 |
| gcem | ipcem) - log(ipcem[t-1]の対数 |
| grprcpet | prcpet) - log(prcpet[t-1]の対数 |
| grres | rresc) - log(rresc[t-1]の対数 |
| grnon | rnonc) - log(rnonc[t-1]の対数 |
| gip | ip) - log(ip[t-1]の対数 |
| grdefs | rdefs) - log(rdefs[t-1]の対数 |
| gmilemp | milemp) - log(milemp[t-1]の対数 |
| jan | month == 1 の場合1 |
| feb | month == 2 の場合1 |
| mar | month == 3 の場合1 |
| apr | month == 4 の場合1 |
| may | month == 5 の場合1 |
| jun | month == 6 の場合1 |
| jul | month == 7 の場合1 |
| aug | month == 8 の場合1 |
| sep | month == 9 の場合1 |
| oct | month == 10 の場合1 |
| nov | month == 11 の場合1 |
| dec | month == 12 の場合1 |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/cement.des](http://fmwww.bc.edu/ec-p/data/wooldridge/cement.des)
