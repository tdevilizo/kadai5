## URL
「Uniform Resource Locator」の略で、
Web上にあるファイルやホームページの位置を示すためのもの
インターネット上の住所の様なものアドレスとも呼ばれる。<br><br>
ex)```https://www.〇〇〇.co.jp/□□□/■■■/△△△.html```
| 名前 | 該当部 | 説明 |
| ---- | ---- | ---- |
| プロトコル | https | インターネットにおけるデータ送受信の規格のようなもの「http」や「https」や「ftp」などがある |
| スキーム | https://| プロトコルに「://」が追加された文字列「://」以前の部分の通信手段に従って通信するを明示するもの |
| ホスト名<br>(サブドメイン) | www | サーバー名「www（World Wide Webの略）」がホスト名とされている場合が多い |
| ドメイン | 〇〇〇 | 該当ページがどこにあるのかを示す住所のような役割を持つ文字列 |
| セカンドレベルドメイン | co | 「.（ドット）」で区切られた右から2番目のドメイン名「.co」(企業)や「.ac」(教育機関)などがある |
| トップレベルドメイン | jp | ドメイン内部の「.com」や「.net」などの、最後に付随する部分 |
| ディレクトリ | □□□/■■■  | サーバー内にあるフォルダの名称※例の場合□□□というフォルダの中に■■■がある |
| ファイル | △△△.html | URLの末尾に記述される「～/index.html」や「～/●●●.html」などの、拡張子のついた文字列 HTML形式のファイルであれば「.html」、画像形式のファイルであれば「.jpg」となる。 

※ホスト名ドメイン系のものを合わせてオーソリティ<br>
ディレクトリ、ファイルを合わせてパスと呼ぶ

## クエリ文字列
サーバーに情報を送るためにURLの末尾につけ足す文字列（変数）のこと<br>
「?」をURLの末尾につけ、その次に「パラメーター＝値」をつける。<br>
複数のパラメーターをつけたい場合は「&」を使用する。
検索クエリ、ページ番号、フィルタ条件などの情報を伝えるために使用される。<br>

ex)```https://www.〇〇〇.co.jp/□□□/■■■/△△△.html?●=▲■&○=△□```<br>
クエリ文字列にあたる部分は?以降の```?●=▲■&○=△□```この場合●の項目が▲■かつ○の項目が△□なもの

## パス変数
URLのパス部分に渡された値を変数として取り出して利用する機能<br>
 ex)```https://www.〇〇〇.co.jp/users/12345```<br>
パス部分にあたる部分は```users/12345```

### クエリ文字列とパス変数の違いとは<br>
クエリパラメーターはURLのパス後に追加される形式<br>
パスパラメーターはURLのパス内に直接組み込まれる形式


### HTTP通信の流れ

クライアントとWebサーバーは以下の手順でやり取りが行われる。

1. クライアント側のPCでブラウザにURLを入力。
2. クライアント側のPCからWebサーバーに「HTTPリクエスト」を送信。
3. Webサーバーが、「HTTPリクエスト」に対応する「HTTPレスポンス」をクライアント側のPCに送信。
4. クライアント側のPCでWebページを表示。





## HTTPメソッド
HTTPリクエストを構成するリクエストラインに記載されてあるサーバーに対して実行したいアクションを指定する文字列<br>
以下のようなものがある。

| 名前 | 説明 |
| ---- | ---- |
| GET | リソース情報を取得する |
| POST | 新しいリソース情報を送り込む |
| PUT | リソース情報を新しい情報で置き換える |
| PATCH | リソース情報の一部を新しい情報で書き換える |
| DELETE | リソース情報を削除する |




