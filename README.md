# django-chat

Django周りの練習として[この記事](https://www.hiramine.com/programming/chat_django_channels/index.html)を参考にチャットアプリ作成を写経します。  
余裕があれば、デザインの変更など諸々改修していきたいと考えています。  


# コンテナの起動

```shell
docker-compose build
docker-compose up -d
```

# Poetryを介してのmanage.pyの実行

```shell
docker-compose exec django poetry run python manage.py hogehoge
```

# 参考

## 環境構築

- [Django3.0の開発環境をDocker,Docker-compose,Poetryで作ってみた](https://qiita.com/k4ssyi/items/b8d1355fed43b526aee1)