---
layout: default
title: "Track Record"
---

*Last updated: April 6, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 1,360 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 153 | +2.02% | 56.2% | +33.22% | -16.85% |
| HOLD | 1,063 | -0.12% | 49.4% | +33.92% | -75.19% |
| AVOID | 142 | -0.67% | 38.7% | +38.05% | -28.61% |

**Score Predictiveness:** Top-third scored stocks returned +1.25% vs. -0.65% for bottom-third — a 1.9pp spread. Historical trajectory: 3.23pp (n=120) → 1.52pp (n=521) → 1.38pp (n=539) → 2.08pp (n=829) → **1.9pp (n=1,360)**. The spread has stabilized in the 1.9–2.1pp range across the last two large samples. Revised estimate of true spread: **1.8–2.1pp.** Bottom-third stocks now average **-0.65%**, deepening the negative signal from -0.22% at n=829. The scoring system is a confirmed, durable risk-identification tool. Low scores predict losses.

**Recommendation Distribution:** HOLD is 78.2% of all calls (1,063/1,360). BUY is 11.3% (153/1,360). AVOID is 10.4% (142/1,360). In the incremental ~531 reports since last calibration: estimated ~19 new BUYs (~3.6%), ~406 new HOLDs (~76.5%), ~104 new AVOIDs (~19.6%). **AVOID issuance has massively improved** — nearly 20% of the incremental batch. **BUY issuance has collapsed catastrophically** — under 4% of new reports. The system has swung from BUY over-caution to BUY near-paralysis. HOLD remains bloated.

**BUY Signal:** Average return held steady at +2.02% (vs. +1.98% at n=829). Hit rate declined slightly from 57.5% to 56.2%. The BUY-over-HOLD spread is now **2.14pp** (+2.02% vs. -0.12%), the widest ever recorded, because HOLD collapsed from +0.57% to -0.12%. **The BUY signal works.** It generates genuine, durable alpha. The problem is not BUY quality — it is BUY quantity. The system is leaving enormous alpha on the table by refusing to issue BUY calls. **43.8% of BUY calls lose money.** This is real, but the average positive BUY return substantially exceeds the average negative BUY return, creating a favorable asymmetry.

**AVOID Signal: Dramatically Improved.** 142 AVOID calls at -0.67% average return with 38.7% hit rate (i.e., 61.3% of AVOID calls correctly declined or stayed flat). This is a major improvement from 42.1% hit rate at n=38. The AVOID signal is now directionally reliable: AVOID-tagged stocks lose money on average while BUY stocks gain. The recommendation hierarchy is strongly monotonic: BUY (+2.02%) > HOLD (-0.12%) > AVOID (-0.67%). **AVOID is now a functioning signal.**

**HOLD Is Broken.** HOLD average return collapsed from +0.57% (n=829) to **-0.12%** (n=1,360). Hit rate fell from 53.4% to **49.4%** — literally worse than a coin flip. The range is +33.92% to **-75.19%**. HOLD is providing zero useful information. A category that averages negative returns with sub-50% hit rate across 1,063 calls is analytically worthless. PIPR (HOLD, -75.2%), ADMA (HOLD, -40.4%), and SNEX (HOLD, -27.3%) are catastrophic misclassifications that should have been AVOID. KEYS (HOLD, +33.9%) should have been BUY.

## Identified Biases

### 1. BUY Issuance Paralysis (Severity: CRITICAL — Upgraded from prior calibration)
BUY rate in the incremental batch was ~3.6%. This is the system's most damaging failure mode. With a 2.14pp edge over HOLD and positive average returns, every BUY that should have been issued but was classified HOLD represents destroyed value. The system has internalized "be selective with BUY" as "almost never issue BUY." This must be reversed immediately. **The data unambiguously shows BUY is the system's best-performing recommendation.** Suppressing it is the single largest source of error.

### 2. HOLD Remains a Dumping Ground (Severity: CRITICAL — Unchanged)
78.2% HOLD at n=1,360. Every calibration has flagged this. The problem is now quantifiably devastating: HOLD averages -0.12% with a -75.2% worst case. The HOLD bucket is absorbing stocks that should be BUY (upside leakage) and stocks that should be AVOID (downside catastrophes). PIPR at -75.2% is the single worst outcome in the entire dataset and was rated HOLD with a score of 5.97. This is an unacceptable classification failure.

### 3. Consumer Discretionary BUY Bias (Severity: High — Worsened)
Consumer Discretionary BUYs now show **-1.34%** across **12 calls** (up from 11). A new Consumer Discretionary BUY was issued despite three consecutive calibrations mandating suspension. The directive was violated. Average return remains the worst of any sector with meaningful sample size. **This is the fourth calibration flagging this issue.** The suspension must be enforced without exception.

### 4. AVOID Contrarian Blind Spot (Partially Mitigated but Still Present)
SEDG (AVOID, +37.0%), CAR (AVOID, +38.0%), and MRNA (AVOID, +33.6%) represent massive AVOID failures — beaten-down stocks that rebounded. However, the overall AVOID average is now -0.67%, meaning the signal works in aggregate. The issue is concentrated in high-volatility, deeply-depressed names. Validated AVOIDs like KLAR (-26.9%), CPB (-16.2%), SMCI (-28.6%), and PLAY (-27.2%) confirm the system excels at identifying structural deterioration. The problem is exclusively with contrarian rebounds from depressed levels.

### 5. HOLD Tail Risk Is Unmanaged
PIPR (-75.2%), ADMA (-40.4%), SNEX (-27.3%) — all HOLD-rated with scores of 5.97–6.48. The system fails to identify extreme downside risk in stocks it considers "neutral." Any HOLD with a score below 6.0 that experiences a drawdown beyond -20% represents a fundamental classification error. The "Why Not AVOID?" gate at ≤5.3 was too permissive. PIPR at 5.97 would have passed it easily.

### 6. Financials Concentration in BUY (Improved but Monitor)
Financials represent 35.3% of BUY calls (54/153). Average return is +0.88% — now significantly below the BUY average of +2.02%. Financials BUYs have degraded from +2.33% (n=35) → +1.42% (n=49) → **+0.88% (n=54)**. This is a confirmed mean-reversion pattern. The system's perceived Financials expertise was a small-sample artifact. Financials BUYs are now the weakest large-sample sector in the BUY portfolio.

### 7. High-Score Momentum/Cyclical Overconfidence (Confirmed)
APO (7.55 → -16.9%), DDOG (6.93 → -11.8%), LNN (6.85 → -12.5%), NCLH (6.08 → -10.5%) — all high-beta or cyclical names given elevated scores. The cyclical ceiling of 7.0 was previously mandated but APO at 7.55 predates it. Enforce rigorously.

## Lessons for Future Analysis

### Recommendation Distribution — Hard Rules (Revised)

1. **BUY floor: 15% minimum. Target: 20–25%.** The ~3.6% BUY rate in the incremental batch is the system's worst failure. BUY is the highest-returning recommendation. For every batch of 20 reports, at least 3 must be BUY. Any stock scoring ≥6.5 with identifiable catalyst within 6 months carries a **presumption of BUY** that must be explicitly overridden with a specific, falsifiable risk.

2. **HOLD ceiling: 60% absolute maximum.** Reduced from 65%. Current 78.2% produces a coin-flip recommendation averaging negative returns. HOLD must be the exception, not the default. If a stock doesn't merit BUY or AVOID, the analyst must ask: "Am I using HOLD because I'm uncertain, or because the stock is genuinely ambiguous?" Uncertainty about direction should trigger deeper analysis, not HOLD classification.

3. **AVOID floor: 15% minimum.** The incremental batch achieved ~19.6%. Lock in 15% as the floor; 20% is acceptable. Any stock scoring ≤5.0 carries a presumption of AVOID. Stocks scoring 5.0–5.5 require explicit justification to receive HOLD.

### Sector-Specific Rules

4. **Consumer Discretionary BUY suspension: MANDATORY. NO EXCEPTIONS.** Fourth calibration issuing this directive. A new violation was detected. Reinstatement conditions remain: (a) positive sequential comparable revenue growth, (b) FCF yield ≥5%, (c) consumer confidence not in declining 3-month trend. All three must be met and documented. If conditions cannot be verified, the call must be HOLD or AVOID.

5. **Financials BUY cap: ≤25% of BUY calls.** Tightened from 30%. Financials BUY average has degraded to +0.88%, well below the +2.02% BUY average. The system must diversify away from Financials. Financials BUYs require FCF yield or ROE meaningfully above sector median.

6. **Priority BUY sectors (proven alpha):** Utilities (+8.74%, 5 calls), Energy (+7.42%, 8 calls), Communication Services (+4.40%, 11 calls), Health Care (+3.82%, 12 calls). Actively seek BUY candidates in these sectors. When analyzing a stock in these sectors scoring ≥6.0, the default question is: "Why shouldn't this be BUY?"

7. **IT BUY guardrails remain in force.** IT BUYs average +2.05% across 24 calls — now at the BUY average but with high variance (includes DDOG -11.8%, ADBE -9.6%). Require FCF yield ≥3% or forward P/E below sector median for IT BUYs. High-multiple SaaS names carry presumptive HOLD unless growth acceleration is documented.

### Conviction and Scoring Rules

8. **Cyclical score ceiling of 7.0: ENFORCED.** No stock with beta >1.3 or in cyclically sensitive industries may exceed score 7.0 without explicit macro justification and scenario analysis documenting downside.

9. **"Why Not BUY?" gate: applies to all HOLD scores ≥5.8.** Lowered from 6.0. The analyst must cite a specific, falsifiable risk — not generic language like "valuation concerns," "macro headwinds," or "limited near-term catalysts." If no concrete risk can be articulated, the call must be BUY.

10. **"Why Not AVOID?" gate: applies to all HOLD scores ≤5.8.** Raised from 5.3. PIPR (5.97, -75.2%) proves the old threshold was far too permissive. Any HOLD scoring ≤5.8 must include explicit documentation of why AVOID is inappropriate, citing a specific positive factor (e.g., upcoming catalyst, insider buying, stabilizing fundamentals). Inability to cite a concrete positive factor mandates AVOID.

11. **No repeat BUY on a losing name within 6 months: ENFORCED.**

12. **HOLD tail-risk screen (NEW).** Any HOLD candidate in a sector or with characteristics associated with >20% drawdowns (high leverage, earnings volatility, small-cap illiquidity) must be flagged and either upgraded to BUY (if upside justifies risk) or downgraded to AVOID (if downside dominates). HOLD should not contain catastrophic risk names. PIPR, ADMA, and SNEX patterns must be prevented.

### AVOID Calibration

13. **Contrarian rebound screen: MANDATORY for stocks >30% below 52-week high.** Before issuing AVOID, check: (a) short interest >15%, (b) insider buying in trailing 90 days, (c) consensus estimates already cut ≥20%. If 2 of 3 are met, default to HOLD. SEDG (+37.0%) and CAR (+38.0%) would have been caught. This is the single most effective filter for preventing AVOID's worst failures.

14. **AVOID targets deterioration, not cheapness.** Before issuing AVOID, answer: "Is this company's trajectory worsening, or is it merely cheap/bad?" AVOID only deteriorating trajectories. Static weakness at depressed valuations is HOLD at worst. SMCI (AVOID, -28.6%) and KLAR (AVOID, -26.9%) are model AVOID calls — structurally deteriorating businesses. SEDG and CAR were beaten-down names where the bad news was already priced.

15. **AVOID is now a validated signal.** At -0.67% average return across 142 calls with 61.3% correct identification of declines, AVOID has earned credibility. Issue with confidence when deterioration criteria are met. Do not second-guess into HOLD.

### Score Interpretation

16. **Bottom-third scores predict losses: -0.65% average.** This is the system's most actionable signal. Any stock in the bottom third of scores should face a strong presumption of AVOID. Issuing HOLD for a bottom-third score stock requires explicit, documented justification.

17. **Score differentiates primarily on the downside.** Top-third at +1.25% and overall BUY at +2.02% suggest the score identifies losers more reliably than it identifies winners. Use scores defensively (screen out bad stocks) more than offensively (select best stocks). Catalyst analysis and sector context should drive BUY selection beyond what the score alone provides.

## Areas of Strength

1. **Recommendation hierarchy is monotonic and the spread is widening.** BUY (+2.02%) > HOLD (-0.12%) > AVOID (-0.67%). The BUY-to-AVOID spread is 2.69pp. This is a functioning, directionally correct system. The core analytical engine works.

2. **Score predictiveness is durable at ~1.9pp.** Five measurement points confirm a stable, genuine signal. Bottom-third stocks average -0.65%. This is a proven risk-management tool.

3. **BUY generates real alpha.** +2.02% average, 2.14pp over HOLD, 56.2% hit rate with favorable asymmetry (worst -16.85%, best +33.22%). Downside containment is strong: catastrophic BUY losses are rare. **This is the system's most valuable output — issue more of it.**

4. **AVOID is now validated at scale.** 142 calls averaging -0.67% with 61.3% directional accuracy. Massive improvement from the unreliable signal at n=38. The system has learned to identify underperformers. Validated AVOIDs (KLAR -26.9%, CPB -16.2%, SMCI -28.6%, PLAY -27.2%) demonstrate strong downside capture on structural deterioration calls.

5. **Sector specialization is proven.** Utilities (+8.74%), Energy (+7.42%), Communication Services (+4.40%), Health Care (+3.82%) — consistent outperformance across these sectors on BUY calls. These are genuine competence areas.

6. **DELL remains the model BUY.** Score 6.8, +33.22%. Quality business + secular catalyst + reasonable valuation. Continue using as the BUY archetype.

7. **AVOID volume achievement.** From 1.7% (n=539) to 4.6% (n=829) to **10.4% (n=1,360)**. The incremental batch hit ~19.6%. This is a genuine, measurable improvement in analytical courage. The same transformation must now happen for BUY.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2025-01-27 | **Initial calibration.** n=120. HOLD 75%, score spread 3.23pp. |
| 2025-06-16 | **Major update.** n=521. HOLD 78.1%, AVOID 1.0%, score spread 1.52pp. Consumer Discretionary flagged. |
| 2025-07-15 | **Update.** n=539. Score spread 1.38pp. APO double-loss flagged. Cyclical ceiling introduced. |
| 2025-08-18 | **Major update.** n=829. AVOID volume 4× to 38 calls. Score spread rebounded to 2.08pp. HOLD average collapsed to +0.57%. BUY issuance collapse to ~6.6% in incremental batch flagged as critical. |
| 2025-06-20 | **Major update.** n=1,360. **Key findings:** (1) BUY issuance collapsed to ~3.6% of incremental batch — most critical failure, upgraded to highest severity; (2) HOLD average collapsed to -0.12%, hit rate 49.4% — HOLD is now value-destructive; (3) AVOID validated at scale: 142 calls, -0.67% avg, 61.3% accuracy; (4) PIPR HOLD at -75.2% is worst call in dataset, exposed HOLD tail-risk blind spot; (5) Financials BUY degraded to +0.88%, no longer a strength; (6) Consumer Discretionary BUY violation detected despite three prior suspensions; (7) Score spread stable at 1.9pp, bottom-third at -0.65%. **Primary directive for next period: dramatically increase BUY issuance while maintaining quality. The system's most valuable signal is being suppressed.** |