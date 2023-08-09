master - 本番環境用　バグFIXしたもののみmasterへcommit
release - 開発環境の大元ソース　devlopにて改修をかけたバグ改修が完了したもののcommit先
devlop - バグ改修時の開発先　ここで改修をかけ終わったものをreleaseへcommit
feature/** - 各案件での開発時にブランチを作成して対応
feature/++ - 各案件先で納品後改修が入ったものや追加改修が入った場合にブランチを作成して対応

コメントの記載について
"機能名　日付　修正内容"

例："入庫入力　20230809　商品名の入力桁数を20から50へ変更"

構成
master
|
|-release
|
|-devlop
||
||-feature/**
|||
|||-feature/++