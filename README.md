# Getting Started

First, run the development server:

## 起動方法

```bash
yarn dev
```

## 事前準備

- yarn への切り替え
- next-authの追加

```sh
yarn add next-auth
```

- 不要なcss設定削除（globals.cssの設定）
- ログイン、トップ、ダッシュボードページを簡易的に生成

- 環境変数を設定

下記コマンドで、ローカル用の.env.localを作成する

```sh
cp .env.local.template .env.local
```

「some-secret」は、ランダムな文字列で置き換える。
