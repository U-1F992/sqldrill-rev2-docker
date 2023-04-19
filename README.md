# 『書き込み式SQLのドリル 改訂新版』Docker環境構築

[ダウンロードページ](https://wings.msn.to/index.php/-/A-07/978-4-8222-9621-6/)から`workbook.sql`を入手し、このリポジトリのルートに配置する。

```sh
# Start db
docker compose up

# Start client
docker exec --interactive --tty sqldrill-rev2 mysql -p workbook
```

## 参考

- [mysql - Official Image | Docker Hub](https://hub.docker.com/_/mysql)
- [DockerのMySQLコンテナで日本語を使いたい！](https://qiita.com/sun33/items/398479ba586e39dcee13)
