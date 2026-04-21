# 参考
https://core-tech.jp/blog/tech_log/4413/

# 起動
`docker compose up -d`

# 終了
`docker compose down`

# php-apacheのサーバーに入る。(composerなどはここで実行)
`docker compose exec php-apache /bin/bash`

# databaseのサーバーに入る。
`docker compose exec database /bin/bash`

## mysqlのサーバーに入る。
mysql -u root -p

# ブラウザ
http://localhost:8080/
