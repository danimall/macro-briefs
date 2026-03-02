---
layout: default
title: "Track Record"
---

*Last updated: March 1, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 120 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 29 | +2.41% | 69.0% | +29.76% | -7.14% |
| HOLD | 90 | +1.93% | 62.2% | +27.44% | -18.31% |
| AVOID | 1 | -2.90% | 0.0% (validated) | -2.90% | -2.90% |

**Score Predictiveness:** The scoring system demonstrates meaningful signal. Top-third scored stocks returned +3.81% on average vs. +0.58% for bottom-third — a 3.23 percentage point spread. This confirms the scoring rubric captures real information, but the spread is modest enough to indicate significant room for improvement.

**Key Concern — HOLD Dominance:** 75% of all calls (90/120) are HOLD. This suggests excessive conservatism and a reluctance to commit to directional views. Several HOLD calls produced returns exceeding +15%, meaning the system repeatedly failed to identify strong BUY candidates. Conversely, HOLDs also produced the worst drawdowns (down to -18.3%), meaning the system failed to flag clear AVOID situations.

**BUY Hit Rate Context:** A 69% hit rate on BUY calls is reasonable but not exceptional. Roughly 1 in 3 BUY calls loses money, with three calls losing more than 5%. The average return of +2.41% is positive but only ~0.48pp above the HOLD average, raising the question of whether the system's BUY conviction adds meaningful alpha beyond its baseline scoring.

## Identified Biases

### 1. Severe Under-Issuance of BUY and AVOID Recommendations
The system defaults to HOLD far too often. With 90 HOLD calls and only 1 AVOID, the system is essentially refusing to make negative calls. Meanwhile, several HOLDs lost 10-18%, which should have been AVOIDs. Stocks like ZBRA (-18.3%), BLDR (-13.5%), and BX (-12.6%) were rated HOLD with scores of 6.5-7.1 — the system saw moderate quality and defaulted to neutrality rather than identifying red flags.

### 2. Information Technology BUY Weakness
IT BUY calls averaged -1.95% across 3 calls, the worst-performing sector for BUYs. WDAY (-7.1%) is a notable failure. The system may be overweighting growth narratives, recurring revenue models, or TAM expansion stories in tech without adequately discounting elevated valuations and multiple compression risk.

### 3. Communication Services BUY Weakness
Only 1 call but negative (-1.45%). Combined with IT underperformance, the system appears to struggle with high-multiple growth/tech-adjacent sectors.

### 4. Missed Upside in HOLD Calls (Conviction Gap)
The four best-performing calls in the entire dataset were all HOLDs: VRSK (+16%), CIEN (+19%), TYL (+23.6%), TPL (+27.4%). These represent massive missed conviction. The system identified quality (scores 6.1-7.1) but failed to translate quality assessment into actionable BUY recommendations. This is the single largest alpha leak in the system.

### 5. Financial Sector Overconfidence Under Stress
Financials represent the largest BUY cohort (9 calls) with a strong +3.96% average, but two notable failures are BAC (-5.1%) and WFC (-5.6%) — both large-cap banks. The system may be applying a uniform positive view to financials without differentiating sensitivity to rate curve shifts and credit risk.

### 6. Valuation Score Insufficiently Weighted
The worst HOLD calls (ZBRA, BLDR, BX) had scores in the 6.5-7.1 range — not low enough to trigger concern. The scoring system appears to insufficiently penalize stocks with stretched valuations or cyclical exposure, allowing vulnerable names to cluster in the "decent" score range.

## Lessons for Future Analysis

1. **Reduce HOLD frequency by at least 15-20 percentage points.** Institute a forcing function: if a stock scores ≥7.0 and has identifiable near-term catalysts, it must be BUY unless a specific, articulable risk justifies downgrade. If a stock scores ≤5.5 or has deteriorating fundamentals, it should be AVOID unless a specific contrarian thesis is documented.

2. **For Information Technology BUY candidates, require a valuation margin of safety.** Apply a stricter valuation screen: do not issue BUY on IT stocks trading above 35x forward earnings unless free cash flow yield exceeds 3% and revenue growth exceeds 15% YoY. The -1.95% average on IT BUYs demands a higher bar.

3. **Differentiate within Financials.** For large-cap banks (BAC, WFC, JPM, C), explicitly model net interest income sensitivity to yield curve changes before issuing BUY. The system's 9-call financial BUY record is skewed by successes that may mask rate-environment dependency. Weight credit quality and loan loss reserve trajectory more heavily.

4. **Backtest HOLD calls scoring ≥6.8 for upgrade potential.** The data shows that high-scoring HOLDs frequently outperform BUYs. Implement a secondary screen: any HOLD with score ≥6.8 should be re-evaluated with a "Why not BUY?" framework that requires explicit documentation of the restraining factor.

5. **Implement downside screening for all HOLD calls.** Any HOLD candidate with >30% revenue cyclicality, >3x net debt/EBITDA, or recent earnings miss should be evaluated against AVOID criteria first. The -18.3% ZBRA loss and -13.5% BLDR loss suggest the system ignores cyclical and housing/construction exposure.

6. **Score recalibration for bottom-third.** Bottom-third scores average only +0.58% return. The system should be more willing to translate low scores into AVOID recommendations. A score below 5.0 should trigger a presumptive AVOID that must be rebutted.

7. **Track catalyst specificity in BUY calls.** Review whether BUY calls with identified near-term catalysts (earnings, product launches, regulatory clearance) outperform those based on general valuation appeal. Prioritize catalyst-driven BUYs.

## Areas of Strength

1. **Score predictiveness is real and meaningful.** The 3.23pp spread between top-third and bottom-third confirms the fundamental analysis framework captures genuine quality differentiation. This core scoring methodology should be preserved.

2. **Financials sector expertise.** +3.96% average across 9 BUY calls with a large sample is the system's strongest sector performance. The analytical framework for financial companies appears sound — the adjustment needed is sub-sector differentiation, not overhaul.

3. **Health Care BUYs are solid.** +3.54% average across 4 calls suggests competent evaluation of healthcare fundamentals. Maintain current approach.

4. **Risk containment on BUY calls.** Worst BUY loss was -7.14%, compared to worst HOLD loss of -18.31%. This means when the system commits to a BUY, it is at least selecting companies with more limited downside. The issue is conviction frequency, not conviction quality.

5. **AVOID validation.** The single AVOID call (CVNA at 4.4 score → -2.9%) was validated. While n=1, combined with bottom-third score underperformance, this supports the system's ability to identify weak stocks — it simply needs to act on that ability far more frequently.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2025-01-27 | **Initial calibration document created.** Key findings: (1) HOLD over-issuance is the dominant systematic error — 75% HOLD rate masks both missed BUY opportunities and unissued AVOID warnings; (2) IT sector BUY calls are the weakest category at -1.95% avg; (3) Scoring system has validated predictive power (3.23pp spread) but is insufficiently translated into directional recommendations; (4) Best-performing calls were overwhelmingly HOLDs that should have been BUYs; (5) Worst-performing calls were HOLDs that should have been AVOIDs. Primary directive for next period: shift the recommendation distribution toward ~40-45% HOLD, ~35% BUY, ~20-25% AVOID by enforcing score-based presumptions and requiring explicit justification for HOLD on extreme-scoring stocks. |