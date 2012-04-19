wasavi (VI editor for any web page)
====================================

これはなに？
------------

wasavi はいくつかの web ブラウザ用のエクステンションで、web ページ上の textarea
要素を vi エディタ化します。

wasavi はほぼすべての vi コマンド、およびいくつかの ex コマンドをサポートしま
す。



インストール
------------

現在、以下の web ブラウザ用のエクステンションが用意されています。

* Google Chrome
  <http://appsweets.net/wasavi/wasavi.crx>
* Opera
  <http://appsweets.net/wasavi/wasavi.oex>
* Firefox
  <http://appsweets.net/wasavi/wasavi.xpi>

以上のブラウザ用のエクステンションの標準的なインストール方法に従って導入してく
ださい。

Google Chrome において、github に公開されているソースを実行する場合は、「パッ
ケージ化されていない拡張機能を読み込む...」で manifest.json を与えてください。



使い方
------

適当な web ページの textarea 要素にフォーカスがある状態で Ctrl+Enter、もしくは
Insert を押下してください。言うまでもありませんが、終了するには ZZ、:q、:wq な
どを入力します。



バグってる！
------------

ぜひ現象と再現方法を教えてください。
バグレポートや要望の受け付けは以下の場所で行います。
  <http://appsweets.net/wasavi/#forum>
github のアカウントを持っているなら issue でも構いません。
  <http://github.com/akahuku/wasavi/issues>
