# Available .OBSERVER One-Word Domains (12,553)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C553%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .observer one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,553 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,553 domains · **Median ask:** $95.38 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-26  
**Canonical page:** `https://unique.domains/domains/tld/observer`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/observer?utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./observer.csv">CSV</a> / <a href="./observer.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .OBSERVER search](https://unique.domains/domains/tld/observer?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .OBSERVER search](https://unique.domains/domains/tld/observer?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .OBSERVER one-word domain catalog.

### Files

- `observer.csv` — public CSV extract (1,000 rows)
- `observer.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/observer-oneword-domains/main/observer.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain                | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| --------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Acup.observer         | available | $16.98    | —             | 80             | 5      | 5      | namecheap |
| Trex.observer         | available | $16.98    | —             | 80             | 24     | 5      | namecheap |
| useit.observer        | available | $15.99    | —             | 94             | 7      | 6      | name.com  |
| dogsit.observer       | available | $15.99    | —             | 96             | 2      | 6      | name.com  |
| playin.observer       | available | $15.99    | —             | 80             | 10     | 7      | name.com  |
| dogsick.observer      | available | $15.99    | —             | 90             | 1      | 7      | name.com  |
| leaveon.observer      | available | $15.99    | —             | 80             | 1      | 8      | name.com  |
| lightup.observer      | available | $15.99    | —             | 82             | 15     | 8      | name.com  |
| surebet.observer      | available | $15.99    | —             | 82             | 7      | 8      | name.com  |
| prompts.observer      | available | $10.99    | $10.99        | 54             | 39     | 7      | namesilo  |
| insight.observer      | premium   | $1,000    | —             | 76             | 69     | 8      | name.com  |
| commonground.observer | available | $15.99    | —             | 74             | 28     | 13     | name.com  |
| farmers.observer      | premium   | $25       | —             | 54             | 59     | 7      | name.com  |
| agents.observer       | premium   | $1,000    | —             | 56             | 50     | 6      | name.com  |
| deeplearning.observer | available | $15.99    | —             | 74             | 23     | 13     | name.com  |
| cars.observer         | premium   | $1,000    | —             | 66             | 47     | 4      | name.com  |
| stadia.observer       | available | $15.99    | —             | 66             | 22     | 6      | name.com  |
| events.observer       | premium   | $1,250    | —             | 68             | 37     | 6      | name.com  |
| unicorns.observer     | available | $15.99    | —             | 73             | 21     | 8      | name.com  |
| homes.observer        | premium   | $11,250   | —             | 86             | 34     | 5      | name.com  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,553 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/observer?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/observer?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=related_pricing)

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

These domains are one-word names on the .observer extension. The set includes dictionary-style words, action phrases compressed into one token, and short brandable forms such as Acup.observer, useit.observer, edamame.observer, and gearup.observer. With a median ask of 95.38, the selection sits in a low upfront price range, but the extension itself is specialized. When comparing these domains, focus on whether the word still reads cleanly with .observer, whether the combined meaning feels credible for a brand or publication, and whether renewal cost and long-term resale demand fit your risk tolerance.

- Check if the keyword pairs naturally with .observer
- Favor clear words over awkward or forced combinations
- Use ask price with renewal cost to judge total hold risk
- Treat niche-TLD resale demand as more selective

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .OBSERVER One-Word Domains*. Version 2026-05-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .OBSERVER page](https://unique.domains/domains/tld/observer?utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_observer_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
