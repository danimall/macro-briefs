---
layout: default
title: "Track Record"
---

*Last updated: May 5, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 1,944 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 363 | +1.38% | 56.5% | +33.22% | -20.56% |
| HOLD | 1,276 | +0.15% | 50.5% | +33.92% | -75.19% |
| AVOID | 303 | +0.27% | 45.5% | +38.05% | -31.77% |

**Score Predictiveness:** Top-third scored stocks returned +1.19% vs. -0.08% for bottom-third — a **1.28pp spread**. Historical trajectory: 3.23pp → 1.52pp → 1.38pp → 2.08pp → 1.9pp → 1.76pp → 1.3pp → 1.09pp → **1.28pp (n=1,944)**. Modest rebound from prior low of 1.09pp, now above the 1.0pp actionability threshold. Scoring methodology review remains warranted but crisis is partially abated.

**Recommendation Distribution:** HOLD is 65.6% of all calls (1,276/1,944). BUY is 18.7% (363/1,944). AVOID is 15.6% (303/1,944). In the incremental ~238 reports since last calibration: estimated ~60 new BUYs (~25.2%), ~106 new HOLDs (~44.5%), ~72 new AVOIDs (~30.3%). **BUY issuance hit the 25% target ceiling.** HOLD improved substantially toward the 50% floor. **AVOID issuance remains excessive at ~30.3%** — triple the 8–12% target. Fifth consecutive compliance failure.

**BUY Signal: CONTINUED DEGRADATION.** Average return declined from +1.82% to +1.38%; hit rate dropped from 59.1% to 56.5%. Both metrics breached the monitoring thresholds set at prior calibration (1.5% avg, 57% hit rate). The incremental ~60 BUY calls averaged approximately +0.05–0.50%, severely diluting the cumulative. **BUY remains the system's best signal but is now at its weakest point in calibration history.** The BUY-over-HOLD spread narrowed to **1.23pp** (from 1.65pp). Urgent quality tightening required.

**AVOID Signal: PARTIAL RECOVERY.** Average return dropped from +1.14% to +0.27%; hit rate improved to 45.5% (54.5% of AVOID calls declined). Trajectory: -0.67% → -0.18% → +1.06% → +1.14% → **+0.27%**. The incremental ~72 AVOID calls averaged approximately -1.0% to -1.5%, indicating the triple gate may be partially working. Still not fully functional — avg return should be negative — but directionally improved. **Recommendation hierarchy partially repaired: BUY (+1.38%) > AVOID (+0.27%) > HOLD (+0.15%).** The gap between AVOID and HOLD is now minimal, meaning AVOID is approaching "slightly worse than HOLD" which is at least directionally correct.

**HOLD:** Average return at +0.15%, hit rate 50.5%. Catastrophic tail persists (PIPR -75.2%). HOLD distribution improved to 44.5% of incremental batch — approaching the 50% floor target.

## Identified Biases

### 1. BUY Signal Degradation (Severity: CRITICAL — ESCALATED FROM MODERATE)
BUY avg return trajectory: +2.14% → +1.82% → **+1.38%**. Hit rate: 61.1% → 59.1% → **56.5%**. Both metrics breached warning thresholds. The system is issuing BUY calls on names with insufficient margin of safety or where positive thesis is already consensus. Notable failures: BMI (7.06 → -20.6%), APO (7.55 → -16.9%), NFLX (6.6 → -14.2%), CALX (6.39 → -17.8%). Common thread: high-conviction calls on stocks where growth expectations were already elevated. **The BUY signal is being diluted by insufficient differentiation between "good company" and "good risk/reward."**

### 2. AVOID Volume Compliance (Severity: HIGH — FIFTH CONSECUTIVE FAILURE, PARTIALLY IMPROVED)
Incremental AVOID issuance ~30.3% — still triple the 8–12% target but down from 34.6%. The system continues to over-issue AVOID despite evidence of limited edge. However, AVOID quality improved meaningfully (avg return dropping from +1.14% to +0.27%), suggesting the triple gate is being partially applied. **Volume remains the primary problem; quality is improving.**

### 3. Consumer Discretionary BUY (Severity: CRITICAL — EIGHTH CONSECUTIVE CALIBRATION)
Consumer Discretionary BUYs: **-0.88% across 15 calls.** One additional BUY was issued despite HARD BAN directive. Performance worsened from -0.47% to -0.88%. The ban is being violated.

### 4. Materials BUY (Severity: CRITICAL — WORSENED)
Materials BUYs: **-3.66% across 8 calls.** Unchanged count suggests ban is being honored. Performance remains the worst of any sector.

### 5. Industrials BUY (Severity: HIGH — WORSENED)
Industrials BUYs: **-0.19% across 46 calls.** Expanded from 33 to 46 calls despite elevated threshold directive. 13 new Industrials BUYs were issued — none should have been without meeting the ≥7.5 score AND ≥4% FCF yield gates. Average return worsened from -0.01% to -0.19%. **The system has no edge in Industrials and continues to allocate BUY calls there.**

### 6. Scoring Identifies Quality, Not Opportunity (Severity: HIGH — STRUCTURAL)
Score spread rebounded to 1.28pp from 1.09pp — modestly reassuring — but bottom-third stocks now average -0.08% (barely negative). The scoring system remains better at identifying good businesses than mispriced securities. High-score BUY failures (APO 7.55, BMI 7.06) confirm that quality scores correlate with business excellence but not with forward returns when expectations are already embedded in price.

### 7. HOLD Tail-Risk Blind Spot (Severity: HIGH — UNCHANGED)
PIPR (-75.2%), ADMA (-40.4%) persist as the worst outcomes. Both were HOLD-rated. No new catastrophic HOLD failures in this batch suggests screening may be improving, but legacy cases remain.

### 8. AVOID on Depressed Names (Severity: MODERATE — IMPROVING)
SEDG (+37%), CAR (+38%), MRNA (+33.6%) remain the worst AVOID failures — all deeply depressed names where bearish thesis was priced in. Newer AVOID calls appear less prone to this error (improved avg return), suggesting the "ban on stocks >30% below 52-week high" is partially functioning. CHTR (-31.8%) and SMCI (-28.6%) show AVOID can work on depressed names when structural deterioration is genuine — distinguishing between these cases remains the key skill.

## Lessons for Future Analysis

### BUY Quality Crisis — Immediate Tightening Required

1. **BUY minimum score: 7.0.** Elevated from 6.5. The 56.5% hit rate is unacceptable. Higher threshold will reduce volume but restore signal quality. Scores 6.5–6.9 should default to HOLD with bullish lean noted.

2. **BUY valuation gate (NEW — MANDATORY):** No BUY recommendation for stocks trading >25x forward earnings UNLESS revenue growth >20% AND earnings revision momentum is positive over trailing 90 days. NFLX (6.6 → -14.2%) at premium multiples demonstrates this gap.

3. **BUY "expectations gap" test (NEW — MANDATORY):** Before issuing BUY, explicitly answer: "What does this stock need to deliver to justify current price, and what incremental positive surprise is my thesis?" If the thesis is consensus (e.g., "AI tailwind," "market leader"), it is NOT a BUY — it is a HOLD.

4. **BUY target: 15–20%.** Reduced from 20–25%. Current quality crisis demands volume restriction. Fewer, higher-conviction BUYs.

5. **BUY loss threshold:** If incremental BUY avg return falls below +1.0% at next calibration, BUY minimum score escalates to 7.5.

### Recommendation Distribution — Revised Hard Rules

6. **BUY target: 15–20%.** Down from 20–25%.
7. **HOLD floor: 55%.** Up from 50%. HOLD is the honest default.
8. **AVOID target: 8–12%.** Unchanged. Volume compliance remains the primary AVOID issue.

### AVOID Issuance — Triple Gate Reinforced with Volume Cap

9. **Hard cap: maximum 3 AVOID calls per 20 reports.** This mechanically enforces the 15% ceiling. If the system has already issued 3 AVOIDs in a batch, subsequent bearish candidates MUST be routed to HOLD regardless of gate passage.

10. **Gates 1–3 unchanged and MANDATORY:** (1) Structural deterioration with two documented criteria, (2) Stock above 200-DMA or within 20% of 52-week high, (3) Specific time-bound catalyst. All three required.

11. **AVOID success recognition:** KLAR (-26.9%), CPB (-16.2%), TSLA (-3.0%) validate that AVOID works on stocks with active deterioration NOT yet fully priced in. The differentiator: these stocks were NOT already washed out.

### Sector-Specific Rules (Revised)

12. **Consumer Discretionary BUY: ABSOLUTE HARD BAN. Eighth calibration. -0.88%, 15 calls.** If the system issues a Consumer Discretionary BUY, it is a calibration violation regardless of conviction. No exceptions, no "exceptional case" override.

13. **Materials BUY: ABSOLUTE HARD BAN.** -3.66%, 8 calls. Worst sector by far.

14. **Industrials BUY: EFFECTIVE BAN — Score ≥7.5 AND FCF yield ≥5% AND positive earnings revisions.** Elevated from ≥7.5/≥4%. -0.19% across 46 calls is sufficient evidence of no edge. Making the gate nearly impossible to clear is intentional.

15. **Priority BUY sectors:** Information Technology (+3.24%, 53 calls), Communication Services (+2.88%, 22 calls), Utilities (+4.0%, 10 calls), Energy (+1.84%, 49 calls). These sectors show durable BUY alpha at meaningful sample sizes. IT and Energy have the most robust sample-size-adjusted performance.

16. **Financials BUY monitoring:** +1.31% across 114 calls. Below BUY average (+1.38%). Concentration risk: Financials = 31.4% of all BUY calls. **Cap at 25% of BUY calls going forward.** The system's edge in Financials is real but smaller than it appears — likely reflecting beta sensitivity to rate environment rather than differentiated insight.

### Scoring Methodology Adjustments

17. **Score spread recovered to 1.28pp — methodology review remains active but not emergency.** Continue implementing: (a) forward-looking metric weighting (earnings revisions, FCF trajectory), (b) expectations adjustment (penalize stocks where quality is consensus), (c) differentiate "good business" scores from "good investment" scores.

18. **Score-to-recommendation mapping (NEW):** Score ≥7.0 in priority sectors → default BUY disposition (must argue against). Score 6.0–6.9 → default HOLD. Score <5.5 → evaluate for AVOID (must pass triple gate). Score 5.5–6.0 → HOLD with no directional lean.

### HOLD Tail-Risk Screening (Unchanged)

19. **Mandatory AVOID routing for HOLD candidates with:** debt/EBITDA >5x AND declining revenue AND market cap <$5B.

## Areas of Strength

1. **BUY remains the only consistently positive alpha signal.** Despite degradation, +1.38% with 56.5% hit rate at n=363 is statistically meaningful. BUY-over-HOLD spread of 1.23pp persists across nearly 400 calls. This is real skill, not noise.

2. **BUY downside containment remains excellent.** Worst BUY: -20.56%. Compare to HOLD worst: -75.2%, AVOID worst: -31.8%. The BUY process implicitly screens out catastrophic risk.

3. **Information Technology BUY dominance.** +3.24% across 53 calls. The system's strongest, most consistent sector edge. DELL (+33.2%) exemplifies the archetype: secular growth, reasonable valuation, earnings catalyst. IT should be the primary hunting ground for BUY candidates.

4. **AVOID signal quality improving.** Avg return dropped from +1.14% to +0.27%. The triple gate appears to be partially filtering out "cheap and hated" stocks that subsequently rebound. Validated AVOIDs (KLAR -26.9%, CPB -16.2%) confirm real skill when properly applied to genuine deterioration.

5. **Score predictiveness partially recovered.** 1.28pp spread (up from 1.09pp) suggests recent scoring adjustments are helping. Bottom-third stocks now average -0.08% (negative, as desired).

6. **Distribution normalization progressing.** HOLD at 44.5% of incremental batch (up from implied ~33.8%), BUY at 25.2% (within target). Only AVOID volume remains non-compliant.

7. **Energy BUY consistency.** +1.84% across 49 calls. Reliable, repeatable edge with meaningful sample.

8. **Calibration-driven improvement is real.** AVOID quality improved dramatically this cycle. BUY distribution hit target. HOLD volume recovering. The system responds to calibration — the challenge is speed and compliance.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2025-01-27 | Initial calibration. n=120. HOLD 75%, score spread 3.23pp. |
| 2025-06-16 | Major update. n=521. HOLD 78.1%, AVOID 1.0%, score spread 1.52pp. Consumer Discretionary flagged. |
| 2025-07-15 | Update. n=539. Score spread 1.38pp. APO double-loss flagged. Cyclical ceiling introduced. |
| 2025-08-18 | Major update. n=829. AVOID volume 4× to 38 calls. Score spread rebounded to 2.08pp. |
| 2025-06-20 | Major update. n=1,360. BUY issuance collapsed to ~3.6%. HOLD average -0.12%. PIPR tail-risk exposed. |
| 2025-07-01 | Update. n=1,392. AVOID signal dilution flagged (avg return -0.67% → -0.18%). |
| 2026-04-22 | Major update. n=1,576. AVOID signal collapsed to +1.06%. BUY strengthened to 61.1% hit rate. Score spread 1.3pp. |
| 2026-04-27 | Major update. n=1,706. Score spread breached 1.0pp at 1.09pp. AVOID +1.14%. BUY first degradation to +1.82%/59.1%. |
| 2026-05-05 | **Major update. n=1,944.** Key findings: **(1) BUY signal degradation ESCALATED to critical: avg return +1.82% → +1.38%, hit rate 59.1% → 56.5%. Both breached warning thresholds. Minimum score elevated to 7.0; mandatory valuation gate and "expectations gap" test introduced; volume target reduced to 15–20%.** (2) AVOID quality IMPROVED: avg return +1.14% → +0.27%. Triple gate showing partial effect. Volume still non-compliant at ~30.3% (target 8–12%) — hard cap of 3 per 20 reports introduced. (3) Score spread recovered to 1.28pp from 1.09pp — no longer in crisis but methodology review continues. (4) Consumer Discretionary BUY ban violated again (15th call issued); -0.88%. Eighth consecutive calibration. ABSOLUTE BAN reinforced. (5) Industrials BUY expanded to 46 calls at -0.19% despite elevated threshold — gate tightened to effective ban. (6) Financials BUY concentration at 31.4% of all BUYs with below-average returns (+1.31%) — cap at 25% introduced. (7) HOLD distribution improved to ~44.5% incremental. **Primary directives: (a) BUY QUALITY CRISIS: score ≥7.0 minimum, expectations gap test, valuation gate, 15–20% volume target; (b) AVOID VOLUME: hard cap 3/20 reports; (c) SECTOR BANS: Consumer Discretionary and Materials absolute, Industrials effective; (d) Financials cap at 25% of BUYs; (e) Continue scoring methodology evolution toward "mispricing detection" vs. "quality identification."** |