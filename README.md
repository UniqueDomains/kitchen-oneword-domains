# Available .KITCHEN One-Word Domains (9,175)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C175%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C175%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .kitchen one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 9,175 rows · **Live catalog:** 9,175 domains

**Last updated:** 2026-04-13  
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

- `kitchen.csv` — public CSV extract (9,175 rows)
- `kitchen.json` — public JSON extract (9,175 rows)
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

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| silver.kitchen  | available | $83.98    | —             | 56             | 99     | 6      | namecheap                                                 |
| gas.kitchen     | resell    | $83.98    | —             | 72             | 31     | 3      | Dynadot Inc                                               |
| zero.kitchen    | premium   | $500      | $500          | 112            | 53     | 4      | name.com                                                  |
| car.kitchen     | available | $83.98    | —             | 94             | 46     | 3      | namecheap                                                 |
| test.kitchen    | resell    | —         | —             | 72             | 89     | 4      | Blue Razor Domains, LLC                                   |
| game.kitchen    | premium   | $500      | $500          | 120            | 50     | 4      | name.com                                                  |
| clear.kitchen   | available | $14.99    | $84.99        | 90             | 46     | 5      | name.com                                                  |
| easy.kitchen    | resell    | —         | —             | 128            | 68     | 4      | Global Domains International, Inc. DBA DomainCostClub.com |
| life.kitchen    | premium   | $520      | $520          | 84             | 50     | 4      | namecheap                                                 |
| every.kitchen   | available | $14.99    | —             | 82             | 46     | 5      | name.com                                                  |
| prompt.kitchen  | resell    | —         | —             | 114            | 68     | 6      | NameCheap, Inc.                                           |
| big.kitchen     | premium   | $500      | $500          | 88             | 47     | 3      | name.com                                                  |
| creator.kitchen | available | $14.99    | $84.99        | 70             | 45     | 7      | name.com                                                  |
| now.kitchen     | resell    | —         | —             | 78             | 66     | 3      | GoDaddy.com, LLC                                          |
| trade.kitchen   | premium   | $520      | $520          | 116            | 46     | 5      | namecheap                                                 |
| pop.kitchen     | available | $14.99    | $84.99        | 82             | 44     | 3      | name.com                                                  |
| fun.kitchen     | resell    | —         | —             | 122            | 62     | 3      | Porkbun LLC                                               |
| auto.kitchen    | premium   | $520      | $520          | 68             | 45     | 4      | namecheap                                                 |
| deep.kitchen    | available | $14.99    | $84.99        | 72             | 43     | 4      | name.com                                                  |
| space.kitchen   | resell    | —         | —             | 80             | 61     | 5      | GoDaddy.com, LLC                                          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 9,175-row public sample | 9,175 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .KITCHEN One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .KITCHEN page](https://unique.domains/domains/tld/kitchen?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_kitchen_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
