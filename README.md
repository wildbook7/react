# react2021

https://ics.media/entry/16329/#webpack-ts-react

「webpack+TypeScript+Reactの最小構成」を Express と組み合わせて
動きを確認する。

- 初回『 package.json』から作成する場合
```
npm init -y
npm i -D webpack webpack-cli typescript ts-loader
```
- 「git clone」を使用する場合
```
npm run build
node app.js
```

path | page
---- | ----
/           | "Hello World!"
/index.html | "Hello React!" (表示されなければ更新操作をしてみる)
