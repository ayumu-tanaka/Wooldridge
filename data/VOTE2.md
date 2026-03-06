# VOTE2 データセットの説明

**観測数（Obs）:** 186

## 変数一覧

| 変数名 | 説明 |
|------|------|
| state | 州の郵便番号 |
| district | U.S. Congressional district |
| democ | incumbent democrat の場合1 |
| vote90 | incum. share two-party vote, 1990 |
| vote88 | incum. share two-party vote, 1988 |
| inexp90 | incum. camp. expends., 1990 |
| chexp90 | chal. camp. expends., 1990 |
| inexp88 | incum. camp. expends., 1988 |
| chexp88 | chal. camp. expends., 1988 |
| prtystr | 1988年同党大統領への投票率（%） |
| rptchall | a repeat challenger の場合1 |
| tenure | years in H.R. |
| lawyer | law degree の場合1 |
| linexp90 | inexp90の対数 |
| lchexp90 | chexp90の対数 |
| linexp88 | inexp88の対数 |
| lchexp88 | chexp88の対数 |
| incshr90 | 100*(inexp90/(inexp90+chexp90)) |
| incshr88 | 100*(inexp88/(inexp88+chexp88)) |
| cvote | vote90 - vote88 |
| clinexp | linexp90 - linexp88 |
| clchexp | lchexp90 - lchexp88 |
| cincshr | incshr90 - incshr88 |
| win88 | =1 by definition |
| win90 | inc. wins, 1990 の場合1 |
| cwin | win90 - win88 |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/vote2.des](http://fmwww.bc.edu/ec-p/data/wooldridge/vote2.des)
