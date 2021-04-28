# docker-composeを使ってalmonshを楽々セットアップ

https://almond.sh/

almondは使いたいけど、ローカルでインストールしたくない人むけ。docker bind mountを利用しているため、
`work`ディレクトリで保存されたものはこちらの`work`ディレクトリにも保存される。その逆も然りで、
こちらの`work`ディレクトリに存在するものはjupyter上で使用可能。

実行する際は下記リンクからイメージを選んで実行してください

https://hub.docker.com/r/almondsh/almond

## 実行方法

```terminal
> docker-compose up
...
 http://127.0.0.1:8888/?token=fb557**********************8cb <- このリンクにアクセス
```

## 停止

```terminal
> docker-compose down
```