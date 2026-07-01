---
layout: default
title: "Track Record"
---

*Last updated: June 30, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 5,900 reports with follow-up return data (+803 vs last cycle).

| Recommendation | Count | Avg Return | Hit Rate | ALPHA vs SPY | Beat-SPY Rate |
|---|---|---|---|---|---|
| BUY | 1,019 | +0.2% | 46.7% | **−0.95pp** | 37.3% (n=1,016) |
| HOLD | 4,015 | +0.32% | 50.9% | **+0.46pp** | 51.1% (n=3,954) |
| AVOID | 864 | +0.07% | 48.0% | **−0.31pp** | 45.8% (n=855) |

**Read this honestly. On alpha the BUY book still has no selection edge.** BUY's raw +0.2% is market beta — stripped of SPY, BUYs *underperform the index by 0.95pp* and beat SPY only 37.3% of the time. The system is not picking winners; it is riding a rising tape with a slightly-worse-than-market basket. Notably, **HOLD is now the only positive-alpha bucket (+0.46pp, 51.1% beat rate)** — the default "do nothing" bucket out-selects the active BUY book. That is a damning comparison: our conviction calls add negative selection value versus our non-calls. The BUY alpha *improved* modestly (−1.21pp → −0.95pp) but remains negative and this is within the range of cycle-to-cycle noise given the volume change — do NOT credit it as an emerging edge.

**Score Predictiveness — still anti-predictive on alpha.** Top-third raw +0.4% vs bottom-third −0.01% (raw spread +0.41pp). But the **alpha spread is −2.22pp** (top −0.42pp vs bottom +1.8pp, n=4,096). The highest-scored names *underperform* SPY while the lowest-scored *beat* it. The positive raw spread is pure market beta; beta-stripped, the score sorts winners from losers in the *wrong direction*. This inversion has now persisted across four consecutive cycles (−2.03 → −2.42 → −2.22pp). It is the single most important, most durable finding in the dataset.

**Restraint vs. selection.** BUY volume ticked up (1,019 of 5,900, 17.3% cumulative). Selection quality did NOT improve on any durable basis — alpha is still negative and the alpha spread still inverted. We remain beta-tracking.

**AVOID Recall — the unsolved weakness.** Of 295 names that fell >15%, the system flagged only **73 as AVOID (recall 24.7%)** — 222 were missed (38 rated BUY, 184 HOLD). Of 131 names that fell >20%, only **38 flagged (recall 29.0%)**, 93 missed. The correctly-negative issued-AVOID return (precision) says nothing about the ~75% of blow-ups we failed to flag. Recall is essentially flat vs last cycle (23.3% → 24.7%, within noise). This remains a distinct, unresolved failure.

**Survivorship Bias.** Of 4,332 snapshots old enough for follow-up, 10 (0.2%) lack one. The gap is non-uniform: AVOID 0.4% (3/722) vs BUY 0.1% (1/915). The worst AVOID outcomes (delistings/takeouts) are disproportionately absent, so the measured AVOID record modestly **understates** true AVOID signal. The −0.31pp AVOID alpha is a slight overstatement of AVOID weakness — but nowhere near enough to rescue the recall problem.

## Identified Biases

1. **Score is anti-predictive on alpha (CRITICAL).** Top-third names underperform SPY by 0.42pp; bottom-third beat by 1.8pp. High-conviction BUYs continue to crater: DOCS (7.03 → −27.1%), BMI (7.06 → −20.6%), TRMB (6.8 → −19.7%), APO (7.55 → −16.9%). Scores >7.5 are not protective.

2. **BUY adds no selection alpha (CRITICAL).** −0.95pp average alpha, 37.3% beat-SPY rate — worse than the HOLD bucket's +0.46pp.

3. **AVOID Recall ~25–29% (HIGH, unsolved).** The system misses roughly three of every four large declines, parking them in HOLD (184 of 222 missed >−15% names).

4. **Sector alpha (judge on alpha, not raw):**
   - Consumer Discretionary BUY: −2.65% raw, **−3.72pp alpha** (29) — worst large sector. Prohibition holds.
   - Energy BUY: −1.56% raw, **−2.87pp alpha** (160, largest cumulative alpha sink). Industry split confirms breadth: Oil & Gas E&P −3.8pp (80), Equip & Services −3.66pp (13), Midstream −2.41pp (12), Storage & Transport −1.66pp (20). Structural, not idiosyncratic.
   - Materials: **−2.82pp** (16). Industrials: **−1.63pp** (113). Financials: **−1.43pp** (299 — 29% of all BUYs). Within Financials, Regional Banks (−3.08pp, 49) and Investment Banking & Brokerage (−3.59pp, 15) are worst; Consumer Finance (+0.67pp, 10) is the lone near-neutral.
   - Health Care BUY: +0.99% raw but **−0.08pp alpha** (113) — NOT a validated sector-level alpha source. Heterogeneous: Health Care Services +2.94pp (11) and Biotechnology +1.85pp (33) carry positive alpha; Health Care Equipment (−1.36pp, 21) drags. Treat HC as neutral at sector level; positive signal is industry-specific and thin.
   - Communication Services: −0.18pp alpha (52) — neutral.
   - **Information Technology: +1.8pp alpha** (148) — the only sector with a real positive edge, but heterogeneous. Driven by Systems Software (+6.51pp, 20), Tech Hardware/Storage (+6.5pp, 11), Semiconductors (+3.73pp, 54), Payment Processing (+2.27pp, 25). Dragged by Application Software (−0.78pp, 28) and Electronic Equipment (−2.23pp, 12). Do NOT treat "IT" wholesale as the edge.

## Lessons for Future Analysis

1. **Stop crediting raw BUY return as skill.** Until alpha turns positive at adequate n across ≥2 cycles, treat the BUY book as beta-tracking. The fix is selection quality, not volume.
2. **Concentrate BUYs in the positive-alpha industries, not heterogeneous sectors.** Target Semiconductors (+3.73pp, n=54), Systems Software (+6.51pp, n=20), Tech Hardware/Storage (+6.5pp, n=11), Payment Processing (+2.27pp, n=25); Biotechnology (+1.85pp, n=33) and Health Care Services (+2.94pp, n=11) are suggestive but thin. Explicitly avoid Application Software and Electronic Equipment within IT. Because the overall score is anti-predictive, this directive rests on industry/sector alpha evidence — NOT on trusting the composite score. Regime caveat: single bull-led window; alpha relationships can flip out-of-sample.
3. **Investigate the inverted alpha spread directly.** "Cheap" names that underperform suggest the valuation dimension is mis-signed; growth_prospects appears to be the only positively-discriminating dimension. Down-weight valuation in the composite — implement as an engineering change with a documented data shift, not a threshold flip.
4. **AVOID recall is the priority project.** Build screening to catch the 184 HOLD-rated names that fell >15% — momentum breakdown, premium valuation post-run-up (the PLAB profile, −35% from a 6.33 HOLD), insider-selling clusters. Going-concern language is high-precision/low-recall and not a general tail detector.
5. **MAINTAIN existing thresholds** (see Stability Protocol).

## Areas of Strength

1. **Positive-alpha industries within IT (+1.8pp at sector level, 148 calls)** — the only beta-stripped edge, concentrated in Semiconductors, Systems Software, Tech Hardware, and Payment Processing. Concentrate at industry granularity. Regime caveat: single window; may not persist.
2. **HOLD is now the best-selecting bucket (+0.46pp alpha, 51.1% beat rate)** — an honest, positive-alpha default that out-picks the active BUY book.
3. **Downside containment:** worst BUY −27.1% vs worst HOLD −49.1% — issued BUYs avoid the deepest holes (risk management, not selection).
4. **AVOID precision:** issued AVOIDs average near-zero/negative alpha; KLAR (−26.9%), CPB (−16.2%) validate. (Precision only — recall remains poor.)

## Calibration Changelog

| Date | Entry |
|---|---|
| 2026-05-25 | n=3,423. Hierarchy restored; BUY non-functional; raw spread 0.67pp. |
| 2026-06-03 | n=4,043. Hierarchy re-inverted. BUY threshold raised to 8.0/8.5; volume cut 8–10%; Financials cap 8%; AVOID negative-momentum gate added. |
| 2026-06-11 | n=4,695. Raw hierarchy re-ordered BUY>HOLD>AVOID; credited restraint. Health Care elevated (later reversed). |
| 2026-06-17 | n=4,806. ALPHA REFRAME — prior "recovery" was beta. BUY −1.24pp; score anti-predictive (alpha spread −2.03pp); AVOID recall 24.4%; HC/Comms demoted to neutral. All thresholds HELD. |
| 2026-06-24 | n=5,097. Findings confirmed within noise, no sign flips. BUY alpha −1.21pp; score anti-predictive (alpha spread −2.42pp); AVOID recall 23.3%; AVOID survivorship gap 0.5% vs BUY 0.1%; IT edge carried by Systems Software/Tech Hardware/Semis/Payments. All thresholds HELD for stability (last change 7d prior). |
| **2026-07-01** | **UPDATE. n=5,900 (+803). Findings persist; no sign flips. (1) BUY alpha −0.95pp (was −1.21pp), 37.3% beat-SPY — still NO selection edge; the improvement is within noise given +803 volume, NOT a durable trend. Raw +0.2% is beta. (2) NEW OBSERVATION: HOLD is now the only positive-alpha bucket (+0.46pp, 51.1% beat) — the passive default out-selects the active BUY book. (3) Score remains ANTI-PREDICTIVE for a 4th consecutive cycle: alpha spread −2.22pp (top −0.42pp, bottom +1.8pp, n=4,096). Direction unchanged; magnitude tightened slightly (−2.42 → −2.22) but still deeply inverted. (4) AVOID RECALL 24.7% (>−15%) / 29.0% (>−20%) — still missing ~75% of blow-ups, 184 of 222 into HOLD. Flat vs last cycle. (5) Survivorship: AVOID gap 0.4% vs BUY 0.1% — AVOID record slightly understates true signal. (6) Industry detail: IT edge (+1.8pp) carried by Systems Software (+6.51pp), Tech Hardware (+6.5pp), Semiconductors (+3.73pp), Payment Processing (+2.27pp); Application Software (−0.78pp) and Electronic Equipment (−2.23pp) drag. HC neutral at sector (−0.08pp); Biotech (+1.85pp) and HC Services (+2.94pp) positive but thin. Energy confirmed worst structural alpha sink across all sub-industries. STABILITY: last policy change was 2026-06-11 (20 days ago, <30d). No qualifying distribution shift — sample grew but no alpha sign flip at adequate n, all movements within noise. Therefore ALL thresholds HELD — BUY floor 8.0/8.5, volume 8–10%, Financials cap 8%, AVOID negative-momentum gate, HOLD floor 70% unchanged. This is a measurement refinement, NOT a policy reversal. Open unsolved problems remain: (a) the inverted alpha spread and (b) AVOID recall.** |

## Stability Protocol Note

Last policy change: 2026-06-11 (20 days ago, <30d). No data-backed distribution shift qualifies a reversal this cycle: sample grew ~803, but no alpha sign flipped at adequate n and all single-cycle movements are within noise (BUY alpha −1.21 → −0.95pp; recall 23.3 → 24.7pp; alpha spread −2.42 → −2.22pp — all same-direction wobbles). The modest BUY-alpha uptick is NOT grounds to relax the BUY floor or raise volume — that would be re-tuning on one cycle's noise. **All thresholds and prohibitions are MAINTAINED for stability.** This update changes *interpretation and observation* (HOLD now positive-alpha) — it does not flip any score floor, volume target, or sector rule. Any future down-weighting of the valuation dimension must be an engineering change with a documented data shift, not a threshold flip.