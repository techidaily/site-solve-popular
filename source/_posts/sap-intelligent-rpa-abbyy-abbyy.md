---
title: 高度な文書処理技術と組み合わせた、SAP Intelligent RPA にABBYYを統合する方法 | ABBYYの技術解説
date: 2024-08-25T21:33:09.276Z
updated: 2024-08-26T21:33:09.276Z
categories:
  - abbyy
thumbnail: https://thmb.techidaily.com/9d3857853f9f78dd8e108c028d0a318d22b529786459d21ef8b234658302fc85.jpg
---

## 高度な文書処理技術と組み合わせた、SAP Intelligent RPA にABBYYを統合する方法 | ABBYYの技術解説

[Back to ABBYY Blog](https://tools.techidaily.com/abbyy/products/)

# SAP Intelligent RPAでのABBYYインテリジェント文書処理との統合

7月17日, 2020

![SAP Intelligent RPA and ABBYY | ABBYY Blog Post](https://static3.abbyy.com/abbyycommedia/25741/sap-intelligence-rpa-and-abbyy-featured-image.jpg) 

今日の企業はデジタル変革の過程で急速に進んでいますが、請求書、注文、その他の非構造化コンテンツなどのビジネスドキュメント内の重要な情報を抽出するという大きな課題があります。これらのさまざまなビジネスドキュメントのコンテンツの多くは、SAPや他のエンタープライズシステムなどのシステムに送られます。

事実として: “Forbes Global 2000企業の92％がSAPを採用しています” [SAP Corporate Fact Sheet](https://www.sap.com/documents/2017/04/4666ecdd-b67c-0010-82c7-eda71af511fa.html)

デジタルトランスフォーメーション(DX)を率先して行おうとすると、全ての中心的な部分には、人間が繰り返すあらゆる定型のタスクを自動化するロボットプロセス自動化（RPA）が含まれます。これには、SAPなどのシステムと対話してデータを入力し、情報を検証することも含まれます。[SAP Intelligent Robotic Process Automation（英語版）](https://www.sap.com/products/robotic-process-automation.html) は、財務、販売、配送、製造、調達、調達、およびプロフェッショナルサービスにおけるこれらのタイプの手動タスクの自動化を支援し、従業員の反復的なタスクを自動化することで、会社の運用効率を改善し、コンプライアンスを向上させ、リスクを低減します。

### **文書、電子メール、および非構造化データを処理するためのSAPロボットのスキルアップ**

企業がここ1,2年で学んだことは、RPAがドキュメントや電子メール、およびその他の非構造化データを含むプロセスの自動化に支援を必要としていることです。SAPロボットにインテリジェンスを追加するとお考えください。ロボットはビジョン、理解、ロボットプロセスへの洞察を適用する必要なデジタルスキルをあらかじめ備えており、それ故に、請求書、注文書、BOL (Bill of Lading)などのドキュメントを処理することが可能となります。そのデジタルスキル（コグニティブスキル）は、SAPロボットによって呼び出すことができるトレーニング済みソフトウェアです。そして、ドキュメントを請求書として識別し、ヘッダー、フッター、およびラインアイテムの詳細を特定して抽出し、SAPロボットにデータを返す前にデータを構造化および検証します。

次の図は、SAP Intelligent RPAとABBYYの間の一般的なプロセスフローを示しています。SAPロボットでメール、電子文書のようなインプットを集め、ABBYYの技術で非定型文書からコンテンツを抽出し、レビューを行い、SAPロボットがそのデータをS/4 HANAのようなシステムに届けるようなフローです。

![SAP ABBYY Process flow](https://static1.abbyy.com/abbyycommedia/25745/sap-abbyy-process-flow-1024x576.png)

よくある誤解は、単なるOCRと思われることです。これでは、実際に何が起こっているかについてのマークを完全に逃してしまいます。別の先入観は、さまざまなベンダーの請求書のように、ドキュメントのバリエーションごとにテンプレートが必要であるというものです。 我々はそれが偽りであり、より良いソリューションを提供するために、無残にプロジェクトを失敗させないためにここにいます。

文書が処理されるときに何が起こっているかを考える、より良い方法は、ビジョン、理解、洞察という言葉を浮かべ、幅広く、どんな自動化が可能かを検討することです。

**ビジョン/Vision** – 文書内のテキストをデジタル化し、画像処理、解析を使って画像を読み取れるよう最適化し、単語、フレーズ、文、および段落をセグメント化することにより文書の構造的構成を分析する機能。

**理解/Understanding** – 文書タイプを分類してデータを抽出できるようにプロジェクトを学習させるために機械学習を採用。このソフトウェアはドキュメントの初期トレーニングセットから学習を開始し、人が検証する際に修正統計が収集されるにつれて、トレーニングセットが拡張され、学習は時間とともに改善されます。 請求書の場合、ABBYYは、企業が簡単に開始できるように事前トレーニング済みモデルを提供します。

**洞察/Insight** – 購入者と販売者のようなデータ間の関係の確立など、人間の判断を模倣するためにテキスト間の構造と意味を活用。

**_以下は、グローバル大手ITマーケティング調査会社、Everestグループでサービス最適化技術部門のディレクターを務める Anil Vijayanの注目すべきコメントです。_**

「RPAと組み合わせて使用されるAIテクノロジ - 機械学習（ML）、自然言語処理（NLP）、コンピュータービジョンを含む - は、スタンドアロンRPAによって達成可能なものよりもはるかに大きなビジネス上の利点を引き出す可能性があります。 この組み合わせは、プロセスの業務処理的な部分だけでなく、判断力が必要とされる部分も自動化するのに役立ちます。」

### **インテリジェントな文書処理のリーダーであるABBYY**

ABBYYのインテリジェント文書処理プラットフォームは、最近、Everestグループの [Intelligent Document Processing (IDP) Peak Matrix Assessment 2020](https://www.abbyy.com/solutions/content-intelligence/everest-group-intelligent-document-processing-products-peak-matrix/?itm%5Fsource=jpblog)にてリーダーとして選ばれました。ABBYYは、ビジョンと機能の軸で最高の地位を獲得しました。この軸は、特に、会社のビジョンと戦略、製品の機能、技術、および商用モデルの将来性と柔軟性を評価するものです。

ABBYYのインテリジェント文書処理プラットフォームとSAP Intelligent RPAを組み合わせると、ABBYYのコンテンツインテリジェンステクノロジーとソリューションは、コンテンツ中心のプロセスの自動化を支援するために必要なコグニティブスキルを提供します。 コンテンツインテリジェンスは、高度なビジネス上の意思決定に必要なスキルと理解を新しいデジタルワーカーに提供することで、企業の働き方を変え始めており、今後の主流になっていくでしょう。

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
### **次のステップとして**

もし、既にSAPのお客様であり、SAP Intelligence RPAソリューションを使用している、または評価に興味がある場合は、SAPインテリジェントRPAとABBYY FlexiCaptureを組み合わせた製品の詳細を学ぶことができます。

SAPとABBYYチームによって6/3に実施されたウェビナ [webinar（英語版）](https://tools.techidaily.com/abbyy/products/)が公開されております。

また、SAPコミュニティに参加して、最新の技術ブログ投稿をご覧頂くことでより詳細を知ることもできます – [How to Combine SAP Intelligent RPA with ABBYY FlexiCapture（英語版）](https://blogs.sap.com/2020/05/06/how-to-combine-sap-intelligent-rpa-with-abbyy-flexicapture/)。SAP Intelligent RPAおよびABBYY FlexiCaptureのライセンスを既にお持ちの場合は、SAP Intelligent RPAストアから [コネクタをダウンロード](https://store.irpa.cfapps.eu10.hana.ondemand.com/#/package/bf4a7007-4034-42f3-bcbf-2f6368603672) できます。

ABBYY FlexiCaptureについての概要、デモの依頼、お問い合わせは[こちら](https://tools.techidaily.com/abbyy/products/)から承ります。

[OCR（文字認識）](https://tools.techidaily.com/abbyy/products/) [コンテンツの理解](https://tools.techidaily.com/abbyy/products/) [AI OCR](https://tools.techidaily.com/abbyy/products/) 

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### いいね！、シェア、再投稿

シェア 

#### ブログのアップデートを購読

名\*

電子メール\*

国\*

国アフガニスタンオーランド諸島アルバニアアルジェリアアメリカ領サモアアンドラアンゴラアンギラ南極アンティグア・バーブーダアルゼンチンアルメニアアルバオーストラリアオーストリアアゼルバイジャンバハマバーレーンバングラデシュバルバドスベルギーベリーズベナンバミューダブータンボリビアカリブ海オランダボスニア・ヘルツェゴビナボツワナブーベ島ブラジルイギリス領インド洋地域イギリス領ヴァージン諸島ブルネイ・ダルサラームブルガリアブルキナファソブルンジカンボジアカメルーンカナダカーボベルデケイマン諸島中央アフリカ共和国チャドチリ中華人民共和国クリスマス島ココス（キーリング）諸島コロンビアコモロコンゴ共和国コンゴ民主共和国クック諸島コスタリカクロアチアキュラソーキプロスチェココートジボワールデンマークジブチドミニカ国ドミニカ共和国エクアドルエジプトエルサルバドル赤道ギニアエリトリアエストニアエチオピアフォークランド（マルビナス）諸島フェロー諸島フィジーフィンランドフランスフランス領ギアナフランス領ポリネシアフランス領南方・南極地域ガボンガンビアジョージアドイツガーナジブラルタルギリシャグリーンランドグレナダグアドループグアムグアテマラガーンジーギニアギニアビサウガイアナハイチハード島とマクドナルド諸島バチカンホンジュラス香港ハンガリーアイスランドインドインドネシアイラクアイルランドマン島イスラエルITジャマイカ日本ジャージーヨルダンカザフスタンケニアキリバス大韓民国クウェートKyrgyzstanラオスラトビアレバノンレソトリベリアリビアリヒテンシュタインリトアニアルクセンブルクマカオマケドニアマダガスカルマラウイマレーシアモルディブマリマルタマーシャル諸島マルティニークモーリタニアモーリシャスマヨットメキシコミクロネシアモルドバモナコモンゴルモンテネグロモントセラトモロッコモザンビークミャンマーナミビアナウルネパールオランダオランダ領アンティル諸島ニューカレドニアニュージーランドニカラグアニジェールナイジェリアニウエノーフォーク島北マリアナ諸島ノルウェーオマーンパキスタンパラオパレスチナパナマパプアニューギニアパラグアイペルーフィリピンピトケアンポーランドポルトガルプエルトリコカタールルーマニアルワンダレユニオンセントヘレナセントクリストファー・ネイビスセントルシアサンピエール島・ミクロン島セントビンセントおよびグレナディーン諸島サン・バルテルミーサン・マルタン（フランス領）サモアサンマリノサントメ・プリンシペサウジアラビアセネガルセルビアセーシェルシエラレオネシンガポールシント・マールテン（オランダ領）スロバキアスロベニアソロモン諸島南アフリカサウスジョージア・サウスサンドウィッチ諸島南スーダンスペインスリランカスリナムスヴァールバル諸島およびヤンマイエン島スワジランドスウェーデンスイス台湾タジキスタンタンザニアタイ東ティモールトーゴトケラウトンガトリニダード・トバゴチュニジアトルコタークス・カイコス諸島ツバルウガンダウクライナアラブ首長国連邦イギリスアメリカ合衆国ウルグアイ合衆国領有小離島ウズベキスタンバヌアツベネズエラベトナムアメリカ領ヴァージン諸島ウォリス・フツナ西サハラザンビアジンバブエ

* [プライバシーポリシー](https://tools.techidaily.com/abbyy/products/)と[クッキーポリシー](https://tools.techidaily.com/abbyy/products/)を読み、同意します。

* ABBYY Solutions Ltd.製品と技術に関連するニュース、イベントとウェビナーへのご案内、ABBYY Solutions Ltd.製品とサービスに関連するホワイトペーパーやコンテンツの情報など、ABBYY Solutions Ltd.からのメールを受け取ることに同意します。  
    
私は、ABBYY Solutions Ltd.から送信されるEメールに記載された配信停止リンクをクリックするか、または [ABBYYデータ主体アクセス権利フォームを](https://tools.techidaily.com/abbyy/products/) 介していつでも同意を取り消すことができることを理解しています。

Referrer

姓

Query string

Product Interest Temp

UTM Campaign Name

UTM Medium

UTM Source

ITM Source

GA Client ID

UTM Content

GDPR Consent Note

Captcha Score

Page URL

Connect with us

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-the-ultimate-screen-recorder-a-2023-evaluation-of-camstudio/"><u>[Updated] 2024 Approved  The Ultimate Screen Recorder  A 2023 Evaluation of CamStudio</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-unveiling-the-best-practices-for-skype-in-obs/"><u>[Updated] 2024 Approved  Unveiling the Best Practices for Skype in OBS</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-downloading-the-latest-tiktok-features-on-your-macbook-for-2024/"><u>[Updated] Downloading the Latest TikTok Features on Your MacBook for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-downloading-your-youtube-watch-lists-step-by-step/"><u>[Updated] Downloading Your YouTube Watch Lists  Step by Step</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-proven-methods-for-sensational-instagram-puzzle-creation/"><u>[Updated] In 2024, Proven Methods for Sensational Instagram Puzzle Creation</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-zip-to-sub-transforming-compressed-texts-to-srt-format/"><u>2024 Approved  From Zip to Sub  Transforming Compressed Texts to SRT Format</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-mastering-game-recordings-on-fortnite/"><u>2024 Approved  Mastering Game Recordings on Fortnite</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-unlock-professional-subtitle-transformation-at-zero-price/"><u>2024 Approved  Unlock Professional Subtitle Transformation at Zero Price</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://solve-popular.techidaily.com/ai-ocr-rpa49/"><u>伝票管理にAI OCRの活用がもたらす変革: RPA併用で年間4.9万時間減少達成</u></a></li>
<li><a href="https://solve-popular.techidaily.com/abbyys-advanced-language-translator-powered-by-ntt-docomo-features-ocr-for-multilingual-support/"><u>ABBYY's Advanced Language Translator - Powered by NTT DOCOMO, Features OCR for Multilingual Support</u></a></li>
<li><a href="https://solve-popular.techidaily.com/abbyy-sdgs/"><u>ABBYY社における世界的な持続可能性への道: SDGs達成へ向けた取り組み</u></a></li>
<li><a href="https://tools.techidaily.com/aiseesoft/video-editor/"><u>Aiseesoft Video Editor</u></a></li>
<li><a href="https://solve-popular.techidaily.com/automatisierte-rechnungsbearbeitung-fur-energielieferanten-mit-branchenrelevanz-empfehlungen-von-abbyy/"><u>Automatisierte Rechnungsbearbeitung Für Energielieferanten Mit Branchenrelevanz – Empfehlungen Von ABBYY</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/become-a-youtube-star-top-fb-songs-and-vids-unlocked-for-2024/"><u>Become a YouTube Star - Top FB Songs & Vids Unlocked for 2024</u></a></li>
<li><a href="https://solve-popular.techidaily.com/boost-site-traffic-with-cookiebot-integration-strategies/"><u>Boost Site Traffic with Cookiebot Integration Strategies</u></a></li>
<li><a href="https://solve-popular.techidaily.com/boost-web-visibility-instantly-using-the-powerful-cookiebot-seo-tech/"><u>Boost Web Visibility Instantly Using the Powerful Cookiebot SEO Tech</u></a></li>
<li><a href="https://solve-popular.techidaily.com/boosting-web-insights-with-cookiebot-technology/"><u>Boosting Web Insights with Cookiebot Technology</u></a></li>
<li><a href="https://solve-popular.techidaily.com/carlsberg-accelere-son-debut-en-mer-avec-la-technologie-abbyy-un-nouveau-partenariat-industriel/"><u>Carlsberg Accélère Son Début en Mer Avec La Technologie ABBYY : Un Nouveau Partenariat Industriel</u></a></li>
<li><a href="https://solve-popular.techidaily.com/cookiebot-driven-customization-enhancing-user-experience-with-personalized-content/"><u>Cookiebot-Driven Customization: Enhancing User Experience with Personalized Content</u></a></li>
<li><a href="https://solve-popular.techidaily.com/cookiebot-driven-performance-enhancing-your-websites-user-engagement/"><u>Cookiebot-Driven Performance: Enhancing Your Website's User Engagement</u></a></li>
<li><a href="https://solve-popular.techidaily.com/cookiebot-enabled-sites-enhanced-personalization-and-engagement/"><u>Cookiebot-Enabled Sites: Enhanced Personalization & Engagement</u></a></li>
<li><a href="https://solve-popular.techidaily.com/cookiebot-enhanced-optimizing-your-site-with-advanced-analytics/"><u>Cookiebot-Enhanced: Optimizing Your Site with Advanced Analytics</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/discover-the-premier-8-free-roku-channels-of-2024/"><u>Discover the Premier 8 Free Roku Channels of 2024</u></a></li>
<li><a href="https://solve-popular.techidaily.com/driven-by-cookiebot-enhancing-online-personalization/"><u>Driven by Cookiebot: Enhancing Online Personalization</u></a></li>
<li><a href="https://solve-popular.techidaily.com/driven-with-innovative-cookiebot-technology/"><u>Driven with Innovative Cookiebot Technology</u></a></li>
<li><a href="https://solve-popular.techidaily.com/elevate-online-experience-with-cookiebot-power-solutions-for-superior-user-targeting-and-retention/"><u>Elevate Online Experience with Cookiebot Power Solutions for Superior User Targeting and Retention</u></a></li>
<li><a href="https://solve-popular.techidaily.com/embracing-innovative-mobility-learn-with-us-on-the-abbyy-blog/"><u>Embracing Innovative Mobility - Learn with Us on the ABBYY Blog</u></a></li>
<li><a href="https://solve-popular.techidaily.com/enhance-online-performance-using-the-powerful-features-of-cookiebot-technology/"><u>Enhance Online Performance Using the Powerful Features of Cookiebot Technology</u></a></li>
<li><a href="https://solve-popular.techidaily.com/enhanced-with-advanced-automation-powered-by-the-cutting-edge-cookiebot-technology/"><u>Enhanced with Advanced Automation: Powered by the Cutting-Edge Cookiebot Technology</u></a></li>
<li><a href="https://solve-popular.techidaily.com/expanded-pdf-handling-in-latest-abbyys-finereader-version-14-for-improved-document-processing/"><u>Expanded PDF Handling in Latest ABBYY's FineReader Version 14 for Improved Document Processing</u></a></li>
<li><a href="https://solve-popular.techidaily.com/experience-personalized-content-with-our-cookiebot-integration/"><u>Experience Personalized Content with Our Cookiebot Integration</u></a></li>
<li><a href="https://solve-popular.techidaily.com/forbes-insight-transitioning-from-traditional-documents-to-advanced-digital-process-analytics/"><u>Forbes Insight: Transitioning From Traditional Documents to Advanced Digital Process Analytics</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-vivo-y100i-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Vivo Y100i to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://solve-popular.techidaily.com/harness-the-power-of-cookiebot-for-optimized-web-traffic-growth/"><u>Harness the Power of Cookiebot for Optimized Web Traffic Growth</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-resolve-the-issue-of-discord-not-launching-properly/"><u>How to Resolve the Issue of Discord Not Launching Properly</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-nokia-c110frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Nokia C110FRP Lock</u></a></li>
<li><a href="https://program-issues.techidaily.com/master-rocket-league-stability-proven-fixes-to-keep-it-running-smoothly-in-2s24/"><u>Master Rocket League Stability: Proven Fixes to Keep It Running Smoothly in 2S24</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-startup-obstacles-a-2022-guide-for-playing-outriders-on-windows/"><u>Overcoming Startup Obstacles: A 2022 Guide for Playing Outriders on Windows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-hashtag-combo-for-6-figure-youtube-traffic-surge-for-2024/"><u>Prime Hashtag Combo for 6-Figure Youtube Traffic Surge for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722975421411-seamlessly-update-your-ryzen-graphics-find-and-download-the-right-drivers-for-model-2600/"><u>Seamlessly Update Your Ryzen Graphics: Find & Download the Right Drivers for Model #2600.</u></a></li>
<li><a href="https://win-able.techidaily.com/solving-the-issue-why-does-my-computer-keep-getting-content-warning-errors-and-how-to-stop-them/"><u>Solving the Issue: Why Does My Computer Keep Getting 'Content Warning' Errors and How to Stop Them</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-guide-to-gestural-recognition-technologies/"><u>The Ultimate Guide to Gestural Recognition Technologies</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/vimeo-and-youtube-analyzing-their-unique-features/"><u>Vimeo and YouTube  Analyzing Their Unique Features</u></a></li>
</ul></div>
