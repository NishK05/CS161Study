# Model Design Notes — what YOUR Excel model needs to do
⚠️ **Per the official rules, the team must build this model. This file is research support —
verified public inputs and a checklist of what the judging criteria demand. It is not a model.**
Sourced input data is in `pitch/data/`.

## The judging criteria are explicit — optimise directly for them
> *"criteria that evaluate **quality and viability of thesis, model and thes[i]s alignment, and
> logic of model assumptions**"*

**"Model and thesis alignment" is where most teams lose.** If the thesis is *"the ARR guide-down
is a deliberate, reversible growth investment, not demand destruction,"* then the model must have
**the ARR bridge as a visible, driver-level input** — not revenue growth as a single typed-in
percentage. A judge must be able to change one cell labelled *"deferred price increases reinstated
in FY27? Y/N"* and watch the valuation move. **That is what alignment means.**

## Drivers the model must expose (not hard-code)
1. **The ARR bridge** — the thesis lives here
   - FY25 exit ARR $25.20B; revalued base entering FY26 **$25.66B**
   - Semrush contribution **~$480M (~1.9pts)** — must be a separate, toggleable line
   - **Organic FY26 ARR growth ~8.3%** vs total guide **+10.2%**
   - A **switch** for whether the deferred price increases return in FY27
2. **Revenue build** from ARR + the two disclosed customer groups
   (Business Professionals & Consumers; Creative & Marketing Professionals)
3. **Margin bridge** — non-GAAP operating margin **46.2% (FY25) → 45.0% (FY26E) → 44.0% (Q3 guide)**.
   Model the freemium investment explicitly as the cause; do not plug it.
4. **SBC as a real cost.** FY25 **$1,942M = 8.17% of revenue**. Show GAAP and non-GAAP side by side
   and a **FCF-less-100%-of-SBC** line. Judges will ask; lead with it instead.
5. **Share count** — this is a major EPS driver and must be modelled, not assumed:
   - Actual: 437.6M → 428.9M → 424.1M → 410.8M → **402.5M**
   - Guide: **399M FY26, 395M Q3 FY26**
   - **$26.78B authorization remaining = 24.6% of market cap**; pace ~$2.3B/qtr
   - **~6.6 of FY26's 16.6pts of non-GAAP EPS growth is buyback** — separate operating from
     financial EPS growth in the output. Showing that split IS the intellectual honesty judges reward.
6. **The forward-book check as a live output**, since it is the thesis's proof and its kill switch:
   RPO growth, cRPO growth, and current deferred revenue growth vs revenue growth.
   Currently **RPO +13%, deferred revenue +15.0%, revenue +12.7%.**

## The valuation section
- **Lead with a reverse DCF, not a forward DCF.** The single most persuasive output is
  *"at $273 the market implies −6.3%/yr FCF for five years at a 9% WACC."* That reframes the
  debate from "is Adobe worth 12x?" to "do you really believe FCF declines for five years?"
- **Do NOT lead with a terminal-value DCF** — a 3-12 month horizon makes terminal value a
  mismatch, and it will be marked down.
- Show the multiple bridge: current 15.2x GAAP → target multiple, and current EPS → your EPS.
- Peer table (verified Aug 26-27, 2026): ADBE 10.6x fwd / CRM 14.2x / INTU 14.0x / WDAY 17.2x /
  NOW 27.8x. **A re-rate merely to CRM/INTU's ~14x on FY27 EPS of $27.49 = $385.**

## The predictive component the rules explicitly demand
> *"Support for the thesis should involve a **predictive component** in addition to historical analysis."*

**Adobe has already published Q3 FY26 guidance, and Q3 reports ~Sept 10 — before your Oct 2
deadline.** Make a specific, dated, falsifiable forecast against it and then show whether it
landed. Guidance is in `pitch/data/adbe_q3fy26_guidance.csv`:
revenue **$6.67–6.72B**, GAAP EPS **$4.40–4.45**, non-GAAP EPS **$6.05–6.10**, shares ~395M.
Forecast where in (or outside) that range you expect the print, **and forecast RPO and deferred
revenue growth**, which is where your thesis actually lives.

## Sanity checks before you submit
- Does the model reproduce FY25 actuals from its own drivers? If not, the drivers are wrong.
- Does changing ONE assumption that matches the thesis move the valuation materially?
  If not, thesis and model are not aligned.
- Is every assumption traceable to a cited source or a stated judgement? *"Logic of model
  assumptions"* is a third of the score.
- Is it **"clearly formatted and easily understandable"** (rule 7)? Inputs on one tab in a
  distinct colour, calculations separate, outputs separate. No hard-codes buried in formulas.
