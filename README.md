# SQL練習
[スッキリわかるSQL入門 第2版](https://sukkiri.jp/books/sukkiri_sql2)の練習問題の実装です。

## 環境構築
### Docker環境
Python用のUbuntu環境とPostgreSQL環境のコンテナを作ります。
下記コマンドでコンテナのbuildを行い、バックグラウンドでコンテナを起動します。
```
docker-compose up --build -d
```
下記コマンドでPython用のUbuntu環境に入ります。
```
docker-compose exec app bash
```

### Python用のUbuntu環境
下記コマンドで必要なPythonパッケージをインストールできます。
```
poetry install
```

## サンプルデータ
`code-ssql2.zip`を[公式サイト](https://sukkiri.jp/books/sukkiri_sql2/sukkiri_sql2_download.html)からインストールします。
ファイルの内容自体はCreative Commons BY-SA 4.0に準拠しています。
ファイルの利用は書籍を持っている方のみとされています。

## コード
[SQL](./SQL)内に各チャプターの練習問題の実装を置いています。
SQLをインタラクティブに実行するためにjupyter notebook上でsqlalchemyを利用してSQLを実行しています。