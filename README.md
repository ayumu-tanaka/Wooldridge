# Wooldridge 計量経済学スライド

## 概要
このリポジトリは、**ジェフリー・ウルドリッジ著『Introductory Econometrics: A Modern Approach』** に基づく講義スライドを含んでいます。

このプロジェクトでは **R Markdown** を使用して **LaTeX Beamer** プレゼンテーションを生成しており、Rコードと計量経済学のデータセット（`wooldridge` パッケージ経由）をスライドに直接統合しています。

## スライド一覧

| 章 | タイトル | PDF | HTML |
| :--- | :--- | :---: | :---: |
| Ch01 | 第1章: 計量経済学と経済データの性質 | [PDF](./Ch01/Wooldridge01.pdf) | [HTML](./Ch01/Wooldridge01.html) |
| Ch02 | 第2章: 単回帰モデル | [PDF](./Ch02/Wooldridge02.pdf) | [HTML](./Ch02/Wooldridge02.html) |
| Ch03 | 第3章: 多重回帰分析：推定 | [PDF](./Ch03/Wooldridge03.pdf) | [HTML](./Ch03/Wooldridge03.html) |
| Ch04 | 第4章: 多重回帰分析：推論 | [PDF](./Ch04/Wooldridge04.pdf) | [HTML](./Ch04/Wooldridge04.html) |
| Ch05 | 第5章: 多重回帰分析：OLS漸近特性 | [PDF](./Ch05/Wooldridge05.pdf) | [HTML](./Ch05/Wooldridge05.html) |
| Ch06 | 第6章: 多変量回帰：発展 | [PDF](./Ch06/Wooldridge06.pdf) | [HTML](./Ch06/Wooldridge06.html) |
| Ch07 | 第7章: 多重回帰分析：質的情報 | [PDF](./Ch07/Wooldridge07.pdf) | [HTML](./Ch07/Wooldridge07.html) |
| Ch08 | 第8章: 多重回帰分析：不均一分散 | [PDF](./Ch08/Wooldridge08.pdf) | [HTML](./Ch08/Wooldridge08.html) |
| Ch09 | 第9章: 定式化とデータの問題 | [PDF](./Ch09/Wooldridge09.pdf) | [HTML](./Ch09/Wooldridge09.html) |
| Ch13 | 第13章: 単純なパネルデータ | [PDF](./Ch13/Wooldridge13.pdf) | [HTML](./Ch13/Wooldridge13.html) |
| Ch14 | 第14章: 発展的なパネルデータ法 | [PDF](./Ch14/Wooldridge14.pdf) | [HTML](./Ch14/Wooldridge14.html) |
| Ch15 | 第15章: 操作変数法と二段階最小二乗法 | [PDF](./Ch15/Wooldridge15.pdf) | [HTML](./Ch15/Wooldridge15.html) |
| Ch19 | 第19章: 実証研究の実施 | [PDF](./Ch19/Wooldridge19.pdf) | [HTML](./Ch19/Wooldridge19.html) |

## ディレクトリ構成
リポジトリは、教科書の章ごとに構成されています：

*   **`ChXX/`**: 特定の章の資料を含みます（例：`Ch01`, `Ch19`）。
    *   `WooldridgeXX.Rmd`: スライドのメインソースファイルです。
    *   `WooldridgeXX.pdf`: コンパイル済みのプレゼンテーション（PDF）です。
    *   `header_beamer.tex`: スタイリング用のLaTeXヘッダーファイルです。
*   **`statafiles/`**: Stata形式（.dta）のデータセットが含まれています。

## 主要ファイルと設定
*   **`ChXX/WooldridgeXX.Rmd`**: R Markdownソースです。日本語文字をサポートするために、エンジンとして `lualatex` を指定しています。
*   **`ChXX/header_beamer.tex`**: カスタムLaTeXプリアンブルです。日本語フォントサポートのために `luatexja` を使用し、Beamerのフッター（スライド番号）をカスタマイズしています。

## スライドのビルド（作成）方法
スライドをコンパイルするには、必要なパッケージを備えた R 環境と、LuaLaTeX をサポートする LaTeX ディストリビューションが必要です。

### 必要要件
*   **R パッケージ:**
    *   `rmarkdown`
    *   `knitr`
    *   `wooldridge` (例題で使用されるデータセットを含みます)
*   **LaTeX:**
    *   TeX Live や MiKTeX などのディストリビューション。
    *   **LuaLaTeX** エンジン（`luatexja` に必要です）。

### コンパイル
R を使用してスライドをレンダリング（生成）できます：

```r
rmarkdown::render("Ch01/Wooldridge01.Rmd")
```

または、RStudio 内で `.Rmd` ファイルを開き、**Knit** ボタンをクリックするだけです。

* * *

出典：Jeffrey M. Wooldridge (2016). _Introductory Econometrics: A Modern Approach_. South-Western Cengage Learning.
