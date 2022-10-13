# web-message-board
ユーザー名、投稿内容を入力できる掲示板アプリです。
投稿された内容はページ下部に表示され、削除ボタンで削除することも可能です。
PHPでデータベースを扱う練習のため作成しました。

## コンテナ起動

起動するときは以下のコマンドを入力します。
プロジェクトルートでコマンドを実行する必要があります。

```sh
# Start
$ docker-compose up -d
```

## アクセス

コンテナ起動中は、以下の URL にアクセスできます。

<http://localhost:8080/>

Herokuでdeployされているので以下URLからもアクセスできます。

https://web-message-board-ice.herokuapp.com/

## コンテナ終了

制作終了時は以下のコマンドでコンテナを終了します。

```sh
$ docker stop web-message-board
```
