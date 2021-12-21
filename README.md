## 概要
* WPテーマ作成やプラグイン作成用のdocker-composeファイル
* editorconfig用ファイルも追加

## 手順
* `.env.sample`を`.env`にコピー(リネーム)
```
$ cp .env.sample .env
```
* `.env`を修正
* コンテナの起動
```
$ docker-compose up -d
```
