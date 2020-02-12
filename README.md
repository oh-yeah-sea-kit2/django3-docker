# Django3 docker-compose

## 起動方法
- git clone https://github.com/oh-yeah-sea-kit2/django3-docker.git
- docker-compose build
- docker-compose run python ./manage.py makemigrations
- docker-compose run python ./manage.py migrate
- docker-compose up -d

### ユーザ作成
- docker-compose run python ./manage.py createsuperuser
  - dev:dev

## Pythonコンテナにログイン
- docker-compose exec python bash

## URL
- http://localhost:8000/admin

## 参考リンク
- https://qiita.com/kenkono/items/6221ad12670d1ae8b1dd
- 

