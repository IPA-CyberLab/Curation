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
* Newly identified wiper malware “PathWiper” targets critical infrastructure in Ukraine
  * ウクライナ国内の重要インフラに対し、これまで知られていないワイパー「PathWiper」を使用した破壊的な攻撃が観測された。この攻撃とそれに関連するワイパーを、ロシアと関係のある高度で持続的な脅威（APT）の攻撃者によるものと推定しているとのこと。Cisco Talos報告。
  * 重要インフラ, ワイパー, マルウェア, ロシア, OT, ICS, 工場セキュリティ
  * 2025年6月6日 12:53
  * https://blog.talosintelligence.com/pathwiper-targets-ukraine/

* From open-source to open threat: Tracking Chaos RAT’s evolution
  * 最近の実際の Linux および Windows 攻撃で、既知のマルウェア ファミリである Chaos RAT の新しい亜種が発見された。Acronis TRU報告。Chaos RAT は、 2022 年に初めて確認されたオープンソースのリモート管理ツール (RAT) です。2024 年に進化し、2025 年に TRU によって新しいサンプルが発見されている。
  * RAT(Remote Access Tool), RAT: Chaos RAT, OSS, オープンソース
  * 2025年6月6日 13:07
  * https://www.acronis.com/en-us/cyber-protection-center/posts/from-open-source-to-open-threat-tracking-chaos-rats-evolution/

* Turning Off the (Information) Flow: Working With the EPA to Secure Hundreds of Exposed Water HMIs
  * 米国の水道施設向けのWebベースのHMI約400件がオンラインで公開されていることを発見された。Censys報告。すべてのシステムは 同じブラウザベースの HMI/SCADA ソフトウェアを使用していた。
  * OT, ICS, 工場セキュリティ, ASM
  * 2025年6月6日 13:10
  * https://censys.com/blog/turning-off-the-information-flow-working-with-the-epa-to-secure-hundreds-of-exposed-water-hmis

* The State of DDoS Attacks in APAC in Q1 2025
  * 2025年第1四半期のアジア太平洋地域におけるDDoS攻撃の状況、StormWall報告。2024年第4四半期から2025年第1四半期で、日本に対する攻撃数は、7％→9％に変化。業種別では、通信業（31%）、エンターテインメント（18%）、政府機関（１12%）が上位。
  * DDoS, 統計
  * 2025年6月6日 13:15
  * https://stormwall.network/resources/blog/ddos-report-apac-q1-2025?rs=linkedin_q1apac2025_0406_ln_post

* Lumma Infostealer – Down but Not Out? - Check Point Blog
  * Lumma の開発者は、活動を再開し、通常通りの業務を遂行するために取り組みをしている。Check Point報告。2025年5月21日、ユーロポール、FBI、マイクロソフトは、他の官民パートナーと協力し、Lummaインフォスティーラーの活動を撲滅するための作戦を発表していた。
  * Infostealer/インフォスティーラー, Lumma
  * 2025年6月6日 13:29
  * https://blog.checkpoint.com/security/lumma-infostealer-down-but-not-out/

* The State of Cloud Runtime Security 2025 - ARMO
  * クラウドランタイムのセキュリティについてARMO報告。月平均4,080件のアラートのうち、実際のインシデントは年間7件。89％のチームがアクティブな脅威の検出に失敗していると回答。63%が5つ以上のクラウド・ランタイム・セキュリティ・ツールを使用している。しかし、これらのツール間でアラートを関連付けることができるのは13%としている。
  * クラウドランタイム (Cloud Runtime), クラウド, 統計
  * 2025年6月6日 13:34
  * https://www.armosec.io/cloud-runtime-security-survey-2025/

* #StopRansomware: Play Ransomware | CISA
  * 2025 年 5 月時点で、FBI はランサムウェア攻撃者によって悪用されたとされる約 900 の影響を受けたことを把握していました。連邦捜査局（FBI）報告。連邦捜査局（FBI）、サイバーセキュリティ・インフラストラクチャセキュリティ庁（CISA）、およびオーストラリア通信信号局のオーストラリアサイバーセキュリティセンター（ASDのACSC）は、2025年1月までのFBIの捜査を通じて特定されたPlayランサムウェアグループのIOCとTTPを広めるために、発表した共同勧告を更新。
  * ランサムウェア:Play, GroupA（政府組織、JASA、CISA、Gartner）
  * 2025年6月6日 13:45
  * https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-352a

* Phishing e-mail that hides malicious link from Outlook users - SANS Internet Storm Center
  * Outlookユーザを回避するフィッシングテクニックが発見された。SANS報告。「ブラウザ」に応じて表示コンテンツを変更する手法（HTML条件文<!--[if mso]>と<!--[if !mso]>）を利用し、 Outlook で表示/指定されているリンクを無害なものに変更し、他の電子メール クライアント/ブラウザーでは、おそらく資格情報を盗む Web サイトを指すようにしていた。
  * GroupB（MITRE, CSA, OWASP, Google, フィッシング対策協議会, SANS, Linux Foundation, ISACA）, Defense Evasion, 防御無効化, Bypass
  * 2025年6月6日 13:49
  * https://isc.sans.edu/diary/32010



## Archive
[202504](https://github.com/IPA-CyberLab/Curation/tree/202504)

[202505](https://github.com/IPA-CyberLab/Curation/tree/202505)
