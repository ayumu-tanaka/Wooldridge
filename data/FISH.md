# FISH データセットの説明

**観測数（Obs）:** 97

## 変数一覧

| 変数名 | 説明 |
|------|------|
| prca | アジア系購入者の場合 |
| prcw | 白人購入者の場合 |
| qtya | アジア系への売却 |
| qtyw | 白人への売却 |
| mon | 月曜日の場合 |
| tues | 火曜日の場合 |
| wed | 水曜日の場合 |
| thurs | 木曜日の場合 |
| speed2 | 過去2日間の風速 |
| wave2 | 過去2日間の最大波高 |
| speed3 | 最大風速の1日ラグ |
| wave3 | 3〜4日ラグの最大波高 |
| avgprc | （+ prcw×qtyw）÷（qtya + qtyw） |
| totqty | + qtyw |
| lavgprc | avgprcの対数 |
| ltotqty | totqtyの対数 |
| t | トレンド |
| lavgp_1 | lavgprc（1期ラグ） |
| gavgprc | - lavgp_1 |
| gavgp_1 | gavgprc（1期ラグ） |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/fish.des](http://fmwww.bc.edu/ec-p/data/wooldridge/fish.des)
