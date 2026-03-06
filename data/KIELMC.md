# KIELMC データセットの説明

**観測数（Obs）:** 321

## 変数一覧

| 変数名 | 説明 |
|------|------|
| year | 1978または1981年 |
| age | 住宅の築年数 |
| agesq | ageの二乗 |
| nbh | 近隣番号（1〜6） |
| cbd | 中央業務地区までの距離（フィート） |
| intst | 州間高速道路までの距離（フィート） |
| lintst | intstの対数 |
| price | 売却価格 |
| rooms | 住宅の部屋数 |
| area | 住宅面積（平方フィート） |
| land | 敷地面積（平方フィート） |
| baths | 浴室数 |
| dist | 住宅から焼却炉までの距離（フィート） |
| ldist | distの対数 |
| wind | 風が焼却炉から住宅方向に吹く時間割合（%） |
| lprice | priceの対数 |
| y81 | year == 1981 の場合1 |
| larea | areaの対数 |
| lland | landの対数 |
| y81ldist | y81 × ldist（交差項） |
| lintstsq | lintstの二乗 |
| nearinc | dist <= 15840 の場合1 |
| y81nrinc | y81 × nearinc（交差項） |
| rprice | 価格（1978年ドル） |
| lrprice | rpriceの対数 |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/kielmc.des](http://fmwww.bc.edu/ec-p/data/wooldridge/kielmc.des)
