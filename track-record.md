---
layout: default
title: "Track Record"
---

*Last updated: August 17, 2026*

*Rating policy: five_level_v1*

> **Scale transition note.** The active taxonomy is the five-bucket `five_level_v1` scale (BUY / ACCUMULATE / HOLD / REDUCE / AVOID). Legacy three-bucket distribution targets, the 70% HOLD floor, and legacy rating-volume quotas were **retired by contract change** in the prior cycle — not reversed on data — and remain retired. No rating distribution is forced. Each bucket is evaluated on its own realized alpha and calibration as post-transition sample accumulates. Empirical observations about selection alpha, score behavior, sector effects, and missed downside carry forward where still supported.

## Track Record Summary

**Overall dataset:** 8,117 reports with follow-up return data (+621 vs last cycle).

| Recommendation | Count | Avg Return | Hit Rate | ALPHA vs SPY | Beat-SPY Rate |
|---|---|---|---|---|---|
| BUY | 1,089 | +0.38% | 48.3% | **−0.75pp** | 39.0% |
| ACCUMULATE | 1,526 | +0.60% | 52.6% | **+0.15pp** | 48.4% |
| HOLD | 3,906 | +0.71% | 53.6% | **+0.53pp** | 51.7% |
| REDUCE | 643 | −0.45% | 49.6% | **−0.26pp** | 49.8% |
| AVOID | 952 | +0.08% | 48.1% | **−0.27pp** | 46.3% |

**Read this honestly. On alpha the BUY book still has no selection edge.** BUY's raw +0.38% is market beta — beta-stripped, BUYs *underperform SPY by 0.75pp* and beat the index only 39.0% of the time. The system is not picking winners; it is riding a rising tape with a slightly-worse-than-market basket. **HOLD remains the only clearly positive-alpha bucket (+0.53pp, 51.7% beat)** — the passive default still out-selects the active BUY book. **ACCUMULATE is barely positive (+0.15pp, 48.4% beat)** — a hair above neutral, no demonstrated edge. The two active bullish buckets together add ~zero-to-negative alpha; the do-nothing bucket adds the most.

**The bearish buckets do NOT sort strongly.** REDUCE (−0.26pp alpha) has the correct sign but weak separation; AVOID at −0.27pp is only marginally negative on alpha. Neither cleanly isolates losers — but see the survivorship caveat, which materially affects AVOID.

BUY alpha held at −0.75pp on a +621 sample. Sign and magnitude unchanged; this is a stable non-edge, NOT a validated skill. Do not credit it.

**Score Predictiveness — still anti-predictive on alpha.** Top-third raw +0.68% vs bottom-third +0.29% (raw spread +0.38pp). But the **alpha spread is −1.39pp** (top +0.5pp vs bottom +1.89pp, n=6,164). The lowest-scored names *beat* SPY while the highest-scored barely track it. The positive raw spread is pure market beta; beta-stripped, the score sorts the *wrong direction*. This inversion has now persisted across nine consecutive cycles. It is the single most durable finding in the dataset. The stable −1.39pp is not a trend toward predictiveness.

**Restraint vs. selection.** BUY volume is 1,089 of 8,117 (13.4%). Selection quality has NOT improved on any durable basis — alpha still negative, alpha spread still inverted. This is a beta/selection problem, not a volume problem. Cutting volume would raise aggregates without proving the signal got better; only rising alpha would show that.

**AVOID Recall — the unsolved weakness.** Of 432 names that fell >15%, only **92 were flagged AVOID (strict recall 21.3%)**; adding REDUCE lifts defensive recall to **34.3%** (148/432). 284 were MISSED (42 BUY, 61 ACCUMULATE, 181 HOLD). Of 212 names that fell >20%, **60 AVOID (recall 28.3%)**, **92 REDUCE+AVOID (43.4%)**, 120 missed. The system still parks the majority of blow-ups in bullish/neutral buckets — 181 of 284 missed >−15% names sit in HOLD. AVOID *precision* says nothing about this recall gap.

**Survivorship Bias.** Of 6,192 snapshots old enough for follow-up, 27 (0.4%) lack one. The gap is non-uniform: **AVOID 1.4% (12/875) vs BUY 0.2% (2/1,036)** — a 7× ratio; REDUCE has 0% gap. The worst AVOID outcomes (delistings/takeouts) are disproportionately absent, so the measured AVOID alpha (−0.27pp) **understates** true AVOID signal. Treat AVOID's near-neutral alpha as a floor on its true value, not an unbiased estimate. This does NOT rescue the recall problem, which measures failures to flag, not the quality of flags issued.

## Identified Biases

1. **Score is anti-predictive on alpha (CRITICAL).** Bottom-third beats SPY by 1.89pp; top-third only +0.5pp. High-conviction bullish calls still crater: DOCS (BUY 7.03 → −27.1%), SNEX (ACCUMULATE 6.5 → −39.9%), PLAB (ACCUMULATE 6.33 → −35.1%), REZI (6.12 → −28.6%), SAIL (6.1 → −25.8%). High scores are not protective.
2. **BUY and ACCUMULATE add no selection alpha (CRITICAL).** BUY −0.75pp; ACCUMULATE +0.15pp (flat). Both sit at-or-below the HOLD default (+0.53pp).
3. **Defensive recall ~21–34% (HIGH, unsolved).** The system misses most large declines, parking 181 of 284 missed >−15% names in HOLD. Worst calls confirm: HON (5.3 HOLD → −49.1%), ADMA (5.98 HOLD → −40.4%). REDUCE adds ~13pp of coverage but ~two-thirds of >−15% names still slip through.
4. **Sector alpha (judge on alpha, not raw):**
   - Consumer Discretionary BUY: −2.03% raw, **−3.05pp alpha** (32) — worst large sector.
   - Energy BUY: −1.5% raw, **−2.81pp alpha** (167, largest cumulative alpha sink). Breadth confirmed: Oil & Gas E&P −3.84pp (84), Equip & Services −3.66pp (13), Midstream −2.17pp (13), Storage & Transport −1.66pp (20). Structural. Refining & Marketing (−0.02pp, 19) is the lone near-neutral pocket.
   - Materials **−2.82pp** (16). Industrials **−1.47pp** (117). Financials **−1.26pp** (317, 29% of BUYs) — worst inside: Investment Banking & Brokerage (−3.75pp, 18), Regional Banks (−2.75pp, 53); Consumer Finance (+0.84pp, 11) lone near-positive.
   - Health Care BUY: +1.23% raw but **+0.27pp alpha** (123) — marginal at sector level. Heterogeneous: Health Care Services +2.94pp (11), Health Care Facilities +2.13pp (10), Biotechnology +1.86pp (35), Pharmaceuticals +0.41pp (26) positive; Health Care Equipment (−1.07pp, 23) drags.
   - **Information Technology: +2.13pp alpha** (162) — the only sector with a real positive edge, but heterogeneous. Driven by Systems Software (+6.45pp, 21), Tech Hardware/Storage (+6.14pp, 13), Semiconductors (+3.5pp, 62), Payment Processing (+2.27pp, 26). Dragged by Application Software (−0.49pp, 33) and Semiconductor Materials & Equipment (−0.32pp, 16). Do NOT treat "IT" wholesale as the edge.

## Lessons for Future Analysis

1. **Stop crediting raw bullish return as skill.** Until BUY/ACCUMULATE alpha turns positive at adequate n across ≥2 cycles, treat both as beta-tracking. The fix is selection quality, not volume.
2. **Concentrate bullish calls in the positive-alpha industries, not heterogeneous sectors.** Target Systems Software (+6.45pp, n=21), Tech Hardware/Storage (+6.14pp, n=13), Semiconductors (+3.5pp, n=62), Payment Processing (+2.27pp, n=26); Biotechnology (+1.86pp, n=35) and Health Care Services (+2.94pp, n=11) are suggestive but thin. Explicitly avoid Application Software and Semiconductor Materials & Equipment within IT. Because the overall score is anti-predictive, this directive rests on industry/sector alpha evidence — NOT on trusting the composite score. Regime caveat: single bull-led window; these relationships can flip out-of-sample.
3. **Investigate the inverted alpha spread directly.** "Cheap" bottom-third names outperform, so the valuation dimension appears mis-signed. Down-weight valuation in the composite — implement as an engineering change with a documented data shift, not a threshold flip.
4. **Defensive recall is the priority project.** Build screening to catch the ~181 HOLD-rated names that fell >15% — momentum breakdown, premium valuation post-run-up, insider-selling clusters. Calibrate REDUCE to catch mid-severity declines short of AVOID conviction; the REDUCE+AVOID combined recall (34.3%) is the metric to move.
5. **Weight free cash flow and balance-sheet quality more heavily for high-multiple names post-run-up** — the missed HOLD blow-ups (ADMA, HON) were richly-valued names that broke down, exactly where the anti-predictive valuation signal hurts most.

## Areas of Strength

1. **Positive-alpha IT industries (+2.13pp at sector level, 162 calls)** — the only beta-stripped edge, concentrated in Systems Software, Tech Hardware, Semiconductors, and Payment Processing. Concentrate at industry granularity. Regime caveat: single window; may not persist.
2. **HOLD is the best-selecting bucket (+0.53pp alpha, 51.7% beat)** — an honest, positive-alpha default that out-picks the active bullish books.
3. **Downside containment:** worst BUY −27.1% vs worst HOLD −49.1% — issued BUYs avoid the deepest holes (risk management, not selection).
4. **AVOID precision (understated by survivorship):** issued AVOIDs average slightly-negative alpha; the 1.4% AVOID follow-up gap (7× BUY) means true precision is somewhat better than measured. Precision only — recall remains poor.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2026-07-20 | n=6,174. No sign flips. BUY −0.92pp; score anti-predictive 5th cycle (−1.7pp); AVOID recall 22.0%; AVOID survivorship gap 7×. ALL thresholds HELD by choice. |
| 2026-07-27 | n=6,387. No sign flips. BUY −0.89pp. Score anti-predictive 6th cycle (−1.53pp). AVOID recall 20.8%/26.8%. ALL thresholds HELD by choice. |
| 2026-08-03 | n=7,309 (+922). No sign flips. BUY −0.78pp; HOLD only positive-alpha bucket (+0.37pp); score anti-predictive 7th cycle (−1.54pp); AVOID recall 20.2%. ALL thresholds HELD by choice. |
| 2026-08-10 | UPDATE. n=7,496 (+187). FIRST five-bucket (five_level_v1) outcome report. Legacy three-bucket distribution targets, 70% HOLD floor, and rating-volume quotas RETIRED per taxonomy contract change — not a data reversal. BUY −0.75pp (no edge); ACCUMULATE +0.05pp (flat); HOLD best-selecting (+0.47pp); REDUCE −0.47pp / AVOID −0.27pp. Score anti-predictive 8th cycle (−1.39pp). Defensive recall 20.7%/33.3%. AVOID survivorship gap 7×. Surviving analytical thresholds HELD by choice. |
| **2026-08-17** | **UPDATE. n=8,117 (+621). (1) BUY alpha −0.75pp, 39.0% beat — sign AND magnitude unchanged on a large +621 sample; the non-edge is now a stable, well-sampled result, still NOT skill. Raw +0.38% is beta. (2) ACCUMULATE +0.15pp alpha (48.4% beat) — up from +0.05 but still within noise of neutral; no demonstrated edge. HOLD remains best-selecting bucket (+0.53pp, 51.7%), the only clearly positive-alpha bucket. (3) REDUCE −0.26pp / AVOID −0.27pp — both weakly negative; AVOID understated by survivorship. (4) Score ANTI-PREDICTIVE for a 9th consecutive cycle: alpha spread −1.39pp (top +0.5pp, bottom +1.89pp, n=6,164) — stable vs prior cycle; sign unchanged. Most durable finding in dataset. (5) Defensive recall: strict AVOID 21.3% (>−15%) / 28.3% (>−20%); REDUCE+AVOID combined 34.3% / 43.4% — REDUCE adds ~13pp coverage but 181 of 284 missed >−15% names still sit in HOLD. (6) Survivorship: AVOID gap 1.4% (12/875) vs BUY 0.2%, 7× — AVOID alpha understates true signal. (7) IT edge (+2.13pp, 162) carried by Systems Software (+6.45pp), Tech Hardware (+6.14pp), Semiconductors (+3.5pp), Payment Processing (+2.27pp); Application Software (−0.49pp) and Semi Materials & Equipment (−0.32pp) drag. Energy remains worst structural alpha sink across all sub-industries. STABILITY: last non-taxonomy policy change was 2026-06-11 (67d, ≥30d — time gate does not block a reversal). NO qualifying data-backed distribution shift this cycle: no alpha sign flipped at adequate n, the score inversion held a 9th cycle, and every metric movement (BUY −0.75→−0.75pp; ACCUMULATE +0.05→+0.15pp; recall 20.7→21.3pp; alpha spread flat at −1.39pp) is within noise despite the +621 sample. Therefore surviving analytical thresholds (BUY score floor, sector/industry prohibitions, AVOID negative-momentum gate) HELD for stability — not re-tuned on within-noise movement. Retired legacy items remain removed per contract. Open unsolved problems: (a) inverted alpha spread, (b) defensive recall.** |

## Stability Protocol Note

Last non-taxonomy policy change: 2026-06-11 (67 days ago, ≥30d — the time gate no longer blocks a reversal). No reversal is made this cycle because **no qualifying data-backed distribution shift occurred**: no alpha sign flipped at adequate n, the score inversion held for a 9th consecutive cycle, and every single-cycle metric movement is within noise even on a +621 sample. The ACCUMULATE alpha tick (+0.05 → +0.15pp) is not a validated edge and does not justify relaxing any bullish threshold. Legacy three-bucket distribution targets, the 70% HOLD floor, and rating-volume quotas remain retired by contract; no forced distribution replaces them. Surviving analytical thresholds (BUY score floor, sector/industry prohibitions, AVOID negative-momentum gate) are **MAINTAINED by choice** — relaxing them on a within-noise cycle would be noise-fitting. Any future down-weighting of the valuation dimension (to address the inverted alpha spread) must be an engineering change with a documented data shift, not a threshold flip. As post-transition five-bucket sample accumulates, each bucket — especially the BUY/ACCUMULATE split and REDUCE — will be re-evaluated on realized alpha before any threshold is tuned.