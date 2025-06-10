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
* Decoding ‘ClickFix’: Lessons from the Latest Browser-Based Phish
  * CloudflareのTurnstileインターフェースを模倣するClickFix手法が発見された。SlashNext報告。「人間であることを確認してください」というボックスにチェックを入れると、コマンドプロンプトを立ち上げて、Powershellスクリプトのコピーペーストを実行するようにユーザーを誘導する。
  * 攻撃手法:ClickFix, フィッシング
  * 2025年6月7日 7:40
  * https://slashnext.com/blog/decoding-clickfix-lessons-from-the-latest-browser-based-phish/

* DragonForce: The Ransomware Cartel Guarding Its Burrow
  * DragonForceは過去1年間で120以上の被害者を出した。Bitdefender報告。このグループは、米国、イタリア、オーストラリアなどの国に拠点を置く組織を攻撃してきた。DragonForceは、 Schtasks.exeやTaskkill.exeといった正規の実行ファイルを用いて常駐化を図るというLiving Off the Landなどの手法を用いるとされている。DragonForceは、製造業、建設業、テクノロジー、ヘルスケア、小売業などの業界が標的。
  * ランサムウェア：DragonForce, ランサムウェア, 統計
  * 2025年6月7日 7:50
  * https://www.bitdefender.com/en-us/blog/businessinsights/dragonforce-ransomware-cartel

* Ponemon Institute Survey – Digital Executive Protection Research Report 2025 - BlackCloak | Protect Your Digital Life™
  * 経営幹部を狙ったサイバー攻撃が増加。2023年比。BlackCloakがスポンサーとなったポネモン研究所の最新調査。過去2年間に経営幹部の51%がサイバー攻撃の標的となり、2023年の43%から増加。幹部がDeepFakeを用いたなりすましの標的になったという報告は2025年は41%に増加。2023年では34%だった。
  * なりすまし, DeepFake, 統計
  * 2025年6月7日 8:00
  * https://blackcloak.io/white-papers-reports/ponemon-digital-executive-protection-report-2025/

* Cybercriminals camouflaging threats as AI tool installers
  * AIソリューションのインストーラーやツールを装った様々なマルウェアを拡散することで、AIの普及を悪用している。 Cisco Talos 報告。正規の AI ツールのインストーラーを装い、ランサムウェア CyberLock、Lucky_Gh0$t、そして新たに発見された「Numero」と呼ばれるマルウェアなどがインストールされる。
  * ランサムウェア, Polymorphic, ポリモーフィック
  * 2025年6月7日 8:13
  * https://blog.talosintelligence.com/fake-ai-tool-installers/

* Disrupting malicious uses of AI: June 2025 | OpenAI
  * OpenAIが、「 AIの悪意ある使用の阻止」と題するケーススタディを完備した包括的な声明を発表。プロパガンダやインプレッション操作、児童搾取、詐欺（偽のIT労働者、リクルーティング）、スパム、AI]を利用したペネトレーションテストなど、人類の最善の利益に反する活動を実行するために独自のAIツールがますます利用されていることに対抗するための取り組みを詳述。
  * AI, AI for Attacker (Pentester)
  * 2025年6月7日 8:18
  * https://openai.com/global-affairs/disrupting-malicious-uses-of-ai-june-2025/

* Kali GPT- AI Assistant That Transforms Penetration Testing on Kali Linux
  * Kali Linuxユーザーのために微調整されたGPT-4上に構築されたAIモデル、Kali GPTが登場。ペンテスターがエクスプロイトの提案を受けたり、初心者のメンターとしての役割が想定される模様。
  * AI, AI for Security, AI for Attacker (Pentester)
  * 2025年6月8日 22:23
  * https://cybersecuritynews.com/kali-gpt/

* Demystifying Myth Stealer: A Rust Based InfoStealer
  * Myth Stealerの亜種が観測された。Trellix報告。Rustで記述されており、Gecko ベースのブラウザと Chromium ベースのブラウザの両方を標的とし、パスワード、クッキー、オートフィル情報などの機密データを抽出する。詐欺的ゲームウェブサイトを通じて配布されている。
  * Infostealer/インフォスティーラー, ブラウザ
  * 2025年6月8日 22:30
  * https://www.trellix.com/blogs/research/demystifying-myth-stealer-a-rust-based-infostealer/

* Unpacking ClickFix: Darktrace’s detection of a prolific social engineering tactic
  * 欧州、中東、アフリカ（EMEA）および米国の顧客環境において、複数のClickFix攻撃が確認された。Darktrace報告。フィッシング メールや偽の CAPTCHA プロンプトから始まり、ユーザーに悪意のある PowerShell コマンドを実行させる侵害が発生、C2通信に至った。
  * 攻撃手法:ClickFix
  * 2025年6月8日 22:35
  * https://www.darktrace.com/blog/unpacking-clickfix-darktraces-detection-of-a-prolific-social-engineering-tactic

* The strange tale of ischhfd83: When cybercriminals eat their own – Sophos News
  * GitHub でホストされているオープンソースのマルウェアプロジェクト「Sakura RAT」についてのレポート。Sphos報告。ゲームチーターや経験の浅い脅威アクターを標的としていた。特定のメールアドレスにリンクされた形で141 のリポジトリを発見。内133 には 4 つの異なる感染方法を利用するバックドアが含まれていた。その大部分はゲームチートを提供すると主張しており (58%)、その他のリポジトリはマルウェア プロジェクト、エクスプロイト、または攻撃ツールであると主張していた(24%)。
  * ハッキングバック, Hacking back, Github
  * 2025年6月8日 22:39
  * https://news.sophos.com/en-us/2025/06/04/the-strange-tale-of-ischhfd83-when-cybercriminals-eat-their-own/

* Central Bureau of Investigation (India) on X: "Operation Chakra V – CBI Conducts Searches at 19 Locations; Busts Transnational Cybercrime Syndicate Targeting Japanese Citizens; 6 Operatives Arrested https://t.co/yl1HrQyR0k" / X
  * インド中央捜査局（CBI）は、日本人を狙った高度な国際技術サポート詐欺に関与していたとして6人を逮捕し、違法コールセンター2か所を解体したことを明らかにした。当局は、日本の警察庁およびマイクロソフトと協力し、この計画の実行犯とその運営体制を追跡したと発表した。
  * 警察
  * 2025年6月8日 23:05
  * https://x.com/CBIHeadquarters/status/1927971239257108729

* 2025 Honeywell Cyber Threat Report
  * 産業システムに対するサイバー攻撃として、USBデバイスを介して拡散するランサムウェア、トロイの木馬、マルウェアが増大。Honeywellが”2025 Honeywell Cyber Threat Report”で報告。産業用制御システム向けに特別に設計された新しいランサムウェアの亜種が存在しないにもかかわらず、既存の敵対者は、重要なセクター全体で業務を妨害し続けた。USBは引き続き様々な種類のワームファミリーを持ち、新しいものも確認されている模様。
  * OT, ICS, 工場セキュリティ, 統計, ランサムウェア, ランサムウェア:CLOP, CL0P, USB
  * 2025年6月9日 6:33
  * https://www.honeywell.com/us/en/reports/2025/honeywell-cyber-threat-report

* Replay Attacks: The Blind Spot in Audio Deepfake Detection | Resemble AI
  * 音声ディープフェイク検出を回避する手法について。Resemble AIのチームと、Fraunhofer AISEC、ヴロツワフ工科大学、クルージュ＝ナポカ工科大学、Neodyme AG、ミュンヘン工科大学の研究者が共同発表。生成AI音声をスピーカーで再生し、再録音するだけでディープフェイク検出を回避することが可能になる。
  * DeepFake, Vishing (Voice Phishing), Defense Evasion, 防御無効化, Bypass
  * 2025年6月9日 6:56
  * https://www.resemble.ai/replay-attacks-the-blind-spot-in-audio-deepfake-detection/?trail=Blog%2520Case%2520Studies%2520and%2520Development%2520Thoughts%2520from%2520our%2520team.

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

* Forensic Analysis in Cybersecurity - Tools and Techniques for Incident Response
  * サイバーセキュリティにおけるフォレンジック分析 - インシデント対応のためのツールとテクニック。Volatility、Wireshark、Plaso
  * まとめ記事/メタアナリシス
  * 2025年6月10日 6:59
  * https://cybersecuritynews.com/forensic-analysis-in-cybersecurity/

* Internet Crime Complaint Center (IC3) | Home Internet Connected Devices Facilitate Criminal Activity
  * 連邦捜査局 ( FBI ) が、サイバー犯罪者が家庭内ネットワークに接続されたモノのインターネット ( IoT ) 1デバイスを悪用し、BADBOX 2.0 を使用して犯罪行為を行っていることについて警告。サイバー犯罪者は、TV ストリーミング デバイス、デジタル プロジェクター、アフターマーケットの車載インフォテインメント システム、デジタル フォト フレームなどの IoT デバイスを侵害して、家庭内ネットワークに不正アクセスする。感染したデバイスのほとんどは中国で製造されていたとのこと。
  * FBI, GroupA（政府組織、JASA、CISA、Gartner）, Botnet, BADBOX2.0, IoT
  * 2025年6月10日 7:02
  * https://www.ic3.gov/PSA/2025/PSA250605#fn2





## Archive
[202504](https://github.com/IPA-CyberLab/Curation/blob/202504/news.json)  
[202505](https://github.com/IPA-CyberLab/Curation/blob/202505/news.json)  
[20250606](https://github.com/IPA-CyberLab/Curation/blob/20250606/news.json)  
[20250608](https://github.com/IPA-CyberLab/Curation/blob/20250608/news.json)
