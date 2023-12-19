## URL
「Uniform Resource Locator」の略で、
Web上にあるファイルやホームページの位置を示すためのもの
インターネット上の住所の様なものアドレスとも呼ばれる。

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
サーバーに情報を送るためにURLの末尾につけ足す文字列（変数）のこと
「?」をURLの末尾につけ、その次に「パラメーター＝値」をつける。
複数のパラメーターをつけたい場合は「&」を使用する。
検索クエリ、ページ番号、フィルタ条件などの情報を伝えるために使用される。
 ex)https://www.〇〇〇.co.jp/□□□/■■■/△△△.html?●=▲■&○=△□
?以降がクエリ文字列。この場合●の項目が▲■かつ○の項目が△□なもの

## パス変数
URLのパス部分に渡された値を変数として取り出して利用する機能
 ex)https://www.〇〇〇.co.jp/users/12345
この/users/12345の部分

クエリ文字列とパス変数の違いとは
クエリパラメーターはURLのパス後に追加される形式
パスパラメーターはURLのパス内に直接組み込まれる形式

ttps://jp.mercari.com/search?brand_id=7545
DSMagazine https://ds-b.jp/media/
ホームページ作成大学　https://www.best-hp.jp/univ/
デジハリONLINE https://online.dhw.co.jp
アイティーエム https://www.itmanage.co.jp/

HTTPメソッド
サーバーに対して実行したいアクションを指定する文字列

