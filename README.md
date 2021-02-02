# Licking test for analysis

リック解析式選択嗜好実験システム LKP2で出力されたファイルをクラスター解析するためのコードになります。

それ以外の実験機器でもおそらくデータ処理は対応可能です。


# DEMO



# Features



# Requirement

anacondaを前提にしています。

# Setting

最初のセルにファイルのパスなどを書き込んでください。


# Note


上手く出力されない場合：
1.データまとめのデータを抽出するセルが自身のエクセルファイルと想定ファイル対応しているか確認してください。

リック試験のアプリケーションによっては、想定している書式と違うかもしれません。

一度にデータ処理できるのはAZの列までです。

バーストサイズを出したい場合:
get_between_zeros(a, 5, True)　を5から10に変えてください。


# Author

作成情報を列挙する

* 伏見駿亮(Fushimi Shunsuke)
* Kyoto U
* f.shunsuke0402@gmail.com

# License
ライセンスを明示する

[MIT license](https://en.wikipedia.org/wiki/MIT_License).


