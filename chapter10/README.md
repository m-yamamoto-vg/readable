# 第10章 無関係の下位問題を抽出する

## はじめに
とりあえず小さな問題については、切り出せ(抽出しなさい)。

* 関数やコードブロックなどの1つのまとまりをみて、このコードの一番の目的は何かを問う
* 目的を達成するための直接的なものか、あるいはそれ以外の無関係なものも解決するものか問う
* それ以外の無関係なものも解決するものについては、相当量あれば切り出す

## 10.1 入門的な例
findClosestLocation()

## 10.2 純粋なユーティリティコード
ファイルを読み込み変数に代入する(PHPにおけるfile_get_contentsに相当するもの)

## 10.3 その他の汎用コード
JavaScriptにおけるalert debugの便利関数(PHPにおけるvar_dumpに相当するも)

## 10.4 汎用コードをたくさんつくる

## 10.5 プロジェクトに特化した機能
urlの生成ロジックの切り出し
* どこまで切り出す？
* どこに置く？

## 10.6 既存のインターフェースを簡潔にする(余談:てかインタフェースが正しい？)
JavaScriptのクッキー扱うの悲しすぎる
jquery-cookieを使うためにjQuery使うのも悲しすぎる

#### 雑談
簡潔なインターフェースって何を参考にする？どう調べる？
例えばRouterという単語を聞いた時に、どういうインターフェースがあるって想像がつかない時どう調べる？
(※あんまりRouter -> インターフェースってならなそうだけど・・・)

## 10.7 必要に応じてインタフェースを整える
暗号化処理にプラスしてURL safeな文字列が欲しい

## 10.8 やりすぎ
人間の理解できる意味単位(この単位ってどういう表現が適切だろうか?)に分割すればよい。細かすぎると伝わらない(らしい)。


## 10.9 まとめ
プロジェクト固有のコードから汎用コードを分離すると、プロジェクト固有の大切なことに集中できる(=わかりやすい)

