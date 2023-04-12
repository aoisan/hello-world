hello-world
===========

Gitをテストしてます。
## 1.クローンして複製2
    git clone https://github.com/aoisan/hello-world.git  

## ファイルを編集する
「README.md」を編集  


## ファイルを削除
    git rm ToDo.txt  

## 3.現在の状態確認
    git status  

### 編集したファイルの差分を確認
    git diff  

## コミットしたいファイルを指定（インデックスに登録する）
    git add README.md  

#### 一度に複数のファイルを指定する場合、
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


## 5.フェッチして、リモートリポジトリが変更されていないか確認する
#### まだローカルには反映されない。
    git fetch https://github.com/aoisan/hello-world.git  


## プルして、リモートリポジトリをローカルリポジトリに反映させる
#### フェッチしてマージするのと同じ
    git pull origin master  
    
## リモートリポジトリを確認
    git remote -vv  

## 6.プッシュして、ローカルの変更をリモートリポジトリに反映する
    git push origin master  


## リモートリポジトリへ新規情報を追加
    git remote add origin https://github.com/aoisan/hello-world.git  




## ブランチ一覧と現在作業中のブランチ表示する
    git branch

## 開発のため作業用ブランチ作成する
    git branch develop

## 開発用ブランチへ移動し、編集する
    git checkout develop


## 開発用ブランチをメインブランチへマージする
#### まず、メインへ移動  
    git checkout master  
    
#### メインへ移動後、開発用ブランチをメインへマージ   
    git merge develop  


## 不必要なブランチを削除する（一般的には残すらしいので例外的に）
    git branch -d develop    



