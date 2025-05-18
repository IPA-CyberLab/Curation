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
### AI
* Phishing in 2025: GenAI’s Role in Hyper-Personalized Attacks
  * ヴィッシングが中心的役割を担う: 音声フィッシング (ヴィッシング) は、攻撃者が IT サポートを装って認証情報をリアルタイムで盗むという、目立った戦術になっています。
  * Vishing (Voice Phishing), CAPTCHA, 暗号通貨/仮想通貨, AI
  * 2025年4月27日 10:54
  * https://www.zscaler.com/jp/campaign/threatlabz-phishing-report

* Threat Analysis: New Noodlophile Stealer Distributes Via Fake AI Video Generation Platforms
  * ブラウザの認証情報の窃取、ウォレットからの情報流出、そしてオプションのリモートアクセス展開といった機能を備えるマルウェア「Noodlophile Stealer」登場。AIをソーシャルエンジニアリングの餌として悪用し、新たな合法的なトレンドを感染経路へと転用している点です。
  * AI, フィッシング
  * 2025年5月12日 5:33
  * https://www.morphisec.com/blog/new-noodlophile-stealer-fake-ai-video-generation-platforms/

* Inside RSAC 2025: The Five Emerging Attack Techniques That Demand Your Attention | SANS Institute
  * SANS Institute の基調講演///1. 認可の乱立（組織がユーザーに重複した権限や過剰な権限を付与する）///2. ICSランサムウェア///3. 破壊的なICS攻撃///4. デジタルフォレンジックの新たな課題（現代の脅威アクターがフォレンジックアーティファクトの消去または作成防止の技術をいかに洗練させているかを強調）///5. AI規制の脅威（攻撃者がAIを武器として利用するケースが増えているにもかかわらず、防御側がシステムを効果的に監視する能力を制限する可能性がある。）
  * GroupB（MITRE, CSA, OWASP, Google, フィッシング対策協議会, SANS, Linux Foundation, ISACA）, OT, ICS, 工場セキュリティ, AI
  * 2025年5月13日 21:52
  * https://www.sans.org/blog/inside-rsac-2025-the-five-emerging-attack-techniques-that-demand-your-attention/

* AI Agents Fail in Novel Ways, Put Businesses at Risk
  * マイクロソフトの AI レッド チームは 4 月 24 日に公開した論文の中で、人工知能 (AI) を搭載し企業が導入するエージェントには、少なくとも 10 種類の新しい広範な障害のクラスが存在すると述べています。これらの障害は、AI アプリケーションまたは環境の安全性やセキュリティを危険にさらす可能性があります。大規模言語モデル (LLM) の障害によって機密情報や危険な情報、不適切な言葉が漏れる可能性がある一方で、マイクロソフトが特定した障害モードでは、エージェントが攻撃者に代わって行動したり、誤った判断を下したり、ユーザーに危害を加えたりする可能性があります。
  * AI
  * 2025年5月13日 22:30
  * https://www.microsoft.com/en-us/security/blog/2025/04/24/new-whitepaper-outlines-the-taxonomy-of-failure-modes-in-ai-agents/


* Real AI Agents with Fake Memories: Fatal Context ManipulationAttacks on Web3 Agents
  * プリンストン大学とセンティエント社の研究者による新たな研究によると、AIエージェントが意思決定を行う際に頼りにするデータに偽の「記憶」を埋め込むことで、AIエージェントに悪意のある行動を誘発させることが可能とのこと。
  * AI
  * 2025年5月15日 9:12
  * https://arxiv.org/pdf/2503.16248

* Cofense_The-Rise-of-AI_2025.pdf
  * 脅威アクターは現在、AIを活用して、経営幹部を装った説得力のあるメールを作成しています。多くの場合、実際の転送スレッドを模倣し、支払い承認に関する言及をしています。これらのメッセージは「@consultant.com」などの類似ドメインから送信され、AIによって作成されるため、通常であれば疑わしい誤字、一貫性のないフォーマット、言い回しが少なくなっています。//////悪意のあるメールの報告数が最も増加した業界://////教育：341%///建設：1,282%///税金関連キャンペーン：340%///正規のファイルを利用したキャンペーン：575%
  * AI, Polymorphic, フィッシング, 統計
  * 2025年5月17日 5:15
  * https://cofense.com/getmedia/46bf7141-4bca-4ab7-8ca8-c6cb8ae5140c/Cofense_The-Rise-of-AI_2025.pdf

* AI-powered Threats Case Study #02: Vulnerabilities
  * サイバー犯罪者は、ChatGPT、Claude、DeepSeek などの生成 AI や大規模言語モデル (LLM) を武器として利用し、エクスプロイトの開発を自動化し、セキュリティ保護を回避し、マルウェア キャンペーンを改良するケースが増えています。//////ダーク ウェブ フォーラムでは 2025 年初頭から AI を活用した攻撃ツールに関する議論が急増している。//////注目すべき例の 1 つは、重大なリモート コード実行の脆弱性である CVE-2024-10914 の悪用で、AI 生成のスキャナーとペイロードが Cracked や BreachForums などのプラットフォームで公開されました。//////2025年1月に「KuroCracks」というユーザーがCVE-2024-10914用のMasscanベースのスキャナーを配布し、ChatGPTを使用して最適化されていると主張した事例を特定したとされる。
  * AI
  * 2025年5月18日 19:28
  * https://s2w.inc/en/resource/detail/825?utm_source=twitter&utm_medium=social-posts&utm_campaign=ti-reports&utm_term=vulnerability&utm_content=ai-llm-02

* Xanthorox – New BlackHat AI Tool Used to Launch Phishing & Malware Attacks
  * フィッシングやマルウェア攻撃の実行に使用される新しいAIツール, Xanthoroxが登場。///攻撃的なサイバー作戦の特定の側面に合わせて設計された 5 つの特殊な AI モデルを備えたモジュール式のマルチモデル アーキテクチャとなっている。
  * AI, Xanthorox
  * 2025年5月18日 19:35
  * https://cybersecuritynews.com/xanthorox-ai-blackhat-tool/

### DPRK
* m-trends-2025-en.pdf
  * 北朝鮮のハッカーが1日のフィッシング攻撃でTRONユーザーから1億3700万ドルを盗むことに成功した模様。Google報告。
  * フィッシング, 北朝鮮/DPRK
  * 2025年4月24日 6:47
  * https://services.google.com/fh/files/misc/m-trends-2025-en.pdf

* How China and North Korea Are Industrializing Zero-Days
  * Google Cloud の脅威インテリジェンス チームによる新しいレポートでは、中国と北朝鮮の国家主体によるゼロデイ脆弱性の利用が急増していることが強調されており、北朝鮮のエクスプロイト量が中国に匹敵するのは初めてです。
  * 0day/ゼロデイ, 中国, 北朝鮮/DPRK
  * 2025年5月13日 23:10
  * https://www.bankinfosecurity.com/how-china-north-korea-are-industrializing-zero-days-a-28252

* APT GROUP123 - CYFIRMA
  * 北朝鮮の国家支援を受ける脅威アクターAPTグループ123は、サイバースパイ活動を強化しており、特に世界中の複数の分野のWindowsシステムを標的としている。//////このグループは少なくとも2012年から活動しており、APT37、Reaper、ScarCruftなどの別名でも追跡されており、歴史的には韓国を標的としていたが、近年は日本、ベトナム、中東、その他の地域にも活動を拡大している。///Cyfirma の研究者は、これらの攻撃の影響は情報窃盗だけにとどまらず、同グループが現在、スパイ活動と並行して金銭目的のランサムウェア攻撃を行っていることを確認したとしている。
  * 北朝鮮/DPRK, APT, APT:APT123, 航空・宇宙業界
  * 2025年5月18日 19:23
  * https://www.cyfirma.com/research/apt-group123/

* 北朝鮮背景のサイバー犯罪を支えるロシアのネットワークインフラ | トレンドマイクロ | トレンドマイクロ (JP)
  * ///トレンドマイクロの評価によれば、北朝鮮に関係するアクターはロシアのIPアドレスレンジを利用して、数十台のVPSサーバへRDP接続し、求人サイトでのやり取りや暗号資産関連サービスへのアクセスなどのタスクを行っているとのこと。暗号資産ウォレットのパスワードを総当たり攻撃で解析しようとする活動に使われているサーバの一部も、これらのロシアのIPレンジに含まれている模様。///さらに、Void Dokkaebiが使用するBeavertailマルウェアのコマンド＆コントロールサーバの構築方法や、暗号資産ウォレットのパスワードを解析する方法を解説した動画も確認したとされる。
  * 北朝鮮/DPRK, ロシア
  * 2025年5月18日 20:23
  * https://www.trendmicro.com/ja_jp/research/25/e/russian-infrastructure-north-korean-cybercrime.html

* Analysis of APT37 Attack Case Disguised as a Think Tank for National Security Strategy in South Korea (Operation. ToyBox Story)
  * 2025年3月、北朝鮮の国家支援を受けたハッカー集団APT37によるものとされる高度なスピアフィッシング攻撃が、北朝鮮情勢に関心を持つ活動家を標的にしていた。///注目を集めるために、韓国の国家安全保障シンクタンクからの学術フォーラムへの招待を装うなどしていた模様。///APT37は、以前にpCloudとYandexを使用した後、DropboxをC2サーバーとして使用していた。
  * APT: APT37, ScarCruft, Reaper, Red Eye, 北朝鮮/DPRK
  * 2025年5月18日 20:38
  * https://www.genians.co.kr/en/blog/threat_intelligence/toybox-story

### ランサムウェア
* 暴露型ランサムウェア攻撃グループ「HellCat」のリークサイトが閉鎖。
  * 2024年に出現を確認した暴露型ランサムウェア攻撃グループである「HellCat」のリークサイトの内容が閉鎖を示唆する記載に変化したことを確認。//////実質的な同ブランド名での活動停止およびリブランドへの移行の可能性がある。//////メンバーとして知られる一人は「HellCatプロジェクトは終了し別の団体へ移管された」と一部でコメントしている。
  * ランサムウェア:Hellcat, ランサムウェア
  * 2025年5月13日 22:12
  * https://x.com/MalwareBibleJP/status/1921750247702970693?t=BYeEhq7X2zqPS86auaXAAA&s=09

* Lockbit Ransomware Hacked - Leaked Database Exposes Internal Chats
  * Lockbitランサムウェア集団が使用していたリークサイトがハッキングされ、改ざんされたという。//////リークサイトは、「犯罪はやめましょう。犯罪は悪いことです。プラハより xoxo」という短いテキストメモに置き換えられました
  * Hackback, ランサムウェア
  * 2025年5月13日 22:36
  * https://cybersecuritynews.com/lockbit-ransomware-hacked/

* Someone hacked ransomware gang Everest’s leak site | TechCrunch
  * Everest ランサムウェア集団が使用していたリークサイトが今週末ハッキングされ、改ざんされたという。//////リークサイトは、「犯罪はやめましょう。犯罪は悪いことです。プラハより xoxo」という短いテキストメモに置き換えられました
  * Hackback, ランサムウェア
  * 2025年5月13日 22:39
  * https://techcrunch.com/2025/04/07/someone-hacked-everest-ransomware-gang-dark-web-leak-site/

* Why Ransomware Isn’t Just a Technology Problem (It’s Worse) - Security Boulevard
  * なぜランサムウェアは単なる技術的問題ではないのか。各関係者毎に支払うべきかに異なるインセンティブがあり、ゴールは競合している。結果として市場の失敗が発生。組織内で方針を明確にするとで混乱は軽減可能。
  * ランサムウェア
  * 2025年5月13日 23:07
  * https://securityboulevard.com/2025/05/why-ransomware-isnt-just-a-technology-problem-its-worse/

* Emulating the Terrorizing VanHelsing Ransomware - AttackIQ
  * AttackIQ はVanHelsing ランサムウェアの動作をエミュレートする新しい攻撃グラフを公開しました。VanHelsing ランサムウェアは，2025 年 3 月に登場し、急速に成長している新しいランサムウェア・アズ・ア・サービス (RaaS) アフィリエイト プログラムであり，イングレス ツール転送，仮想化/サンドボックス回避，システム回復の禁止などの機能を持つ。
  * ランサムウェア, Ransomware-as-a-Service (RaaS), ランサムウェア:VanHelsing
  * 2025年5月16日 9:15
  * https://www.attackiq.com/2025/05/15/emulating-vanhelsing-ransomware/

### Authoritative
* Inside RSAC 2025: The Five Emerging Attack Techniques That Demand Your Attention | SANS Institute
  * SANS Institute の基調講演///1. 認可の乱立（組織がユーザーに重複した権限や過剰な権限を付与する）///2. ICSランサムウェア///3. 破壊的なICS攻撃///4. デジタルフォレンジックの新たな課題（現代の脅威アクターがフォレンジックアーティファクトの消去または作成防止の技術をいかに洗練させているかを強調）///5. AI規制の脅威（攻撃者がAIを武器として利用するケースが増えているにもかかわらず、防御側がシステムを効果的に監視する能力を制限する可能性がある。）
  * OT, ICS, 工場セキュリティ, AI
  * 2025年5月13日 21:52
  * https://www.sans.org/blog/inside-rsac-2025-the-five-emerging-attack-techniques-that-demand-your-attention/

* Building a Better OT Ransomware Response Plan: A Simple Framework for ICS Environments | SANS Institute
  * OTにおいて、良いランサムウェア対策計画を立てる方法・・・環境を知る///IT/OTの（コミュニケーションの）断絶を是正する///プレイブック自体は、SANS PICERLライフサイクル（準備、特定、封じ込め、根絶、復旧、そして教訓の活用）に合わせ，何を含めるかを考える。
  * OT, ICS, 工場セキュリティ
  * 2025年5月13日 22:09
  * https://www.sans.org/blog/building-a-better-ot-ransomware-response-plan-a-simple-framework-for-ics-environments/

* 悪用された脆弱性の傾向分析 | PwC Japanグループ
  * ソフトウェア種別の傾向、CVSS基本評価基準の傾向、脆弱性の攻撃手法の傾向などで分析。///脆弱性が悪用されやすいソフトウェアの種別が存在する///悪用された脆弱性のCVSSは比較的高い傾向にある///悪用される脆弱性の多くは端末への侵入（Initial Access）・実行（Execution）、特権の奪取（Privilege Escaration）など、攻撃の最初のステップとして利用されている
  * 統計
  * 2025年5月13日 22:32
  * https://www.pwc.com/jp/ja/knowledge/column/awareness-cyber-security/vulnerabilities-exploited.html

* Cybersecurity Skills Framework
  * Linux Foundationは本日、サイバーセキュリティ スキル フレームワークの立ち上げを発表しました。これは、サイバーセキュリティ専門家にとどまらず、幅広いIT職種において重要なサイバーセキュリティ能力を特定し、対処するためのグローバル リファレンス ガイドです。///このフレームワークは、基礎、中級、上級の熟練度レベルにおける実践的なサイバーセキュリティの期待値を定義し、それらのスキルをDoD 8140、CISA NICEフレームワーク、ICT e-CFなどの認定標準にマッピングします。広く採用されている標準に準拠し、カスタマイズも可能なため、このフレームワークは業界、地域、組織規模を問わず容易に導入できます。このフレームワークは、無料で使いやすいウェブインターフェースで提供されており、ユーザーは関連する職種を選択したり、スキルをカテゴリ間で移動したり、該当しないスキルを削除したり、必要なカスタム項目を追加したりできます。
  * 教育、社内教育、訓練
  * 2025年5月17日 3:42
  * https://cybersecurityframework.io/

* Primary Mitigations to Reduce Cyber Threats to
Operational Technology
  * Cybersecurity and Infrastructure Security Agency（CISA）、Federal Bureau of Investigation（FBI）、Environmental Protection Agency（EPA）、Department of Energy（DOE）は、米国の重要インフラ事業体の運用技術（OT）および産業制御システム（ICS）に影響を及ぼすサイバーインシデントを認識していると公表。重要インフラ事業体に対し、インターネットに接続された OT および ICS を特に意図的に標的とするサイバー脅威活動に対するサイバーセキュリティ態勢を改善するために、今すぐ検討し、行動するよう要請した。///1. 公衆インターネットへのOT接続を削除する。///2. デフォルトのパスワードを直ちに変更し、強力でユニークなパスワードを使用する。///3. OTネットワークへのリモートアクセスを保護する。///4. IT ネットワークと OT ネットワークをセグメント化する。///5. OT システムを手動で操作する能力を練習し、維持する。
  * OT, ICS, 工場セキュリティ
  * 2025年5月17日 7:52
  * https://www.ic3.gov/CSA/2025/250506.pdf


## Archive
[202504](https://github.com/IPA-CyberLab/Curation/tree/202504)
