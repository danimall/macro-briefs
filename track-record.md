---
layout: default
title: "Track Record"
---

*Last updated: June 17, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 4,806 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate | ALPHA vs SPY | Beat-SPY Rate |
|---|---|---|---|---|---|
| BUY | 935 | +0.09% | 45.7% | **−1.24pp** | 34.7% (n=932) |
| HOLD | 3,112 | +0.02% | 48.5% | **−0.06pp** | 47.5% (n=3,051) |
| AVOID | 757 | −0.09% | 47.4% | **−0.71pp** | 42.9% (n=748) |

**Read this honestly: the raw ranking looks correct (BUY > HOLD > AVOID), but on alpha the picture inverts.** BUY's raw +0.09% is pure market beta — stripped of SPY, BUYs *underperform the index by 1.24pp* and beat SPY only 34.7% of the time. The system is not picking winners; it is riding a rising tape with a slightly worse-than-market basket. HOLD is the only category near alpha-neutral (−0.06pp). The "BUY edge" claimed in prior calibrations is an artifact of raw return in a bull market and should not be credited as skill.

**Score Predictiveness — anti-predictive on alpha.** Top-third raw +0.31% vs bottom-third −0.29% (raw spread +0.61pp). But the **alpha spread is −2.03pp** (top −1.28pp vs bottom +0.75pp, n=3,134). The highest-scored names *underperform* SPY while the lowest-scored *beat* it. The raw spread is entirely market beta; on a beta-stripped basis the score sorts winners from losers in the *wrong direction*. This is the single most important finding in the dataset and it has persisted across cycles.

**Restraint vs. selection.** BUY volume remains compressed (935 of 4,806, 19.5% cumulative). Prior calibrations credited the "restored hierarchy" to this restraint. State plainly: restraint improved raw aggregates and contained downside (risk management), but it did **not** improve selection — alpha is still negative and the alpha spread still inverted. We got more selective; our selection did not get better.

**AVOID Recall — the unsolved weakness.** Of 217 names that fell >15%, the system flagged only **53 as AVOID (recall 24.4%)** — 164 were missed (31 rated BUY, 133 HOLD). Of 96 names that fell >20%, only **31 flagged (recall 32.3%)**, 65 missed. The negative average AVOID return (precision) says issued AVOIDs were reasonable calls; it says nothing about the ~75% of blow-ups we failed to flag at all. Better AVOIDs do not fix not issuing them. This is a distinct, unresolved failure.

**Survivorship Bias.** Of 3,367 snapshots old enough for follow-up, 7 (0.2%) lack one. The gap is non-uniform: AVOID 0.5% (3/552) vs BUY 0.1% (1/800). The worst AVOID outcomes (delistings/takeouts) are disproportionately absent, so the measured AVOID record modestly **understates** true AVOID signal. The −0.71pp AVOID alpha is a slight overstatement of AVOID weakness — but not enough to rescue the recall problem.

## Identified Biases

1. **Score is anti-predictive on alpha (CRITICAL).** Top-third names underperform SPY by 1.28pp; bottom-third beat by 0.75pp. The ranking engine is sorting backwards once beta is removed. High-conviction BUYs continue to crater: DOCS (7.03 → −27.1%), BMI (7.06 → −20.6%), TRMB (6.8 → −19.7%), APO (7.55 → −16.9%). Scores >7.5 are not protective.

2. **BUY adds no selection alpha (CRITICAL).** −1.24pp average alpha, 34.7% beat-SPY rate. The book is riding the tape.

3. **AVOID Recall ~24–32% (HIGH, unsolved).** The system misses three of every four large declines, parking them in HOLD (133 of 164 missed >−15% names).

4. **Sector alpha (judge on alpha, not raw):**
   - Consumer Discretionary BUY: −2.75% raw, **−3.92pp alpha** (28 calls) — worst. Prohibition holds.
   - Energy BUY: −1.59% raw, **−3.02pp alpha** (145 calls) — largest cumulative alpha sink.
   - Materials: **−3.66pp alpha** (15). Industrials: **−2.05pp** (105). Financials: **−1.69pp** (280 calls, 30% of all BUYs — 3× cap).
   - Health Care BUY: +1.12% raw but **−0.07pp alpha** (95) — essentially zero edge, NOT a validated alpha source. Prior elevation was beta.
   - Communication Services: +0.03pp alpha (47) — neutral.
   - **Information Technology: +1.83pp alpha** (131) — the only sector with a real positive edge. Semiconductors +0.16pp (12, thin).

## Lessons for Future Analysis

1. **Stop crediting raw BUY return as skill.** Until alpha turns positive at adequate n, treat the BUY book as beta-tracking. The fix is selection quality, not volume.
2. **Concentrate BUYs in Information Technology — the sole positive-alpha sector (+1.83pp).** Demote Health Care and Comms to neutral/HOLD-default; their apparent edge was market beta.
3. **Investigate the inverted alpha spread directly.** The valuation dimension scoring "cheap" names that underperform is the likely culprit; growth_prospects is the only positively-discriminating dimension. Down-weight valuation in the composite (pending engineering confirmation).
4. **AVOID recall is the priority project.** Build screening to catch the 133 HOLD-rated names that fell >15% — momentum breakdown, insider selling clusters, premium valuation post-run-up (the PLAB/IBP profile). Going-concern language is high-precision/low-recall (~0.15%) and not a general tail detector.
5. **MAINTAIN existing thresholds** (see Stability Protocol): BUY score floor 8.0/8.5, BUY volume 8–10%, Financials hard cap 8%, AVOID max score 4.0 + negative-momentum gate, HOLD floor 70%.

## Areas of Strength

1. **Information Technology BUY (+1.83pp alpha, 131 calls)** — the only durable, beta-stripped edge. Maintain concentration here.
2. **Downside containment:** worst BUY −27.1% vs worst HOLD −40.4% — issued BUYs avoid the deepest holes.
3. **AVOID precision:** issued AVOIDs average negative raw return; KLAR (−26.9%), CPB (−16.2%) validate. (Precision only — recall remains poor.)
4. **HOLD is alpha-neutral (−0.06pp)** — an honest default that neither helps nor hurts.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2026-05-25 | n=3,423. Hierarchy restored; BUY non-functional; raw spread 0.67pp. |
| 2026-06-03 | n=4,043. Hierarchy re-inverted. BUY threshold raised to 8.0/8.5; volume cut 8–10%; Financials cap 8%; AVOID negative-momentum gate added. |
| 2026-06-11 | n=4,695. Raw hierarchy re-ordered BUY>HOLD>AVOID; credited restraint. Health Care elevated to secondary alpha source. |
| **2026-06-17** | **UPDATE. n=4,806. ALPHA REFRAME — prior "recovery" was beta. Key findings: (1) On alpha, BUY is −1.24pp (34.7% beat-SPY) — NO selection edge; the +0.09% raw return is market beta. (2) Score is ANTI-PREDICTIVE on alpha: alpha spread −2.03pp (top −1.28pp, bottom +0.75pp) — ranking sorts backwards beta-stripped. (3) AVOID RECALL 24.4% (>−15%) / 32.3% (>−20%) — system misses ~75% of blow-ups, mostly into HOLD; precision ≠ recall. (4) Survivorship: AVOID gap 0.5% vs BUY 0.1% — measured AVOID record slightly understates true signal. (5) On alpha, only IT (+1.83pp) has a real edge; Health Care (−0.07pp) and Comms (+0.03pp) are neutral, NOT validated — prior elevation was beta. Consumer Disc (−3.92pp), Materials (−3.66pp), Energy (−3.02pp) confirmed alpha sinks. STABILITY: last change was 6 days ago (<30d). No qualifying distribution shift this cycle (n grew ~111, no alpha sign flip at adequate n). Therefore all thresholds HELD for stability — BUY floor 8.0/8.5, volume 8–10%, Financials cap 8%, AVOID gate, HOLD floor 70% unchanged. The reframe is a measurement correction, not a policy reversal. Primary directive: stop reading raw BUY return as skill; concentrate residual BUYs in IT; treat AVOID recall and the inverted alpha spread as the two open, unsolved problems.** |

## Stability Protocol Note

Last policy change: 2026-06-11 (6 days ago, <30d). No data-backed distribution shift qualifies a reversal this cycle: sample grew only ~111 names, no alpha sign flip at adequate n, single-cycle movements within noise. **All thresholds and prohibitions are MAINTAINED for stability.** This update changes *interpretation* (alpha-framed, recall-aware) — it does not flip any score floor, volume target, or sector rule. Any future down-weighting of the valuation dimension must be implemented as an engineering change with a documented data shift, not a threshold flip.