# これはなに

[リクルートライフスタイル Advent Calendar 2019](https://qiita.com/advent-calendar/2019/recruitlifestyle) 8 日目の記事で利用する Babel による Polyfill 注入を確認するためのサンプルです。

サンプルを実行すると `./src/test.js` が Babel で変換されて `./dist` 配下に構文変換と Polyfill が注入された状態で出力されます。

- Babel 7.7.4
- core-js 3.4.7

# 実行環境

node.js 12.13.1 で動作を確認しています。 

（Babel 7.7.4 が動く node.js バージョンであれば問題なく動作すると思います。）

# 実行方法

npm の場合

```
$ npm run babel
```

yarn の場合

```
$ yarn babel
```
