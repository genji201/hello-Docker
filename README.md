# hello-docker

### Docker 起動

`$ docker-compose up -d`

### Docker 終了

`$ docker-compose down`

## 動作確認

1. VSCode のプラグイン、[Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)をインストール
2. `$ npm install`
3. Docker を起動
4. コンテナ内でサーバーを起動する
   1. VSCode のプラグイン、Remote-Containers でコンテナにアクセスする。
   2. app/vue-project/ に移動し、サーバーを起動する
      1. `$ npm run serve`
5. ローカルのファイルを編集して、起動中のサーバーに繁栄されれば OK
6. Docker を終了する
