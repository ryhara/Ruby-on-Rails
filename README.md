# Ruby-on-Rails Web Application

## Version
※2023/07/01　時点
- Rails 6.1.7.3
- ruby 3.1.2p20 (2022-04-12 revision 4491bb740a) [x86_64-linux]
- node v16.19.0
- yarn 1.22.19
- Version: ImageMagick 7.1.1-5 Q16-HDRI x86_64 92a5afcfa:20230326 https://imagemagick.org
  - Copyright: (C) 1999 ImageMagick Studio LLC
  - License: https://imagemagick.org/script/license.php
  - Features: Cipher DPC HDRI OpenMP(4.5) 
  - Delegates (built-in): jng jpeg lzma png tiff xml zlib
  - Compiler: gcc (7.3)
- sqlite3 3.42.0

## Usage
```
$ bundle install
$ rails webpacker:install (when asked, answer Y)
$ rails webpacker:compile
$ rails db:migrate
($ rails db:seed)
```
```
$ rails s
```
If "Webpacker::Manifest::MissingEntryError" occur
```
$ yarn add @babel/plugin-proposal-private-methods @babel/plugin-proposal-private-property-in-object
```





<!-- ## [meshiterro](https://github.com/ryhara/meshiterro)
Ruby on rails 練習用　アプリケーション -->

## [Bookers1](https://github.com/ryhara/Bookers1)
**本の感想投稿アプリ**

- 本のタイトルと感想を投稿、閲覧、編集、削除が可能

## [Bookers2](https://github.com/ryhara/Bookers2)
**ログイン、ユーザー機能付き、本の感想投稿アプリ**

- 本のタイトルと感想を投稿、閲覧、編集、削除が可能
- ユーザーの登録、ログイン、ログアウト、ユーザー情報の編集が可能
- 他のユーザーの投稿も閲覧可能

## [Bookers2_ver2](https://github.com/ryhara/Bookers2_ver2)
**Bookers2 + いいね、コメント機能**

- 上記のBookers2と同様の機能
- 他のユーザーの投稿にいいねやコメントが可能

## [Bookers2_ver3](https://github.com/ryhara/Bookers2_ver3)
**Bookers2_ver2 + いいね、コメント機能の非同期通信化 + 検索機能 + フォロー/フォロワー機能**

- 上記のBookers2_ver2に加えて、フォロー/フォロワー機能、検索機能を追加
- JavaScript, jQueryを用いたいいね、コメント機能の非同期通信化
- 他のユーザーのフォローが可能、フォロー、フォロワーの一覧も可能、X(旧Twitter)のイメージ
- UserとBookの2種類で検索可能、完全一致、前方一致、後方一致、部分一致で検索が可能

## [nagano-cake](https://github.com/ryhara/nagano-cake)
**ECサイト 未実装部分あり**

- ケーキ屋のECサイト
- ユーザー機能、商品の注文、カート機能、履歴など
- 管理者機能、ジャンル編集、商品編集、注文・製作ステータス更新、ユーザー編集など
