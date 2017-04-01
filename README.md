BXjatool パッケージバンドル
===========================

laTeX: 和文処理のための小規模なパッケージの集まり。

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

bxcalcize パッケージ ― calc 数式の適応範囲の拡大
-------------------------------------------------

LaTeX 標準命令中の長さ指定でこれまで calc パッケージの数式の使用が
不可だった箇所を可能にする。

詳細は解説文書 bxcalcize.pdf を参照。

### 更新履歴

  * Version 0.2b 〈2017/04/01〉
  * Version 0.2  〈2012/05/20〉

bxcalcux パッケージ ― 新しい長さ単位の追加
-------------------------------------------

ユーザが新しい長さ単位を定義して calc 数式で使えるようにする。

詳細は解説文書 bxcalcux.pdf を参照。

### 更新履歴

  * Version 0.3  〈2013/05/05〉
  * Version 0.2  〈2012/05/20〉

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

bxjaprnind パッケージ ― 行頭の開き括弧の位置の自動調整
-------------------------------------------------------

段落冒頭および強制改行後の行頭における開き括弧の位置をユーザが予め
設定した値に自動的に調整する。

詳細は解説文書 bxjaprnind.pdf を参照。

### 更新履歴

  * Version 0.3a 〈2013/05/05〉
      - 会話用の特別な鉤括弧の処理を追加した。
  * Version 0.3  〈2013/04/29〉
      - everyhook パッケージへの依存を無くした。
  * Version 0.2  〈2012/05/14〉

bxjavert パッケージ ― 縦書き独特の処理のサポート
-------------------------------------------------

「縦中横」や「欧文の正立の縦書き」等の専ら縦書きで現れる特殊な組版
表現をサポートする。

### 更新履歴

  * Version 0.2  〈2013/05/05〉

----------------------------------------
Takayuki YATO (aka. "ZR")  
http://zrbabbler.sp.land.to/
