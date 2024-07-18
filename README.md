# 授業用画像投稿可能な掲示板

## 起動方法

### コンテナ起動

```sh
docker compose up
```

### テーブル作成

```sh
docker compose exec mysql mysql techc
```

以下のSQLを流し込む

```sql
CREATE TABLE hogehoge ...
```
