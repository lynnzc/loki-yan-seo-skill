# Dimension: cases, war stories, talks, leaks, named sites

Source: `@loki_yan_seo` tweets only (`/workspace/loki-yan/corpus.md`, `/workspace/loki-yan/corpus.json`). 978 items in the dump (532 from him: 129 posts, 403 replies; 24 reposts ignored; 446 are other people's tweets in the same threads). No blog. No decks. No prior skill.

A **case** here is a named incident: a client or prospect disaster, an experiment with a before/after, a talk he gave or sat, a leak he tore down, a specific site or keyword he worked, or a question he put to Gary / Google staff.

**Proof** is only what the tweet itself contains.

- **in-corpus** — named hosts, URLs, titles, leak field names, slide sentences, counts he publishes.
- **partial** — some of those artifacts, but the outcome or the data is not in the tweet.
- **asserted** — “I saw / I tested / I processed / they came to me.” No artifact in-corpus.

Tips that only name a brand as a slogan (Apple = copy this, Shopify = use this) are not cases unless he did work on them. Brighton SEO’s free deck library is a resource pointer, not a case.

**Case count: 40** (39 standalone incidents + 1 minor-notes cluster).

---

## The 8 he most often cites as proof

These are the receipts he reaches for when a thesis needs a body. Ranked by reuse across tweets, not by likes.

| # | Case | Why it is a receipt | Proof | Primary ids |
|---|---|---|---|---|
| 1 | Content Warehouse API leak (`siteFocus` / `siteRadius` / `contentEffort`) | He calls it “数据验证.” Three separate posts mine the same 2024-03 dump. Effort is the EEAT door; focus/radius is the stay-vertical door. | in-corpus for field names and his reading; asserted that they cause rank | 2091894056687431704, 2092090944648581505, 2090291222556578070 |
| 2 | Search Central Live circuit + questions to Gary / Google staff | Four cities he attended. Official-mouth quotes. Two live questions (Gary on effort; unnamed staff on Gemini). | partial — quotes and questions in-corpus; no slide images; he forgot Gary’s exact words | 2092090944648581505, 2088131678065852712, 2091364706703581191, 2091362717907251353, 2091353930425127142, 2091487107806323136, 2092027807719444899 |
| 3 | Alibaba AIGC + fake-author matrix | Later reduced to one line: “假作者长什么样？你参考阿里就可以了。” Full host list earlier. Recycled against Baidu Wiki quality. | in-corpus for the host inventory and the 5.9M product-insights kill; asserted 10M+ pages and “agent” | 2037884887307526631, 2091739865121783923, 2039641960601043096 |
| 4 | US in-house affiliate: Angular Soft-404, DA 30 vs 80+, SRA, $20K/mo links, SCL speaker slot | His “临床” origin story. The render fix is the before/after. The link-budget stop is the second before/after. Extra color: it was YMYL, and “DR, 外链都没用.” | asserted — no site name, no chart, no GSC | 2091301352463102268, 2090685656079241520, 2088623359366209644, 2037884887307526631 |
| 5 | His news site + “just do traditional SEO, ChatGPT rose” | Ongoing self-experiment. No blogs, no Reddit, no schema, no PR, no FAQ. Hand-shot photos. $10K domain. | asserted — “数据也很有意义” / “ChatGPT来的流量就涨了,” no numbers | 2088803453565059194, 2064883047825395749, 2079109647160734202 |
| 6 | Zhihu `robots.txt` — overnight Google traffic death | The audit-order receipt. He uses it whenever ranking collapses: first `robots.txt`, then crawl status. | partial — named site, Semrush as the tool, a “picture” he says shows the revert. Picture is not in the text. | 2091795112745689273 |
| 7 | 逐玉 / Pursuit of Jade — WeTV loses its own show on title | Recycled at Ahrefs Evolve Singapore with SEA friends. The three titles are the body. | in-corpus for the three URLs and the three titles; asserted that this is *why* WeTV lost | 2091682678261375106 |
| 8 | 11.5M-euro casino affiliate — EEAT Trust death | He frames it as a “著名案例.” “为啥我知道？因为来找我买过.” The Trust-hole receipt. | asserted — no domain, no chart, no sale listing | 2090697074153283687 |

Close runners he also deploys as proof, but once each: Ameba / Kimura noindex at billion scale (2092027807719444899), 2023 Top Stories playbook (2091729433279496522), Shenzhen double-rebrand migration (2091309003397902703), Wirecutter’s 150 named editors (2090735573443158517).

---

## A. Leak teardowns

### 1. Content Warehouse: `siteFocusScore` / `siteRadius` / topical authority

**Type:** leak teardown
**When:** he dates the dump to 2024-03. Tweet 2026-08-24 (CST).
**Ids:** 2091894056687431704 (main), 2090291222556578070 (Site Focus applied to About Us), 2091895491982405998 (one-line restatement)

**What happened:** Google “误将 Content Warehouse API 的内部代码文档开源到 Github.” He states 2500 pages, 14,000 ranking-related files. He opens one block: `QualityAuthorityTopicEmbeddingsVersionedItem`. Fields he names: `siteFocusScore`, `siteRadius`, page/site `embedding`.

His gloss: `siteFocusScore` = vertical focus; `pageEmbedding` = page topic vector; `siteRadius` = how far page vectors sit from `siteEmbedding`. Small radius = tight topic. SEO blogger who starts posting 唱跳 Rap on the same host → focus down, radius up.

**He claims it proves:** topical authority / EEAT-A is a computed site-wide thing, not a vibe. Vertical sites win. “千万不要东做一点，西做一点，乱铺内容，要stay focus.” High DA cannot rank a travel page on an SEO-About-Us site because Site Focus forbids it. About Us “定性” the brand. He says this theory sits on the 2024 Site Reputation Abuse update *plus* the Warehouse leak as “数据验证.”

**Proof:** **in-corpus** for the leak date, page count, block name, and three field names. **asserted** that these fields decide rank, and that his 唱跳-Rap / SEO-vs-travel examples would move the scores. The 2024 SRA update is invoked as the other half of the About-Us theory — not shown.

---

### 2. Content Warehouse: `contentEffort`, plus the question to Gary

**Type:** leak teardown + question to Gary
**When:** he says he chased Effort from 2025-08 Bangkok to 2026-05 Shanghai. Tweets 2026-08-14 and 2026-08-25 (CST).
**Ids:** 2092090944648581505 (main), 2092095823731462302 (Effort + Originality as the EEAT door), 2088131678065852712 (English retell to Cyrus Shepard)

**What happened:** At the Shanghai Google event he asked Gary: about EEAT / Quality Rater Guidelines, does Google have an algorithm that runs automatically? How would effort be measured automatically?

Gary “没有特别正面.” Loki forgot the exact words. The gist he kept, in two languages: “mathematic calculation” / “there's ‘mathematic calculation’ for those ‘things’ mentioned on the EEAT Guideline.”

Then he opened the Warehouse dump and found: `contentEffort - LLM-based effort estimation for article pages`.

He is not an ML engineer. He still lists five things he would code if he were: AI template/structure; paraphrase of top-10/20; unique entities/params; original vs AI images/video; Information Gain (has this appeared before).

**He claims it proves:** Effort is computable, therefore original text / photos / video / takes are `contentEffort`, therefore they raise SEO. Batch without increment = low effort = “被干.” Generic SEO automation cannot cross Effort + Originality by spending tokens. “你要不把我蒸馏了。”

**Proof:** **in-corpus** for the field name + one-line definition, and for the fact of the Gary question (told twice). **partial** for Gary’s answer (admitted paraphrase). **asserted** that raising `contentEffort` raises SEO, and that his five coding guesses are how Google would do it.

---

### 3. Google Cloud AI Image Detection as a `contentEffort` analog

**Type:** leak-adjacent inference (named Cloud API, not the Warehouse dump)
**When:** 2026-08-25 (CST), same morning as the Effort post.
**Ids:** 2092100375239438810

**What happened:** He says a lot of what Google Search / Gemini uses “说不定会有” inside Google Cloud. Example: the AI Image Detection API. Even if it does not punish you, “你contentEffort分数一定不会是 正 的.” He pastes `https://docs.cloud.google.com/gemini-enterprise-agent-platform/models/ai-content-detection`. Advice: hire a sharp intern, give them a Canva account, make images by hand. US friends should ask ex-Googlers what systems they built.

**He claims it proves:** Best Practice is using the published rules inside the lines. AI images are a negative (or at least non-positive) effort signal. Human-made images are the cheap fix.

**Proof:** **in-corpus** for the Cloud docs URL. **asserted** that Search/Gemini uses this API, and that detected-AI images force `contentEffort` off positive. No site, no score, no GSC.

---

### 4. Navboost leak vs AI Overview / AI Mode zero-click

**Type:** leak teardown (paradox, not a field-by-field read)
**When:** 2026-06-12 (CST).
**Ids:** 2065232184374645078

**What happened:** He recalls the Navboost leak: foundation is user clicks and search journeys. AI Overviews and AI Mode are “inherently Zero-Click.” If users do not click out, Navboost’s primary data “completely dries up.”

Two possibilities he offers: (1) Navboost theories are obsolete for generative search, replaced by semantic/vector validation; (2) Google swapped clicks for micro-behaviors (hover, dwell, query steps). Then: does Navboost even exist? If it does, did they change it?

**He claims it proves:** the click-based Navboost story does not fit AI Mode. He does not pick a side.

**Proof:** **asserted** recall of the leak. No field names, no docs, no measurements in-corpus. The paradox is the case.

---

## B. Talks, hallway stories, questions to Google staff

### 5. Search Central Live Shanghai: Gemini is not Search (asked official staff)

**Type:** talk recap + question to Google staff
**When:** SCL Shanghai (he also says 2026-05 for the slide). Tweet 2026-08-23 (CST).
**Ids:** 2091364706703581191 (main), 2091071455350169891 (same split, shorter)

**What happened:** He had not written the Shanghai recap. Then he did.

Google’s three boxes as he wrote them down:

1. Traditional Search — crawl, index, serve.
2. AI Mode / AI Overview — crawl and index “完全一致” with traditional Search. Serve adds Grounding on Search Index Query Fanout. Same database.
3. Gemini — “uses crawlers for data,” different crawler, indexing “Not part of search.”

“我在上海特地问了谷歌官方人员，Gemini 是不归 Search部门管的，他们是不同的部门。”

**He claims it proves:** optimizing Google SEO and AIO is the same job. Optimizing Gemini can *borrow* SEO theory because the infra rhymes, but Search-team docs do not cover Gemini. This is why Western SEOs say “Google GEO is SEO.” Anything that enters via Google.com (Search, ecommerce, Image, Video, News, Discover, AIO, AI Mode) is Search; Gemini itself is not.

**Proof:** **partial** — the three-way split and the staff answer are in the tweet. He says it is the official slide. No slide image in-corpus. Staff unnamed.

---

### 6. Four Search Central Lives: Bangkok / Hong Kong / Shanghai / Sydney — effort, then “humans for humans”

**Type:** talk recap (four events)
**When:** 2025 Bangkok, 2025 HK, 2026 Shanghai, Sydney. “我都去了.” Tweet 2026-08-23 (CST).
**Ids:** 2091362717907251353

**What happened:** All four events said they do not care if content is AI-created, as long as it has effort, helpful, original (HCU). Shanghai then added, as he quotes the 2026-05 official slide:

> 由于基于机器学习的排名算和信号是用“人类为人类创作的内容”训练出来的
> 他们天然更注重用户体验。因此，它们能更好地理解并推荐那些自然、优质的内容

**He claims it proves:** rankable content is (1) close to human, (2) has Quality, (3) Quality = Effort + Original. AI that fakes those three can rank. AI blog factories exist *in order not to spend effort while pretending to be original.*

**Proof:** **partial** — he quotes the Shanghai sentences and names four events. No decks in-corpus. “Original ≠ 缝合” is his gloss.

---

### 7. Search Central Live Shanghai PPT: Quality is a ranking factor, site-wide

**Type:** talk recap
**When:** Shanghai official PPT. Tweet 2026-08-23 (CST).
**Ids:** 2091353930425127142

**What happened:** He says Google first called Quality a ranking factor in 2025. Quality is a site-wide signal. Opposite is Spam. Quality < competitor → you lose.

Quality examples he gives: every product photo shot on a DSLR, every alt and description written by hand. Spam example: an AI agent that stitches other sites.

**He claims it proves:** the SEO job after 2025 is site-wide Quality (UX, content, CWV, all of QRG), not page-level tricks. Spam on the site taxes the whole Quality score.

**Proof:** **partial** — he says “这个是…官方PPT” and restates it. No PPT in-corpus. The DSLR / agent examples are his.

---

### 8. Search Central Live North America: Non-commodity Content (then his own X as the demo)

**Type:** talk citation + his experiment
**When:** “今年谷歌在北美的 Search Central Live 第一次提到.” Tweet 2026-08-23 (CST).
**Ids:** 2091487107806323136

**What happened:** Google said AI Search prefers Non-commodity Content. Commodity = 大宗商品化 / 高度同质化. His commodity examples: “做SEO一定要做外链,” “DA不够所以没有排名,” “写博客铺词,” “做GEO一定要做Reddit.” Non-commodity = 独家经验, 独特视角, cannot be replaced by a generic knowledge base.

He then uses his own account as the before/after: 2 days, 30/100 fans → 500 / 1.7K followers, after talking to @GoSailGlobal. He says every claim he posted had a concrete instance, all handwritten, “Token买不来情感波动.”

**He claims it proves:** AI Search likes non-commodity; automation cannot produce it without a human first distilled. Sincerity is the social-and-SEO kill shot. His follower spike is the receipt.

**Proof:** **partial** for the Google definition (his paraphrase, no slide). **asserted** for the follower counts and the causal link (non-commodity → engage → followers). No screenshot in the text.

---

### 9. Search Central Live Deep Dive: Kimura / Ameba Blog, plus the Sydney cigarette

**Type:** talk he sat + origin story
**When:** “去年” SCL Deep Dive; later a Sydney SEO Conference afterparty. Tweet 2026-08-25 (CST).
**Ids:** 2092027807719444899

**What happened:** He met Japanese SEOs at SCL Deep Dive. Best talk: @kimuyan, SEO Director at listed CyberAgent, 20+ years, on Ameba Blog (“日本的微博？小红书？”).

Numbers he wrote down: 92 million blogs, 2.8 billion articles, 5 billion page views, 500 million search traffic.

Quality problem at that scale: they built an internal ML spam filter, classified posts for Quality / Spam, and **noindexed** low-quality / AI slop / spam.

Hallway story: at the Sydney afterparty he clocked Kimura as a smoker, handed him a cigarette, and they have talked at every offline event since, via Google + ChatGPT translation.

**He claims it proves:** 100-page, 1M-page, and billion-page sites need different strategies. At Ameba scale, Quality is a site-wide spam-filter problem, not “write more.” Also: go to conferences so you can have these conversations. Japanese SEO JDs are “上路.”

**Proof:** **in-corpus** for the four Ameba numbers and the noindex mechanism as he recorded them. **asserted** that this is how they run it (he is retelling a talk). Cigarette story is asserted color.

---

### 10. Bangkok Google Conference: Al Jazeera news-SEO talk, then the Chinese subdomain dies

**Type:** talk he sat + later site death
**When:** talk “去年7月” Bangkok. Death noticed 2026-03-20 (CST).
**Ids:** 2034784854009946123

**What happened:** At Bangkok he heard Al Jazeera’s SEO talk and thought their news SEO was “特别好.” Later `https://chinese.aljazeera.net/` is gone; the whole subdomain 301s to elsewhere. He asks if anyone knows why.

**He claims it proves:** nothing causal. It is a question, not a moral. Implicit: even a site whose news SEO impressed him at SCL can shut a language folder.

**Proof:** **in-corpus** that he names the host and the 301. **asserted** that the Bangkok talk was good. No crawl log, no GSC, no reason.

---

### 11. Ahrefs Evolve Singapore 2026 — he is speaking

**Type:** talk he gave / will give
**When:** announced 2026-03-16 (CST). Later tweets treat Evolve as already happened (“今年在 Ahrefs Evolve Singapore 的时候”).
**Ids:** 2033414646775083406 (announcement), 2091716914599067838 and 2091682678261375106 (hallway, after)

**What happened:** Title: *Rebuilding for the Machine: A “Day 0” Framework for AI Inclusion.* Thesis in the announcement: most APAC brands do not have an authority problem, they have a technical one. Expertise / products / story exist; digital foundations were never built for machine interpretation. Session = traditional Technical SEO × AI Search, “not in theory, but in practice.”

**He claims it proves:** AI invisibility is a Day-0 machine-readability failure, not a missing-DA failure.

**Proof:** **in-corpus** for the title and the thesis as advertised. **asserted** that this is what actually happens to APAC brands. No deck, no case studies from the talk itself in-corpus. The tweet does not contain Day-0 steps.

---

### 12. Ahrefs Evolve hallway: how do we get 豆包 / Deepseek to recommend us?

**Type:** hallway questions (he was asked)
**When:** Ahrefs Evolve Singapore. Tweet 2026-08-24 (CST).
**Ids:** 2091716914599067838

**What happened:** Foreign SEOs asked him how to get Doubao and Deepseek to recommend them. Example queries they cared about: 去泰国旅游推荐哪家免税店, 去日本旅游买什么伴手礼, 去澳洲旅游买什么酒. He does not understand Doubao / Deepseek yet. He floats “反向代理一波” and jokes that the inverse of 出海 is 上岸.

**He claims it proves:** Chinese GEO is already a foreign demand. The opportunity is getting domestic models to recommend foreign products.

**Proof:** **asserted** that those conversations happened. No names, no transcripts.

---

### 13. Shenzhen SEO Conference: leaked login-page talk, 5-keyword test, impossible triangle

**Type:** talk he was preparing (@shenzhenseoconf)
**When:** PPT week of 2026-08-20. “谍照” 2026-08-23 (CST). He also told Lily Ray he planned to cover a topic in Shenzhen (2081865732271550669).
**Ids:** 2091376367740789153 (login page / QRG 8.4), 2090684152328945976 (5-group KW research), 2090567084933787767 (Scale / Quality / Speed)

**What happened:**

1. He posted a spy-photo version of a Shenzhen talk. QRG 182 pages, section 8.4 p.83, login-page case. Highest-quality login, as he lists it: privacy disclosure, firewall, full register + password reset, not a thin third-party login.
2. Writing the PPT he ran “SEO Research”: when sites are all 神仙打架, `{品牌+关键字}` search volume and that page’s rank are “基本上是线性的一致关系.” He tested 5 keyword groups. Same shape.
3. Same PPT week: SEO 不可能三角 = Scale, Quality, Speed. You cannot have all three without spending money.

**He claims it proves:** (1) QRG-highest is operational, including login. (2) At the top, brand+KW demand ≈ rank. (3) You pay for the third vertex.

**Proof:** **partial** for the QRG cite (section/page in-corpus, Google’s own case not reproduced). **asserted** for the 5-group test (no keywords, no table). The triangle is a concept, not a measured case.

---

## C. Named-site teardowns and disasters

### 14. Zhihu `robots.txt` — overnight Google traffic death

**Type:** public disaster he diagnosed (and wrote on 小红书 two years earlier)
**When:** original 小红书 post ~2024. Recap tweet 2026-08-24 (CST).
**Ids:** 2091795112745689273

**What happened:** A giant site blocked all crawlers in `robots.txt`. Timing: AI boom, Google–Reddit deal. He noticed because Chinese Google SERPs that “永远都是知乎” suddenly had no Zhihu. Semrush confirmed `robots.txt`. He published. “从这个图片上基本上可以看到发帖以后没多久，他们把 robots.txt 给改回去了.” Recovery is only now trending. He does not know if the damage was fatal or if something else capped the rebound. Zhihu also runs Adsense — he thinks they left free overseas-Chinese traffic on the table.

**He claims it proves:** on a ranking collapse, audit order is (1) `robots.txt` (2) crawl status. `robots.txt` can zero a giant.

**Proof:** **partial** — named site, Semrush as the tool, a “picture” he says shows the revert. Picture is not in the text corpus. Causal “my post made them revert” is asserted. “危害是不是致命的…不得而知.”

---

### 15. Alibaba: 10M+ AI pages, fake authors, subdomain massacre

**Type:** leak-style teardown of a live site
**When:** matrix from “十一月.” Teardown 2026-03-28 (CST). Later used as the fake-author poster child, 2026-08-24 (CST).
**Ids:** 2037884887307526631 (inventory), 2091739865121783923 (“你参考阿里就可以了”), 2037898118898012638 / 2038013959954153823 (replies: all auto, fake authors, soft 404), 2039641960601043096 (Baidu Wiki “much better than Alibaba.com’s 10M AI Pages”)

**What happened:** He estimates Alibaba’s full-AI + fake-author matrix at **10M+ pages, conservative**, “跑了什么 Agent.” “这个 Agent 没有读过 E-E-A-T 和谷歌的 Policy.” First spotted by an Indian guy on LinkedIn.

`/product-insights/*` already dead. “昨天还有 5.9M 个收录页面.”

His live/dead list at publish time:

| host | status | extra |
|---|---|---|
| bigbird.alibaba.com | still up | birds |
| wellness.alibaba.com | gone | Semrush peak 1.6 traffic, 1.4M keywords |
| sportssurge.alibaba.com | gone | |
| diy.alibaba.com | gone | |
| reads.alibaba.com | gone | |
| plantin.alibaba.com | still up | |
| party.alibaba.com | gone | |
| catlovers.alibaba.com | still up | |
| carinterior.alibaba.com | still up | |
| lifetips.alibaba.com | still up | |
| smartbuy.alibaba.com | still up | |
| alibaba.com/supplier/guide/ | still up | |

He forgot to screenshot the afternoon state. Semrush / Ahrefs should still show the old ranks. Semrush showed a lot of this AIGC cited in AI Overviews; he expects Google to act. He wonders if the manual action will be site-wide. He adds Alibaba is “机会都是 soft 404”; flipping them to HTTP 404 might “网站会蹦.”

**He claims it proves:** fake authors + AI volume at scale get killed. EEAT/policy-blind agents are how you manufacture a 10M-page liability. SRA / fake-author is a domain-level Trust event, not a folder event. If you must batch, use Organization as author (`@type: Organization` + name + url), not invented people. If AIGC gets you hit, delete it.

**Proof:** **in-corpus** for the host list, the 5.9M product-insights number, wellness Semrush peak. **asserted** for 10M+, “agent,” AIO citations, and that his US-SRA 404 playbook is the analog. No screenshots in the text.

---

### 16. 逐玉 / Pursuit of Jade — WeTV loses its own show on title

**Type:** keyword / SERP teardown; also used as an Evolve hallway example
**When:** “今年” his wife searched 逐玉. Recycled at Ahrefs Evolve Singapore. Tweet 2026-08-24 (CST).
**Ids:** 2091682678261375106

**What happened:** Wife asked where to watch 逐玉. Google SERP: 爱壹帆, 爱奇艺, Netflix, YouTube. Tencent as co-producer is missing or buried. Peak-window traffic went to those four, not to WeTV paid users.

At Evolve he used the same example with Indonesian / Filipino / Thai / Singapore friends. Query `pursuit of jade` in SEA: iQIYI and Netflix on top, WeTV below. “你自家的出品的东西，你排名都不在上面.”

He published the three URLs and the titles:

- Netflix: `<title>观看《逐玉》</title>` / `<title>Watch Pursuit of Jade</title>`
- iQIYI: `<title>逐玉 (2026) 全集 带字幕 –爱奇艺 iQIYI | iQ com</title>`
- WeTV: a long generic platform title about 免費觀看國產劇、韓劇… No show name.

He reads WeTV as duplicated default title, or a front-end that calls a default title at render. Also: people search with verbs (在线 / 免费 / 观看 / watch) — those should be in the title.

**He claims it proves:** page title is not a tip, it is the reason you lose your own product to pirates. Own-brand window is perishable.

**Proof:** **in-corpus** for the three URLs and the three titles. **asserted** that this is *why* WeTV lost (he does not show rank history, GSC, or a title-fix after). The wife story is color.

---

### 17. 11.5M-euro casino affiliate — EEAT Trust death

**Type:** client / prospect disaster
**When:** site sold 2017 for 11.5M euro. Crushed from 2023 algo updates. “现在直接蹦没了.” Tweet 2026-08-21 (CST).
**Ids:** 2090697074153283687

**What happened:** A “著名案例.” The whole stack was links, fake authors, spam, garbage content — “欧洲打法.” After 2023 they tried to recover EEAT by buying more links, posting more blogs, making more fake authors. Site is gone. “为啥我知道？因为来找我买过 lol.”

**He claims it proves:** an EEAT Trust hole is fatal. You cannot patch Trust with the same spam that dug it.

**Proof:** **asserted.** No domain, no chart, no sale listing. The 11.5M figure and “他们来买过” are his. He frames it as famous, not as a teardown he published.

---

### 18. Shenzhen 出海 company — two rebrands, no migration, traffic crash

**Type:** client-adjacent war story (dinner with their PM)
**When:** “去年” Shenzhen dinner. Tweet 2026-08-23 (CST).
**Ids:** 2091309003397902703

**What happened:** Head 出海 company’s PM. One subdomain, two Re-brands in a short window, migration not done, traffic 暴跌. He generalizes: rebuild / rebrand / product rewrite regularly 崩流量 because (1) devs skip 301, (2) 301 must be 1:1, (3) you must version-control every URL, (4) Google has a standard migration process, (5) one sloppy URL/domain change can wipe years, (6) do an SEO review before the boss / product / design “说改就改,” or you own the bag.

**He claims it proves:** Site Migration is the most technical SEO job, and skipping it is how leadership sites die.

**Proof:** **asserted.** Company unnamed, subdomain unnamed, no before/after numbers. The Google migration doc URL is in the tweet; that is a citation, not proof of *this* crash.

---

### 19. Two 小红书 “AI SEO blog automation” sites — cliff from last December

**Type:** observed disaster
**When:** noticed 2026-03-20 (CST); drop “从去年12月.”
**Ids:** 2034868852602151058

**What happened:** Two sites that had been pushing AI SEO blog automation on Xiaohongshu started a 断崖 ranking drop from December.

**He claims it proves:** the people selling AI-SEO tools do not understand EEAT, YMYL, HCU.

**Proof:** **asserted.** No names, no charts, no URLs.

---

### 20. Domestic head DTC brands — AI batch blogs, traffic 腰斩

**Type:** observed disaster
**When:** “今年.” Tweet 2026-06-26 (CST).
**Ids:** 2070420648900403202

**What happened:** “我已经看到不止一家 国内头部的DTC大牌子搞这个事情，今年流量直接腰斩了。” “This” = AI batch-generated blogs, sold as SEO/GEO help.

**He claims it proves:** mass AI blogs cannot help SEO or GEO from CS / AI / ML / math. Users do not buy because of a generated article.

**Proof:** **asserted.** Brands unnamed. “腰斩” is his word, no numbers.

---

### 21. Unnamed site — non-brand KWs, KW count, traffic to the floor

**Type:** observed / implied-client disaster
**When:** 2026-08-17 (CST).
**Ids:** 2089165558516437461

**What happened:** Non-brand keywords, keyword count, and traffic all “掉到到谷底.” He does not name the site.

**He claims it proves:** site authority cannot cancel AI spam / AI slop / junk blogs. 铺词 and 铺内容 are 伪命题. One bad decision can wreck traffic and the business for a long time.

**Proof:** **asserted.** No host, no chart. This is the exhibit he points at, not a teardown.

---

### 22. Canva — 200+ SEO bodies, hiring map, KW Difficulty as troop count

**Type:** specific-site competitive case
**When:** 2026-08-23 (CST).
**Ids:** 2091668405367791619, also 2091321150127366357 (Canva / Zillow / Booking as “maintain leadership”)

**What happened:** Canva is #1 / #2 on many country × language keywords. He estimates the global SEO-related team (content included) at 200+. Careers page is hiring SEO in Italy, Japan, Korea, Malaysia, Argentina, Spain. He publishes `https://www.lifeatcanva.com/en/jobs/?search=SEO`.

Same week, with his partner: two kinds of SEO. Growth SEO (rank, traffic, convert). Leadership SEO at Canva / Zillow / Booking = risk control — stop other teams from shipping traffic-killing changes, because that moves the stock.

**He claims it proves:** KW Difficulty is opponent ammo, not word hardness. A fireteam cannot take a battalion. “你老板莫不是战犯，派你去送死？” Enterprise SEO at those brands is 守江山, not 打江山.

**Proof:** **in-corpus** for the careers URL and the country list. **asserted** for “200+” and for “#1/#2 in many markets.” No keyword table.

---

### 23. Klook JD — enterprise SEO as culture, not magic

**Type:** specific-site (he uses the JD as the case)
**When:** posted 2026-08-24 (CST); he says he has shared this JD many times.
**Ids:** 2091844216980979877 (DNA block), 2091060807065117104 (Klook SEO Director as the hexagon)

**What happened:** He keeps pasting Klook’s SEO JD. Reason: “Klook 在SEO的表现真的很强。是真的真的真的花了很多功夫.” The DNA block he quotes: Evangelist (crawl budget to C-level, business value to junior dev); “Data-Driven, Not Voodoo”; global (ccTLD, hreflang, Naver, Yahoo! Japan). Link: `https://www.linkedin.com/jobs/view/4402241924/`

**He claims it proves:** real enterprise SEO is hypothesis → test → measure → iterate, because the algo is a black box. Serious orgs do not hire people to “write blogs and build links.” The job sits between marketing, product, and engineering. Named companies and agencies he can think of do not staff “write blogs and do links.”

**Proof:** **in-corpus** for the JD excerpt and URL. **asserted** that Klook’s SEO is “真的很强” — no traffic, no rank, no before/after.

---

### 24. Wirecutter — 150 named editors, $75.5M in one Q2

**Type:** specific-site counter-case to “replace writers with AI”
**When:** 2026-08-21 (CST).
**Ids:** 2090735573443158517

**What happened:** Wirecutter, US head content-affiliate. Q2 revenue he states: $75.5M. NYT bought it in 2016 for $30M. 150+ editors. At $100K fully loaded, that is a huge payroll. Why not fire 100 and stand up an AI agent to “write high-quality content” and save ~$10M?

**He claims it proves:** the moat *is* those 150 named, experienced people. SEO assets are brand and people. Big companies already know how to cut cost; they do not cut this.

**Proof:** **partial** — the $75.5M / $30M / 150+ figures are stated as fact, no source link in the tweet. Causal “they don’t use AI because of EEAT” is his inference.

---

### 25. Feishu — no `.app`, and a JD “内行一看就知道是不对的”

**Type:** specific-site miss (two small hits, one case)
**When:** 2026-08-22 / 08-23 (CST).
**Ids:** 2091492121186635988 (`.app`), 2091542149083041998 (“好玩的动作”), 2091060807065117104 (JD)

**What happened:** Companies forget to buy `.app` when they buy the site. Example: FEISHU. He later says if you cannot get `.com`, `.app` is still a defensive play, and Feishu can be used for “好玩” moves. Separately: do not study 国内巨头 JDs; 飞书’s SEO JD is wrong on sight.

**He claims it proves:** `.app` is a second store-profile backlink (App Store + Play) and a memorable name. Domestic giant JDs are not a syllabus.

**Proof:** **asserted** that Feishu missed `.app` and that the JD is wrong. He does not paste the JD or show `feishu.app`.

---

### 26. Soft 404 — even LinkedIn; Google spent a year saying it at every conference

**Type:** specific-site + conference chorus
**When:** “去年整整一年谷歌在所有 conference.” Tweet 2026-08-23 (CST).
**Ids:** 2091349098553295075 (also the Angular Soft-404 in 2091301352463102268)

**What happened:** Soft 404 = error template, HTTP 200. Google hammered crawl-budget Soft 404 at conferences for a full year. Side effects he names: (1) crawl budget burned on empty 200s, so the pages you need crawled starve; (2) if title/h1 are taken from the URL, blackhats mint indexable junk via PBN, spam score up. “越大的网站越会发生这种问题，linkedin 也没办法避免.”

**He claims it proves:** a thing Google repeats for a year is a landmine. Soft 404 is how big sites get both under-crawled and spam-scored.

**Proof:** **asserted** that LinkedIn has it, and that Google said this at “所有 conference.” No LinkedIn URL, no GSC screenshot.

---

### 27. Expired YMYL domains used to rank Casino / Web3

**Type:** observed black-hat pattern
**When:** “Covid 之后囤了一批.” Tweet 2026-08-22 (CST).
**Ids:** 2091011325438955723 (also the pre-buy hygiene tip 2064981657497813013)

**What happened:** Affiliate players buy expired domains and, on algo-update timing, rank expensive keywords. He has seen Gov / Clinic / Medical / Restaurant / Education sites used to rank Casino and Web3. He thinks they stockpiled after Covid.

**He claims it proves:** the YMYL gate is bound to the *domain*, not a sandbox. Domain = stored good (or bad) data, not just a name. Buy-side hygiene: Semrush / Ahrefs / Majestic for links, Semrush / Ahrefs / SimilarWeb for traffic, Wayback for past life. Spam / PBN / 黄赌毒 history = hell-level start.

**Proof:** **asserted.** No domains, no SERP, no dates. The hygiene method is in-corpus as a procedure, not as a worked example.

---

### 28. Reddit auto-translated Chinese ranking high

**Type:** SERP observation
**When:** “最近.” Tweet 2026-08-22 (CST).
**Ids:** 2091013621790716336

**What happened:** He keeps seeing Reddit threads auto-translated into Chinese ranking well. He calls it 扯淡. Broader point: Reddit-as-GEO is the old link-building logic — one algo change breaks the whole model. Still useful outside English, especially 简中, because 90%+ of the good Chinese web is invisible to Google/Bing.

**He claims it proves:** translated Reddit occupying Chinese SERPs is a symptom of a closed domestic corpus, not a strategy you should copy.

**Proof:** **asserted.** No query, no URL.

---

### 29. 315 / 莆田系 — GEO as the new bought entrance

**Type:** historical case he maps onto GEO
**When:** 315晚会 called out domestic “GEO技术.” Tweet 2026-03-16 (CST).
**Ids:** 2033335605925654664 (also short replies 2033324298694455330, 2033322311051575534, 2033321100848095548)

**What happened:** 315 put “GEO技术” on stage. He maps it to 百度莆田系: when the entrance concentrates, someone buys it. Search → feeds → now the AI answer layer. Replies: even if the surface is banned, dark channels at big companies can still sell it; poisoning is easy to close if a model team wants to; 315 may trigger measures, but domestic models have no EEAT frame.

**He claims it proves:** GEO will not die; it will split white / black like SEO. Helping a model understand you ≠ making a model prefer you. Gemini / AI Mode / AIO are harder to poison because of EEAT; ChatGPT and Claude “毒抗” also got better. Question: will the two GEOs become 百度 vs 谷歌 again?

**Proof:** **asserted** mapping. 315 and 莆田 are public history; he does not show a GEO-poison case he worked.

---

## D. His clinical work, clients, own experiments, before/after

### 30. Three 悟道 — especially the US affiliate Angular Soft-404, and the SCL speaker slot

**Type:** career war story / before-after
**When:** 悟道 1 = ~2017 master’s workshop. 悟道 2–3 = agency → US in-house affiliate years. Tweet 2026-08-23 (CST).
**Ids:** 2091301352463102268 (also 2033383720305230314: “过去三年在美国市场做过最难的几个 SEO Niche”; 2091900022115938340: the work he knew was “best hotels” style affiliate listicles)

**What happened:**

1. 2017 workshop + his IT background (React / Angular). Technical SEO is the foundation: crawl budget, render, CWV on fat data sites. “临床” — if you can do Tech SEO you can get a decent job.
2. In-house US affiliate. Their DA ~30. Competitors average 80+, backlink graphs at billion scale, century-old media brands. He lived a full Site Reputation Abuse cycle. The site was Angular. Google timed out on render → pages went Soft 404. **Fixing that render problem “让网站流量一下子冲了上去.”** Then: DA is a *result*, not a cause. That clinical year “把我送上了 Google Search Central Live 做了 Speaker.”
3. Same period: once tech is even, rank is micro — every HTML tag, word, alt, anchor. The page’s final shape vs the competitor’s final shape.

**He claims it proves:** Tech SEO (especially render) can move traffic without buying DA. DA/links on winners are trophies. After tech, the fight is the page. The speaker slot is the social proof of the render win.

**Proof:** **asserted.** No site, no GSC, no DA screenshot, no SCL talk title from that year. This is the most important before/after in the corpus and the least evidenced.

---

### 31. Stopped a $20K USD/month link budget — “没有半毛钱影响”

**Type:** before/after, same US-era company
**When:** “三年前工作公司” / “我出来做Agency之前那个工作.” Tweets 2026-08-15 and 2026-08-21 (CST).
**Ids:** 2090685656079241520, 2088623359366209644

**What happened:** Company spent $20K USD/month on links, in the most competitive YMYL vertical. They stopped. He says zero impact / “DR，外链都没用.” He points at Google’s 2016 post: Penguin is in the core.

**He claims it proves:** links work, chasing them wastes money. Penguin already prices the chase.

**Proof:** **asserted.** No domain, no spend sheet, no traffic overlay. The 2016 URL is a citation, not the experiment. The YMYL color is only in the reply.

---

### 32. Two unnamed sites: delete guest-post anchors → rank up; keep buying links → zeroed

**Type:** two observed before/afters
**When:** tweeted 2026-08-20 (CST), after the August 2026 spam update he had just referenced.
**Ids:** 2090396597066899635 (also the YMYL/Web3 version 2033817449922245047)

**What happened:** Spam_score mental model: each spam finding +1; Spam Policies probably have a crawler; Spam Updates refresh the ledger. Things that “肯定被干”: cloaking, AI 洗稿, AI 灌水, link spam.

He has seen: (a) a site delete all custom-anchor guest posts, then rank **up**; (b) a site that thought it was just an algo victim, kept buying links, got **清零**.

YMYL / Web3 tip in March: if your links are custom-anchor, disavow or have them deleted; if content is AIGC with fake authors, replace them; “很有可能你的排名一下子就会上去.”

**He claims it proves:** spam is additive and automatic. Recovery is subtraction (delete / disavow / replace authors), not more of the same.

**Proof:** **asserted.** No hosts. The +1 spam_score loop is his sketch, not a leak field.

---

### 33. US publisher SRA wave — 404 the junk, file reconsideration

**Type:** client / publisher work he says he processed
**When:** “之前处理过美国那波 Publisher 的 Site Reputation Abuse.” Mentioned inside the Alibaba teardown, 2026-03-28 (CST).
**Ids:** 2037884887307526631

**What happened:** He processed that wave. Manual action on the whole domain was “致命.” Method: “直接 404，再去提解除.” He then warns Alibaba’s junk is mostly Soft 404, so a hard 404 sweep might knock the site over.

**He claims it proves:** SRA is a domain-level Trust event. The clean kill is HTTP 404 + reconsideration, not more content.

**Proof:** **asserted.** No publisher names, no manual-action IDs, no before/after.

---

### 34. A friend’s deindex (not a manual action) — 3–4 months to repair

**Type:** friend / peer war story, told while advising on Alibaba-scale cleanup
**When:** 2026-03-29 (CST).
**Ids:** 2038199743797690529

**What happened:** He splits two recoveries. If it *is* a Manual Action: 404 every flagged subdomain and subfolder from the source. Subfolders are harder. If it is *not* a Manual Action and the site was simply deindexed: “我一个朋友碰到过，修复周期差不多要3-4个月.” Method he recites: noindex all AIGC at the source, staged nofollow on internal links, tune `robots.txt`. At that friend’s volume, even the audit takes a long time.

**He claims it proves:** Manual Action and deindex are different clocks. Deindex at AIGC volume is a months-long subtraction job, not a reconsideration form.

**Proof:** **asserted.** Friend unnamed, site unnamed, no GSC, no date of the hit.

---

### 35. 2023 Google Top Stories method — writer outranks US first-tier news

**Type:** in-house experiment / playbook
**When:** 2023, at “公司里.” Tweets 2026-08-23 / 08-24 (CST).
**Ids:** 2091729433279496522 (the win), 2091387930963263678 (why News SEO became his life)

**What happened:** In 2023 he worked out “如何排 Google Top Stories.” A writer colleague learned it and then, “无论写什么都比美国一线的新闻网站都要高.” The writer, who liked writing anyway, went 鸡血, night and day, because everything published produced a result.

2020 origin: work put him on News SEO (Top Stories / Google News / Discover). News rank “是可以通过 SEO 手法去操控的.” BBC / NYT have topical authority from long, wide coverage. Domestic media, for ecosystem reasons, have done none of this, so they are weak on those topics. If a Chinese news site also lacks IA and author-profile / degree entity links, they stay disadvantaged — “别人可以追着你写你的坏话.”

**He claims it proves:** news SERPs are steerable. Topical authority is coverage over time. A working playbook is the best writer incentive. This is why he kept SEO as a career.

**Proof:** **asserted.** No article URLs, no Top Stories screenshots, no query list. “美国一线” unnamed.

---

### 36. The news site he is raising — $10K domain, hand-shot photos, no links, Bing > Google on YMYL

**Type:** own experiment (likely one project, two tweets)
**When:** 2026-06-11 (build story), 2026-08-16 (test results) (CST).
**Ids:** 2064883047825395749, 2088803453565059194 (also 2081384202596209058: ~$30K USD on domains in three years; 2090324134177931459: bought another)

**What happened:** Site with a friend, “准备养老用.” Domain $10K USD, US news / local. All copy handmade. No agent, no workflow. No backlinks. All photos/video shot by real people. All authors real. CMS stood up in ~one week, $500/year. “迄今为止觉得物超所值.” “SEO就那样，没有捷径，护城河要靠人来堆.”

Later, “我正在养的一个新闻网站，做了很多有意思的SEO测试”:

- YMYL: Bing currently has **no threshold**.
- Typical SEO traffic split Google:other ≈ 9:1, but Bing/Microsoft organic **can exceed** Google.
- NA / EU Bing traffic quality is high.
- Original images add a lot of “质量”; “上千张图片都是我的合伙人自己拍的.”

**He claims it proves:** the moat is people (real authors, real cameras), not agents or links. Bing will take YMYL that the US Google gate still holds. Original photos are a Quality additive he has felt.

**Proof:** **asserted.** Domain never named. $10K / 1000 photos / Bing>Google are his numbers, no GSC, no Bing dashboard. The $30K three-year domain spend is a related personal anecdote, not a ranking case.

---

### 37. “I just did traditional SEO to the extreme — ChatGPT traffic rose”

**Type:** own / client-shaped experiment, negative control
**When:** 2026-07-20 (CST).
**Ids:** 2079109647160734202

**What happened:** He asked what GEO optimization even is. His answer: he maxed traditional SEO. ChatGPT traffic went up. Explicitly **not** done: blogs, Reddit, 语意匹配, PR, schema, FAQ.

**He claims it proves:** the popular GEO recipe has no evidence in the education / papers / research he accepts, “因为逻辑不通.” GEO, for him, collapsed into SEO.

**Proof:** **asserted.** No site, no ChatGPT-referral number, no date range. This is the cleanest negative-control claim in the corpus and it has no chart.

---

### 38. His 小红书 account — AI-assisted posts get 100 views; 5-minute handwritten posts get distribution

**Type:** own platform experiment (not Google)
**When:** “之前.” Tweet 2026-08-16 (CST).
**Ids:** 2088799633766289467

**What happened:** On Xiaohongshu, posts he wrote with AI assist “基本上一开始都不给推流，小眼睛100.” Posts he dashed off in five minutes by hand got distribution. His account only has a few thousand fans, so he treats that as enough control to say some platforms simply do not push AI-generated text.

**He claims it proves:** some platforms already suppress AI-direct content. Effort / human-made is not only a Google story.

**Proof:** **asserted.** No post URLs, no screenshot. “基本上可以确定” is his inference from one small account.

---

### 39. Profound / Peec vs Ahrefs / Semrush / Lumar / Botify / Frog — and last year’s recovery-consulting boom

**Type:** named-company market case (why the people who *could* ship SEO/GEO automation do not)
**When:** 2026-08-25 (CST), after DMs asking him to build an SEO/GEO agent.
**Ids:** 2092067172021608918

**What happened:** Friends DMed: can we do SEO Agent / GEO Automation, because it cuts cost so someone will pay. He says he *could* sit with Claude, Codex, and a few big-tech leads and design one. Unicorns with infinite bullets do not. Profound and Peec.ai are the hot GEO names because they sell **insights / data intelligence to enterprises**, not automation. Ahrefs, Semrush, Lumar, Botify, Screaming Frog already have crawlers, render, audit — and they still do not sell SEO/GEO automation. “去年开始 SEO届最喜闻乐见的，就是大家收到了更多的 Algorithm Recovery 的咨询业务了.”

**He claims it proves:** the missing product is missing because the logic does not work, not because the engineering is hard. Recovery consulting is the actual boom. (He also asked, same week, how generic automation crosses Effort + Originality — case 2.)

**Proof:** **in-corpus** that he names those companies and their supposed pitch. **asserted** that they refuse automation for the reason he gives, and that recovery consulting volume rose last year. No filings, no product pages, no booking numbers.

---

## E. Minor field notes he still treats as evidence

Bundled so the count stays honest: each row is a real mention, none is a full war story.

**Type:** small experiments / observations
**Ids:** 2091198495197913207, 2091304086608236745, 2075237380844654947, 2091368193977987496, 2033189225483677758, 2090960111447794111, 2090289091011391554, 2071839385998569488, 2091008050262110227, 2088639745807278589, 2065243510832582707, 2091461940237467827, 2091727382726205949

| note | what happened | he claims | proof |
|---|---|---|---|
| `loki.digital` | “前两天我特地花了几百刀买了 Loki.digital.” Chain: 网站 A ↔ 开发者网站 ↔ GitHub/LinkedIn, then write a 远景 on the dev site. | This is the cheapest EEAT for a named, credentialed founder. (Grey-hat is the other fork.) | **in-corpus** that he bought the domain. **asserted** that the chain works — he has not published the built-out site as a result. |
| “AI Agent” on Trends | Last-5-year regional Trends, top 10 mostly Asia, US #8, China #1, Singapore #2. He has long felt the term is a Chinese export. | C-end users may not search “Agent” yet. Don’t name the product XXX AI Agent if you want SEO. | **partial** — the ranking of countries is stated, no Trends URL / screenshot. |
| Two days in Korea | “基本上都不用谷歌.” | A Korean site with no Naver work loses more than half. | **asserted.** He later says he has only *heard* this from Korean SEOs and has not done Naver himself (2091368193977987496). |
| Smaller sites outrank Amazon / Walmart / Canva / ESPN / Forbes / WaPo | He has worked competitive KWs where this happens “nearly as often.” | DA / backlink volume is a myth as a linear rank driver. Real work is quality, topical authority, trust. | **asserted.** No query, no SERP. Same thesis as case 30. |
| 周杰伦 墨尔本演唱会 in AI Mode | AI Mode shows YouTube and Facebook, not just sites. GSC now reports social-account performance. | Future SEO is not site-only. | **asserted** illustration. |
| Writer who always ranks / designer who always converts | He has seen both. | SEO needs writers the way paid needs creatives. | **asserted.** |
| His copy rates | 800–1K AUD long landing, 300–500 AUD blog, 200 AUD product page, to senior writers. | Implicit: this is what “effort” costs. | **in-corpus** as his price list, not as a ranking result. |
| US first-tier sites have no m-dot | “你去观察一下现在专门吃SEO流量的美国一线网站，没有任何一个网站有专门的手机站点.” Apple is the example host (`apple.com` vs `m.apple.com`). | Google and Bing have said for ~10 years: do not split mobile. Canonical does not save it. Domestic H5 / mini-program templates are “十有八九” unfit. | **asserted** observation. No named US host besides the Apple hypothetical. |
| PSEO without an original system | “不然半年内就会被砸掉.” This year, non-original PSEO + 铺内容 “基本上今年都要出问题,” whatever the DA. | PSEO needs an original spine (your algo, ratings, data, product). Else it dies inside six months. | **asserted.** No host. |
| $300M ARR Chinese ecommerce brand, ads manager | Last year’s beta: CPMs “way higher” than other channels, conversions poor. He asks whether feed ads fix it. | Not an SEO proof. Color on Google ads experiments. | **asserted** hearsay. Brand unnamed. |
| OpenAI / Meta / Claude hired SEO last year | Reply to “AI Vibeseo is enough.” | If the model labs still hire SEO, vibe-SEO is not enough. | **asserted.** No JDs. |
| Autodesk Search Intelligence Manager | Named as the interesting AEO/GEO-leaning title. He still cannot tell you how to do AEO/GEO. | Big-company hiring is the tell: they pull AEO/GEO people from the SEO pool. | **in-corpus** that he names the title. **asserted** as a trend. No JD URL. |

---

## What he never shows, even on the cases he uses as proof

- No GSC / Semrush / Ahrefs screenshots survive in the tweet *text*. He refers to “这个图片” (知乎) and “忘记截图了” (阿里) — the pictures are not in this corpus.
- No client or employer domain is named except the public teardowns (知乎, 阿里巴巴 hosts, 逐玉 / WeTV / iQIYI / Netflix, Al Jazeera Chinese, Canva careers, Klook JD, Wirecutter, Feishu, LinkedIn, Ameba).
- The three cleanest before/afters — Angular render → traffic up, $20K links → zero impact, ChatGPT traffic up with no GEO tricks — are all **asserted**.
- Gary’s answer is explicitly a forgotten paraphrase (told in Chinese and again in English).
- Alibaba 10M, Ameba 92M/2.8B/5B/500M, Wirecutter $75.5M, casino €11.5M, Canva 200+, loki.digital “几百刀,” news-site $10K, domain-spend $30K, friend’s 3–4 month deindex: numbers he states, sources not in-corpus except where he pastes a URL (Klook JD, Canva jobs, WeTV/iQIYI/Netflix titles, Cloud AI-detection docs, Google migration doc, Penguin 2016).
- He is honest about gaps inside the corpus: Doubao / Deepseek “我不是很理解”; Naver “自己还没做过”; AEO/GEO “我现在也没有办法回复你.”

---

## Not cases (talked about, no incident)

Brighton SEO deck library (2091671329812717693). Apple i18n / no auto-redirect (2091014853863637176, 2091027410028536057, 2091029095614464197). Shopify feed / headless tip (2089230010616062038, 2091062668056838266, 2091199226856521823). Generic QRG author/LinkedIn (2091381622616797394). Homepage entity “Melbourne SEO Consultant” as a worked hypothetical (2091185632202883243). Baidu overseas Wiki as a future GEO shortcut (2039650266858037280). Language-asymmetry essay on non-English brands in EN-trained LLMs (2034056213529563637, 2034056920827629816) — observation, no named site. Anthropic $320K SEO Lead / “Claude is the worst model because it still cannot mass-produce blogs” (2067542156647305588) — joke, not a case. Stitch / Nano Banana image tests (2034757166255808697, 2034060421578297579) — product doodling.

---

## Index by tweet id

| id | case # |
|---|---|
| 2092100375239438810 | 3 (Cloud AI image detection) |
| 2092090944648581505 | 2 (contentEffort + Gary) |
| 2092095823731462302 | 2 |
| 2092067172021608918 | 39 (Profound / Peec / recovery boom) |
| 2092027807719444899 | 9 (Ameba / Kimura) |
| 2091894056687431704 | 1 (Warehouse focus/radius) |
| 2091895491982405998 | 1 |
| 2091900022115938340 | 30 (affiliate listicles) |
| 2091844216980979877 | 23 (Klook) |
| 2091795112745689273 | 14 (知乎) |
| 2091739865121783923 | 15 (阿里 as fake-author) |
| 2091729433279496522 | 35 (Top Stories) |
| 2091727382726205949 | 40 notes (Autodesk title) |
| 2091716914599067838 | 12 (Evolve / 豆包) |
| 2091682678261375106 | 16 (逐玉) |
| 2091668405367791619 | 22 (Canva) |
| 2091542149083041998 | 25 (Feishu .app) |
| 2091492121186635988 | 25 |
| 2091487107806323136 | 8 (Non-commodity + X growth) |
| 2091461940237467827 | 40 notes (OpenAI / Meta / Claude hiring) |
| 2091387930963263678 | 35 (News SEO origin) |
| 2091376367740789153 | 13 (Shenzhen / login) |
| 2091368193977987496 | 40 notes (Naver: not done) |
| 2091364706703581191 | 5 (Gemini ≠ Search) |
| 2091362717907251353 | 6 (four SCLs) |
| 2091353930425127142 | 7 (Quality PPT) |
| 2091349098553295075 | 26 (soft 404 / LinkedIn) |
| 2091321150127366357 | 22 (Canva / Zillow / Booking) |
| 2091309003397902703 | 18 (Shenzhen migration) |
| 2091304086608236745 | 40 notes (AI Agent Trends) |
| 2091301352463102268 | 30 (US affiliate / SCL speaker) |
| 2091198495197913207 | 40 notes (loki.digital) |
| 2091071455350169891 | 5 |
| 2091060807065117104 | 23, 25 |
| 2091013621790716336 | 28 (Reddit ZH) |
| 2091011325438955723 | 27 (expired YMYL) |
| 2091008050262110227 | 40 notes (no US m-dot) |
| 2090960111447794111 | 40 notes (周杰伦 AI Mode) |
| 2090735573443158517 | 24 (Wirecutter) |
| 2090697074153283687 | 17 (casino) |
| 2090685656079241520 | 31 ($20K links) |
| 2090684152328945976 | 13 (5 KW groups) |
| 2090567084933787767 | 13 (triangle) |
| 2090396597066899635 | 32 (guest posts / bought links) |
| 2090324134177931459 | 36 (bought another domain) |
| 2090291222556578070 | 1 (Site Focus / About Us) |
| 2090289091011391554 | 40 notes (writer who ranks) |
| 2089165558516437461 | 21 (unnamed slop wipe) |
| 2088803453565059194 | 36 (news site tests) |
| 2088799633766289467 | 38 (小红书 AI vs hand) |
| 2088639745807278589 | 40 notes (PSEO six months) |
| 2088623359366209644 | 31 (YMYL $20K) |
| 2088131678065852712 | 2 (Gary, English) |
| 2081865732271550669 | 13 (will cover in Shenzhen) |
| 2081384202596209058 | 36 ($30K domains) |
| 2079109647160734202 | 37 (SEO-only, ChatGPT up) |
| 2075237380844654947 | 40 notes (Korea / Naver) |
| 2071839385998569488 | 40 notes (copy rates) |
| 2070420648900403202 | 20 (DTC 腰斩) |
| 2065243510832582707 | 40 notes ($300M ads) |
| 2065232184374645078 | 4 (Navboost) |
| 2064981657497813013 | 27 (domain hygiene) |
| 2064883047825395749 | 36 (news site build) |
| 2038199743797690529 | 34 (friend deindex) |
| 2038013959954153823 | 15 |
| 2037898118898012638 | 15 |
| 2037884887307526631 | 15, 33 (阿里 + US SRA) |
| 2039641960601043096 | 15 |
| 2034868852602151058 | 19 (XHS AI-SEO tools) |
| 2034784854009946123 | 10 (Al Jazeera) |
| 2033817449922245047 | 32 (YMYL/Web3 cleanup) |
| 2033414646775083406 | 11 (Evolve speaker) |
| 2033383720305230314 | 30 (US niches) |
| 2033335605925654664 | 29 (315 / 莆田) |
| 2033324298694455330 | 29 |
| 2033322311051575534 | 29 |
| 2033321100848095548 | 29 |
| 2033189225483677758 | 40 notes (small outranks Amazon) |
