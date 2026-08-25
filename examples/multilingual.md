# Example: multilingual / IP redirect

> EXAMPLE. Invented export site. Not a Loki case.

**Task type:** multilingual (US + JP), asked “should we IP-redirect”

**Do first / stop first**
1. Do **not** auto-switch language or auto-redirect by IP. Copy Apple’s top banner. (id=2091014853863637176)
2. `Raw = Rendered`, `Desktop = Mobile`; no separate `m.` JP site. (id=2091008050262110227)
3. Japanese: submit Bing Webmaster (Yahoo JP uses Google; other Yahoos use Bing).
4. JS-off pass on both language templates. (id=2092105285955473656)
5. hreflang fine-tuning: `no procedure in corpus`. Point at official docs.

**Red flags:** IP auto-jump; H5 template as the JP stack; empty mobile fold on the JP homepage.

**One-query-per-page**

| URL | Query | Notes |
|---|---|---|
| `/` | `EXAMPLE {modifier} + Entity` in EN | Homepage should cover 3–5 years |
| `/jp/` | cannot say | Title still EN default |

**Evidence grade:** in-corpus for no-IP-redirect + Bing-for-JP. hreflang recipe is missing.

**How to test:** from a JP IP, confirm you still *choose* language (banner), you are not 301’d to EN. Bing WMT submission receipt.

**Decision stays with you.** Legal/compliance exceptions he allowed are yours to judge.
