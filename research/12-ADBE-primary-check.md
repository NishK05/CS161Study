# ⭐ ADBE — Primary-Source Check via SEC XBRL API (my own read)
Pulled directly from `data.sec.gov/api/xbrl/companyconcept/CIK0000796343/...`
(no aggregator involved). Price reference $273.47, Aug 26 2026.

## THE HEADLINE FINDING: ADOBE'S REVENUE GROWTH IS **ACCELERATING**
| Quarter ending | Revenue | YoY |
|---|---|---|
| Feb 28, 2025 (Q1 FY25) | $5,714M | — |
| May 30, 2025 (Q2 FY25) | $5,873M | — |
| Aug 29, 2025 (Q3 FY25) | $5,988M | — |
| **Feb 27, 2026 (Q1 FY26)** | **$6,398M** | **+12.0%** |
| **May 29, 2026 (Q2 FY26)** | **$6,618M** | **+12.7%** |

Annual: FY2023 **$19,409M** → FY2024 **$21,505M (+10.8%)** → FY2025 **$23,769M (+10.5%)**

**=> Growth went from ~10.5% annual to +12.0% then +12.7%. It is SPEEDING UP.**
A company being structurally disrupted by generative AI does not accelerate from 10.5% to 12.7%.

## GAAP diluted EPS — also growing
| Period | GAAP diluted EPS | YoY |
|---|---|---|
| FY2023 | $11.82 | — |
| FY2024 | $12.36 | +4.6% |
| FY2025 | **$16.70** | +35.1% |
| Q1 FY25 | $4.14 | — |
| Q2 FY25 | $3.94 | — |
| Q3 FY25 | $4.18 | — |
| Q4 FY25 (derived) | $4.44 | — |
| **Q1 FY26** | **$4.60** | **+11.1%** |
| **Q2 FY26** | **$4.25** | **+7.9%** |
| **TTM (Q3'25→Q2'26)** | **$17.47** | — |

## The valuation, on GAAP — no non-GAAP games needed
- **$273.47 / $17.47 TTM GAAP diluted EPS = ~15.7x TRAILING GAAP EARNINGS.**
- For a software franchise with Adobe's margins, growing revenue 12.7% and GAAP EPS ~8-11%,
  that is genuinely, unusually cheap.
- Stock is **down ~24.7% over 52 weeks.**
- Consensus is **HOLD (n=40)** with an average price target of **~$270.61 — essentially AT,
  and marginally BELOW, the current price. ZERO embedded optimism.**
- Short interest only ~4.88% of float, and FALLING (20.3M → 19.4M).

## ⭐ WHY THIS IS THE STRONGEST SETUP IN THE UNIVERSE SO FAR
The market has priced Adobe for **terminal decline** — a Hold rating, a target at spot, a 24.7%
drawdown, and a mid-teens GAAP multiple — while the actual reported fundamentals show
**accelerating revenue and growing earnings.** That is a clean, falsifiable, quantified variant
perception: *consensus believes the AI disruption is showing up in the numbers; the numbers say
the opposite, and I can show it from the XBRL data.*

This satisfies the rules' demand for evidence that is *"technical rather than purely subjective"*
with *"a predictive component"* — the prediction is that Q3 FY26 revenue growth holds ≥11%.

## ⚠️ WHAT I HAVE NOT YET VERIFIED — do this before relying on it
1. **The 10.55x "forward P/E" from aggregators implies forward EPS of ~$25.9**, which is far
   above both TTM GAAP ($17.47) and any plausible near-term non-GAAP figure. **Either that
   forward number is non-GAAP on a later fiscal year, or the aggregator is wrong.**
   **Do NOT put 10.55x in the memo until it is reconciled to a stated consensus EPS figure.**
   Use the **15.7x trailing GAAP** number, which I computed myself and can defend.
2. Stock-based compensation as a % of revenue — Adobe's non-GAAP flatters heavily. **Compute
   FCF less SBC** and value on that; it is the honest basis and judges will ask.
3. Net new Digital Media ARR by quarter — the metric that would actually reveal seat loss.
   Not in XBRL; pull from the 10-Q/earnings releases.
4. Buyback pace and share-count reduction — at a mid-teens multiple with large FCF this is a
   material EPS driver. Get diluted share count by quarter.

## THE CATALYST — and it is beautifully timed
**Adobe Q3 FY2026 earnings, ~mid-September 2026** (fiscal quarter ended ~Aug 28, 2026).
That lands **just before the October 2 first-round deadline** and inside the finalist window.
If revenue growth holds at ~12%, the disruption narrative takes a direct, dated, public hit.
**Confirm the exact date from Adobe IR.**

## Method note
Used the SEC XBRL company-concept API with a compliant User-Agent rather than scraping filings.
Fast, exact, and free of aggregator error. Concepts used: `EarningsPerShareDiluted`, `Revenues`.

---
# ADDENDUM — gaps closed via SEC XBRL (share count, SBC, cash flow, buyback)

## ⭐ THE SHARE COUNT IS SHRINKING ~6% A YEAR
| Quarter ending | Diluted shares | YoY |
|---|---|---|
| Feb 28, 2025 | 437.6M | — |
| May 30, 2025 | 428.9M | — |
| Aug 29, 2025 | 424.1M | — |
| **Feb 27, 2026** | **410.8M** | **−6.1%** |
| **May 29, 2026** | **402.5M** | **−6.2%** |

**Adobe is retiring ~6% of its diluted share count per year, net of all SBC dilution.**
At a ~15.7x multiple that is roughly **6 points of mechanical EPS growth annually before any
operating growth at all.** Combine with ~12.7% revenue growth and even flat margins produce
solidly double-digit EPS growth. **A "Hold" rating with a target at spot is not consistent
with this arithmetic.**

## Stock-based compensation — real, but comfortably covered
| Quarter | SBC | as % of revenue |
|---|---|---|
| Q1 FY25 (Feb 2025) | $475M | 8.3% |
| **Q1 FY26 (Feb 2026)** | **$509M** | **8.0%** |
- Annualizing: SBC ≈ **$2.0B/yr**.
- Buyback: **$2,478M in Q1 FY26 alone** ($3,250M in Q1 FY25) — annualizing near **$10B/yr**.
- **=> Buybacks exceed SBC by roughly 5x.** The 6% net share reduction is genuine, not optical.
  This is the honest answer to the standard "but the non-GAAP hides SBC" objection: even paying
  for all of it in cash, Adobe still shrinks the count 6%/yr.

## Cash generation is accelerating too
| Quarter | Operating cash flow | YoY |
|---|---|---|
| Q1 FY25 | $2,482M | — |
| **Q1 FY26** | **$2,958M** | **+19.2%** |
(Q1 is seasonally Adobe's strongest billings quarter — do not naively annualize.)

## Where the thesis now stands
Every reported metric I can pull from primary data points the SAME direction:
- Revenue growth **accelerating** (+12.0% → +12.7%)
- Operating cash flow **+19.2%**
- Share count **−6.2%**
- GAAP EPS **growing** (TTM $17.47)
- Valuation **~15.7x trailing GAAP**
- Consensus **Hold, PT ~$270.61 vs $273.47 spot**, short interest 4.88% and falling
- Stock **−24.7% over 52 weeks**

**The market is pricing structural disruption. The financial statements show acceleration.**
That gap IS the pitch — and it is falsifiable on a dated catalyst (Q3 FY26, ~mid-Sept 2026).

## Still open
- Reconcile the aggregator's 10.55x "forward P/E" (implies ~$25.9 EPS) — **do not use until
  reconciled**; the defensible number is 15.7x trailing GAAP, which I computed myself.
- Net new Digital Media ARR by quarter — the metric that would actually show seat loss.
  Not in XBRL; pull from the earnings releases. **This is the single best place for a bear to
  attack, so own it first.**
- Confirm the exact Q3 FY26 earnings date from Adobe IR.

---
# ADDENDUM 2 — the Q2 FY26 earnings release itself (SEC 8-K Ex-99.1, June 11, 2026)
Source: https://www.sec.gov/Archives/edgar/data/796343/000079634326000109/adbeex991q226.htm

## ✅ THE FORWARD MULTIPLE IS RECONCILED — AND IT IS REAL
| | Q2 FY26 actual |
|---|---|
| Revenue | **$6.62B, +13% YoY (+11% cc)** — a record |
| **Diluted EPS GAAP** | **$4.25** |
| **Diluted EPS NON-GAAP** | **$5.96** |
| GAAP operating income | $2.24B |
| Non-GAAP operating income | $2.95B |
| GAAP net income | $1.71B |
| Non-GAAP net income | $2.40B |
| Operating cash flow | $2.17B |
| **Total ARR exiting quarter** | **$27.10B** (incl. ~$480M from Semrush) |
| RPO | **$22.27B**, cRPO 67% |
| **Shares repurchased in the quarter** | **~8.5 million** |
- GAAP EPS includes a **$0.17/share non-cash goodwill impairment** (Publishing & Advertising unit).
- Subscription revenue $6.39B, **+14%** (+12% cc).
- **Business Professionals & Consumers $1.85B, +16%**; Creative & Marketing Professionals $4.54B, +13%.

## ⭐ MANAGEMENT RAISED FY26 GUIDANCE — headline of the release:
> *"Adobe Raises FY26 Total Revenue and Non-GAAP EPS Targets"*
> *"**AI-first ARR triples year over year and exceeds $500 million**"*

### FY2026 targets (raised)
| | |
|---|---|
| Total revenue | **$26.50B – $26.60B** (vs FY25 $23.769B = **+11.5% to +11.9%**) |
| **GAAP EPS** | **$17.90 – $18.00** |
| **Non-GAAP EPS** | **$24.35 – $24.45** |
| Non-GAAP operating margin | **~45.0%** |
| Diluted share count | ~399M |
| Total ARR growth | 10.2% YoY |

### Q3 FY2026 targets
Revenue **$6.67B – $6.72B** · GAAP EPS **$4.40 – $4.45** · **Non-GAAP EPS $6.05 – $6.10** ·
non-GAAP op margin ~44.0% · diluted shares ~395M

## ⇒ THE VALUATION, ON MANAGEMENT'S OWN CURRENT-YEAR GUIDANCE, AT $273.47
| Basis | EPS | Multiple |
|---|---|---|
| **FY26 non-GAAP guidance midpoint** | **$24.40** | **11.2x** |
| **FY26 GAAP guidance midpoint** | **$17.95** | **15.2x** |
| TTM GAAP actual | $17.47 | 15.7x |
The aggregator's "10.55x forward" is FY27 consensus non-GAAP (~$25.9). **It reconciles.**
**Adobe trades at ~11x THIS YEAR's guided non-GAAP EPS and ~15x guided GAAP EPS, while
raising guidance and growing revenue ~12%.** Use the GAAP number in the memo — it is
unimpeachable — and show the non-GAAP as a cross-check.

## ⚠️⚠️ TWO THINGS THAT MUST BE OWNED IN THE MEMO — do not hide these
### 1. THE CFO DEPARTED
> *"Dan Durn, executive vice president and CFO of Adobe, **is departing the company on
> June 15, 2026** to pursue a new professional opportunity. **Steve Day**… will serve as
> **interim** Chief Financial Officer."*
A CFO exit announced *in the earnings release itself*, at a company already under an
AI-disruption narrative, is exactly what a bear points to and is likely part of why the stock
de-rated. **Raise it first and address it.** Mitigants: Day has 20 years at Adobe; guidance was
RAISED in the same release, not withdrawn. Watch for a permanent CFO appointment as a catalyst.

### 2. PART OF THE "ACCELERATION" IS INORGANIC — Semrush
Adobe acquired **Semrush**. Q2 subscription revenue *"includ[ed] approximately $40 million from
Semrush"* on a $6.618B quarter ≈ **0.6pp of the 13% growth**. Total ARR includes ~$480M of Semrush.
**So report organic Q2 growth as ~12.4%, not 13%.** Still an acceleration versus FY25's +10.5%,
but state it honestly — an inflated organic number is the fastest way to lose credibility in Q&A.
**Confirm whether Q1 FY26 (+12.0%) contained any Semrush contribution before claiming a clean
two-quarter organic acceleration.**

## Why this is now the strongest pitch in the universe
The bear case is *"generative AI destroys Adobe's franchise."* The company's own reported and
guided numbers say: revenue accelerating, guidance RAISED, **AI-first ARR TRIPLING to >$500M**
(i.e. Adobe is *monetizing* AI, not being eaten by it), ~6%/yr share count reduction, ~45%
non-GAAP operating margins, $22.27B RPO — at **~15x GAAP / ~11x non-GAAP** with a **Hold**
consensus whose target sits **below** the share price.

**Catalyst: Q3 FY26 earnings, ~mid-September 2026** (Q2 was reported June 11; Q3 quarter ended
~Aug 28). Guidance is already public: revenue $6.67–6.72B and non-GAAP EPS $6.05–6.10.
**That gives the memo a genuine, dated, falsifiable PREDICTIVE component — exactly what the
official rules ask for.** Confirm the date with Adobe IR.
