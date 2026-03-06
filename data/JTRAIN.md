# JTRAIN データセットの説明

**観測数（Obs）:** 471

## 変数一覧

| 変数名 | 説明 |
|------|------|
| year | 1987、1988、または1989年 |
| fcode | 企業コード番号 |
| employ | 工場従業員数 |
| sales | 年間売上（ドル） |
| avgsal | 従業員の平均給与 |
| scrap | 廃棄率（100品目当たり） |
| rework | 手直し率（100品目当たり） |
| tothrs | 訓練の総時間 |
| union | unionized の場合1 |
| grant | received grant の場合1 |
| d89 | year = 1989 の場合1 |
| d88 | year = 1988 の場合1 |
| totrain | 訓練を受けた従業員数 |
| hrsemp | 総時間÷訓練時間 |
| lscrap | scrapの対数 |
| lemploy | employの対数 |
| lsales | salesの対数 |
| lrework | reworkの対数 |
| lhrsemp | 1 + hrsempの対数 |
| lscrap_1 | lscrapのラグ（1987年欠損） |
| grant_1 | 補助金のラグ（1987年は0と仮定） |
| clscrap | lscrapの変化（1987年以降） |
| cgrant | 補助金の変化 |
| clemploy | 雇用（対数）の変化 |
| clsales | lavgsalの変化 |
| lavgsal | avgsalの対数 |
| clavgsal | lavgsalの変化 |
| cgrant_1 | cgrant（1期ラグ） |
| chrsemp | 雇用時間の変化 |
| clhrsemp | lhrsempの変化 |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/jtrain.des](http://fmwww.bc.edu/ec-p/data/wooldridge/jtrain.des)
