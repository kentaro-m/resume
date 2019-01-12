# 職務経歴書
<img src="./avatar.png" width="200px" />

|key|value|
|---|-----|
|Name|松下 健太郎|
|GitHub|[kentaro-m \(Kentaro Matsushita\)](https://github.com/kentaro-m)|
|SpeakerDeck|[Kentaro Matsushita](https://speakerdeck.com/kentarom)|
|Qiita|[kentaro_m \- Qiita](https://qiita.com/kentaro_m)|
|Twitter|[@_kentaro_m](https://twitter.com/_kentaro_m)|
|Portfolio|[Kentaro Matsushita - @kentaro-m](https://kentarom.com/)|
|Mail|contact@kentarom.com|

## 職務経歴
### 合同会社DMM.com (正社員: 2016/04/01 ~ 現職)

#### プラットフォームリプレイス開発
* 時期: 2016/07〜2018/07
* 役割: サーバーサイドエンジニア
* 技術
  * Node.js
  * React.js
  * Express.js
  * AWS
    * ALB
    * EC2
    * Kinesis Firehose
    * Lambda
    * API Gateway
    * ElasticSearch Service
    * CloudFormation
    * ElastiCache
  * New Relic
  * CircleCI
  * Sentry
* 担当したこと
  * Node.jsとExpress.js、React.jsを用いたフロントエンド開発
  * CloudFormationを用いたインフラ構成のコード化
  * オートスケーリングを用いた負荷対策
  * アプリケーションのリリース作業をSlackコマンドで行うサーバーレスアプリケーション構築
  * ログ基盤及びアプリケーションエラーを通知するサーバーレスアプリケーション構築
  * New Relicを用いたインフラ監視の導入
  * チーム内輪読会開催による開発手法の啓蒙活動
* 工夫したところ
  * アプリケーションリリース作業をSlackから実施できるようにし、精度の高いリリースを実現した
  * ログ基盤及びアプリケーションエラーを通知する仕組みを整備し、障害検知と復旧の迅速化を実現した
  * インフラ監視にNew Relicを導入し、開発者が運用監視しやすい環境を整えた
  * GitHubのプルリクエストワークフローを改善するBotを導入し、レビューからマージまでの時間を短縮した
    * [GitHubでのプルリクエスト運用を加速するためにプルリくんというBotを作った話 - Qiita](https://qiita.com/kentaro_m/items/fc79511f463ff51b4d0f)

#### Webアプリケーション機能追加及び保守・運用
* 時期: 2018/07〜現在
* 役割: サーバーサイドエンジニア
* 技術
  * Node.js
  * React.js
  * Express.js
  * AWS
    * ALB
    * EC2
    * Kinesis Firehose
    * Lambda
    * API Gateway
    * ElasticSearch Service
    * CloudFormation
    * ElastiCache
  * New Relic
  * CircleCI
  * Sentry
  * Java
  * Spring Framework
  * Jenkins
  * MySQL
  * Couchbase
  * Cassandra
* 行ったこと
  * Node.jsとExpress.js、React.jsを用いたフロントエンド開発
  * Spring Frameworkを用いたAPI開発
  * MySQLテーブル設計及びレビュー
  * ZenHubを用いたプロダクトバックログ管理
* 工夫したところ
  * プロダクトバックログ管理のためにZenHubを導入
    * 新チームの組成に伴い、スクラム開発で使用するプロジェクト管理ツールの選定と導入を行った。ZenHubを選定したあとは、チームで運用するための指針を作成し、使い方のレクチャーもあわせて行った。
  * 開発や運用の改善アイデアを収集するBotの開発・導入
    * Slackから気軽にGitHub Issueを作成できるBotを開発しました。
    * 週1回Issueについて話し合うMTGがあり、良い改善サイクルができつつある。

## 登壇歴
|Date|Event|Content|
|----|-----|-------|
|2018/11/23|JAWS-UG金沢 #36 x OpsJAWS！ AWS運用・監視についてのクロスイベント！|[AWSの既存サービスを活用して、 障害検知・復旧を迅速化するカラクリ](https://speakerdeck.com/kentarom/jaws-ug-kanazawa-x-opsjaws)|
|2018/10/31|AWS Dev Day Tokyo 2018 LT大会|[DMM.comの認証基盤を支えるエラー通知の仕組み](https://speakerdeck.com/kentarom/aws-dev-day-tokyo-2018-lightning-talk)|
|2017/09/16|GitHub勉強会 in Kanazawa|[GitHubでのプルリクエストレビューを加速するためにいろいろと作った話](https://speakerdeck.com/kentarom/githubtefalsehururikuesutorehiyuwojia-su-surutameniiroirotozuo-tutahua)|

## ブログ
* [技術書の輪読会を定着させるまでの道のりで学んだこと - DMM inside](https://inside.dmm.com/entry/2018/10/02/rindokukai)
* [Go言語初学者がConfluenceをMarkdownで書くためのCLIツールを開発した話 - DMM inside](https://inside.dmm.com/entry/2018/05/28/golang-cli-tool)

## OSS
* [kentaro-m/auto-assign: 🤖 A Probot app that adds reviewers to pull requests when pull requests are opened.](https://github.com/kentaro-m/auto-assign)
  * GitHubのプルリクエストにレビュアーを自動追加するGitHub Appsです。
* [kentaro-m/md2confl: 🛠 md2confl is a CLI tool to convert the markdown text to confluence wiki format.](https://github.com/kentaro-m/md2confl)
  * マークダウン文書をAtlassianのConfluence記法に変換するためのCLIツールです。
* [kentaro-m/blackfriday-confluence: 🛠 Blackfriday-Confluence is confluence wiki renderer for the Blackfriday v2 markdown processor.](https://github.com/kentaro-m/blackfriday-confluence)
  * Goのマークダウンプロセッサー「Blackfriday」でConfluence記法を出力するライブラリです。
* [kentaro-m/coverage-markers: 📦 Atom package to display JavaScript test coverage on gutter of editor.](https://github.com/kentaro-m/coverage-markers)
  * JavaScriptのプロジェクトのテストカバレッジをAtomエディタに表示するパッケージです。
* [kentaro-m/issue-creator: A Slack slash command for creating quickly a new issue on GitHub.](https://github.com/kentaro-m/issue-creator)
  * SlackのSlashコマンドから素早くGitHub Issueを作るためのアプリケーションです。
* [kentaro-m/zenhub-time-tracker: Keep track of time to move an issue between pipelines and notify the time into Slack.](https://github.com/kentaro-m/zenhub-time-tracker)
  * IssueのZenHubパイプライン間の移動時間を計測・表示をするアプリケーションです。

## プログラミング言語・フレームワーク
業務経験のあるものを列挙。

* サーバーサイド
  * Node.js
  * Java
  * PHP
* フロントエンド
  * React.js
* ミドルウェア
  * MySQL
  * Couchbase
  * Cassandra
  * Redis
* モニタリング
  * New Relic
  * Zabbix
* インフラ
  * AWS
* その他
  * CircleCI
  * Jenkins
  * Git