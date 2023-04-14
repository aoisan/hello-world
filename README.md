hello-world
===========
`*.md`をテストしてます。


## ローカル内の開発用ブランチをメインブランチへマージする

1. まず、メインへ移動
```
    git checkout master
```
2. メインへ移動後、開発用ブランチをメインへマージ
```
    git merge develop
```


## プッシュして、ローカル「master」の変更をリモートリポジトリに反映する
    git push origin master

## 不必要なブランチを削除する
    git branch -d develop