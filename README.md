# これは何

これは golang の echo フレームワークを使えるようにするコンテナを定義した dockerfile 。

# この dockerfile の使い方

## echoのみ使いたい！
1. dockerfile ビルドする
2. ビルドしたイメージを run
3. `/home/workspace` に app フォルダ結びつけてね

## echo + mysql を使いたい!
1. `docker-compose up` する
2. `/home/workspace` に app フォルダ結びつけてね

### mysql に入る時
1. `go_db` が DB 名
2. `password` が Password