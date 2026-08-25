# Loki Yan SEO Skill

Unofficial, third-party Agent Skill. It turns the public SEO / AIO / GEO operating logic of **Loki Yan ([@loki_yan_seo](https://x.com/loki_yan_seo))** into a repeatable diagnosis engine.

It models *how he frames a site, what he treats as causal, and what he refuses to do*. Not his voice. Not a biography. Not a generic SEO encyclopedia. **Not affiliated, authorized, or endorsed.**

Use it for Google SEO, international / cross-border sites, technical SEO, EEAT / Trust, AI Overviews / AI Mode, or GEO questions.

> Distilled bottom-up from **979 public posts** (367 originals, 588 replies, 24 reposts; **533** Loki-authored) recovered via CarryFeed, 2025-07-11 → 2026-08-25. The public profile listed 574 statuses when this started and 580 on the last refresh. Older posts were not recoverable. This is not a full-lifetime distillation.

---

## Disclaimer (read this first)

- **Not SEO consulting, and not Loki Yan.** Independent distillation of **public tweets**. Unofficial.
- **His case studies are mostly asserted.** The cleanest before/after stories have no site names, no GSC screenshots, and no independent audit in the corpus. Cite them as `[asserted]`.
- **AEO / GEO tactics are explicitly missing.** He said he currently has no way to answer “how to do GEO.” Do not invent a playbook.
- Decisions stay with you. Absolute-sounding lines (Shopify-only, “you will 100% drop”) are tagged judgments, not orders.

---

## Layout

```
loki-yan-seo-skill/
  SKILL.md              # runnable engine (load this)
  methodology.md        # knowledge SSOT, tweet-id anchors
  references/           # five bottom-up dimensions
  examples/             # output-contract shapes (EXAMPLE data only)
  UPDATE.md             # how new tweets get merged (append, don't overwrite)
  meta.json             # corpus counts + version
  CHANGELOG.md
  LICENSE
```

`SKILL.md` is how to run a task. `methodology.md` is what is true in his words. `references/` is the evidence trail. `examples/` is the output shape. On conflict: methodology wins; if methodology also has nothing, mark `no procedure in corpus`.

Inspired by the *idea* of [ZadAnthony/serenity-skill](https://github.com/ZadAnthony/serenity-skill) (engine + SSOT). This repo is intentionally thicker so the distillation can be audited.

---

## What you get

A diagnosis of *this site*, not a recap of a blogger:

- Task type (decline / new site / growth / hold-the-hill / migration / multilingual / ecommerce / GEO ask / YMYL / personal brand)
- Do first / stop first: 3–7 things actually blocking this site
- Red flags, named
- One-query-per-page table
- Evidence grade: `in-corpus rule` / `[once]` / `[asserted case]` / `no procedure in corpus`
- How to test each change
- Independent review (or a labeled self-check)

**What it refuses:** schema / FAQ / Reddit / PR as required GEO; DA / backlink volume / citations as causes; Day 0 / three reversals / topic clusters; filling in Top Stories, feed hacks, hreflang recipes, recovery algorithms.

---

## Install

```bash
git clone https://github.com/<you>/loki-yan-seo-skill.git <your-runtime-skills-dir>/loki-yan-seo
```

Invoke it the way your runtime discovers skills (`/loki-yan-seo`, `@Loki Yan SEO`, or load `SKILL.md` + `methodology.md` as context). Update with `git pull`.

## Usage

```
/loki-yan-seo traffic dropped 40% after a Shopify theme change
/loki-yan-seo new bilingual site, US + JP, should we IP-redirect
/loki-yan-seo how do we show up in AI Overviews
```

See `examples/` for the expected output shape.

## Method

1. Pull the public timeline (profile statuses + replies + dated search windows).
2. Split into five dimensions: repeated claims, procedures, rejections, named terms, cases.
3. Converge into `methodology.md` and `SKILL.md`.
4. Keep gaps explicit. Do not import blog posts, talks, or generic SEO frameworks unless a tweet itself states them.

## License

MIT for this distillation. Underlying SEO views belong to [@loki_yan_seo](https://x.com/loki_yan_seo). Do not impersonate the original author.
