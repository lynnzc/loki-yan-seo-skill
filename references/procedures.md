# Procedures

Source: `@loki_yan_seo` only. Window **2025-07-11 → 2026-08-31 UTC**. Last full public-post count remains **979**. Loki-authored **+165** since last cutoff (was 689; now 854). Other accounts in the same threads are not sources. No blog. No decks. No Day 0 / three-reversals / 5-step FO / CRO framework / hreflang recipe / Top Stories / feed-hack SOP imported from outside.

English only. His English is kept as-is. Chinese is a tight rendering of what he said. Names and steps keep **his** meaning. Incomplete means the tweets stop before a method.

For every real step: tweet `id` + quote. When he names a topic and gives no steps, the entry is marked `[no procedure in corpus]`.

**Real procedures with steps: 38.** Named topics with no steps sit in the Gaps section.

---

## 1. Hypothesis, test, measure, iterate

**When:** Everyday work. The algo is a black box; daily work is still feeling stones to cross the river.

**Steps:**
1. Paste the Klook JD line as the work method.
   - id=2091844216980979877 — "You don't believe in \"SEO magic.\" You believe in hypothesis, test, measure, and iterate."
2. Restate it as his own line: every experience is done through hypothesis, test, measure, iterate.
   - id=2091844216980979877 — "Because Google's algorithm is essentially a black box… our daily work still belongs to feeling the stones to cross the river. All experience is done through hypothesis, test, measure, and iterate."

He did not write how to file a hypothesis, how long to test, or what sheet to measure on. Those four words *are* the method.

---

## 2. Rankings drop in a big way — SEO Audit order

**When:** The site's rankings drop across a large area. He used it on Zhihu losing Google traffic overnight.

**Steps:**
1. First thing to look at is robots.txt.
   - id=2091795112745689273 — "When a site has a large-area ranking drop, when you do an SEO Audit, the first thing to look at is robots.txt."
2. Second thing to look at is Crawl status.
   - id=2091795112745689273 — "the second thing to look at is Crawl status."
3. His own diagnostic move on Zhihu: Chinese Google results always had Zhihu on top, then Zhihu suddenly gone, then open Semrush, then robots.txt is the problem.
   - id=2091795112745689273 — "Normally when I search Chinese things on Google, Zhihu is always in front. Later Zhihu suddenly disappeared. I went to SEMRush and looked once. Sure enough, robots.txt had a problem."
4. Watch point after a full crawl ban: traffic and index trend.
   - id=2091795112745689273 — "if robots.txt forbids all crawlers, you can observe what his traffic and index trend look like."

Audit item 3 is not written. Whether the harm is fatal, whether something else stopped ranks from recovering to the old level — "we just cannot know."

---

## 3. contentEffort — the question to Gary, the engineer list, the no-error method

**When:** Unpacking the Content Warehouse API leak; answering "raising contentEffort can raise SEO, so what should I do." He chased Effort from Bangkok (2025-08) to Shanghai (2026-05).

**The question he asked Gary (Shanghai):**
1. Ask whether EEAT / QRG things such as effort are auto-run by an algorithm, and how effort would be measured automatically.
   - id=2092090944648581505 — "At the Shanghai Google event I asked Gary: about EEAT, inside this Quality Rater Guideline thing, does Google have an algorithm that runs automatically? For example, how would a thing like effort be measured automatically?"
2. He remembers the answer as not straight: there is a "mathematic calculation."
   - id=2092090944648581505 — "Of course Google's answer was not especially direct… the rough meaning is there would be a \"mathematic calculation.\""
   - id=2088131678065852712 — "I asked a similar question in Search Central Live Shanghai 2026. The answer from Google: there's \"mathematic calculation\" for those \"things\" mentioned on the EEAT Guideline."
3. Then open the Warehouse dump and find the field.
   - id=2092090944648581505 — "contentEffort - LLM-based effort estimation for article pages" / "Since this contentEffort has a variable definition, then it can definitely be calculated, right?"

**Assume you are a Google Engineer — how would you auto-compute contentEffort (he says he is not one; this is a hypothesis list, not a production script):**
1. Generic Template, generic structure written by AI?
   - id=2092090944648581505 — "1. Generic Template, generic structure written by AI?"
2. Is the content paraphrasing and stitching of the top 20 or top 10 articles?
   - id=2092090944648581505 — "2. Is the content Paraphrasing and stitching of the top 20, or top 10 articles?"
3. Can the content provide unique entities, parameters, and so on (he thinks ML can predict this)?
   - id=2092090944648581505 — "3. Whether the content can provide unique entities, parameters and so on (I think this machine learning can predict)."
4. Asset effort: are the images and videos original? He is sure Google can tell original vs AI-generated.
   - id=2092090944648581505 — "4. Asset effort in the content: are the images and videos I put original? I am very sure Google can tell whether images and videos are original, whether they are AI generated."
5. Information Gain: has what you wrote appeared before?
   - id=2092090944648581505 — "5. Information Gain, has what you wrote appeared before?"

**What he tells operators, not the code above:**
1. Original text, original images, original video, original insights can all be counted as contentEffort.
   - id=2092090944648581505 — "Given that raising contentEffort can raise SEO, then original text, original images, original video, original insights can all be counted as contentEffort."
2. No-error method for batch work: at least have increment; get some original stuff, or you will be judged low effort and hit.
   - id=2092090944648581505 — "Is there a method that does not go wrong? I think it is: whatever batch thing you do, at least have increment. At least from the data and content angle, you have to find a way to get a bit of original stuff, otherwise you will definitely be judged as low effort, then you get hit."
3. The EEAT door is Effort + Originality; tokens do not cross it.
   - id=2092095823731462302 — "The reason I have always said I don't believe in pure SEO Automation is that Google set this EEAT threshold. Here there are 2 key points: Effort and Originality. How does generic SEO Automation cross Effort and Originality? By how many Tokens you spent?"

---

## 4. Buy human effort — intern + Canva; go ask ex-Google friends

**When:** After the Effort / Original talk. Small company, small studio, solo going-global. "SEO edge-ball": Google Cloud may already have the detector.

**Steps:**
1. Associate and hypothesize yourself. Example: Google Cloud has an AI Image Detection API; even if it will not punish you, your contentEffort score will definitely not be positive.
   - id=2092100375239438810 — "You have to associate and hypothesize yourself. For example Google Cloud has this AI Image Detection API. Even if it will not punish you, your contentEffort score will definitely not be positive."
2. Hire a sharp domestic university intern, better school, fast learner, to do the effort things. They want work experience; you want "human" effort.
   - id=2092100375239438810 — "If you are a small company, small studio, even an independent going-global person, I think you hire a sharp domestic university intern… to help you do the effort things — is that not OK? They want work experience, you want \"human\" effort."
3. Get a Canva account and make images by hand. In a month you can make a lot.
   - id=2092100375239438810 — "Get a Canva account, make images by hand, in a month you can make a lot."
4. US friends: from time to time ask Google / ex-Google friends what systems they have worked on; maybe it strings together.
   - id=2092100375239438810 — "I see a lot of American friends, you probably have Google or ex-Google friends around. From time to time you can inquire what systems they have done. Maybe it strings together."
5. The point of learning Best Practice is to use the rules inside a reasonable range.
   - id=2092100375239438810 — "The purpose of learning SEO Best Practice is to use the rules inside a reasonable range."

No hiring brief, no Canva SOP, no "how to use the Cloud API" — he only names it as a hint.

---

## 5. AI-product site: name the model, write the changelog, make download pages, or get a real GitHub

**When:** AI going-global sites. Friends who are ex-big-tech, PhD, CS.

**Steps:**
1. Give the model you built a name. Make a page / page set that explains from day one how many versions you shipped and what you updated — like an App Store changelog. Clarify and write it out. You used to write Engineer Docs every day.
   - id=2092098493695553818 — "1. Give the model you made a name. Make a page, a page set, inside it explain in detail from the first day you started this model, how many versions you released, how many things you updated. You know App Store changelogs, right? … Clarify the matter and write it clearly. You used to write Engineer Docs every day at the ex-big-tech, right?"
2. If you have an app: make a download page, a download/ios, a download/android, then link out to the app stores.
   - id=2092098493695553818 — "2. If you have an app, make a download page, make a download/ios, make a download/android. Then link out to your app stores."
3. If you do not want to link your own LinkedIn, get a GitHub — a stronger GitHub, higher activity.
   - id=2092098493695553818 — "3. Don't want to link your own Linkedin, then get a github, a stronger github, activity a bit higher."
4. If you do not want to put in any effort and only want to scoop: he has no method for you.
   - id=2092098493695553818 — "4. Don't want to put in any effort at all, pure scoop? Then I have no method."

No page template, no schema, no "how much GitHub activity is enough."

---

## 6. When you pick keywords, look at how many troops the other side has

**When:** Treat SEO as a war. Looking at KW Difficulty. Used to decide whether you are a single soldier walking into their camp.

**Steps:**
1. When you look at KW Difficulty while picking words, you are looking at how much ammo, equipment, and people the competitor has — not how easy or hard the word is.
   - id=2091668405367791619 — "When you pick words and look at KW Difficulty, what you are actually looking at is how much ammo and equipment and people the competitor has, not how simple or hard this word is."
2. Go to their LinkedIn. Search how many people have SEO in the title, how many have content in the title. That tells you how big an army you are fighting.
   - id=2091668405367791619 — "1. Go to their linkedin, search how many employees have SEO title, search how many employees have content title, then you know how big an army you are fighting."
3. Canva example: he estimates the whole SEO-related team (including content and other people) is globally 200+ people.
   - id=2091668405367791619 — "2. Take Canva as an example, I estimate the whole SEO-related team (including content and other people), globally will be above 200 people."
4. Go to the company's careers site and look at their moves. Canva is hiring SEO roles in Italy, Japan, Korea, Malaysia, Argentina, Spain — they are deploying for local-country markets.
   - id=2091668405367791619 — "3. Go to the company's recruiting site and look at their moves. Canva is recruiting SEO roles for Italy, Japan, Korea, Malaysia, Argentina, Spain, meaning they are deploying troops to do those local-country markets."

No "how many people means you can fight" cutoff. No third-company template.

---

## 7. Why the other guy ranks above you — look from page title

**When:** Ordinary-person view of why SEO matters. Your own product loses the SERP and you miss the conversion window. Example: Pursuit of Jade.

**Steps:**
1. Open Google, search that word. Look at this SERP. Who would you pick.
   - id=2091682678261375106 — "Very simple, just open Google, search 逐玉. Look at this SERP, would you pick iQIYI, iQ, or Netflix?"
2. Then analyse why iQIYI / Netflix / iQ rank above WeTV. Line the title tags up.
   - id=2091682678261375106 — "Then go analyse why iQIYI, Netflix, and iQ rank in front of Tencent Video. Look from the same page title angle."
3. Check for a duplicated page title, or the core keyword not in the title. Or they put it, but the front end calls a default page title at render.
   - id=2091682678261375106 — "Tencent Video overseas version, this is a duplicated page title problem. Or you did not put the core keyword in the title. … Or maybe he put it, but when the front end rendered it called a default page title."
4. Conclusion: the importance of optimising page title. Otherwise your own product cannot outrank piracy.
   - id=2091682678261375106 — "Then you can easily get a conclusion, the importance of optimising page title. Otherwise your own product cannot outrank piracy, this thing, right, does not make sense."
5. People searching this word will bring a verb or modifier — online, free, watch. Put those verbs and modifiers into the page title to match.
   - id=2091682678261375106 — "Then because when people search this word, they will definitely bring some verb or modifier, right. For example 在线, 免费, 观看, watch and so on, you can put these verbs and modifiers into the page title to do a match."

No title length, no format template, no retest method.

---

## 8. Look at keywords, analyse keywords — tool ladder, then check users actually search that way

**When:** A real long-term SEO project. The concept "SEO spreading words" does not exist. When you make each page, you clearly know what that page is for and what words it will rank.

**Tool order (ability ladder, not a one-week homework):**
1. This is when you use Semrush, Ahrefs.
   - id=2090954259680694666 — "This is when you need to use Semrush, Ahrefs."
2. If your foundation is a bit stronger, you can use Dataforseo.
   - id=2090954259680694666 — "If your foundation is a bit stronger, you can use Dataforseo."
3. If you want to refine it, hand-work can use Google Keyword Planner (Google's side is the most accurate).
   - id=2090954259680694666 — "If you want to refine it, playing by hand you can use Google Keyword Planner (Google's side is the most accurate)."
4. You can also look at Google Keyword Trends.
   - id=2090954259680694666 — "You can also look at Google Keyword Trends."
5. Looking at keywords, analysing keywords, is physical work and brain work.
   - id=2090954259680694666 — "Looking at keywords, analysing keywords, is physical work, and is also brain work."

**Check that users would actually search it:**
1. Take Google Trends and break it down carefully by region. Example: AI Agent past 5 years, top 10 are basically Asia, US is 8th. If you do AI SEO for C-end users, they may not search "Agent", not yet. From the SEO angle you may need to change the name.
   - id=2091304086608236745 — "The concepts you know do not mean your users will search that way. … If you take Google Trends and break it down carefully by region, in the past 5 years the top 10 are basically Asia, the US is only 8th. … Suppose you want to do AI SEO, and it is C-end users, the word they may search is not \"Agent\", not yet. … From the SEO angle you may need to change a name."

**Per page / homepage:**
1. In theory every page should be able to find one non-duplicate keyword that has search volume.
   - id=2090938323284185332 — "Also in theory every one of your pages should be able to find one non-duplicate keyword that has search volume."
2. For the homepage, try to find one keyword that can cover your direction for the next three to five years.
   - id=2091185632202883243 — "About your site's homepage, try to find one keyword that can cover your direction for the next three to five years."
3. That keyword is generally {modifier} + Entity. Example: Melbourne SEO Consultant. Services extend as child pages. Words unrelated to this Entity, the site in theory cannot cover and should not cover.
   - id=2091185632202883243 — "This keyword is generally {modifier} + Entity. For example if I rank my own site homepage, it would definitely be Melbourne SEO Consultant. Then the services I provide would extend down as child pages. Words unrelated to SEO Consultant, my site in theory cannot cover, and should not cover."
4. A keyword is not a String, it is an Entity. KW Density is nonsense.
   - id=2091185632202883243 — "Here you can understand: a keyword is actually not a string (String) but an entity thing (Entity). … Once you understand entity, you will discover the KW Density concept is actually nonsense."

Site architecture (URL) "has no standard answer, but it will definitely follow a logic" — commercial logic, clinical logic, fact logic, science logic — and he stops there (id=2090938323284185332). No export, no clustering, no map-to-URL ritual, no KD cutoff.

---

## 9. Root keyword, download Ads Forecast, let Claude tidy it

**When:** Someone asked how to get a decent Search Volume set. One-reply method.

**Steps:**
1. First you need a Root keyword.
   - id=2065688886270108027 — "that is, first you need to have a Root keyword"
2. Then download all the Ads Forecast data in one go.
   - id=2065688886270108027 — "then take the Ads Forcast data and download it all in one go"
3. Then let Claude tidy it. Basically you can get a fairly accurate Search Volume.
   - id=2065688886270108027 — "then let Claude tidy it, basically you can obtain a fairly accurate Search Volume"

Which Ads Forecast UI, which columns, what Claude prompt — not written.

---

## 10. Screaming Frog for what the crawler sees — formula Raw = Rendered, Desktop = Mobile

**When:** Check whether your technical architecture is better than the competitor. A lot of the time SEO problems appear on design, code, and the product side.

**Steps:**
1. Use Screaming Frog (paid) to see what the fully rendered page looks like, so you know what the simulated crawler sees.
   - id=2091508567119642847 — "Using Screaming Frog (paid version) you can see what the fully rendered page looks like, so you can know what the simulated crawler sees on the site."
2. Screaming Frog can find the difference between your Raw HTML and the JS-rendered HTML.
   - id=2091508567119642847 — "Screaming Frog can find where your Raw HTML and the JS-rendered HTML differ, this is very helpful."
3. Remember one formula. At the content level both must be satisfied. Try not to use Display none; that causes duplicate content.
   - id=2091508567119642847 — "Remember one formula, this will help. At the content level you must satisfy both at the same time, try not to use Display none to do it, this will cause duplicate content. Raw = Rendered. Desktop = Mobile."
4. If you want to 100% guarantee your technical architecture is better than the competitor: (1) Mobile and desktop content must be consistent. (2) Raw HTML must match rendered content. (3) One piece of HTML can appear only once; you cannot use a display none write-up.
   - id=2091008050262110227 — "If you want to 100% guarantee your technical architecture is better than your competitor, then 1, your mobile and desktop content must be consistent 2, Raw HTML must be consistent with the Rendered content 3, one piece of HTML can appear only once, you cannot use a display none write-up."

Google and Bing both do not recommend splitting an m-site from the desktop site. Even with Canonical done it still does not work. Domestic mini-program / H5 template logic, nine times out of ten, does not fit modern SEO and GEO (id=2091008050262110227).

No Frog tab, no threshold. Render-timeout Soft 404 on Angular is a case he lived (id=2091301352463102268), not a repair playbook.

---

## 11. How to test Mobile first screen / above-the-fold

**When:** Especially going-global sites now. Google is fully mobile first and can do JS render. 2012 above-the-fold: if after the crawler renders, the first screen is empty or has little, you get hit.

**Steps:**
1. Google is fully mobile first, and can do JS render.
   - id=2090686787534598639 — "1. Google is fully mobile first, and can do JS render."
2. The first screen here means the Mobile first screen.
   - id=2090686787534598639 — "4. The first screen here means the Mobile first screen."
3. Put h1 on the first screen. Do not hide it below.
   - id=2090686787534598639 — "5. Remember to put <h1> on the first screen, don't hide it below."
4. How to test: go to GSC or Rich Results Test and see whether Google can render the page, whether the first screen has content, whether a cookie or ad popup covers above-the-fold content.
   - id=2090686787534598639 — "How to test? Go to GSC or Rich Results Test and see whether your page can be rendered by Google, whether the first screen has content, whether a Cookie or ad popup covers above the fold content?"
   - id=2090716049574605075 — "Remember to test render. https://search.google.com/test/rich-results"
5. If there is a problem, after you fix it there will be effect immediately.
   - id=2090686787534598639 — "If there is, after you change it there will be effect immediately."

No GSC report name. "Immediately" is not a number of days.

---

## 12. Soft 404 — error pages must return HTTP 404

**When:** Any error page. He says Google spent a whole year at conferences calling this a crawl-budget landmine.

**Steps / rule:**
1. A normal 404 should return the HTTP 404 code.
   - id=2091349098553295075 — "A normal 404 should return the http 404 code."
2. Soft 404 means you made an error page, but the HTTP status actually returned is 200.
   - id=2091349098553295075 — "Soft 404 means you made an error page, but the HTTP status actually returned is 200."
3. Side effect 1: it burns crawl budget. Error pages and non-existent pages all return 200, so the crawler spends budget looking at empty pages, and the big site's pages that should be crawled do not get crawled.
   - id=2091349098553295075 — "1. Affects Google's crawl budget. Because your error pages, non-existent pages, all return 200, the crawler has to spend budget to look at your pages. But this page of yours has nothing. The big site's places that should be crawled cannot get crawled."
4. Side effect 2: you get attacked. If the front-end template does not set 404 title / h1 and pulls them from the URL, junk pages can get indexed and raise your spam score.
   - id=2091349098553295075 — "2. Get attacked. The front-end Template did not set the 404 title, h1 and other components, but got them from the url. This will let people manufacture a batch of junk pages that can be indexed. Your site's spam score goes up."
5. Alibaba observation: almost the whole site is soft 404; if they change to HTTP 404 the site will probably explode. Even after they take pages down they are still soft 404.
   - id=2037884887307526631 — "alibaba's whole site is almost all soft 404, I estimate if they change to http404 the site will explode."
   - id=2037898118898012638 — "Their HTTP 404 still has problems. Even if they take these pages down they are all still soft 404."
6. His Angular case: Google often hit render timeout while crawling, so many pages went Soft 404. Just fixing that render problem sent traffic up at once. [asserted]
   - id=2091301352463102268 — "When Google crawled the site it often hit render timeout, causing many pages to show a Soft404 state. Just fixing this render problem made the site's traffic rush up at once."

No batch-find Soft 404 checklist. No "how to fix Angular timeout" steps.

---

## 13. Manual Action vs straight Deindex — fork, then 404 / Noindex from the source

**When:** Site Reputation Abuse / Manual Action on a publisher, or a friend whose AIGC block got deindexed. He handled the US publisher wave.

**Steps:**
1. First you have to confirm whether it is Manual Action.
   - id=2038199743797690529 — "First you have to confirm whether it is Manual Action."
2. If it is: every flagged subdomain and subfolder needs a dedicated 404 page. Then 404 the subdomain from the source entirely. Subfolder is much more trouble.
   - id=2038199743797690529 — "If it is, all flagged subdomains and Subfolders have to specially make a 404 page. Then take the Subdomain and 404 it entirely from the source. Subfolder is a lot more trouble."
3. The handling method is simple: directly 404, then file for removal. Manual Action is basically fatal to the whole domain.
   - id=2037884887307526631 — "The handling method is very simple, directly 404, then go file for removal. Manual Action is basically fatal as a strike on the whole domain."
4. Other case — not Manual Action, straight Deindex (a friend of his): repair cycle about 3-4 months. All AIGC pages Noindex from the source; internal links still need staged nofollow; robots.txt adjusted. At that volume, even investigating takes a long time.
   - id=2038199743797690529 — "There is another case, it is not Manual Action, straight Deindex, a friend of mine ran into it, the repair cycle is about 3-4 months. AIGC pages, all pages Noindex from the source, internal links still have to do nofollow in stages, robots.txt adjusted. In this situation at his volume, even investigating takes a long time."

What to type on the reconsideration form, how long Manual Action takes, how to stage nofollow, how to batch Soft 404 into real 404 — not written.

---

## 14. YMYL / Web 3: take the custom-anchor links off, swap the fake authors

**When:** YMYL sites, especially Web 3. Backlinks are all custom Anchor Text; content is all AIGC and authors are all fake. Opposite of the "European play" that keeps buying links / posting blogs / making fake authors after Trust already broke.

**Steps:**
1. If your backlinks are all custom Anchor Text, disavow or ask the other side to delete them.
   - id=2033817449922245047 — "If your backlinks are all custom Anchor Text, disavow or ask the other side to delete them."
2. If your content is all AIGC and the authors are all fake, swap them for new ones.
   - id=2033817449922245047 — "If your content is all AIGC and the authors are all fake, swap for new ones."
3. Very possibly your rankings will go up at once.
   - id=2033817449922245047 — "Very possibly your rankings will go up at once."
4. He has seen a site rise after deleting all the Anchor Guest Posts. He has also seen sites that kept buying links after an update get zeroed.
   - id=2090396597066899635 — "I have seen a site whose ranking rose after deleting all the Anchor Guest Posts it had done. I have also seen sites that felt they were hit by an algorithm update, kept spending money buying backlinks, and finally got zeroed."

How to build the "new" author, how to replace the content — not written. Casino affiliate that kept buying links after Trust broke "directly bounced gone" is a counter-example, not a recovery SOP (id=2090697074153283687).

---

## 15. Buy a new domain — check history first

**When:** About to buy a new domain. Old-school Expired Domain shopping uses the same hunt. If the name was used for spam / PBN / bad backlink history / adult-gambling, "your first step is directly hell-tier."

**How to check, his words:**
1. For backlinks, look at Semrush, Ahrefs, or Majestic.
   - id=2064981657497813013 — "How to check? Backlinks go look at SEMRush, Ahrefs or Majestic."
2. Site traffic trends can also be looked at on Semrush, Ahrefs, or SimilarWeb.
   - id=2064981657497813013 — "The site's Traffic Trends can also be looked at on SEMRush, Ahrefs or Similar Web."
3. And Wayback Machine, to see whether this site ever existed.
   - id=2064981657497813013 — "And another one is Wayback Machine, see whether this site ever existed."
4. Malware / botnet history can still trip Chrome years later.
   - id=2092604590067970417 — "我差点就中过一次招，域名弄回来上线了，chrome打开直接是红色木马警报。" / "后来查出来是之前网站域名被当过肉机，或者垃圾站点。"

No "this history is buyable / this history is not" table. YMYL threshold "should be bound to the domain" is an observation (id=2091011325438955723), not a buy/don't-buy checklist.

---

## 16. Site Migration

**When:** Site rebuild, re-brand, product restructure, change URL, cut the host. "Site Migration is the most complex and highest-technical-gold job in SEO." Used to stop the boss, Product, and design from changing on a whim.

**Steps (accident causes + what you should do — not Google's full doc):**
1. Dev does not know they have to do 301 Redirect.
   - id=2091309003397902703 — "1, Dev does not know they have to do 301 Redirect."
2. 301 Redirect has to be one-to-one.
   - id=2091309003397902703 — "2, 301 Redirect has to be one-to-one."
3. Before migration, no matter how many URLs you have, when you do it you must fully control the before/after URL versions, not change on a whim.
   - id=2091309003397902703 — "3, Before Migration, no matter how many URLs you have, when you do it you must fully control the before and after URL versions, not just change on a whim."
4. Google has a standard Migration flow. (He only dropped the official doc link.)
   - id=2091309003397902703 — "4, Google's side doing Migration has a set of standard process." Link only: https://support.google.com/webmasters/answer/9370220
5. If you casually change a page, a product, a domain, and the flow above is not done, years of accumulation can go to waste.
   - id=2091309003397902703 — "5, You casually change a page, change a product, change a domain, if the above process is not done well, years of accumulation can all go to waste."
6. Before changing URL, cutting the host, product restructure, Re Brand, you can do an SEO Review first. Do not let the boss, Product, design change on a whim. The person who eats the pot is you.
   - id=2091309003397902703 — "6, Before changing URL, cutting the host, product restructure, Re Brand, you can do an SEO Review first. Don't let the boss, Product, design change on a whim. The person who eats the pot is yourself."

Google's standard flow itself is not in the tweet. `[no procedure in corpus]` for the official migration runbook — link only.

---

## 17. How to read Google official docs

**When:** Reading official docs, or arguing whether a "recommend" is optional. He used it on the multilingual-redirect fight.

**Steps:**
1. "Please do" = you cannot skip it.
   - id=2091807896053101013 — "Please execute: not doing it is not OK."
2. "Recommend" = must do.
   - id=2091807896053101013 — "Recommend: must do."
3. "Avoid" = do not do.
   - id=2091807896053101013 — "Avoid: do not do."
4. "Do not" = execute.
   - id=2091807896053101013 — "Do not: execute (kill)."
5. Why no auto-redirect: there is no why. Google said do not redirect. If you do SEO, official recommend is what it is. Why wrestle traffic/rank.
   - id=2091805576611471526 — "There just is no why. Google said do not do redirects. If you want to do SEO, whatever official recommend is, that is what it is. Why are you wrestling traffic/rank."

This is a reading method, not an audit checklist.

---

## 18. Multilingual — copy Apple; do not auto-switch or auto-redirect by IP

**When:** The site needs more than one language. Unified reply to "why not auto-redirect." Add engines when you ship Traditional Chinese / Japan / Korea.

**Steps:**
1. If your site will do multilingual, copy the Apple official site. It is all details.
   - id=2091014853863637176 — "If your site will do multilingual, copying the Apple official site is enough, it is all details."
2. Do not auto-switch language or auto-jump by IP.
   - id=2091014853863637176 — "Right, definitely do not auto-switch language and auto-jump according to IP."
3. How to not auto-jump: look at the popup at the very top of apple.com. Best not to jump. You can also look at Apple and Canva.
   - id=2091064564846854527 — "About how you should do not-auto-jump? Look at the popup at the very top of the apple official site."
   - id=2091029095614464197 — "Best not to jump. You can look at Apple and Canva."
4. Why? There is no why. Google said do not redirect.
   - id=2091805576611471526 — "There just is no why. Google said do not do redirects."
5. Thought check: the page the user entered from search should already be the right country/language. Why would you still auto-switch a correct version. Browser is English, query is Chinese, they land on com/zh-hans/ — do you 301 them to the English site?
   - id=2091188848244273532 — "In theory. The page the user comes in from the search engine should have the country/language right. If it is the right version, why still auto-switch."
   - id=2091187822300643663 — "My browser is English. I search in Chinese and click into your site, you jump me to English? At that moment the page I click into in theory should be domain.com/zh-hans/, then you just 301 me to the English site?"
6. Yahoo outside Japan uses Bing's engine. Yahoo Japan uses Google. Yahoo Japan plus Bing can take 50% of traffic. Remember to submit the site to Bing Webmaster, about the same as GSC.
   - id=2091014853863637176 — "Yahoo outside Japan all use Bing's engine. Japan's Yahoo uses Google. Japan Yahoo plus Bing can take 50% of traffic. Remember to go to Bing Webmaster and submit your site, about the same as GSC."
7. If you will do Korean, remember to do Naver. Koreans basically all use Naver. A Korea site without Naver-direction work: effect is cut by more than half.
   - id=2091014853863637176 — "If you will do Korean, remember to go do Naver a bit. Koreans basically all use Naver."
   - id=2075237380844654947 — "If you have a Korea site but do not do Naver-direction optimisation, the effect is cut by half and then some."
8. Going-global Traditional Chinese: remember to think whether you are talking to zh-HK or zh-TW. Hong Kong people read Traditional Chinese and in their head it is Cantonese. If they read your translation and it does not go smoothly, 100% Drop.
   - id=2090743694878290165 — "If you go global and do Traditional Chinese, remember to think whether you are talking to zh-HK and zh-TW. Hong Kong people look at Traditional Chinese and in their head what they read out is Cantonese. If they read your translation and it does not go smoothly, 100% Drop."

hreflang, URL pattern, language-switcher code, what "do Naver a bit" actually is: `[no procedure in corpus]`.

---

## 19. Want to know how to learn SEO, how to do it — read JDs as if you are the candidate

**When:** Someone asks how to learn, how to do it. From junior to SEO head at a unicorn.

**Steps:**
1. First assume you are an SEO job seeker, and you want to go from entry level all the way to SEO head at a unicorn.
   - id=2091060807065117104 — "First assume you are an SEO job seeker, you hope to go from entry level all the way to becoming SEO head at a unicorn company."
2. Then just look at JDs on LinkedIn. Try to look at US, Europe, Australia giant-company JDs, or well-known award-winning SEO Agency JDs.
   - id=2091060807065117104 — "Then you just look at JDs on LinkedIn. Try to look at US, Europe, Australia giant-company JDs, or those well-known, award-winning SEO Agency JDs."
3. You can skip domestic giant-company JDs. Example: Feishu's JD, an insider can tell at a glance it is wrong.
   - id=2091060807065117104 — "You can skip looking at domestic giant-company JDs, for example this Feishu JD, an insider can tell at a glance it is wrong."
4. Observation: most AIO / GEO roles have merged with SEO. Some companies turned the old SEO role into Discoverability, especially in the US. Manager+ leans AEO / GEO.
   - id=2091060807065117104 — "The trend I currently observe is that most AIO, GEO roles have merged with SEO. Some companies turned the previous traditional SEO role into Discoverablity, especially the US."
   - id=2091727382726205949 — "You can look at these industry-leader companies' moves. Manager and above roles are all leaning into AEO, GEO."
5. The higher you go in this role, the more you need CS and IT background. Basically a hexagon fighter. You can look at Klook's SEO Director.
   - id=2091060807065117104 — "The higher you go in this SEO role, the more you need CS and IT background, basically you are a hexagon fighter. You can look at Klook's SEO Director."
6. Almost every name-brand company and Agency is not paying people to write blogs and build links. The writing role is separate: Content, Editor, or Content Strategist.
   - id=2091060807065117104 — "Then you can almost discover that name-brand companies and Agencies have not spent money hiring people to write blogs and do backlinks. The writing-content role is separate, all called Content, Editor or Content Strategist."

If he hired: learn while doing real work, have your own judgment, have commercial sensitivity, do not mechanically execute SOP (id=2091761728241766791). That is a hiring bar, not a curriculum.

---

## 20. Want a course path — learningseo.io first, then the academies

**When:** "Today a student asked me how to learn SEO." He has sat Ahrefs / Semrush / Hubspot / Moz / Coursera / Udemy, free and paid, "at least spent a few thousand dollars."

**Steps:**
1. If you want to walk it from the start, unless you truly love it, he does not recommend it.
   - id=2091453544683729230 — "If you want to walk it from the start, unless you truly love it, otherwise I do not recommend it."
2. First recommendation is definitely follow Aleyda's SEO Roadmap on https://learningseo.io/. "The most complete systematic SEO learning path so far, basically full coverage."
   - id=2091453544683729230 — "First recommendation, definitely follow @aleyda's https://learningseo.io/ SEO Roadmap to learn. This SEO learning Roadmap is the most complete systematic SEO learning path so far, basically full coverage."
3. If you learn very fast and are gifted, you can go back to Ahrefs, Semrush, Moz, Coursera courses.
   - id=2091453544683729230 — "If you learn very fast, gifted, you can go back and look at Ahrefs, SemRush, Moz, Coursera courses."
4. Ahrefs Academy and Semrush Academy "both count as relatively frontier things."
   - id=2091453544683729230 — "Ahrefs and SEMRush courses both count as relatively frontier things."
5. Moz is paid-for-a-certificate, you can judge yourself. Coursera is paid; for zero foundation it is quite good.
   - id=2091453544683729230 — "Moz is paid and gives a certificate, you can judge yourself. Coursera courses are also paid, I think going to learn from zero foundation is quite good."
6. For 2026, Udemy stuff is not recommended. A lot of it is small sites, WordPress, the most basic things.
   - id=2091453544683729230 — "For 2026, Udemy stuff is not recommended. A lot of it is small sites, Wordpress and the most basic things."

He does not map the roadmap to a calendar. This is a pointer, not a syllabus he wrote.

---

## 21. Author LinkedIn must link to the site, site must link to the author's LinkedIn

**When:** Blogs, site content, content marketing. "Writing blogs and not talking about the author concept is like dating and not getting married — playing rogue." Going-global technical background should be used. "The hardest way to raise SEO."

**How Google judges a content author's reputation (QRG Section 3.3.4, the list he named):**
1. Educational Degrees
2. Co-authors
3. Citations
4. Employment History
5. Influencers on Social Media platforms
   - id=2091381622616797394 — "How Google judges a content author's reputation. Among them it mentioned a few points 1. Educational Degrees 2. Co-authors 3. Citations 4. Employment History 5. Influencers on Social Media platforms."

**The setup he calls the preferred solution:**
1. Educational Degrees and Employment History — on this whole earth only LinkedIn can do those two. So the author's LinkedIn must link to the site, and the site must link to the author's LinkedIn.
   - id=2091381622616797394 — "Educational Degrees, Employment History, these two things, on this whole earth only Linkedin can do. So the author's Linkedin linking to the site, the site linking to the author's linkedin, this thing is the preferred solution."
2. Going-global, technical background: your site can become a project of your developer studio. Get your own GitHub and LinkedIn done. The chain is: site A <-> developer site <-> GitHub/LinkedIn. Then on the developer site write a vision, an ideal description.
   - id=2091198495197913207 — "Your site can become a project of your developer studio. … Get your own GitHub, Linkedin done. This is the most convenient thing for realising a site's EEAT. Site A <-> developer site <-> GitHub/Linkedin. Then on the developer site write a vision, an ideal description of yours."
3. Get LinkedIn done, do entity linking with the site, use GitHub if you have it, and make yourself an expert in some field.
   - id=2090750446839476639 — "The hardest way to raise SEO is actually linkedin. … Get Linkedin done, do entity linking with the site, if you have github use it, make yourself into an expert in some field."
4. Fake authors definitely do not work. QRG Section 4.5.3. What does a fake author look like? Look at Alibaba.
   - id=2091381622616797394 — "And fake authors definitely do not work. Section 4.5.3 already talks about it."
   - id=2091739865121783923 — "Fake authors will definitely get executed by Google, this thing is the floor. What does a fake author look like? You can look at Ali."
5. Google looks at the author entity, public resume, LinkedIn, background, and whether these can be cross-verified.
   - id=2033390752001335397 — "But Google looking at authors is not only looking at you writing a name. It looks at the author entity, public resume, LinkedIn account, industry background, and whether these pieces of information can be cross-verified."
6. Social: X / Youtube / Ins can raise author authority; "I think Xiaohongshu, official accounts probably have no use."
   - id=2091381622616797394 — "Social Media Platform is like us doing X, Youtube, Ins and so on, it can also raise your authority as an author (I think Xiaohongshu, official accounts probably have no use)."

The grey-area version "if you do not want people to know it is you, that is another way of doing it" — that way is not written (id=2091198495197913207).

---

## 22. If you insist on publishing / "spreading words" / scaling volume

**When:** Already using a workflow / agent to batch blogs and still putting an author. He does not recommend the road. Floor only.

**Steps:**
1. Fake authors will definitely get executed by Google. This is the floor.
   - id=2091739865121783923 — "Fake authors will definitely get executed by Google, this thing is the floor."
2. Use your own company as the Organization author. Schema he gave: "@type":"Organization", name + url.
   - id=2091739865121783923 — "If you insist on publishing, want to \"spread words\", raise volume. Use your own company as the Organization author." plus the JSON-LD block with "@type":"Organization", name, url.
3. If you cannot verify authenticity, better not put an author. Or just put the site itself.
   - id=2091744284668305427 — "If you have no way to verify authenticity, better not put an author. Or just put your site itself."
4. If you got hit because of AIGC content, after you delete it, that is enough.
   - id=2091739865121783923 — "If you got hit because of AIGC content, after you delete it, that is enough."

How you know "deleted enough", whether to file reconsideration after delete — not written.

---

## 23. Login page to highest quality

**When:** Day-to-day SEO, budget allowing, push every surface to the top. Login pages exist on most going-global, membership, payment sites. Source: QRG section 8.4, page 83.

**If you want to optimise the login page, roughly consider these to reach highest quality:**
1. Disclosure about information protection?
   - id=2091376367740789153 — "If you want to optimise the login page, you roughly have to consider the following things to reach highest quality - Disclosure about information protection?"
2. Did you install something like a firewall?
   - id=2091376367740789153 — "Did you install something like a firewall?"
3. Is register complete? Is there a forgot-password function?
   - id=2091376367740789153 — "Is the register function complete? Is there a forgot-password function?"
4. Is your register/login system on a third party? Is your login page too simple?
   - id=2091376367740789153 — "Is your register login system on a third party? Is your login page too simple?"

He said "roughly consider." QRG case not unpacked. List ends.

---

## 24. What you do for SEO: Idea, conversion path, Money Page and Trust

**When:** Doing SEO is to make money, not to generate electricity for love.

**Steps:**
1. You have to have an Idea that can make money.
   - id=2090983234146574708 — "Doing SEO is to make money, not to generate electricity for love. Then what you have to do is very simple, you have to have an Idea that can make money."
2. Then get the conversion path through.
   - id=2090983234146574708 — "then get the conversion path through."
3. Then what you optimise is your Money Page, your Trust.
   - id=2090983234146574708 — "Then what you have to optimise is your Money Page, your Trust."
4. He thinks you should do money page. Competition is bigger, but users convert from your service / money page, not from blogs.
   - id=2091775475635073373 — "I think you should do money page. Although money page competition is big, users will all convert from your service, money page, not blogs."
5. Find a way to do the highest-conversion pages. Unless you are doing it for Adsense.
   - id=2088639745807278589 — "Find a way to do the highest-conversion pages. Unless you are doing it for Adsense."
6. A site and business that has not even run regular Digital Marketing channels, then inexplicably doing "GEO", is the stupidest thing.
   - id=2064910376060498033 — "A site and business that has not even run regular Digital Marketing channels, inexplicably doing \"GEO\", is one of the stupidest things."

How to optimise the Money Page, how to build Trust — not unpacked on this thread. Regular Digital Marketing itself has no steps.

---

## 25. PSEO — original system underneath, or it gets smashed in half a year

**When:** Programmatic / spreading content. Same money-page thread.

**Steps:**
1. Find a way to do the highest-conversion pages. Unless you are doing it for Adsense.
   - id=2088639745807278589 — "Find a way to do the highest-conversion pages. Unless you are doing it for Adsense."
2. PSEO is best if it has a set of original things holding it up (your own algorithm, rating system, data, product). Otherwise it will get smashed within half a year.
   - id=2088639745807278589 — "PSEO is best if it can have a set of original things holding it up (whether your own algorithm, rating system, data, product), otherwise within half a year it will get smashed."
3. No matter how high the site authority, as long as PSEO and the spread content are not original, basically this year there will be a problem.
   - id=2088639745807278589 — "No matter how high the site authority, as long as PSEO and the spread content are not original, basically this year there will be a problem."

How to design that algorithm / rating system: not written.

---

## 26. Personal Branding — stand up your own site and gather everything

**When:** You want Personal Branding, or you want to use degree, Title, company experience.

**Steps:**
1. You should prepare to make your own site, and gather all your things together.
   - id=2091316062709309490 — "You should prepare to make your own site, gather all your things together."
2. Finding the domain has a lot of particularity. Best find a domain directly related to your name. Best not use a stage name.
   - id=2091316062709309490 — "Finding the domain has a lot of particularity. Best find a domain directly related to your name. Best not use a stage name."
3. If your name collides with a celebrity, you can consider changing a name, because the domain probably cannot be bought.
   - id=2091316062709309490 — "If your name collides with a celebrity, you can consider changing a name, because the domain probably cannot be bought."
4. Domain can be .com, .digital, .io, .ai, .dev, and so on.
   - id=2091316062709309490 — "Domain can be chosen .com, .digital, .io, .ai, .dev and so on."
5. TLD pick in his English: .com > .ai > .io. If you decide to make mobile apps, use .app because great names are still available.
   - id=2033312223096086964 — "I will pick .com > .ai > .io. If you decide to make mobile apps, then use .app because you can find great domain names still available under .app."
6. More special trades (lawyer, dentist, psychologist, engineer, Urban Planner, accountant, Financial planning) who want the personal site to get clients can use a local TLD. Examples: jameslinlawyer.com.au; lindawuaccounting.co.uk.
   - id=2091316062709309490 — "If you are a more Special trade, for example lawyer, dentist, psychologist, engineer, Urban Planner, accountant, Financial planning… hoping to get clients through your own personal site, you can get a local domain. For example an Australian lawyer can get a jameslinlawyer.com.au. A UK accountant can get a lindawuaccounting.co.uk."

What goes on the site, what the homepage ranks for — not wired to {modifier} + Entity on this thread.

---

## 27. How he writes Non-commodity Content

**When:** His own method while tweeting. Google said at North America Search Central Live that AI Search prefers Non-commodity Content.

**Steps:**
1. Every concept or share he throws out has a concrete instance as evidence.
   - id=2091487107806323136 — "These two days while writing tweets, I have been using the Non-commodity Content write-up: every concept I throw out, or share, will have a concrete instance as evidence."
2. On the content layer only, he chooses to hand-make it fully manual. Write wherever the thought goes.
   - id=2091487107806323136 — "I am AI Native, a heavy AI user. Only on the content layer, I choose to hand-make it fully manual. You read that right, these two days the content I wrote is fully hand-made, write wherever I think. Main play is true feeling flowing out."
3. Whether SEO or Social Media, sincerity is the sure-kill technique.
   - id=2091487107806323136 — "Whether SEO or doing Social Media, sincerity is the sure-kill technique. Tokens cannot buy emotion fluctuation."

This is *his* writing, not a production SOP for you. Same tweet: as of today, automation / AIGC probably still cannot fully realise Non-Commodity with no human intervention.

---

## 28. Semantic HTML / MC — every page's code follows this

**When:** People who have read MC (Main Content) in the EEAT QRG. Stops Div-all-the-way-down from shipping non-main stuff into the algorithm.

**Steps:**
1. From the Semantic HTML angle, every page's code must follow: header, nav, main, section, section, aside, footer.
   - id=2090738619808088255 — "From the Semantic HTML angle, it is that every page's code must follow <header> <nav> <main> <section> <section> <aside> <footer> this kind of write-up."
2. h1 h2 h3 img table, ul, all kinds of HTML elements must be paid attention to. A lot of plug-and-play design libraries have problems.
   - id=2090738619808088255 — "h1 h2 h3 img table, ul, all kinds of html elements must be paid attention to. A lot of plug-and-play design libraries have problems."
3. What is MC? The stuff inside main. If you Div all the way down, things unrelated to main content get sent into the algorithm system.
   - id=2090738619808088255 — "What is MC? The stuff inside <main>. If you Div all the way down, it will cause some things unrelated to main content to be sent into the algorithm system."

No QA step, no tool.

---

## 29. New ecommerce — go Shopify; then second-pass feed / schema; three things that "rise fiercely"

**When:** New ecommerce from 2026 on. Old site that already makes money: you can observe a bit more. New site: you do not need to hesitate one second.

**Steps:**
1. From 2026 on, if you will do ecommerce, charging at Shopify is definitely not wrong. You do not need to pick anything else. Two modes: pure Shopify / headless. Why: Shopify's feed integration is the most perfect.
   - id=2091062668056838266 — "From 2026 on, if you will do ecommerce, charging at Shopify is definitely not wrong, you do not need to pick anything else at all. … Shopify two modes - pure shopify - headless Headless. Why? Because shopify's feed integration is the most perfect."
2. If theme-modding can sell directly, then theme-mod. Headless is generally only when there is more customisation demand.
   - id=2091369232944734595 — "If theme-modding can sell directly, then theme-mod. Headless is generally only done when there is more customisation demand."
3. Using Shopify you do not build wheels. You can spend time on fruit-done CRO, product description, PDP design, Collection classification, shooting product photos. You only need a very small cost to get Merchant Centre done.
   - id=2091199226856521823 — "Using Shopify you don't build wheels. You can spend time doing other things, for example fruit-done CRO, product description, PDP design, Collection classification, shooting product photos and so on. … You only need to spend a very small cost to get Merchant Centre done."
4. Product feed needs extra second-pass optimisation, done in Merchant Centre; Shopify native support is not good enough. Product schema also needs a second-pass magic-mod. If you get these two done, there will be a qualitative leap.
   - id=2089230010616062038 — "Product feed needs extra second-pass optimisation, it has to be done in merchant centre, shopify native support is not good enough. Product schema also needs a second-pass magic-mod. If you get these two done, there will be a qualitative leap."
5. He recently found: Shopping feed (Merchant Centre), image alt, product-image quality — after these three are done well, it rises fiercely.
   - id=2091995138864406654 — "I recently discovered, Shopping feed (merchant centre), image alt, product image quality, after these three things are done well, it will rise fiercely."

How to second-pass the feed, how to magic-mod schema: `[no procedure in corpus]`. Shopify-as-the-only-platform is his absolute; treat as overclaim.

---

## 30. Ecommerce besides the feed — reviews, reputation, prove you are first; HTML on the product card

**When:** "Ecommerce has a lot of things you can do." Reply-level list, not a full audit.

**Steps:**
1. One very important thing is review, brand reputation, and how you prove you are first in this field — you are the manufacturer; you collaborate with designers; you have won awards, and so on.
   - id=2092036772687716771 — "Ecommerce has a lot of things you can do.. one very important thing is review, brand reputation, and how you prove you yourself are first in this field. - You are the manufacturer - You collaborate with designers - You have won awards and so on."
2. On the technical side it is HTML things: does your product card use something like article; is Breadcrumb done; is Schema Markup complete.
   - id=2092036772687716771 — "Technical side is HTML things. For example does your product card use <article> and the like. Is Bread Crumb done. Is Schema Markup complete."

No review platform, no schema types, no breadcrumb code. Do not turn this into a generic ecommerce audit.

---

## 31. Questions he actually asked Google staff

**When:** Search Central Live, on the floor. Used to line official talk up with the docs.

**What left his mouth:**
1. To Gary: about EEAT / Quality Rater Guideline, does Google have an algorithm that runs automatically? How would effort be measured automatically?
   - id=2092090944648581505 — "At the Shanghai Google event I asked Gary: about EEAT, inside this Quality Rater Guideline thing, does Google have an algorithm that runs automatically? For example, how would a thing like effort be measured automatically?"
2. In Shanghai he specifically asked official staff — the tweet writes the *answer* he got: Gemini is not under the Search department; they are different departments. The original question sentence is not on the tweet.
   - id=2091364706703581191 — "In Shanghai I specifically asked Google official people, Gemini is not under the Search department, they are different departments."

He did not publish a "questions to ask at every conference" list. Another floor line he tells you to taste carefully: machine-learning ranking signals were trained on "content created by humans for humans" (id=2091362717907251353).

---

## 32. GSC Generative AI numbers — the questions he asks, not a pull-data SOP

**When:** You can already see Generative AI in GSC. He is asking other people, and giving a measuring frame.

**Questions he asked:**
1. In GSC, Generative AI data, what is your highest?
   - id=2088839484083404844 — "GSC Generative AI data, what is your highest?"
2. Will you treat this as a goal, or a KPI?
   - id=2088839484083404844 — "Will you treat this as a goal, or a KPI?"
3. Do Citation and key conversion data line up?
   - id=2088839484083404844 — "Do Citation and key conversion data line up?"
4. Can real conversions from AI traffic exceed 5% of the whole site?
   - id=2088839484083404844 — "Can the real conversions brought by traffic from AI exceed 5% of the whole site?"

Bing AI Performance Dashboard: Total Citations = times you were seen or cited as Source in an AI-generated answer (id=2021379383303471595). How to filter AI Mode in GSC — he says you can try the SEJ article; he did not write the clicks (id=2090312730695913704). `[no procedure in corpus]` for the GSC click-path.

---

## 33. {brand + keyword} search volume and that page's rank

**When:** SEO Research while writing the Shenzhen SEO Conference PPT. Premise: "when the sites are all extremely good (immortal-fighting level)."

**Steps:**
1. Look at the size of {brand + keyword} search volume and that page's rank.
   - id=2090684152328945976 — "When the sites are all extremely good (immortal-fighting level), the size of {brand+keyword} search volume and that page's rank is basically a linear consistent relationship."
2. He tested 5 keyword groups; basically all were like this.
   - id=2090684152328945976 — "Tested 5 groups of keywords, basically all were like this."

Which 5 groups, which tool for volume, how rank was recorded — not written. Do not generalise into DA to rank.

---

## 34. About Us must qualitatively position the brand; then check whether that definition can cover the topics

**When:** SEO small tip; also the EEAT page people treat as an afterthought. Theory from 2024 Site Reputation Abuse + Content Warehouse Site Focus.

**Steps:**
1. Your site must have an About Us page, and a Contact Us page.
   - id=2090291222556578070 — "Your site must have an About Us page, and a Contact Us page."
2. Inside About Us you must give your site, your brand, a qualitative positioning. That positioning will affect your final rank. Site Focus basically decides what you can rank and what you cannot rank.
   - id=2090291222556578070 — "Inside the About Us page you must give your site, your brand, a \"qualitative positioning\". This qualitative positioning will affect your final rank. … Google has a thing called Site Focus. Site Focus basically decides what you can rank, what you cannot rank."
3. English version of what the page should establish: who is behind the site; what the business actually does; what experience or credentials support it; whether the site’s content aligns with the real-world entity behind it.
   - id=2033192558889963680 — "It helps establish: 1.who is behind the site 2.what the business actually does 3.what experience or credentials support it 4.whether the site’s content aligns with the real-world entity behind it."
4. Give yourself a definition, then whether it can cover the topics you want to cover. If the definition is too wide at the start, you will definitely be slow. If it is too narrow, too vertical, you will have to change later.
   - id=2091897363598315734 — "That is, you give yourself a definition, then whether it can cover the topics you want to cover. If at the start the definition is too wide, you will definitely be slow doing it. If at the start the definition is too narrow, too vertical, in the future you will have to change again."
5. Relevance: you can group by category. Get classification done, do not lay everything flat. Example: you are doing SAAS, at least SAAS is a category. He would navigate SEO / Digital Marketing first, then development / AI because he can build.
   - id=2091897363598315734 — "The relevance problem you mentioned, you can group by category. I feel I get classification done. Not laid flat together. You are doing SAAS, at least SAAS is a kind of category."
6. You can look at how bigger North-America listicles and review sites classify, or how game-rank sites split (shooter, mobile, multiplayer) and put related things together.
   - id=2091897967330619745 — "You can go look at how some bigger North-America listicles, and review sites, do classification. Or look at game-rank sites, how they split. For example shooter class, mobile class, multiplayer class. Put related ones together."

Stay-focus line from the Warehouse post: small-radius (siteRadius) sites succeed more easily in a vertical. Do not do a bit of east and a bit of west, randomly spreading content; stay focus (id=2091894056687431704).

No About outline, no word count, no "must put team photos."

---

## 35. Stay focus — small siteRadius, do not spread content

**When:** After opening QualityAuthorityTopicEmbeddingsVersionedItem in the Warehouse leak. Used to tell people not to write sing-dance-Rap on an SEO site.

**Steps / rule:**
1. Open the leak block: siteFocusScore, siteRadius, embedding (page/site).
   - id=2091894056687431704 — "First the block: QualityAuthorityTopicEmbeddingsVersionedItem. A few look-ats of this block 1. siteFocusScore 2.siteRadius 3 embedding (embedding vector) page/site."
2. siteFocusScore = your score for a specific vertical. If the whole site writes SEO, SEO Focus is higher.
   - id=2091894056687431704 — "siteFocusScore means your site's score for a specific vertical. For example me, if my whole site writes SEO, then my Focus score on SEO will be higher."
3. siteRadius = how far each page vector sits from the site-center vector (siteEmbedding). Smaller radius = more unified; larger = more mixed.
   - id=2091894056687431704 — "siteRadius is the degree of deviation / dispersion of each page vector on the site from the site-center vector (siteEmbedding) (the smaller the radius, the more unified all on-site content is; the larger the radius, the more mixed the span of articles)."
4. Recommended move: small-radius sites succeed more easily in a vertical and more easily build expert weight. Do not do a bit of east and a bit of west, randomly spreading content; stay focus.
   - id=2091894056687431704 — "Small-radius (siteRadius) sites succeed more easily in a vertical, more easily build your \"expert weight\" on this topic and field, this is the method I recommend. Definitely do not do a bit of east and a bit of west, randomly spreading content, stay focus."

This is a stay-vertical rule, not an IA template.

---

## 36. Huge sites avoiding Spam — internal ML class, low-quality pages actively No Index

**When:** He retells @kimuyan / CyberAgent on Ameba (92M blogs, 2.8B articles). Used to ask: you do 100 pages, 1M pages, Billion scale — what is the strategy for each. Quality should consider the site as a whole.

**Ameba's set (Kimura's, not Loki's SOP):**
1. Bring in internal Spam Filtering; build an internal Machine Learning program.
   - id=2092027807719444899 — "They brought in an internal Spam Filtering mechanism, that is they made an internal Machine Learning program."
2. Classify on-site articles into Quality and Spam.
   - id=2092027807719444899 — "Take the articles on the site and do Quality and Spam classification."
3. Actively No Index low-quality, AI Slope, Spam articles.
   - id=2092027807719444899 — "Take low-quality, AI Slope, Spam articles and actively go No Index."

His three scale questions have no answers in the tweet. `[no procedure in corpus]` for 100 / 1M / Billion-page strategy.

---

## 37. Conditions for content that can rank (Shanghai slides wired together)

**When:** After 2025 Bangkok / Hong Kong and 2026 Shanghai / Sydney Search Central Live. Used to judge what content will probably rank.

**Conditions he wired:**
1. Close to human-written.
   - id=2091362717907251353 — "So, content that can have ranking roughly needs the following conditions: 1. Close to human-written."
2. Has Quality.
   - id=2091362717907251353 — "2. Has Quality."
3. Quality's definition is Effort and Original.
   - id=2091362717907251353 — "3. Quality's definition is Effort and Original."
4. Wired: if AI-written stuff can be close to human-written, spend heart-force (effort), and is original content, then it will have ranking. Original here is not you finding a few sites and stitching them.
   - id=2091362717907251353 — "You wire them together: if AI-written stuff can be close to human-written, spend heart-force (effort), and is original content, then it will have ranking. The original here is not you finding a few sites and stitching them."

This is a judgment, not a production line. He asks: how do you make an AI system, spend heart-force, to do original content — and does not give that system.

---

## 38. What Search is, vs Gemini — so you stop mixing the jobs

**When:** After Search Central Live Shanghai, he finally wrote the recap.

**Steps / definitions he uses as a work split:**
1. Three Google concepts: traditional Search / AI Mode · AI Overview / Gemini.
   - id=2091364706703581191 — "At Google here SEO/AIO/GEO have three concepts 1. Traditional Search 2. AI Mode / AI Overview 3. Gemini."
2. Traditional Search does three things: crawl sites, index sites, serve (rank).
   - id=2091364706703581191 — "Traditional Search, that is what we used to call SEO, it does three things, crawl sites, index sites, serve (rank)."
3. AI Mode / AI Overview: the first two steps Crawl and Index are consistent with traditional SEO. Serving adds Grounding on Search Index Query Fanout. Same database.
   - id=2091364706703581191 — "AI Mode/AI Overview, in the first two steps Crawl and Index, is consistent with traditional SEO! Its mechanism is fully consistent! … The Serving part… AI Mode and AI Overview, under the traditional ranking mechanism, newly added Grounding on Search Index Query Fanout. So their database is fully consistent."
4. Gemini: uses crawlers for data; indexing is Not part of search. He asked staff: Gemini is not under the Search department.
   - id=2091364706703581191 — "Gemini, uses crawlers for data… indexing here writes Not part of search. In Shanghai I specifically asked Google official people, Gemini is not under the Search department, they are different departments."
5. Optimising Google SEO and AIO: the AI Mode / AI Overview line is doing SEO, no difference at all.
   - id=2091364706703581191 — "Optimising Google SEO and AIO: the AI Mode / AI Overview line is doing the SEO thing, no difference at all."
6. Optimising Gemini you can refer to traditional SEO theory. Official Google Search releases are limited to traditional SEO, AI Mode / AI Overview, and have nothing to do with Gemini.
   - id=2091364706703581191 — "Optimising Gemini you can refer to that traditional SEO set of theory. … So the things Google Search official releases that everyone usually watches are limited to traditional SEO, AI Mode / AI Overview, and have nothing to do with Gemini."
7. Anything whose entrance is Google.com (Search, ecommerce, Image, Video, News, Discover, AIO, AI Mode) he calls Google Search.
   - id=2091071455350169891 — "Google SEO includes traditional Search, ecommerce, Image Search, Video, News, Discover and so on. As long as the entrance is going in from Google.com, I think it can all be called the Google Search part. Including the newest AI Overview, AI Mode. But, Gemini itself, is not under Search."

No Gemini-specific SOP. How to do GEO — "If you ask me how to do AEO, GEO? Right now I also have no way to reply to you" (id=2091727382726205949).

---

## Named topics with no steps — `[no procedure in corpus]`

He named, did, or asked someone about these. The tweets do not leave a followable program.

### AEO / GEO how-to
`[no procedure in corpus]`
- id=2091727382726205949 — "If you ask me how to do AEO, GEO? Right now I also have no way to reply to you. I feel their underlying logic is about the same as SEO, both are optimising your brand and site entity, letting LLM, AI recommend your brand and product."
- id=2079109647160734202 — "Anyway I just took traditional SEO to the extreme, traffic from ChatGPT rose. Never written a blog, never posted Reddit, never done semantic matching, never sent a PR draft, also never done schema, never written FAQ." That is an anti-list, not a method.
- id=2092054444854968463 — "But how to get found and how to get chosen? I guess it's called magic."

### How to rank Google Top Stories
`[no procedure in corpus]`
- id=2091729433279496522 — "In 2023 at the company I researched out the method for how to rank Google Top Stories. After my writer colleague learned it, no matter what he wrote he was higher than US front-line news sites." Method not written.
- id=2091387930963263678 — News SEO three lines (Top Stories / News / Discover) only get topical authority plus "1 did not get site architecture done, 2 did not have Author Profile, degree and other entity links." Steps: none.

### hreflang / ccTLD / international setup recipe
`[no procedure in corpus]`
He has copy-Apple, do-not-auto-jump, submit Bing, do Naver, think zh-HK vs zh-TW (procedure 18). The Klook JD mentions "ccTLDs, Hreflang" as DNA, not as his recipe (id=2091844216980979877). No hreflang code, no URL-pattern table.

### Algorithm Recovery
`[no procedure in corpus]`
- id=2092067172021608918 — "Starting last year the most delightful thing in the SEO world is that everyone received more Algorithm Recovery consulting business." No recovery steps.
Buying more links after an update is the anti-method (id=2090396597066899635, id=2090697074153283687).

### Day 0 Framework for AI Inclusion
`[no procedure in corpus]`
- id=2033414646775083406 — Talk title: "Rebuilding for the Machine: A \"Day 0\" Framework for AI Inclusion" plus "brands fail the AI readability test." Framework steps are not in the tweets.

### How to get Doubao / Deepseek to recommend you
`[no procedure in corpus]`
- id=2091716914599067838 — "I do not really understand Doubao and deepseek's mechanism, I myself am also learning."

### Google Site Migration standard flow
`[no procedure in corpus]`
He says it exists and drops https://support.google.com/webmasters/answer/9370220 (id=2091309003397902703). The official runbook is not copied into the tweet.

### Finish one keyword-analysis round
`[no procedure in corpus]`
Tools exist (procedure 8-9). Cluster / map / difficulty cutoff do not.

### Shopify product feed / product schema second-pass magic-mod
`[no procedure in corpus]`
Must do, in Merchant Centre (id=2089230010616062038). How: not written.

### How to find AI Mode traffic in GSC
`[no procedure in corpus]`
Points at an SEJ article, "you can try" (id=2090312730695913704). Clicks are not in his tweet.

### 100 pages / 1M pages / Billion pages, each strategy
`[no procedure in corpus]`
Questions only (id=2092027807719444899).

### Soft 404 system hunt
`[no procedure in corpus]`
Harm + Angular timeout case + Alibaba 200-status error pages (procedure 12). No item-by-item check table.

### Crawl budget, how to fix render timeout
`[no procedure in corpus]`
Named at first enlightenment (id=2091301352463102268). No repair method. CWV now has a field-data *panel* (procedure 39) — still not a repair playbook and still not the main lever.

### How to build links
`[no procedure in corpus]`
"Useful, but do not chase. Chase and you waste money." Stopped a $20K USD/mo budget; later stopping had not a hair of impact (id=2090685656079241520). No construction process.

### How to design and sell a generic SEO / GEO Agent
`[no procedure in corpus]`
Logic does not work; he only builds process / agent / automation / prompts for himself (id=2092067172021608918, id=2092073561171398727). How he built those: not written.

### llms.txt file format / where to put it
`[no procedure in corpus]`
He only splits the word: Google Search / AIO / AI Mode do not use it; Gemini is another department; broad GEO (chatbots / all platforms) still might need LLM.txt (id=2071840010593358218). No spec.

### Rest of Content Warehouse
`[no procedure in corpus]`
He opened QualityAuthorityTopicEmbeddingsVersionedItem and contentEffort. Nothing else.

### Batch-imitate Google Audit without GSC
`[no procedure in corpus]`
- id=2091832629112996343 — "If you do not have GSC permission you can use this to batch-imitate Google to Audit. GSC is definitely the most accurate." The tool is not named in the tweet text.

### What he pays writers
A price, not a procedure: 800-1K AUD long landing, 300-500 a blog, 200 a product page, to a senior Copy Writer (id=2071839385998569488).

---

## Do not import

Do not fill the holes above from: topic cluster, content calendar, CWV-as-main-lever (field panel exists; still not the main lever), featured snippet, generic Local-SEO kits beyond the GBP procedure, CRO frameworks, popular GEO homework (Reddit / schema / FAQ / PR / semantic matching as must-dos), Day 0, three reversals, 5-step First Optimise, hreflang recipes, Top Stories playbooks, feed hacks, or anyone else's GEO "three things."

"Do not mechanically execute SOP" (id=2091761728241766791) is a hiring bar. These lists are scan order.

---

## 2026-08-28 delta (append)

### 39. Local / GBP
**When:** Brick-and-mortar / local (id=2092207366305681808)
1. Bing Business + Apple Business too.
2. GBP team ≠ Search team — run and optimize separately.
3. Site must have map, address, phone, schema, dedicated Contact.
4. Everything done in GBP must exist on the site.
5. Social + reviews. Summary: dirty work.

### 40. CWV field data
**When:** How to read Core Web Vitals accurately (id=2092889660783722868)
1. https://cruxvis.withgoogle.com/#/ — origin + all, 28d, LCP / CLS / INP.
2. Lighthouse / PSI = lab / debug only.
3. CWV is not a named ranking factor; with other page-experience it is ranking-related.
4. Don’t over-invest; don’t lag competitors; late-game all-green helps; do it early because migration is painful.

### 41. Keyword ladder refresh
**When:** Keyword research (id=2092448668712645088). Does not replace procedure 8.
1. Lazy: AI + Ahrefs / DataForSEO.
2. Traditional: Semrush / Ahrefs.
3. Advanced: Trends.
4. Detail: funded Google Ads Planner = most accurate volume.

### 42. Product-first IA
**When:** New product site (id=2093181903579087176)
On day 1 know each page’s query / title / h1 / url. Do not find keywords then invent pages.
He is not a 出海 / 新站 expert (id=2093165450708537490, 2092722291243458579). 出海 category-pick list is `[once]` / `[asserted, hypothetical]` — not a default SOP (id=2092174932323311912).

### 43. Screaming Frog is the one must-have
**When:** Doing SEO (id=2092784685650997342)
Other tools optional. Raw vs rendered. Lumar + Botify = enterprise Frog; do not install at mid-size (id=2092723929249132561).

### 44. Language lock
**When:** GEO / AI Search questions (id=2092248676324520232)
Mechanism + one implication (multilingual for AI-platform exposure). How-to GEO remains `[no procedure in corpus]`.

### 45. Author vectors
**When:** Author entity (id=2092468221794513075)
Bidirectional LinkedIn required. Patent US10599770B1.

### Optional tool note (not a procedure)
GA MCP if tagging / tracking already done (id=2092210684503503245).

## 2026-08-31 delta (append)

### 46. H1 = ranking query
**When:** Page HTML (id=2093224389605261381, 2093236681449332851)
1. H1 should carry the keyword that page is meant to rank for.
2. Poetic non-entities / beautiful empty prose: Google cannot parse.
No H1 template.

### 47. sameAs
**When:** Entity (id=2093250660125089901)
Reverse-link, then schema sameAs. No JSON-LD template.

### 48. CN + overseas TLD split
**When:** Brand does China + overseas (id=2093339633614754128)
Copy Apple/Canva. Overseas `.com` then language/region. China `.com.cn` or `.cn`. hreflang fine-config: `[no procedure in corpus]`.

### 49. Bing / IndexNow / engine routing
**When:** Not Google-only (id=2093355461303218245, 2093336738643275842)
IndexNow. ChatGPT/Copilot/Yahoo use Bing. Claude uses Bing; Gemini uses Google; ChatGPT uses Bing. **Do not invent a Bing ranking SOP.**

### 50. JS: Google renders; chatbots often do not
**When:** JS-heavy / AIO (id=2094275636357714095)
Extends JS-off. Check GSC live-index render or Frog Raw vs rendered. Official JS SEO basics link only.

### 51. No tracking params on internal links
**When:** PMs want UTM on internal links (id=2094278631296315660)
Anti-crawler. Canonical does not save it in the moment. Collect server-side. Clean URL = one ID card.

### 52. 千人千面 vs crawler
**When:** Product wants personalization (id=2094314984310514045)
“你给爬虫看哪一面？” Cloaking-adjacent. No test script.

### 53. Crawl Budget Management
**When:** Enterprise / huge site (id=2093665083486523872)
Know URL count, indexed vs not, what was crawled. Soft 404 is the most important point. Item-by-item playbook: `[no procedure in corpus]`.

### 54. Spam policy dual track
**When:** Cloaking / spam requests (id=2094335458423742688)
Algorithm + Manual Action. Throw official spam-policies doc. Appends to existing Manual Action.

### Optional tool / stack notes
- Microsoft Clarity: session heatmap, free panel. Not a ranking cause (id=2093511886683951613).
- WordPress `[once]`: overseas SEO default. Scoped vs Shopify (id=2093542304372129882).
- Search Central YouTube 101 (id=2094325559820197987).

Gaps still `[no procedure in corpus]`: GEO how-to, hreflang fine-config, Bing ranking SOP, crawl-budget item-by-item, China GEO 规范 as imported doctrine.

## 2026-09-03 delta (append)

### 55. Brave Search / Claude routing
**When:** Claude / Brave / JS-heavy SPA (id=2094338319807078577)
1. Claude uses Brave Search API. Brave has its own crawler/index.
2. Check not blocking Brave.
3. Brave likely does not render JS → SPA fails; do SSR.
4. Submit https://search.brave.com/submit-url
5. No webmaster tool → pure SEO.
Keep tension with Claude→Bing. Not a GEO how-to.

### 56. IndexNow — Google out
**When:** IndexNow / Bing / Naver / Yandex (id=2094396130427900220)
Google does not support IndexNow (said three times). Connect Bing, Naver, Yandex. https://www.indexnow.org/ Tightens §49. **Do not invent a Bing ranking SOP.**

### 57. FAQ — not every page
**When:** Copycat FAQ on every page/blog (id=2095122990493282767, 2095157057255268605, 2095157590301061376)
Google dropped FAQ rich results. FAQ is for user questions (e.g. buying). Service/product pages may still have FAQ; blogs usually not. Intuition.

### 58. SaaS Trust as QRG online-store
**When:** SaaS / money Trust (id=2094935978851078531)
Payment system + customer service named. Stripe mention/logo. Trust / Help / Contact. DNA of a real product, not a bolted SEO kit. Manus: pricing → trust.manus.im; help.manus.im/en.

### 59. Product /updates changelog
**When:** Outbound / AI product (id=2094710822136418378, 2094711722024325186)
Extends AI-product changelog. `/updates` pages can rank core product queries. A log page helps any outbound product (like git commits).

### 60. Ecommerce blogs / Foundation first
**When:** Shopify / ecommerce content (id=2095159020072124578, 2095320035690725505, 2095344173826363791)
Blogs OK only for product / feature / own Guide. Do not auto-generate related long-tail blogs while PDP / Collection / Foundation is broken. Shopify still better ecommerce architecture; being K’d is the domain. Keep Shopify `[overclaim]` AND WordPress `[once]` scoped.

### 61. PageSpeed after product+content
**When:** Someone leads with PageSpeed (id=2095287266247836131, 2095288889506443712)
Only when product AND content are already good. PageSpeed does not improve content. Content is the ranking key. Authority is another layer. Aligns with CWV-not-main-lever.

### 62. HCU — named; pointer only
**When:** Helpful Content (id=2094576318788833400)
Must practice HCU. Points at article 2094559188676734976. **Do not import the article body.**

### 63. X Articles — optional channel
**When:** Optional content channel (id=2094635693993832480)
Logged-out blog-like pages; Article schema + isAccessibleForFree. Not required homework.

### 64. Person/social carrier `[once/experiment]`
**When:** Site/brand weak (id=2094615467981930559)
Future SEO can be the person. X-account SEO. Chinese as low-hanging fruit. **Not a quit-the-site SOP.**

Gaps still `[no procedure in corpus]`: GEO how-to, hreflang fine-config, Bing ranking SOP, crawl-budget item-by-item, China GEO 规范 as imported doctrine, HCU article body.

### 65. Own product is fastest Effort / Originality
**When:** Quality / EEAT door (id=2094726807568478504)
Own product is the fastest way to raise Originality and Effort — you tell Google and AI why the product is good.

### 66. Fake as hard as real
**When:** Fake authors / fake profiles as an efficiency ask (id=2095347481655840877, 2095348801607491906)
Faking it is as hard as doing it real. Expert-as-author needs a real Profile. YMYL money / health / web3. Strengthens existing fake-author floor.

### 67. llms.txt no-regret (keep both)
**When:** Someone asks whether to do LLM.txt (id=2094440229482721382)
Not causal for AI recommendation; doing it will not hurt. Keep Search/AIO ignore (id=2071840010593358218); still optional for chatbots / no-regret.

### 68. AI Slop / PSEO KPI restatement
**When:** PSEO junk for short-term KPI (id=2094431347851055262)
Restates existing PSEO/spam: junk to punch KPI then jump ship. Not a new production SOP.

### 69. YMYL L = Life
**When:** Medical / YMYL (id=2094438099694833690)
L is Life. Google invests in medical SERPs (莆田系 contrast). Appends to existing YMYL door; not a medical-SEO playbook.
