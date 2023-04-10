hello-world
===========

test
テストしてます。
1.クローンして複製、デフォルトだと自動的にチェックアウト
git clone https://github.com/aoisan/hello-world.git

2.ファイルを編集
「README.md」を編集

3.現在の状態確認
git status

編集したファイルの差分を確認
git diff

4.編集したコミットしたいファイルを指定
git add README.md

4.編集したファイルをローカルにコミット
git commit -m "[update]文章編集"

コメント簡易版
fix:バグ修正
add:追加
update:（バグではない）修正、更新
remove:削除

Redmineなどのチケットの紐づけ
refs #xxx コメント



5.フェッチして、リモートリポジトリが変更されていないか、確認する。
git fetch https://github.com/aoisan/hello-world.git

リモートリポジトリを確認
git remote -vv

6.プッシュして、ローカルの変更をリモートリポジトリに反映する。
git push origin master


XX.リモートリポジトリへ新規情報を追加
git remote add origin https://github.com/aoisan/hello-world.git


