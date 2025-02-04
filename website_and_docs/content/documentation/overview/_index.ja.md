---
title: "Overview"
linkTitle: "Overview"
weight: 1
description: >
  Is Selenium for you? See an overview of the different project components.
aliases: ["/documentation/ja/introduction/"]
---

{{% pageinfo color="warning" %}}
<p class="lead">
   <i class="fas fa-language display-4"></i> 
   Page being translated from 
   English to Japanese. Do you speak Japanese? Help us to translate
   it by sending us pull requests!
</p>
{{% /pageinfo %}}

Seleniumは一つのツールやAPIではありません。たくさんのツールから構成されています。

## WebDriver

デスクトップのウェブサイトのテスト自動化をはじめるのなら、WebDriver APIを使いましょう。
[WebDriver]({{< ref "/webdriver.md" >}}) はブラウザ自動化のAPIを使用します。このAPIは、ブラウザをコントロールしてテストを実行するためにブラウザベンダーによって提供されています。これは現実のユーザーがブラウザを操作するかのように動きます。
WebDriverのAPIはアプリケーションのコードと一緒にコンパイルする必要がありませんから、全く邪魔になりません。
これによって、あなたは本番環境と同じアプリケーションをテストすることができます。

## IDE

[IDE](https://selenium.dev/selenium-ide) (Integrated Development Environment: 統合開発環境)はSeleniumのテストケースを開発するためのツールです。
これは利用しやすいChromeとFirefoxの拡張機能であり、テストケースを開発するための一般に最も効率的なツールです。
IDEはあなたのブラウザ上で、その要素で定義されたパラメーターと共にSeleniumのコマンドを使いユーザーの動作を記録します。
これは時間の節約だけでなく、Seleniumスクリプトのシンタックスを学ぶための優れた方法です。


## Grid

Selenium Grid を使用すると、さまざまなプラットフォームのさまざまなマシンでテストケースを実行できます。
テストケースの起動の制御はローカル端末で行われ、テストケースが起動されると、
リモート端末によって自動的に実行されます。

WebDriverテストの開発後、複数のブラウザーとオペレーティングシステムの組み合わせでテストを実行する必要が出てくる場合があります。
ここで [Grid]({{< ref "/grid.md" >}}) が登場します。