# HTMLやJavaScriptのサンプル

簡単なHTMLやJavaScriptでホームページ的なものを作るサンプル。

自分でコードを書くときには、テキストエディタを使用すること。
テキストエディタは、今の時点では
[Visual Studio Code](https://code.visualstudio.com/)がオススメだが、
最初は設定にそれなりの時間がかかるので、授業外で行うこと。

ここに置いてあるソースコードは、いずれもブラウザで開いて実行・動作確認する。
ブラウザは何でも良いが、
[Google Chrome](https://www.google.com/intl/ja/chrome/)
などに付属のデベロッパツールを使うとエラーを発見しやすい。
Google Chromeの場合は、右上の点が縦に3つ並んでいる
「Google Chromeの設定」から「その他のツール」を選び、「デベロッパツール」を
選ぶと起動する。

デベロッパツールの「Console」タブを選んでおくと、コード中の`console.log()`で出力した内容が表示される。
Processingの`println()`で出力した内容が、下の黒い部分に表示されるのと同じイメージ。

ここに置いてあるコードは以下の通り。

* [simple.html](./simple.html):
    一番単純なサンプル。タイトルを設定し、本文に1行だけ表示するもの。
    HTMLのみを使用し、JavaScriptは使っていない。
* [image.html](./image.html):
    画像を表示するサンプル。HTMLを使って貼るのが簡単で一般的だが、
    今回はJavaScriptを使用する（恐らくこちらが必要な班が多いため）　。
* [button.html](./button.html):
    ボタンのサンプル。
    ボタンのパーツはHTMLで用意し、押された時の挙動はJavaScriptで書く。
* [simpleDraw.html](./simpleDraw.html):
    [simple.html](./simple.html)に、Processingと同じノリで絵を描く機能を
    追加したもの。絵を描く部分にJavaScriptを用いる。
    偶数回目では塗りつぶした円を、奇数回目では輪郭のみの円を描き、
    何回目の描画かをコンソールに出力する。
* [youtube.html](./youtube.html):
    YouTube動画を埋め込んでJavaScriptから操作するサンプル。Chromeだと動かない。

上記以外にも色々なことができるので、各自でググってみるなどして調べてみること。
例えば、リンクを貼りたい場合などは「HTML リンクの貼り方」などで調べれば良い。
四角を描きたいときには「Javascript Canvas 四角を描く」などで調べれば良い。
その際、検索オプションを設定するなどして、なるべく新しい情報を参照すること。
