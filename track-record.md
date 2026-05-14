---
layout: default
title: "Track Record"
---

*Last updated: May 14, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 2,758 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 690 | +0.37% | 47.5% | +39.69% | -20.56% |
| HOLD | 1,688 | -0.01% | 47.2% | +62.52% | -81.92% |
| AVOID | 378 | +0.49% | 47.9% | +48.13% | -31.77% |

**Score Predictiveness:** Top-third scored stocks returned +0.37% vs. -0.02% for bottom-third — a **0.39pp spread**. Historical trajectory: 3.23pp → 1.52pp → 1.38pp → 2.08pp → 1.9pp → 1.76pp → 1.3pp → 1.09pp → 1.28pp → **0.39pp (n=2,758)**. **Catastrophic collapse below 1.0pp actionability threshold. Scoring system has lost predictive value.**

**Recommendation Distribution:** HOLD is 61.2% of all calls (1,688/2,758). BUY is 25.0% (690/2,758). AVOID is 13.7% (378/2,758). In the incremental ~814 reports since last calibration: estimated ~327 new BUYs (~40.2%), ~412 new HOLDs (~50.6%), ~75 new AVOIDs (~9.2%). **AVOID volume finally compliant at ~9.2%.** HOLD hit 50% floor. **BUY issuance exploded to ~40.2% — double the 15–20% target.** This is the primary driver of BUY signal collapse.

**BUY Signal: CRISIS — SIGNAL DESTROYED.** Average return collapsed from +1.38% to +0.37%; hit rate dropped from 56.5% to 47.5% (below coin-flip). The incremental ~327 BUY calls averaged approximately **-0.25% to -0.40%**, dragging cumulative performance to near-zero. **The BUY signal no longer generates alpha.** BUY-over-HOLD spread narrowed to **0.38pp** (from 1.23pp). At current performance, BUY is statistically indistinguishable from HOLD.

**AVOID Signal: FULLY BROKEN.** Average return +0.49% — AVOID-rated stocks OUTPERFORM BUY-rated stocks (+0.49% vs +0.37%). The recommendation hierarchy is **inverted**: AVOID (+0.49%) > BUY (+0.37%) > HOLD (-0.01%). This is a complete system failure. AVOID calls are being issued on stocks that subsequently rise more than BUY calls.

**HOLD:** Average return at -0.01%, hit rate 47.2%. Catastrophic tail worsened (CVNA -81.9%). HOLD is performing as expected — neutral — but the system's inability to differentiate BUY/AVOID from HOLD renders the entire recommendation framework non-functional.

## Identified Biases

### 1. BUY Volume Explosion Destroyed Signal Quality (Severity: EMERGENCY)
BUY issuance surged from ~18.7% to 25.0% cumulative, with the incremental batch at ~40.2%. The May 6 retrospective revision — which relaxed gates, lowered BUY thresholds to 6.0, and added anti-contrarian guidance — caused massive over-issuance. The system interpreted "don't miss rallies" as "call everything a BUY." Result: avg return collapsed from +1.38% to +0.37%, hit rate from 56.5% to 47.5%. **The May 6 calibration revision was catastrophically miscalibrated.** It solved a perceived "missed rallies" problem by destroying the BUY signal entirely.

### 2. Energy BUY Collapse (Severity: CRITICAL)
Energy BUYs: **-1.84% across 106 calls.** Previously +1.84% across 49 calls. The system issued 57 new Energy BUYs that averaged approximately **-5.0% to -6.0%**, completely inverting a former strength. This suggests the system chased a sector that was rolling over, likely issuing BUYs on commodity-sensitive names during a price downturn. Energy was a "priority BUY sector" per prior calibration — this designation must be revoked.

### 3. Consumer Discretionary BUY (Severity: CRITICAL — NINTH CONSECUTIVE)
Consumer Discretionary BUYs: **-1.35% across 18 calls.** Worsened from -0.88%. Gate conditions are either not being applied or are insufficient.

### 4. Materials BUY (Severity: CRITICAL)
Materials BUYs: **-3.89% across 10 calls.** Worst sector performance. The "cycle-aware gate" has failed to prevent losses.

### 5. Industrials BUY (Severity: CRITICAL — WORSENED)
Industrials BUYs: **-0.74% across 86 calls.** Nearly doubled from 46 to 86 calls — 40 new Industrials BUYs issued. Average worsened from -0.19% to -0.74%. **The relaxed gate from May 6 was exploited.**

### 6. Financials Concentration (Severity: HIGH)
Financials BUYs: **+0.09% across 216 calls.** This is 31.3% of ALL BUY calls, with near-zero returns. The 25% cap was not enforced. 216 BUY calls returning +0.09% is indistinguishable from random. The system has no edge in Financials.

### 7. Scoring System Failure (Severity: EMERGENCY)
Score spread collapsed to 0.39pp. The scoring system no longer meaningfully predicts returns. Likely causes: (a) the May 6 revision's cycle-adjusted valuation scoring and growth-exemption gates inflated scores for stocks that subsequently underperformed; (b) bottom-third scores being assigned AVOID (which then rallied) created an artificial floor on bottom-third returns; (c) score inflation across the board compressed differentiation.

### 8. AVOID on Momentum/Growth Names (Severity: HIGH)
RKLB: AVOID → +45.7%. BLMN: AVOID → +48.1%. CAR: AVOID → +38.0%. STRL: HOLD → +62.5%. The system continues to underrate high-momentum or recovery situations. However, the prior fix (May 6) overcompensated by making BUY too permissive rather than simply fixing AVOID scoring.

### 9. High-Conviction BUY Failures Persist
BMI (7.06 → -20.6%), TRMB (6.8 → -19.7%), APO (7.55 → -16.9%), LDOS (6.9 → -16.7%). High scores continue to produce severe losses in Industrials and Financials — sectors where the system demonstrably lacks edge.

## Lessons for Future Analysis

### EMERGENCY: Reverse May 6 Permissiveness

1. **BUY minimum score: 7.5 (standard) / 7.0 (exceptional circumstances only).** The 6.0 threshold from May 6 is revoked immediately. The data is unambiguous: relaxing BUY gates destroyed the signal. Every gate relaxation from May 6 that increased BUY volume is reversed.

2. **BUY volume target: 10–15%.** Reduced from 15–20%. The system MUST issue fewer BUYs. At current n=2,758, BUY calls are at coin-flip accuracy. The only path to recovery is extreme selectivity. Target: ~50–75 BUYs per 500 reports (10–15%), not 200+ (~40%).

3. **BUY "expectations gap" test — ELEVATED TO GATING.** Before issuing BUY, the system must identify a SPECIFIC, NON-CONSENSUS catalyst that is not yet reflected in price. "Strong fundamentals" is not a catalyst. "Secular tailwind" is not a catalyst. Acceptable catalysts: upcoming earnings where estimates are materially too low (with evidence), product launch with quantifiable TAM expansion, regulatory approval, restructuring with timeline. If no specific catalyst can be identified, the recommendation is HOLD regardless of score.

4. **BUY must have quantified upside ≥15%.** State a price target with explicit assumptions. If the upside math doesn't produce ≥15% from entry, it is a HOLD.

### Sector Prohibitions and Restrictions

5. **Materials: BUY PROHIBITED.** -3.89% across 10 calls. Insufficient sample to prove any gate works. All Materials candidates → HOLD until cumulative evidence of edge emerges from HOLD-rated Materials stocks rising.

6. **Consumer Discretionary: BUY PROHIBITED unless score ≥8.0 AND positive same-store sales AND FCF yield ≥5%.** -1.35% across 18 calls. De facto prohibition with narrow exception for exceptional cases.

7. **Industrials: BUY requires score ≥8.0 AND earnings revision momentum ≥20% (90-day).** -0.74% across 86 calls. The prior relaxed gate failed. Near-prohibition.

8. **Energy: BUY requires score ≥7.5 AND commodity price above 200-DMA AND positive earnings revisions.** Priority sector designation REVOKED. The -1.84% across 106 calls invalidates prior edge assumption. The system was chasing a deteriorating sector.

9. **Financials: HARD CAP at 15% of BUY calls (previously 25%).** +0.09% across 216 calls is zero alpha. Reduce exposure immediately. Score ≥7.5 required for Financials BUY.

10. **Priority BUY sectors (revised): Information Technology (+3.91%, 94 calls) and Communication Services (+2.24%, 34 calls) ONLY.** These are the only sectors with meaningful positive BUY returns at reasonable sample sizes. Health Care (+1.40%, 66 calls) is permitted but not prioritized.

### AVOID Signal Repair

11. **AVOID volume is now compliant (~9.2% incremental).** Do not change volume guidance. The problem is directional accuracy: AVOID stocks average +0.49%. 

12. **AVOID must NOT be issued on stocks showing positive price momentum (above 50-DMA AND above 200-DMA).** These are the AVOID calls that rally 30–50%.

13. **AVOID requires ALL of:** (a) declining revenue for ≥2 consecutive quarters, (b) negative earnings revisions (trailing 90 days), (c) identifiable structural impairment (not cyclical), (d) stock NOT already >25% below 52-week high. If any condition fails → HOLD.

14. **AVOID maximum score: 4.0.** Any stock scored ≥4.0 that triggers AVOID concerns should be HOLD with bearish lean, not AVOID. RKLB (4.7 → +45.7%) exemplifies: a 4.7 score is too high for AVOID — the scoring itself suggests the stock has merit.

### Scoring System Emergency Intervention

15. **Score spread at 0.39pp is non-functional.** Immediate changes: (a) Remove growth-exemptions from scoring gates — these inflated scores uniformly; (b) Valuation must constitute ≥25% of overall score weight — the cycle-adjusted valuation guidance caused the system to discount valuation for too many names; (c) Reintroduce mean-reversion penalty: stocks >50% above 200-DMA receive a -0.5 score adjustment; (d) Introduce "expectations embedded" penalty: stocks at >30x forward P/E with consensus growth >20% receive -0.5 score adjustment (the market already knows).

16. **Score-to-recommendation mapping (REVISED):** Score ≥8.0 in IT/Comms → BUY disposition. Score 7.5–8.0 in IT/Comms → evaluate for BUY with catalyst requirement. Score ≥8.0 in other sectors → evaluate for BUY with catalyst. Score <8.0 in weak sectors (Energy, Financials, Industrials, Materials, Consumer Discretionary) → HOLD regardless. Score ≤3.5 with all AVOID gates met → AVOID. Everything else → HOLD.

### HOLD as Default (Reinforced)

17. **HOLD floor: 65%.** Elevated from 55%. The data proves the system cannot differentiate BUY from HOLD at current volumes. HOLD is intellectually honest. HOLD with directional lean (bullish/bearish) provides information without the false precision of BUY/AVOID.

18. **When uncertain, HOLD.** The system's worst errors come from forced conviction. A HOLD with "bullish lean, would upgrade on earnings beat" is superior to a BUY that averages +0.37%.

## Areas of Strength

1. **Information Technology BUY remains the system's only reliable alpha source.** +3.91% across 94 calls. MU (+39.7%) exemplifies the archetype. This is the system's core competency — identifying mispriced tech with catalysts.

2. **Communication Services BUY.** +2.24% across 34 calls. Smaller sample but consistent positive returns.

3. **BUY downside containment intact.** Worst BUY: -20.56%. Compare to HOLD: -81.9%, AVOID: -31.8%. Whatever the system does in BUY selection, it avoids catastrophic blowups.

4. **AVOID volume compliance achieved.** After five consecutive failures, AVOID volume reached target (~9.2%). This proves the system CAN follow calibration directives when clearly stated.

5. **Validated AVOID calls show real skill when gates are met.** KLAR (-26.9%), CPB (-16.2%) demonstrate that properly gated AVOIDs on genuinely deteriorating businesses work. The problem is false positives, not inability to identify deterioration.

6. **Health Care BUY.** +1.40% across 66 calls. Modest but consistent positive returns with meaningful sample.

## Calibration Changelog

| Date | Entry |
|---|---|
| 2025-01-27 | Initial calibration. n=120. HOLD 75%, score spread 3.23pp. |
| 2025-06-16 | Major update. n=521. HOLD 78.1%, AVOID 1.0%, score spread 1.52pp. |
| 2025-07-15 | Update. n=539. Score spread 1.38pp. Cyclical ceiling introduced. |
| 2025-08-18 | Major update. n=829. AVOID volume 4×. Score spread rebounded to 2.08pp. |
| 2025-06-20 | Major update. n=1,360. BUY issuance collapsed. PIPR tail-risk exposed. |
| 2025-07-01 | Update. n=1,392. AVOID signal dilution flagged. |
| 2026-04-22 | Major update. n=1,576. AVOID signal collapsed. BUY strengthened to 61.1% hit rate. |
| 2026-04-27 | Major update. n=1,706. Score spread breached 1.0pp. BUY first degradation. |
| 2026-05-05 | Major update. n=1,944. BUY degradation escalated. Minimum score elevated to 7.0. |
| 2026-05-06 | Retrospective-driven revision. Gates relaxed for growth/inflection names. BUY threshold lowered to 6.0 for high-growth. Anti-contrarian guidance added. |
| 2026-05-14 | **EMERGENCY UPDATE. n=2,758.** Key findings: **(1) SYSTEM FAILURE: BUY signal destroyed — avg return +1.38% → +0.37%, hit rate 56.5% → 47.5% (coin-flip). Recommendation hierarchy INVERTED (AVOID > BUY > HOLD). The May 6 retrospective revision catastrophically over-corrected by relaxing all gates simultaneously, causing BUY issuance to surge to ~40% of incremental calls.** (2) Score spread collapsed to 0.39pp (from 1.28pp) — scoring system non-functional. (3) Energy BUY collapsed from +1.84% to -1.84% after 57 new calls into deteriorating sector. (4) Financials: 216 BUY calls at +0.09% — zero edge, massive concentration. (5) AVOID volume finally compliant at ~9.2% but directional accuracy still wrong (+0.49% avg). **(6) ONLY functional signal: IT BUY (+3.91%, 94 calls) and Comms BUY (+2.24%, 34 calls).** **Emergency directives: (a) BUY minimum score → 7.5; volume target → 10–15%; mandatory specific non-consensus catalyst; (b) Materials BUY PROHIBITED; Consumer Discretionary/Industrials near-prohibited; Energy priority REVOKED; (c) Financials hard cap → 15% of BUYs; (d) HOLD floor → 65%; (e) Score system emergency: restore valuation weight, remove growth-exemptions, add expectations-embedded penalty; (f) May 6 permissiveness FULLY REVERSED.** The system must accept that missing rallies is preferable to destroying signal quality through indiscriminate BUY issuance. |