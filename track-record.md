---
layout: default
title: "Track Record"
---

*Last updated: March 25, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 829 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 134 | +1.98% | 57.5% | +33.22% | -16.85% |
| HOLD | 657 | +0.57% | 53.4% | +33.92% | -23.82% |
| AVOID | 38 | +0.08% | 42.1% | +33.56% | -26.88% |

**Score Predictiveness:** Top-third scored stocks returned +1.86% vs. -0.22% for bottom-third — a 2.08pp spread. This is a notable reversal of the decay trend: 3.23pp (n=120) → 1.52pp (n=521) → 1.38pp (n=539) → 2.08pp (n=829). The rebound is likely attributable to the larger sample capturing more tail outcomes in the bottom third (which now averages negative), improving differentiation. Revised estimate of true spread: **1.5–2.1pp range.** The scoring system provides a genuine, durable signal. Bottom-third stocks now average negative returns — the score is more useful as a warning flag for low-scored stocks than previously estimated.

**Recommendation Distribution:** HOLD remains 79.3% of all calls (657/829), **worsening** from 77.0% (n=539) and 78.1% (n=521). BUY is 16.2% (134/829), **declining** from 21.3%. AVOID rose to 4.6% (38/829), a meaningful improvement from 1.7% (9/539) — roughly quadrupled in volume. Despite AVOID progress, distribution remains severely imbalanced. The system issued 29 new AVOID calls in the last 290 reports (~10.0% of the incremental batch), suggesting the AVOID directive is finally gaining traction in newer output. HOLD over-issuance and BUY under-issuance in the incremental batch (estimated ~6.6% BUY rate in new reports) are deeply concerning.

**BUY Signal Continues Eroding:** BUY average return fell from +2.45% (n=115) to +1.98% (n=134). Hit rate dropped from 61.7% to 57.5%. The BUY-over-HOLD spread is now 1.41pp (1.98% vs. 0.57%), which is actually slightly wider than the prior 0.97pp due to HOLD average collapsing from +1.48% to +0.57%. **The BUY signal's absolute quality declined, but its relative edge held because HOLD deteriorated even faster.** This suggests many marginal stocks that should have been BUY or AVOID were dumped into HOLD, dragging that bucket down. **42.5% of BUY calls lose money.** This must be stated plainly: nearly half of all BUY recommendations result in losses.

**AVOID: Volume Improved, Accuracy Still Poor:** 38 AVOID calls is a major increase from 9. Average return is +0.08% — essentially zero, meaning AVOID-tagged stocks went approximately nowhere on average. Hit rate is 42.1% (16 of 38 declined). **57.9% of AVOID calls saw the stock rise.** The system's AVOID mechanism remains unreliable directionally, though the near-zero average is dramatically better than the prior MRNA-contaminated data. The AVOID signal works for identifying stocks that underperform (avg +0.08% vs. +0.57% HOLD vs. +1.98% BUY) even when it doesn't correctly predict negative returns.

## Identified Biases

### 1. HOLD Over-Issuance Is Worsening, Not Improving (Severity: Critical)
79.3% HOLD at n=829, up from 77.0% at n=539. Every calibration has flagged this. Every calibration has set targets (initially 40-45%, revised to 55-60%, then ≤65%). Every target has been violated. The HOLD bucket has become a dumping ground: its average return collapsed from +1.48% to +0.57%, and its hit rate dropped from 60.7% to 53.4%. This is mathematically consistent with a bucket absorbing both missed BUYs and missed AVOIDs. **HOLD is now barely a coin flip for positive returns.** The category is analytically meaningless at this concentration level.

### 2. BUY Issuance Collapsed Instead of Being Sharpened
BUY dropped from 21.3% to 16.2% of calls. In the incremental ~290 reports, the estimated BUY rate was approximately 6.6% — meaning the system dramatically overcorrected on BUY caution instead of improving precision. Combined with a declining hit rate (57.5%), this suggests the system became more conservative without becoming more accurate. The sharpening directives (sector guardrails, valuation filters) may have suppressed good BUY calls alongside bad ones. **The system's BUY mechanism needs precision, not suppression.**

### 3. Consumer Discretionary BUY Bias Persists
Consumer Discretionary BUYs average **-1.54%** across 11 calls. Despite three consecutive calibrations flagging this and the most recent codifying a mandatory suspension, the sample count remains at 11 (unchanged or near-unchanged). If the suspension was implemented, this is a legacy data artifact. If new Consumer Discretionary BUYs were issued, the directive was violated. Either way, the -1.54% average on 11 calls is the only sector with a negative BUY average at meaningful sample size. The suspension must remain in force.

### 4. AVOID Contrarian Blind Spot Remains Active
MRNA (AVOID, +33.6%) remains in the dataset. Among 38 AVOID calls, the best return was +33.56% — almost certainly still MRNA or a similar beaten-down name that rebounded. With 57.9% of AVOID calls rising, the system continues to conflate "bad company" with "will decline further." Validated AVOIDs (KLAR -26.9%, CPB -16.2%) remain structurally deteriorating names, confirming the prior finding: AVOID works for trajectory deterioration but fails for static weakness at depressed prices.

### 5. High-Score Overconfidence on Momentum/Cyclicals (Confirmed)
APO (7.55 → -16.9%, 7.35 → -8.8%) and DDOG (6.93 → -11.8%) remain the worst BUY losses. No new data contradicts the prior finding. The system overweights quality narratives for high-beta names without adequately discounting cyclical and multiple-compression risk.

### 6. HOLD Contains the Dataset's Best and Worst Outcomes
HOLD range: +33.92% to -23.82%. The four best-returning stocks in the entire dataset include three HOLDs (COIN +29.8%, FIG +29.9%, KEYS +33.9%) and one HOLD at the very top (+33.92%). Two of the five worst calls are also HOLDs (GIS -23.8%, NCLH -23.2%). A recommendation category that spans +34% to -24% with a 53.4% hit rate is providing almost no useful information. The alpha is leaking from both ends simultaneously.

### 7. Financials Concentration Risk in BUY Portfolio
Financials represent 36.6% of all BUY calls (49/134) — more than double any other sector. While Financials BUYs average +1.42%, this is now **below** the overall BUY average of +1.98%. The prior calibration called Financials the system's "most reliable signal" at +2.33% across 35 calls. With 14 additional calls, the average has declined to +1.42%. The system's Financials expertise may have been a smaller-sample artifact, or overreliance led to less selective issuance. Either way, Financials BUYs are no longer outperforming the BUY average and should not be treated as the system's core competence.

## Lessons for Future Analysis

### Recommendation Distribution (Revised — Enforced as Hard Rules)

1. **HOLD ceiling: 65% absolute maximum.** Current 79.3% is unacceptable. For every batch of 20 reports, at least 7 must be non-HOLD. Any stock scoring ≤5.0 should carry a presumption of AVOID. Any stock scoring ≥6.5 with a specific catalyst should carry a presumption of BUY. HOLD is for genuinely ambiguous cases, not the default.

2. **AVOID floor: 10% minimum.** The incremental batch achieved ~10% AVOID rate. Lock this in as the permanent floor. Any stock scoring ≤4.8 must be AVOID with no override. Stocks scoring 4.8–5.2 require explicit justification to avoid AVOID classification.

3. **BUY target: 20–25%.** The collapse to ~6.6% in the incremental batch overcorrected. BUY issuance must recover, but hit rate must improve above 60% before expanding beyond 25%. The goal is **selective aggression**, not blanket conservatism.

### Sector-Specific Rules

4. **Consumer Discretionary BUY suspension remains mandatory.** Three prior calibrations have flagged this. The conditions for reinstatement remain: (a) positive sequential comparable revenue growth, (b) FCF yield ≥5%, (c) consumer confidence not in declining 3-month trend. All three must be met simultaneously and documented.

5. **Financials BUY calls: apply tighter selection.** Downgrade from "bread and butter" to "standard sector." Average return declined from +2.33% to +1.42% with expanded sample. The system over-indexed on Financials and should diversify BUY issuance. Cap Financials at ≤30% of BUY calls in any period.

6. **Prioritize BUY issuance in proven outperforming sectors.** Utilities (+8.74%, 5 calls), Materials (+7.88%, 2 calls), Communication Services (+4.40%, 11 calls), Health Care (+2.91%, 10 calls), Energy (+2.94%, 5 calls), and Industrials (+2.25%, 12 calls) all exceed the BUY average. Actively seek BUY candidates in these sectors. When reviewing a stock in these sectors, explicitly ask: "What would prevent this from being a BUY?"

7. **IT BUY guardrails remain in force.** IT BUYs average +1.44% across 22 calls — below the BUY average and barely above HOLD. Require FCF yield ≥3% or forward P/E below sector median. High-multiple SaaS names carry a presumptive HOLD.

### Conviction and Scoring Rules

8. **Cyclical score ceiling of 7.0 remains in force.** No stock with beta >1.3 or in cyclically sensitive sectors may exceed 7.0 without explicit macro documentation.

9. **No repeat BUY on a losing name within 6 months remains in force.** APO double-loss pattern must never recur.

10. **"Why Not BUY?" gate for HOLD scores ≥6.0.** Lowered from 6.2. The documented reason must cite a specific, falsifiable risk — not "valuation concerns" or "limited catalysts." If the analyst cannot articulate a specific, concrete risk, the call should be BUY.

11. **"Why Not AVOID?" gate for HOLD scores ≤5.3.** New directive. Any HOLD scoring 5.3 or below must include explicit documentation of why AVOID is inappropriate. GIS (HOLD, 5.3, -23.8%) and NCLH (HOLD, 4.9, -23.2%) would have been caught by this gate.

### AVOID Calibration

12. **Contrarian rebound analysis remains mandatory for stocks >30% below 52-week high.** Check: (a) short interest >15%, (b) insider buying in trailing 90 days, (c) consensus estimates already cut ≥20%. If 2 of 3 met, default to HOLD.

13. **AVOID should target deteriorating trajectories, not cheap stocks.** Reiterated from prior calibration. Before issuing AVOID, answer: "Is this company getting worse, or is it merely bad?" AVOID only the former. Static weakness at depressed prices is a HOLD at worst, possibly a contrarian BUY.

14. **Accept AVOID as a relative-underperformance signal.** AVOID stocks average +0.08% vs. +0.57% HOLD vs. +1.98% BUY. Even when AVOID stocks rise, they underperform. Frame AVOID as "this stock will underperform the opportunity set" rather than demanding it decline absolutely. This reframe may improve issuance confidence.

### Score Interpretation

15. **Bottom-third scores are now a genuine negative signal.** At -0.22% average return, the lowest-scored third of stocks actually loses money on average. Any stock in the bottom third of scores should face a strong presumption of AVOID. This is the single most actionable finding in the updated data: low scores predict negative returns.

16. **Do not over-rely on score magnitude for high-score stocks.** The score works primarily by identifying losers (bottom third), not by differentiating among winners. Top-third (+1.86%) and mid-range returns are close enough that the score's upside differentiation is modest.

## Areas of Strength

1. **Score predictiveness rebounded to 2.08pp spread.** The scoring system is more useful than the prior two calibrations suggested. Bottom-third stocks now average negative returns, making the score a genuine risk-management tool. This is the system's strongest analytical asset.

2. **BUY still generates meaningful alpha over HOLD.** +1.98% vs. +0.57% is a 1.41pp spread. Across 134 calls, this represents durable outperformance. The mechanism works but needs higher precision (target >60% hit rate).

3. **AVOID volume improved dramatically.** From 9 to 38 calls. The incremental batch ran ~10% AVOID rate, near the target floor. The system is learning to issue negative calls. Maintain and expand this progress.

4. **AVOID identifies relative underperformers.** +0.08% average vs. +0.57% HOLD vs. +1.98% BUY. The ordering is correct and monotonic: BUY > HOLD > AVOID. The recommendation hierarchy is directionally sound even if AVOID's absolute hit rate (42.1%) is weak.

5. **Downside containment on BUY is acceptable.** Worst BUY is -16.85%. Only 5 of 134 BUY calls lost >5%. Catastrophic BUY errors are rare. The system's risk management on the long side is solid.

6. **DELL (+33.2%, score 6.8) remains the model BUY call.** Quality business + secular catalyst + reasonable valuation. Continue using this as the BUY template.

7. **Utilities, Materials, Communication Services, Energy, and Health Care BUYs are strong.** All above +2.9% average. These sectors represent proven competence areas and should be prioritized for BUY sourcing.

8. **Validated AVOIDs demonstrate extreme downside capture.** KLAR (-26.9%), CPB (-16.2%) show the system can identify true structural losers. The AVOID mechanism's value lies in these high-conviction deterioration calls, not broad negative screening.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2025-01-27 | **Initial calibration created.** n=120. Key findings: HOLD over-issuance at 75%; IT BUY weakness at -1.95%; score spread 3.23pp. Target: 40-45% HOLD, 35% BUY, 20-25% AVOID. |
| 2025-06-16 | **Major update.** n=521. Key findings: HOLD worsened to 78.1%; AVOID still broken at 1.0%; score spread compressed to 1.52pp; Consumer Discretionary replaced IT as worst BUY sector; APO (7.55) highest-score BUY was worst loss. Revised targets: 55-60% HOLD, 25-30% BUY, 12