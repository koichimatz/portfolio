# DMM英会話プラス
## サイト概要
DMM英会話ユーザーがより快適に、効率よく学習する手助けをするサイトです。

### サイトテーマ
DMM英会話でこんな機能あったらいいなを実現するサイト

### テーマを選んだ理由
自分自身がDMM英会話のヘビーユーザーで、レッスン時間の登録にGASを使ってレッスン予約を自動でGoogleCalendarに同期して使っている。この機能はユーザーの多くが使いたいと思う機能だと思うが、GASを導入するというのは多くの人にとってハードルが高い。この機能以外にも他にもこんな機能があればもっと便利というアイディアがあったのでそれらを簡単に使えるためのサイト製作をテーマとした。
### ターゲットユーザ
DMM英会話のユーザー全て

### 主な利用シーン
1. レッスン予約していた時間を忘れてしまう→GoogleCal連携
2. DMMのレッスンノートをもっと活用したい→レッスンノートメール送信機能
3. DMM英会話のレッスン履歴を月別に可視化してモチベーションをあげたい→カレンダー表示機能
4. レッスンノートの内容をまとめて表示し活用しやすく
5. 発展:DMM英会話ユーザー同士で繋がる、競い合う

## 設計書
<...>

## 参考
[DMM英会話の予定をGoogleカレンダーに自動登録する方法](https://www.cg-method.com/life/dmm-eikaiwa-google-calendar/)
[スクレイピング](https://tech-camp.in/note/technology/48812/)
	http://nokogiri.org/
https://qiita.com/katsuyuki/items/1a78360988d96eec1d54
https://qiita.com/mmmm/items/545e0aec82e6949ebb0a
## チャレンジ要素一覧
<https://docs.google.com/spreadsheets/d/14hjbKu8GXgWfNYsE13ZXtjElVOSodwy2kRKpWxsdSfg/edit?usp=sharing>

## 開発環境
- OS：Linux(CentOS)
- 言語：HTML,CSS,JavaScript,Ruby,SQL
- フレームワーク：Ruby on Rails
- JSライブラリ：jQuery
- IDE：Cloud9

## 最終的に組み込みたい技術

-   フロントエンド
    -   HTML/CSS
    -   Javascript
    -   Vue.js
-   バックエンド
    -   Ruby 
    -   Ruby on Rails
    -   Rubocop（コード解析ツール)
    -   Rspec（テスト)
-   インフラ
    -   Docker / Docker-compose
    -   AWS (EC2 / RDS(MySQL) / S3 / VPC / IAM / Route53 / ACM / ALB / Cloudfront)
    -   CircleCI (CI/CD)
    -   MySQL / Puma / Nginx
    - 
## 使用素材
- 外部サービスの画像素材・音声素材を使用した場合は、必ずサービス名とURLを明記してください。
- 使用しない場合は、使用素材の項目をREADMEから削除してください。
