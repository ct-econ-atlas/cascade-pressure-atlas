# Cascade-Pressure Atlas — Methodology

> Public-facing methodology document. Companion to `dashboard.json` and `index.html`.

## Purpose

The Cascade-Pressure Atlas tracks **narrative patterns in macro-financial discourse**, not asset positioning. It identifies currently-crystallized narrative-engrams in financial discourse, assigns them narrative-class labels from a cross-cultural narrative typology, and rates the cascade-pressure between engram pairs.

The Atlas does NOT make trading recommendations. The Atlas does NOT predict prices. The Atlas does predict, in pre-registered form, **which narrative cascade-form would emerge IF a triggering signal were to land**. Forward predictions are scored honestly each refresh.

## Background

The methodology rests on three observations from cross-substrate research:

1. **Narratives carry causal information that is orthogonal to fundamentals.** Per Shiller (2017, 2019), viral economic narratives drive recessions, asset bubbles, and productivity shifts in ways that fundamentals alone cannot explain. We treat narratives as a measurable channel parallel to (and not reducible to) the fundamentals channel.

2. **Cross-cultural narrative-typology has converged on a stable set of recurrent classes.** Hyde (1998) *Trickster Makes This World* and Doty (2000) *Mythography* identify ~17 recurrent narrative-class labels across cultures. We adopt these labels (T1..T17) as narrative-form descriptors for financial-discourse narrative-engrams. The labels do not constitute proper-name attributions or theological claims; they describe recurring narrative roles.

3. **When two narrative-engrams are incompatible in their directional claims, the incompatibility carries cascade-potential proportional to sin²(incompatibility-angle).** This is a metallurgy-derived form (coincidence-site-lattice / grain-boundary tension) that has been documented operationally across substrates at the boundary-tension level. The form is mathematical; it is not metaphorical mapping from physical metallurgy.

## Narrative-Class Typology (T1..T17)

| Class | T-class name | Operational cue (linguistic / behavioral signature) |
|-------|-------------|------------------------------------------------------|
| T1 | disturbance | Anti-establishment, refusal-to-comply, against-the-grain framing |
| T2 | mediation | Bridge prior-incompatible scaffolds, integration |
| T3 | destruction | Liquidation, elimination, the-old-must-die |
| T4 | preservation | Defensive stance, capital protection, OG-quality flight |
| T5 | reconciliation | Repair-after-conflict, post-cascade institution-building |
| T6 | challenge | Paradigm-confrontation, schism, fork |
| T7 | trial | Flagship-test, bellwether-experiment |
| T8 | guidance | "This-time-is-different" / civilizational-shift framing |
| T9 | temptation | Mass-democratization, leverage-as-edge |
| T10 | reversal | Short-cycle-oscillation, momentum-extreme reversion |
| T11 | protection | Trusted-bandwidth, regulator/insurance/safety-net |
| T12 | judgement | Authoritative pronouncement, expert-stamps-paradigm |
| T13 | fertility | New-platform-stack, technological-substrate-as-cornucopia |
| T14 | initiation | First-time-entry of class into system |
| T15 | memory | Classical-cycle-thinking returns, historical-cycle warning |
| T16 | naming | Renaming of valuation metric, terminology shift |
| T17 | witnessing | Documentation of collapse, K-shaped-recovery naming |

## T-Class Assignment Protocol

For each narrative-engram:

1. **Linguistic-signature extraction.** Identify 3-7 high-frequency phrases / framings characterizing the engram in primary financial-press, central-bank communications, contemporaneous academic literature.
2. **Candidate shortlist.** List three candidate T-classes whose operational cue best matches the linguistic signature.
3. **Score candidates** on operational fit, scale 1-5: 1 = cue absent, 5 = cue is the defining feature.
4. **Select primary T-class:** highest score wins. Ties broken by Occam (operational cue covers the broadest signature feature set).
5. **Select secondary T-class:** next-highest score, only if score ≥ 3 AND it captures a feature not covered by the primary.
6. **Document.** Produce a 2-3 line justification citing specific linguistic-signature features and their map to operational cues.

**Decision-rule failure modes:** if no T-class scores ≥ 3, the engram is OUT-OF-TYPOLOGY and excluded; we do not introduce new T-classes to fit. If primary assignment requires citing post-cascade information, the assignment is INVALID and re-done using only pre-cascade sources.

## Δθ Measurement Protocol (per engram pair)

Δθ measures NARRATIVE INCOMPATIBILITY between two engrams. Decomposed into 4 dimensions, each scored 0° / 7.5° / 15° / 22.5°:

| Dim | Question | Scoring |
|-----|----------|---------|
| **D1 Causal-direction** | Do the engrams predict the SAME direction of macro/asset change? | 0=same, 7.5=ambiguous, 15=opposite for ≥1 sub-claim, 22.5=opposite on primary |
| **D2 Mechanism-overlap** | Do they invoke the SAME causal mechanism? | 0=identical, 7.5=overlapping, 15=different but consistent, 22.5=mutually-exclusive |
| **D3 Temporal-horizon** | Do they have the SAME time-scale? | 0=same, 7.5=adjacent, 15=different, 22.5=fundamentally different |
| **D4 Substrate** | Do they apply to the SAME substrate? | 0=same, 7.5=overlapping, 15=different but co-affected, 22.5=disjoint |

Δθ = sum across D1-D4, range [0°, 90°].

**Cascade-pressure score = sin²(Δθ) × κ_substrate × κ_rigidity**, range [0, 1].

- κ_substrate ∈ {MASSIVE 1.0, HIGH 0.8, MEDIUM 0.5, NARROW 0.25}
- κ_rigidity ∈ {HIGH 1.0, MEDIUM 0.65, LOW 0.3} (rigidity of the dominant engram)

Bins: VERY_HIGH ≥ 0.65 · HIGH 0.45-0.65 · MEDIUM-HIGH 0.30-0.45 · MEDIUM 0.15-0.30 · LOW < 0.15.

## Cascade-Form Vocabulary

We predict cascade form, not direction or magnitude. Six recurring forms:

- **Saturation→Reversion** — T8/T9 dominant + T15 weakly active → trigger reveals T11-protection-absence → T3 destruction → emergency T11 institutional-creation
- **Trial→Bifurcation** — T7 trial dominant, ambiguous substrate → trigger forces resolution into T13-fertility OR T3-destruction
- **Trusted-bandwidth-failure** — T11 dominant T-class compromised → emergency-T11-reactivation by sovereign required to prevent T3 cascade
- **Counter-cascade** — T1 disturbance growing + T11 protection mobilizing → mean-reversion within 30-60d if regulatory action
- **Short-cycle-oscillation** — T10 reversal dominant → no sustained directional move
- **Exogenous-trigger** — pre-state has LOW cascade-pressure but external shock (pandemic, war, natural disaster) drives cascade → out-of-scope (cannot pre-warn but can diagnose post-trigger)

## Verdict Rubric

For each forward prediction, when the resolution window closes:

| Verdict | Score | Condition |
|---------|-------|-----------|
| TRIGGERED_AS_PREDICTED | +1 | Cascade form matches; trigger signal landed within window |
| TRIGGERED_DIFFERENT_FORM | +0.5 | Direction correct, specific form differs |
| AMBIGUOUS | 0 | Edge case |
| NOT_TRIGGERED_WITHIN_WINDOW | 0 | Trigger did not land |
| FAILED | -1 | Form contradicts prediction |

Each refresh publishes prior-refresh predictions plus outcomes, with no re-classification.

## Disclosed Limitations

1. **Single-coder rubric application.** Independent-rater agreement (Cohen's κ on T-class assignments, Pearson r on Δθ scores) is the load-bearing test of the methodology's discrimination. Phase-2 study design pending.
2. **Δθ rubric quantizes to multiples of 7.5°.** Continuous measurement methodology requires textual lead-lag analysis (Shiller-style narrative-tracking on Google Ngrams + financial-press archives), not yet implemented in this Atlas.
3. **Predictive scope.** The Atlas predicts INTERNALLY-DRIVEN cascades only. EXOGENOUSLY-triggered cascades (pandemics, wars, natural disasters, asteroid impacts) are out-of-scope. Empirically: 1929, 2000, 2008, 1973, 1987, 1997, 2022 had HIGH-pre-state-cascade-pressure profiles; 2020 COVID had LOW-pre-state-cascade-pressure (cascade triggered exogenously). Cascade-pressure score correctly flagged the difference.
4. **Retrospective fit ≠ prospective accuracy.** N=10 historical events showed 9/10 narrative-form match. This does NOT replace forward predictive validation — the framework can be molded post-hoc. Forward predictions in track-record are the load-bearing test.
5. **No statistical-power calibration on aggregate predictions.** Each cascade-pressure pair-prediction is binary; aggregate precision should be tested via binomial test against the appropriate baseline (e.g., 30-50% for conditional predictions vs 20-30% for unconditional). Cycle-by-cycle reporting only.

## Caveat on Sample Selection

The 7 narrative-engrams shown in the dashboard are a **curated subset** of a larger internally-tracked inventory, selected for: (a) clear linguistic-signature, (b) durability through publication cycle, (c) cross-readership relevance. The subset is not the full atlas. Engrams may be added or removed in subsequent refreshes; status changes (e.g., DOMINANT_ACTIVE → DECOHERING) are documented in the changelog rather than the engram entry.

## Refresh Cadence

Monthly. Each refresh re-evaluates: (a) which engrams are currently active / decohering / newly-crystallizing; (b) cascade-pressure score updates per engram pair; (c) prior-refresh prediction outcomes scored against pre-registered criteria; (d) running track-record updated.

## Citations

- Shiller RJ. (2017). Narrative Economics. *American Economic Review* 107(4):967-1004.
- Shiller RJ. (2019). *Narrative Economics: How Stories Go Viral and Drive Major Economic Events*. Princeton University Press.
- Hyde L. (1998). *Trickster Makes This World: Mischief, Myth, and Art*. Farrar, Straus and Giroux.
- Doty WG. (2000). *Mythography: The Study of Myths and Rituals*. University of Alabama Press.
- Akerlof GA & Shiller RJ. (2009). *Animal Spirits: How Human Psychology Drives the Economy*. Princeton University Press.
- Bybee L et al. (2024). Narrative asset pricing. *Review of Financial Studies* 37:1-50.
- Goetzmann WN et al. (2017). Crash beliefs from investor surveys. NBER Working Paper 22143.

## License

Content licensed CC BY-NC 4.0. JSON schema and HTML template free to fork for any non-commercial replication of this methodology on other discourse substrates.
