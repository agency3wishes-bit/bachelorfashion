# Codebook v2 — Directed Qualitative Content Analysis

*Refines Codebook v1 (`research/coding/codebook_v1.md`) based on pilot coding of
matched FY2024 sections of both companies (`research/coding/pilot_coding_report.md`,
Stage 9). Per the Stage 9 stop rule, this is a targeted revision, not a rewrite —
only the changes justified by the pilot are made. Everything in Codebook v1 not
listed as changed below carries forward unchanged and is not reproduced in full here;
Stage 10 coders should use v1 for full table content plus the amendments in this file.*

## Changelog from v1

1. **§2 Institutional Pressure codes — multiple codes per unit now explicit.**
2. **§3 Response codes — MIXED split into two documented sub-patterns.**
3. **§4 RQ2 indicators — OMISSION split into two narrower sub-tests; DISPROPORTIONAL
   EMPHASIS given an explicit text-anchored operational test.**
4. **§9 (was Codebook v1 §9) — open questions updated with pilot results; two
   resolved, one deferred to Stage 10 as originally planned.**

No changes to: unit-of-analysis definition (v1 §1), RQ2 competitive-signal codes (v1
§5), the decoupling axis definitions (v1 §6), the coding matrix column template (v1
§7), or the general coding procedure notes (v1 §8), all of which the pilot found
workable as written.

## 1. Institutional Pressure codes (amends Codebook v1 §2)

Definitions, textual signals, and literature anchors for COERCIVE / NORMATIVE /
MIMETIC / NONE are unchanged from Codebook v1 §2. **New rule, confirmed necessary by
pilot rows P6, P7, and P9** (COERCIVE and NORMATIVE pressure co-present in the same
unit — an SBTi/ESRS-anchored target sitting alongside voluntary third-party standards
like Textile Exchange or Canopy):

> **A unit may carry more than one Institutional Pressure code.** Record every
> pressure type that is clearly, textually present — do not force a single choice.
> Where more than one applies, list them in order of textual prominence (the pressure
> given more space/emphasis in the unit listed first). MIMETIC/COERCIVE co-occurrence
> (flagged as a risk in the Literature Review, per Álvarez-Etxeberria et al., 2023)
> was not encountered in the pilot's 12 units and should be actively watched for at
> Stage 10, since peer-comparison language ahead of regulation is exactly the pattern
> the literature predicts and the pilot's topic/document selection did not happen to
> surface it.

## 2. Response codes (amends Codebook v1 §3)

SUBSTANTIVE and SYMBOLIC definitions are unchanged. **MIXED is split into two
sub-patterns**, both still coded as MIXED in the matrix's Response column, but the
Interpretation column must state which sub-pattern applies:

| Sub-pattern | Definition | Pilot example |
|---|---|---|
| **MIXED (scope-narrowed)** | The original v1 definition: a real, verifiable action, but its framing/scope is exaggerated beyond what the action covers, or scope-narrowing language is present without prominent disclosure. | Not observed in this pilot's 12 units — retained from v1 for Stage 10. |
| **MIXED (self-disclosed unfavourable trend)** | A real, verifiable metric is reported, and the *same unit* transparently disloses an unfavourable year-over-year or comparative data point alongside a favourable longer-term baseline comparison — the company is not hiding the unfavourable number, only presenting it next to a more flattering comparator. | Pilot rows P2 (H&M scope 3: −23.7% vs. 2019 baseline, but +3% vs. 2023) and P8 (Inditex renewable share: 92% in 2024 vs. 93% in 2023). |

**Rationale:** conflating these two sub-patterns risks mischaracterising transparent
self-disclosure of a setback as equivalent to scope manipulation, which would
overstate the greenwashing finding in Ch.4/5 beyond what the evidence supports —
directly relevant to the `CLAUDE.md` §1 scope boundary (coding communication
patterns, not asserting wrongdoing).

## 3. RQ2 Greenwashing Indicator codes (amends Codebook v1 §4)

MISMATCH, UNCLEAR BOUNDARY, INCONSISTENT METRIC, CONTRADICTION, WEAK SUBSTANTIATION,
and EXTERNAL CHALLENGE definitions are unchanged from Codebook v1 §4.

### 3.1 OMISSION — split into two sub-tests

The pilot (row P10) found the original single OMISSION definition too broad to apply
confidently without a pre-built materiality/SDG-mapping reference (Codebook v1 §9,
second open question). Replace the single test with two narrower, independently
applicable sub-tests. **Both remain coded as OMISSION** in the matrix; the
Interpretation column states which sub-test triggered it.

| Sub-test | Definition | How to identify it | Status |
|---|---|---|---|
| **Cross-case topic omission** | A topic covered in one company's disclosure for a given theme (e.g. a named metric, sub-target, or risk category) is entirely absent from the comparable section of the *other* company's report for the same or an adjacent reporting year. | Direct comparison of the two case companies' matched sections — no external framework required. Confirms or refutes at the Stage 10 cross-case matrix stage, but individual instances can be flagged during within-document coding. | Usable now, from the two corpora alone. |
| **Metric-denominator omission** | A company reports an absolute figure (tonnes, count, hours) without any accompanying scale/denominator (production volume, turnover, headcount, % of total), in a section where the *same company* discloses denominators for comparable metrics elsewhere in the same report. | Check whether the company's own reporting practice elsewhere in the document provides a percentage/share/rate for a structurally similar metric; if so, the absence of one here is internally inconsistent, not just under-detailed. | Usable now, from internal document consistency alone. |

The original, broader materiality/SDG-mapping-based OMISSION test (comparing
disclosed topics against an external materiality matrix or SDG checklist,
Garcia-Torres et al., 2017) remains available as a **Stage-10-only enhancement** if
time permits, but is not required for either sub-test above to be applied.

**Caution carried forward from the pilot:** row P10 shows that what looks like an
OMISSION candidate may actually be a metric-*type* difference (absolute tonnes vs.
percentage) rather than a withheld figure — do not code OMISSION merely because two
companies report a topic in different units. Apply the sub-tests above explicitly
before coding; if neither sub-test is met, leave the cell blank per the golden rule
in Codebook v1 §4.

### 3.2 DISPROPORTIONAL EMPHASIS — explicit operational test added

Definition unchanged from Codebook v1 §4. Pilot row P6 confirms the code captures a
real, codebook-relevant pattern, but needs a text-anchored trigger rather than a
qualitative "which figure is headlined" impression, to comply with the golden rule
(never code on tone alone). **Add this operational test:**

> Apply DISPROPORTIONAL EMPHASIS only when: (a) the unit's own narrative sentence(s)
> state a favourable, small-denominator or fast-moving figure, AND (b) the
> corresponding large-denominator or slow-moving figure for the *same underlying
> topic* is not stated in the same sentence or an immediately adjacent sentence,
> even though it is disclosed *somewhere* in the report (usually a data table). The
> code targets the gap between *narrative prominence* and *tabular disclosure*, not
> the mere existence of a table a reader could consult. If the large-denominator
> figure is unfavourable AND entirely absent from the report (not just
> narratively de-emphasised), code OMISSION instead (or in addition).

Pilot rows P6 (Inditex scope 1+2 vs. scope 3) and P7 (self-consumption vs. total
energy consumption) both satisfy this test and remain flagged as candidates pending
Stage 10 application across the full corpus, where a consistent pattern (not a single
instance) would be needed before this becomes a Results-chapter claim.

## 4. Known gaps — status after pilot (updates Codebook v1 §9)

| Open question | Status | Resolution |
|---|---|---|
| COERCIVE/NORMATIVE/MIMETIC cleanly distinguishable? | **Partially resolved** | Multi-code rule added (§1 above). COERCIVE/NORMATIVE co-occurrence confirmed workable; COERCIVE/MIMETIC entanglement not yet tested — watch for it at Stage 10. |
| OMISSION codeable without a materiality/SDG-mapping reference? | **Resolved for the pilot's purposes** | Split into two sub-tests (§3.1 above), both usable without external frameworks. The original heavier-weight method remains an optional Stage-10 enhancement, not a blocker. |
| PROPRIETARY WITHHOLDING codeable from public reports alone? | **Not yet tested — deferred as originally planned** | Confirmed to require the Stage 10 cross-case (Ch.4.4) comparison stage; no per-unit test was possible or expected from the FY2024 pilot topics. No change to Codebook v1's framing. |

## 5. New gaps surfaced by the pilot (carry into Stage 10)

- **MIXED sub-pattern labelling** (§2 above) must be applied consistently across all
  four full coding matrices — coders should re-read pilot rows P2 and P8 as worked
  examples before starting Stage 10.
- **Definitional non-comparability between the two companies' headline materials
  metrics** (H&M's "recycled materials" / "sustainably sourced materials" vs.
  Inditex's "lower-impact fibres," pilot row P9) must be flagged explicitly in
  Ch.4/4.4 wherever these headline percentages are juxtaposed — never state e.g.
  "H&M's 89% vs. Inditex's 73%" without the definitional caveat, or that would itself
  risk an INCONSISTENT METRIC problem in the thesis's own argument.
- **The Inditex 2024 PDF-page/internal-page offset** (documented in
  `research/coding/pilot_coding_report.md` §1: internal = PDF + 85 in part1, internal
  = PDF + 185 in part2) should be re-derived and recorded for the 2022, 2023, and 2025
  splits too, before Stage 10 full coding begins, to avoid repeating the page-location
  work per matrix row.
