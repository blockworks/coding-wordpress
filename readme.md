# coding-wordpress

* WordPress向けコーディングファイル郡です。
* package.jsonおよびgulp(gulpfile.js)を使い、Webコーディングに便利なデータを入れています。

## 作業の流れ

1. Coding Filesを自分のパソコンにclone（ダウンロード）します。

``git clone git@github.com:blockworks/coding-wordpress.git``

2. ダウンロードしたディレクトリへ移動します。

``cd coding-wordpress``

3. gulpの関連ファイルをインストールします。（package.jsonの内容を元に自動でインストールされます）

``npm install``

4. 対象ファイルを監視します。（ブラウザが起動します）

``gulp``


## ファイル構成の説明

* ``gulpfile.js``…gulpプラグインを使用するためのプログラムが記述されています
* ``package.json``…gulp関連ファイルをインストールするための設定ファイルです
* ``readme.md``…このファイルです


## cssディレクトリ、ファイルについて

css/*.scssのファイル群の内容をコンパイルし、Wordpress基準となるstyle.cssへ全cssコードを統合するようになっています。

scssとcssを別ディレクトリにする必要性を感じないため、cssにまとめています。

``style.scss``から``_reset.scss``、``_sp.scss``、``_pc.scss``の順番で読み込み、最終的にstyle.cssにひとまとめにされます。


## jsディレクトリ、ファイルについて

* 個人的によく使うjQueryプラグインを同梱しています。

* jquery.usercode.jsには、個人的によく使うコードを記載しています。不要なコードは削除してください。


## その他

* htmlには、使う可能性のあるコードをすべて記述しています。不要なコードは削除してお使いください。
