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

# 2026年11月 サイバー脅威動向レポートサマリー

## 1. AI技術に関連する攻撃と悪用

* 脅威アクターが基本的なプロンプト利用を超え、自律型マルチエージェントフレームワークや自動化された脆弱性悪用パイプラインを展開する段階に入ったとGoogle（GTIG）が報告。侵害した企業環境からLLM認証情報とクラウドリソースを盗み、プロキシサービス経由で再販するLLMJackingにより収益化している。
  + URL: https://cloud.google.com/blog/topics/threat-intelligence/agentic-threat-activity-crosses-a-significant-threshold?hl=en
* 米国企業が中国で開発されたオープンウェイトAIモデルを自社の技術スタックに組み込んでいる現状について、議会報告書が憂慮すべきものとして警告。
  + URL: https://therecord.media/chinese-open-weight-AI-use-by-US-companies-house-investigation
* 欧州委員会が、公開されているAIツールを用いたサイバー攻撃を受けていたことを確認（最初の兆候は10月22日に検出）。
  + URL: https://therecord.media/european-commission-confirms-cyberattack-using-ai
* アフリカの主要証券取引所がAI支援型攻撃の標的に。41個のPowerShellモジュールがWebシェル上で3分強にわたり連続実行され、認証情報と秘密情報の探索が行われた。
  + URL: https://www.security.com/threat-intelligence/african-stock-exchange-ai-assisted-attack
* 攻撃ツールの中核にLLMを組み込み、人間の承認なしに自律実行させる事例（Skynet）が登場。偵察・悪用・認証情報窃取・ボットネット制御など約74個の関数を搭載。
  + URL: https://www.security.com/threat-intelligence/cyber-ai-predictions-2027

## 2. 国家支援型攻撃

* 北朝鮮は開発者・DevOps環境を標的としたサプライチェーン攻撃が増加。中国のAPT41はBlackX UEFIブートキットで外交機関へ長期侵入。Vapor Pandaは、ARTEX（DeepSeekベースのAI侵入フレームワーク）を使用して脆弱性の悪用、権限昇格、内部偵察を自動化し、少なくとも9つの組織への侵入が確認された。ロシアのAPT28はNATO加盟国の法執行機関・防衛請負業者を標的。イランのCL-STA-1178は求人を装った悪意あるVisual Studioプロジェクトを配信。
  + URL: https://asec.ahnlab.com/en/96569/

## 3. 一般社員向け

* ブラックフライデーに急増するフィッシングメールへの注意喚起（カスペルスキー報告）。11月の最初の2週間で22万件超の販促目的スパムメールを検出、2025年比50.2%増。
  + URL: https://securelist.com/black-friday-threat-report-2026/122061/
* 正規のAIツール配布ページを装ったウェブサイトから、BYOVDを組み込んだマルウェアが配布されている。
  + URL: https://asec.ahnlab.com/en/96708/
* インフォスティーラーの配布はSEOポイズニング、ファイルホスティングサービス、クラウドストレージ経由が主流。
  + URL: https://asec.ahnlab.com/en/96698/

## 4. 開発者向け

* マルチオペレーターC2システムEmperor（emp3r0r）が公開。AIで動作し、EDRの検知回避ループを搭載していると記載されている。
  + URL: https://github.com/jm33-m0/emp3r0r
* ゼロデイ脆弱性のPOC公開から悪用までの平均時間は1日未満、最短35分。POC公開後48時間以内に91%が悪用されている（CrowdStrike）。
  + URL: https://www.crowdstrike.com/en-us/blog/adversaries-turn-vulnerability-ecosystem-against-defenders/
* タイポスクワッターが大手ブランドの新規ドメイン登録からわずか1日で一文字違いの偽ドメインを登録。企業が利用する専門のドメイン登録業者を監視していたとみられる。
  + URL: https://www.security.com/threat-intelligence/typosquatting-new-brand-domains

## 5. 権威ドキュメント

* インシデント調査報告書の受領時チェックリストをJPCERT/CCが公開。報告書の構成や、調査結果・根拠の記載例が含まれる。
  + URL: https://blogs.jpcert.or.jp/ja/2026/11/ir_report_checklist.html
