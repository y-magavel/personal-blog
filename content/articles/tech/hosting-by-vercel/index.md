---
title: "ホスティングサービスとしてVercelを使ってみた。"
description: "静的ホスティングサービスについての感想記事です。"
date: "2022-08-13"
banner:
  src: "../../../images/kelly-sikkema-Hl3LUdyKRic-unsplash.jpg"
  alt: ""
  caption: ""
categories:
  - "ホスティングサービス"
keywords:
  - "ホスティングサービス"
  - "Vercel"
  - "Gatsby.js"
---

こんにちは👋 Magavelです。

今回は、ホスティングサービスについての話です。

この個人ブログ兼ポートフォリオサイトは、Gatsby.jsで構築し、Vercelでホスティングしています。

他にもホスティングサービスとして有名なところだと、NetlifyとCloudflare Pagesがあると思うのですが、公式サイトのデザインが好みだったVercelを選びました。あのグラデーションで宇宙を連想させるようなデザインが好きです。JetBrainsとかGitHubのようなデザインです。

選定にあたってはZennの下記スクラップを参考にさせていただきました。

- [Cloudflare Pages・Vercel ・Netlify の違いや使い分けをまとめる](https://zenn.dev/catnose99/scraps/6780379210136f)

実際、Vercelを使ってみてデプロイ体験の良さには感動しました。
GitHubと連携してリポジトリを指定するだけでホスティングが完了します。作業時間としては15分もかからなかったです。

独自ドメインの設定も提示されるIPアドレスをDNSにAレコードとして登録するだけです。ちなみにDNSサーバはVercelのサーバではなくGoogle Domainsのサーバを使いましたが、1〜2時間後には独自ドメインでのアクセスができるようになっていました。

以上です。