# Available .KITCHEN One-Word Domains (12,125)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C125%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .kitchen one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,125 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,125 domains · **Median ask:** $22.98 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/kitchen`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/kitchen?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./kitchen.csv">CSV</a> / <a href="./kitchen.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .KITCHEN search](https://unique.domains/domains/tld/kitchen?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .KITCHEN search](https://unique.domains/domains/tld/kitchen?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .KITCHEN one-word domain catalog.

### Files

- `kitchen.csv` — public CSV extract (1,000 rows)
- `kitchen.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/kitchen-oneword-domains/main/kitchen.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status    | ask_price | renewal_price | attractiveness | demand | length | registrar        |
| -------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------- |
| tips.kitchen         | available | $14.99    | —             | 80             | 26     | 4      | name.com         |
| koala.kitchen        | premium   | —         | —             | 80             | 31     | 5      | —                |
| finals.kitchen       | available | $14.99    | —             | 80             | 7      | 6      | name.com         |
| ladies.kitchen       | available | $14.99    | —             | 80             | 17     | 6      | name.com         |
| geton.kitchen        | available | $14.99    | —             | 82             | 10     | 6      | name.com         |
| getup.kitchen        | available | $14.99    | —             | 82             | 14     | 6      | name.com         |
| matcha.kitchen       | available | $14.99    | —             | 86             | 39     | 6      | name.com         |
| Apples.kitchen       | available | $83.98    | —             | 90             | 16     | 6      | namecheap        |
| useit.kitchen        | available | $14.99    | —             | 94             | 7      | 6      | name.com         |
| makeit.kitchen       | available | $14.99    | —             | 82             | 22     | 7      | name.com         |
| stirup.kitchen       | available | $14.99    | —             | 82             | 3      | 7      | name.com         |
| coins.kitchen        | available | $14.99    | —             | 56             | 41     | 5      | name.com         |
| code.kitchen         | resell    | —         | —             | 72             | 62     | 4      | Porkbun LLC      |
| Tools.kitchen        | premium   | $560      | $560          | 56             | 40     | 5      | namecheap        |
| shortcuts.kitchen    | available | $14.99    | —             | 48             | 41     | 10     | name.com         |
| dads.kitchen         | resell    | —         | —             | 60             | 17     | 4      | NameCheap, Inc.  |
| photos.kitchen       | premium   | $500      | —             | 54             | 28     | 6      | name.com         |
| VeniceBeach.kitchen  | resell    | —         | —             | 56             | 7      | 12     | GoDaddy.com, LLC |
| justin.kitchen       | available | $14.99    | —             | 58             | 38     | 7      | name.com         |
| neuroscience.kitchen | available | $14.99    | —             | 80             | 37     | 12     | name.com         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,125 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/kitchen?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/kitchen?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

These domains are all one-word names on the .kitchen extension, which makes the selection unusually specific. The set includes direct dictionary-style words and broad consumer terms such as tips.kitchen, girls.kitchen, ladies.kitchen, jewels.kitchen, and WiFi.kitchen. For founders, the main question is whether the word is memorable, easy to say, and naturally fits a food, cooking, appliance, recipe, or kitchen-adjacent brand. For investors, the key test is whether the word has clear commercial meaning inside this extension and whether the ask leaves room versus likely resale demand. Median ask in this selection is $22.98, so pricing appears accessible, but fit and trademark risk still matter.

- Prefer words that match kitchen, food, cooking, or home use cases
- Check whether the word feels natural before .kitchen
- Use pricing discipline: median ask is $22.98
- Avoid terms with obvious trademark or brand conflict risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .KITCHEN One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .KITCHEN page](https://unique.domains/domains/tld/kitchen?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
