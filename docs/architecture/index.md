---
sidebar_position: 1
---

# アーキテクチャ

![アーキテクチャ](./img/architecture.svg)

システムを疎結合にするためUIを提供するフロントエンドサーバーとAPIを提供するAPIサーバーを分ける。

## フロントエンド

React, Next.jsでUIを作る。

## APIサーバー

ビューの生成は一切行わず、API機能のみ有する。

- DBアクセス
- 認証、認可