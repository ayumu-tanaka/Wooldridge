# レポジトリ詳細


## ディレクトリ構成
リポジトリは、教科書の章ごとに構成されています：

*   **`ChXX/`**: 特定の章の資料を含みます（例：`Ch01`, `Ch19`）。
    *   `WooldridgeXX.Rmd`: スライドのメインソースファイルです。
    *   `WooldridgeXX.pdf`: コンパイル済みのプレゼンテーション（PDF）です。
    *   `header_beamer.tex`: スタイリング用のLaTeXヘッダーファイルです。
*   **`statafiles/`**: Stata形式（.dta）のデータセットが含まれています。詳細は [data.md](./data.md) を参照してください。

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
