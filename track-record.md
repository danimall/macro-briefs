---
layout: default
title: "Track Record"
---

*Last updated: March 17, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 539 reports with follow-up return data (expanded from 521 in prior calibration).

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 115 | +2.45% | 61.7% | +33.22% | -16.85% |
| HOLD | 415 | +1.48% | 60.7% | +33.92% | -23.19% |
| AVOID | 9 | -0.20% | 33.3% | +33.56% | -26.88% |

**Score Predictiveness:** Top-third scored stocks returned +2.35% vs. +0.96% for bottom-third — a 1.38pp spread. This continues the deterioration trend: 3.23pp (n=120) → 1.52pp (n=521) → 1.38pp (n=539). The scoring system retains directional signal but is weaker than every prior estimate. The spread is likely converging toward its true value somewhere in the 1.2–1.5pp range. Scores work, but modestly. Do not over-rely on score magnitude as a signal of conviction quality.

**HOLD Dominance — Marginal Improvement:** 77.0% of all calls (415/539) are HOLD, down from 78.1% in the prior period. BUY issuance is 21.3% (115/539), up slightly. AVOID issuance rose to 1.7% (9/539) — nearly doubling from 5 to 9, but still catastrophically low against the target of 12-18%. At this pace, the system would need to issue ~65-97 AVOID calls per 539 to hit the floor of its target range. It issued 9. The distribution problem remains the system's single largest structural flaw.

**BUY Alpha Has Eroded:** BUY calls average +2.45% vs. HOLD at +1.48% — a 0.97pp spread, down from 1.24pp at n=521 and representing consistent decay across measurement periods. Simultaneously, BUY hit rate declined from 64.2% to 61.7%. The system is issuing slightly more BUYs (115 vs. 109) with lower precision and lower average return. **Roughly 4 in 10 BUY calls lose money.** This is not a strong signal — it is a weak-to-moderate signal that needs sharpening, not expansion.

**AVOID Calls — Modest Progress, Still Unreliable:** The expanded 9 AVOID calls average -0.20%, an improvement over the prior +0.06% at n=5. Hit rate is 33.3% (3 of 9 stocks declined). This means 6 of 9 AVOID calls saw the stock rise — two-thirds of AVOID calls were wrong directionally. However, the validated AVOIDs include a -26.9% (KLAR) and -16.2% (CPB), showing the system can identify true losers when it commits. The MRNA catastrophe (+33.6% on an AVOID) remains the worst single call in the dataset by opportunity cost. The core problem is dual: AVOIDs are too rare AND too inaccurate when issued.

## Identified Biases

### 1. Critical Under-Issuance of AVOID Recommendations (Unchanged — Severity: Existential)
9 AVOID calls out of 539 reports (1.7%) is indefensible. The HOLD bucket contains stocks like NCLH (-23.2%, score 4.9), GPC (-20.5%, score 6.25), POOL (-18.9%, score 6.3), and ZBRA (-18.3%, score 6.6) — all rated HOLD, all delivered devastating losses. The system's revealed preference is to avoid reputational risk by defaulting to HOLD rather than making a falsifiable negative call. This must be treated as the primary failure mode.

### 2. Consumer Discretionary BUY Calls Remain Destructive
Consumer Discretionary BUYs average **-1.54%** across 11 calls — still the only sector with a negative BUY average at meaningful sample size. The prior calibration flagged this; the system did not correct. Failed names (NCLH -10.5%) confirm the pattern: the system overweights brand narrative and market positioning while underweighting cyclical sensitivity, consumer balance sheet stress, and margin vulnerability. Every Consumer Discretionary BUY call issued since this bias was identified represents a known, documented failure to implement calibration.

### 3. High-Score Overconfidence on Cyclicals and Momentum Names
APO (score 7.55 → -16.9%) remains the system's worst BUY by both absolute loss and irony: the highest-conviction BUY was the worst-performing BUY. DDOG (6.93 → -11.8%), NCLH (6.08 → -10.5%), and ADBE (6.75 → -9.6%) reinforce the pattern. APO appears twice in the loss list (-16.9% and -8.8% on separate calls at scores 7.55 and 7.35), meaning the system doubled down on a losing thesis. Repeated high-conviction BUY calls on the same losing stock is a critical overconfidence pattern that requires a structural block.

### 4. HOLD Bucket Contains the System's Best Opportunities (Unchanged)
COIN (+29.8%, HOLD), FIG (+29.9%, HOLD), KEYS (+33.9%, HOLD) — three of the five best-performing stocks in the entire dataset were rated HOLD. The system's largest alpha leak is not bad BUY calls but missed BUY calls languishing in the HOLD bucket. The "Why Not BUY?" gate proposed in the prior calibration was either not implemented or was ineffective.

### 5. AVOID Mechanism Has a Contrarian Blind Spot and a Precision Problem
MRNA (AVOID, +33.6%) was a beaten-down name flagged AVOID near its bottom. Meanwhile, 6 of 9 AVOIDs rose in price. The system appears to issue AVOID on stocks it finds fundamentally unattractive without adequately considering whether negative sentiment is already fully priced. Conversely, validated AVOIDs (KLAR -26.9%, CPB -16.2%) tend to be names with genuine structural deterioration, not just poor fundamentals. **Lesson: AVOID should be reserved for deteriorating situations, not merely weak fundamentals at already-depressed prices.**

### 6. Score Predictiveness Continues to Weaken — Likely Structural
The spread decay (3.23 → 1.52 → 1.38pp) across expanding samples suggests the scoring rubric systematically overweights stable, backward-looking quality factors (moat durability, management track record, balance sheet strength) relative to forward-looking factors (sentiment inflection, catalyst timing, positioning/flow dynamics, mean reversion). The score differentiates good companies from bad companies — but that differentiation is only weakly correlated with forward returns over the analysis horizon.

## Lessons for Future Analysis

### Recommendation Distribution (Revised Enforcement)

1. **Hard floor for AVOID: any stock scoring ≤4.8 must be AVOID.** The prior threshold of ≤5.0 was not implemented. Lowering to 4.8 as a non-negotiable floor. Any override must cite a specific, dated catalyst (e.g., "FDA decision on March 15 with 60%+ approval probability per analyst consensus") — not a general narrative.

2. **Hard ceiling on HOLD: no more than 65% of calls.** The prior target of ≤60% was ignored. Setting 65% as the absolute ceiling, with a stretch target of 60%. Any reporting period where HOLD exceeds 65% should trigger automated review.

3. **BUY issuance target: 20-25%.** Current rate (21.3%) is within this range but precision is declining. Do not expand BUY issuance further until hit rate recovers above 65%.

### Sector-Specific Rules

4. **Consumer Discretionary: suspend BUY issuance unless three conditions are met simultaneously.** (a) Positive sequential same-store sales or comparable revenue growth, (b) FCF yield ≥5%, (c) consumer confidence index not in declining trend over trailing 3 months. This was recommended in the prior calibration and not enforced. It is now mandatory.

5. **Lean aggressively into proven BUY sectors.** Utilities (+8.74%, 5 calls), Materials (+7.88%, 2 calls), Communication Services (+4.40%, 11 calls), Health Care (+3.48%, 9 calls), and Industrials (+2.78%, 11 calls) all outperform the BUY average. The system should actively seek BUY opportunities in these sectors rather than defaulting to HOLD. When analyzing stocks in these sectors, explicitly ask: "Does this warrant a BUY?"

6. **IT BUY calls require valuation guardrails.** IT BUYs average only +1.44% across 22 calls — barely above the HOLD average of +1.48%. The IT BUY signal is essentially zero. Require FCF yield ≥3% or forward P/E below sector median for any IT BUY. High-multiple SaaS/cloud names (DDOG, WDAY, ADBE pattern) should carry a presumptive HOLD unless a discrete catalyst is identified with a timeline.

### Conviction and Scoring Rules

7. **Cyclical score ceiling: 7.0 maximum.** No stock with beta >1.3 or in cyclically sensitive sectors (asset management, airlines, cruise lines, housing, commodities) may receive a score above 7.0 unless macro indicators (PMI >52, yield curve positive, unemployment stable/declining) are explicitly documented as supportive. APO at 7.55 was reckless.

8. **No repeat high-conviction BUY on a losing name within 6 months.** APO was issued BUY twice (7.55 and 7.35), losing both times. If a BUY call results in a loss exceeding 5%, the system must wait at least 6 months and document what has materially changed before re-issuing BUY. "Doubling down" on a losing thesis is the system's single most embarrassing pattern.

9. **Mandatory "Why Not BUY?" documentation for any HOLD scoring ≥6.2.** Lowered from 6.5 to capture more of the missed-BUY population (KEYS 6.25, GPC 6.25, POOL 6.3 were all in the 6.2-6.5 range). The documented reason must be specific and falsifiable, not "valuation appears full" or "limited near-term catalysts."

### AVOID Calibration

10. **Before issuing AVOID on any stock trading >30% below its 52-week high, require explicit contrarian rebound analysis.** Check: (a) short interest >15% of float (potential squeeze), (b) insider buying in trailing 90 days, (c) whether consensus estimates have already been cut ≥20% (negative priced in). If 2 of 3 conditions are met, default to HOLD, not AVOID. MRNA was the lesson. Do not repeat it.

11. **AVOID should target deteriorating trajectories, not static weakness.** Validated AVOIDs (KLAR -26.9%, CPB -16.2%, TSLA -3.0%) share a feature: worsening operational metrics or structural headwinds. Failed AVOIDs (MRNA +33.6%, CVNA — which has since rallied massively in the broader market) were cheap-for-a-reason names where the reason was already reflected in price. Score for trajectory, not level.

## Areas of Strength

1. **BUY calls still generate positive alpha.** Even at a reduced 0.97pp spread over HOLD, across 115 calls this is a meaningful and consistent edge. The BUY mechanism works. The priority is sharpening it, not abandoning it.

2. **Sector expertise in Financials is the system's most reliable signal.** BUY average of +2.33% across 35 calls — the largest sample of any sector. This is a battle-tested competence. Financials BUY calls should be the system's bread and butter.

3. **Utilities, Communication Services, Health Care, and Industrials BUYs are strong.** Ranging from +2.78% to +8.74% average returns. Small samples for some (Utilities 5, Materials 2), but the pattern is consistent enough to exploit more aggressively.

4. **DELL BUY (+33.2%, score 6.8) remains the model call.** Fundamental quality + secular catalyst (AI infrastructure) + reasonable entry valuation. This template — quality business at fair price with identifiable structural tailwind — should be the explicit checklist for every BUY.

5. **Downside containment on BUY is acceptable.** Only 5 of 115 BUY calls lost >5%. Median BUY loss is moderate. The system generally avoids catastrophic BUY errors. APO is the outlier, and structural fixes (cyclical ceiling, no-repeat rule) should prevent recurrence.

6. **AVOID accuracy is improving with sample size.** Moving from +0.06% average (n=5) to -0.20% (n=9) shows directionality. Validated AVOIDs (KLAR -26.9%, CPB -16.2%) demonstrate the system can identify true losers. The mechanism needs volume and precision, not replacement.

7. **Score remains directionally valid.** 1.38pp spread is real and durable. Top-third stocks outperform. The scoring framework is a sound foundation that needs supplementation with forward-looking factors, not overhaul.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2025-01-27 | **Initial calibration created.** n=120. Key findings: HOLD over-issuance at 75%; IT BUY weakness at -1.95%; score spread 3.23pp. Target: 40-45% HOLD, 35% BUY, 20-25% AVOID. |
| 2025-06-16 | **Major update.** n=521. Key findings: HOLD worsened to 78.1%; AVOID still broken at 1.0%; score spread compressed to 1.52pp; Consumer Discretionary replaced IT as worst BUY sector; APO (7.55) highest-score BUY was worst loss. Revised targets: 55-60% HOLD, 25-30% BUY, 12-18% AVOID. |
| 2025-07-11 | **Incremental update.** n=539. Key findings: (1) BUY alpha eroded further to 0.97pp spread over HOLD (from 1.24pp), hit rate declined to 61.7% — ~4 in 10 BUY calls lose money; (2) AVOID sample doubled to 9 but still only 1.7% of calls, average improved to -0.20%; (3) Score predictiveness continued decay to 1.38pp — likely converging on true value near 1.2-1.5pp; (4) Consumer Discretionary BUY bias uncorrected despite prior flagging; (5) APO confirmed as repeat-offender overconfidence pattern (two losing BUY calls). **New/tightened directives:** AVOID floor lowered to score ≤4.8 (from ≤5.0); HOLD ceiling set at 65% (from 60%); IT BUY requires FCF yield ≥3% or below-median P/E; "Why Not BUY?" gate lowered to score ≥6.2 (from ≥6.5); no-repeat BUY rule on losing names within 6 months; contrarian rebound analysis mandatory for AVOID on stocks >30% below 52-week high. **Consumer Discretionary BUY suspension codified as mandatory, not advisory.** Distribution targets revised to: ≤65% HOLD, 20-25% BUY, ≥10% AVOID. Prior targets were aspirational and ignored; these are enforceable minimums/maximums. |