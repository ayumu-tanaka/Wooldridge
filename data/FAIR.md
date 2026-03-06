# FAIR データセットの説明

**観測数（Obs）:** ?

## 変数一覧

| 変数名 | 説明 |
|------|------|
| year | 1916〜1992年（4年ごと） |
| V | 民主党への投票割合 |
| I | Dem. in White House, -1 if Rep. の場合1 |
| DPER | 現職者が立候補している場合 |
| DUR | 期間 |
| g3 | 前3四半期の年平均成長率 |
| p15 | 前15四半期の年平均インフレ率 |
| n | 良いニュースの四半期数 |
| g2 | 前2四半期の年平均成長率 |
| gYR | 前年の年間成長率 |
| p8 | 前8四半期の年平均インフレ率 |
| p2YR | 2年間のインフレ率 |
| Ig2 | I×g2 |
| Ip8 | I×p8 |
| demwins | V > .5 の場合1 |
| In | I×n |
| d | 1920、1944、1948年の場合1 |
| Id | I×d |
| Ig3 | I×g3 |
| Ip151md | I×p15×(1-d) |
| In1md | I×n×(1-d) |
| demvote | = V |
| incum | = DPER |
| gnews | = n |
| inf | = p15 |
| partyWH | = I |
| pWHgnews | 政権政党 × 良いニュース（交差項） |
| pWHinf | 政権政党 × インフレ率（交差項） |

* * *

**出典**: [http://fmwww.bc.edu/ec-p/data/wooldridge/fair.des](http://fmwww.bc.edu/ec-p/data/wooldridge/fair.des)
