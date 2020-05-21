# nuxt-typescript(SPA)
nuxt-typescript(SPA)

## WANTED🔥

- [x] PR求む
- [x] ISSUE求む

## 環境構築

クローンして、ローカルのnode_moduleをインポートしましょう。

```
$ git clone <url> && cd <repository-name>
$ yarn install // HaskyをInstallし、コミット時にLintを流します。
```

Dockerのビルドし、Docker内のnode_moduleをインポートしましょう。

```
$ docker-compose build

$ docker-compose run --rm app yarn install
```

アプリの立ち上げ

```
$ docker-compose build
```

以上！課題多そう

```
$ yarn test // テスト
$ yarn lint // 解析
$ yarn lintfix // 自動修正
```

## 入れたいライブラリ群

- [x] TypeScript
- [x] ESLint
- [x] Prettier
- [x] Jest
- [x] Puppeteer
- [x] Sass
- [x] Pug

- Dockerに閉じ込めたい
- Atomic Designを採用
- CSS設計は、とりあえず、Atomic Designを同じ構成にした。記法は考えていない。
