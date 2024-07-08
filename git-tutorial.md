gitの機能
 gitは分散管理型のバージョン管理システムであり，変更履歴の保存，変更した箇所に戻ることが可能という利点に加え，他人と共同編集できるツールである．

gitのコマンドは多くのあり，以下のようにまとめる．
(設定・確認系)
・git init : gitの初期化，設定開始
・git status : ワークツリーのステータスを表示
・git config : 設定まわりの確認，変更
・git log : ログを表示 (--onelineでコミットメッセージの一行のみの一覧表示)
・git diff : ファイルの差分を表示

(コミット系)
・git add : ステージングエリアに追加
・git commit : コミットの実行

(修正系)
・git commit --amend --no-edit : コミットの修正
・git checkout : 削除されたファイルを復旧や過去コミットの復元など
・git reset : コミットのリセット
・git revert : 「コミットの変更を打ち消す」コミット
・git rm : ファイルとindex情報の削除

(リモート系)
・git clone : レポジトリをコピー
・git pull : リモートレポジトリの同期
・git push : 変更をアップロードする
・git request-pull : プルリクエスト，変更依頼
・git remote : リモートレポジトリの設定

(ブランチ系)
・git branch : ブランチの作成
・git checkout : ブランチの切り替え
・git merge : ブランチの統合
・git clone : レポジトリをコピー
・git push : 変更をアップロードする
