# Available .VANA One-Word Domains (36,531)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-36%2C531%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .vana one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **36,531 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 36,531 domains · **Median ask:** $2,259.86 · **High-demand under $2,500:** 218

**Last updated:** 2026-10-03
**Canonical page:** `https://unique.domains/domains/tld/vana`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/vana?utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./vana.csv">CSV</a> / <a href="./vana.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .VANA search](https://unique.domains/domains/tld/vana?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .VANA search](https://unique.domains/domains/tld/vana?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .VANA one-word domain catalog.

### Files

- `vana.csv`, public CSV extract (1,000 rows)
- `vana.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/vana-oneword-domains/main/vana.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| citibank.vana  | available | $2,140.22 | $2,140.22     | high           | medium | 8      | dynadot   |
| believe.vana   | available | $2,298    | $2,498        | high           | low    | 7      | namecheap |
| personal.vana  | available | $2,298    | $2,498        | high           | low    | 8      | namecheap |
| hashtag.vana   | available | $2,070.20 | $2,070.20     | high           | low    | 7      | spaceship |
| organize.vana  | available | $2,298    | $2,498        | high           | low    | 8      | namecheap |
| spoon.vana     | available | $2,070.20 | $2,070.20     | high           | low    | 5      | spaceship |
| clear.vana     | available | $2,298    | $2,498        | high           | medium | 5      | namecheap |
| remember.vana  | available | $2,070.20 | $2,070.20     | high           | low    | 8      | spaceship |
| refresh.vana   | available | $2,298    | $2,498        | high           | low    | 7      | namecheap |
| loved.vana     | available | $2,298    | $2,498        | high           | low    | 5      | namecheap |
| research.vana  | available | $2,060.25 | $2,060.25     | high           | medium | 8      | porkbun   |
| clay.vana      | available | $2,070.20 | $2,070.20     | high           | low    | 4      | spaceship |
| adequate.vana  | available | $2,298    | $2,498        | high           | low    | 8      | namecheap |
| ecosystem.vana | available | $2,060.25 | $2,060.25     | high           | low    | 9      | porkbun   |
| passion.vana   | available | $2,070.20 | $2,070.20     | high           | low    | 7      | spaceship |
| cook.vana      | available | $3,999.99 | $3,999.99     | high           | low    | 4      | name.com  |
| forces.vana    | available | $2,298    | $2,498        | high           | low    | 6      | namecheap |
| angular.vana   | available | $2,298    | $2,498        | high           | low    | 7      | namecheap |
| detroit.vana   | available | $2,070.20 | $2,070.20     | high           | low    | 7      | spaceship |
| seek.vana      | available | $2,070.20 | $2,070.20     | high           | low    | 4      | spaceship |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 36,531 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 218 high-demand names under $2,500         |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/vana?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/vana?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This is a curated list of one-word .vana domain names — short, everyday words like half, feel, sorry, and great, each paired with the .vana extension. With 12,925 domains in this set and a median ask near $2,497, the selection spans common vocabulary suited for brandable, memorable naming. Compare word length, everyday recognition, and asking price to identify domains that fit either a straightforward acquisition or a founder's brand shortlist.

- 12,925 one-word .vana domain names in this selection
- Median ask around $2,497 per domain
- Everyday words like half, feel, sorry, and great
- Short, brandable names across common vocabulary

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .VANA One-Word Domains*. Version 2026-10-03. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .VANA page](https://unique.domains/domains/tld/vana?utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_vana_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
