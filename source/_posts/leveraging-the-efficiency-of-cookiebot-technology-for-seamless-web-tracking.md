---
title: Leveraging the Efficiency of Cookiebot Technology for Seamless Web Tracking
date: 2024-09-30T04:12:58.698Z
updated: 2024-10-03T00:50:13.320Z
categories:
  - abbyy
thumbnail: https://thmb.techidaily.com/8edbdeedec707f11bb72a9ed7f55e988ffc8071bad7a0eaa9fbee4357c112fe7.jpg
---

## Leveraging the Efficiency of Cookiebot Technology for Seamless Web Tracking

[Back to ABBYY Blog](https://tools.techidaily.com/abbyy/products/)

# What We Learned at JSConf Budapest 2022

###### Attila Kling

October 27, 2022

![](https://static1.abbyy.com/abbyycommedia/36301/jsconf_cover.jpg) 

This summer, ABBYY was a proud sponsor of [JSConf Budapest—](https://jsconfbp.com/)an international conference bringing together JavaScript enthusiasts from all over the world. Six people from the ABBYY Hungary team, including myself, were representing the company at the event. During the two-day conference, we got to talk to hundreds of developers from as far afield as Singapore, Israel, Serbia, the UK, and many other locations. A steady stream of visitors attended our booth where everyone could take our fun (but not so easy) quiz and win prizes, while learning about ABBYY. We also had the opportunity to listen to dozens of great speakers, and collected some interesting thoughts and insights to share in this post\*.

### **The Power of JS Generators by Anjana Vakil**

In this presentation, Anjana shared her passion about generators with the audience with so much energy that even if you didn’t know anything about generators, you were instantly hyped up!

The presentation started with a brief introduction to generators. In case your generator-related knowledge is a little bit rusty, here's a [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global%5FObjects/Generator) to refresh your memory, but I advise you to watch Anjana's presentation instead, which has it all covered.

_Iterables_

Generator functions are also iterables which means we can loop through them, and we can use, for example, the spread operator:

function\* abcs() {

 yield 'a';

 yield 'b';

 yield 'c';

\[...abcs()\]; _// \['a', 'b', 'c'\]_

In the presentation there was a neat example about a French card deck object with the special property \[Symbol.iterator\] and the presenter used the fact that generators are also iterable so that when we spread the deck object, the internal iterator of the object, which is a generator function, creates all the French deck cards. This presentation helped us to **think out-of-the-box about generators and their practical uses in our applications**.

[Here](https://youtu.be/gu3FfmgkwUc) you can watch the full presentation.

**Typed JavaScript? For Real? The “Type Annotations” Proposal and What It’s All About by Gil Tayar**

Gil presented a TC39 proposal on including types in vanilla JavaScript. The proposal currently is in the first stage, so anything can happen still, but the idea behind types in JavaScript is not uncommon—just think about TypeScript or Flow.

_But we have TypeScript!_ – you might think.

Yes, but the proposal aims to provide a **common alternative to TypeScript in which you don't necessarily have to transpile your code**.

The types would still be ignored by the runtime, similar to how TypeScript works, and the types would be applied by annotations with similar syntax to TypeScript.

Internally, we had an interesting conversation about this topic. In itself, this doesn't provide anything more than just using TypeScript. However, diversity is always welcome, and another option for typed JavaScript is, again, very good. We are very curious about how this proposal will evolve.

[Here](https://youtu.be/SdV9Xy0E4CM) you can watch the full presentation.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Communicating Intention with Functional TypeScript by Thiago Temple**

This presentation by Thiago caught our attention for several reasons:

1. a) we use TypeScript extensively here at ABBYY;
2. b) let's face it, when it comes to typing, we developers can be lazy 😊

So hearing some advice, tips and tricks is always helpful. The “gotcha” moment for us in this presentation was to **put more focus on typing, not just for the positive scenario but for (controlled) failures as well**. I'm pretty sure all of you are familiar with code (pseudo) like this:

type Order = {...}

type OrderResult = Result<ProcessedOrder>

function processOrder(order: Order): OrderResult {}

The upper code is quite standard, but what if we throw from the function, or what happens if the order is null ? Maybe the function handles the missing input, in which case it returns a different result. Thiago reminded us to handle those edge-cases as well. Here is an example from the presentation:

type Order = {...}

type OrderResult = Result<ProcessedOrder, OrderProcessingError>

function processOrder(order: Order): OrderResult {}

The speaker also talked about using union types when the input for the function is a well-defined finite set of string values. One way this helps us is to catch typo errors. Here at ABBYY we use union types all the time, so it was nice to learn a little more about them.

[Here](https://youtu.be/fhyHgkH0ZEg) you can watch the full presentation.

### **7±2 Reasons Psychology Will Help You Write Better Code by Moran Weber**

This was a really exciting talk, and I encourage all of you to watch the video and play along with the little “games”. Moran has a degree in social psychology along with a lot of experience in software development. She shared several cognitive psychology principles that help to better understand how we read and interpret code.

For example, it is common knowledge among developers to use meaningful naming of variables, functions, etc. We all know the requirements. But do we really understand why good naming yields better collaboration? While shamelessly I would reply “yes”, in reality I did not. This presentation explains and demonstrates this extremely well.

One other thing that sticks in my mind and that I have practiced with my team since the conference is that **code reviews should always be cold**. This means no design explanation and intro is needed before handing your code—just send out a pull request. Otherwise, we could fall into a selective attention trap and not stay objective while reviewing the code.

[Here](https://youtu.be/jAUcbFM0nXE) you can watch the full presentation.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Testing Web Accessibility by Adrián Bolonio**

Adrián spoke about web accessibility. At ABBYY Hungary we are working on a web application for ABBYY [Timeline](https://tools.techidaily.com/abbyy/products/)—a cloud-based process intelligence platform that helps companies improve their processes. The target audience does not include every day users rather, per se, superusers such as business analysts. We don't have to think about web accessibility (which is usually referred to as a11y), the target audience just does not require this, right? WRONG. And Adrián explains very well why my statement is so wrong.

According to the presenter, every web application should care about accessibility. It is so easy to consider a11y as something we have to think about only when the target audience includes people with disabilities. Well, what if I tell you this mindset is wrong, and we all should care about a11y regardless of the type of application we are making? Adrián showed us that not only disabled people might use our applications leveraging a11y capabilities, like screen readers or other aids, but people with temporary inconveniences may also need them. For example, a father having his kid on his lap (sounds familiar in the era of home office?) and being able to use the application with only one hand. Or a worker having some temporary eye strain, which can happen to any of us.

This talk was influential—I could even say eye-opening!—to many of us attending the conference. The presentation has given us **ideas and inspiration about the direction in which we want to develop the product we are working on**.

[Here](https://tools.techidaily.com/abbyy/products/) you can watch the full presentation.

\*_All presentations in the program were insightful, and we enjoyed each one of them. The upper excerpts reflect our team's best memories about the conference._

### **Conclusion**

For me, personally, this was the first JSConf I was able to attend here in Budapest. I felt the focus was more on the less technical aspects of web development rather than straight technical JavaScript, which was an advantage. This way topics like web accessibility and psychology could gain some love and attention. Huge thanks to the JSConf Budapest team for organizing the conference.

[Tech Talk](https://tools.techidaily.com/abbyy/products/) 

![](https://static4.abbyy.com/abbyycommedia/36306/attila-kling-88x88.png)

<!-- affiliate ads begin -->
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Attila Kling

Software Development Group Team Lead

Attila leads a software development group of ABBYY Timeline. His day-to-day job includes managing web development projects, and he has a keen interest in web-security, user-management, authentication, and authorization.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049379/7443" target="_top" id="2049379">
  <img src="//a.impactradius-go.com/display-ad/7443-2049379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Like, share or repost

Share 

#### Subscribe for blog updates

First name\*

E-mail\*

Сountry\*

СountryAfghanistanAland IslandsAlbaniaAlgeriaAmerican SamoaAndorraAngolaAnguillaAntarcticaAntigua and BarbudaArgentinaArmeniaArubaAustraliaAustriaAzerbaijanBahamasBahrainBangladeshBarbadosBelgiumBelizeBeninBermudaBhutanBoliviaBonaire, Sint Eustatius and SabaBosnia and HerzegovinaBotswanaBouvet IslandBrazilBritish Indian Ocean TerritoryBritish Virgin IslandsBrunei DarussalamBulgariaBurkina FasoBurundiCambodiaCameroonCanadaCape VerdeCayman IslandsCentral African RepublicChadChileChinaChristmas IslandCocos (Keeling) IslandsColombiaComorosCongo (Brazzaville)Congo, (Kinshasa)Cook IslandsCosta RicaCroatiaCuraçaoCyprusCzech RepublicCôte d'IvoireDenmarkDjiboutiDominicaDominican RepublicEcuadorEgyptEl SalvadorEquatorial GuineaEritreaEstoniaEthiopiaFalkland Islands (Malvinas)Faroe IslandsFijiFinlandFranceFrench GuianaFrench PolynesiaFrench Southern TerritoriesGabonGambiaGeorgiaGermanyGhanaGibraltarGreeceGreenlandGrenadaGuadeloupeGuamGuatemalaGuernseyGuineaGuinea-BissauGuyanaHaitiHeard and Mcdonald IslandsHoly See (Vatican City State)HondurasHong Kong, SAR ChinaHungaryIcelandIndiaIndonesiaIraqIrelandIsle of ManIsraelITJamaicaJapanJerseyJordanKazakhstanKenyaKiribatiKorea (South)KuwaitKyrgyzstanLao PDRLatviaLebanonLesothoLiberiaLibyaLiechtensteinLithuaniaLuxembourgMacao, SAR ChinaMacedonia, Republic ofMadagascarMalawiMalaysiaMaldivesMaliMaltaMarshall IslandsMartiniqueMauritaniaMauritiusMayotteMexicoMicronesia, Federated States ofMoldovaMonacoMongoliaMontenegroMontserratMoroccoMozambiqueMyanmarNamibiaNauruNepalNetherlandsNetherlands AntillesNew CaledoniaNew ZealandNicaraguaNigerNigeriaNiueNorfolk IslandNorthern Mariana IslandsNorwayOmanPakistanPalauPalestinian TerritoryPanamaPapua New GuineaParaguayPeruPhilippinesPitcairnPolandPortugalPuerto RicoQatarRomaniaRwandaRéunionSaint HelenaSaint Kitts and NevisSaint LuciaSaint Pierre and MiquelonSaint Vincent and GrenadinesSaint-BarthélemySaint-Martin (French part)SamoaSan MarinoSao Tome and PrincipeSaudi ArabiaSenegalSerbiaSeychellesSierra LeoneSingaporeSint Maarten (Dutch part)SlovakiaSloveniaSolomon IslandsSouth AfricaSouth Georgia and the South Sandwich IslandsSouth SudanSpainSri LankaSurinameSvalbard and Jan Mayen IslandsSwazilandSwedenSwitzerlandTaiwan, Republic of ChinaTajikistanTanzania, United Republic ofThailandTimor-LesteTogoTokelauTongaTrinidad and TobagoTunisiaTurkeyTurks and Caicos IslandsTuvaluUgandaUkraineUnited Arab EmiratesUnited KingdomUnited States of AmericaUruguayUS Minor Outlying IslandsUzbekistanVanuatuVenezuela (Bolivarian Republic)Viet NamVirgin Islands, USWallis and Futuna IslandsWestern SaharaZambiaZimbabwe

* I have read and agree with the [Privacy policy](https://tools.techidaily.com/abbyy/products/) and the [Cookie policy](https://tools.techidaily.com/abbyy/products/).

* I agree to receive email updates from ABBYY Solutions Ltd. such as news related to ABBYY Solutions Ltd. products and technologies, invitations to events and webinars, and information about whitepapers and content related to ABBYY Solutions Ltd. products and services.  
    
I am aware that my consent could be revoked at any time by clicking the unsubscribe link inside any email received from ABBYY Solutions Ltd. or via [ABBYY Data Subject Access Rights Form](https://tools.techidaily.com/abbyy/products/).

Referrer

Last name

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
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-transform-videos-on-vimeo-using-zero-dollar-resources/"><u>[New] In 2024, Transform Videos on Vimeo Using Zero-Dollar Resources</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-practical-steps-for-saving-real-time-chat-sessions-for-2024/"><u>[Updated] Practical Steps for Saving Real-Time Chat Sessions for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-from-novice-to-geometric-master-crafting-perfect-circular-and-spherical-objects/"><u>2024 Approved From Novice to Geometric Master Crafting Perfect Circular & Spherical Objects</u></a></li>
<li><a href="https://solve-popular.techidaily.com/elevate-online-experience-with-cookiebot-power-solutions-for-superior-user-targeting-and-retention/"><u>Elevate Online Experience with Cookiebot Power Solutions for Superior User Targeting and Retention</u></a></li>
<li><a href="https://solve-popular.techidaily.com/embracing-innovative-mobility-learn-with-us-on-the-abbyy-blog/"><u>Embracing Innovative Mobility - Learn with Us on the ABBYY Blog</u></a></li>
<li><a href="https://solve-popular.techidaily.com/enhance-online-performance-using-the-powerful-features-of-cookiebot-technology/"><u>Enhance Online Performance Using the Powerful Features of Cookiebot Technology</u></a></li>
<li><a href="https://solve-popular.techidaily.com/enhanced-with-advanced-automation-powered-by-the-cutting-edge-cookiebot-technology/"><u>Enhanced with Advanced Automation: Powered by the Cutting-Edge Cookiebot Technology</u></a></li>
<li><a href="https://solve-popular.techidaily.com/expanded-pdf-handling-in-latest-abbyys-finereader-version-14-for-improved-document-processing/"><u>Expanded PDF Handling in Latest ABBYY's FineReader Version 14 for Improved Document Processing</u></a></li>
<li><a href="https://solve-popular.techidaily.com/experience-personalized-content-with-our-cookiebot-integration/"><u>Experience Personalized Content with Our Cookiebot Integration</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-broadcast-battles-tech-titans-tussle-for-top-spot/"><u>In 2024, Broadcast Battles Tech Titans Tussle for Top Spot</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-nokia-g310-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Nokia G310 To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722972754251-ryzen-cpu-firmware-updates-get-your-latest-drivers-here/"><u>Ryzen CPU Firmware Updates - Get Your Latest Drivers Here</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/streamline-your-skype-experience-with-obs-recordings-for-2024/"><u>Streamline Your Skype Experience with OBS Recordings for 2024</u></a></li>
</ul></div>

