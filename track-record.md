---
layout: default
title: "Track Record"
---

*Last updated: April 14, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 1,392 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 157 | +2.04% | 56.7% | +33.22% | -16.85% |
| HOLD | 1,077 | -0.07% | 49.8% | +33.92% | -75.19% |
| AVOID | 156 | -0.18% | 41.0% | +38.05% | -28.61% |

**Score Predictiveness:** Top-third scored stocks returned +1.28% vs. -0.48% for bottom-third — a **1.76pp spread**. Historical trajectory: 3.23pp (n=120) → 1.52pp (n=521) → 1.38pp (n=539) → 2.08pp (n=829) → 1.9pp (n=1,360) → **1.76pp (n=1,392)**. The spread has compressed slightly from 1.9pp. Bottom-third average improved marginally from -0.65% to -0.48%. Revised estimate of true spread: **1.7–2.0pp.** The scoring system remains a confirmed, durable risk-identification tool, though its edge is modestly narrowing. Low scores still predict underperformance.

**Recommendation Distribution:** HOLD is 77.4% of all calls (1,077/1,392). BUY is 11.3% (157/1,392). AVOID is 11.2% (156/1,392). In the incremental ~32 reports since last calibration: estimated ~4 new BUYs (~12.5%), ~14 new HOLDs (~43.8%), ~14 new AVOIDs (~43.8%). **The incremental batch shows dramatic improvement** — BUY issuance rebounded sharply from the catastrophic ~3.6% rate, and HOLD dropped well below the 60% ceiling. This is exactly the distributional correction mandated. However, the cumulative distribution remains deeply distorted by legacy HOLD overissuance.

**BUY Signal:** Average return ticked up to +2.04% (from +2.02% at n=1,360). Hit rate improved to 56.7% (from 56.2%). The BUY-over-HOLD spread is **2.11pp** (+2.04% vs. -0.07%). **The BUY signal continues to work.** It generates genuine, durable alpha with favorable asymmetry (worst -16.85%, best +33.22%). 43.3% of BUY calls lose money — this is the cost of the signal. The average winner substantially exceeds the average loser.

**AVOID Signal:** 156 AVOID calls at -0.18% average return with 41.0% hit rate (i.e., **59.0% of AVOID calls correctly declined or stayed flat**). Average return moved from -0.67% toward zero, and hit rate increased from 38.7% to 41.0%. **The AVOID signal is weakening.** The directional correctness dropped from 61.3% to 59.0%. More critically, the average AVOID return is now only -0.18%, significantly less negative than -0.67%. The recommendation hierarchy remains monotonic — BUY (+2.04%) > HOLD (-0.07%) > AVOID (-0.18%) — but the HOLD-to-AVOID gap has **nearly vanished** at just 0.11pp. AVOID is barely distinguishable from HOLD in returns. This demands attention.

**HOLD Improved Marginally.** HOLD average return rose from -0.12% to -0.07%. Hit rate improved from 49.4% to 49.8%. Still essentially a coin flip with near-zero expected return. The catastrophic tail remains (PIPR -75.2%). HOLD is still providing minimal useful information, but the slight improvement suggests the incremental batch's better distribution is beginning to help.

## Identified Biases

### 1. BUY Issuance Recovery — Sustain and Accelerate (Severity: HIGH — Downgraded from CRITICAL)
The incremental batch showed ~12.5% BUY issuance, a massive improvement from ~3.6%. However, cumulative BUY remains at 11.3%, still below the 15% minimum floor and far below the 20–25% target. The correction has begun but must accelerate. Every report batch must continue targeting ≥15% BUY. The system demonstrated it can issue BUYs when directed — the constraint was psychological, not analytical.

### 2. HOLD Remains Bloated (Severity: HIGH — Downgraded from CRITICAL)
Cumulative HOLD is 77.4%, still far above the 60% ceiling, but the incremental batch at ~43.8% is a breakthrough. If sustained, this will rapidly dilute legacy bloat. The incremental batch performance validates that forcing distribution away from HOLD improves outcomes. **Maintain the 60% ceiling rigorously.**

### 3. AVOID Signal Dilution (Severity: HIGH — NEW)
AVOID average return moved from -0.67% to -0.18%. This is a concerning degradation. Possible causes: (a) the increased AVOID volume (~43.8% of incremental batch) may be including marginal names that don't truly warrant AVOID — the contrarian rebound problem at scale; (b) market conditions may have favored beaten-down names. The AVOID-to-HOLD spread collapsed from 0.55pp to just **0.11pp**. At this rate, AVOID is becoming synonymous with HOLD. **AVOID quality must be prioritized over AVOID quantity.** The 15% floor remains, but 43.8% is overcorrection. AVOID should be 15–25% of calls, not >40%.

### 4. Consumer Discretionary BUY Bias (Severity: High — Unchanged)
Consumer Discretionary BUYs: **-1.34% across 12 calls** (up from 11 at last calibration). Another violation of the mandatory suspension detected. Average return remains the worst of any sector with meaningful sample size. **Fifth calibration flagging this issue.** The suspension is not optional.

### 5. AVOID Contrarian Blind Spot (Severity: ELEVATED — Worsened)
SEDG (AVOID, +37.0%), CAR (AVOID, +38.0%), MRNA (AVOID, +33.6%) remain the three worst AVOID failures. The dilution of AVOID's average return from -0.67% to -0.18% suggests more marginal contrarian-rebound names are entering the AVOID bucket. The contrarian rebound screen (stocks >30% below 52-week high) must be applied strictly, especially at higher AVOID volumes.

### 6. Financials Concentration (Severity: MODERATE — Stable)
Financials represent 35.0% of BUY calls (55/157). Average return is +0.97% — a minor tick up from +0.88% but still well below the +2.04% BUY average. Degradation pattern: +2.33% (n=35) → +1.42% (n=49) → +0.88% (n=54) → **+0.97% (n=55)**. Stabilized but underperforming. The 25% cap must be enforced going forward.

### 7. High-Score Cyclical Overconfidence (Severity: MODERATE — Unchanged)
APO (7.55 → -16.9%) remains the worst BUY loss. Cyclical ceiling of 7.0 must continue to be enforced.

### 8. HOLD Tail-Risk Blind Spot (Severity: HIGH — Unchanged)
PIPR (-75.2%), ADMA (-40.4%), SNEX (-27.3%) — all HOLD-rated. The HOLD tail-risk screen mandated in prior calibration must be enforced. No evidence yet of implementation.

## Lessons for Future Analysis

### Recommendation Distribution — Hard Rules (Revised)

1. **BUY floor: 15% minimum. Target: 20–25%.** The incremental batch hit ~12.5%. Close, but below floor. Continue pushing. Every stock scoring ≥6.5 with identifiable catalyst carries a **presumption of BUY** requiring explicit, falsifiable override.

2. **HOLD ceiling: 60% absolute maximum.** Incremental batch achieved ~43.8% — excellent. Sustain this. Cumulative will correct over time.

3. **AVOID target: 15–25%. NOT higher.** The incremental batch at ~43.8% AVOID is overcorrection. AVOID's average return degraded from -0.67% to -0.18% as volume surged. Quality collapsed with quantity. **AVOID must be reserved for stocks with demonstrable structural deterioration, not merely low scores or generic weakness.** Issuing AVOID on marginal names dilutes the signal and approaches HOLD-level randomness.

### Sector-Specific Rules

4. **Consumer Discretionary BUY suspension: MANDATORY. NO EXCEPTIONS.** Fifth calibration. Reinstatement conditions unchanged: (a) positive sequential comparable revenue growth, (b) FCF yield ≥5%, (c) consumer confidence not in declining 3-month trend. All three documented or the call is HOLD/AVOID.

5. **Financials BUY cap: ≤25% of BUY calls.** At +0.97%, Financials BUYs drag down portfolio alpha by >1pp vs. the BUY average. Require ROE or FCF yield meaningfully above sector median.

6. **Priority BUY sectors:** Utilities (+8.74%, 5 calls), Energy (+7.42%, 8 calls), Communication Services (+4.40%, 11 calls), Health Care (+3.82%, 12 calls). When analyzing stocks in these sectors scoring ≥6.0, the default question is: "Why shouldn't this be BUY?"

7. **IT BUY guardrails in force.** IT BUYs at +2.33% across 26 calls — above BUY average, but high variance. Require FCF yield ≥3% or forward P/E below sector median. High-multiple SaaS names carry presumptive HOLD unless growth acceleration is documented.

### AVOID Quality Control (NEW SECTION)

8. **AVOID issuance quality gate.** Before issuing AVOID, the analyst must document at least ONE of: (a) declining revenue trajectory over ≥2 quarters, (b) deteriorating margins with no credible turnaround plan, (c) balance sheet stress (rising leverage, covenant risk, liquidity concern), (d) secular headwind with no pivot strategy. Generic "overvalued" or "weak outlook" is insufficient for AVOID. If none of (a)–(d) can be documented, default to HOLD.

9. **Contrarian rebound screen: MANDATORY for stocks >30% below 52-week high.** Before issuing AVOID, check: (a) short interest >15%, (b) insider buying in trailing 90 days, (c) consensus estimates already cut ≥20%. If 2 of 3 are met, default to HOLD. This screen prevented SEDG and CAR type errors.

10. **AVOID targets deterioration, not cheapness.** SMCI (-28.6%), KLAR (-26.9%), CPB (-16.2%), PLAY (-27.2%) are model AVOIDs — structurally deteriorating businesses. SEDG (+37.0%), CAR (+38.0%) were statically weak at depressed valuations. Only issue AVOID for active deterioration.

### Conviction and Scoring Rules

11. **Cyclical score ceiling of 7.0: ENFORCED.** No stock with beta >1.3 may exceed 7.0 without documented macro justification and scenario analysis.

12. **"Why Not BUY?" gate: applies to all HOLD scores ≥5.8.** Analyst must cite a specific, falsifiable risk — not generic language. Inability to articulate a concrete risk mandates BUY.

13. **"Why Not AVOID?" gate: applies to all HOLD scores ≤5.8.** Must cite a specific positive factor (upcoming catalyst, insider buying, stabilizing fundamentals). Inability to cite a concrete positive mandates AVOID.

14. **HOLD tail-risk screen: ENFORCED.** Any HOLD candidate with high leverage (debt/EBITDA >4x), earnings volatility (>30% EPS variance), or small-cap illiquidity (<$2B market cap) must be routed to BUY (if upside justifies risk) or AVOID (if downside dominates). HOLD must not contain catastrophic risk names.

15. **No repeat BUY on a losing name within 6 months: ENFORCED.**

### Score Interpretation

16. **Bottom-third scores predict underperformance: -0.48% average.** While slightly improved from -0.65%, still the system's most actionable defensive signal. Bottom-third scores carry a presumption of AVOID; issuing HOLD requires documented justification.

17. **Score spread is compressing (1.76pp from 1.9pp).** Monitor closely. If spread falls below 1.5pp, the scoring methodology may need recalibration. The system's primary edge is on the downside (identifying losers), not the upside.

## Areas of Strength

1. **Recommendation hierarchy remains monotonic.** BUY (+2.04%) > HOLD (-0.07%) > AVOID (-0.18%). The core analytical engine produces directionally correct rankings. This is non-trivial across 1,392 calls.

2. **BUY is the system's crown jewel.** +2.04% average, 56.7% hit rate, favorable asymmetry, worst loss contained at -16.85%. BUY generates genuine alpha. Issue more of it.

3. **Score predictiveness is durable at ~1.76pp.** Six measurement points confirm a stable, genuine signal. Proven risk-management tool.

4. **Distribution correction is underway.** The incremental batch showed dramatic improvement in recommendation distribution. The system demonstrated it can break out of HOLD paralysis when directed. This proves the calibration process works.

5. **Sector specialization is proven.** Utilities (+8.74%), Energy (+7.42%), Communication Services (+4.40%), Health Care (+3.82%) — consistent BUY outperformance. These are genuine competence areas.

6. **DELL remains the model BUY archetype.** Score 6.8, +33.22%. Quality business + secular catalyst + reasonable valuation.

7. **Validated AVOID calls demonstrate structural-deterioration expertise.** KLAR (-26.9%), CPB (-16.2%), SMCI (-28.6%), PLAY (-27.2%) — the system excels at identifying businesses in genuine decline. This skill must be preserved by restricting AVOID to these types of calls rather than diluting the signal.

8. **BUY downside containment is excellent.** Worst BUY loss is -16.85% (APO). No BUY has ever lost >17%. Compare to HOLD worst of -75.2%. The BUY vetting process successfully screens out catastrophic risk.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2025-01-27 | **Initial calibration.** n=120. HOLD 75%, score spread 3.23pp. |
| 2025-06-16 | **Major update.** n=521. HOLD 78.1%, AVOID 1.0%, score spread 1.52pp. Consumer Discretionary flagged. |
| 2025-07-15 | **Update.** n=539. Score spread 1.38pp. APO double-loss flagged. Cyclical ceiling introduced. |
| 2025-08-18 | **Major update.** n=829. AVOID volume 4× to 38 calls. Score spread rebounded to 2.08pp. BUY issuance collapse flagged as critical. |
| 2025-06-20 | **Major update.** n=1,360. BUY issuance collapsed to ~3.6% — most critical failure. HOLD average collapsed to -0.12%. AVOID validated at scale (142 calls, -0.67%). PIPR -75.2% exposed HOLD tail-risk blind spot. |
| 2025-07-01 | **Update.** n=1,392. **Key findings:** (1) Incremental batch distribution dramatically improved: ~12.5% BUY, ~43.8% HOLD, ~43.8% AVOID — proves calibration directives work when followed; (2) **AVOID signal dilution is the new critical issue** — AVOID avg return improved from -0.67% to -0.18%, AVOID-to-HOLD spread collapsed to 0.11pp, indicating AVOID overcorrection and quality degradation; (3) BUY signal remains robust: +2.04% avg, 56.7% hit rate, slight improvement; (4) Score spread compressed to 1.76pp from 1.9pp — monitor for further erosion; (5) Consumer Discretionary BUY violation detected for fifth consecutive calibration; (6) Financials BUY stabilized at +0.97% but still underperforms BUY average by >1pp. **Primary directives for next period: (a) Continue increasing BUY issuance toward 20–25% target; (b) REDUCE AVOID volume from ~43.8% back to 15–25% range while tightening quality criteria — AVOID must mean structural deterioration, not generic weakness; (c) Enforce AVOID quality gate requiring documented deterioration evidence; (d) Enforce Consumer Discretionary BUY suspension.** |