# dev-container-django

django 開発環境用（DB:MySql）

# Python

## Version

3.8.0

## ソース格納先

.code

# MySql

## データベース名

mydb

## ユーザー名

test_user

## パスワード

password

## root パスワード

password

## 起動

```
docker-compose up
```

## 停止（コンテナ／ネットワーク削除）

```
docker-compose down
```

## 停止（コンテナ／ネットワーク／イメージ／ボリューム削除）

```
docker-compose down --rmi all --volumes
```

## PHPMyAdmin

http://localhost:8080

## Package Install

```
pip install django
pip install mysqlclinet
pip freeze > requirements.txt
```

## Database Setting

settings.py
```python
'ENGINE': 'django.db.backends.mysql',
'OPTIONS': {
  'read_default_file': '/code/my.conf',
},
```

## Run Server

```
python manage.py runserver 0:8000
```