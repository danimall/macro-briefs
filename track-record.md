---
layout: default
title: "Track Record"
---

*Last updated: August 3, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 7,309 reports with follow-up return data (+922 vs last cycle).

| Recommendation | Count | Avg Return | Hit Rate | ALPHA vs SPY | Beat-SPY Rate |
|---|---|---|---|---|---|
| BUY | 1,079 | +0.33% | 47.9% | **−0.78pp** | 38.7% (n=1,079) |
| HOLD | 5,319 | +0.41% | 52.1% | **+0.37pp** | 50.8% (n=5,319) |
| AVOID | 909 | +0.11% | 47.9% | **−0.20pp** | 46.2% (n=909) |

**Read this honestly. On alpha the BUY book still has no selection edge.** BUY's raw +0.33% is market beta — stripped of SPY, BUYs *underperform the index by 0.78pp* and beat SPY only 38.7% of the time. The system is not picking winners; it is riding a rising tape with a slightly-worse-than-market basket. **HOLD remains the only positive-alpha bucket (+0.37pp, 50.8% beat rate)** — the passive "do nothing" default still out-selects the active BUY book. BUY alpha moved −0.89 → −0.78pp; despite a large +922 sample this quarter, the sign is unchanged and the magnitude improvement is same-direction drift, NOT a validated edge. Do not credit it as skill.

**Score Predictiveness — still anti-predictive on alpha.** Top-third raw +0.52% vs bottom-third +0.17% (raw spread +0.35pp). But the **alpha spread is −1.54pp** (top +0.44pp vs bottom +1.98pp, n=6,074). The lowest-scored names *beat* SPY while the highest-scored barely track it. The positive raw spread is pure market beta; beta-stripped, the score sorts in the *wrong direction*. This inversion has now persisted across seven consecutive cycles (−2.03 → −2.42 → −2.22 → −1.7 → −1.53 → −1.54pp). It is the single most important, most durable finding in the dataset. The sign is unchanged — do NOT treat any prior narrowing as a trend toward predictiveness; the spread reverted flat this cycle.

**Restraint vs. selection.** BUY volume is 1,079 of 7,309 (14.8% cumulative). Selection quality did NOT improve on any durable basis — alpha is still negative and the alpha spread still inverted. We remain beta-tracking. This is a beta problem, not a volume problem.

**AVOID Recall — the unsolved weakness.** Of 415 names that fell >15%, the system flagged only **84 as AVOID (recall 20.2%)** — 331 were missed (42 rated BUY, 289 HOLD). Of 205 names that fell >20%, only **55 flagged (recall 26.8%)**, 150 missed. Issued-AVOID precision says NOTHING about the ~80% of blow-ups we failed to flag. Recall is flat vs last cycle (20.8% → 20.2%, within noise). This remains a distinct, unresolved failure.

**Survivorship Bias.** Of 6,102 snapshots old enough for follow-up, 27 (0.4%) lack one. The gap is non-uniform: **AVOID 1.4% (12/874) vs BUY 0.2% (2/1,034)** — a 7× ratio. The worst AVOID outcomes (delistings/takeouts) are disproportionately absent, so the measured AVOID alpha (−0.20pp) **understates** true AVOID signal. Caveat AVOID conclusions accordingly — but this does not rescue the recall problem, which measures failures to flag, not the quality of flags issued.

## Identified Biases

1. **Score is anti-predictive on alpha (CRITICAL).** Bottom-third beats SPY by 1.98pp; top-third only +0.44pp. High-conviction BUYs continue to crater: DOCS (7.03 → −27.1%), BMI (7.06 → −20.6%), TRMB (6.8 → −19.7%), APO (7.55 → −16.9%), CALX (6.39 → −17.8%). Scores >7.5 are not protective.

2. **BUY adds no selection alpha (CRITICAL).** −0.78pp average alpha, 38.7% beat-SPY rate — worse than the HOLD bucket's +0.37pp.

3. **AVOID Recall ~20–27% (HIGH, unsolved).** The system misses roughly four of every five large declines, parking them in HOLD (289 of 331 missed >−15% names). Worst calls confirm: HON (5.3 HOLD → −49.1%), ADMA (5.98 HOLD → −40.4%), SNEX (6.5 HOLD → −39.9%).

4. **Sector alpha (judge on alpha, not raw):**
   - Consumer Discretionary BUY: −2.03% raw, **−3.05pp alpha** (32) — worst large sector. Prohibition holds.
   - Energy BUY: −1.52% raw, **−2.82pp alpha** (166, largest cumulative alpha sink). Industry split confirms breadth: Oil & Gas E&P −3.84pp (84), Equip & Services −3.66pp (13), Midstream −2.17pp (13), Storage & Transport −1.66pp (20). Structural, not idiosyncratic. Refining & Marketing (−0.02pp, 19) is the lone near-neutral pocket.
   - Materials: **−2.82pp** (16). Industrials: **−1.47pp** (117). Financials: **−1.26pp** (317 — 29% of all BUYs). Within Financials, Investment Banking & Brokerage (−3.75pp, 18) and Regional Banks (−2.75pp, 53) are worst; Consumer Finance (+0.84pp, 11) is the lone near-neutral.
   - Health Care BUY: +1.23% raw but **+0.27pp alpha** (123) — marginal, not a validated sector-level source. Heterogeneous: Health Care Services +2.94pp (11), Health Care Facilities +2.13pp (10), Biotechnology +1.86pp (35), Pharmaceuticals +0.41pp (26) positive; Health Care Equipment (−1.07pp, 23) drags. Treat HC as neutral-to-slightly-positive at sector level; the real signal is industry-specific and thin.
   - Communication Services: −0.16pp alpha (55) — neutral. Interactive Media & Services −1.52pp (28) drags within it.
   - **Information Technology: +1.91pp alpha** (158) — the only sector with a real positive edge, but heterogeneous. Driven by Systems Software (+6.45pp, 21), Tech Hardware/Storage (+6.14pp, 13), Semiconductors (+3.38pp, 57), Payment Processing (+2.27pp, 26). Dragged by Application Software (−0.14pp, 31), Semiconductor Materials & Equipment (−0.32pp, 16), and Electronic Equipment (−2.23pp, 12). Do NOT treat "IT" wholesale as the edge.

## Lessons for Future Analysis

1. **Stop crediting raw BUY return as skill.** Until alpha turns positive at adequate n across ≥2 cycles, treat the BUY book as beta-tracking. The fix is selection quality, not volume.
2. **Concentrate BUYs in the positive-alpha industries, not heterogeneous sectors.** Target Semiconductors (+3.38pp, n=57), Systems Software (+6.45pp, n=21), Tech Hardware/Storage (+6.14pp, n=13), Payment Processing (+2.27pp, n=26); Biotechnology (+1.86pp, n=35) and Health Care Services (+2.94pp, n=11) are suggestive but thin. Explicitly avoid Application Software, Semiconductor Materials & Equipment, and Electronic Equipment within IT. Because the overall score is anti-predictive, this directive rests on industry/sector alpha evidence — NOT on trusting the composite score. Regime caveat: single bull-led window; alpha relationships can flip out-of-sample.
3. **Investigate the inverted alpha spread directly.** "Cheap" bottom-third names outperform, so the valuation dimension appears mis-signed; growth_prospects appears to be the only positively-discriminating dimension. Down-weight valuation in the composite — implement as an engineering change with a documented data shift, not a threshold flip.
4. **AVOID recall is the priority project.** Build screening to catch the 289 HOLD-rated names that fell >15% — momentum breakdown, premium valuation post-run-up, insider-selling clusters. Going-concern language is high-precision/low-recall and not a general tail detector.
5. **MAINTAIN existing thresholds** (see Stability Protocol).

## Areas of Strength

1. **Positive-alpha industries within IT (+1.91pp at sector level, 158 calls)** — the only beta-stripped edge, concentrated in Semiconductors, Systems Software, Tech Hardware, and Payment Processing. Concentrate at industry granularity. Regime caveat: single window; may not persist.
2. **HOLD is the best-selecting bucket (+0.37pp alpha, 50.8% beat rate)** — an honest, positive-alpha default that out-picks the active BUY book.
3. **Downside containment:** worst BUY −27.1% vs worst HOLD −49.1% — issued BUYs avoid the deepest holes (risk management, not selection).
4. **AVOID precision (understated by survivorship):** issued AVOIDs average slightly-negative alpha; KLAR (−26.9%), CPB (−16.2%) validate. The 1.4% AVOID follow-up gap means true precision is somewhat better than measured. (Precision only — recall remains poor.)

## Calibration Changelog

| Date | Entry |
|---|---|
| 2026-06-17 | n=4,806. ALPHA REFRAME — prior "recovery" was beta. BUY −1.24pp; score anti-predictive (alpha spread −2.03pp); AVOID recall 24.4%; HC/Comms demoted to neutral. All thresholds HELD. |
| 2026-06-24 | n=5,097. Findings confirmed within noise. BUY alpha −1.21pp; alpha spread −2.42pp; AVOID recall 23.3%. All thresholds HELD (last change 7d prior). |
| 2026-07-01 | n=5,900. Findings persist. BUY alpha −0.95pp; HOLD only positive-alpha bucket (+0.46pp); score anti-predictive 4th cycle (−2.22pp); AVOID recall 24.7%. All thresholds HELD for stability (last change 20d prior). |
| 2026-07-20 | n=6,174. Findings persist; NO sign flips. BUY alpha −0.92pp; HOLD only positive-alpha bucket (+0.42pp); score anti-predictive 5th cycle (−1.7pp); AVOID recall 22.0%; AVOID survivorship gap 1.4% (7× BUY). IT edge carried by Systems Software/Tech Hardware/Semis/Payments. STABILITY: last policy change 39 days prior (≥30d), but no data-backed shift — ALL thresholds HELD by CHOICE. |
| 2026-07-27 | UPDATE. n=6,387 (+213). Findings persist; NO sign flips. BUY alpha −0.89pp, 38.1% beat-SPY — no edge. HOLD only positive-alpha bucket (+0.36pp). Score anti-predictive 6th cycle (−1.53pp). AVOID recall 20.8%/26.8%. Survivorship AVOID gap 1.4% (7×). IT edge industry-specific. STABILITY: 46 days since last change (≥30d), but no qualifying data shift — ALL thresholds HELD by CHOICE. |
| **2026-08-03** | **UPDATE. n=7,309 (+922 — largest single-cycle sample growth). Findings persist; NO sign flips. (1) BUY alpha −0.78pp (was −0.89pp), 38.7% beat-SPY — still NO selection edge; raw +0.33% is beta. The magnitude uptick did NOT reverse the sign even with +922 names, so it is drift, not an emerging edge. (2) HOLD remains the only positive-alpha bucket (+0.37pp, 50.8% beat) — passive default still out-selects the active BUY book. (3) Score ANTI-PREDICTIVE for a 7th consecutive cycle: alpha spread −1.54pp (top +0.44pp, bottom +1.98pp, n=6,074) — reverted flat vs prior −1.53pp; prior narrowing was NOT a trend. This is the most durable finding in the dataset. (4) AVOID RECALL 20.2% (>−15%) / 26.8% (>−20%) — still missing ~80% of blow-ups, 289 of 331 into HOLD. Flat vs last cycle, within noise. (5) Survivorship: AVOID gap 1.4% (12/874) vs BUY 0.2% (2/1,034), 7× ratio — AVOID alpha (−0.20pp) understates true AVOID signal; caveat AVOID conclusions. (6) Industry detail: IT edge (+1.91pp) carried by Systems Software (+6.45pp), Tech Hardware (+6.14pp), Semiconductors (+3.38pp), Payment Processing (+2.27pp); Application Software (−0.14pp), Semi Materials & Equipment (−0.32pp), and Electronic Equipment (−2.23pp) drag. HC marginally positive at sector (+0.27pp); Biotech (+1.86pp)/HC Services (+2.94pp) positive but thin. Energy confirmed worst structural alpha sink across all sub-industries. STABILITY: last policy change was 2026-06-11 (53 days ago, ≥30d — a reversal is permissible on the clock). HOWEVER, no data-backed distribution shift warrants one: despite +922 names, no alpha sign flipped, the score inversion held for a 7th cycle, and all movements (BUY alpha −0.89→−0.78pp; recall 20.8→20.2pp; alpha spread −1.53→−1.54pp) are same-direction noise or flat. Relaxing the BUY floor or raising volume on a within-noise BUY-alpha uptick would be re-tuning on noise. Therefore ALL thresholds HELD by CHOICE (not clock constraint) — BUY floor 8.0/8.5, volume 8–10%, Financials cap 8%, AVOID negative-momentum gate, HOLD floor 70% unchanged. Open unsolved problems remain: (a) the inverted alpha spread and (b) AVOID recall.** |

## Stability Protocol Note

Last policy change: 2026-06-11 (53 days ago, **≥30d — the time gate no longer blocks a reversal**). This cycle I am HOLDING all thresholds by choice, not by constraint. The reason: there is no qualifying data-backed distribution shift. Sample grew +922 — a genuinely large increment — yet no alpha sign flipped at adequate n, the score inversion held for a 7th consecutive cycle, and every single-cycle movement is same-direction noise or flat (BUY alpha −0.89 → −0.78pp; recall 20.8 → 20.2pp; alpha spread −1.53 → −1.54pp). Critically, the +922 names are the strongest available test of the BUY-alpha uptick, and they did NOT turn the sign positive — so the drift is not evidence of improving selection. Relaxing the BUY floor or raising volume now would be noise-fitting. **All thresholds and prohibitions are MAINTAINED.** This update changes *interpretation and observation* (7th-cycle confirmation of score inversion at materially larger n; AVOID survivorship gap steady at 7×) — it does not flip any score floor, volume target, or sector rule. Any future down-weighting of the valuation dimension must be an engineering change with a documented data shift, not a threshold flip.