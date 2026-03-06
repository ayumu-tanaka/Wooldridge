# PRISON データセットの説明

**観測数（Obs）:** 714

## 変数一覧

| 変数名 | 説明 |
|------|------|
| state | alphabetical; DC = 9 |
| year | 80 to 93 |
| govelec | gubernatorial election の場合1 |
| black | proportion black |
| metro | proportion in metro. areas |
| unem | proportion unemployed |
| criv | violent crimes per 100,000 |
| crip | property crimes per 100,000 |
| lcriv | crivの対数 |
| lcrip | cripの対数 |
| gcriv | lcriv - lcriv_1 |
| gcrip | lcrip - lcrip_1 |
| y81 | year == 81 の場合1 |
| y82 | （説明なし） |
| y83 | （説明なし） |
| y84 | （説明なし） |
| y85 | （説明なし） |
| y86 | （説明なし） |
| y87 | （説明なし） |
| y88 | （説明なし） |
| y89 | （説明なし） |
| y90 | （説明なし） |
| y91 | （説明なし） |
| y92 | （説明なし） |
| y93 | （説明なし） |
| ag0_14 | prop. pop. 0 to 14 yrs |
| ag15_17 | prop. pop. 15 to 17 yrs |
| ag18_24 | prop. pop. 18 to 24 yrs |
| ag25_34 | prop. pop. 25 to 34 yrs |
| incpc | per capita income, nominal |
| polpc | police per 100,000 residents |
| gincpc | incpc) - log(incpc_1の対数 |
| gpolpc | lpolpc - lpolpc_1 |
| cag0_14 | ag0_14の変化 |
| cag15_17 | ag15_17の変化 |
| cag18_24 | ag18_24の変化 |
| cag25_34 | ag25_34の変化 |
| cunem | 失業率の変化 |
| cblack | blackの変化 |
| cmetro | metroの変化 |
| pris | prison pop. per 100,000 |
| lpris | prisの対数 |
| gpris | lpris - lpris[t-1] |
| final1 | fnl dec on litig, curr yr の場合1 |
| final2 | dec on litig, prev 2 yrs の場合1 |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/prison.des](http://fmwww.bc.edu/ec-p/data/wooldridge/prison.des)
