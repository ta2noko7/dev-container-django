# dev-container-django
django開発環境用（DB:MySql）

# Python
## Version
3.8.0
## ソース格納先
.code

# MySql
## データベース名
test_db
## ユーザー名
test_user
## パスワード
password
## rootパスワード
password

## 起動
docker-compose up

## 停止（コンテナ／ネットワーク削除）
docker-compose down

## 停止（コンテナ／ネットワーク／イメージ／ボリューム削除）
docker-compose down --rmi all --volumes

## PHPMyAdmin
http://localhost:8080
