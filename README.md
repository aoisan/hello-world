hello-world
===========

Gitをテストしてます。
## 1.クローンして複製、デフォルトだと自動的にチェックアウト
    git clone https://github.com/aoisan/hello-world.git  

## 2.ファイルを編集
「README.md」を編集  


## ファイルを削除
    git rm ToDo.txt  

## 3.現在の状態確認
    git status  

### 編集したファイルの差分を確認
    git diff  

## コミットしたいファイルを指定
    git add README.md  

#### 一度に複数のファイルを指定する場合
    git add README.md *.txt

## 4指定したファイルをローカルにコミット
    git commit -m "[Prefix]コメント"  
    

#### コメント簡易版

Prefix  | 概要
------------- | -------------
fix  | バグ修正
add  | 追加
update  | （バグではない）修正、更新  
remove  | 削除

#### 以下、Redmineなどのチケット紐づけテンプレート
    refs #番号 コメント  


## 5.フェッチして、リモートリポジトリが変更されていないか\確認する。
    git fetch https://github.com/aoisan/hello-world.git  

## リモートリポジトリを確認
    git remote -vv  

## 6.プッシュして、ローカルの変更をリモートリポジトリに反映する。
    git push origin master  


## リモートリポジトリへ新規情報を追加
    git remote add origin https://github.com/aoisan/hello-world.git  

## ブランチの削除
    git branch -d develop




## ブランチ一覧と現在作業中のブランチ表示
    git branch

## 開発のため作業用ブランチ作成
    git branch develop

## 開発用ブランチへ移動
    git checkout develop


## 開発用ブランチをメインへマージする。
#### メインへ移動  
    git checkout master  
    
#### 開発用ブランチをメインへマージ   
    git merge develop  


    
