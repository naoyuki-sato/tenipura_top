# tenipura_top

## 更新手順
- まずはここでファイルを更新
- npm run devでファイル更新
- npm run buildでminmizeを行い、index.htmlとassetsファイルを作成する
- index.htmlのパスを変更しないと次のページで公開出来ない
```
    <script type="module" crossorigin src="https://naoyuki-sato.github.io/tenipura/assets/index-Bn5v2N5_.js"></script>
    <link rel="stylesheet" crossorigin href="https://naoyuki-sato.github.io/tenipura/assets/index-RqBkh1U7.css">
```
- 上記を行ったら、index.htmlをtop_page.htmlにして以下のレポにコミットする

https://github.com/naoyuki-sato/tenipura/tree/main

場所はdocsした。

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
