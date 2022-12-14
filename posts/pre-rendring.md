---
title: 'プリレンダリングの2つの形態'
date: '2020-01-01'
---

Next.jsでは、プリレンダリングに2つの形式があります。**静的生成**と**サーバーサイドレンダリング**です。違いは、ページのHTMLをいつ生成するかという点です。

- 静的生成**は、**ビルド時**にHTMLを生成するプリレンダリング方法です。プリレンダリングされたHTMLは、各リクエストで再利用されます。
- サーバーサイドレンダリング** は、リクエストごとにHTMLを生成するプリレンダリング方式です**。

重要なのは、Next.jsでは、各ページで使用するプリレンダリング方式を**選択できることです。ほとんどのページで静的生成、その他のページでサーバーサイドレンダリングを利用することで、「ハイブリッド」なNext.jsアプリを作成することができます。