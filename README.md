# Citadel Intercollegiate Stock Pitch Competition 2026 — Research Dossier

Research workspace for a 3-person undergraduate team.

## ⚠️ READ FIRST — TWO RULES THAT GOVERN EVERYTHING

**1. The universe is FIXED.** You must pitch a long or short on ONE of:
**ABNB, ADBE, CPRT, GEV, NCLH, NKE, SBUX, SPOT** — 3-12 month horizon.
*"Submissions analyzing any other security will be disqualified."*

**2. Generative AI may be used for DISCLOSED INITIAL RESEARCH ONLY.**
> *"While Teams may use artificial intelligence tools for initial research in the preparation of
> Submission (provided such use is clearly disclosed to Sponsor), Submissions must not be
> generated in whole or in part by any generative artificial intelligence tool."*

**=> This repo is a RESEARCH DOSSIER, not a draft submission. The team writes the memo and
builds the Excel model. The team must disclose the AI-assisted research to Citadel.**

## Deadlines (all 11:59:59 pm ET)
| Stage | Date |
|---|---|
| Interest form | **Sept 18, 2026** |
| **First Round submission** | **Oct 2, 2026** |
| Finalists notified | ~Oct 12, 2026 |
| Finalist Round submission | Oct 21, 2026 |
| Finals in NYC (presentations Oct 23) | Oct 22–24, 2026 |

Deliverable: **2-page max PDF memo (including appendix) + an Excel valuation model + a resume
for every team member** (missing resumes can disqualify the team).

Judging criteria, verbatim: *"quality and viability of thesis, **model and thes[i]s alignment**,
and logic of model assumptions."*

## 🥇 THE RECOMMENDATION: **LONG ADBE** → see `pitch/01-RANKING-AND-RECOMMENDATION.md`

## Index
### Start here
- `research/00-COMPETITION-RULES-CONFIRMED.md` — universe + rules, from Citadel's live page
- `research/00-OFFICIAL-RULES-EXTRACT.md` — the official rules PDF, incl. the AI restriction
- `pitch/01-RANKING-AND-RECOMMENDATION.md` — **all 8 names ranked; the recommendation**
- `pitch/00-memo-structure.md` — how to structure a 2-page Citadel memo
- `pitch/02-model-design-notes.md` — what your Excel model must expose
- `pitch/data/` — SEC-verified Adobe inputs (CSV)

### The eight names
| File | Name | Call |
|---|---|---|
| `research/15-ADBE-DEEP-DIVE.md` (+ `12`) | **ADBE** | **LONG — the pick** |
| `research/18-CPRT-ABNB-deep-dive.md` | ABNB / CPRT | LONG half-size / PASS |
| `research/14-SBUX-deep-dive.md` (+ `07`) | SBUX | SHORT |
| `research/11-GEV-deep-dive.md` (+ `06`) | GEV | SHORT (structurally hard) |
| `research/17-NKE-deep-dive.md` (+ `08`) | NKE | PASS |
| `research/13-SPOT-deep-dive.md` | SPOT | PASS |
| `research/16-NCLH-deep-dive.md` (+ `10`) | NCLH | PASS |

### Thematic background (the GLP-1 work that started this)
- `research/09-penetration-model-CORRECTIONS.md` — **read before citing any GLP-1 number**
- `research/05-glp1-consumption-math.md` — the defensible consumption framework
- `research/02-consumer-retail-apparel.md`, `04-thematic-context-for-universe.md`
- `research/01-glp1-penetration-hard-data.md` — ⚠️ partially superseded by `09`
- `research/03-primary-source-checks.md` — EDGAR screens

## Corrections log — claims tested and withdrawn
Kept deliberately, because the discipline matters more than a clean story:
1. **"Victoria's Secret was hurt by GLP-1s"** — false. CEO: *"minimal impact… 3% and below."*
   Stock +308% over 52 weeks.
2. **"US obesity fell 39.9% → 36.4%"** — not defensible. Gallup is self-reported; **NHANES shows
   no significant decline** and its latest window predates mass adoption.
3. **"11% of US adults are on a GLP-1"** — IQVIA dispensing implies **~6.1%**.
4. **"GLP-1 users exercise more, so buy Nike"** — **falsified by wearable data**: steps −11.1%,
   moderate-to-vigorous activity −21.4% (ENDO 2026, n=753).
5. **"GLP-1 cuts cruise food cost / onboard alcohol spend"** — refuted both ways. Food is 3.21%
   of NCLH revenue and *grew*; onboard revenue *grew 12.6%*; Free at Sea bundles alcohol into
   the fare, so drinking less cuts COGS, not revenue.
6. **"GEV's forward P/E above trailing means consensus expects decline"** — a data artifact from
   a one-off Prolec acquisition gain. Real clean trailing P/E is ~112x.
7. **"NCLH forward bookings are healthy"** — my error: I compared to year-end, not year-over-year.
   Correctly measured, deferred revenue **−4.8% on +8.9% capacity**.
8. **"Starbucks is a GLP-1 demand short"** — inverts. Food mix is *rising* and food attach hit a
   record; GLP-1 shows up as margin mix, not lost demand.
