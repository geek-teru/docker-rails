### 概要
- rails実行用Dockerコンテナ
- Ubuntu 22.04
- Ruby 3.0.2
- Rails 7.0.0

### インストール用URL


### 利用手順
```
# ディレクトリ移動
cd docker-rails

# 起動
docker-compose up -d

# docker接続
docker exec -it rails.local bash

# 停止、削除
docker-compose down --rmi all --volumes --remove-orphans
```
### Rails 設定
```

```

### Rails 起動
```
cd /rails/hello

# bunble install
bundle install --gemfile /rails/hello/Gemfile

# サーバー起動。0.0.0.0からのリクエストを受け付ける
rails s -b 0.0.0.0