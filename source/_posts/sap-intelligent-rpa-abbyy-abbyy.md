---
title: 高度な文書処理技術と組み合わせた、SAP Intelligent RPA にABBYYを統合する方法 | ABBYYの技術解説
date: 2024-10-10T18:57:59.265Z
updated: 2024-10-15T00:02:28.028Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144275/7443" target="_top" id="2144275">
  <img src="//a.impactradius-go.com/display-ad/7443-2144275" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144275/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **インテリジェントな文書処理のリーダーであるABBYY**

ABBYYのインテリジェント文書処理プラットフォームは、最近、Everestグループの [Intelligent Document Processing (IDP) Peak Matrix Assessment 2020](https://www.abbyy.com/solutions/content-intelligence/everest-group-intelligent-document-processing-products-peak-matrix/?itm%5Fsource=jpblog)にてリーダーとして選ばれました。ABBYYは、ビジョンと機能の軸で最高の地位を獲得しました。この軸は、特に、会社のビジョンと戦略、製品の機能、技術、および商用モデルの将来性と柔軟性を評価するものです。

ABBYYのインテリジェント文書処理プラットフォームとSAP Intelligent RPAを組み合わせると、ABBYYのコンテンツインテリジェンステクノロジーとソリューションは、コンテンツ中心のプロセスの自動化を支援するために必要なコグニティブスキルを提供します。 コンテンツインテリジェンスは、高度なビジネス上の意思決定に必要なスキルと理解を新しいデジタルワーカーに提供することで、企業の働き方を変え始めており、今後の主流になっていくでしょう。

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **次のステップとして**

もし、既にSAPのお客様であり、SAP Intelligence RPAソリューションを使用している、または評価に興味がある場合は、SAPインテリジェントRPAとABBYY FlexiCaptureを組み合わせた製品の詳細を学ぶことができます。

SAPとABBYYチームによって6/3に実施されたウェビナ [webinar（英語版）](https://tools.techidaily.com/abbyy/products/)が公開されております。

また、SAPコミュニティに参加して、最新の技術ブログ投稿をご覧頂くことでより詳細を知ることもできます – [How to Combine SAP Intelligent RPA with ABBYY FlexiCapture（英語版）](https://blogs.sap.com/2020/05/06/how-to-combine-sap-intelligent-rpa-with-abbyy-flexicapture/)。SAP Intelligent RPAおよびABBYY FlexiCaptureのライセンスを既にお持ちの場合は、SAP Intelligent RPAストアから [コネクタをダウンロード](https://store.irpa.cfapps.eu10.hana.ondemand.com/#/package/bf4a7007-4034-42f3-bcbf-2f6368603672) できます。

ABBYY FlexiCaptureについての概要、デモの依頼、お問い合わせは[こちら](https://tools.techidaily.com/abbyy/products/)から承ります。

[OCR（文字認識）](https://tools.techidaily.com/abbyy/products/) [コンテンツの理解](https://tools.techidaily.com/abbyy/products/) [AI OCR](https://tools.techidaily.com/abbyy/products/) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-football-video-analysis-top-youtube-infographics/"><u>[Updated] 2024 Approved Football Video Analysis Top YouTube Infographics</u></a></li>
<li><a href="https://extra-resources.techidaily.com/brilliant-backdrops-using-light-to-enchant-audiences/"><u>Brilliant Backdrops Using Light to Enchant Audiences</u></a></li>
<li><a href="https://solve-popular.techidaily.com/cookiebot-unleashing-advanced-tracking-solutions-for-your-websites-success/"><u>Cookiebot: Unleashing Advanced Tracking Solutions for Your Website's Success</u></a></li>
<li><a href="https://solve-popular.techidaily.com/data-driven-personalization-through-smart-analytics-solutions/"><u>Data-Driven Personalization Through Smart Analytics Solutions</u></a></li>
<li><a href="https://solve-popular.techidaily.com/demystifying-rpa-insights-from-the-abbyy-experts-guide/"><u>Demystifying RPA: Insights From the ABBYY Expert's Guide</u></a></li>
<li><a href="https://solve-popular.techidaily.com/desamorcez-votre-gestion-des-credits-immobiliers-grace-a-levolutif-et-performant-service-de-dematerialisation-la-caisse-depargne-bretagne-pays-de-loire/"><u>Désamorcez Votre Gestion Des Crédits Immobiliers Grâce À L'évolutif Et Performant Service De Dématérialisation La Caisse D’Epargne Bretagne Pays De Loire</u></a></li>
<li><a href="https://solve-popular.techidaily.com/elevate-your-site-performance-using-cookiebot-technology/"><u>Elevate Your Site Performance Using Cookiebot Technology</u></a></li>
<li><a href="https://solve-popular.techidaily.com/empowering-website-insights-with-cookiebot-advanced-tracking-solutions-for-improved-seo/"><u>Empowering Website Insights with Cookiebot: Advanced Tracking Solutions for Improved SEO</u></a></li>
<li><a href="https://solve-popular.techidaily.com/enhance-site-performance-with-our-cookiebot-integrated-tools/"><u>Enhance Site Performance with Our Cookiebot Integrated Tools</u></a></li>
<li><a href="https://solve-popular.techidaily.com/enhance-website-traffic-analysis-with-our-advanced-cookiebot-technology-solutions/"><u>Enhance Website Traffic Analysis with Our Advanced Cookiebot Technology Solutions</u></a></li>
<li><a href="https://solve-popular.techidaily.com/enhanced-by-cookiebot-solutions/"><u>Enhanced by Cookiebot Solutions</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-drone-selections-for-young-pilots-and-rookie-flyers/"><u>In 2024, Best Drone Selections for Young Pilots and Rookie Flyers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-nighttime-tales-on-screen-insights-into-storytelling-videos-for-kids/"><u>In 2024, Nighttime Tales on Screen Insights Into Storytelling Videos for Kids</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-premier-platforms-for-live-chat-and-screen-sharing-alternatives-to-omegle/"><u>New The Premier Platforms for Live Chat and Screen Sharing Alternatives to Omegle</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/perfect-your-skills-in-designing-engaging-videotutorials-for-2024/"><u>Perfect Your Skills in Designing Engaging Videotutorials for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/tiktoks-top-15-books-for-page-turning-pleasure/"><u>TikTok’s Top 15 Books for Page-Turning Pleasure</u></a></li>
<li><a href="https://some-guidance.techidaily.com/turning-tails-into-heads-android-video-editing-for-2024/"><u>Turning Tails Into Heads Android Video Editing for 2024</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/unlocking-the-secrets-of-high-efficiency-video-coding-hevch265-enable-smooth-x265-media-playback-on-windows-10-systems/"><u>Unlocking the Secrets of High-Efficiency Video Coding (HEVC/H.265): Enable Smooth X265 Media Playback on Windows 10 Systems</u></a></li>
</ul></div>

