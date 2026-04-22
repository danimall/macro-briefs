---
layout: default
title: "Track Record"
---

*Last updated: April 22, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 1,576 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 262 | +2.14% | 61.1% | +33.22% | -20.56% |
| HOLD | 1,126 | +0.18% | 51.1% | +33.92% | -75.19% |
| AVOID | 186 | +1.06% | 47.3% | +38.05% | -28.61% |

**Score Predictiveness:** Top-third scored stocks returned +1.42% vs. +0.12% for bottom-third — a **1.3pp spread**. Historical trajectory: 3.23pp (n=120) → 1.52pp (n=521) → 1.38pp (n=539) → 2.08pp (n=829) → 1.9pp (n=1,360) → 1.76pp (n=1,392) → **1.3pp (n=1,576)**. The spread has compressed meaningfully. Bottom-third average improved from -0.48% to +0.12% — bottom-third stocks are no longer losing money on average. **The scoring system's predictive edge is eroding and approaching actionability threshold.** Revised estimate of true spread: **1.2–1.5pp.** If the next calibration shows spread below 1.0pp, a fundamental scoring methodology review is required.

**Recommendation Distribution:** HOLD is 71.4% of all calls (1,126/1,576). BUY is 16.6% (262/1,576). AVOID is 11.8% (186/1,576). In the incremental ~184 reports since last calibration: estimated ~105 new BUYs (~57%), ~49 new HOLDs (~27%), ~30 new AVOIDs (~16%). **BUY issuance surged dramatically** — the system overcorrected from chronic BUY underissuance to massive BUY overissuance. The 20–25% target was blown through to ~57%. Meanwhile, AVOID overcorrection from the prior batch was corrected back to ~16%, which is within the 15–25% target range.

**BUY Signal:** Average return improved to +2.14% (from +2.04% at n=1,392). Hit rate jumped to 61.1% (from 56.7%). The BUY-over-HOLD spread is **1.96pp** (+2.14% vs. +0.18%). **The BUY signal strengthened materially despite massively increased volume.** This is the most important finding of this calibration: issuing more BUYs did not degrade BUY quality. Hit rate improved by 4.4pp and average return improved by 0.10pp. The prior hesitancy to issue BUYs was demonstrably suboptimal. However, the worst BUY loss widened from -16.85% to -20.56% (BMI), indicating the expanded BUY universe includes slightly more volatile names. BUY asymmetry remains strongly favorable.

**AVOID Signal: BROKEN.** 186 AVOID calls now have an average return of **+1.06%** with only 47.3% hit rate (i.e., only **52.7% of AVOID calls declined or stayed flat**). This is a catastrophic deterioration from -0.67% (n=142) → -0.18% (n=156) → **+1.06% (n=186)**. AVOID stocks are now *gaining* money on average — nearly as much as BUY stocks. **The recommendation hierarchy is no longer monotonic**: BUY (+2.14%) > AVOID (+1.06%) > HOLD (+0.18%). AVOID has leapfrogged HOLD. The AVOID signal is actively misleading. This is the system's most critical failure.

**HOLD Improved.** HOLD average return rose from -0.07% to +0.18%. Hit rate improved from 49.8% to 51.1%. Modest improvement, but HOLD is now the worst-performing recommendation category. The catastrophic tail remains (PIPR -75.2%).

## Identified Biases

### 1. AVOID Signal Collapse (Severity: CRITICAL — NEW ESCALATION)
AVOID average return has gone from -0.67% → -0.18% → **+1.06%** across three calibrations. The signal is now directionally wrong — AVOID stocks outperform HOLD stocks. The incremental ~30 AVOID calls likely had a strongly positive average return to drag the cumulative from -0.18% to +1.06%. Root causes: (a) issuing AVOID on beaten-down names at depressed valuations (contrarian rebound problem); (b) issuing AVOID on volatility rather than structural deterioration; (c) conflating "I don't like this business" with "this stock will decline." The validated AVOIDs (KLAR -26.9%, CPB -16.2%, SMCI -28.6%, PLAY -27.2%) share a common trait: active business deterioration with no catalyst for reversal. The failed AVOIDs (SEDG +37.0%, CAR +38.0%, MRNA +33.6%) share a trait: deeply depressed valuations where bad news was priced in. **The system cannot distinguish between "bad business declining" and "bad business already priced for decline."** Until this is fixed, AVOID calls should be issued with extreme restraint.

### 2. BUY Overissuance Overcorrection (Severity: MODERATE — NEW)
The incremental batch was ~57% BUY — far above the 20–25% target. While BUY quality held up remarkably well, this level of issuance is unsustainable and risks eventual degradation. The system swung from chronic BUY underissuance (<5%) to extreme overissuance (>50%). **The target remains 20–25%.** The good news: this batch proves the system has substantial headroom to issue BUYs without degrading quality. The BUY threshold was previously set too conservatively.

### 3. Consumer Discretionary BUY Weakness (Severity: HIGH — Worsened)
Consumer Discretionary BUYs: **-0.47% across 14 calls.** Sixth consecutive calibration flagging this. The suspension has been repeatedly violated. Average return remains negative and is the second-worst sector (behind Materials). **This directive is being ignored. Mandatory compliance required.**

### 4. Materials BUY Failure (Severity: ELEVATED — NEW)
Materials BUYs: **-2.98% across 6 calls.** Worst-performing sector for BUY calls. Small sample but consistent losses. Materials BUYs should be suspended pending further data, with the same reinstatement criteria as Consumer Discretionary.

### 5. Financials Concentration and Underperformance (Severity: MODERATE — Worsened)
Financials represent **35.1% of BUY calls** (92/262). Average return is +2.05% — essentially at the BUY average now (+2.14%), which is a meaningful improvement from +0.97%. The concentration concern remains, but the quality concern has largely resolved. Maintain the 25% cap to manage concentration risk, but the underperformance bias has been corrected.

### 6. Score Spread Erosion (Severity: HIGH — NEW ESCALATION)
Score spread compressed from 1.76pp to 1.3pp. Bottom-third scores now return +0.12% on average — essentially flat, not negative. The scoring system's ability to identify losers has meaningfully degraded. If spread falls below 1.0pp at next calibration, the scoring methodology requires fundamental review.

### 7. HOLD Tail-Risk Blind Spot (Severity: HIGH — Unchanged)
PIPR (-75.2%), ADMA (-40.4%), SNEX (-27.3%) — all HOLD-rated. No evidence of tail-risk screening implementation. The worst HOLD loss exceeds the worst AVOID and worst BUY losses combined.

### 8. BUY Downside Expansion (Severity: MODERATE — NEW)
Worst BUY loss widened from -16.85% to -20.56% (BMI at score 7.06). BMI is an industrial/materials-adjacent name. The expanded BUY volume introduced slightly more downside risk. APO (-16.9%) remains the second-worst. Both are cyclical names with elevated scores. The cyclical ceiling of 7.0 was violated with BMI (score 7.06).

## Lessons for Future Analysis

### Recommendation Distribution — Hard Rules (Revised)

1. **BUY target: 20–25%.** Floor of 15% remains. **Ceiling of 30% introduced.** The ~57% BUY rate in the last batch is overcorrection. BUY quality held up, which validates that the prior threshold was too conservative, but >30% risks eventual quality degradation.

2. **HOLD ceiling: 60% absolute maximum.** Incremental batch achieved ~27% — excellent. Sustain HOLD compression.

3. **AVOID target: 10–15%. Reduced from 15–25%.** AVOID is the system's worst-performing signal. Until the AVOID signal is repaired, issue fewer AVOIDs and only for clear structural deterioration. Every marginal AVOID should default to HOLD. **Quality over quantity is paramount.**

### AVOID Repair Protocol (CRITICAL — NEW)

4. **AVOID issuance requires mandatory structural deterioration checklist.** Before issuing AVOID, document ALL of the following: (a) at least TWO consecutive quarters of declining revenue or margins, (b) a specific identified catalyst for further decline (not "weak outlook"), (c) explicit statement of why negative fundamentals are NOT already priced in at current valuation. If (c) cannot be convincingly answered, default to HOLD. This is the system's core AVOID failure: inability to assess whether bearish thesis is in the price.

5. **Valuation floor screen: MANDATORY for all AVOID candidates.** If the stock trades below 0.7x its 3-year average P/S or P/E, AVOID carries a presumption of rejection. The system must document why the valuation discount will widen further, not merely persist.

6. **Absolute ban on AVOID for stocks >40% below 52-week high.** SEDG (+37.0%), CAR (+38.0%), MRNA (+33.6%) — all were deeply depressed. The system systematically fails to recognize mean reversion in beaten-down names. Any stock >40% below its 52-week high receives HOLD by default, regardless of fundamental view. This is a hard rule, not a guideline.

### Sector-Specific Rules (Revised)

7. **Consumer Discretionary BUY suspension: MANDATORY. SIXTH CALIBRATION.** If violated again, all Consumer Discretionary analysis should default to HOLD regardless of score. Reinstatement criteria unchanged: (a) positive sequential comparable revenue growth, (b) FCF yield ≥5%, (c) consumer confidence not in declining 3-month trend. All three documented.

8. **Materials BUY suspension: MANDATORY. NEW.** -2.98% across 6 calls. Reinstatement criteria: (a) positive commodity price momentum in relevant input/output, (b) EBITDA margins above 5-year average, (c) debt/EBITDA <2.5x. All three documented.

9. **Priority BUY sectors:** Utilities (+6.59%, 6 calls), Information Technology (+4.45%, 43 calls), Communication Services (+4.38%, 18 calls), Consumer Staples (+2.97%, 1 call — sample too small), Health Care (+2.11%, 22 calls). Default question for stocks scoring ≥6.0 in these sectors: "Why shouldn't this be BUY?"

10. **Financials BUY cap: ≤25% of BUY calls.** Currently at 35.1%. Average return improved to +2.05%, resolving the underperformance concern, but concentration risk remains. Apply the cap strictly; prioritize highest-conviction Financials names only.

### Scoring and Conviction Rules

11. **Cyclical score ceiling of 7.0: ENFORCED.** BMI (7.06 → -20.56%) validates this rule. No stock with beta >1.3 may exceed 7.0.

12. **"Why Not BUY?" gate: applies to all HOLD scores ≥5.8.** Must cite a specific, falsifiable risk. This gate is working — BUY hit rate improved to 61.1% even with dramatically expanded volume, suggesting the system was previously defaulting high-quality names to HOLD.

13. **"Why Not HOLD?" gate replaces "Why Not AVOID?" gate for scores ≤5.8.** Given AVOID signal collapse, the bias for low-scoring stocks should be toward HOLD, not AVOID. Only route to AVOID if the structural deterioration checklist (Rule 4) is fully satisfied.

14. **HOLD tail-risk screen: ENFORCED.** Any HOLD candidate with debt/EBITDA >4x, EPS variance >30%, or market cap <$2B must be routed to BUY or AVOID. HOLD must not contain catastrophic risk.

15. **Bottom-third scores no longer carry a presumption of AVOID.** With bottom-third average at +0.12%, the defensive signal has weakened substantially. Bottom-third scores carry a presumption of HOLD. AVOID requires additional deterioration evidence beyond a low score.

## Areas of Strength

1. **BUY is the system's proven, durable alpha signal.** +2.14% average, 61.1% hit rate, robust at n=262. Quality held up under dramatically increased volume — the most important finding. The system has substantial capacity to issue BUYs without degrading the signal.

2. **Recommendation hierarchy is monotonic for BUY vs. HOLD.** BUY (+2.14%) beats HOLD (+0.18%) by 1.96pp. This is genuine, actionable alpha.

3. **BUY downside containment remains strong.** Worst BUY loss is -20.56%. Compare to HOLD worst of -75.2%. Even the expanded BUY universe maintains reasonable downside bounds.

4. **Sector specialization is confirmed.** Utilities (+6.59%), IT (+4.45%), Communication Services (+4.38%) — consistent BUY outperformance with meaningful sample sizes (especially IT at 43 calls).

5. **DELL remains the model BUY archetype.** Score 6.8, +33.22%. Quality business + secular catalyst + reasonable valuation. The template works.

6. **Validated AVOID calls demonstrate genuine expertise in structural deterioration.** KLAR (-26.9%), CPB (-16.2%), SMCI (-28.6%), PLAY (-27.2%) — the system excels when AVOID is applied to actively deteriorating businesses. This skill is intact; it's being diluted by misapplication to depressed-valuation names.

7. **Calibration process is demonstrably effective.** BUY hit rate improved from 56.7% to 61.1% after mandating increased BUY issuance. HOLD compression from 77.4% to 71.4%. Distribution directives produce measurable improvement.

8. **Energy BUY consistency.** Energy BUYs at +0.67% across 20 calls — lower than BUY average but positive with meaningful sample. Modest but reliable.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2025-01-27 | Initial calibration. n=120. HOLD 75%, score spread 3.23pp. |
| 2025-06-16 | Major update. n=521. HOLD 78.1%, AVOID 1.0%, score spread 1.52pp. Consumer Discretionary flagged. |
| 2025-07-15 | Update. n=539. Score spread 1.38pp. APO double-loss flagged. Cyclical ceiling introduced. |
| 2025-08-18 | Major update. n=829. AVOID volume 4× to 38 calls. Score spread rebounded to 2.08pp. BUY issuance collapse flagged as critical. |
| 2025-06-20 | Major update. n=1,360. BUY issuance collapsed to ~3.6%. HOLD average -0.12%. AVOID validated at scale. PIPR tail-risk exposed. |
| 2025-07-01 | Update. n=1,392. Incremental distribution improved. AVOID signal dilution flagged as new critical issue (avg return -0.67% → -0.18%). |
| 2025-07-14 | **Major update. n=1,576.** Key findings: **(1) AVOID signal has collapsed — avg return now +1.06%, making AVOID stocks more profitable than HOLD. Recommendation hierarchy broken: BUY > AVOID > HOLD. AVOID issuance must be drastically curtailed and restricted to documented structural deterioration only. Hard ban on AVOID for stocks >40% below 52-week high.** (2) BUY signal strengthened materially despite ~57% issuance rate — avg return +2.14%, hit rate 61.1% (up from 56.7%). Proves prior BUY conservatism was the system's biggest drag. BUY ceiling of 30% introduced to prevent overcorrection. (3) Score spread compressed to 1.3pp from 1.76pp — approaching actionability threshold. Bottom-third no longer loses money (+0.12%). Monitor for sub-1.0pp at next calibration. (4) Consumer Discretionary BUY violation detected for sixth consecutive calibration (-0.47%, 14 calls). (5) Materials BUY suspension introduced (-2.98%, 6 calls). (6) Financials BUY underperformance resolved (+2.05% vs. prior +0.97%) but concentration at 35.1% exceeds 25% cap. (7) BMI (-20.56% at score 7.06) validates cyclical ceiling of 7.0. **Primary directives: (a) Repair AVOID signal — reduce volume to 10–15%, enforce structural deterioration checklist, ban AVOID on deeply depressed names; (b) Normalize BUY at 20–25% (not 57%); (c) Enforce Consumer Discretionary and Materials BUY suspensions; (d) Monitor score spread — if <1.0pp at next calibration, initiate scoring methodology review.** |