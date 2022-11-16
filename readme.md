# 職務経歴書

## 自己紹介
| key | value |
|:--|:--|
| Name | 岡本 健太郎 |
| Job | Infrastructure (Cloud) Engeneer |
| GitHub | [kokamoto01](https://github.com/kokamoto01) |
| Qiita | [kokamoto01 - Qiita](https://qiita.com/kokamoto01) |
| Wantedly | [kokamoto01](https://www.wantedly.com/id/kokamoto01) |
| LinkedIn | [kentaro-okamoto-a0bb87223](https://www.linkedin.com/in/kentaro-okamoto-a0bb87223/)  

## 職務要約
株式会社アウトソーシングテクノロジーに新卒入社し、ソリューションサービス事業本部に配属されました。  
大手不動産会社、大手人材会社、大手事務用品通販会社、ヘルスケアサービス会社に対してAWSを用いたインフラの構築・保守を行った実績があります。  
その中でもAWSでコード(コーディング)を用いたサービス作成をすることが得意です。その実力を現職で認められ、現在担当している業務では技術担当のリーダーとしてインフラの設計を一任されています。  
また、所属部署内で作業の進捗報告がうまくできる仕組みがないことに課題を感じ、新たにプロジェクト管理ツールの導入を提案し正式採用まで持っていきました。  
他にはチームの作業工数を削減するため、現在稼働しているサービスにコードレビュー後の変更内容を自動で適用する仕組みを作成する等の試みも行っています。  

## スキル
### LinuxおよびDockerベースのインフラ設計・構築・運用
- AWSを使ったプロジェクトの多数の経験があります。
  - ワークロードに応じた監視ツールの提案・導入
  - Blue/Greenデプロイなど難易度が高い課題にも対処した経験あり
- IaC(Infrastructure as Code)ツールを用いたインフラ構築ができます。
  - Terraform, CloudFormationの2つのツールに対応
  - CI/CDの仕組みを活用したシステムを浸透させ運用コストの低下を実現

### ドキュメント整備能力
- 限られた情報から推測してドキュメント・マニュアル化することができます。
  - 部内AWS環境のマニュアルを再整備して周知の徹底
  - 退職済みのメンバーが残してくれた情報から推測した、基本設計書の再構築

### トラブルシューティング能力
- 緊急性が高い問題にも取り組むことができます。
  - 他部署からのAWSのトラブルシューティングの相談
  - 障害の原因調査から復旧、再発防止策の作成までの対応

### チームリーダー経験
- 上記の経験を認められ、通常では4年かかるリーダーポジションを2年目で担当しました。
- 現在はAWSのスペシャリストを目指していますが、マネジメントの知識も身につけたいと考えています。

## 職務経歴
### ★【プロジェクト】大手不動産会社
【期間】2022/9 ~ 現在  
【開発規模】インフラエンジニア4名(技術リーダーとして参画) 、PM1名、他社インフラエンジニア2名  
【業務】物件情報サービスの開発環境基盤構築請負
- 基本設計書の改訂
- CI/CDを活用したインフラ構築
- CloudFormationテンプレートのコードレビュー
- 参画メンバーの得意分野を加味したタスクの振り分け

【成果】
- 基本設計書の不備を修正し、より良いソリューションの提案を行った
  - 大きすぎるインスタンスサイズの修正
  - コンテナイメージ脆弱性スキャンの導入
- WBSからさらに仕事を細分化する技術を身に着け、それを基に指示を振る術を身につけた
  - カンバンボードを有効活用して、メンバーの得意分野に合わせたタスクの振り分けを行った
- 技術リーダーとしての責任の重さからメンタルを保つための工夫を考えるようになった
  - 「ザッソウ」を意識して、チーム全体の息苦しさの解消を心がけた

【環境】
- Docker
  - アプリケーション: nginx + php-fpm(CakePHP4)
  - リバースプロキシ+画像リサイズ: nginx + OpenResty
- CloudFormation
  - ECS(Fargate), Aurora, ElastiCache, ELB, Route53, S3
  - CodeCommit, CodeBuild, CodeDeploy(Blue/Green), CodePipeline
  - CloudFront, AWS WAF
- セキュリティ
  - Cloud One Storage Security (オブジェクトスキャン)
  - Trivy (コンテナイメージ脆弱性スキャン)

### 【プロジェクト】大手事務用品通販会社
【期間】2022/4 ~ 2022/8  

【開発規模】インフラエンジニア3名(メンバーとして参画)、PM1名、他社インフラエンジニア5名  
【業務】
- Terraform, Ansibleを用いた既存インフラの保守・移行
  - サービス過渡期の段階であり、開発環境で導入されていたソリューションをステージング環境や本番環境に移行してほしいとの依頼
  - アクセス権限の変更や開発環境IAMユーザ・OSユーザ作成の依頼

【成果】
- アクセス権限変更などの細かな仕事を重ねてお客様からの信頼度を高めることができたため、難易度が高い仕事を依頼されることができた
- チーム内でGitについてのナレッジがないメンバーが大半だったため、マニュアルを作成し共有することでナレッジを浸透することができた
- GitHub Actionsを使ったCI/CDについての知識がついたことにより、今後CI/CDをどのように導入・運用すればいいかのノウハウを身につけることができた

### 【プロジェクト】ヘルスケアサービス会社
【期間】2022/2 ~ 2022/4  
【開発規模】インフラエンジニア2名(メンバーとして参画。うち1名PM兼任)   
【業務】
- 監視サービス導入提案および構築  
  - 予算面や、機能・保守の容易さなどを考慮してCloudWatch, Datadogの両方を提案
  - 上記の導入が決定したため、Datadogをスモールスタートで導入
  - 評判が良かったため、監視の大部分をCloudWatchからDatadogに移行
- サーバーサイドのセキュリティ向上
  - セキュリティ要件が厳しい案件のため、以下のサービスを導入の提案をして、構築を行なった。
    - AWS WAFv2
    - CloudOne Workload Security  

【成果】
- 稼働しているサーバのサイズをアップグレードする必要があることが分かった
- 不審なユーザがアクセスしようとしていることが判明し、そのIPアドレスを遮断することができた
- Webサーバの内部にリアルタイムスキャンを導入することで、サービスの安全性を確保することができた

<!-- ### 【プロジェクト】社内インフラ（AWS）の検証・保守運用  
【期間】2021/11 ~  2022/2  
【業務】企画提案・テスト・運用・改善すべて  
【役割・規模】構築1名、PM１名  
-  社内リソースのコスト削減・棚卸し（月額コスト30%軽減達成）  
-  AWS社内利用ポリシー・基本設計書作成  
-  Lambdaを使い、Teamsに通知を飛ばすプログラム作成(CodeCommitリポジトリのプルリクエスト作成通知, コスト週報通知など)  
-  IAM管理 (既存のIAMポリシー見直し、アカウント管理)

### 【プロジェクト】大手人材会社向けの、AWS活用の企画提案  
【期間】2021/11 ~  現在  
【業務】企画提案  
【役割・規模】PM2名, メンバー3名  
-  Webサイト更新作業提案(シェルスクリプト)  
-  CI/CD提案(CodeCommit → CodePipeline → CodeBuild → CodeDeploy)  

### 【プロジェクト】お客様企業に向けた、統合OAシステムのインフラ基盤再構築  
【期間】2021/7 ~  2021/9  
【業務】ネットワークコンフィグ入力・テスト  
【役割・規模】PM2名, 設計構築5名, コーダー4名  
・ L2スイッチ、ルータ、APのコンフィグ入力  
・ ネットワークの到達テスト・パフォーマンステスト  

### 【プロジェクト】CMSを使った自社用ツール構築  
【期間】2021/6 ~  2021/6  
【業務】AWS上のインフラ設計  
【役割・規模】インフラエンジニア2名、フロントエンジニア3名  
・ CMS(Drupal)環境を作成するためのVPC, EC2などのインフラ構成作成  
・ DevOps形式での開発   -->
