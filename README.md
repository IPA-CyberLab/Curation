## 概要

このリポジトリでは、サイバーセキュリティに関する最新のニュースやトピックをキュレーションし、整理して掲載しています。

## 作成にあたって

- 収集にあたって，なるべく1次ソースを追うようにしています。
- 主に収集するニュース
  + 日本との関係が強いと考えられるニュース
  + 攻撃者の動向（攻撃手法，狙いなど）
- あまり収集しないニュース
  + 製品の脆弱性情報

## コンテンツ構成

- ページタイトル
- サマリー（日本語）
- タグ
- 収集日
- ページURL

## 免責事項

当リポジトリは情報提供を目的としており、記載された内容の正確性・完全性を保証するものではありません。
本リポジトリに掲載した内容は予告なく変更することがあります。

# 2026年7月 サイバー脅威動向レポートサマリー

## 1. AI技術に関連する攻撃と悪用

* 多層防御（検知エンジニアリングの重要性）。SpecterOpsのAdam Chesterが、GPT-5.5-CyberとBinary NinjaをCodex-CLI経由で組み合わせたシンプルなループハーネス「Day Shift」を用い、Cortex XDRのローカル検知ロジックを全自動で解析・抽出した。
  + URL: https://specterops.io/blog/2026/06/29/llm-powered-edr-analysis/
* AIコーディングエージェント起因のアラートが増加する可能性。ブラウザの認証情報の復号化、Windows認証情報ストアの一覧表示、組み込みシステムツールによるファイルダウンロード、スタートアップフォルダへの書き込みといった挙動がEDRに検知されている（Sophos報告）。
  + URL: https://www.sophos.com/en-us/blog/2607_agents_vs_telemetry
* AIエージェントを狙った攻撃HalluSquatting。流行しているリポジトリやプラグインを対象に、攻撃者はAIにそのリソースを繰り返し取得させ、AIが最も頻繁に生成する偽名を記録する。
  + URL: https://sites.google.com/view/agentic-botnets/home

## 2. 国家支援型攻撃

* 北朝鮮。開発者の採用やコードレビューといったテーマを利用してフィッシングキャンペーンを仕掛け、金融、暗号通貨、教育、テクノロジーなどを標的としている。攻撃の起点は、攻撃者が管理するGitHubリポジトリへのリンクを含むメールや、Microsoftアカウントのセキュリティ通知を装ったスピアフィッシングメッセージなど。
  + URL: https://www.proofpoint.com/us/blog/threat-insight/dont-fear-repo-unkdeaddrop-phishing-campaign-targets-developers-steal
  + URL: https://www.genians.co.kr/en/blog/threat_intelligence/narwhalrat
* 中国。重要インフラを狙ったとみられる攻撃を展開中。日本向けには製造業を狙い、BYOVD（正規だが脆弱性があるドライバー）をインストールして攻撃に利用する手法が観測されている。「amsdk.sys」「wsftprm.sys」「BootRepair.sys」「EnPortv.sys」の4つについてアラートを検知した場合は注意。スピアフィッシングおよびASPX Webシェルなどを起点に偵察とツール配信を行い、その後SoftEther VPN、Yuze、VNTを使用してリモート通信を確立する。
  + URL: https://unit42.paloaltonetworks.com/cl-sta-1062-tinyrct-backdoor/
  + URL: https://thehackernews.com/2026/07/silverfox-targets-japanese-manufacturer.html
  + URL: https://www.acronis.com/en/tru/posts/mustang-panda-targets-indias-government-and-energy-sectors/
* ロシア。Turlaに関連する記事が増加。フィッシングメール、感染したウェブサイトへのアクセス、脆弱な公開サーバが攻撃手法。
  + URL: https://www.cert.ssi.gouv.fr/uploads/CERTFR-2026-CTI-005.pdf
  + URL: https://cloud.google.com/blog/topics/threat-intelligence/stockstay-turla-intelligence-gathering/?hl=en

## 3. 一般社員向け

* GitHubの公開設定について再点検。2026年7月9日、米国のサイバーセキュリティ・インフラストラクチャセキュリティ庁（CISA）が、委託先担当者の個人用GitHubリポジトリを通じて同庁のAWS認証情報などが長期間インターネット上に公開状態にあった事案について、対応の経緯と教訓をまとめた公式ブログを公表した。
  + GitGuardianの分析によれば、「Private-CISA」リポジトリは2025年11月13日に作成されて以降、CISAのビルド・デプロイ用リポジトリのコピーや管理者・ビルド用の認証情報が継続的に公開状態でコミットされていた。
  + 容量は作業ツリー498MB・Git履歴等346MBの合計844MB。AWS GovCloudの管理者認証情報、CI/CDのビルドログ、Kubernetesマニフェスト、Terraformコード、GitHub Actionsのワークフロー、Entra IDのSAML証明書、内部システムのプレーンテキストパスワードが含まれていた。
  + 一次対応として公開リポジトリのオフライン化、開発環境のオフライン化と認証情報のリセット、漏洩させた人物のアクセス権剥奪を実施。調査の結果、漏洩した認証情報はCISA環境外では使用されておらず、顧客データや任務データの漏洩はないことを確認した。
  + 是正措置として、当該人物に管理者権限が付与されていたすべての環境の認証情報をローテーションし、コードリポジトリの許可／拒否リストを調整、ユーザーが公開コードリポジトリにアップロードする機能を制限した。
  + URL: https://piyolog.hatenadiary.jp/entry/2026/07/13/123024
  + URL: https://www.cisa.gov/news-events/news/lessons-cisas-cyber-incident
  + URL: https://krebsonsecurity.com/2026/05/cisa-admin-leaked-aws-govcloud-keys-on-github/

## 4. その他

* IPA：中小企業のセキュリティ、今から取り組むなら「SCS評価制度」を参考に。★3は広く知られた脆弱性を悪用するような一般的なサイバー攻撃に対処できる水準で「全てのサプライチェーン企業が最低限実施すべきセキュリティ対策」、★4はサプライチェーン全体に打撃を与える攻撃まで見据えた「サプライチェーン企業等が標準的に目指すべきセキュリティ対策」とされる。「対応しなければ取引から外される」と不安を煽り、「このツールさえ入れれば安心」と特定の製品へ誘導するといった売り込みに注意。
  + URL: https://internet.watch.impress.co.jp/docs/special/2121836.html
