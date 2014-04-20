---
layout: post
title: "「extract till you drop」/PhpStormショートカット"
description: ""
date: 2014-02-09 00:00:00
category: "php"
tags:
- php
- ddd
---
{% include JB/setup %}

今さらだけれど、extract-till-you-drop（「限界まで抽出せよ」） の screencast を見た。

[extract-till-you-drop](http://verraes.net/2013/09/extract-till-you-drop/)

最後は、コードが自然言語みたい。
抽象でわかりやすく。
知識をまとめるとシンプルに。

[道場生レポートブログ](http://phpmentors.jp/post/63422732564/symfony-meetup-tokyo)も読みました。

私もPhpStorm使っているのに、無知過ぎたので、反省メモ。。。

- phpunit、コンソール（手 or grunt-phpunit）で見ていたけれど、エディタも試してみる。エディタでカバレッジも見れるんだ・・・。
- Ctrl + T は [Rename] 以外も便利(namespace、定数、メソッド、シグネチャ）
- Overrideメソッドは、 Cmd + N -> Override… でインクリメンタル検索すると1秒で
- ワード選択後に [Alt] + [Enter] -> [Add field]、[Add import] で自動挿入。
- Cmd + Shift + T でテストクラス作成
- Ctrl + N でphpunitテストメソッド追加もできる
- 一括インデントは [Reformat Code] で

英語が全然分からなかったけれど、モックtestについて、 small and fast だと言っていた。
