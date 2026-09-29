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

# 2026年9月 サイバー脅威動向レポートサマリー

## 1. AI技術に関連する攻撃と悪用

* AIの悪用を検知し、対策する：2026年9月。脅威アクターがClaudeを悪用しようとした作戦を特定・阻止した事例のレポート。AIの利用はチャットボットによる単純な質問と応答にとどまらず、偵察、悪用、データ漏洩を実行するマルチエージェントフレームワークの利用にまで及んだ。GTG-20006は、セキュリティ製品に検出された場合にツールキットを自動的に再構築して再展開するAI支援ワークフローを開発していた。
  + URL: https://www.anthropic.com/threat-intelligence-report-september-2026
* GTIG AI脅威トラッカー：プロンプトから自律性へ – 敵対的AIの進化。先進的な攻撃者が基本的なプロンプトからエージェント型AIワークフローやAIを活用した自動化へと移行していることを確認。人間が関与する遅延が劇的に減少し、防御側が対応できる従来の時間が短縮されている。
  + URL: https://cloud.google.com/blog/topics/threat-intelligence/from-prompting-to-autonomy-the-evolution-of-adversarial-ai/

## 2. 攻撃手法

* VectraRAT：文書化されていない、ゼロから構築されたフルスタックMaaS。流出したRATコードをフォークするのではなく完全にゼロから構築されたマルウェアサービスプラットフォーム。月額250ドルからレンタル可能で、デスクトップの隠し制御、キーロギング、クリップボードのハイジャック、ブラウザ認証情報の窃盗、プロンプトなしで権限昇格を行うUACバイパスなどの機能を提供。オペレーター「Vectra」は「Nyxel」のリブランド。
  + URL: https://socradar.io/blog/vectrarat-undocumented-stack-maas/
* SloppyRAT：ランサムウェア攻撃のための新たなツール。多段階のClickFix感染チェーンを通じて配信されている。多数の組み込みPowerShellライクなコマンド、暗号化されたコードブロック、Polygon JSON-RPCプロトコルを介したC2解決のためのEtherHiding、複数のアンチアナリシス機能をサポート。
  + URL: https://www.zscaler.com/blogs/security-research/sloppyrat-new-tool-ransomware-attacks

## 3. 国家支援型攻撃

* アジアで活動レベルが高いアクターの一覧（2026年上半期）。
  + URL: https://cyble.com/blog/most-active-threat-actors-h1-2026/
* 北朝鮮。北朝鮮労働者と疑われる人物に関する考察。注意すべき危険信号として、PiKVM および Guermok デバイス（特に両方が同一ユーザーアカウントで使用されている場合）が挙げられている。Defender は device_description に PiKVM または Guermok が含まれている場合に Windows セキュリティイベント ID 6416 で警告を発し、レジストリパス `HKLM\SYSTEM\CurrentControlSet\Enum\USB` の FriendlyName 値（PiKVM Composite Device、Guermok USB3 Video など）を調査できる。また、VDO.Ninja、タブ録画用のChromeプラグイン、ファイル送信用のToffeeshare など、画面・音声・動画のリダイレクトや録画、マイクテスト、翻訳、ファイル共有に関連するウェブサービスとブラウザ拡張機能の利用も確認されている。
  + URL: https://www.huntress.com/blog/huntress-dprk-remote-worker-investigation
* ロシア。正規の認証フローを悪用して、ヨーロッパ全域の学術機関、航空宇宙・防衛機関、政府機関、シンクタンク、および米国の学術機関やシンクタンクで働く個人を標的とする3つの脅威クラスターをGTIGが追跡。攻撃者はターゲットにアカウントへ特定のアプリパスワードを設定するよう説得し、そのパスワードを使用して2要素認証を必要とせずにアカウントへアクセスする。UNC7005はMicrosoftアカウントとWhatsAppアカウントの両方を対象としたデバイスコードフィッシング攻撃も行っている。手口は、標的の分野に関連する著名な組織の人物との通話への招待、最近では外交イベントや会議への招待など。
  + URL: https://cloud.google.com/blog/topics/threat-intelligence/distinct-clusters-target-individuals-of-interest-to-russia/

## 4. 一般社員向け

* AIを利用した役員なりすましや請求書詐欺から組織を守る。攻撃者は不審なメールを正規のメール通知に見せかけるため、経営陣メンバーからの内部送信メールを偽装する手法を用いている。AIの導入により、キャンペーンテンプレートを改善し受信者に合わせたメールを作成できるようになった。さらに1通のメール内で複数の手法を組み合わせ、全体的なストーリーをより巧妙に作り上げている。
  + URL: https://www.microsoft.com/en-us/security/blog/2026/09/10/protecting-organizations-ai-assisted-executive-impersonation-invoice-fraud/
* ClickFixがブラウザに進出：GoogleがホストするC2による仮想通貨窃盗。Google Visualization APIをC2に悪用し、公開されているGoogleスプレッドシートから難読化されたJavaScriptを取得して被害者のブラウザセッションに挿入するキャンペーン（Cisco Talos）。
  + URL: https://blog.talosintelligence.com/clickfix-moves-into-the-browser/
* ITサポートになりすます：脅威アクターがリモートセッションを企業全体へのアクセスに変える方法。Microsoft Teams の外部コラボレーションを悪用して IT サポートになりすまし、リモートアクセスを取得し、Node.js ベースのインプラントを展開する、人間が操作する侵入キャンペーン。
  + URL: https://www.microsoft.com/en-us/security/blog/2026/09/02/impersonating-it-support-threat-actors-turn-remote-session-into-enterprise-wide-access/
* TerminalFixキャンペーンは、多段階侵入を通じて逆トンネルを展開する。ClickFixの亜種で、侵害されたWebサイトを使用して偽のCloudflare CAPTCHA検証オーバーレイを表示し、ユーザーを騙して悪意のあるPowerShellコマンドをコピーして実行させる。従来のClickFixが「ファイル名を指定して実行」ダイアログに誘導するのに対し、TerminalFixはWindowsターミナルまたはPowerShellに誘導するため、複雑な複数行のスクリプトが正常に実行される可能性が高くなる。
  + URL: https://www.microsoft.com/en-us/security/blog/2026/08/28/terminalfix-campaign-deploys-reverse-tunnel-through-multistage-intrusion/

## 5. 開発者向け

* PhantomRaven：バグ報奨金獲得のために開発された、LLM生成型の情報窃盗マルウェア。バグバウンティハンターとして活動する金銭目的の脅威アクターが、JavaScriptベースの情報窃盗マルウェアを開発し npm を通じて配布していた。冗長なコメント、プレースホルダーコード、統計的手法に基づき、LLM生成であると高い確信度で評価されている。
  + URL: https://www.crowdstrike.com/en-us/blog/phantomraven-llm-generated-information-stealer-for-bug-bounty-hunting/

## 6. 業界関連情報

* 国際流星機構（IMO）が、サイバー攻撃によりウェブサイトが「致命的な打撃」を受けたと発表。老朽化したインフラに深刻な打撃を与える攻撃を受けサイトの大部分がオフラインになり、数週間の部分的なダウンタイムが見込まれるとしている。
  + URL: https://therecord.media/international-meteor-organization-cyberattack
* MITREの評価制度変更に伴い、大手サイバーセキュリティベンダー各社が英国の新たなテストプログラムに注目。SE Labs が購入者がベンダーを評価するためのテストプログラム「PIVOT」を9月15日に発表。Broadcom、CrowdStrike、Fortinet、Palo Alto Networks、Sophos などが参加する6か月間のプログラムで、世界で最も危険なハッキンググループや攻撃手法にどれだけ効果的に対抗できるかを評価する。
  + URL: https://selabs.uk/pivot/

## 7. 権威ドキュメント

* サイバーデコイを使用して探知と対応を強化する。CISAが、サイバーセキュリティ成熟度の異なる防御チームがデコイ戦略を計画・実装するのに役立つガイダンスを作成。多くの組織は、正規の認証情報、ネイティブツール、Living Off the Land（LOTL）技術を使用する攻撃者の検出に苦労している。サイバーデコイは正規のシステム、アカウント、データのように見える資産で、注意をそらすように設計されている。
  + URL: https://www.cisa.gov/resources-tools/resources/using-cyber-decoys-strengthen-detection-and-response
* ポスト量子時代への備え：行動への呼びかけ。CISAとG7サイバーセキュリティワーキンググループが、新たな量子コンピューティングの脅威から機密データ、認証システム、重要資産を保護するため、ポスト量子暗号（PQC）への移行を早急に開始する必要があることを強調。移行を成功させるための5つの優先事項を概説している。
  + URL: https://www.cisa.gov/resources-tools/resources/preparing-post-quantum-era-call-action

## 8. OTセキュリティ

* 産業インフラを脅かすもの：フロンティアAIが変えるリスクの構図。APTグループが、将来の戦略的な利用に向けて持続的なアクセスを確保するため、OT環境の構成を積極的に調べているとのレポート。
  + URL: https://www.trendaisecurity.com/ja/resources-insights/deep-research/critical-infrastructure-under-threat-how-frontier-ai-changes-the-risk-equation
* 産業インフラを標的とする犯罪経済の全体像。産業・エネルギー・製造（IE&M）分野のアンダーグラウンドは将来のリスクではなく、今まさに稼働している経済である。アクセスブローカーは、窃取された認証情報や銀行データの取引に使われるのと同じフォーラム上で、同じエスクローと評価の仕組みを使い、工場、公益事業、エネルギー企業への足がかりを販売している。BreachForumsでは、タイの製造業者の生産システムが25米ドル、ドイツの再生可能エネルギー企業の内部データベースが12 BTC（約74万8,000米ドル）で出品されている。アクセスブローカー市場の中心に位置するのは製造業で、ロシア語圏および英語圏のフォーラムの販売者はVPNやRDP経由のアクセスを出品している。
  + URL: https://www.trendaisecurity.com/ja/resources-insights/deep-research/mapping-the-criminal-economy-targeting-critical-infrastructure
