---
title: 高度な文書処理技術と組み合わせた、SAP Intelligent RPA にABBYYを統合する方法 | ABBYYの技術解説
date: 2024-09-30T02:20:07.647Z
updated: 2024-10-03T09:34:03.203Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1884017/19272" target="_top" id="1884017">
  <img src="//a.impactradius-go.com/display-ad/19272-1884017" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884017/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **インテリジェントな文書処理のリーダーであるABBYY**

ABBYYのインテリジェント文書処理プラットフォームは、最近、Everestグループの [Intelligent Document Processing (IDP) Peak Matrix Assessment 2020](https://www.abbyy.com/solutions/content-intelligence/everest-group-intelligent-document-processing-products-peak-matrix/?itm%5Fsource=jpblog)にてリーダーとして選ばれました。ABBYYは、ビジョンと機能の軸で最高の地位を獲得しました。この軸は、特に、会社のビジョンと戦略、製品の機能、技術、および商用モデルの将来性と柔軟性を評価するものです。

ABBYYのインテリジェント文書処理プラットフォームとSAP Intelligent RPAを組み合わせると、ABBYYのコンテンツインテリジェンステクノロジーとソリューションは、コンテンツ中心のプロセスの自動化を支援するために必要なコグニティブスキルを提供します。 コンテンツインテリジェンスは、高度なビジネス上の意思決定に必要なスキルと理解を新しいデジタルワーカーに提供することで、企業の働き方を変え始めており、今後の主流になっていくでしょう。

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134499/19576" target="_top" id="2134499">
  <img src="//a.impactradius-go.com/display-ad/19576-2134499" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134499/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **次のステップとして**

もし、既にSAPのお客様であり、SAP Intelligence RPAソリューションを使用している、または評価に興味がある場合は、SAPインテリジェントRPAとABBYY FlexiCaptureを組み合わせた製品の詳細を学ぶことができます。

SAPとABBYYチームによって6/3に実施されたウェビナ [webinar（英語版）](https://tools.techidaily.com/abbyy/products/)が公開されております。

また、SAPコミュニティに参加して、最新の技術ブログ投稿をご覧頂くことでより詳細を知ることもできます – [How to Combine SAP Intelligent RPA with ABBYY FlexiCapture（英語版）](https://blogs.sap.com/2020/05/06/how-to-combine-sap-intelligent-rpa-with-abbyy-flexicapture/)。SAP Intelligent RPAおよびABBYY FlexiCaptureのライセンスを既にお持ちの場合は、SAP Intelligent RPAストアから [コネクタをダウンロード](https://store.irpa.cfapps.eu10.hana.ondemand.com/#/package/bf4a7007-4034-42f3-bcbf-2f6368603672) できます。

ABBYY FlexiCaptureについての概要、デモの依頼、お問い合わせは[こちら](https://tools.techidaily.com/abbyy/products/)から承ります。

[OCR（文字認識）](https://tools.techidaily.com/abbyy/products/) [コンテンツの理解](https://tools.techidaily.com/abbyy/products/) [AI OCR](https://tools.techidaily.com/abbyy/products/) 

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-knowledge.techidaily.com/new-snapchat-like-stories-adding-movement-to-instagram-texts/"><u>[New] Snapchat-Like Stories Adding Movement to Instagram Texts</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-elevate-your-intellect-with-top-11-general-knowledge-quiz-networks/"><u>[Updated] 2024 Approved Elevate Your Intellect with Top 11 General Knowledge Quiz Networks</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-honor-90-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Honor 90 | Dr.fone</u></a></li>
<li><a href="https://solve-popular.techidaily.com/emotional-intelligence/"><u>Emotional Intelligence</u></a></li>
<li><a href="https://solve-popular.techidaily.com/enhance-your-data-capture-efficiency-transitioning-to-the-advanced-abbyy-flexicapture-cloud-solution/"><u>Enhance Your Data Capture Efficiency: Transitioning to the Advanced ABBYY FlexiCapture Cloud Solution</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-integrate-a-computer-printer-with-windows-11-a-comprehensive-guide/"><u>How to Integrate a Computer Printer with Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://solve-popular.techidaily.com/how-to-triumph-in-mobile-user-onboarding-your-essential-e-book-resource/"><u>How to Triumph in Mobile User Onboarding - Your Essential E-Book Resource</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-free-up-your-time-with-these-5-chrome-plugins-for-fb-video-downloads/"><u>In 2024, Free Up Your Time with These 5 Chrome Plugins for FB Video Downloads</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-14-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 14 Passcode without iTunes without Knowing Passcode?</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/is-8k-resolution-a-future-possibility-for-playstation-5-and-xbox-series-x-consoles/"><u>Is 8K Resolution a Future Possibility for PlayStation 5 and Xbox Series X Consoles?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1726220879793-2024/"><u>𝗠𝗮'𝘃'𝗶𝘁𝗵-2024: 𝗕𝗲𝗼𝗿𝗸𝗮𝗹𝗹𝗹 𝗧𝗵𝗮'𝘁 𝗶𝘀𝗰𝗲𝗻𝘂𝘇𝗶𝗱𝗮𝘁 🚹🚺 | 𝗡𝗼𝘃𝗼𝘀𝘄𝗶𰨒: 𝗦𝗸𝗶𝘀 𝗮𝗹𝗱'𝘁𝘂𝗿𝗻𝗲𝗻𝘀</u></a></li>
<li><a href="https://solve-popular.techidaily.com/neoml-discover-the-power-of-abbyys-enrichit-and-open-source-software-capabilities/"><u>NeoML: Discover the Power of ABBYY's Enrichit and Open-Source Software Capabilities</u></a></li>
<li><a href="https://solve-popular.techidaily.com/optimized-with-advanced-traffic-analysis-from-cookiebot/"><u>Optimized with Advanced Traffic Analysis From Cookiebot</u></a></li>
<li><a href="https://solve-popular.techidaily.com/streamline-e-commerce-success-the-power-of-advanced-cookiebot-solutions/"><u>Streamline E-Commerce Success: The Power of Advanced Cookiebot Solutions</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/troubleshooting-guide-how-to-get-windows-10-to-detect-your-usb-devices/"><u>Troubleshooting Guide: How to Get Windows 10 to Detect Your USB Devices</u></a></li>
<li><a href="https://solve-popular.techidaily.com/unveiling-process-intelligence-insights-into-advanced-data-analytics/"><u>Unveiling Process Intelligence: Insights Into Advanced Data Analytics</u></a></li>
</ul></div>

