---
layout: post
title: "はじめてのSymfony2 - 2.4でファイルアップロード -"
description: ""
date: 2014-01-02 00:00:00
category: "php"
tags:
- php
---
{% include JB/setup %}

こういう自分専用のメモは、ブログじゃなくてローカルに保存した方が良いかな、と悩みつつ。

Symfony2を使ったことが一度も無い。それだと何かと困る（仕事じゃなくて、個人学習上）。入門することにした。

プルリク歓迎の日本語訳プロジェクトもあるのでした（内容が一部古いけれども）。<a href="http://docs.symfony.gr.jp/" target="_blank">Symfony2 books 日本語訳</a>。
オリジナルのブログチュートリアルもあって勉強になります。


### サンプルコード仕様

#### ファイルアップロード

- ファイルをアップロードできる
- ファイル一覧ページ（ホーム）が見られる

※そのうちコレをやりたいけど、今日はできなかった→<a href="http://rosylilly.hatenablog.com/entry/2013/10/21/190019" target="_blank">鳩舎「ファイルアップローダを作ろう」</a>

### 作ったサンプルコード置き場はこちら

<a href="https://github.com/kumamidori/SymfonyMinimamFileUpload" target="_blank">https://github.com/kumamidori/SymfonyMinimamFileUpload</a>

<a href="http://symfony.com/doc/current/cookbook/doctrine/file_uploads.html" target="_blank">公式クックブック「How to handle File Uploads with Doctrine」</a>ママです

### メモ

- このフレームワークで作った結果、自分が仕事で作っている／作ってきた様々なコードよりも、明らかに読みやすいものができた。考えていきたいところ。
- マニュアルと同梱デモコードが充実している。
- マニュアル中のコードは、読みやすさのため、細かいところは端折ってある。そのまま動くコードっていうわけでもない。
- フォームがエンティティとタイプから成る作りは分かりやすかった。エンティティのメソッドをTwigでそのまま使えて感動。これってsmartyでもできるのかな。。。
- フォームの validation.yml は、配置しただけで自動ロードされる
- TODO：Doctrine、DBAL も初めて使ったので学習

### 参考リンク

- [2011年スライド「Symfony2のフォームフレームワーク」（@fivestr）](http://www.slideshare.net/fivestar/symfony2-8203873 "2011年のスライド ")
- [Symfonyユーザ会Googleグループに投稿されていた、実務的なファイルアップロード設計例(@brtriver)](https://groups.google.com/forum/#!topic/symfony-users-ja/J_I1kr_jP_k)
