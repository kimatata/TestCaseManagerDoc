# TestCaseManagerDoc

[Docusaurus](https://docusaurus.io/)により生成。

## ローカルでのサーバー起動準備

### nodeをインストール

[https://nodejs.org/en/download](https://nodejs.org/en/download)

### パッケージインストール

```
$ npm ci
```

## ローカルでのサーバー起動

### Installation

```
$ npm run start
```

## Github pagesへのデプロイ

### ビルド

```
$ npm run build
```

このコマンドにより`build`配下に静的コンテンツが生成される。
### デプロイ

SSHの場合

```
$ USE_SSH=true npm run deploy
```