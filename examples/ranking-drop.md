# Example: ranking drop

> EXAMPLE. Invented site. Not a Loki case. Not real GSC.

**Task type:** decline (Shopify theme change last Tuesday)

**Do first / stop first**
1. Open `robots.txt` and Crawl status before anything else. (id=2091795112745689273)
2. Frog Raw vs rendered on the new theme. `Raw = Rendered`, `Desktop = Mobile`. (id=2091508567119642847)
3. Chrome → disable JavaScript. If the first screen or product grid vanishes, the new theme hid core content under JS. (id=2092105285955473656)
4. Soft 404: collection filters that 200 on empty states. (id=2091349098553295075)
5. Stop the “buy 200 links to recover” plan. (id=2090685656079241520)

**Red flags:** JS-only product grid; empty mobile fold; someone treating DA as the cause.

**One-query-per-page**

| URL | Query | Notes |
|---|---|---|
| `/` | `EXAMPLE brand + running shoes` | Title still the old default theme string |
| `/products/pegasus` | cannot say | PDP title is the product handle |

**Evidence grade:** in-corpus rules for robots / render / JS-off / no-chase-links. Traffic numbers above are `EXAMPLE`.

**How to test:** GSC inspect URL + coverage; Frog render diff; JS-off screenshot vs apple.com/iphone; 7-day crawl-stat, not DA.

**Decision stays with you.** Theme rollback vs CSS-only effects is your call.
