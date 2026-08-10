---
layout: default
title: "Track Record"
---

*Last updated: August 10, 2026*

*Rating policy: five_level_v1*

> **Scale transition note.** This is the first calibration cycle reporting the full five-bucket taxonomy (BUY / ACCUMULATE / HOLD / REDUCE / AVOID) on realized outcomes. Legacy three-bucket distribution targets, the 70% HOLD floor, and legacy rating-volume quotas are **retired** — not reversed on data, but removed by contract change. No rating distribution is forced. Each bucket is now evaluated on its own realized alpha and calibration as post-transition sample accumulates. Empirical observations about selection alpha, score behavior, sector effects, and missed downside carry forward where still supported.

## Track Record Summary

**Overall dataset:** 7,496 reports with follow-up return data (+187 vs last cycle).

| Recommendation | Count | Avg Return | Hit Rate | ALPHA vs SPY | Beat-SPY Rate |
|---|---|---|---|---|---|
| BUY | 1,087 | +0.38% | 48.2% | **−0.75pp** | 38.9% |
| ACCUMULATE | 1,470 | +0.49% | 51.6% | **+0.05pp** | 47.8% |
| HOLD | 3,522 | +0.60% | 52.9% | **+0.47pp** | 51.2% |
| REDUCE | 496 | −0.87% | 49.0% | **−0.47pp** | 50.2% |
| AVOID | 920 | +0.06% | 47.9% | **−0.27pp** | 46.2% |

**Read this honestly. On alpha the BUY book still has no selection edge.** BUY's raw +0.38% is market beta — beta-stripped, BUYs *underperform SPY by 0.75pp* and beat the index only 38.9% of the time. The system is not picking winners; it is riding a rising tape with a slightly-worse-than-market basket. **HOLD remains the only clearly positive-alpha bucket (+0.47pp, 51.2% beat)** — the passive default still out-selects the active BUY book. **ACCUMULATE is essentially flat (+0.05pp, 47.8% beat)** — a hair above neutral, no demonstrated edge. The two active bullish buckets (BUY, ACCUMULATE) together add ~zero-to-negative alpha; the do-nothing bucket adds the most.

**The bearish buckets do NOT sort as intended.** REDUCE (−0.47pp alpha) is the correct sign but weaker downside than AVOID's raw figure suggests, and AVOID at −0.27pp is only marginally negative on alpha. Neither strongly separates losers — but see survivorship caveat below, which materially affects AVOID.

BUY alpha moved −0.78 → −0.75pp on a modest +187 sample. Sign unchanged; magnitude is same-direction drift, NOT a validated edge. Do not credit it as skill.

**Score Predictiveness — still anti-predictive on alpha.** Top-third raw +0.56% vs bottom-third +0.17% (raw spread +0.40pp). But the **alpha spread is −1.39pp** (top +0.5pp vs bottom +1.89pp, n=6,164). The lowest-scored names *beat* SPY while the highest-scored barely track it. The positive raw spread is pure market beta; beta-stripped, the score sorts the *wrong direction*. This inversion has now persisted across eight consecutive cycles (−2.03 → −2.42 → −2.22 → −1.7 → −1.53 → −1.54 → −1.39pp). It is the single most durable finding in the dataset. Do NOT read the modest narrowing (−1.54 → −1.39) as a trend toward predictiveness — it is within-noise wobble on top of a stable negative sign.

**Restraint vs. selection.** BUY volume is 1,087 of 7,496 (14.5%). Selection quality has NOT improved on any durable basis — alpha still negative, alpha spread still inverted. This is a beta problem, not a volume problem. Getting more selective would raise aggregates without proving the signal got better; only rising alpha would show that.

**AVOID Recall — the unsolved weakness.** Of 420 names that fell >15%, only **87 were flagged AVOID (strict recall 20.7%)**; adding REDUCE lifts defensive recall to **33.3%** (140/420). 280 were MISSED (42 BUY, 61 ACCUMULATE, 177 HOLD). Of 210 names that fell >20%, **58 AVOID (recall 27.6%)**, **90 REDUCE+AVOID (42.9%)**, 120 missed. The system still parks the majority of blow-ups in bullish/neutral buckets. AVOID *precision* (do issued AVOIDs fall?) says nothing about this recall gap.

**Survivorship Bias.** Of 6,192 snapshots old enough for follow-up, 27 (0.4%) lack one. The gap is non-uniform: **AVOID 1.4% (12/875) vs BUY 0.2% (2/1,036)** — a 7× ratio; REDUCE has 0% gap. The worst AVOID outcomes (delistings/takeouts) are disproportionately absent, so the measured AVOID alpha (−0.27pp) **understates** true AVOID signal. Treat AVOID's near-neutral alpha as a floor on its true value, not an unbiased estimate. This does NOT rescue the recall problem, which measures failures to flag, not the quality of flags issued.

## Identified Biases

1. **Score is anti-predictive on alpha (CRITICAL).** Bottom-third beats SPY by 1.89pp; top-third only +0.5pp. High-conviction bullish calls still crater: DOCS (BUY 7.03 → −27.1%), SNEX (ACCUMULATE 6.5 → −39.9%), PLAB (ACCUMULATE 6.33 → −35.1%), REZI (ACCUMULATE 6.12 → −28.6%), SAIL (ACCUMULATE 6.1 → −25.8%). High scores are not protective.

2. **BUY and ACCUMULATE add no selection alpha (CRITICAL).** BUY −0.75pp; ACCUMULATE +0.05pp (flat). Both active bullish buckets are at-or-below the HOLD default (+0.47pp).

3. **Defensive recall ~21–33% (HIGH, unsolved).** The system misses most large declines, parking 177 of 280 missed >−15% names in HOLD. Worst calls confirm: HON (5.3 HOLD → −49.1%), ADMA (5.98 HOLD → −40.4%). REDUCE catches an incremental slice (recall +12.6pp), but the combined defensive net still lets ~two-thirds of >−15% names through.

4. **Sector alpha (judge on alpha, not raw):**
   - Consumer Discretionary BUY: −2.03% raw, **−3.05pp alpha** (32) — worst large sector.
   - Energy BUY: −1.5% raw, **−2.81pp alpha** (167, largest cumulative alpha sink). Industry split confirms breadth: Oil & Gas E&P −3.84pp (84), Equip & Services −3.66pp (13), Midstream −2.17pp (13), Storage & Transport −1.66pp (20). Structural, not idiosyncratic. Refining & Marketing (−0.02pp, 19) is the lone near-neutral pocket.
   - Materials: **−2.82pp** (16). Industrials: **−1.47pp** (117). Financials: **−1.26pp** (317, 29% of BUYs). Within Financials, Investment Banking & Brokerage (−3.75pp, 18) and Regional Banks (−2.75pp, 53) worst; Consumer Finance (+0.84pp, 11) lone near-positive.
   - Health Care BUY: +1.23% raw but **+0.27pp alpha** (123) — marginal at sector level. Heterogeneous: Health Care Services +2.94pp (11), Health Care Facilities +2.13pp (10), Biotechnology +1.86pp (35), Pharmaceuticals +0.41pp (26) positive; Health Care Equipment (−1.07pp, 23) drags. Neutral-to-slightly-positive; real signal is thin and industry-specific.
   - **Information Technology: +2.13pp alpha** (160) — the only sector with a real positive edge, but heterogeneous. Driven by Systems Software (+6.45pp, 21), Tech Hardware/Storage (+6.14pp, 13), Semiconductors (+3.54pp, 61), Payment Processing (+2.27pp, 26). Dragged by Application Software (−0.49pp, 33) and Semiconductor Materials & Equipment (−0.32pp, 16). Do NOT treat "IT" wholesale as the edge.

## Lessons for Future Analysis

1. **Stop crediting raw bullish return as skill.** Until BUY/ACCUMULATE alpha turns positive at adequate n across ≥2 cycles, treat both as beta-tracking. The fix is selection quality, not volume.
2. **Concentrate bullish calls in the positive-alpha industries, not heterogeneous sectors.** Target Systems Software (+6.45pp, n=21), Tech Hardware/Storage (+6.14pp, n=13), Semiconductors (+3.54pp, n=61), Payment Processing (+2.27pp, n=26); Biotechnology (+1.86pp, n=35) and Health Care Services (+2.94pp, n=11) are suggestive but thin. Explicitly avoid Application Software and Semiconductor Materials & Equipment within IT. Because the overall score is anti-predictive, this directive rests on industry/sector alpha evidence — NOT on trusting the composite score. Regime caveat: single bull-led window; these alpha relationships can flip out-of-sample.
3. **Investigate the inverted alpha spread directly.** "Cheap" bottom-third names outperform, so the valuation dimension appears mis-signed. Down-weight valuation in the composite — implement as an engineering change with a documented data shift, not a threshold flip.
4. **Defensive recall is the priority project.** Build screening to catch the ~177 HOLD-rated names that fell >15% — momentum breakdown, premium valuation post-run-up, insider-selling clusters. Now that REDUCE exists as a softer defensive tier, calibrate it to catch the mid-severity declines that fall short of AVOID conviction; the REDUCE+AVOID combined recall (33.3%) is the metric to move.
5. **Weight free cash flow and balance-sheet quality more heavily for high-multiple names post-run-up** — the missed HOLD blow-ups (ADMA, HON) were richly-valued names that broke down, exactly where the anti-predictive valuation signal hurts most.

## Areas of Strength

1. **Positive-alpha IT industries (+2.13pp at sector level, 160 calls)** — the only beta-stripped edge, concentrated in Systems Software, Tech Hardware, Semiconductors, and Payment Processing. Concentrate at industry granularity. Regime caveat: single window; may not persist.
2. **HOLD is the best-selecting bucket (+0.47pp alpha, 51.2% beat)** — an honest, positive-alpha default that out-picks the active bullish books.
3. **Downside containment:** worst BUY −27.1% vs worst HOLD −49.1% — issued BUYs avoid the deepest holes (risk management, not selection).
4. **AVOID precision (understated by survivorship):** issued AVOIDs average slightly-negative alpha; the 1.4% AVOID follow-up gap (7× BUY) means true precision is somewhat better than measured. Precision only — recall remains poor.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2026-07-01 | n=5,900. BUY alpha −0.95pp; HOLD only positive-alpha bucket (+0.46pp); score anti-predictive 4th cycle (−2.22pp); AVOID recall 24.7%. All thresholds HELD (20d prior). |
| 2026-07-20 | n=6,174. No sign flips. BUY −0.92pp; score anti-predictive 5th cycle (−1.7pp); AVOID recall 22.0%; AVOID survivorship gap 7×. ALL thresholds HELD by choice. |
| 2026-07-27 | n=6,387. No sign flips. BUY −0.89pp, 38.1% beat. Score anti-predictive 6th cycle (−1.53pp). AVOID recall 20.8%/26.8%. ALL thresholds HELD by choice. |
| 2026-08-03 | n=7,309 (+922). No sign flips. BUY −0.78pp; HOLD only positive-alpha bucket (+0.37pp); score anti-predictive 7th cycle (−1.54pp); AVOID recall 20.2%. ALL thresholds HELD by choice (53d since last change, but no qualifying data shift). |
| **2026-08-10** | **UPDATE. n=7,496 (+187). FIRST five-bucket (five_level_v1) outcome report. (1) Legacy three-bucket distribution targets, 70% HOLD floor, and rating-volume quotas RETIRED per taxonomy contract change — not a data reversal. No distribution is now forced; each bucket evaluated on its own realized alpha. (2) BUY alpha −0.75pp (was −0.78), 38.9% beat — still NO edge; raw +0.38% is beta; +187 is same-direction drift. (3) ACCUMULATE +0.05pp alpha (47.8% beat) — flat, no demonstrated edge. HOLD remains best-selecting bucket (+0.47pp, 51.2%). (4) REDUCE −0.47pp / AVOID −0.27pp — bearish buckets weakly negative; AVOID understated by survivorship. (5) Score ANTI-PREDICTIVE for an 8th consecutive cycle: alpha spread −1.39pp (top +0.5pp, bottom +1.89pp, n=6,164) — modest narrowing vs −1.54 is within-noise; sign stable. Most durable finding in dataset. (6) Defensive recall: strict AVOID 20.7% (>−15%) / 27.6% (>−20%); REDUCE+AVOID combined 33.3% / 42.9% — REDUCE tier adds ~13pp of coverage but ~two-thirds of >−15% names still missed (177 in HOLD). (7) Survivorship: AVOID gap 1.4% (12/875) vs BUY 0.2%, 7× — AVOID alpha (−0.27pp) understates true signal. (8) IT edge (+2.13pp) carried by Systems Software (+6.45pp), Tech Hardware (+6.14pp), Semiconductors (+3.54pp), Payment Processing (+2.27pp); Application Software (−0.49pp) and Semi Materials & Equipment (−0.32pp) drag. Energy confirmed worst structural alpha sink across all sub-industries. STABILITY: last non-taxonomy policy change was 2026-06-11 (60d, ≥30d — time gate does not block a reversal). No qualifying data-backed distribution shift: no alpha sign flipped, score inversion held an 8th cycle, every single-cycle movement (BUY −0.78→−0.75pp; recall 20.2→20.7pp; alpha spread −1.54→−1.39pp) is within noise. The five-bucket taxonomy transition removes legacy quotas by contract but does NOT itself justify re-tuning surviving thresholds on this cycle's noise. Therefore surviving analytical thresholds (BUY floor, sector prohibitions, AVOID negative-momentum gate) HELD; retired items removed per contract. Open unsolved problems: (a) inverted alpha spread, (b) defensive recall.** |

## Stability Protocol Note

Last non-taxonomy policy change: 2026-06-11 (60 days ago, ≥30d — the time gate no longer blocks a reversal). This cycle I removed the legacy three-bucket distribution targets, the 70% HOLD floor, and rating-volume quotas **because the active taxonomy changed to five_level_v1** — this is a contract change, not a data-mined reversal, and no forced distribution replaces them. Surviving analytical thresholds (BUY score floor, sector/industry prohibitions, AVOID negative-momentum gate) are **MAINTAINED by choice**: no qualifying data-backed distribution shift occurred. No alpha sign flipped at adequate n, the score inversion held for an 8th consecutive cycle, and every single-cycle metric movement is within noise. Relaxing a BUY floor or reintroducing a volume target on a within-noise uptick would be noise-fitting. Any future down-weighting of the valuation dimension must be an engineering change with a documented data shift, not a threshold flip. As post-transition five-bucket sample accumulates, each bucket (especially REDUCE and the BUY/ACCUMULATE split) will be re-evaluated on realized alpha before any threshold is tuned.