---
layout: home
title: スキルシート
---

## 基本情報

|key|value|
|----|----|
|名前|Takaharu Niki|
|現在地|大阪市|
|ブログ|[アントレプログラマー](https://entreprogrammer.jp/)
|X(Twitter)|[@takaharu_niki](https://twitter.com/takaharu_niki)|
|趣味|筋トレ・アニメ|

## 得意分野

- バックエンド開発が専門です。最も得意な言語/フレームワークはPHP/Laravelです。
- 周辺技術としては、AWS/Nginx/MySQL/Docker等を使った開発が得意です。
- フロントエンド開発はNext.jsの経験があります。
- GitHub ActionsやAWSを利用したCI/CD環境構築等のDevOps業務の経験があります。

## 得意技術

### 言語

PHP, Python, Kotlin, Java, JavaScript, Go, TypeScript

### フレームワーク

Laravel, Spring Boot, CakePHP, Next.js, React, Vue.js, jQuery

### RDB/NoSQL

MySQL, PostgreSQL, Redis, Memcached

### AWS

VPC, S3, API Gateway, Lambda, ELB, EC2, ECS, Fargate, Route53, IAM, Cognito, RDS(MySQL), Aurora, DynamoDB, ElastiCache(Redi,Memcached), SNS, SES, CloudFormation, CloudWatch, EventBridge, Secrets Manager, Amplify, CodeBuild, CodeDeploy, CodePipeline, ECR, Athena

### SaaS/PaaS

GitHub, GitHub Actions, BitBucket, Datadog

### その他

Docker, Jenkins, Fluentd, Ansible, Nginx, Apache, Gulp, Webpack, SASS

## 得意業務

- SQLチューニング
- TDDを用いた安全なコード変更
- デプロイの自動化
- インフラのコード化
- LinterやFormatterの導入
- 単体テストの導入
- CIサービスの導入
- コンテナ化(Docker化)
- オートスケールの設定
- デプロイの自動化
- 変更に強い設計

## 主な業務経歴

### 宅食サービス事業会社(2021/09〜現在)

| 期間              | 業務内容                                                                                                                                                                                                                                                                                                                                                                                                              | 役割と規模            | 使用言語           | DB            | サーバOS   | FW・MWツール等                                                                                     | 担当工程 |
|-------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|-------------------|---------------|------------|---------------------------------------------------------------------------------------------------|----------|
| 2022/3〜  | ［担当業務］ <br>- コーディングルールの策定 <br>- 設計・アーキテクチャの策定<br>- コードレビュー| **アプリケーションアーキテクト** <br>チーム: 1<br>開発: 1<br>全体: 1 | PHP  | Amazon Aurora             | Amazon Linux          | AWS, Laravel | 全て     |
| 2024/5〜2024/6  | **Push通知用のテスト環境整備とライブラリ変更**<br>- iOS, Androidともに本番とは独立してテスト可能にする。<br>- FCM APIエンドポイントの廃止に伴うライブラリ更新。<br>［担当業務］<br>- 調査、実装、証明書の配置| **テックリード** <br>チーム: 4<br>開発: 2<br>全体: 4 | PHP, Swift, Kotlin | Amazon Aurora              | Amazon Linux          | AWS, Laravel | 全て     |
| 2024/4〜2024/4  | **返送記録とユーザー停止機能の開発**<br>- 代引き払い予定の商品返送時に、ユーザー停止にする。 <br>［担当業務］<br>- 要件からリリースまで| **テックリード** <br>チーム: 3<br>開発: 1<br>全体: 6 | PHP  | Amazon Aurora              | Amazon Linux          | AWS, Laravel | 全て     |
| 2024/1〜2024/3  | **AWSリソースのコード化**<br>- Amazon EC2 Auto Scaling の動的スケーリング 対応 <br>- CodePipeline, CodeBuild, CodeDeployのコード化 <br>［担当業務］ <br>- Auto Scaling グループや起動テンプレートを<br>クラウドフォーメーション（CDK）で管理| **テックリード** <br>チーム: 6<br>開発: 2<br>全体: 6 | Python  | -             | Amazon Linux          | AWS | 全て     |
| 2023/12〜2023/12  | **Laravelのアップグレード**<br>Laravelアップグレードにおける計画と実行。<br>［担当業務］<br>- 自動ツールLaravel Shiftの採用と実行<br>- Laravel Upgrade Guideに基づいた確認と修正。<br>- カナリアリリースを用いた影響を抑えたリリースの実施<br>postメソッドのAjax通信やモバイルアプリに不具合が発生した。<br>原因はセッションとキャッシュ用に同一ストレージを採用していると、<br>アプリケーションはキャッシュを通してセッションデータを取得するが、<br>キャッシュのキーに付与するプレフィックス変更を許容していたため。 | **テックリード** <br>チーム: 3<br>開発: 1<br>全体: 3 | PHP  | Amazon Aurora             | Amazon Linux          | Laravel                                                                                           | 全て     |
| 2023/07〜2023/11  | **AWS CodeDeployを使ったAuto Scaling対応**<br>カナリアリリース等を目的に、DevOpsエンジニアとして技術選定と実施を担当。<br>［担当業務］<br>- EC2内の各種ログファイルデータのアーカイブ設定<br>- CodeDeployの導入<br>- EC2からS3への転送方法の調査・決定<br>- Fluentdのインストール、設定ファイルの作成、S3バケットへの転送確認<br>- Datadogの設定ファイル作成、Datadogへの転送確認<br>- GitHubでの設定ファイル管理                                                                                                        | **テックリード** <br>チーム: 3<br>開発: 1<br>全体: 3 | Python               | -             | Amazon Linux        | Fluentd, Datadog, S3,<br> CodePipeline, CodeDeploy,<br> CloudFormation                                 | 全て     |
| 2023/04〜2023/06  | **入金消込システムの開発**<br>決算前業務の効率化のために、決済データと入金データを突合するシステムを開発。<br>［担当業務］<br>- 大量データ処理のパフォーマンスを考慮したシステム設計・実装・テスト<br>- 入金データの管理テーブル作成<br>- 外部APIからのデータ取得とテーブル記録のバッチ処理作成<br>- 突合結果を取得するUIの作成                                                                                                                                                       | **テックリード** <br>チーム: 2<br>開発: 1<br>全体: 4 | Kotlin, PHP    | Amazon Aurora             | Amazon Linux          | Spring Boot, React, Laravel                                                                     | 全て     |
| 2023/01〜2023/03  | **決済代行会社変更のためのシステム開発**<br>決済代行会社のサービス終了に伴い、<br>システムの再設計・リファクタリングと新しい決済ロジックの導入。<br>［担当業務］<br>- 度重なる決済会社変更への対応とシステム改修<br>- テスト駆動開発(TDD)の実施<br>- Rectorを用いた自動リファクタリング<br>- 新しい決済システムロジックの導入                                                                                                                                                | **テックリード** <br>チーム: 3<br>開発: 2<br>全体: 3 | PHP  | Amazon Aurora             | Amazon Linux          | Laravel                                                                                    | 設計 - 保守・運用    |
| 2021/09〜2022/12  | **ECサイト・管理画面の機能開発**<br>マーケティング施策実施や社内業務遂行を目的としたシステム開発。<br>［担当業務］<br>- フロント・バックエンドの設計・実装・テスト                                                                                                                                                                                                                                                                           | チーム: -<br>開発: -<br>全体: - | PHP, JavaScript | Amazon Aurora             | Amazon Linux          | Laravel                                                                                 | 全て     |

プロジェクト外の活動

- 採用活動
- 静的解析ツール、フォーマッターの導入
- 本番に追随するためのコンテナイメージのバージョンアップ
- ジョブの同期実行を目的としたメールコンテナの追加
- シークレットの管理のためにSecrets Managerを使用
- Secrets ManagerのシークレットをECSのタスク定義のsecretsに設定し、Spring Boot内で利用
- Findy Team+を使った、DevOps FourKeysの分析・改善

### レンタルサーバー事業会社(2019/09〜2021/08)

| 期間              | 業務内容                                                                                                                                                                                                                                                                                                                                                                                                              | 役割と規模            | 使用言語           | DB            | サーバOS   | FW・MWツール等                                                                                     | 担当工程 |
|-------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------|-------------------|---------------|------------|---------------------------------------------------------------------------------------------------|----------|
| 2019/09〜2021/08  | **レンタルサーバー事業会社の各種プロジェクト**<br>コンソール画面の追加・改修、Windows ServerのOSテンプレートの開発、VPSサービス用の追加テンプレートの新規開発。<br>［担当業務］<br>- 実装とテスト<br>- Ansible Playbookの作成と修正                                                                                                                                                                                                | **メンバー** <br>チーム: -<br>開発: -<br>全体: - | PHP, JavaScript | PostgreSQL    | CentOS     | Laravel, Vue.js,<br>Zend Framework, Vanilla JS, OpenStack, Ansible                              | 実装 - 総合テスト     |
