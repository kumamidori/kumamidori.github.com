---
layout: post
title: "Aura for PHPをさわってみる（第12回関西PHP勉強会に参加してきた）"
description: ""
date: 2013-12-22 00:00:00
category: "php"
tags:
- php
---
{% include JB/setup %}

第12回関西PHP勉強会に参加しました。もくもく会でした。

各自、好きな作業をする、という趣旨で、私は「フレームワーク、<a href="http://auraphp.com/" target="_blank">Aura for PHP</a>をさわってみる」というテーマにしました。

### このテーマを選んだ理由

これのマニュアル翻訳を一部やったので、実際にさわってみようと思って。
<a href="http://auraphp.com/manuals/v1/ja/" target="_blank">http://auraphp.com/manuals/v1/ja/</a>

### Aura for PHP の特徴

<a href="http://auraphp.com/" target="_blank">http://auraphp.com/</a>

- 公式マニュアルより引用：

> Auraの主な目標は、標準に準拠し、どのコードベースでも使うことができて、
> 高品質にテストされた、疎結合なライブラリを提供することです。

- 「疎結合なライブラリ」とは？

Symfonyなどのフルスタックフレームワークは、一部のバンドルだけ取り出して使う、といったことが難しいです。
Auraプロジェクトでは、機能がパッケージの集合で、各パッケージが独立していることから、
好きなように、プロジェクト全体で使うこともできれば、一部だけを取り入れて使うということもできます。

Composerの流れを受けて出てきたコンポーネント志向、ということかなと思います。

- リードは、Zendのコミッタ等された、PHP-FIG策定メンバー、<a href="http://paul-m-jones.com/" target="_blank">pmjones</a>さん。

### はじめ方

<a href="http://auraphp.com/framework" target="_blank">http://auraphp.com/framework</a>
このママで動くので略。

### 書いた Hello World 

<a href="https://github.com/kumamidori/HelloAura" target="_blank">https://github.com/kumamidori/HelloAura</a>

ちょっとしか動かせていない！ので、コードの説明は省きます。もうちょっと理解が進んだら、また別記事として書きたいところ。


もくもく会の当日お世話になった皆様、ありがとうございました！

### 関連リンク

#### リンク：イベント参加者レポート

- <a href="http://www.1x1.jp/blog/2013/12/phpdbg.html">PHP 5.6 に採用されるデバッガ phpdbg を使ってみた</a>
- <a href="http://tanakahisateru.hatenablog.jp/entry/2013/12/22/030817">PHP関西勉強会でYii2-alphaを試しました</a>

#### リンク：Aura for PHPの紹介記事

- <a href="http://yuubiseiharukana.blog.shinobi.jp/Entry/1168/" target="_blank">http://yuubiseiharukana.blog.shinobi.jp/Entry/1168/</a>
