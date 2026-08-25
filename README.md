# Loki Yan SEO Skill

Unofficial Agent Skill. Turns Loki Yan ([@loki_yan_seo](https://x.com/loki_yan_seo)) public SEO / AIO / GEO operating logic into a diagnosis engine for *this site*. Not his voice. Not a generic SEO encyclopedia.

Use it for Google SEO, international / cross-border sites, technical SEO, EEAT / Trust, AI Overviews / AI Mode, or GEO questions.

Distilled bottom-up from **979 public posts** (367 originals, 588 replies, 24 reposts; **533** Loki-authored), 2025-07-11 → 2026-08-25.

## Install

```bash
npx skills add lynnzc/loki-yan-seo-skill
```

or:

```bash
git clone https://github.com/lynnzc/loki-yan-seo-skill.git <your-runtime-skills-dir>/loki-yan-seo
```

Then invoke `/loki-yan-seo` or load `SKILL.md` + `methodology.md`. Update with `git pull`.

This repo is also a Cursor plugin. After listing, install it from the Cursor Marketplace. Local test: copy the repo into `~/.cursor/plugins/local/loki-yan-seo`.

## Usage

```
/loki-yan-seo traffic dropped 40% after a Shopify theme change
/loki-yan-seo new bilingual site, US + JP, should we IP-redirect
/loki-yan-seo how do we show up in AI Overviews
```

See `examples/` for the output shape.

## What you get

A diagnosis of *this site*:

- Task type (decline / new site / growth / hold-the-hill / migration / multilingual / ecommerce / GEO ask / YMYL / personal brand)
- Do first / stop first: 3–7 things actually blocking this site
- Red flags, named
- One-query-per-page table
- Evidence grade: `in-corpus rule` / `[once]` / `[asserted case]` / `no procedure in corpus`
- How to test each change

It will not treat schema / FAQ / Reddit / PR as required GEO, or DA / backlink volume as causes. Gaps stay gaps.

## Files

| File | Role |
|---|---|
| `SKILL.md` | Engine. Load this. |
| `methodology.md` | Knowledge SSOT, tweet-id anchors. Wins on conflict. |
| `references/` | Five bottom-up dimensions |
| `examples/` | Output shapes (EXAMPLE data only) |
| `UPDATE.md` | How new tweets get merged |
| `meta.json` | Corpus counts + version |
| `.cursor-plugin/` | Cursor Marketplace manifest |

If methodology also has nothing, mark `no procedure in corpus`.

## Method

1. Start from the public tweet corpus.
2. Split into five dimensions: repeated claims, procedures, rejections, named terms, cases.
3. Converge into `methodology.md` and `SKILL.md`.
4. Keep gaps explicit. Do not import blog posts, talks, or generic SEO frameworks unless a tweet itself states them.

## License

MIT for this distillation. Underlying SEO views belong to [@loki_yan_seo](https://x.com/loki_yan_seo). Do not impersonate the original author.
