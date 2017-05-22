BXjatool パッケージバンドル
===========================

laTeX: 和文処理のための小規模なパッケージの集まり。

--------------------------------------------------
**整理中**

  * bxcalcize, bxcalcux を [BXcalc パッケージ]に移動した。
  * bxjaprnind を [BXjaprnind パッケージ]に移動した。

[BXcalc パッケージ]: https://github.com/zr-tex8r/BXcalc
[BXjaprnind パッケージ]: https://github.com/zr-tex8r/BXjaprnind

--------------------------------------------------

### 対応環境

  - TeX フォーマット： LaTeX2e
  - TeX エンジン： パッケージ毎に異なるので各々の解説文書を参照。
    一般に、その処理系で原理的に対応可能な場合はできるだけ
    対応するように努めている。
    ただし、「CJK パッケージによる日本語組版」には非対応であり、
    将来も対応する予定は無い。
  - 依存パッケージ： 各パッケージ毎の解説文書を参照。

### インストール

TDS 1.1 に準拠するシステムの場合、以下のようにファイルを移動する：

  - *.sty      →  $TEXMF/tex/latex/BXjatool/

この後必要に応じて mktexlsr を実行する。

bxjacalcux パッケージ ― pTeX 専用の長さ単位のサポート
------------------------------------------------------

pTeX 専用の zw や Q 等の長さ単位を他エンジンの LaTeX でも使用可能に
する。

詳細は解説文書 bxjacalcux.pdf を参照。

### 更新履歴

  * Version 0.2a 〈2013/05/05〉
  * Version 0.2  〈2012/05/20〉

bxjafsize パッケージ ― 和文規準でのフォントサイズ指定
------------------------------------------------------

和文スケールが施されている状態で、フォントサイズの指定を和文を規準
（「和文を～ptにする」の様）に行えるようにする。

詳細は解説文書 bxjafsize.pdf を参照。

### 更新履歴

  * Version 0.2a 〈2013/05/05〉
  * Version 0.2  〈2013/04/27〉

----------------------------------------
Takayuki YATO (aka. "ZR")  
http://zrbabbler.sp.land.to/
