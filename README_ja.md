# netlify-410

[English](README.md) / 日本語

Netlify を使用し、全ての HTTP アクセスに HTTP ステータスコード 410 を返します。

## How to use

1. このリポジトリをフォークします。
1. フォークしたリポジトリから、Netlify で新しいサイトを作成します。
1. サイト設定、デプロイ設定を行います、. Basic build settings には何も入力する必要はありません。
1. Netlify で Custom domain の設定を行います。あなたが使用しているDNSサービスでCAMEレコードを追加します。
1. CNAME レコード追加が Netlify 側で確認が出来たら、サーバー証明書が自動的に作成され、 HTTPS でサイトにアクセス出来るようになります。

## Sample site

[![Netlify Status](https://api.netlify.com/api/v1/badges/e5b953ea-0d12-4ec9-8720-6d98dd2153d1/deploy-status)](https://app.netlify.com/sites/sharp-einstein-854dcc/deploys)

サンプルサイトは [こちら](https://sharp-einstein-854dcc.netlify.app/) にあります。

このサイトは main ブランチが自動的にデプロイされます。

## Lisence
[MIT License](https://github.com/cyber-gene/netlify-410/blob/main/LICENSE)

## Author
[cybergene](https://github.com/cyber-gene)