# CRIME4 データセットの説明

**観測数（Obs）:** 630

## 変数一覧

| 変数名 | 説明 |
|------|------|
| county | 郡識別子 |
| year | 1981〜1987年 |
| crmrte | 一人当たり犯罪件数 |
| prbarr | 逮捕確率 |
| prbconv | 有罪判決確率 |
| prbpris | 禁錮刑確率 |
| avgsen | 平均刑期（日） |
| polpc | 一人当たり警察官数 |
| density | 1平方マイルあたりの人口 |
| taxpc | 一人当たり税収 |
| west | ノースカロライナ西部の場合1 |
| central | ノースカロライナ中部の場合1 |
| urban | SMSA内の場合1 |
| pctmin80 | 少数民族割合（%、1980年） |
| wcon | 週給（建設業） |
| wtuc | 週給（運輸・公益・通信業） |
| wtrd | 週給（卸売・小売業） |
| wfir | 週給（金融・保険・不動産業） |
| wser | 週給（サービス業） |
| wmfg | 週給（製造業） |
| wfed | 週給（連邦政府職員） |
| wsta | 週給（州政府職員） |
| wloc | wkly wge, local gov emps |
| mix | offense mix: face-to-face/other |
| pctymle | percent young male |
| d82 | year == 82 の場合1 |
| d83 | year == 83 の場合1 |
| d84 | year == 84 の場合1 |
| d85 | 1985年の場合1 |
| d86 | year == 86 の場合1 |
| d87 | year == 87 の場合1 |
| lcrmrte | 犯罪率の対数 |
| lprbarr | 逮捕確率の対数 |
| lprbconv | 有罪確率の対数 |
| lprbpris | 禁錮確率の対数 |
| lavgsen | 平均刑期の対数 |
| lpolpc | polpcの対数 |
| ldensity | 人口密度の対数 |
| ltaxpc | 一人当たり税収の対数 |
| lwcon | 建設業週給の対数 |
| lwtuc | 運輸等週給の対数 |
| lwtrd | 卸小売業週給の対数 |
| lwfir | 金融等週給の対数 |
| lwser | サービス業週給の対数 |
| lwmfg | 製造業週給の対数 |
| lwfed | 連邦職員週給の対数 |
| lwsta | 州職員週給の対数 |
| lwloc | 地方職員週給の対数 |
| lmix | 犯罪タイプ構成の対数 |
| lpctymle | pctymleの対数 |
| lpctmin | 少数民族割合の対数 |
| clcrmrte | lcrmrte - lcrmrte[t-1] |
| clprbarr | lprbarr - lprbarr[t-1] |
| clprbcon | lprbconv - lprbconv[t-1] |
| clprbpri | lprbpri - lprbpri[t-1] |
| clavgsen | lavgsen - lavgsen[t-1] |
| clpolpc | lpolpc - lpolpc[t-1] |
| cltaxpc | ltaxpc - ltaxpc[t-1] |
| clmix | lmix - lmix[t-1] |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/crime4.des](http://fmwww.bc.edu/ec-p/data/wooldridge/crime4.des)
