---
layout: default
title: "Track Record"
---

*Last updated: May 25, 2026*

# AI Investment System Calibration Document

## Track Record Summary

**Overall Dataset:** 3,423 reports with follow-up return data.

| Recommendation | Count | Avg Return | Hit Rate (positive return) | Best | Worst |
|---|---|---|---|---|---|
| BUY | 810 | +0.19% | 46.4% | +39.77% | -27.06% |
| HOLD | 2,048 | -0.23% | 46.5% | +62.52% | -81.92% |
| AVOID | 563 | -0.47% | 44.8% | +48.13% | -42.23% |

**Score Predictiveness:** Top-third scored stocks returned +0.20% vs. -0.47% for bottom-third — a **0.67pp spread**. Historical trajectory: 3.23pp → 1.52pp → 1.38pp → 2.08pp → 1.9pp → 1.76pp → 1.3pp → 1.09pp → 1.28pp → 0.39pp → **0.67pp (n=3,423)**. Marginal recovery from the 0.39pp nadir but still well below the 1.0pp actionability threshold. Scoring system remains functionally impaired.

**Recommendation Distribution:** HOLD is 59.8% (2,048/3,423). BUY is 23.7% (810/3,423). AVOID is 16.4% (563/3,423). In the incremental ~665 reports since last calibration: estimated ~120 new BUYs (~18.0%), ~360 new HOLDs (~54.1%), ~185 new AVOIDs (~27.8%). **BUY volume has been corrected back toward target (~18%).** HOLD exceeded 50% floor. **AVOID volume surged to ~27.8% of incremental calls — massively exceeding the 9–12% target.**

**BUY Signal: CONTINUED CRISIS — FURTHER DEGRADED.** Average return declined from +0.37% to +0.19%; hit rate dropped from 47.5% to 46.4%. The incremental ~120 BUY calls averaged approximately **-0.75% to -1.0%**, continuing the downward drag. BUY volume correction has not yet translated into quality recovery. The signal remains statistically indistinguishable from noise.

**AVOID Signal: PARTIAL RECOVERY.** Average return flipped from +0.49% to **-0.47%**. This is directionally correct — AVOID stocks are now declining. The recommendation hierarchy is no longer inverted: BUY (+0.19%) > HOLD (-0.23%) > AVOID (-0.47%). The ~185 incremental AVOID calls appear to be performing well directionally, pulling the cumulative average into negative territory. However, hit rate (44.8%) means 55.2% of AVOIDs declined — only modestly better than random.

**HOLD:** Average return at -0.23%, hit rate 46.5%. Slight deterioration from -0.01%. Catastrophic tail persists (CVNA -81.9%). HOLD remains the neutral baseline.

**Hierarchy Status:** BUY (+0.19%) > HOLD (-0.23%) > AVOID (-0.47%). **Hierarchy restored.** Spread between BUY and AVOID is 0.66pp. Spread between BUY and HOLD is 0.42pp. These are positive signs but remain too narrow for actionable alpha generation.

## Identified Biases

### 1. BUY Signal Still Non-Functional Despite Volume Correction (Severity: EMERGENCY)
BUY volume has returned to ~18% of incremental calls, complying with directives. However, avg return continued declining to +0.19% with 46.4% hit rate — below coin-flip. The volume correction alone is insufficient; the *quality* of BUY selection has not recovered. Incremental BUYs are still losing money on average. The emergency gates (score ≥7.5, catalyst requirement) are either not being applied rigorously or are insufficient to identify winning stocks.

### 2. Consumer Discretionary BUY: CHRONIC FAILURE (Severity: CRITICAL — TENTH CONSECUTIVE)
Consumer Discretionary BUYs: **-2.75% across 28 calls.** Worsened dramatically from -1.35% (18 calls). 10 new BUY calls issued despite near-prohibition directive. These 10 new calls averaged approximately **-5.3%**. The prohibition was violated or the gate (score ≥8.0 + positive SSS + FCF yield ≥5%) was improperly applied.

### 3. Energy BUY: PERSISTENT DETERIORATION (Severity: CRITICAL)
Energy BUYs: **-1.24% across 124 calls.** 18 new Energy BUYs issued since last calibration, slight improvement in avg from -1.84% but still heavily negative. Priority sector revocation acknowledged but the system continues issuing Energy BUYs at meaningful volume.

### 4. Materials BUY: PROHIBITION VIOLATED (Severity: CRITICAL)
Materials BUYs: **-1.81% across 14 calls.** 4 new Materials BUY calls issued despite explicit prohibition. All are contributing to losses.

### 5. Industrials BUY: WORSENED (Severity: CRITICAL)
Industrials BUYs: **-1.02% across 94 calls.** 8 new calls issued; average worsened from -0.74%. The score ≥8.0 + earnings revision momentum gate is not preventing losses.

### 6. Financials Concentration Reduced But Still Zero-Alpha (Severity: HIGH)
Financials BUYs: **-0.12% across 245 calls.** 29 new calls issued. Average flipped slightly negative from +0.09%. 245 BUY calls is 30.2% of all BUYs — still double the 15% hard cap. The system continues to lack any edge in Financials.

### 7. AVOID Over-Issuance (Severity: MODERATE — NEW)
AVOID surged to ~27.8% of incremental calls (185 of 665). While AVOID directional accuracy improved (cumulative avg now -0.47%), the volume explosion risks diluting signal quality — the same failure mode that destroyed BUY in the May 6 era. The system over-corrected from under-issuing AVOID to flooding it. Best AVOID return of +48.13% (BLMN) still demonstrates false positives exist.

### 8. High-Conviction BUY Failures Continue
DOCS (7.03 → -27.1%), BMI (7.06 → -20.6%), TRMB (6.8 → -19.7%), APO (7.55 → -16.9%). Scores of 7.0+ continue to produce severe losses. APO at 7.55 (meeting the elevated threshold) still lost 16.9%. The score itself is not a reliable quality filter.

### 9. HOLD Catastrophic Tail Risk (Severity: MODERATE)
CVNA (-81.9%), PIPR (-75.2%), ADMA (-40.4%). HOLD is supposed to be neutral, but contains stocks that lose 40–80%. These suggest the system is placing genuinely impaired names in HOLD rather than AVOID — likely because AVOID gates were too restrictive in prior calibrations (now partially corrected with increased AVOID volume).

## Lessons for Future Analysis

### BUY Quality — Beyond Gates to Conviction Filtering

1. **BUY minimum score remains 7.5.** However, APO (7.55 → -16.9%) proves this alone is insufficient. **NEW: BUY requires BOTH score ≥7.5 AND at least one of:** (a) earnings estimate revisions trending up ≥10% over 90 days, (b) insider buying within 90 days, (c) identifiable catalyst within 60 days with specific timeline. Two of three preferred.

2. **BUY volume target: 10–12%.** Reduced from 10–15%. At 46.4% hit rate, the system is still issuing too many BUYs. Target: ~50–60 BUYs per 500 reports. The incremental ~18% is still above target.

3. **BUY "base rate" test:** Before issuing BUY, explicitly state what the market is pricing in and why the market is wrong. If the answer is "the market hasn't recognized strong fundamentals yet," that is insufficient — markets generally DO recognize strong fundamentals. The market must be wrong about something SPECIFIC.

4. **BUY maximum loss tolerance:** If a BUY thesis would result in >15% downside in a bear case, it should be HOLD with bullish lean. BUY should asymmetrically skew toward situations with limited downside and substantial upside.

### Sector Rules (Updated)

5. **Materials: BUY REMAINS PROHIBITED.** -1.81% across 14 calls. Prohibition violated 4 times. **ABSOLUTE prohibition — no exceptions regardless of score.** Any Materials candidate → HOLD maximum.

6. **Consumer Discretionary: BUY PROHIBITED — NO EXCEPTIONS.** -2.75% across 28 calls, worsening for 10 consecutive calibrations. The score ≥8.0 gate failed. **Complete prohibition.** The system has zero demonstrated ability to pick winners in this sector. All Consumer Discretionary → HOLD or AVOID only.

7. **Industrials: BUY requires score ≥8.5 AND positive earnings revisions ≥20% AND order backlog growth.** -1.02% across 94 calls. Near-prohibition elevated to effective prohibition.

8. **Energy: BUY requires score ≥8.0 AND WTI above 200-DMA AND positive earnings revisions ≥15%.** -1.24% across 124 calls. 124 Energy BUYs with negative returns represents massive capital destruction.

9. **Financials: HARD CAP at 10% of BUY calls.** Reduced from 15%. -0.12% across 245 calls is definitive proof of zero edge. At 10–12% total BUY volume (~50–60 calls per 500), this means ≤6 Financials BUYs per 500 reports. Score ≥8.0 required.

10. **Priority BUY sectors: Information Technology (+3.33%, 114 calls) and Communication Services (+1.82%, 38 calls).** IT return declined from +3.91% (20 new calls likely averaged lower) but remains the system's primary alpha source. Health Care (+1.01%, 77 calls) permitted at score ≥7.5. Consumer Staples (+0.90%, 15 calls) — small sample, permitted but not prioritized.

### AVOID Signal Calibration

11. **AVOID volume target: 12–15%.** Reduced from the ~27.8% incremental surge. The directional improvement is encouraging but over-issuance will eventually dilute quality. The system correctly identified the need for more AVOIDs but overshot.

12. **AVOID gates remain:** (a) declining revenue ≥2 quarters OR (b) negative earnings revisions (90-day) AND (c) identifiable structural impairment AND (d) stock NOT already >25% below 52-week high AND (e) NOT showing positive price momentum (above both 50-DMA and 200-DMA). Require 4 of 5 conditions met.

13. **AVOID maximum score: 4.0 MAINTAINED.** RKLB (4.7 → +45.7%) remains the cautionary example. If scored ≥4.0, use HOLD with bearish lean.

### Scoring System

14. **Score spread recovered to 0.67pp from 0.39pp — still non-functional but improving.** Continue: (a) valuation ≥25% of score weight; (b) no growth-exemptions from valuation penalty; (c) mean-reversion penalty for stocks >50% above 200-DMA (-0.5); (d) expectations-embedded penalty for >30x P/E with >20% consensus growth (-0.5). These appear to be partially working — maintain and monitor.

15. **Score-to-recommendation mapping (REVISED):** Score ≥8.5 in IT/Comms with catalyst → BUY. Score 8.0–8.5 in IT/Comms with catalyst → BUY if upside ≥15%. Score ≥8.5 in Health Care/Staples/Real Estate with catalyst → BUY. Score <8.0 in Energy/Financials/Industrials/Materials/Consumer Discretionary → HOLD regardless. Score ≤3.5 with AVOID gates met → AVOID. Everything else → HOLD.

### HOLD Posture

16. **HOLD floor: 70%.** Elevated from 65%. At 46.4% BUY hit rate and 44.8% AVOID accuracy, the system's conviction calls are barely better than coin-flip. HOLD with directional lean is the honest call for most stocks. A system with 70% HOLD, 10–12% BUY, 12–15% AVOID, and remaining as HOLD-with-lean is the target distribution.

17. **HOLD tail-risk screening:** Stocks in HOLD that have (a) >5x leverage, (b) >50% revenue decline trajectory, (c) going-concern language in filings should be re-evaluated for AVOID. The -81.9% CVNA loss in HOLD is unacceptable — this should have been flagged.

## Areas of Strength

1. **Information Technology BUY remains the sole reliable alpha source.** +3.33% across 114 calls. Slight dilution from +3.91% (94 calls) as 20 new calls were weaker, but still meaningfully positive. DDOG (+39.8%), MU (+39.7%) demonstrate the archetype: mispriced tech with clear catalysts.

2. **Communication Services BUY.** +1.82% across 38 calls. Consistent positive performance maintained.

3. **AVOID signal directional recovery.** Average return flipped from +0.49% to -0.47%. The recommendation hierarchy is restored. The calibration directives regarding AVOID gates appear to be working — validated calls include KLAR (-26.9%) and CPB (-16.2%).

4. **Recommendation hierarchy restored.** BUY > HOLD > AVOID in average returns. This was broken at last calibration. While spreads are narrow, the ordinal relationship is correct.

5. **BUY downside containment.** Worst BUY: -27.06%. Compare to HOLD: -81.9%. The system still avoids catastrophic blowups in BUY-rated names.

6. **Health Care BUY.** +1.01% across 77 calls. Modest but consistent.

7. **BUY volume compliance improving.** Incremental BUY rate returned to ~18%, down from the catastrophic ~40.2%. The system demonstrated it can follow volume directives.

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
| 2026-05-06 | Retrospective-driven revision. Gates relaxed. BUY threshold lowered to 6.0. Catastrophic miscalibration. |
| 2026-05-14 | EMERGENCY UPDATE. n=2,758. System failure: BUY signal destroyed, hierarchy inverted. May 6 reversed. |
| 2026-05-25 | **UPDATE. n=3,423.** Key findings: **(1) Recommendation hierarchy RESTORED: BUY (+0.19%) > HOLD (-0.23%) > AVOID (-0.47%). No longer inverted.** (2) BUY signal remains non-functional: avg +0.19%, hit rate 46.4% — below coin-flip. Volume correction achieved (~18% incremental) but quality not recovered. (3) Score spread partially recovered: 0.39pp → 0.67pp — still below 1.0pp threshold but trending correctly. (4) AVOID directional accuracy recovered: avg flipped from +0.49% to -0.47%. However, AVOID volume exploded to ~27.8% of incremental calls — must be reined back to 12–15%. (5) Chronic sector failures persist: Consumer Discretionary (-2.75%, worsened), Materials (-1.81%, prohibition violated), Energy (-1.24%), Industrials (-1.02%), Financials (-0.12%, 30% concentration). (6) Consumer Discretionary upgraded to ABSOLUTE BUY PROHIBITION — no gate has ever worked. Materials prohibition reinforced. (7) BUY volume target tightened to 10–12%. HOLD floor elevated to 70%. Score threshold for non-IT/Comms elevated to 8.5. (8) System's only alpha: IT BUY (+3.33%) and Comms BUY (+1.82%). All other sectors are noise at best, destructive at worst. **Primary directive: extreme selectivity. The system should issue BUYs only when it has genuine differentiated insight, overwhelmingly concentrated in Information Technology and Communication Services.** |