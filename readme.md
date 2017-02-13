# JavaScriptで差分ファイル出力
### 概要
JavaScriptの勉強として自分の欲しいツールを作成する。
ライブラリに依存しないピュア？なJavaScriptで。

### やりたい事
1. newFile と oldFile を取得
2. それぞれソート
3. newFile minus oldFile をdiffFileとして出力
4. oldFileを削除
5. newFileをoldFileにリネーム

### 出来た事
1. newFile と oldFile の取得
- 配列に行単位で代入してソート
- 表示
- 差分をダウンロードファイルとして出力

何度もJavaで作り直したくなった。。。
結局、削除やらリネームやらのファイル操作は出来ず終い。
