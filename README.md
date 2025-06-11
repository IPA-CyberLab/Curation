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

* Sustaining Select Efforts to Strengthen the Nation's Cybersecurity and Amending Executive Order 13694 and Executive Order 14144 – The White House
  * 大統領令13694号および14144号 を改正。ホワイトハウス発表。人工知能を活用したセキュリティの推進や中国による重要インフラネットワークに対する攻撃に言及。2025年9月2日までに、NIST SP800-53を更新しパッチとアップデートを安全かつ確実に展開する方法に関するガイダンスを提供する旨記述。また、消費者向けIoT製品を連邦政府向けに販売しているベンダーに対し、それらの製品に米国サイバートラストマークの表示を義務付ける要件を採用する方針を示した。
  * 大統領令, GroupA（政府組織、JASA、CISA、Gartner）, OT, ICS, 工場セキュリティ, 重要インフラ, AI
  * 2025年6月12日 5:11
  * https://www.whitehouse.gov/presidential-actions/2025/06/sustaining-select-efforts-to-strengthen-the-nations-cybersecurity-and-amending-executive-order-13694-and-executive-order-14144/

* Breaking down ‘EchoLeak’, the First Zero-Click AI Vulnerability Enabling Data Exfiltration from Microsoft 365 Copilot | Aim Labs | Echoleak Blogpost
  * Microsoft 365 (M365) Copilot に「EchoLeak」と呼ばれる脆弱性。脆弱性は既に修正済み。Aim Labs報告。最小権限の原則に違反しているLLMが，「権限のないメール」（つまり、
    * 組織外から送信されたメール）によってプロンプトインジェクションを許し，権限のあるデータ（つまり、組織内から送信されたデータ）にアクセスすることが出来た。Aim Labsによると，AIアプリケーションに特有の新たな脅威であるとしている。
  * AI, Agentic AI, 脆弱性, プロンプトインジェクション
  * 2025年6月12日 5:12
  * https://www.aim.security/lp/aim-labs-echoleak-blogpost

* Gone But Not Forgotten: Black Basta’s Enduring Legacy - ReliaQuest
  * Black Bastaの解散後も，元メンバーは実績のある戦術を使い続けている可能性がある。ReliaQuest報告。大量のメールスパムとそれに続くTeamsフィッシング（サポートなりすまし）は、依然として持続的かつ効果的な攻撃方法となっている。元メンバーは，CactusやBlackLockに合流した可能性があるとしている。
  * ランサムウェア: Black Basta, ランサムウェア:Cactus, ランサムウェア：BlackLock
  * 2025年6月12日 5:12
  * https://reliaquest.com/blog/decline-and-legacy-of-black-basta-whats-next-ransomware-phishing/

* Memo-AcceleratingSecureSoftware.pdf | Department of Defense
  * アメリカ国防総省がソフトウェア・ファスト・トラック（SWFT）イニシアチブの開発を指示。(1)サイバーセキュリティとSCRM( Supply Chain Risk Management)の要件、(2)厳格なソフトウェアセキュリティ検証プロセス、(3)安全な情報共有メカニズム、(4)迅速なソフトウェア採用のためのサイバーセキュリティ認可を迅速化する連邦政府主導のリスク判定を明確かつ具体的に定義するものであるとしている。
  * GroupA（政府組織、JASA、CISA、Gartner）, SBOM
  * 2025年6月12日 5:19
  * https://dodcio.defense.gov/Portals/0/Documents/Library/Memo-AcceleratingSecureSoftware.pdf

* 偽CAPTCHA認証の指示で利用者を操りマルウェア感染させる攻撃キャンペーンを確認 | トレンドマイクロ | トレンドマイクロ (JP)
  * 偽のCAPTCHAページを用いた攻撃事例が急増している。トレンドマイクロ報告。攻撃手口は、フィッシングメール、不正URLを用いた誘導手口、不正広告、SEOポイズニングなどを介して到達する。
  * 攻撃手法:ClickFix
  * 2025年6月12日 5:21
  * https://www.trendmicro.com/ja_jp/research/25/f/unmasking-fake-captcha-cases.html

* Two Botnets, One Flaw: Mirai Spreads Through Wazuh Vulnerability | Akamai
  * Botnet Miraiの亜種がWazuhの脆弱性を通じて拡散している。Akamai社報告。2025 年 2 月の最初の開示以来、この脆弱性を悪用した最初のアクティブな攻撃として報告された。
  * Mirai
  * 2025年6月12日 5:22
  * https://www.akamai.com/blog/security-research/botnets-flaw-mirai-spreads-through-wazuh-vulnerability





## Archive
[202504](https://github.com/IPA-CyberLab/Curation/blob/202504/news.json)  
[202505](https://github.com/IPA-CyberLab/Curation/blob/202505/news.json)  
[20250606](https://github.com/IPA-CyberLab/Curation/blob/20250606/news.json)  
[20250608](https://github.com/IPA-CyberLab/Curation/blob/20250608/news.json)  
[20250610](https://github.com/IPA-CyberLab/Curation/blob/20250610/news.json)  
[20250611](https://github.com/IPA-CyberLab/Curation/blob/20250611/news.json)  
