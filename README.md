# git 基本操作

## git基本操作の流れ
1. issueを作成

2. issue番号と同じブランチを作成、移動

3. そのブランチにリモートの master ブランチから最新版を取り込み

4. 作業

5. 同じブランチにプッシュ

6. pull riquest

7. margeされたのを確認してissueを閉じる

## プッシュ操作の流れ

#ステージングエリアに移動
git add -A

#コミット
git commit -m "メッセージ"

#プッシュ
git push origin ブランチ名

## ブランチ操作

#新しくブランチを作成と移行
git checkout -b "ブランチ名"

#現在のブランチを確認
git branch

#既存のブランチへ移動
git checkout ブランチ名

## 変更分を取り込み

#リモートの master ブランチから最新版を取り込み
git pull origin master

#任意のブランチを取り込み
git pull origin ブランチ名
