# @loki_yan_seo glossary — named terms / mechanisms (English)

Source: his own posts / replies. Window **2025-07-11 → 2026-08-31 UTC**. Last full public-post count remains **979**. Loki-authored **+165** since last cutoff (was 689; now 854). Other people's tweets and **repost** bodies are not his definitions.

Rule: define only in his words. English below is a tight rendering of what he wrote (his English left as-is). If he used a name and never defined it, the entry records **usage only** — no industry fill-in.

---

## A. Google Content Warehouse / leak fields

### Content Warehouse API Leak
**He said:** In March 2024 "Google accidentally open-sourced the Content Warehouse API internal code docs to Github. That document contained 2,500 pages, 14,000 ranking-related files." "Google engineers' naming conventions let us have traces to follow." Later "there was also data validation."
**ids:** 2091894056687431704, 2092090944648581505, 2090291222556578070
**Related:** contentEffort, QualityAuthorityTopicEmbeddingsVersionedItem, Site Focus

### contentEffort
**He said:** Warehouse variable: "contentEffort - LLM-based effort estimation for article pages." "Since there is a variable definition, then it can definitely be calculated." He assumes an engineer would compute: (1) "generic Template, generic structure written by AI"; (2) "whether the content is Paraphrasing and stitching of the top 20 or top 10 articles"; (3) "whether it can provide unique entities, parameters"; (4) "asset effort in the content: are the images and videos I put original… whether AI-generated"; (5) "Information Gain: has what you wrote appeared before?" Conclusion: "raising contentEffort can raise SEO"; "original text, original images, original video, original insights can all be counted as contentEffort." Batch work with no increment "will definitely be judged as low effort, then you get hit." Google Cloud has an "AI Image Detection" API: "even if it will not punish you, your contentEffort score will definitely not be positive."
**ids:** 2092090944648581505, 2092095823731462302, 2092100375239438810
**Related:** Effort, Originality, Information Gain, EEAT, low effort, Non-commodity Content, AI Image Detection, human effort

### QualityAuthorityTopicEmbeddingsVersionedItem
**He said:** The leak section he talks about first. Look-ats: siteFocusScore, siteRadius, embedding (page/site).
**Quote (2091894056687431704):** "先讲的板块：QualityAuthorityTopicEmbeddingsVersionedItem / 这个板块的几个看点 / 1. siteFocusScore / 2.siteRadius / 3 embedding (嵌入向量) page/site"
**ids:** 2091894056687431704
**Related:** siteFocusScore, siteRadius, pageEmbedding, siteEmbedding, topical authority

### siteFocusScore / Site Focus
**He said:** siteFocusScore "means your site's score for a specific vertical. For example if my whole site writes SEO, then my Focus score on SEO will be higher." Later as Site Focus: "Site Focus basically decides what you can rank and what you cannot rank." The qualitative positioning on About Us feeds this; when focus does not match, "even if my authority is higher (DA, backlinks higher), I still cannot rank travel-related content on this site." Writing east and west, "the Focus score may drop."
**ids:** 2091894056687431704, 2090291222556578070, 2033192558889963680
**Related:** siteRadius, topical authority, qualitative positioning, About Us, Site Reputation Abuse, EEAT

### siteRadius
**He said:** "the degree of deviation / dispersion of each page vector on the site from the site-center vector (siteEmbedding) (the smaller the radius, the more unified all on-site content is; the larger the radius, the more mixed the span of articles)." "Small-radius (siteRadius) sites succeed more easily in a vertical and more easily build your 'expert weight' on that topic and field." If the topic jumps from SEO to "sing, dance, Rap," "siteRadius will get larger."
**ids:** 2091894056687431704
**Related:** siteFocusScore, siteEmbedding, pageEmbedding, expert weight, stay focus

### pageEmbedding
**He said:** "the topic vector of a single page."
**ids:** 2091894056687431704
**Related:** siteEmbedding, siteRadius, embedding

### siteEmbedding
**He said:** "the site-center vector." siteRadius is each page vector's deviation from it.
**ids:** 2091894056687431704
**Related:** pageEmbedding, siteRadius

### embedding
**He said:** One leak look-at: "embedding page/site." Separately: "Google’s embedding system can calculate the similarity between content. It is not about the content creation process, it’s about the originality I guess."
**ids:** 2091894056687431704, 2033897408468553871
**Related:** pageEmbedding, siteEmbedding, Originality

### Navboost
**He said:** "Google's Navboost leak, its entire foundation relies on user clicks and search journeys." He then asks: AI Overviews and AI Mode "are inherently Zero-Click environments"; if users do not click out, "Navboost’s primary data source completely dries up." Two possibilities: (1) "Navboost theories are obsolete for Generative Search, replaced by semantic/vector validation"; (2) "Google secretly swapped 'clicks' with micro-behaviors (hovering, dwell time, query steps)." He closes as a question: "Does Navboost even exist?"
**ids:** 2065232184374645078
**Related:** Zero-Click, AI Mode, AI Overview

---

## B. EEAT / Quality / Spam

### EEAT / E-E-A-T
**He said:** "The reason I have always said I don't believe in pure SEO Automation is that Google set this EEAT threshold." "Here there are 2 key points: Effort and Originality." Generic SEO Automation cannot cross those two. It is bound to topical authority / siteFocus. The "most convenient" way to realize EEAT is site to developer site to GitHub/LinkedIn. "In EEAT, especially sites where Trust goes wrong, it is fatal." "This is the YMYL concept talked about inside Google EEAT." About Us is "often treated like an afterthought" but "one of the most important pages for EEAT." Gemini / AI Mode / AI Overview: "because of the EEAT frame as a floor, AI poisoning is not that easy." English clarification: "EEAT is not a ranking factor (Google said). EEAT determines quality, and Google said Quality is a ranking factor." He did not unpack the four letters one by one in the tweets.
**ids:** 2092095823731462302, 2092090944648581505, 2091894056687431704, 2091198495197913207, 2090738619808088255, 2090697074153283687, 2037884887307526631, 2034868852602151058, 2033390752001335397, 2033335605925654664, 2033192558889963680, 2033189225483677758, 1978391845844426780
**Related:** Effort, Originality, Trust, YMYL, Quality, QRG, topical authority, entity linking, fake author

### Effort
**He said:** "Google has mentioned the Effort concept more than once." He asked how it is quantified; Gary's rough meaning was there would be "mathematic calculation." Quality's "definition is Effort and Original." "Spend heart-force (effort)." The HCU set also listed effort. Generic Automation: "how do you cross Effort and Originality? By how many Tokens you spent?" For AI-export sites, hire a sharp intern to "do the effort things"; "they want work experience, you want 'human' effort." Make images by hand on Canva.
**ids:** 2092095823731462302, 2092090944648581505, 2091362717907251353, 2092100375239438810
**Related:** contentEffort, Originality, Quality, EEAT, HCU, mathematic calculation, human effort

### Originality / original
**He said:** One of the two key points of the EEAT threshold. Quality = Effort + Original. "The original here is not you finding a few sites and stitching them." "You use the education you received… how do you make an AI system, spend heart-force (Effort) to do original content?" Batch work at least needs "increment… get a bit of original stuff." Embedding similarity: "it’s about the originality I guess."
**ids:** 2092095823731462302, 2091362717907251353, 2092090944648581505, 2033897408468553871
**Related:** Effort, contentEffort, Quality, Information Gain, stitching

### Trust
**He said:** "In EEAT, especially sites where Trust goes wrong, it is fatal." What you optimize is "your Money Page, your Trust." In the YMYL frame: "search ranking is not mere traffic distribution, it is trust distribution."
**ids:** 2090697074153283687, 2090983234146574708, 2033390752001335397
**Related:** EEAT, YMYL, Money Page, European playbook

### Quality
**He said:** "Quality should consider the site as a whole." "Starting from 2025 Google first said Quality is a Ranking Factor." "Quality should be a site-wide singal." "The opposite of Quality is Spam." "If your Quality is not as high as the competitor, you cannot outrank the competitor." Quality "can refer to" user experience, site content, Core Web Vitals, "all the details mentioned in QRG"; it can also be "all product photos shot by yourself with a DSLR. All Image Alt, product descriptions written one by one by yourself." Conditions for content that can rank: "1. close to human-written 2. has Quality 3. Quality's definition is Effort and Original." Original images "add a lot to the site's 'quality'." Tension sentence [once]: "It's not about quality. It's about how it was created. If you make your own input there, it is more likely to rank."
**ids:** 2092027807719444899, 2091353930425127142, 2091362717907251353, 2091376367740789153, 2088803453565059194, 2033808549445570669
**Related:** Spam, Effort, Originality, QRG, site-wide, HCU, Core Web Vitals, how it was created

### site-wide signal / site-wide consistency
**He said:** Quality "should be a site-wide singal." "credibility is not only built through isolated articles. It is built through site-wide consistency. And in many cases, the About page is where that consistency becomes visible."
**ids:** 2091353930425127142, 2033192558889963680
**Related:** Quality, About Us, qualitative positioning, Site Focus

### QRG / Quality Rater Guideline
**He said:** "the 182-page QRG." He treats it as the detail book Google uses to look at site Quality. Sections he pointed at: Section 3.3.4 author reputation; 4.5.3 fake authors; 8.4 / page 83 login pages; and several Quality tiers, "highest is the top tier." When asking Gary he put EEAT and QRG together and asked whether "there is an algorithm that runs automatically." "Read that Google 182-page search quality evaluator guidelines carefully, that is the document that defines what EEAT is. Basically every line is an answer."
**ids:** 2092090944648581505, 2091381622616797394, 2091376367740789153, 2091353930425127142, 2090738619808088255, 2088648155172876567
**Related:** EEAT, Quality, highest, author reputation, fake author, MC, login page

### highest (QRG tier)
**He said:** QRG "defines several Quality tiers, of which highest is the top tier." For a login page to reach highest quality he listed: disclosure about information protection; whether you installed a firewall; whether register / forgot-password is complete; whether the login system is third-party; whether the login page is too simple.
**ids:** 2091376367740789153
**Related:** QRG, Quality, login page

### YMYL
**He said:** "If you understand YMYL and EEAT, many topic sites have a threshold mechanism (this is not the sandbox). For example medical, health, news, and keywords directly related to money." "From my observation, the YMYL threshold should be bound to the domain." The real threshold for money-adjacent sites is "authoritativeness, professionalism, compliance," "this is the YMYL concept talked about inside Google EEAT." On a news site he is raising: "for YMYL-category sites, Bing currently should have no threshold."
**ids:** 2091011325438955723, 2088803453565059194, 2033390752001335397, 2033817449922245047, 2034868852602151058
**Related:** EEAT, threshold mechanism, sandbox, Trust, Expired Domain, trust distribution

### threshold mechanism (YMYL)
**He said:** YMYL topics "have a threshold mechanism (this is not the sandbox)." "The threshold should be bound to the domain." Money-adjacent "the threshold is actually very high," "not backlinks," it is "authoritativeness, professionalism, compliance."
**ids:** 2091011325438955723, 2033390752001335397, 2088803453565059194
**Related:** YMYL, sandbox, Expired Domain

### sandbox
**He said:** Used only to negate: "this is not the sandbox." He did not define sandbox itself.
**ids:** 2091011325438955723
**Related:** YMYL, threshold mechanism

### HCU
**He said:** On stage they said that whether or not it is AI-created, as long as the content has "effort, helpful, original and so on (that set of things in HCU)." Another time he lined it up with E-E-A-T and YMYL and asked whether tool sites understand them. He did not unpack the three letters.
**ids:** 2091362717907251353, 2034868852602151058
**Related:** Effort, helpful, Originality, Quality

### helpful
**He said:** Lined up with effort and original as "that set of things in HCU." No standalone definition.
**ids:** 2091362717907251353
**Related:** HCU, Effort, Originality

### Spam
**He said:** "The opposite of Quality is Spam. If you have Spam things on your site it will affect your Quality." "Spam can be: researched an AI Agent, took other people's stuff from various sites and stitched / washed the draft." Large sites use internal ML to do "Quality and Spam classification," then actively No Index low-quality / AI Slope / Spam.
**ids:** 2091353930425127142, 2092027807719444899, 2090697074153283687
**Related:** Quality, Spam_score, AI Slope, stitching, No Index

### Spam_score
**He said:** "Google SEO has a thing called Spam_score. Google has a document called Spam Policies. The things recorded in it probably have an automatic system running." Logic: "For each spam found on your website, spam score +1." "The most obvious few that will definitely get hit are Clocking, AI draft-washing collage, AI flooding, Link Spam." When soft 404 is used by black hats "your site's spam score goes higher."
**ids:** 2090396597066899635, 2091349098553295075
**Related:** Spam, Spam Policies, Spam Update, Clocking, Link Spam

### Spam Policies
**He said:** "Google has a document called Spam Policies. The things recorded in it probably have an automatic system running."
**ids:** 2090396597066899635
**Related:** Spam_score

### Spam Update
**He said:** "Every Spam Update is a refresh." After one: "more reddits, parasites, fake authors after Spam Update."
**ids:** 2090396597066899635, 2037039070371864892
**Related:** Spam_score, parasites, fake author

### Clocking
**He said:** "The ones that will definitely get hit are Clocking, AI draft-washing collage, AI flooding, Link Spam." No other definition. (He wrote Clocking, not Cloaking.)
**ids:** 2090396597066899635
**Related:** Spam_score

### Link Spam
**He said:** Listed among the Spam_score items that "will definitely get hit." No other definition. Backlinks "are useful, but you don't need to chase them. Chasing wastes money."
**ids:** 2090396597066899635, 2090685656079241520
**Related:** Spam_score, Penguin, Anchor Guest Post

### AI draft-washing collage / AI flooding
**He said:** Spam_score items that "will definitely get hit." The Spam example is also "take other people's stuff and stitch / wash the draft."
**ids:** 2090396597066899635, 2091353930425127142
**Related:** Spam, stitching, AIGC, AI Slope

### MC / Main Content
**He said:** "In Google EEAT QRG there is an MC (Main Content) concept." "Looked at from Semantic HTML" that is header / nav / main / section / aside / footer. "What is MC? The stuff inside <main>. If you Div to the end, some things unrelated to main content get fed into the algorithm system."
**ids:** 2090738619808088255
**Related:** QRG, EEAT, Semantic HTML

### topical authority
**He said:** siteFocus / vertical Authoritativeness "is the topical authority thing everyone talks about. Related to EEAT. That is why you see many sites that do a vertical especially well." News SEO: "a given journalist or institution, the coverage of content they publish on a given topic (long enough time, wide enough range), then they naturally have a thing on that topic called topical authority, and their ranking naturally goes up." When you cannot rank, "real work is still in quality, topical authority, and trust."
**ids:** 2091894056687431704, 2091387930963263678, 2033189225483677758
**Related:** siteFocusScore, Authoritativeness, EEAT, News SEO, coverage

### Authoritativeness / A-score
**He said:** After going deep on a vertical "my site's Authoritativeness score on that vertical will correspondingly be higher… my A-score on the whole SEO topic will be higher." After you cross an Authority threshold, "what you compare is page vs page, the micro layer." If the micro layer is maxed, "what you compare is the entity's content depth on a given topic and fame at the social-media layer."
**ids:** 2091894056687431704, 2088627560033009736
**Related:** topical authority, siteFocusScore, EEAT, micro / final form

### expert weight
**He said:** Small siteRadius "more easily builds your 'expert weight' on that topic and field."
**ids:** 2091894056687431704
**Related:** siteRadius, topical authority

### author reputation
**He said:** QRG 3.3.4 "how Google judges a content author's reputation": Educational Degrees, Co-authors, Citations, Employment History, Influencers on Social Media. "Co-author, citation means articles you signed get referenced, and you publish in well-known places." Social "can also raise your authority as an author (I think Xiaohongshu and WeChat official accounts should be useless)." Degrees and employment history "on the whole planet only Linkedin can do this."
**ids:** 2091381622616797394
**Related:** fake author, author entity, entity linking, QRG, EEAT

### fake author
**He said:** "Fake authors will definitely get executed by Google, this thing is a red line. What does a fake author look like? Just look at Alibaba." If you must spread keywords: use the company as Organization author. He quoted QRG 4.5.3 in English: pages with fake owner / AI generated author profiles. "From what I know of Google, anything a command forbids you to do, basically they have a program running there."
**ids:** 2091739865121783923, 2091381622616797394, 2037884887307526631, 2033817449922245047, 2090697074153283687
**Related:** Organization author, author reputation, EEAT, AIGC, European playbook

### Organization author
**He said:** If you must publish and "spread keywords": "use your own company as the Organization author." He gave a "@type":"Organization" JSON-LD sample (name + url).
**ids:** 2091739865121783923
**Related:** fake author

### author entity
**He said:** "When Google looks at authors, it is not just looking at a name you wrote. It looks at the author entity, public resume, LinkedIn account, industry background, and whether this information can be cross-validated." "If the author is packaged by AIGC, it is actually easy to expose once you check." News SEO without Author Profile / degrees and other "entity links" has no topic advantage.
**ids:** 2033390752001335397, 2091387930963263678, 2091381622616797394
**Related:** author reputation, entity linking, fake author, Entity, YMYL

### entity linking
**He said:** "The author's Linkedin should link to the site, the site should link to the author's linkedin — that is the good solution." Convenient EEAT path: "site A <-> developer site <-> GitHub/Linkedin." "Do Linkedin well, and do entity linking with the site."
**ids:** 2091381622616797394, 2091198495197913207, 2090750446839476639, 2091387930963263678
**Related:** author entity, EEAT, Entity

### Site Reputation Abuse
**He said:** About Us / Site Focus "theory is based on the 2024 Google Site Reputation Abuse push, including later data validation in the Google Content Warehouse API Leak." He handled "that wave of US Publisher Site Reputation Abuse, Manual Action is basically fatal to the whole domain." Another time he "personally went through a whole live-fire of Site Reputation Abuse." He did not give a standalone meaning-sentence for the name.
**ids:** 2090291222556578070, 2037884887307526631, 2091301352463102268
**Related:** Site Focus, Manual Action, Content Warehouse API Leak

### Manual Action
**He said:** On Site Reputation Abuse "Manual Action is basically fatal to the whole domain. The handling method is simple: 404 directly, then submit for removal." If it is Manual Action, "every flagged subdomain and Subfolder needs a dedicated 404 page. Then 404 the Subdomain from the source entirely." He also distinguished a different case: "not Manual Action, directly Deindex."
**ids:** 2037884887307526631, 2038199743797690529
**Related:** Site Reputation Abuse, Soft 404, Deindex

### Deindex
**He said:** A case that is "not Manual Action, directly Deindex"; a friend hit it; "recovery cycle is about 3-4 months." For AIGC pages: "Noindex every page from the source, internal links still need staged nofollow, robots.txt adjusted."
**ids:** 2038199743797690529
**Related:** Manual Action, No Index, AIGC

---

## C. Content types and effort judgment

### Commodity Content
**He said:** "Commodity Content means bulk-commoditized content, meaning highly homogenized content." SEO examples: "to do SEO you must do backlinks, because backlinks raise weight. Your site DA is not enough so you have no ranking, you must do DA." "You must write blogs, spread keywords, then you get traffic." "To do GEO you must do Reddit."
**ids:** 2091487107806323136
**Related:** Non-commodity Content, keyword-spreading, DA

### Non-commodity Content / Non-Commodity Content
**He said:** "This year at Search Central Live in North America Google first mentioned the definition of Non-Commodity Content. Google said AI Search will prefer Non-commodity Content more." "Non-commodity Content means non-commoditized content: exclusive experience sharing, unique viewpoint, content that cannot be easily replaced by a generic knowledge base." His writing method: "every concept I throw out, or share, will have a concrete instance as evidence." "As of today, automation and AIGC things probably still cannot, with no human intervention, fully realize this Non-Commodity concept."
**ids:** 2091487107806323136
**Related:** Commodity Content, contentEffort, distillation, AIGC

### Information Gain
**He said:** contentEffort assumption #5: "Information Gain: has what you wrote appeared before?" Batch work "at least needs increment. At least from the data and content angle, you have to find a way to get a bit of original stuff."
**ids:** 2092090944648581505
**Related:** contentEffort, Originality

### low effort
**He said:** Batch with no original increment "will definitely be judged as low effort, then you get hit."
**ids:** 2092090944648581505
**Related:** contentEffort, Effort

### how it was created
**He said:** On whether AI-generated content can rank: "It's not about quality. It's about how it was created. If you make your own input there, it is more likely to rank."
**ids:** 2033808549445570669
**Related:** Quality, Effort, Originality, contentEffort

### human effort
**He said:** For small companies / indie exporters, hire a sharp domestic intern "to do the effort things." "They want work experience, you want 'human' effort. Get a Canva account, make images by hand, you can do a lot in a month."
**ids:** 2092100375239438810
**Related:** Effort, contentEffort, AI Image Detection

### AI Image Detection
**He said:** "For example Google Cloud has this AI Image Detection API. Even if it will not punish you, your contentEffort score will definitely not be positive."
**ids:** 2092100375239438810
**Related:** contentEffort, Effort, SEO edge-work

### AI Slope
**He said:** Used as a name for low-quality AI content. Japanese-region JDs "did not require us SEO people to develop AI Agent/workflow to manufacture large amounts of high-quality AI Slope." Ameba actively No Indexes "low-quality, AI Slope, Spam articles." "Site weight cannot offset the negative impact brought by AI Spam, AI Slope, junk blogs." He did not write "AI Slope is…".
**ids:** 2092027807719444899, 2089165558516437461
**Related:** AI Spam, Spam, AIGC, No Index

### AI Spam
**He said:** Lined up with AI Slope and junk blogs; site weight cannot offset its negative impact.
**Quote (2089165558516437461):** "网站权重并不能抵消掉 AI Spam, AI Slope, 垃圾博客带来的负面影响。"
**ids:** 2089165558516437461
**Related:** AI Slope, Spam, keyword-spreading

### AIGC
**He said:** Used as the name for generated content. "If you got hit because of AIGC content, just delete it and you're done." Fake-author cases, YMYL author swaps, Non-commodity "AIGC things probably still cannot do it." Authors "packaged by AIGC are actually easy to expose once you check."
**ids:** 2091739865121783923, 2091487107806323136, 2033817449922245047, 2033390752001335397, 2037884887307526631
**Related:** fake author, Non-commodity Content, AI Slope

### stitching
**He said:** contentEffort check: "Paraphrasing and stitching." Original "is not you finding a few sites and stitching them." Spam = "take other people's stuff and stitch / wash the draft."
**ids:** 2092090944648581505, 2091362717907251353, 2091353930425127142
**Related:** contentEffort, Originality, Spam

### PSEO
**He said:** "PSEO is best if it can be held up by a set of original things (whether your own algorithm, rating system, data, or product), otherwise it will get smashed within half a year. No matter how high the site weight, as long as PSEO and the spread content are not original, basically this year there will be problems."
**ids:** 2088639745807278589
**Related:** Originality, keyword-spreading, Commodity Content

### distillation
**He said:** On whether AI can quantify contentEffort: "I think it's shaky. Why don't you distill me." Content is the hardest because "unless before you write you first distill everything you understand and know," AI cannot replace human thinking.
**ids:** 2092090944648581505, 2091487107806323136
**Related:** Non-commodity Content, contentEffort

---

## D. Search forms: SEO / GEO / AIO / AEO

### SEO (his working definition)
**He said:** "Writing blogs is not called SEO." "Writing blog posts != SEO." Traditional Search "does three things: crawl sites, index sites, serve (ranking)." Two kinds: one "does ranking, organic traffic, raise conversion. This is doing growth"; the other, big firms, "does Maintain leadership, must control risk… stop other people from messing around" — "the difference between taking the hill and holding the hill." Doing SEO (and future GEO) "is all catching demand." Also: "SEO is like an adhesive, or a foundation… it is the process of maximizing a site and a brand's exposure on search engines." "Even later when it is AI, it is still a process of maximizing site and brand exposure in each place." "Doing SEO is to make money… what you optimize is your Money Page, your Trust."
**ids:** 2092059738062348681, 2081519248011370590, 2091364706703581191, 2091321150127366357, 2091668405367791619, 2091463375003983897, 2090983234146574708
**Related:** two kinds of SEO, GEO, Technical SEO, keyword-spreading, maximize exposure

### two kinds of SEO / take the hill / hold the hill
**He said:** The ordinary kind is growth; the higher-order kind, "Canva, Zillow, Booking, those big firms that eat SEO traffic… Maintain leadership, must control risk." "Any change on the site can cause potential organic-traffic drop risk, causing your Leader position in the industry to drop, indirectly causing stock-price problems." "The difference between taking the hill and holding the hill."
**ids:** 2091321150127366357
**Related:** SEO, Site Migration

### GEO
**He said:** "SEO is slowly leaning toward AEO, GEO." "How do you do AEO, GEO?… I think their underlying logic is about the same as SEO: optimize your brand and site entity, so LLM / AI recommend your brand and product." "What is GEO optimization actually doing? Anyway I just took traditional SEO to the extreme, and traffic from ChatGPT rose." The internet set of Reddit / semantic matching / PR / schema / FAQ: "all the materials I have seen… have no evidence proving these methods are the correct way, because the logic does not hold." He splits: "Helping the model understand you more accurately, and finding ways to make the model lean toward you, are not the same thing at all. The former is construction. The latter easily slides into pollution." "GEO will not disappear in the end; it will only, like SEO, split into white-hat and black-hat." "Sites and businesses that have not even run ordinary Digital Marketing channels, then inexplicably do GEO, is the stupidest thing." A later understanding: "Doing GEO is just more expensive SEO, because now besides your own site you also have to do Social, influencers, PR, media." On Reddit-as-GEO: "same logic as people who specialized in backlinks more than ten years ago. One algorithm change can blow up your whole logic." For non-English, especially Simplified Chinese, he left a door: "not saying the method of using Reddit for GEO is wrong."
**ids:** 2091727382726205949, 2079109647160734202, 2033335605925654664, 2064910376060498033, 2091013621790716336, 2091487107806323136, 2091368931353362479
**Related:** AEO, AIO, Entity, SEO, white-hat GEO, answer layer, AI poisoning, Broad GEO

### AEO
**He said:** Lined up with GEO, same "underlying logic is about the same as SEO." Roles "are all leaning into AEO, GEO." No standalone mechanism sentence.
**ids:** 2091727382726205949, 2091060807065117104
**Related:** GEO, SEO, AIO

### AIO
**He said:** "At Google, SEO/AIO/GEO have three concepts: 1. traditional Search 2. AI Mode / AI Overview 3. Gemini." "Optimizing Google SEO and AIO: the AI Mode / AI Overview line is just doing SEO, no difference at all." Roles: "most AIO, GEO roles have fused with SEO."
**ids:** 2091364706703581191, 2091060807065117104
**Related:** AI Mode, AI Overview, Gemini, SEO, GEO

### traditional Search
**He said:** First of the three SEO/AIO/GEO concepts. "Traditional Search, which is what we used to call SEO, does three things: crawl sites, index sites, serve (ranking)."
**ids:** 2091364706703581191, 2091071455350169891
**Related:** SEO, Crawl, Index, serve

### AI Mode / AI Overview
**He said:** "AI Mode/AI Overview, in the first two steps Crawl and Index, are consistent with traditional SEO! The mechanism is completely consistent!" Serving "is based on the traditional ranking mechanism, plus Grounding on Search Index Query Fanout. So their database is completely consistent." "Including the newest AI Overview, AI Mode, they are one whole system, they are Gemini Power systems, using Search logic." "are inherently Zero-Click environments." "The essence of AI Mode is Google Search. It is the old set of things, swapped to Gemini to do ranking." "LLM things, for example inside the gemini app, are still not under SEO (Google Search department)."
**ids:** 2091364706703581191, 2091071455350169891, 2065232184374645078, 2033335605925654664, 2090307375836315959
**Related:** Grounding on Search Index Query Fanout, Gemini, AIO, Zero-Click, Navboost

### Grounding on Search Index Query Fanout
**He said:** AI Mode / AI Overview, at Serving, "added Grounding on Search Index Query Fanout." He did not unpack those three words further.
**ids:** 2091364706703581191
**Related:** AI Mode, AI Overview

### Gemini (versus Search)
**He said:** Third of the three concepts. "uses crawlers for data, Gemini's crawlers should be a different crawler mechanism from Google Search." "indexing here is written Not part of search." "Gemini is not under the Search department, they are different departments." "But, Gemini itself is not under Search." "So the things Google Search officially publishes that everyone usually watches are limited to traditional SEO, AI Mode / AI Overview, and have nothing to do with Gemini." Optimizing Gemini "you can refer to that traditional SEO theory set, because their core, including a lot of the infrastructure they use, is the same." "Gemini's mechanism will be different."
**ids:** 2091364706703581191, 2091071455350169891, 2091368931353362479, 2090307375836315959
**Related:** AI Mode, AIO, SEO, LLM.txt

### Google SEO (the scope he drew)
**He said:** "Google SEO includes traditional Search, ecommerce, Image Search, Video, News, Discover and so on. As long as the entry is through Google.com, I think it can all be called the Google Search part."
**ids:** 2091071455350169891
**Related:** News SEO, AI Mode, Discover

### News SEO
**He said:** "News SEO is a very vertical track inside Google, including three lines: Google Top Stories, Google News, Google Discover." "When you search news on Google, news ranking can be manipulated by SEO methods." Topic advantage comes from coverage to topical authority.
**ids:** 2091387930963263678, 2091729433279496522
**Related:** topical authority, Google SEO, author entity

### Discoverability
**He said:** "Some companies turned the old traditional SEO role into Discoverablity, especially in the US." No mechanism definition. (He spelled it Discoverablity.)
**ids:** 2091060807065117104
**Related:** SEO, AIO, GEO

### white-hat GEO / black-hat GEO / construction / pollution
**He said:** "Helping the model understand you more accurately, and finding ways to make the model lean toward you, are not the same thing at all. The former is construction. The latter easily slides into pollution." "Whether this industry will quickly form a white-hat and black-hat boundary." "The real question is not whether you are doing GEO, but whether you are optimizing, or polluting."
**ids:** 2033335605925654664
**Related:** GEO, AI poisoning, answer layer

### answer layer
**He said:** The entry gets bought: used to be search results, then recommendation feeds, "now, it is AI's answer layer's turn."
**ids:** 2033335605925654664
**Related:** GEO, pollution

### AI poisoning / poison resistance
**He said:** "Google Gemini, AI Mode, AI Overview, because of the EEAT frame as a floor, AI poisoning is not that easy to interfere with Google's results. ChatGPT and Claude's newest models, on poison resistance, are also more significant than before."
**ids:** 2033335605925654664
**Related:** EEAT, GEO, pollution

### Zero-Click / 0-Click
**He said:** "AI Overviews & AI Mode are inherently Zero-Click environments." On Bing Total Citations: "According to 0-Click theory. Is this number not the traffic Bing stole from your site?"
**ids:** 2065232184374645078, 2021379383303471595
**Related:** Navboost, Total Citations, AI Mode

### Total Citations (Bing)
**He said:** "In the official guide, Total Citations means, in a specified time range, the number of times your site was seen or Cited as Source in an AI-Generated Answer."
**ids:** 2021379383303471595
**Related:** 0-Click, GEO, GSC Generative AI

### Broad GEO
**He said:** "There is a word trap here: what Google said is, from the Google Search angle, AI Overview and AI Mode do not care about LLM.txt. Google Search does not include Gemini, they are two departments. Broad GEO includes ChatBOT, LLMs, including all other platforms. So if GEO is the broad kind, and you have to do all platforms, you still have to do LLM.txt."
**ids:** 2071840010593358218
**Related:** GEO, LLM.txt, Gemini, AIO

### LLM.txt
**He said:** From the Google Search angle, "AI Overview and AI Mode do not care about LLM.txt." "If GEO is the broad kind, and you have to do all platforms, you still have to do LLM.txt."
**ids:** 2071840010593358218
**Related:** Broad GEO, Gemini, AI Mode

### Day 0 Framework / machine-readable / AI readability test
**He said:** Talk title "Rebuilding for the Machine: A Day 0 Framework for AI Inclusion." "Most APAC brands don’t have an authority problem. They have a technical one." "still invisible… because their digital foundations were never built for machine interpretation." He will talk "what actually makes a brand machine-readable" and "AI readability test," "what needs to be rebuilt from Day 0 if we want AI systems to retrieve, interpret, and trust our information correctly." No steps in the tweet.
**ids:** 2033414646775083406
**Related:** Technical SEO, GEO, Entity

### Search Marketing
**He said:** "Search Marketing includes SEO, PPC. Its content covers Content Marketing, Digital PR, GTM and so on."
**ids:** 2091671329812717693
**Related:** SEO

### be found / be chosen
**He said:** "to get ChatGPT recommend your brand, you need to be found, be chosen... It's like you need to drink water and eat dinner. But how to get found and how to get chosen? I guess it's called magic."
**ids:** 2092054444854968463
**Related:** GEO, SEO magic

### information cocoons / asymmetric rules / non-English disadvantage
**He said:** "AI did not eliminate information cocoons. It may only have re-amplified old information asymmetry in a new way." "The rules themselves are not fully symmetric." If models like ChatGPT / Gemini / Claude / Grok "are built mostly on English-heavy training data," "non-English brands are already at a disadvantage? Not because their product is worse. Not because their content is worse. But because the model understands their world less well." Other-language brands "naturally have a harder time entering that layer of information network the model reaches for most smoothly." This "looks like a technical problem, but in essence becomes a brand-visibility problem, a recommendation-power problem, even a discourse-power problem."
**ids:** 2034056213529563637, 2034056920827629816
**Related:** GEO, brand visibility, recommendation power

### maximize exposure
**He said:** "we used to call it search-engine optimization, actually it is the process of maximizing a site and a brand's exposure on search engines." "Even later when it is AI, it is still a process of maximizing site and brand exposure in each place." Future SEO "may not be as simple as just doing a site"; AI Mode already has "not only sites, but also Youtube, Facebook."
**ids:** 2091463375003983897, 2090960111447794111
**Related:** SEO, GEO, AI Mode

### Copilot (Bing)
**He said:** "Microsoft has copilot. It should be the same as the Bing side." Bing AI Performance Dashboard shows Microsoft Copilot and AI Summary in Bing Search.
**ids:** 2091368931353362479, 2021379383303471595
**Related:** GEO, Total Citations

---

## E. Technical mechanisms

### Technical SEO
**He said:** "Suddenly I realized Technical SEO is all of the Foundation. Crawler-resource management, render management, Core Web Vitals of giant sites (with a lot of data interaction) and so on." "As long as you understand Tech SEO you can find a pretty good SEO job." The premise of the third awakening is "the site is at a Technical level." Day 0 talk: "connect traditional Technical SEO with AI Search."
**ids:** 2091301352463102268, 2033414646775083406
**Related:** Crawl Budget, render, Core Web Vitals, Soft 404, Day 0 Framework

### Soft 404
**He said:** "A normal 404 should return the http 404 code. Soft 404 means you made an error page, but the HTTP status actually returned is 200." Side effects: (1) "affects Google's crawl budget… the places on a large site that should be crawled cannot be crawled"; (2) the frontend takes title/h1 from the URL, "black hats use PBN and such to manufacture a batch of junk pages that can be indexed. Your site's spam score goes higher." Angular render timeouts "caused many pages to show a Soft404 state"; after fixing render "traffic suddenly surged." Alibaba "the whole site is almost all soft 404; if you change them to http 404 the site will explode."
**ids:** 2091349098553295075, 2091301352463102268, 2037884887307526631
**Related:** Crawl Budget, PBN, Spam_score, render, Error Rate

### Crawl Budget
**He said:** Soft 404: "the crawler has to spend budget to look at your page. But this page of yours has nothing." "All last year, at every conference, when Google talked crawl budget they specially mentioned soft 404." In the Klook JD, The Evangelist must be able to explain "Crawl Budget" to C-level.
**ids:** 2091349098553295075, 2091844216980979877
**Related:** Soft 404, Technical SEO

### Raw = Rendered
**He said:** "At the content layer you must satisfy both at once, try not to use Display none, that causes duplicate content. Raw = Rendered." To "100% guarantee your technical architecture is better than your competitor": "Raw HTML must be consistent with the content after Rendered." Screaming Frog can see "the difference between Raw HTML and JS-rendered HTML."
**ids:** 2091508567119642847, 2091008050262110227
**Related:** Desktop = Mobile, display none, Technical SEO

### Desktop = Mobile
**He said:** The other half of the formula: "Desktop = Mobile." To beat the competitor: "your mobile-end and desktop-end content must be consistent."
**ids:** 2091508567119642847, 2091008050262110227
**Related:** Raw = Rendered, m-site

### display none / one HTML may appear only once
**He said:** "Try not to use Display none, that causes duplicate content." "One HTML may appear only once, you cannot use a display none writing style."
**ids:** 2091508567119642847, 2091008050262110227
**Related:** Raw = Rendered

### m-site
**He said:** "Google and Bing both do not recommend separating the m-site and the desktop site." "Mobile site means your site is called apple.com, and you also made an m.apple.com." "Even if Canonical is done well, it still does not work."
**ids:** 2091008050262110227
**Related:** Desktop = Mobile

### Site Migration
**He said:** "Site Migration is the most complex and highest-technical-gold job in SEO." Points he listed: developers must do 301; "301 Redirect must be one-to-one"; "fully control the before-and-after URL versions"; "Google has a standard process for Migration"; casually changing a page / product / domain "may throw away years of accumulation"; do an SEO Review before changing.
**ids:** 2091309003397902703
**Related:** 301 Redirect, two kinds of SEO

### 301 Redirect
**He said:** Migration: "developers did not know they had to do 301 Redirect"; "301 Redirect must be one-to-one." A Chinese subdomain of Al Jazeera "now the whole subdomain is 301'd."
**ids:** 2091309003397902703, 2034784854009946123
**Related:** Site Migration

### above-the-fold / first screen (Mobile)
**He said:** "Google's 2012 above-the-fold algorithm" + "Google is fully mobile first, and can do JS render" so "if after the crawler has rendered your page, your first screen is empty, or has little stuff, you will get hit directly." "The first screen here means the Mobile first screen." "Remember to put <h1> on the first screen, don't hide it below." Test: GSC / Rich Results Test, see whether Cookie / ad popups cover above the fold.
**ids:** 2090686787534598639
**Related:** mobile first, render

### Penguin
**He said:** "In 2016 Google already folded the Penguin algorithm into core. Penguin is Google's algorithm specifically aimed at backlinks."
**ids:** 2090685656079241520
**Related:** Link Spam, backlinks

### Semantic HTML
**He said:** MC "looked at from Semantic HTML means every page's code must follow" header / nav / main / section / aside / footer. "h1 h2 h3 img table, ul, all kinds of html elements must be watched."
**ids:** 2090738619808088255
**Related:** MC

### duplicated page title
**He said:** WeTV used a long platform-default title and did not put the show name in: "this is the duplicated page title problem. Or you did not put the core keyword in the title." It may also be "the frontend called a default page title when rendering."
**ids:** 2091682678261375106
**Related:** page title, render

### product feed / product schema / Shopping feed
**He said:** Shopify "product feed needs extra second-pass optimization, do it in merchant centre, Shopify native support is not good enough. product schema also needs a second-pass hack. If you do these two well, there will be a qualitative leap." Later: "Shopping feed (merchant centre), image alt, product image quality — after these three things are done well, it grows very hard."
**ids:** 2089230010616062038, 2091995138864406654, 2091199226856521823
**Related:** Shopify, Agentic Shopping

### robots.txt (audit item 1)
**He said:** "If a site has large-area ranking drop, when doing an SEO Audit, the first thing to look at is robots.txt, the second is Crawl status." Zhihu "banned all crawlers in robots.txt" then the traffic / index story.
**ids:** 2091795112745689273
**Related:** Crawl status, index

### Crawl status
**He said:** Large-area drop audit "the second thing to look at is Crawl status."
**ids:** 2091795112745689273
**Related:** robots.txt, Crawl Budget

### No Index (quality gate)
**He said:** Ameba, at that volume, avoiding Spam / AI Slope: after internal ML classification, "actively No Index low-quality, AI Slope, Spam articles." Deindex recovery: "Noindex every AIGC page from the source."
**ids:** 2092027807719444899, 2038199743797690529
**Related:** Spam Filtering, Quality, AI Slope, Deindex

### Spam Filtering (in-site ML)
**He said:** "They introduced an internal Spam Filtering mechanism, i.e. they built an internal Machine Learning program, to classify articles on the site into Quality and Spam."
**ids:** 2092027807719444899
**Related:** No Index, Quality, Spam

### Core Web Vitals
**He said:** One of the things Quality can refer to; one of the Technical SEO foundations (CWV of giant sites "with a lot of data interaction"). Field panel: cruxvis.withgoogle.com origin+all 28d LCP/CLS/INP. Lighthouse/PSI = lab. CWV is not a named ranking factor; with other page-experience it is ranking-related.
**ids:** 2091353930425127142, 2091301352463102268, 2092889660783722868
**Related:** Quality, Technical SEO

### PBN
**He said:** Soft 404 gets "black hats using PBN and such to manufacture a batch of junk pages that can be indexed." When buying a domain, check whether it was "used as a spam site, PBN network." No PBN definition.
**ids:** 2091349098553295075, 2064981657497813013
**Related:** Soft 404, Expired Domain

### Expired Domain
**He said:** "In the Affiliate performance-marketing world there is a group of players who buy expired domains and, at algorithm-update Timing, quickly rank some high-value keywords." "The domain itself also carries a lot of good, valuable data." How to check: backlinks via SEMRush/Ahrefs/Majestic, Traffic Trends, Wayback. "Old hands who like to buy Expired Domain all pan for valuable domains this way." He has seen Gov/Clinic/Medical domains used to rank Casino, Web3.
**ids:** 2091011325438955723, 2064981657497813013
**Related:** YMYL, PBN, domain

### Error Rate
**He said:** If they have never done a standard http 404, "if you do the whole site, you will probably pull out tens of millions to hundreds of millions of 404s at once. The whole site's Error Rate goes up."
**ids:** 2038188681090183215
**Related:** Soft 404, Manual Action

### .app domain / dual-end Authority
**He said:** "You can do the site and the mobile App through the same .app domain." "After web and App dual-end are connected you can accelerate your Authority, after all you gained two extra Profile backlinks from App Store and Google Play Store at the same time." If you decide to make mobile apps, "use .app because you can find great domain names still available under .app." Domain preference: ".com > .ai > .io."
**ids:** 2091492121186635988, 2033312223096086964
**Related:** Authority, Personal Branding, backlinks

### Bread Crumb / Schema Markup / article tag
**He said:** Ecommerce technical side "is HTML things": "whether your product card used article or the like / whether Bread Crumb is done / whether Schema Markup is complete."
**ids:** 2092036772687716771
**Related:** product feed, Semantic HTML

---

## F. Names and redefinitions he made

### SEO impossible triangle
**He said:** "SEO's impossible triangle, i.e. Scale, Quality, Speed. You are unlikely to realize the above three things at the same time without spending money."
**ids:** 2090567084933787767
**Related:** Quality, Scale, Speed

### European playbook
**He said:** A Casino Affiliate "from start to finish played the old playbook of backlinks, fake authors, Spam, stacking junk content; I call it the European playbook." After the algorithm smashed it they still "kept buying backlinks, kept publishing blogs, kept making fake authors, to recover the EEAT problem."
**ids:** 2090697074153283687
**Related:** EEAT, Trust, fake author, Spam

### official-doc modality
**He said:** "Please implement: you must do it / Recommend: must do / Avoid: don't do / Do not: execute." Multilingual: "Google said don't do redirects… whatever the official recommendation is, that is what it is."
**ids:** 2091807896053101013, 2091805576611471526
**Related:** auto-redirect

### auto-redirect (don't)
**He said:** Multilingual "why not auto-redirect? There is no why, Google said don't do redirects." "Never automatically switch language and auto-jump by IP." How: "refer to the popup at the very top of the apple official site."
**ids:** 2091805576611471526, 2091014853863637176, 2091064564846854527
**Related:** official-doc modality

### KW Difficulty (ammo redefinition)
**He said:** "When you pick words and look at KW Difficulty, what you are actually looking at is how much ammo and equipment and personnel the competitor has, not how simple or hard the word is." How to see opponent scale: headcount of SEO / content titles on LinkedIn, hiring moves.
**ids:** 2091668405367791619
**Related:** catch demand

### DA / Domain Authority (result, not cause)
**He said:** "Suddenly realized it seems DA is not the cause of ranking, but the result. I.e. many high-ranking sites have a lot of DA and backlinks, that does not mean that to rank you must have very high DA and backlinks." "One of the most persistent SEO myths is that Domain Authority and backlink volume are the most important ranking indicators." "Third-party authority metrics are, at best, rough proxies." Commodity counter-example: "your site DA is not enough so you have no ranking, you must do DA."
**ids:** 2091301352463102268, 2033189225483677758, 2091487107806323136, 2090291222556578070
**Related:** Commodity Content, topical authority, Quality, Domain Rating

### Domain Rating / DR
**He said:** "you don’t need domain rating to rank. Domain rating is old fashion now." "I used to do 40 beating 90, so I think DR is for reference only." "DA and backlinks are mainly for reference. Don't chase them on purpose. DA can be a reference for whether this track is especially crowded, because the cost to get it up is relatively high."
**ids:** 2033717808757149896, 2088606575581856225, 2088636106271256974
**Related:** DA, On Page

### SEO keyword-spreading (he said it does not exist)
**He said:** "You should understand that the concept SEO keyword-spreading does not exist. In theory, when you make every page, you clearly know what each page is for, and what word it will rank." "I think spreading keywords and spreading content, these two things are in essence a pseudo-proposition." The Commodity example also has "you must write blogs, spread keywords." If you must spread: use an Organization author.
**ids:** 2090954259680694666, 2089165558516437461, 2091487107806323136, 2091739865121783923
**Related:** Commodity Content, fake author, AI Slope, PSEO

### Entity
**He said:** Homepage-word formula "{modifier} + Entity." Example: Melbourne is the modifier, SEO Consultant is the Entity. "If you don't understand the Entity concept, you can refer to the 2012 article Google published about the Knowledge Graph." "Here you can understand it as: a keyword is actually not a string (String) but an entity thing (Entity). You can imagine Entity as a NoSQL structure, to make it easier." "After you understand entity, you will find the KW Density concept is actually nonsense." GEO: "optimize your brand and site entity."
**ids:** 2091185632202883243, 2091727382726205949, 2090750446839476639
**Related:** {modifier}+Entity, KW Density, author entity, GEO, Knowledge Graph, root keyword

### {modifier}+Entity
**He said:** The homepage should find a keyword that can cover the next three-to-five-year direction; generally it is "{modifier} + Entity." Once the homepage tone is set, sing-dance-Rap should not go on the same site to rank. "My root word I picked is SEO Consultant, the modifier is Melbourne, then I locked the Melbourne region. Because many words have a geographic limit."
**ids:** 2091185632202883243, 2091399665241759915
**Related:** Entity, Hierarchy, Site Focus, root keyword

### root keyword
**He said:** "You first need a Root keyword, then take Ads Forecast data, download it all at once, then let Claude tidy it, basically you can get a fairly accurate Search Volume." Lined up with the modifier: "my root word I picked is SEO Consultant."
**ids:** 2065688886270108027, 2091399665241759915
**Related:** {modifier}+Entity, Entity

### KW Density
**He said:** After understanding Entity "the KW Density concept is actually nonsense." He does not treat it as a valid mechanism.
**ids:** 2091185632202883243
**Related:** Entity

### Hierarchy (homepage)
**He said:** "From the Hierarchy angle, and for the vast majority of companies, the homepage is the most valuable page."
**ids:** 2091185632202883243
**Related:** {modifier}+Entity, qualitative positioning

### qualitative positioning / dingxing (About Us)
**He said:** "Your site must have an About Us page, and a Contact Us page. On the About Us page you must give your site, your brand, a qualitative positioning (定性). This positioning will affect your final ranking." Theory based on Site Reputation Abuse + Warehouse leak Site Focus. In English, About Us establishes who / what / experience / whether it aligns with the real-world entity. Later: "the definition on your homepage and about us… you give yourself a definition, then whether it can cover the topics you want to cover. If the starting definition is too wide, you will definitely be slow. If the starting definition is too narrow, too vertical, you will have to change later." "You can group by category… do the classification well. Not lay them flat together."
**ids:** 2090291222556578070, 2033192558889963680, 2091897363598315734
**Related:** Site Focus, About Us, Entity, EEAT

### trust distribution
**He said:** YMYL / money sites: "search ranking is not mere traffic distribution, it is trust distribution."
**ids:** 2033390752001335397
**Related:** YMYL, Trust, EEAT

### Money Page
**He said:** "What you optimize is your Money Page, your Trust." "I think you should do money page. Although money page competition is larger, users will convert from your service, money page, not from blogs."
**ids:** 2090983234146574708, 2091775475635073373
**Related:** Trust

### {brand+keyword} linearity
**He said:** "When sites are all extremely good (god-fight level), the size of {brand+keyword} search volume and that page's ranking are basically a linear consistent relationship."
**ids:** 2090684152328945976
**Related:** Entity

### clinical
**He said:** Tech SEO "only after you have done it hands-on can you have clinical experience." The render-fix time, that clinical experience sent him to Search Central Live. Site architecture "can fully follow business logic, clinical logic, fact logic, science logic, and so on."
**ids:** 2091301352463102268, 2090938323284185332
**Related:** Technical SEO

### micro / final form
**He said:** After Technical is at a level, "what plays the decisive ranking factor is all things at the micro layer. Every HTML Tag on the page, every character, every paragraph, every Alt Tag, every Anchor Text, they finally compose your page's final form. Ranking ranks this final form."
**ids:** 2091301352463102268
**Related:** Technical SEO, Quality, Authoritativeness

### generic SEO Automation
**He said:** Does not believe "pure SEO Automation" because the EEAT threshold is Effort + Originality. "If every site needs some customized strategy to realize Effort and original, then what do you still want generic SEO Automation for? Isn't that just customization?" Doing "process, agent, automation… all customized to raise my own work efficiency" is fine; "making a generic Agent to sell" needs more thought. The question is "is it technically unrealizable, or is the logic blocked?"
**ids:** 2092095823731462302, 2092073561171398727, 2092067172021608918
**Related:** EEAT, Effort, Originality, contentEffort

### mathematic calculation
**He said:** Asked Gary how effort is automatically measured; the other side "roughly meant there would be mathematic calculation." Asked again at Search Central Live Shanghai 2026: "there's mathematic calculation for those things mentioned on the EEAT Guideline."
**ids:** 2092090944648581505, 2088131678065852712
**Related:** Effort, contentEffort, QRG

### catch demand
**He said:** "Doing SEO including future GEO is all catching demand. Suppose 100 people a month search a solution or a product, then everyone is grabbing dishes from the same plate."
**ids:** 2091668405367791619
**Related:** SEO, GEO, KW Difficulty

### SEO magic / black box
**He said:** Quoted and stressed the Klook JD: "You don't believe in SEO magic. You believe in hypothesis, test, measure, and iterate." "Because Google's algorithm is in essence a black box… our ordinary work is still crossing the river by feeling the stones; all experience is done through hypothesis, test, measure, iterate." The ChatGPT-recommend line also called the how "magic."
**ids:** 2091844216980979877, 2092054444854968463
**Related:** clinical

### On Page
**He said:** "Suppose you have a page A to VS several competitor pages. You can fully, through On Page and other things, surpass the other side." Because he "used to do 40 beating 90," DR is for reference.
**ids:** 2088606575581856225
**Related:** Domain Rating, micro / final form

### XXX AI Agent (invented search name)
**He said:** "The concepts you know do not mean your users will search that way." "When doing AI export don't casually always call yourself XXX AI Agent." AI Agent search volume is high, but Trends by region over 5 years: "top ten are basically Asia, the US is only 8th, China is first by a leading margin." "I have always felt this word is something we created ourselves." For C-end AI SEO "the words they search may not be Agent, not yet."
**ids:** 2091304086608236745
**Related:** catch demand, Entity

### moat
**He said:** Wirecutter "its whole ranking and traffic moat is based on these 150 named, experienced people." "SEO's assets are always brand and people." On a self-run news site: "all content is hand-made, there is no Agent, no Workflow." "SEO is like that, there is no shortcut, the moat has to be stacked by people."
**ids:** 2090735573443158517, 2064883047825395749
**Related:** Effort, author entity, Non-commodity Content

### money-printer play
**He said:** "The North American money-printer play of this kind is spend money to buy people, buy content, accumulate day by day."
**ids:** 2090735573443158517
**Related:** moat, Effort, Content Writer

### Personal Branding / real-name domain
**He said:** If you want to do Personal Branding: "you should prepare to make your own site, gather all your things together." "Best find a domain directly related to your name, best not use a stage name." Domains: ".com, .digital, .io, .ai, .dev and so on." For more special local professions (lawyer, dentist, etc.) who want the personal site to get clients, "you can do a local domain" (e.g. .com.au, .co.uk).
**ids:** 2091316062709309490
**Related:** entity linking, author entity, .app domain

### reviews / brand reputation / prove you are first
**He said:** Ecommerce "one very important thing is review, brand reputation, and how you prove you yourself are first in this field" — manufacturer / collaborate with designers / won awards, etc.
**ids:** 2092036772687716771
**Related:** Trust, EEAT, Money Page

### GSC Generative AI / 5% test
**He said:** "GSC Generative AI data, what is your highest?" "Will you treat this as a goal, or a KPI?" "Do Citation and key conversion data line up?" "Can real conversions brought by traffic from AI exceed 5% of the whole site?"
**ids:** 2088839484083404844
**Related:** Total Citations, GEO, Zero-Click

### SEO edge-work
**He said:** Besides tips and dry goods he can also do a little "SEO edge-work." "Many Google SEO things, even things Gemini uses now, may exist in the Google Cloud system. You have to associate and hypothesize yourself." "The purpose of learning SEO Best Practice is to use the rules inside a reasonable range." For AI-export sites: name your model; make a page/set that states versions from day one (App Store changelog / Engineer Doc); make download / download/ios / download/android and link the app stores; if you will not link LinkedIn, make a higher-activity GitHub.
**ids:** 2092100375239438810, 2092098493695553818
**Related:** Best Practice, AI Image Detection, contentEffort, entity linking

### Best Practice
**He said:** "The purpose of learning SEO Best Practice is to use the rules inside a reasonable range."
**ids:** 2092100375239438810
**Related:** SEO edge-work, official-doc modality

---

## G. Named tools and market mechanisms he operationalized (his use, not vendor copy)

### one page, one non-repeating word with search volume
**He said:** "In theory every one of your pages should be able to find a non-repeating keyword that has search volume." "When you make every page, you clearly know what each page is for, and what word it will rank."
**ids:** 2090938323284185332, 2090954259680694666
**Related:** keyword-spreading, Entity

### keyword tool ladder
**He said:** Semrush, Ahrefs; if stronger, Dataforseo; "if you want to refine, hands-on you can use Google Keyword Planner (most accurate on the Google side)"; also Google Keyword Trends. Refresh: lazy = AI + Ahrefs / DataForSEO; traditional = Semrush / Ahrefs; advanced = Trends; detail = funded Google Ads Planner (most accurate volume).
**ids:** 2090954259680694666, 2092448668712645088
**Related:** root keyword, KW Difficulty

### Shopify / Headless / Agentic Shopping
**He said:** From 2026 on, new ecommerce "rush Shopify, you don't need to pick anything else." Two modes: "pure shopify / headless Headless." "Shopify's feed integration is the most perfect." Shopify's development "is related to the Agentic Shopping Google and OpenAI are pushing." Native feed/schema is not enough; second-pass in Merchant Centre.
**ids:** 2091062668056838266, 2089230010616062038, 2091199226856521823
**Related:** product feed, Merchant Centre

### Naver / Yahoo / Bing Webmaster
**He said:** "Outside Japan, Yahoo uses Bing's engine. Japan's Yahoo uses Google. Japan Yahoo plus Bing can take 50% of traffic." "Remember to go to Bing Webmaster and submit your site, about the same as GSC." Korean: "remember to handle Naver. Koreans basically all use Naver." Not doing Naver "the effect is more than cut in half."
**ids:** 2091014853863637176, 2075237380844654947
**Related:** auto-redirect, Google SEO

### zh-HK vs zh-TW
**He said:** Traditional-Chinese export: "remember to think whether you are targeting zh-HK or zh-TW." "When Hong Kong people look at Traditional Chinese, what they read out in their head is Cantonese." "If they read your translation and it does not go smoothly, 100% Drop."
**ids:** 2090743694878290165
**Related:** auto-redirect

### login page (QRG 8.4)
**He said:** QRG section 8.4 / page 83 "specially mentioned how to optimize login pages." Most export / membership / payment sites have one. To reach highest quality: information-protection disclosure; firewall; register / forgot-password complete; whether login is third-party; whether the page is too simple.
**ids:** 2091376367740789153
**Related:** QRG, highest, Quality

### Google Business Profile
**He said:** On a site review: "if you don't have a fixed address, you can also do google business profile"; "missing a contact page (at least leave an email?)." Later procedure: Bing Business + Apple Business; site must have map, address, phone, schema, dedicated Contact; everything in GBP must exist on the site; social + reviews; GBP team ≠ Search team; dirty work.
**ids:** 2039659702192427443, 2092207366305681808
**Related:** Contact Us, About Us, Local

---

## H. He used these as names, almost no "X is…" sentence

These he threw as proper names. Tweets have no definition sentence. No industry meaning filled in.

| Term | How he used it | ids |
|---|---|---|
| Algorithm Recovery | "Starting last year the most delightful thing in the SEO world is that everyone received more Algorithm Recovery consulting business." | 2092067172021608918 |
| Anchor Guest Post | "I have seen sites whose ranking rose after they deleted all the Anchor Guest Post they had done" | 2090396597066899635 |
| parasites | "more reddits, parasites, fake authors after Spam Update"; also "More spam websites, parasite websites, expired domain, AI content abuse, fake authors." | 2037039070371864892, 2037101323024556384 |
| AI content abuse | "More spam websites, parasite websites, expired domain, AI content abuse, fake authors." | 2037101323024556384 |
| Agentic Shopping | Shopify development "is related to the Agentic Shopping Google and OpenAI are pushing" | 2091062668056838266 |
| Headless | Shopify "two modes: pure shopify / headless Headless" | 2091062668056838266 |
| Canonical | "Even if Canonical is done well, it still does not work" (vs m-site) | 2091008050262110227 |
| hreflang / ccTLD | He quotes the Klook JD: "You understand the nuances of international SEO (ccTLDs, Hreflang)" | 2091844216980979877 |
| mobile first | "Google is fully mobile first, and can do JS render" | 2090686787534598639 |
| Knowledge Graph | To understand Entity "refer to the 2012 article Google published about the Knowledge Graph" | 2091185632202883243 |
| non-brand keywords | "non-brand keywords, total keyword count, site traffic dropped to the floor" | 2089165558516437461 |
| user intent | Guessed a miss reason: "not meeting user intent" | 2071958163314925863 |
| sitemap changefreq / priority | "sitemap can delete changefreq and priority" | 2039659702192427443 |
| Ads Forecast | "就是你先要有Root keyword, 然后拿Ads Forcast的数据 一下子全部下载下来" | 2065688886270108027 |
| CRO / PDP / Collection | Shopify time should go to "CRO, product description, PDP design, Collection classification, shooting product photos" | 2091199226856521823 |
| Discover | "Google SEO 包括传统的Search, 电商，Image Search, Video, News, Discover等等。" / News SEO includes "Google Top Stories, Google News, Google Discover 三条线。" | 2091071455350169891, 2091387930963263678 |
| Top Stories | "我在公司里，研究出来了如何排Google Top Stories的方法" / News SEO includes "Google Top Stories, Google News, Google Discover" | 2091729433279496522, 2091387930963263678 |
| inbound / shang'an | "How do you get domestic AI to recommend foreign products? Going overseas said in reverse — inbound?" He does not understand Doubao / Deepseek mechanisms. | 2091716914599067838 |
| attribution | "很多网站如果把归因的东西弄好的话，最先疯的是程序员……第二个疯的是做Google Ads的……第三个就是做不正经SEO的" | 2070785863806837170 |
| brand-term pollution | Google Ads people "mess a pile of brand terms and pollute the data" | 2070785863806837170 |
| Search Intelligence Manager | "Autodesk的这个岗位更有意思，叫Search Intelligence Manager。" | 2091727382726205949 |
| quality raters | "I wonder if the quality raters would give those websites high ratings or low ratings." | 2033312823431049431 |
| staged nofollow | Deindex recovery: "internal links still need staged nofollow" | 2038199743797690529 |
| html language / JS switcher | Site review: "html start has no language defined"; "Chinese and English version switcher is js not a link" | 2039659702192427443 |
| GEO Citations | "I think the KPI of Baidu is to get more GEO Citations." | 2039641960601043096 |

---

## Count

- **Terms with his own definition or operationalized use: 142**
- **Named only, no definition sentence: 25** (table H)
- **Total listed: 167**

Corpus boundary: last full public-post count remains 979; Loki-authored +156 since last cutoff (now 689). Full originals/replies/reposts recount was not rerun.

---

## 2026-08-28 delta (append)

### ranking model
**He said:** "我的模型就是 Ranking = (Techinical Foundation + Quality) * Brand Reputation." Methods he cannot graph, he will not recommend. `[once]`. Not a scorecard.
**ids:** 2093195666847879327

### Language Lock
**He said:** AI Search is still language-isolated. CJK can pull EN citations/fanout. No cross-language summary. To show up on AI platforms, do multilingual. Mechanism + one implication, not a GEO SOP.
**ids:** 2092248676324520232

### SEO captures demand
**He said:** "SEO Capture Demand。SEO Doesnt Create Demand。" No 种草 / no search → many businesses should not start with SEO. Paid can scale on ROAS.
**ids:** 2092387406242787628, 2092380170426765423

### quality four-part
**He said:** First-hand experience + Originality + Non-commodity + Effort (手写，不是AI，费劲心力). Folds into Effort + Original.
**ids:** 2092977176501228007

### author vectors / US10599770B1
**He said:** Bidirectional LinkedIn required — "人家linkedin 没连你，就不算." Patent US10599770B1.
**ids:** 2092468221794513075

### product-first IA
**He said:** On day 1 know each page’s query / title / h1 / url. Do not find keywords then invent pages.
**ids:** 2093181903579087176

### PR 51000 / 47000
**He said:** Leak-adjacent: PR>51000 rare/expensive (uint16 65535); PR<47000 same if not spam; cheap bulk links weak; badbacklinksPenalized; penguinEarlyAnchorProtected.
**ids:** 2092595964888699272, 2092791651349713156, 2092601636241953071

### Screaming Frog (must-have)
**He said:** The one must-have tool; other tools optional. Raw vs rendered. Lumar / Botify = enterprise Frog; skip at mid-size.
**ids:** 2092784685650997342, 2092723929249132561

### site reputation abuse / ghost writing
**He said:** Third-party content machines on a publisher’s authority. He walked a recovery cycle. Do not buy the service.
**ids:** 2092557180755144890

## 2026-08-31 delta (append)

### H1 = ranking query
**He said:** Theoretically every page’s H1 should carry the keyword that page is meant to rank for. Beautiful empty prose / poetic non-entities: “谷歌是看不懂的.”
**ids:** 2093224389605261381, 2093236681449332851

### sameAs
**He said:** “还要反过来连，然后做sameAs.”
**ids:** 2093250660125089901

### IndexNow / Bing routing
**He said:** Do Bing; IndexNow. ChatGPT / Copilot / Yahoo use Bing. “Claude uses Bing, Gemini uses Google, ChatGPT uses Bing.” Engine routing, not a Bing ranking SOP.
**ids:** 2093355461303218245, 2093336738643275842

### CN/overseas TLD split
**He said:** Copy Apple/Canva. Overseas unified `.com` then language/region. China `.com.cn` or `.cn`. Rest to the engines.
**ids:** 2093339633614754128

### internal-link params
**He said:** Do not put tracking parameters on internal links. Anti-crawler / anti-Google. Canonical does not save it in the moment. Clean URL = one ID card.
**ids:** 2094278631296315660

### 千人千面
**He said:** Product wants customized recommendation; “你给爬虫看哪一面？” Cloaking-adjacent.
**ids:** 2094314984310514045

### Crawl Budget Management
**He said:** Enterprise-required (Klook JD). 10 pages ≠ 1M ≠ 10M. Soft 404 is the most important point. No item-by-item playbook.
**ids:** 2093665083486523872

### WordPress (overseas default)
**He said:** `[once]` In overseas Digital Marketing / SEO, WordPress is the default; people who say WP is unusable usually never did overseas SEO. Ecosystem 120% SEO-adapted. Scoped vs Shopify.
**ids:** 2093542304372129882

### Microsoft Clarity
**He said:** Free session heatmap / UI-UX panel. Later Bing GEO dashboard. Tool, not a ranking cause.
**ids:** 2093511886683951613

### spam policy dual track
**He said:** Google spam policy is dual-track: algorithm + Manual Action. Spam costs Google money. Cloaking first named item.
**ids:** 2094335458423742688

### expired domain abuse
**He said:** A domain may carry a topic. Google has expired domain abuse as a spam punishment. Domain should bind to a category.
**ids:** 2093547820808896687

### Language Lock (restated)
**He said:** GEO two languages (non-CN-AI): input language + English. AI will not assemble other languages for you. All brands → multilingual / international SEO. Not a GEO how-to.
**ids:** 2093347878098042898 (plus 2092248676324520232)

## 2026-09-03 delta (append)

### Brave Search / Claude
**He said:** Claude uses Brave Search API. Brave has its own crawler and index. Check not blocking Brave. Brave likely does not render JS so SPA fails — do SSR. Submit URL. No webmaster tool → pure SEO. Tension with earlier Claude→Bing.
**ids:** 2094338319807078577

### IndexNow (Google out)
**He said:** IndexNow lets you push new URLs to some engines. Google does not support it (said three times). Connect Bing, Naver, Yandex. https://www.indexnow.org/
**ids:** 2094396130427900220

### AI Slop (KPI)
**He said:** AI Slop — not that it will not be punished, the time has not come. PSEO junk for short-term KPI then jump ship.
**ids:** 2094431347851055262

### YMYL L = Life
**He said:** The L in YMYL is Life. Google invests in medical search (莆田系 contrast).
**ids:** 2094438099694833690

### LLM.txt (no-regret)
**He said:** Doing LLM.txt is not causal for AI recommendation; doing it will not hurt. Keep Search/AIO ignore + optional for chatbots.
**ids:** 2094440229482721382 (plus 2071840010593358218)

### HCU (must practice)
**He said:** People doing Google SEO must practice HCU (Helpful Content Update). He practiced it on X. Points at article 2094559188676734976. Do not import the article body.
**ids:** 2094576318788833400

### person/social carrier
**He said:** Future SEO may not be only the site — it can be you as the carrier. If site/brand weak, start from social. X-account SEO. Chinese as low-hanging fruit. `[once/experiment]`. Not quit-the-site.
**ids:** 2094615467981930559

### X Articles
**He said:** Logged-out X Articles are blog-like pages, SEO’d, Article schema, isAccessibleForFree. Optional channel.
**ids:** 2094635693993832480

### product /updates log
**He said:** Manus updates pages rank core product queries; not coincidence. A product-update log helps any outbound product (like git commits).
**ids:** 2094710822136418378, 2094711722024325186

### own product (Effort)
**He said:** Your own product is the fastest way to raise Originality and Effort.
**ids:** 2094726807568478504

### SaaS Trust / QRG store
**He said:** QRG Trust for Online Stores: secure payment + reliable customer service. SaaS is part of online stores. Stripe mention/logo; Trust/Help/Contact. DNA of a real product.
**ids:** 2094935978851078531

### FAQ (not every page)
**He said:** Google dropped FAQ rich results. Don’t FAQ every page/blog. FAQ is for user questions (buying). Service/product maybe; blogs usually not. Intuition.
**ids:** 2095122990493282767, 2095157057255268605, 2095157590301061376

### ecommerce auto-blogs / Shopify vs K
**He said:** 3–4 CN electronics cross-border Shopify sites auto-blogging were Spam Hit. Blogs OK only for product/feature/own Guide. Shopify better ecommerce architecture; being K’d is the domain.
**ids:** 2095159020072124578, 2095320035690725505, 2095344173826363791

### PageSpeed (after product+content)
**He said:** PageSpeed only matters when you already have good product and content. PageSpeed does not improve content. Content is the ranking key. Authority is another layer.
**ids:** 2095287266247836131, 2095288889506443712

### fake as hard as real
**He said:** Faking authors/profiles is as hard as doing it real. Expert-as-author needs a real Profile. YMYL money/health/web3.
**ids:** 2095347481655840877, 2095348801607491906

### handwritten dry-goods experiment
**He said:** 10 days to 5000 followers. Pure handwritten dry goods still get seen. Light `[asserted]`, not a growth SOP.
**ids:** 2094551785461764302
