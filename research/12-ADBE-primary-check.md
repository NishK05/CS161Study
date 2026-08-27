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
