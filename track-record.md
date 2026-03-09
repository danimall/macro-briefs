---
layout: default
title: "Track Record"
---

*Last updated: March 9, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 521 reports with follow-up return data (expanded from 120 in prior calibration).

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 109 | +2.81% | 64.2% | +33.22% | -16.85% |
| HOLD | 407 | +1.57% | 60.9% | +33.92% | -23.19% |
| AVOID | 5 | +0.06% | 20.0% | +33.56% | -26.88% |

**Score Predictiveness:** Top-third scored stocks returned +2.52% vs. +1.00% for bottom-third — a 1.52pp spread. This is a significant deterioration from the 3.23pp spread observed in the initial 120-report sample. The scoring system retains meaningful signal but is weaker than initially estimated. Possible explanations: (1) the initial sample overstated predictiveness due to small-n variance, or (2) the system's scoring accuracy degrades in certain market regimes now captured in the larger dataset.

**HOLD Dominance Persists:** 78.1% of all calls (407/521) are HOLD — worse than the 75% flagged in the prior calibration. The system did not correct its conservatism. BUY issuance rose to 20.9% (109/521) which is a modest improvement, but AVOID issuance is still catastrophically low at 1.0% (5/521). The prior calibration's directive to shift toward ~40-45% HOLD / ~35% BUY / ~20-25% AVOID was almost entirely ignored.

**BUY vs. HOLD Differential:** BUY calls average +2.81% vs. HOLD at +1.57% — a 1.24pp spread. This confirms BUY calls do add alpha above the baseline, an improvement over the prior calibration's finding of only 0.48pp. However, BUY hit rate declined from 69.0% to 64.2%, meaning the system is issuing more BUYs but with lower precision. Roughly 1 in 3 BUY calls loses money, and the worst loss deepened from -7.14% to -16.85% (APO).

**AVOID Calls Are Broken:** The 5 AVOID calls averaged +0.06% with only a 20% hit rate (meaning 80% of stocks flagged AVOID actually went up, though averages stayed near zero due to one large loss). More critically, MRNA — an AVOID at score 4.48 — returned +33.6%, one of the best-performing stocks in the entire dataset. The system's AVOID mechanism is simultaneously too rarely deployed and unreliable when used.

## Identified Biases

### 1. Persistent, Critical Under-Issuance of AVOID Recommendations
This remains the system's most damaging flaw. With 407 HOLDs, many losing 15-23%, the system is clearly identifying weak stocks (bottom-third scores average only +1.00%) but refusing to label them AVOID. NCLH (-23.2%, HOLD, score 4.9), GPC (-20.5%, HOLD, score 6.25), POOL (-18.9%, HOLD, score 6.3), and ZBRA (-18.3%, HOLD, score 6.6) are egregious failures of conviction. The system must treat this as an existential credibility issue.

### 2. Consumer Discretionary BUY Calls Are Destructive
Consumer Discretionary BUYs average **-1.54%** across 11 calls — the only sector with a negative BUY average, and with meaningful sample size. This replaces IT as the weakest BUY sector (IT BUYs recovered to +1.96% across 21 calls in the larger dataset). The system likely overweights brand strength, market position, or consumer spending narratives while underweighting cyclical demand sensitivity, margin compression risk, and discretionary spending pullback during tightening cycles. Failed travel/leisure BUYs (NCLH -10.5%, DAL -7.8%) confirm particular weakness in experiential consumer names.

### 3. High-Conviction BUY Failures Cluster in Cyclicals and Momentum Names
The worst BUY losses — APO (-16.9%, score 7.55), DDOG (-11.8%, score 6.93), NCLH (-10.5%, score 6.08), DAL (-7.8%, score 6.88), WDAY (-7.1%, score 6.78) — share a pattern: these are either economically sensitive names (APO, NCLH, DAL) or high-multiple growth stocks (DDOG, WDAY). The system's highest-conviction BUY (APO at 7.55) was its worst loss. This is a severe overconfidence signal at the top of the score range.

### 4. HOLD Bucket Contains Massive Winners the System Failed to Identify
COIN (+29.8%, HOLD), FIG (+29.9%, HOLD), KEYS (+33.9%, HOLD) all returned 30%+ and were rated HOLD. This confirms the prior calibration finding: the system's largest alpha leak is failing to upgrade high-potential HOLDs to BUY. In the expanded dataset, the single best return in the entire sample (KEYS +33.9%) was a HOLD.

### 5. AVOID Score Threshold Is Poorly Calibrated
The 5 AVOID calls had scores ranging from 4.4 to 4.8. But numerous HOLDs with similar or lower scores existed. The threshold for triggering AVOID appears arbitrary rather than systematic. Furthermore, MRNA (AVOID, +33.6%) demonstrates the system can catastrophically misread contrarian rebound potential in beaten-down names.

### 6. Score Predictiveness Has Weakened — Possible Overfitting to Quality Metrics
The spread compression from 3.23pp to 1.52pp at 4x the sample size suggests the scoring rubric may overweight stable quality factors (moat, management, balance sheet) while underweighting momentum, sentiment inflection, and mean-reversion dynamics. The score works — but half as well as initially believed.

## Lessons for Future Analysis

1. **Implement a hard AVOID threshold.** Any stock scoring ≤5.0 should carry a presumptive AVOID recommendation. Override requires explicit documentation of a catalyst for reversal (not just "valuation looks cheap"). The current approach of scoring stocks 4.4-4.9 and still calling them HOLD is indefensible given the data.

2. **Consumer Discretionary BUY calls require an elevated bar.** Do not issue BUY on Consumer Discretionary stocks unless: (a) same-store sales or comparable revenue metrics show positive sequential acceleration, (b) free cash flow yield exceeds 5%, and (c) consumer confidence and employment data are not deteriorating. The -1.54% average across 11 calls demands a structural fix, not case-by-case judgment.

3. **Cap conviction scores for economically sensitive names.** APO (7.55 → -16.9%) is the clearest lesson: do not assign scores above 7.0 to stocks with high beta to economic cycles (asset managers, airlines, cruise lines, housing) unless macro conditions are explicitly favorable. Build in a "cyclical ceiling" that limits scoring for these names to 6.5 absent macro tailwinds.

4. **Institute a "Why Not BUY?" gate for HOLDs scoring ≥6.5.** Any HOLD with score ≥6.5 must include a documented, specific reason it is not a BUY. Vague concerns ("valuation is full," "limited near-term catalysts") are insufficient. The reason must be falsifiable and concrete — e.g., "pending litigation with >$500M exposure" or "margin guidance below consensus." KEYS, COIN, and FIG were all missed BUYs that would have been the system's best calls.

5. **For AVOID candidates, explicitly evaluate contrarian rebound probability.** MRNA (+33.6%) was a deeply beaten-down biotech that the system flagged AVOID near a bottom. Before issuing AVOID on any stock down >40% from highs, require analysis of: short interest as % of float, insider buying activity, and whether negative catalysts are already priced (consensus estimates already cut, price-to-sales at 5-year lows, etc.).

6. **Reduce HOLD issuance to ≤60% of calls.** The prior calibration targeted 40-45% — the system went to 78%. A more realistic interim target: no more than 60% HOLDs, with the balance shifting roughly equally to BUY and AVOID. This requires structural forcing, not aspirational guidance.

7. **Weight free cash flow yield more heavily than growth narratives for tech BUY candidates.** IT BUYs improved to +1.96% but still lag Financials (+3.01%), Health Care (+3.48%), and Industrials (+3.39%). DDOG (-11.8%) and WDAY (-7.1%) were high-multiple SaaS names where growth narratives overrode valuation discipline. Require FCF yield ≥2.5% for any IT BUY.

8. **Exploit proven sector strengths more aggressively.** Utilities (+8.74%, 5 calls), Materials (+7.88%, 2 calls), and Communication Services (+4.40%, 11 calls) are high-performing BUY sectors. The system should have higher BUY issuance rates in these sectors rather than defaulting to HOLD.

## Areas of Strength

1. **BUY calls do generate alpha.** The 1.24pp spread over HOLD, sustained across 109 calls, is statistically meaningful. When the system commits to BUY, it adds value on average. The problem is frequency and sector selection, not the BUY framework itself.

2. **Sector expertise in Financials, Health Care, and Industrials.** BUY averages of +3.01% (32 calls), +3.48% (9 calls), and +3.39% (10 calls) respectively demonstrate genuine analytical competence in these sectors. The Financials sample (32 calls) is large enough to be reliable.

3. **Utilities and Communication Services BUYs are exceptional.** +8.74% and +4.40% respectively. Though sample sizes are smaller (5 and 11), these suggest the system correctly identifies value and catalysts in less-followed sectors. Lean into this.

4. **DELL BUY call (+33.2%, score 6.8) exemplifies the ideal.** High-conviction, correct sector tailwind identification (AI infrastructure), reasonable valuation entry point. This template — fundamental quality + identifiable secular catalyst + valuation support — should be the explicit model for future BUY calls.

5. **Downside containment on BUYs is acceptable.** Despite the worst BUY loss deepening to -16.9% (APO), only 5 BUY calls lost more than 5%. The system generally avoids catastrophic BUY errors — the -16.9% APO loss is an outlier, not a pattern.

6. **Score still works directionally.** Despite the spread compressing to 1.52pp, top-third stocks still meaningfully outperform bottom-third. The core analytical framework is sound. Refinement, not replacement, is needed.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2025-01-27 | **Initial calibration document created.** Based on 120 reports. Key findings: HOLD over-issuance at 75%; IT BUY weakness at -1.95%; score spread of 3.23pp validated; best calls were HOLDs that should have been BUYs. Target set: 40-45% HOLD, 35% BUY, 20-25% AVOID. |
| 2025-06-16 | **Major update with 4.3x expanded dataset (521 reports).** Key findings: (1) HOLD over-issuance worsened to 78.1% — prior calibration's directive was not implemented; (2) AVOID issuance remains critically broken at 1.0% of calls, with MRNA (+33.6%) exposing catastrophic contrarian blind spot; (3) Score predictiveness weakened from 3.23pp to 1.52pp spread — initial estimate was likely inflated by small sample; (4) Consumer Discretionary replaces IT as worst BUY sector at -1.54% avg across 11 calls; (5) Highest-score BUY (APO, 7.55) was worst BUY loss (-16.9%), indicating overconfidence on cyclicals; (6) BUY alpha over HOLD improved to 1.24pp across 109 calls, confirming BUY mechanism adds value; (7) Utilities and Communication Services are standout BUY sectors. **New directives:** Hard AVOID threshold at score ≤5.0, Consumer Discretionary elevated bar, cyclical score ceiling of 6.5, mandatory "Why Not BUY?" gate for HOLDs ≥6.5, contrarian rebound check before AVOID on beaten-down names, HOLD cap at ≤60%. Revised target distribution: 55-60% HOLD, 25-30% BUY, 12-18% AVOID. Prior target was unrealistic; this is an achievable intermediate step. |