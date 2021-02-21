# Alamofireを使うための練習用リポジトリ

- サーバーサイド　Rails
- フロントエンド　SwiftUI

iOSアプリでHTTP通信のできるものを目指す。

## 機能

任意の文字を投稿、編集、削除するだけのもの。ログイン機能はつけない。

まずRailsでWEBアプリケーションとしての動作を確認してから同様の操作をSwiftUIで作れるか試す。

## DB設計

### Postテーブル

| Column  | Type   | Option      |
| ------- | ------ | ----------- |
| content | string | null: false |