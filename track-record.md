---
layout: default
title: "Track Record"
---

*Last updated: June 24, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 5,097 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate | ALPHA vs SPY | Beat-SPY Rate |
|---|---|---|---|---|---|
| BUY | 959 | +0.11% | 45.7% | **−1.21pp** | 35.0% (n=956) |
| HOLD | 3,361 | −0.02% | 48.0% | **−0.16pp** | 46.6% (n=3,300) |
| AVOID | 775 | −0.13% | 46.7% | **−0.76pp** | 42.2% (n=766) |

**Read this honestly: the raw ranking is nearly flat (BUY +0.11%, HOLD −0.02%, AVOID −0.13%) and on alpha the apparent BUY edge vanishes.** BUY's raw +0.11% is market beta — stripped of SPY, BUYs *underperform the index by 1.21pp* and beat SPY only 35.0% of the time. The system is not picking winners; it is riding a rising tape with a slightly worse-than-market basket. HOLD is the closest to neutral (−0.16pp alpha). The "BUY edge" claimed in older calibrations is an artifact of raw return in a bull market and should not be credited as skill. The alpha numbers are essentially unchanged from last cycle (BUY −1.24pp → −1.21pp; this is noise, not improvement).

**Score Predictiveness — anti-predictive on alpha.** Top-third raw +0.34% vs bottom-third −0.38% (raw spread +0.71pp). But the **alpha spread is −2.42pp** (top −1.29pp vs bottom +1.13pp, n=3,526). The highest-scored names *underperform* SPY while the lowest-scored *beat* it. The positive raw spread is pure market beta; on a beta-stripped basis the score sorts winners from losers in the *wrong direction*. This is the single most important finding in the dataset and it has now persisted across multiple cycles (−2.03pp last cycle → −2.42pp this cycle).

**Restraint vs. selection.** BUY volume remains compressed (959 of 5,097, 18.8% cumulative). Restraint contained downside (risk management), but it did **not** improve selection — alpha is still negative and the alpha spread still inverted. We are more selective; our selection is not better.

**AVOID Recall — the unsolved weakness.** Of 245 names that fell >15%, the system flagged only **57 as AVOID (recall 23.3%)** — 188 were missed (35 rated BUY, 153 HOLD). Of 107 names that fell >20%, only **32 flagged (recall 29.9%)**, 75 missed. The negative average AVOID return (precision) says issued AVOIDs were reasonable; it says nothing about the ~77% of blow-ups we failed to flag. Better AVOIDs do not fix not issuing them. This is a distinct, unresolved failure — and recall actually slipped versus last cycle (24.4% → 23.3%, within noise).

**Survivorship Bias.** Of 3,759 snapshots old enough for follow-up, 7 (0.2%) lack one. The gap is non-uniform: AVOID 0.5% (3/611) vs BUY 0.1% (1/851). The worst AVOID outcomes (delistings/takeouts) are disproportionately absent, so the measured AVOID record modestly **understates** true AVOID signal. The −0.76pp AVOID alpha is a slight overstatement of AVOID weakness — but nowhere near enough to rescue the recall problem.

## Identified Biases

1. **Score is anti-predictive on alpha (CRITICAL).** Top-third names underperform SPY by 1.29pp; bottom-third beat by 1.13pp — the spread *widened* this cycle. High-conviction BUYs continue to crater: DOCS (7.03 → −27.1%), BMI (7.06 → −20.6%), TRMB (6.8 → −19.7%), APO (7.55 → −16.9%). Scores >7.5 are not protective.

2. **BUY adds no selection alpha (CRITICAL).** −1.21pp average alpha, 35.0% beat-SPY rate. The book is riding the tape.

3. **AVOID Recall ~23–30% (HIGH, unsolved).** The system misses roughly three of every four large declines, parking them in HOLD (153 of 188 missed >−15% names).

4. **Sector alpha (judge on alpha, not raw):**
   - Consumer Discretionary BUY: −2.75% raw, **−3.92pp alpha** (28) — worst sector. Prohibition holds.
   - Energy BUY: −1.66% raw, **−3.05pp alpha** (156, largest cumulative alpha sink). Industry split confirms breadth: Oil & Gas E&P −3.98pp (78), Equip & Services −3.66pp (13), Midstream −3.49pp (11).
   - Materials: **−3.66pp** (15). Industrials: **−2.05pp** (105). Financials: **−1.66pp** (283 — 30% of all BUYs). Within Financials, Regional Banks (−3.27pp, 48) and Investment Banking & Brokerage (−3.59pp, 15) are the worst; only Asset Management (−0.49pp) is near neutral.
   - Health Care BUY: +0.79% raw but **−0.36pp alpha** (110) — NOT a validated alpha source. Industry split is heterogeneous: Health Care Services +2.94pp (11) and Biotechnology +1.45pp (31) carry positive alpha, while Health Care Equipment (−1.36pp, 21) drags. Treat HC as neutral at sector level; the positive signal is industry-specific and thin.
   - Communication Services: +0.04pp alpha (49) — neutral.
   - **Information Technology: +1.84pp alpha** (132) — the only sector with a real positive edge, but heterogeneous. Driven by Systems Software (+6.51pp, 20), Tech Hardware/Storage (+7.08pp, 10), Semiconductors (+4.10pp, 51), and Transaction & Payment Processing (+2.03pp, 24). Dragged by Application Software (−1.06pp, 25) and Electronic Equipment (−3.04pp, 11). Do NOT treat "IT" wholesale as the edge.

## Lessons for Future Analysis

1. **Stop crediting raw BUY return as skill.** Until alpha turns positive at adequate n, treat the BUY book as beta-tracking. The fix is selection quality, not volume.
2. **Concentrate BUYs in the positive-alpha industries, not heterogeneous sectors.** Target Semiconductors (+4.10pp, n=51), Systems Software (+6.51pp, n=20), Tech Hardware/Storage (+7.08pp, n=10), Transaction & Payment Processing (+2.03pp, n=24); Biotechnology (+1.45pp) and Health Care Services (+2.94pp) are suggestive but thin (n≤31). Explicitly avoid Application Software and Electronic Equipment within IT. Because the overall score is anti-predictive, this directive rests on industry/sector alpha evidence — NOT on trusting the composite score. Regime caveat: single bull-led window; alpha relationships can flip out-of-sample.
3. **Investigate the inverted alpha spread directly.** The valuation dimension scoring "cheap" names that underperform is the likely culprit; growth_prospects appears to be the only positively-discriminating dimension. Down-weight valuation in the composite — but implement as an engineering change with a documented data shift, not a threshold flip.
4. **AVOID recall is the priority project.** Build screening to catch the 153 HOLD-rated names that fell >15% — momentum breakdown, premium valuation post-run-up (the PLAB profile, −35% from a 6.33 HOLD), insider-selling clusters. Going-concern language is high-precision/low-recall and not a general tail detector.
5. **MAINTAIN existing thresholds** (see Stability Protocol).

## Areas of Strength

1. **Positive-alpha industries within IT (+1.84pp at sector level, 132 calls)** — the only beta-stripped edge, concentrated in Semiconductors, Systems Software, Tech Hardware, and Payment Processing. Concentrate at industry granularity. Regime caveat: single window; may not persist.
2. **Downside containment:** worst BUY −27.1% vs worst HOLD −40.4% — issued BUYs avoid the deepest holes.
3. **AVOID precision:** issued AVOIDs average negative raw return; KLAR (−26.9%), CPB (−16.2%) validate. (Precision only — recall remains poor.)
4. **HOLD is near alpha-neutral (−0.16pp)** — an honest default.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2026-05-25 | n=3,423. Hierarchy restored; BUY non-functional; raw spread 0.67pp. |
| 2026-06-03 | n=4,043. Hierarchy re-inverted. BUY threshold raised to 8.0/8.5; volume cut 8–10%; Financials cap 8%; AVOID negative-momentum gate added. |
| 2026-06-11 | n=4,695. Raw hierarchy re-ordered BUY>HOLD>AVOID; credited restraint. Health Care elevated (later reversed). |
| 2026-06-17 | n=4,806. ALPHA REFRAME — prior "recovery" was beta. BUY −1.24pp; score anti-predictive (alpha spread −2.03pp); AVOID recall 24.4%; HC/Comms demoted to neutral. All thresholds HELD (last change 6 days prior). |
| **2026-06-24** | **UPDATE. n=5,097 (+291). Findings confirm and slightly sharpen prior cycle — all movements within noise, no sign flips. (1) BUY alpha −1.21pp (was −1.24pp), 35.0% beat-SPY — NO selection edge; raw +0.11% is beta. (2) Score remains ANTI-PREDICTIVE: alpha spread −2.42pp (top −1.29pp, bottom +1.13pp, n=3,526), wider than last cycle but same direction — ranking sorts backwards beta-stripped. (3) AVOID RECALL 23.3% (>−15%) / 29.9% (>−20%) — system still misses ~77% of blow-ups, mostly into HOLD (153 of 188). (4) Survivorship: AVOID gap 0.5% vs BUY 0.1% — AVOID record slightly understates true signal. (5) Industry detail sharpened: IT edge (+1.84pp) is carried by Systems Software (+6.51pp), Tech Hardware (+7.08pp), Semiconductors (+4.10pp), Payment Processing (+2.03pp); Application Software (−1.06pp) and Electronic Equipment (−3.04pp) drag. HC neutral at sector (−0.36pp) but Biotech (+1.45pp) and HC Services (+2.94pp) positive (thin n). Energy confirmed worst structural alpha sink across all sub-industries. STABILITY: last change was 7 days ago (<30d). No qualifying distribution shift — sample grew ~291, no alpha sign flip at adequate n, all moves within noise. Therefore ALL thresholds HELD for stability — BUY floor 8.0/8.5, volume 8–10%, Financials cap 8%, AVOID negative-momentum gate, HOLD floor 70% unchanged. This is a measurement refinement, NOT a policy reversal. Primary directives unchanged: stop reading raw BUY return as skill; concentrate residual BUYs in the named positive-alpha industries; AVOID recall and the inverted alpha spread remain the two open, unsolved problems.** |

## Stability Protocol Note

Last policy change: 2026-06-11 (13 days ago, <30d). No data-backed distribution shift qualifies a reversal this cycle: sample grew ~291 names, no alpha sign flip at adequate n, all single-cycle movements within noise (BUY alpha −1.24→−1.21pp, recall 24.4→23.3pp). **All thresholds and prohibitions are MAINTAINED for stability.** This update changes *interpretation and industry granularity* — it does not flip any score floor, volume target, or sector rule. Any future down-weighting of the valuation dimension must be an engineering change with a documented data shift, not a threshold flip.