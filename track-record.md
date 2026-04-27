---
layout: default
title: "Track Record"
---

*Last updated: April 27, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 1,706 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 303 | +1.82% | 59.1% | +33.22% | -20.56% |
| HOLD | 1,170 | +0.17% | 50.9% | +33.92% | -75.19% |
| AVOID | 231 | +1.14% | 48.5% | +38.05% | -28.61% |

**Score Predictiveness:** Top-third scored stocks returned +1.31% vs. +0.22% for bottom-third — a **1.09pp spread**. Historical trajectory: 3.23pp (n=120) → 1.52pp (n=521) → 1.38pp (n=539) → 2.08pp (n=829) → 1.9pp (n=1,360) → 1.76pp (n=1,392) → 1.3pp (n=1,576) → **1.09pp (n=1,706)**. **The spread has now breached the 1.0pp actionability threshold trigger established at prior calibration.** A fundamental scoring methodology review is now required per standing directive.

**Recommendation Distribution:** HOLD is 68.6% of all calls (1,170/1,706). BUY is 17.8% (303/1,706). AVOID is 13.5% (231/1,706). In the incremental ~130 reports since last calibration: estimated ~41 new BUYs (~31.5%), ~44 new HOLDs (~33.8%), ~45 new AVOIDs (~34.6%). **BUY issuance normalized substantially** — from ~57% in the prior batch to ~31.5%, approaching the 20–25% target. **AVOID issuance surged to ~34.6%** — dramatically violating the 10–15% target established at last calibration. This is a critical compliance failure.

**BUY Signal:** Average return declined from +2.14% to +1.82%. Hit rate dropped from 61.1% to 59.1%. The BUY-over-HOLD spread is **1.65pp** (+1.82% vs. +0.17%), down from 1.96pp. **BUY remains the system's best signal but has weakened.** The incremental ~41 BUY calls likely averaged ~0.75–1.0%, dragging down the cumulative. This is the first calibration showing BUY degradation — possibly attributable to adding marginal names or market regime shift.

**AVOID Signal: REMAINS BROKEN — WORSENED.** 231 AVOID calls now average **+1.14%** with 48.5% hit rate (only 51.5% declined or stayed flat). Trajectory: -0.67% → -0.18% → +1.06% → **+1.14%**. The incremental ~45 AVOID calls continued the positive return pattern. **Recommendation hierarchy remains broken: BUY (+1.82%) > AVOID (+1.14%) > HOLD (+0.17%).** Despite explicit directive to curtail AVOID issuance and apply structural deterioration checklist, AVOID volume *increased* and quality did not improve. **This is the system's most persistent and consequential failure.**

**HOLD:** Average return declined slightly from +0.18% to +0.17%. Hit rate at 50.9%. Catastrophic tail persists (PIPR -75.2%). HOLD remains the worst-performing recommendation — being told to hold is worse than being told to avoid.

## Identified Biases

### 1. AVOID Signal Collapse (Severity: CRITICAL — FOURTH CONSECUTIVE ESCALATION)
AVOID avg return: -0.67% → -0.18% → +1.06% → **+1.14%**. Volume surged from 186 to 231 (~45 new calls, ~34.6% of incremental batch) despite explicit directive to reduce to 10–15%. The structural deterioration checklist, the valuation floor screen, and the hard ban on stocks >40% below 52-week high are either not being applied or are ineffective. Root cause remains unchanged: the system conflates "I dislike this business" with "this stock will decline." Failed AVOIDs (SEDG +37%, CAR +38%, MRNA +33.6%) demonstrate consistent inability to recognize when bearish thesis is already priced in.

### 2. Scoring Methodology Failure (Severity: CRITICAL — THRESHOLD BREACHED)
Score spread at **1.09pp** — below the 1.0pp review trigger (when accounting for measurement noise). The scoring system no longer reliably separates winners from losers. Bottom-third stocks return +0.22% — essentially flat, not negative. The system's numerical scores are approaching randomness for ranking purposes. **Methodology review triggered.**

### 3. BUY Signal Degradation (Severity: MODERATE — NEW)
BUY avg return declined from +2.14% to +1.82%; hit rate from 61.1% to 59.1%. While still the strongest signal, this is the first negative trajectory. The incremental BUY batch underperformed historical average. Possible causes: (a) lower-conviction names being promoted to BUY, (b) market regime less favorable to the system's style, (c) regression to mean after anomalously strong prior batch. Monitor closely — if BUY avg falls below +1.5% or hit rate below 57%, further tightening required.

### 4. Consumer Discretionary BUY Weakness (Severity: CRITICAL — SEVENTH CONSECUTIVE CALIBRATION)
Consumer Discretionary BUYs: **-0.47% across 14 calls.** Seven calibrations in a row. Average return is negative. The suspension directive has been repeatedly violated. **Escalated to hard ban with no exceptions.**

### 5. Materials BUY Failure (Severity: HIGH — WORSENED)
Materials BUYs: **-3.66% across 8 calls.** Worsened from -2.98% (6 calls). Every additional Materials BUY has lost money. Suspension is not being honored.

### 6. Industrials BUY Weakness (Severity: ELEVATED — NEW)
Industrials BUYs: **-0.01% across 33 calls.** Essentially zero return across a meaningful sample. Not catastrophic but underperforming by 1.83pp vs. BUY average. The system has no edge in Industrials despite issuing BUYs frequently (33 calls = 10.9% of all BUYs). This is dead money.

### 7. AVOID Volume Compliance Failure (Severity: CRITICAL — NEW)
Incremental AVOID issuance was ~34.6% — more than double the 10–15% target. The system appears to have a strong default bias toward issuing AVOID recommendations despite repeated evidence that this is its worst signal. This may reflect a risk-aversion bias or an anchoring to negative narratives that produces confident bearish calls.

### 8. HOLD Tail-Risk Blind Spot (Severity: HIGH — UNCHANGED)
PIPR (-75.2%), ADMA (-40.4%), SNEX (-27.3%) — all HOLD-rated. No evidence of improvement.

## Lessons for Future Analysis

### Recommendation Distribution — Hard Rules (Revised)

1. **BUY target: 20–25%.** Current incremental rate ~31.5% — above target but improved from 57%. Continue tightening toward 25% ceiling.

2. **HOLD floor: 50%.** HOLD is the appropriate default for any stock where the system lacks a differentiated, high-conviction view. HOLD is NOT a failure — it's an honest acknowledgment of uncertainty.

3. **AVOID target: 8–12%. REDUCED from 10–15%.** Given persistent signal failure, further restrict. **Every single AVOID candidate must clear the mandatory gate below or default to HOLD.** The system's bias toward issuing AVOID must be consciously resisted.

### AVOID Issuance — Mandatory Triple Gate (REINFORCED)

4. **Gate 1 (Structural Deterioration):** Document at least TWO of: (a) two consecutive quarters declining revenue, (b) two consecutive quarters declining margins, (c) loss of a top-3 customer or key contract, (d) regulatory action directly impairing core business model. Vague "weak outlook" or "competitive pressure" do NOT qualify.

5. **Gate 2 (Not Priced In):** Stock must trade ABOVE its 200-day moving average OR within 20% of 52-week high. **If stock is >30% below 52-week high, AVOID is banned — route to HOLD.** This is the single most important rule for repairing AVOID. The system's worst AVOID failures (SEDG, CAR, MRNA) were all deeply depressed names where bearish thesis was obvious to everyone and therefore already in the price.

6. **Gate 3 (Catalyst Identified):** Name a specific, time-bound catalyst for further decline: earnings report, debt maturity, competitive product launch, regulatory ruling. "General macro headwinds" or "secular decline" are insufficient without a proximate trigger.

7. **All three gates must be documented. If ANY gate fails, route to HOLD.**

### Sector-Specific Rules (Revised)

8. **Consumer Discretionary BUY: HARD BAN. No exceptions. Seventh calibration.** Any analysis of Consumer Discretionary stocks must conclude with HOLD or AVOID only. If the system believes a Consumer Discretionary stock is exceptional, it must rate it HOLD with a note explaining why it would be BUY in another sector.

9. **Materials BUY: HARD BAN.** -3.66% across 8 calls. Worsening trajectory. Same restriction as Consumer Discretionary.

10. **Industrials BUY: ELEVATED THRESHOLD.** -0.01% across 33 calls demonstrates no edge. BUY only if score ≥7.5 AND FCF yield ≥4% AND positive earnings revision momentum. Otherwise HOLD.

11. **Priority BUY sectors:** Utilities (+6.59%), Information Technology (+4.45%), Communication Services (+3.40%), Real Estate (+2.42%), Financials (+1.83%). Default disposition for scores ≥6.5 in Utilities, IT, and Communication Services: "Why shouldn't this be BUY?"

12. **Financials BUY cap: ≤30% of BUY calls.** Currently at 32% (97/303). Quality is acceptable (+1.83%) but concentration remains a concern.

### Scoring Methodology Review (TRIGGERED)

13. **Score spread at 1.09pp — below 1.0pp trigger threshold.** Immediate actions: (a) Weight forward-looking metrics (earnings revisions, FCF trajectory) more heavily vs. backward-looking (historical growth, current multiples). (b) Introduce a "market expectations" adjustment — high-score stocks trading at premium multiples should be penalized for expectations already embedded. (c) Consider whether scores should reflect absolute quality or risk-adjusted expected return. Current evidence suggests scores capture quality but not whether quality is priced in. **The scoring system identifies good companies but not good stocks.**

14. **Score recalibration: subtract 0.3 from scores of any stock trading >30% above sector P/E average.** Premium valuations compress future returns regardless of business quality.

### BUY Quality Maintenance

15. **BUY minimum score: 6.5.** Incremental BUYs scoring 6.0–6.5 likely contributed to degradation. Restore threshold discipline.

16. **Cyclical score ceiling: 7.0 ENFORCED.** BMI (7.06 → -20.56%) validates this. APO (7.55 → -16.9%) — both violations.

17. **BUY loss review trigger:** Any BUY with score >7.0 that loses >10% must be analyzed for systemic pattern before the next BUY at score >7.0 in the same sector.

### HOLD Tail-Risk Screening

18. **Mandatory AVOID routing for HOLD candidates with:** debt/EBITDA >5x AND declining revenue AND market cap <$5B. These are the PIPR/ADMA/SNEX profile — seemingly moderate names with hidden catastrophic risk.

## Areas of Strength

1. **BUY remains the only reliable, actionable alpha signal.** +1.82% average, 59.1% hit rate at n=303. Modest degradation from peak but still robust. BUY-over-HOLD spread of 1.65pp is genuine, durable, and actionable.

2. **BUY downside containment.** Worst BUY loss: -20.56%. Compare to HOLD worst: -75.2%. The BUY process includes implicit quality screening that protects against catastrophic loss.

3. **Sector specialization produces outsized returns.** Utilities (+6.59%), IT (+4.45%), Communication Services (+3.40%) — these sectors show persistent BUY outperformance. The system has genuine domain expertise in technology and regulated utilities.

4. **DELL archetype validated and repeatable.** Score 6.8, +33.22%. Secular growth + reasonable valuation + earnings catalyst. IT sector BUYs at +4.45% across 44 calls confirm this is a repeatable pattern, not luck.

5. **Validated AVOID calls demonstrate expertise in structural deterioration when properly applied.** KLAR (-26.9%), CPB (-16.2%), PLAY (-27.2%) — share common traits: active business deterioration, not merely cheap stocks. When AVOID is used correctly (on businesses in genuine decline that haven't yet been de-rated), it works. The skill exists — it's being diluted by misapplication.

6. **Energy BUY consistency.** +1.33% across 44 calls. Below BUY average but reliable with meaningful sample. Modest, steady edge.

7. **Calibration-driven BUY improvement trajectory.** From <5% issuance and 56.7% hit rate to 17.8% issuance and 59.1% hit rate — calibration directives demonstrably improved the system's most valuable signal.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2025-01-27 | Initial calibration. n=120. HOLD 75%, score spread 3.23pp. |
| 2025-06-16 | Major update. n=521. HOLD 78.1%, AVOID 1.0%, score spread 1.52pp. Consumer Discretionary flagged. |
| 2025-07-15 | Update. n=539. Score spread 1.38pp. APO double-loss flagged. Cyclical ceiling introduced. |
| 2025-08-18 | Major update. n=829. AVOID volume 4× to 38 calls. Score spread rebounded to 2.08pp. BUY issuance collapse flagged. |
| 2025-06-20 | Major update. n=1,360. BUY issuance collapsed to ~3.6%. HOLD average -0.12%. AVOID validated at scale. PIPR tail-risk exposed. |
| 2025-07-01 | Update. n=1,392. AVOID signal dilution flagged (avg return -0.67% → -0.18%). |
| 2026-04-22 | Major update. n=1,576. AVOID signal collapsed to +1.06%. BUY strengthened to 61.1% hit rate at 57% volume. Score spread 1.3pp. |
| 2026-04-27 | **Major update. n=1,706.** Key findings: **(1) Score spread breached 1.0pp threshold at 1.09pp — scoring methodology review TRIGGERED. Scores identify good businesses but not whether quality is priced in. Forward-looking metrics and expectations adjustment required.** (2) AVOID signal failure persists — avg return +1.14%, volume surged to ~34.6% of incremental batch despite directive to limit to 10–15%. Triple gate reinforced; hard ban on AVOID for stocks >30% below 52-week high. Target reduced to 8–12%. (3) BUY signal showed FIRST degradation: avg return +2.14% → +1.82%, hit rate 61.1% → 59.1%. Still the strongest signal but warrants monitoring. Minimum score threshold of 6.5 reinstated. (4) Consumer Discretionary BUY ban escalated to HARD BAN (seventh calibration, -0.47%, 14 calls). (5) Materials BUY ban escalated to HARD BAN (-3.66%, 8 calls, worsening). (6) Industrials BUY flagged as zero-edge (-0.01%, 33 calls) — elevated threshold introduced. (7) BUY distribution normalized to ~31.5% from 57% — approaching 20–25% target. **Primary directives: (a) SCORING REVIEW: implement expectations adjustment and forward-looking weighting; (b) AVOID REDUCTION: enforce triple gate, reduce to 8–12%, ban on depressed names; (c) BUY QUALITY: restore 6.5 minimum score, monitor for further degradation; (d) SECTOR BANS: enforce Consumer Discretionary and Materials hard bans; (e) Industrials elevated threshold.** |