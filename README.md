# Available .EVENTS One-Word Domains (29,702)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-29%2C702%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .events one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **29,702 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 29,702 domains · **Median ask:** $17.91 · **High-demand under $2,500:** 1

**Last updated:** 2026-09-25
**Canonical page:** `https://unique.domains/domains/tld/events`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/events?utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./events.csv">CSV</a> / <a href="./events.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .EVENTS search](https://unique.domains/domains/tld/events?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .EVENTS search](https://unique.domains/domains/tld/events?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .EVENTS one-word domain catalog.

### Files

- `events.csv`, public CSV extract (1,000 rows)
- `events.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/events-oneword-domains/main/events.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                  |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------- |
| ana.events      | available | $21.99    | —             | high           | low    | 3      | name.com                   |
| election.events | resell    | $21.99    | —             | high           | low    | 8      | GoDaddy.com, LLC           |
| bed.events      | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                   |
| bjp.events      | available | $21.99    | —             | high           | low    | 3      | name.com                   |
| anti.events     | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC           |
| cot.events      | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                   |
| icu.events      | available | $21.99    | —             | high           | low    | 3      | name.com                   |
| auto.events     | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC           |
| dog.events      | premium   | $500      | —             | high           | low    | 3      | name.com                   |
| lvi.events      | available | $10.48    | $57.98        | high           | low    | 3      | namecheap                  |
| beam.events     | resell    | —         | —             | high           | medium | 4      | Dynadot Inc                |
| don.events      | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                   |
| nyt.events      | available | $21.99    | —             | high           | low    | 3      | name.com                   |
| mode.events     | resell    | —         | —             | high           | low    | 4      | united-domains GmbH        |
| ear.events      | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                   |
| acts.events     | available | $21.99    | —             | high           | low    | 4      | name.com                   |
| xmas.events     | resell    | —         | —             | high           | low    | 4      | GoDaddy.com, LLC           |
| flu.events      | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                   |
| alky.events     | available | $10.48    | $57.98        | medium         | low    | 4      | namecheap                  |
| local.events    | resell    | —         | —             | high           | medium | 5      | Squarespace Domains II LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 29,702 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 1 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/events?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/events?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=related_pricing)

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

This list covers one-word .EVENTS domain names suited to conferences, festivals, launches, and campaign-specific sites. Each name pairs a short, memorable word with the .EVENTS extension, signaling purpose instantly to visitors. With a median asking price near $32 across 10,833 domains, the set stays budget-friendly for founders shortlisting a name and for buyers comparing pricing patterns across a single-TLD selection.

- One-word .EVENTS names for events, launches, and campaigns
- Median asking price near $32 across this selection
- 10,833 domains updated daily for fresh availability
- Short, memorable terms ready for brand ownership

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

> Unique Domains. *Available .EVENTS One-Word Domains*. Version 2026-09-25. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .EVENTS page](https://unique.domains/domains/tld/events?utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_events_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
