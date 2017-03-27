# Coding WordPress

* 個人的にWordPressのテーマ制作をするための最初の雛形ファイルです。
* package.jsonおよびgulp(gulpfile.js)を使い、Webコーディングに便利なデータを入れています。
* サンプル画像やCSSも入っています。

## 作業の流れ

1. Coding Filesを自分のパソコンにclone（ダウンロード）します。

2. ダウンロードしたディレクトリへ移動します。

3. gulpの関連ファイルをインストールします。（package.jsonの内容を元に自動でインストールされます）

``npm install``

4. 対象ファイルを監視します。（ブラウザが起動します）

``gulp``


## ファイル構成の説明

* gulpfile.js…gulpプラグインを使用するためのプログラムが記述されています
* LICENSE…このファイル郡のライセンスです
* package.json…関連gulpファイルをインストールするための設定ファイルです
* readme.md…このファイルです

## その他

* htmlには、使う可能性のあるコードをすべて記述しています。不要なコードを削除してお使いください。