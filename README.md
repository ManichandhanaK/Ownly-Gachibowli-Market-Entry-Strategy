# Ownly × Gachibowli — Market Entry Strategy

**Should Rapido's zero-commission food delivery playbook, built in Bengaluru, transfer to Gachibowli, Hyderabad — and if so, which parts?**

A self-directed strategy case study combining primary survey research, competitive benchmarking, and a price/positioning audit to produce a **Keep / Adapt / Deprioritise** launch recommendation.

[**→ Read the full interactive report**](docs/index.html) · [Raw survey data](data/survey_responses_clean.csv)

---

## 1. Business context

Rapido is turning its ride-hailing user base — roughly 2x the size of India's online food-ordering base — into repeat food-ordering customers via **Ownly**, using its existing bike fleet and a zero-commission model instead of a paid-ad growth engine. Ownly scaled to ~20,000 restaurant partners in Bengaluru before folding into the main Rapido app. The question: does that Bengaluru playbook hold in a different city, competitive set, and awareness stage?

## 2. Method

| Input | What it produced |
|---|---|
| **Primary survey** — 136 respondents (Bengaluru + Hyderabad/Gachibowli, mixed frequency/segment) | Ordering behaviour, fee sensitivity, brand awareness, blind price/positioning tests |
| **Price & catalogue audit** | Delivery ETA gap, catalogue overlap %, fee-load comparison across apps |
| **Competitive benchmark** | Ownly vs. Toing (direct national competitor) vs. incumbents (Swiggy/Zomato) |
| **Qualitative interviews** | Switching-cost drivers, group-order dynamics, trust/brand-transfer effects |

Survey design included **blind head-to-head tests** (unnamed "Service P" vs. "Service Q") to isolate what actually drives preference from what respondents *say* drives preference — e.g. the winning checkout format wasn't the one people predicted they'd want.

## 3. Key findings

- **The local gap is density, not breadth.** Catalogue overlap with incumbents is already high (88.9%) — the real problem is a +17–24 min ETA gap, pointing to a rider-density issue rather than a restaurant-coverage issue.
- **Brand trust transfers, but the association doesn't.** Once told Ownly is from Rapido, trust increases — but the existing association is bikes/mobility, not food. It needs to be built, not assumed.
- **A clean total beats a transparent breakdown.** "Same food, smaller final bill" beat a full fee breakdown (GST/delivery/platform/packaging) head-to-head — full transparency *increased* checkout friction rather than building trust.
- **A live national competitor already occupies the same segment.** Toing targets the same fee-fatigued, student-heavy segment and is already live in Hyderabad — zero-commission is becoming a category norm, not a differentiator on its own.
- **Switching cost is concrete, not abstract.** Saved addresses, payment details, and "my usual restaurants" were named directly as reasons not to switch — a discount alone doesn't clear that bar.

## 4. Recommendation framework

| Keep | Adapt | Deprioritise |
|---|---|---|
| Zero-commission / fee-honesty claim | Checkout: single total, not itemised | Restaurant-count as headline growth metric |
| Bike-taxi fleet reuse + in-app distribution | Coverage strategy: real regulars over raw count | Discount-led messaging |
| Organic-only, in-app marketing | Invest in rider density before breadth | GMV/order volume before margin data exists |

## 5. What this demonstrates

- Designing primary research that separates stated preference from revealed preference (blind A/B framing)
- Structuring an ambiguous "should we launch, and how" question into a testable, MECE recommendation
- Reading conflicting signals (e.g. transparency helps trust but hurts conversion) without flattening the nuance
- Communicating findings as a decision-ready framework rather than a data dump

## Repo structure

```
├── README.md                          — this file
├── docs/
│   └── index.html                     — full interactive report (open directly, or serve via GitHub Pages)
└── data/
    └── survey_responses_clean.csv     — 136 survey responses, de-duplicated, PII removed
```

## Viewing the report

Open `docs/index.html` directly in a browser, or enable **GitHub Pages** (Settings → Pages → Source: `main` branch, `/docs` folder) to host it at a shareable link.

## Data note

The published dataset excludes the optional "can we contact you" field, which respondents used to volunteer phone numbers. No other identifying information was collected.

---
*Independent research project — not affiliated with or endorsed by Rapido / Ownly.*
