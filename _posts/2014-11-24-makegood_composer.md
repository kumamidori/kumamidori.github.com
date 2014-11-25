---
layout: post
title: "PHPUnit tests in Eclipse - MakeGood, Luna and Composer -"
description: ""
date: 2014-11-24 00:00:00
category: "php"
tags:
- php
---
{% include JB/setup %}


## PHPUnit tests in Eclipse - MakeGood, Luna and Composer -

[MakeGood](https://github.com/piece/makegood) is a continuous test runner to run unit tests on Eclipse PDT.

### Environment

- Mac 10.9 Maverics
- PHP : 5.6 (Liip binary), Xdebug enabled
- Eclipse for PHP Developers, Luna Service Release 1 (4.4.1)
- MakeGood
- **PHPUnit 4 via project's composer (local install)**

### Configure Eclipse (Project - [properties])

#### MakeGood

- [General]

[Add] your [Test Folders]. 
Set the [Preload Script] to your bootstrap file.

Example:

```
[Test Folders] your-project_path/src, 
[Preload Script] bootstrap_test.php
```

<img src="/assets/images/201411/1_properties_makegood_general.png" />

- [PHPUnit]

Set the path to the phpunit xml file under the PHPUnit tab.

<img src="/assets/images/201411/2_properties_makegood_phpunit.png" />

#### PHP - [Build Path]

Your project path.

<img src="/assets/images/201411/3_properties_buildpath.png" />

### And you're DONE!

Everything should be ready now. 
If you can't see the MakeGood tab already, browse to Window > Show View > MakeGood.

<img src="/assets/images/201411/5_makegood-show-view1.png" />

<img src="/assets/images/201411/6_makegood-show-view2.png" />

... and see the results ...

<img src="/assets/images/201411/7_phpunit_results.png" />

Happy TDD-ing♪

### Links

- <a href="https://github.com/piece/makegood">MakeGood (Github wiki)</a>
- <a href="http://blog.loftdigital.com/running-phpunit-tests-in-eclipse-pdt" >Running PHPUnit tests in Eclipse PDT - blog.loftdigital.com</a>
