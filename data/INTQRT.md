# INTQRT データセットの説明

**観測数（Obs）:** 124

## 変数一覧

| 変数名 | 説明 |
|------|------|
| r3 | bond equiv. yield, 3 mo. T-bill |
| r6 | bond equiv. yield, 6 mo. T-bill |
| r12 | yield on 1 yr. bond |
| p3 | price of 3 mo. T-bill |
| p6 | price of 6 mo. T-bill |
| hy6 | holding yield:  100*(p3 - p6[t-1])/p6[t-1]) |
| hy3 | holding yield:  r3*(91/365) |
| spr63 | spread:  r6 - r3 |
| hy3_1 | hy3[t-1] |
| hy6_1 | hy6[t-1] |
| spr63_1 | spr63[t-1] |
| hy6hy3_1 | hy6 - hy3_1 |
| cr3 | r3 - r3_1 |
| r3_1 | r3[t-1] |
| chy6 | hy6 - hy6_1 |
| chy3 | hy3 - hy3_1 |
| chy6_1 | chy6[t-1] |
| chy3_1 | chy3[t-1] |
| cr6 | r6 - r6_1 |
| cr6_1 | cr6[t-1] |
| cr3_1 | cr3[t-1] |
| r6_1 | r6[t-1] |
| cspr63 | spr63 - spr63_1 |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/intqrt.des](http://fmwww.bc.edu/ec-p/data/wooldridge/intqrt.des)
