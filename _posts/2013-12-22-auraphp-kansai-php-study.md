---
layout: post
title: "Aura for PHP で Hello World（第12回関西PHP勉強会に参加してきた）"
description: ""
date: 2013-12-22 00:00:00
category: "php"
tags:
- php
- aura_php
---
{% include JB/setup %}

第12回関西PHP勉強会に参加しました。もくもく会でした。

各自、好きな作業をする、という趣旨で、私は「フレームワーク、<a href="http://auraphp.com/" target="_blank">Aura for PHP</a>をさわってみる」というテーマにしました。

### このテーマを選んだ理由

これのマニュアル翻訳を一部やったので、実際にさわってみようと思って。
<a href="http://auraphp.com/manuals/v1/ja/" target="_blank">http://auraphp.com/manuals/v1/ja/</a>

### Aura for PHP の特徴

- <a href="http://auraphp.com/" target="_blank">公式マニュアル</a>より引用：

> Auraの主な目標は、標準に準拠し、どのコードベースでも使うことができて、
> 高品質にテストされた、疎結合なライブラリを提供することです。

- 「疎結合なライブラリ」とは？

Auraのドキュメントに、「Library First, Framework Second」とあります。
独立したパッケージの集合なので、開発者の好きなように、プロジェクト全体で使うこともできれば、
一部だけを取り入れて使うということもできます。

Composerの流れを受けて出てきたコンポーネント志向、ということかなと思います。

- リードは、Zendのコミッタ等された、PHP-FIG策定メンバー、<a href="http://paul-m-jones.com/" target="_blank">pmjones</a>さん。

### とりあえず Hello World するには？

<a href="http://auraphp.com/framework" target="_blank">http://auraphp.com/framework</a>

↑この手順ママで即動くので省きます。
注意点は、「Remove the Demo Package」というセクションの手順を飛ばさないでやることくらい。

### 作ったもの

<a href="https://github.com/kumamidori/HelloAura" target="_blank">https://github.com/kumamidori/HelloAura</a>

<strike>ちょっとしか動かせていない！ので、コードの説明は省きます。もうちょっと理解が進んだら、また別記事として書きたいところ。</strike>

→ 後日ちょっと進められたので、別記事を<a href="http://kumamidori.github.io/php/2013/12/23/auraphp-01-di" target="_blank">こちら</a>に書きました。


もくもく会の当日お世話になった皆様、ありがとうございました！

### 関連リンク：イベント参加者レポート

- <a href="http://www.1x1.jp/blog/2013/12/phpdbg.html">PHP 5.6 に採用されるデバッガ phpdbg を使ってみた</a>
- <a href="http://tanakahisateru.hatenablog.jp/entry/2013/12/22/030817">PHP関西勉強会でYii2-alphaを試しました</a>

#### 関連リンク：Aura for PHPの紹介記事

- <a href="http://yuubiseiharukana.blog.shinobi.jp/Entry/1168/" target="_blank">http://yuubiseiharukana.blog.shinobi.jp/Entry/1168/</a>
