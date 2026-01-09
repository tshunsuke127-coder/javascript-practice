# JavaScript 一覧表示アプリ

## 概要
外部APIから取得したデータを一覧表示し、
検索・フィルター・並び替えができるシンプルなWebアプリです。

## 使用技術
- HTML
- CSS
- JavaScript（Vanilla JS）
- Fetch API

## 機能一覧
- APIからデータ取得
- ローディング表示
- エラー表示
- 一覧表示
- キーワード検索
- 並び替え（昇順 / 降順）

## 工夫した点
- stateを使って状態管理を行い、UIとロジックを分離しました
- state → render の一方向データフローを意識しました
- loading / error / data の状態を明確に分けました

## 起動方法
1. このリポジトリをクローン
2. index.html をブラウザで開く
