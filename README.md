## なにコレ
ブラウザ上で動くUserscriptです

ふたば☆ちゃんねるのカタログに現在表示されているすべてのスレ本文の文字列を監視してページトップに一覧表示します。  
一度検索ワードを設定しておけば定時スレ等が探しやすくなります。  


Firefox + [Greasemonkey](https://addons.mozilla.org/ja/firefox/addon/greasemonkey/),  
Chrome + [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo),  
Opera(ver.15+) + [Tampermonkey](https://addons.opera.com/extensions/details/tampermonkey-beta/)  
で動作確認済みです


※このUserscriptは[赤福Firefox SP](http://toshiakisp.github.io/akahuku-firefox-sp/)と[ふたクロ](http://futakuro.com/)に対応しています。

## 使い方
* ふたばのカタログモードの設定で「文字数」を適当な大きさ(4以上推奨)に設定してください。(板毎に設定が必要です)
* スレッド検索該当スレッドの[設定]ボタンをクリックして監視したい検索ワードを入力してください。
|で区切ると複数の語句を指定できます。(正規表現使用可。特殊な記号　\*?+.^$|()[]{}　は全て正規表現のメタキャラクタとして認識されます。)
(Ver.1.5)検索ワードは全板共通と各板個別でそれぞれ設定できます。

## 注意事項
Firefoxアドオン[ねないこ](http://nenaiko.sakura.ne.jp/nenaiko/)と併用する場合は、ねないこの設定より「カタログ2」→「カタログ本文のスタイルを指定する」のチェックを外してください。

## おまけ
スレ本文の文字数を増やしたらカタログが見づらくて生きるのが辛い場合  
こちらのユーザースタイルシートも使ってみてください。  
[futaba_catalog_mod(モダンバージョン)](https://userstyles.org/styles/114129/futaba-catalog-mod-modern)  
または  
[futaba_catalog_mod(クラシックバージョン)※ねないこユーザー向け](https://userstyles.org/styles/114130/futaba-catalog-mod-classic)

## 更新履歴
* v.1.6 2015-12-12
  - 設定画面に区切り文字を挿入ボタンを追加
  - 検索ワードの正規表現の処理を修正
* v1.5 2015-07-07
  - 板毎の検索ワードの設定を追加
  - 削除した検索ワードのハイライトが残ったままになる問題を修正
* v1.4 2015-05-21
  - スタイルの調整
  - アイコン追加
* v1.3 2015-05-19
  - スタイルの調整
* v1.2 2015-05-18
  - スタイルの変更
  - 文字スレがマッチした場合の不具合修正
