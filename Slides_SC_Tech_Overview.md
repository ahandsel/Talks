---
theme: light-icons
layout: intro
image: ./background/green_forest_2-andrew-coelho-aL7SA1ASVdQ-unsplash.png
favicon: ./Kintone/KDP_favicon.png
selectable: true
download: true
exportFilename: Slides_SC_Tech_Overview.pdf
title: 2022 SC Training - SC Tech Overview - Bilingual Slides
---

<!-- markdownlint-disable -->

<div class="mb-4 absolute top-20 right-12" style="text-align: right;">
  <div>
    <span class="text-6xl text-primary-lighter text-opacity-80" style="font-weight:500;text-align: right;">
    基礎技術概論
  </span>
  </div>
  <div class="text-3xl text-white text-opacity-60" style="font-weight:600;text-align: right;">
    <br>
    きそ ぎじゅつ がいろん
    <br>
    2021年 新人研修 - 伊藤 柾人
    <br><br>
    2022 SC Training - SC Tech Overview
    <br>
    Japanese by Satoshi Ito
    <br>
    English translation by Genji
  </div>
</div>

<div class="absolute bottom-5 left-12">
  <span @click="$slidev.nav.next" class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-60 flex justify-center items-center">
    Press Space for the next page  <light-icon icon="arrow-narrow-right" size="24px"/>
  </span>
</div>

<!--
基礎技術概論  
きそ ぎじゅつ がいろん
-->

---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  Concept / コンセプト
</div>

::left::

### ターゲット
SC本部メンバー

### バリュー
SC本部で必要なスキルセットが分かった

SC研修の各講義でどんなことを学ぶのかを  
大まかに知ることができた

::right::

### Target
New members joining the SC department!

### Value
Overview of the required skill set for working in the SC dept.

Overview of the upcoming SC training lectures

<!--
SC ほんぶ で ひつような Skill Set が わかった

SC けんしゅう の かく こうぎ で どんな こと を まなぶ の か を おおまか に しる こと が できた
-->

---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  SC本部で必要なスキル / Required Skills at SC
</div>

::left::

**SC本部の立ち位置**
* いわゆるSE集団
* 営業と開発の間の職種
  * パートナーさん, 外部の開発者 などに 技術的な 説明をする機会が多い！

<br>

**技術を「わかりやすく伝える」スキルが必要！**
* そのために「技術」を理解することが大事

::right::

**SC Dept.'s Position**
* Essentially we are **System Engineers** (SE)
* We **bridge** the Development & Sales dept.s
* Many opportunities to present technical content to partners, external developers, & others!

**Showcasing tech in an "easy-to-understand" manner is vital!**
* Critically, we must understand the "tech"


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  今後の研修講義内容 / SC Training Lectures
</div>

<br>

_Find your interest!_ : SC研修を通して, 興味のある分野を探してみてください！

::left::

* Linux講義
* ネットワーク
* データベース
* シェルスクリプト / 正規表現
* 認証 / Webサーバ
* クラウド (cybozu.com)
* HTML / CSS
* JavaScript / API
* Git / GitHub

::right::

* Linux
* Computer Networking
* Database
* Shell Script & Regular Expression (RegEx)
* Authentication & Web Server
* Cloud Computing (cybozu.com)
* HTML & CSS
* JavaScript & API
* Git & GitHub


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  オペレーティング・システム / Operating System (OS)
</div>

::left::

コンピューターを動かすための基本ソフトウェア

### OSの例:
* Windows, Linux, MacOS
* Android, iOS

<br>

### OSの役割
* 様々なソフトウェアを動かすための土台
* ハードウェアとソフトウェアを仲介してくれる
* 例: キーボードを打ったら文字が入る, マウスのポインタが動く

::right::

The Operating System (OS) is the core software that runs the device

### Examples of OS:
* Windows, Linux, MacOS, Android, iOS

<br>

### The role of the OS:
* Manges other software
* Mediates between hardware and software
* Ex) Typing on the keyboard triggers character input & pointer movement


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  オペレーティング・システム / Operating System (OS)
</div>

::left::

### Linux講義で学べること
* Linuxの歴史
* Unixコマンドの種類, 使い方
* コマンドとは？ : 「命令」のこと

例) ファイルを表示して! の命令を  
Unixコマンドで行う

### SCで今後どう役立つ？
Linux と Windows Server での  
オンプレミス Garoon 構築

::right::

### Linux lecture will cover
* Linux history
* Unix command types and usage
* What is a command? : an *order*

Ex) Open a file using Unix commands

### How will this be used?
Building on-premises Garoon  
on Linux & Windows servers


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500" >
  ネットワーク / Computer Networking
</div>

::left::

複数のコンピュータ同士を接続して,  
相互に通信できるようにする技術

### ネットワーク講義で学べること
* ネットワークが繋がる仕組み

<br>

### SCで今後どう役立つ？
* .com移行業務
* オンプレミスGaroon構築

::right::

The tech that connects multiple devices  
so they can exchange data  
and share resources with each other

### Network lecture will cover
* Mechanism that connects the devices

<br>

### How will this be used?
* .com migration business
* Building on-premises Garoon


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  データベース / Database
</div>

::left::

検索や蓄積などが容易にできるように  
整理された情報の集まり

* データベース : 様々な情報が管理されている「箱」 のイメージ
* SQL というデータベース言語を使って操作する

<br>

### Garoonの場合
スケジュール情報, メッセージ情報  
などがデータベースに保管されている

::right::

A collection of information organized for easy search and retrial
* Database : A **box** filled with various data
* Managed using database language like SQL

<br>

### In Garoon's Case
Schedules, messages, & other information are stored in a database


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  データベース / Database
</div>

::left::

### データベース講義で学べること
* SQL言語の使い方
* データベースの種類:

例) MySQL, SQL Server, etc. 

### SCで今後どう役立つ？
* Garoonのデータベース操作
* cybozu.comのログ解析

::right::

### Database lecture will cover
* Using SQL
* Database type

Ex) MySQL, SQL Server, etc.

### How will this be used?
* Managing Garoon's database
* cybozu\.com log analysis


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  シェルスクリプト / Shell Script
</div>

::left::

複数のコマンド(命令)を実行するための処理を  
まとめたプラグラム

プログラム:  
コンピューターへの命令をまとめて記述したもの

### 講義で学べること
* シェルスクリプトの書き方

<br>

### SC本部で今後どう役立つ？
* 自動化作業(性能検証, Garoon構築の自動化)

::right::

A type of a program that executes multiple simple commands {Instructions}

Program:  
A set of instructions for a computer to follow

### Shell script lecture will cover
* Writing a shell script

<br>

### How will this be used?
* Automation work: performance testing, automate building a Garoon instance


---
layout: dynamic-image
image: ./background/jordy-meow-OQbppjf5ouc-unsplash.png
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  シェルスクリプト / Shell Script
</div>

### example.sh

```shell
#!/bin/sh

echo "What is your name?"
read PERSON
echo "Hello, $PERSON"
```

### Set Permissions / 権限を設定する

```bash
chmod +x example.sh
```


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  正規表現 / Regular Expression (RegEx)
</div>

::left::

様々な種類の文字列を  
1つの文字列で表現するための表記法

1つの文字列で表現することで,  
簡単に検索することができる!

### 講義で学べること
* 正規表現の書き方

<br>

### SC本部で今後どう役立つ？
* JavaScriptなどのコーディング
* テキストをまとめて変更する

::right::

Notation for expressing various types of character strings in one character string

Build complex search queries easily!

### RegEx lecture will cover
* How to write a regular expression

<br>

### How will this be used?
* Coding _such as JavaScript_
* Changing text in bulk


---
layout: dynamic-image
image: ./background/red_woods-sophia-simoes-HKVM_34Ykac-unsplash.png
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  正規表現 / Regular Expression (RegEx)
</div>

### RegEx

```regex
(|s)kinton(en|e|)
```

### Matches

```text
akintone
kinton
kintone
kintonen
skintone
```


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  認証 / Webサーバ
  <br>
  Authentication & Web Server
</div>

::left::

### 認証
対象の正当性や真正性を確かめるための仕組み

Webサービスにアクセスしてきているのが誰なのかを確認する役割

### Webサーバ
Webサービスを提供するためのサーバ

::right::

### certification
Mechanism for confirming the legitimacy and authenticity of the object

The role of checking who is accessing the web service

### Web server
Server for providing web services


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  認証 / Webサーバ
  <br>
  Authentication & Web Server
</div>

::left::

### 講義で学べること
認証の種類:
* セッション認証, Basic認証, SAML認証..  

webサーバの構築方法  

### SC本部で今後どう役立つ？
* オンプレミスGaroon構築  
* 様々な認証パターンを使ったGaroon構築

::right::

### Authentication & Web server lecture will cover
Authentication types:
* Session authentication, Basic authentication, SAML authentication ..  

How to build a web server  

### How will this be used?
* Building on-premises Garoon
* Configuring various authentication methods for Garoon


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  クラウド / Cloud Computing
</div>

::left::

インターネットを経由してサービスを提供する形態
* サイボウズも cybozu.com という クラウドサービス を提供している
* その他外部クラウドサービス
  * Amazon Web Service (AWS)
  * Microsoft Azure

### cybozu.com講義で学べること
* cybozu.comの仕組み


::right::

A form of providing services via the Internet
* Cybozu also offers a cloud service called cybozu.com.
* Popular cloud services
  * Amazon Web Service (AWS)
  * Microsoft Azure

### cybozu.com lecture will cover
* How cybozu.com works


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  HTML & CSS
</div>

::left::

### HTML
webページを作成するためのマークアップ言語  

役割:  
この場所に文字を, こっちにはボタンを配置しよう

### CSS
webページのスタイルを  
設定するためのスタイルシート

役割:  
この文字の色を赤色にして,  
このボタンは大きくしよう

::right::

### HTML
Markup language for creating web pages

Purpose:  
Let's put a letter in this place and a button here

### CSS
Stylesheets for styling web pages

Purpose:  
Make this letter red and make this button bigger


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  HTML & CSS
</div>

::left::

### 講義で学べること
* 基本的なHTML / CSSの書き方

<br>

### SCで今後どう役立つ？
* Webデザイン系
  * denvet, Cypn業務など
* kintoneカスタマイズ でのリッチなUIの実装 &nbsp;&nbsp;&nbsp;

::right::

### HTML & CSS lecture will cover
* How to write basic HTML & CSS

<br>

### How will this be used?
* Frontend web development:
  * [denvet](https://kintone.dev/en/), Cypn business, etc.
* UI-focused Kintone customizations


---
layout: dynamic-image
image: ./background/water-caleb-george-Lh6X0gXu7eg-unsplash.png
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  HTML & CSS
</div>

### HTML

```html
<div class="text-3xl text-primary dark:text-primary top-1">
  HTML & CSS
</div>
```

### CSS

```css
div {
  font-weight:500;
}
```


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  JavaScript (JS) & API
</div>

::left::

### JavaScript
Webページに動きをつけるための  
プログラミング言語です  

kintoneカスタマイズも JS で実装します

<br>

### API
ソフトウェアの機能を,  
外部から使うために用意された窓口

例) kintoneと他システムと連携したい..

::right::

### JavaScript
A programming language for moving web pages

Kintone customization is written in JS

<br>

### API
A window prepared for using software functions from the outside

Ex) I want to link with kintone and other systems ..


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  JavaScript & API
</div>

::left::

### 講義で学べること
* JavaScriptの基本的な文法
* 外部サービスAPIの使い方

<br>

### SCで今後どう役立つ？
* kintoneカスタマイズ、プラグイン開発
* 外部サービス連携
* かっこいいものを作る

::right::

### JavaScript & CSS lecture will cover
* Writing JavaScript
* How to use the external service API

<br>

### How will this be used?
* Kintone customization, plugin development
* External service cooperation
* Building cool [things](https://99percentinvisible.org/episode/numbers-stations/transcript/#article:~:text=Application)


---
layout: center-image
image: ./Slides_SC_Tech_Overview/kintone_game.gif
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  JavaScript & API
  <br><br>
</div>


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  Git & GitHub
</div>

::left::

### Git
プログラムの変更履歴を管理することができる  
バージョン管理システム

### GitHub
ソースコードをホスティングできるwebサービス

### 講義で学べること
* Git, GitHubとは？
* Gitを使ったバージョン管理の仕方

<br>

### SCで今後どう役立つ？
* JavaScriptなどのソースコードの管理
* チーム開発

::right::

### Git
A version control system that can manage the change history of programs

### GitHub
Web service that can host source code

### Git & GitHub lecture will cover
* What are Git and GitHub?
* How to manage versions using Git

<br>

### How will this be used?
* Manage source code such as JavaScript
* Team development


---
layout: image
image: ./Slides_SC_Tech_Overview/github_kintonedev_clear.png
---




---
layout: image
image: ./background/fatty-corgi-Zn5chZcnFRA-unsplash.png
---

<div class="mb-4 absolute top-20 right-10" style=" position: absolute; text-align: right;">
  <span class="text-6xl text-primary-light text-opacity-80" style="font-weight:500;">
    Any questions? <i class="light-icon-messages"></i>
  </span>
  <div><br></div>
  <div class="text-3xl text-black text-opacity-60" style="font-weight:600;" >
  質問ありますか？
  </div>
</div>


---
layout: image
image: ./background/thomas-tucker-KraXdvWzKNw-unsplash.png
---

<div class="mb-4 absolute top-20 right-12 rounded bg-black bg-opacity-10" style="position: absolute; text-align: right;">
  <span class="text-6xl text-primary-lightest" style="font-weight:500;">
    Thank you for your time <i class="light-icon-atom"></i>
  </span>
  <div><br></div>
  <div class="text-4xl text-white" style="font-weight:600;" >
    お時間をいただきありがとうございました
  </div>
</div>

<div class="absolute bottom-5 left-12">
  <a href="https://sli.dev/">
    <span class="text-5xl p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-60 flex justify-center items-center">
      <i class="light-icon-anchor" size="24px" />
    </span>
  </a>
</div>
