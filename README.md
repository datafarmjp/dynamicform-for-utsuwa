# dynamicform-for-utsuwa

## a-blog cmsの「utsuwa」で利用するための動的フォームのテンプレートです。

System内の動的フォームフォルダを元に以下の点を変更いたしました。

- utsuwa内のスタイルでフォームを最適化
- unit.htmlで
	- 「recruit」カテゴリとそうでない場合で
	- 見出し、本文の一部をif文にて分岐、最適化
- body.html、adminbody.txtにおいて以下のカスタムフィールドを再利用
	- 郵便番号
	- 住所
	- 電話番号
	- 電話対応時間
- caption欄をフォームに最適化する形で挿入
	- text、textareaはplaceholderとして
	- それ以外はform-helper-text文として
- thanks.htmlは利用しない形に修正

