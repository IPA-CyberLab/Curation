# CyberSecurity News Curation

## 概要

このリポジトリでは、サイバーセキュリティに関する最新のニュースやトピックをキュレーション*し、整理して掲載しています。

## 作成にあたって

- 収集にあたって，なるべく1次ソースを追うようにしています。
- 英語のニュースについては，意訳を施してサマリーとして掲載します。
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

## ニュース更新
* Blitz Malware: A Tale of Game Cheats and Code Repositories
  * Blitzマルウェアをバックドアを仕込んだゲームチートを介して拡散する活動を観測。Palo Alto Networks UNIT42報告。Blitzマルウェアは、ダウンローダーとボットペイロードの2段階で構成。Blitzの開発者は、人工知能（AI）コードリポジトリ「Hugging Face Spaces」を悪用し、C2インフラのファイルやコンポーネントをホストしていた。後続のマルウェアには、仮想通貨Moneroをマイニングするマルウェアも。
  * マルウェア：Blitz, ゲームチート
  * 2025年6月10日 6:11
  * https://unit42.paloaltonetworks.com/blitz-malware-2025/

* DuplexSpy RAT: Stealthy Windows Malware Enabling Full Remote Control and Surveillance - CYFIRMA
  * 新規のRATである，DuplexSpy RATがGitHub上で公開された。CYFIRMA報告。DuplexSpy RATは、スタートアップフォルダーの複製とWindowsレジストリの変更によって永続化を確立するとともに、ファイルレス実行と権限昇格の手法を用いてステルス性を高める。主な機能には、キーロギング、スクリーンキャプチャ、Webカメラ/音声の盗聴、リモートシェル、解析回避機能など。
  * RAT(Remote Access Tool), RAT: DuplexSpy RAT
  * 2025年6月10日 6:25
  * https://www.cyfirma.com/research/duplexspy-rat-stealthy-windows-malware-enabling-full-remote-control-and-surveillance/

* Follow the Smoke | China-nexus Threat Actors Hammer At the Doors of Top Tier Targets | SentinelOne
  * SentinelOneを標的とした偵察作戦と関連する活動クラスターPurpleHazeとShadowPadについて。SentinelOne報告。活動クラスターは、2024年7月から2025年3月の間に発生した、異なるターゲットへの複数の部分的に関連した侵入にまたがります。被害者には、日本を含む南アジアの政府機関、欧州の報道機関、および幅広い分野の70以上の組織が含まれる。PurpleHazeの侵入の一部が、APT15およびUNC5174として公に報告されている中国のサイバースパイ集団の容疑者と重なる行為者と緩やかに関連していると考えている。
  * 中国, ターゲット：セキュリティベンダー
  * 2025年6月10日 6:29
  * https://www.sentinelone.com/labs/follow-the-smoke-china-nexus-threat-actors-hammer-at-the-doors-of-top-tier-targets/

* Analysis of the Triple Combo Threat of the Kimsuky Group
  * Kimsukyが、2025年3月から4月にかけて実施した攻撃について。Facebook、メール、Telegramのプラットフォームのユーザーをターゲットにした高度なマルチプラットフォームキャンペーン。北朝鮮脱北者のボランティア活動に関する信憑性のあるコンテンツでターゲットを誘い込んでいた。
  * 北朝鮮/DPRK
  * 2025年6月10日 6:50
  * https://www.genians.co.kr/en/blog/threat_intelligence/triple-combo?hs_amp=true

* Internet Crime Complaint Center (IC3) | Home Internet Connected Devices Facilitate Criminal Activity
  * 連邦捜査局 ( FBI ) が、サイバー犯罪者が家庭内ネットワークに接続されたモノのインターネット ( IoT ) 1デバイスを悪用し、BADBOX 2.0 を使用して犯罪行為を行っていることについて警告。サイバー犯罪者は、TV ストリーミング デバイス、デジタル プロジェクター、アフターマーケットの車載インフォテインメント システム、デジタル フォト フレームなどの IoT デバイスを侵害して、家庭内ネットワークに不正アクセスする。感染したデバイスのほとんどは中国で製造されていたとのこと。
  * FBI, GroupA（政府組織、JASA、CISA、Gartner）, Botnet, BADBOX2.0, IoT
  * 2025年6月10日 7:02
  * https://www.ic3.gov/PSA/2025/PSA250605#fn2

* Threat landscape for industrial automation systems. Regions, Q1 2025 | Kaspersky ICS CERT
  * 2025年第1四半期の産業オートメーションシステムのセキュリティに関する統計。カスペルスキー報告。東アジア内でのICSコンピュータで検知した脅威のトップはスパイウェア。また、東アジアはランサムウェアおよびNASでの検知率が世界1位。
  * OT, ICS, 工場セキュリティ, 統計
  * 2025年6月11日 11:58
  * https://ics-cert.kaspersky.com/publications/reports/2025/06/10/threat-landscape-for-industrial-automation-systems-regions-q1-2025/

* Eggs in a Cloudy Basket: Skeleton Spider’s Trusted Cloud Malware Delivery - DomainTools Investigations | DTI
  * Skeleton Spider（別名FIN6）によるソーシャルエンジニアリングテクニックについて。DomainTools報告。LinkedInやIndeedなどの求人プラットフォームを介して連絡を取り始め、熱心な求職者を装って採用担当者とやり取りした後、フィッシングメッセージを送信する。
  * 偽求人・面接（Job Interview）, 偽の労働者, 脅威アクター: FIN 6/Skeleton Spider
  * 2025年6月11日 12:12
  * https://dti.domaintools.com/skeleton-spider-trusted-cloud-malware-delivery/

* Deceptive Links: Unmasking SharePoint Phishing Attacks – CyberProof
  * フィッシング攻撃においてSharePointの悪用が急増している。CyberProof報告。フィッシング成功後、悪意のある受信トレイルールを作成し、組織の内外に悪意のあるコンテンツを転送を試みる。
  * フィッシング, LOtL (Living Off the Land), SharePoint
  * 2025年6月11日 12:13
  * https://www.cyberproof.com/blog/deceptive-links-unmasking-sharepoint-phishing-attacks/

* TRACE Report: Researching Exposed Cameras in the Wild | Bitsight
  * 日本国内において，インターネット上で公開状態になっているカメラが7000台以上見つかる。Bitsight報告。アメリカの14,000台に次いで2位。国外のカメラについては，ハッキングされて画面上に不正な文字が表示されているものも発見されていた。
  * IoT
  * 2025年6月11日 22:03
  * https://www.bitsight.com/resources/trace-report-researching-exposed-cameras-wild

* 20,000 malicious IPs and domains taken down in INTERPOL infostealer crackdown
  * 情報窃盗犯摘発で2万件の悪質IPとドメインが削除された。インターポール発表。Operation Secureというコードネームがついた本活動は2025年1月～4月で行われ、日本を含む26か国の法執行機関がサーバーの特定、物理ネットワークのマッピング、標的の削除に取り組んだ。
  * 警察, テイクダウン
  * 2025年6月11日 22:11
  * https://www.interpol.int/News-and-Events/News/2025/20-000-malicious-IPs-and-domains-taken-down-in-INTERPOL-infostealer-crackdown





## Archive
[202504](https://github.com/IPA-CyberLab/Curation/blob/202504/news.json)  
[202505](https://github.com/IPA-CyberLab/Curation/blob/202505/news.json)  
[20250606](https://github.com/IPA-CyberLab/Curation/blob/20250606/news.json)  
[20250608](https://github.com/IPA-CyberLab/Curation/blob/20250608/news.json)  
[20250610](https://github.com/IPA-CyberLab/Curation/blob/20250610/news.json)  
