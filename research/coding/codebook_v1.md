# Codebook v1 — Directed Qualitative Content Analysis

*Draft for author review and pilot testing (Stage 9). Deductive codes derived from the
Literature Review (`thesis/2_Literature_Review.md`) and the approved source corpus —
not invented ad hoc. Every code cites the source(s) that operationalise it. This will
be refined into Codebook v2 after pilot coding one H&M and one Inditex report on
matched sections (climate, materials, circularity, supply chain, targets/progress),
per `PROJECT_PLAN.md` Stage 9.*

## 1. Unit of analysis

A **coding unit** is a discrete passage — typically one sentence to one short paragraph,
or one table/graphic with its caption — that makes a claim, commitment, target,
disclosure, or omission-relevant statement about environmental/sustainability practice
in a corporate report. Units are identified by meaning (a bounded claim), not by fixed
sentence/word counts, following the deductive logic of directed content analysis:
codes are established *before* reading the reports, from Institutional Theory and the
supporting concepts, and applied to whatever unit of text carries that meaning (Kibiswa,
2019 — general principle; procedural specifics pending full-text access, see
`research/source_notes/S14_Kibiswa_2019.md`).

A unit may receive **more than one code**: an institutional-pressure code AND a
response code (RQ1) AND zero or more greenwashing-indicator codes (RQ2) are not
mutually exclusive layers.

## 2. RQ1 codes — Institutional Pressure Type

Applied to a unit only when it explicitly or clearly implicitly references an
*external* driver for the disclosed practice or claim. A unit with no such reference
is not coded on this dimension (NONE).

| Code | Definition | Textual signal to look for | Literature anchor |
|---|---|---|---|
| **COERCIVE** | The claim/action is framed as a response to a regulatory, legal, or mandatory requirement. | Explicit reference to EU CSRD/ESRS, the Green Claims Directive, the EU Strategy for Sustainable and Circular Textiles, national/EU consumer-protection rulings (e.g. the ACM case), or other binding legal/regulatory obligation. | Latif et al. (2020) validates coercive pressure as a separately measurable construct; Álvarez-Etxeberria et al. (2023) and Manshoven & Van Opstal (2022) document EU regulatory anticipation in disclosure behaviour. |
| **NORMATIVE** | The claim/action is framed as conforming to professional standards, industry norms, or stakeholder/societal expectations of appropriate conduct — not a legal mandate. | References to industry associations, voluntary standards/certifications, "responsible business conduct," stakeholder expectations, NGO benchmarks treated as a norm to meet. | Fraser & van der Ven (2022) operationalise "domestic norms about appropriate corporate conduct" as a driver of transparency; Bernini & La Rosa (2024) situate normative pressure within the institutional triad. |
| **MIMETIC** | The claim/action is framed with reference to peers/competitors or "industry practice," suggesting imitation under uncertainty rather than an independent standard. | "In line with industry leaders," explicit competitor/peer comparison, adoption of a certification/target because peers have adopted it, benchmarking language. | Álvarez-Etxeberria et al. (2023) document mimetic isomorphism as disclosure convergence toward sector leaders ahead of regulation. |
| **NONE** | No external driver referenced; purely internal/operational statement. | — | — |

## 3. RQ1 codes — Corporate Response Type

Applied to a unit describing an action, target, or commitment (whether or not an
institutional-pressure code was also applied).

| Code | Definition | Textual signal | Literature anchor |
|---|---|---|---|
| **SUBSTANTIVE** | Concrete, measurable, verifiable action: specific target, quantified outcome, named third-party verification/audit, or dated milestone with reported progress. | Numbers, percentages, dates, named certifying/auditing body, year-over-year comparable data. | Papa et al. (2024) and Loko & Schiehll (2025) operationalise substantive response as measurable KPI movement, not narrative alone. |
| **SYMBOLIC** | Narrative or aspirational language without measurable specifics; commitment framed in values/vision terms rather than verifiable steps. | "Committed to," "striving for," "aims to lead," vague futures ("by 2030 we will..." with no interim metric or baseline), imagery/design emphasis without accompanying data (executional greenwashing per de Freitas Netto et al., 2020). | Montgomery et al. (2024); Gatti et al. (2019) "grey zone" of unaudited voluntary disclosure. |
| **MIXED** | A real, verifiable action is described, but its framing/scope is exaggerated beyond what the action actually covers, or only partial follow-through is reported against an earlier commitment. | A genuine metric present, but qualified by scope-narrowing language ("in select markets," "pilot program") not disclosed prominently; a prior target restated without progress data. | Dzhengiz et al. (2023) rebound-type logic (real per-unit gain, absolute volume still rising); Garcia-Torres et al. (2017) "orphan issues" (materially important topic addressed only nominally). |

## 4. RQ2 codes — Greenwashing / Selective-Disclosure Indicators

These are the eight indicators locked in `CLAUDE.md` §1. **Golden rule: a unit is never
coded on this dimension merely for sounding promotional.** Each code requires an
identifiable textual or cross-referential basis, not a tone judgment.

| Code | Definition | How to identify it | Literature anchor |
|---|---|---|---|
| **MISMATCH** | The claim contradicts other evidence documented elsewhere in the same or a comparable document (about actual practice, not just wording). | Cross-reference against another passage, an earlier/later report, or a context document (EU Textiles Strategy, ACM decision, NGO assessment). | Bernini & La Rosa (2024) "misleading-disclosure" (active mismatch) vs. "selective-disclosure" (omission). |
| **OMISSION** | A materially relevant negative topic is absent from an otherwise detailed disclosure on the same theme. Requires benchmarking against a reference point (the firm's own materiality matrix, an external framework like the SDGs, or a topic the other case company discloses). | Compare disclosed topics against a materiality/SDG checklist (method precedent: Garcia-Torres et al., 2017, "orphan issues"). | Nemes et al. (2022) integrated assessment framework; Garcia-Torres et al. (2017). |
| **UNCLEAR BOUNDARY** | The claim's scope (which products, markets, subsidiaries, suppliers, timeframe) is not specified, making it unfalsifiable or non-comparable. | Absence of scope qualifiers on an otherwise strong claim ("our products are sustainable" without % or product line named). | de Freitas Netto et al. (2020) firm-level vs. product-level greenwashing distinction. |
| **DISPROPORTIONAL EMPHASIS** | The prominence given to a claim (space, visual design, headline placement, repetition) is disproportionate to its underlying materiality or quantitative significance. | Compare page/visual space devoted to a topic against its share of the firm's own materiality matrix or its quantitative weight (e.g. % of RASs on a topic, per Garcia-Torres et al.'s method). | Garcia-Torres et al. (2017) — Innovation as most material issue yet ~3.54% of coded action statements. |
| **INCONSISTENT METRIC** | A reported metric's definition, baseline, scope, or unit changes across years or reports without explanation, hindering comparability. | Compare the same named metric (e.g. "recycled materials share") across the four years in the corpus; flag redefinitions. | Papa et al. (2024) narrative-vs-KPI gap methodology. |
| **CONTRADICTION** | Two statements within the same report, or across the same company's reports, directly conflict. | Internal cross-reference within the coding matrix (see §6). | Bernini & La Rosa (2024); Gatti et al. (2019). |
| **WEAK SUBSTANTIATION** | A claim is made without supporting data, methodology disclosure, or third-party verification. | Absence of a cited data source, audit statement, or methodology footnote for a specific factual claim. | Spaniol et al. (2024) — "unsubstantiated" as a constitutive attribute of greenwashing. |
| **EXTERNAL CHALLENGE** | The claim is contradicted or challenged by an external, independent source (NGO report, media investigation, regulatory decision such as the ACM ruling). | Cross-reference against `resources/document_corpus.md` context documents (Stage 4, pending). | Dhanjee et al. (2026) — corporate SDG claims vs. independent media coverage. |

## 5. RQ2 codes — Competitive Pressure Signals

| Code | Definition | Textual signal | Literature anchor |
|---|---|---|---|
| **PEER BENCHMARKING** | Explicit comparison or reference to a named or implied competitor's practice. | "Unlike other retailers," "ahead of the industry," direct competitor naming. | Álvarez-Etxeberria et al. (2023) peer-driven disclosure convergence. |
| **COMPETITIVE FRAMING** | Claim framed in market-leadership or differentiation terms rather than compliance/legitimacy terms. | "Industry-leading," "first to," "pioneering." | Lee & Lee (2022) — competitive signalling logic. |
| **PROPRIETARY WITHHOLDING** | A cross-case, not per-unit, judgment: granular data disclosed by one firm is conspicuously absent from the comparable disclosure of the other, in a category plausibly competitively sensitive (e.g. supplier-level pricing, sourcing-cost data). | Applied at the cross-case comparison stage (Ch.4.4), not during within-document coding. | Lee & Lee (2022) proprietary-cost hypothesis. |

## 6. Decoupling axis (cross-cutting, supports RQ1)

| Code | Definition | Literature anchor |
|---|---|---|
| **POLICY-PRACTICE DECOUPLING** | A stated policy, target, or commitment is documented, but no corresponding implementation evidence appears anywhere in the same report or subsequent-year reports. | Loko & Schiehll (2025) — internal-action vs. external-endorsement measurement framework. |
| **MEANS-ENDS DECOUPLING** | Implementation activity is described, but it is disconnected from, or insufficient to plausibly achieve, the stated outcome/goal it is attached to. | Papa et al. (2024) — narrative-disclosure gains without matching non-carbon KPI gains. |

## 7. Coding matrix (per-unit row template)

Matches the structure already specified in `PROJECT_PLAN.md` Stage 10:

| Company | Year | Document | Page | Topic | Extract (verbatim/paraphrase) | Institutional Pressure Code | Response Code | Greenwashing Indicator Code(s) | Competitive Signal Code(s) | Decoupling Code | Evidence (what supports the code) | Counter-evidence (any disconfirming material in the same document) | Interpretation (cautious, one sentence) | RQ |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|

Four separate matrices per Stage 10: H&M 2022–2025; Inditex 2022–2025; cross-case
institutional pressures; cross-case competitive pressure and disclosure.

## 8. Coding procedure notes

1. Read a full section (not isolated sentences) before coding, to correctly judge
   OMISSION, DISPROPORTIONAL EMPHASIS, and CONTRADICTION, which require comparing a
   unit against the surrounding or cross-document context.
2. Apply RQ1 codes (pressure + response) and RQ2 codes (indicators + competitive
   signals) independently — a unit can be SUBSTANTIVE with zero greenwashing
   indicators, or SYMBOLIC with several, or (rarely) SUBSTANTIVE yet still flagged
   DISPROPORTIONAL EMPHASIS if a minor verified action is given outsized prominence.
3. Always log counter-evidence in the same row, per the negative-case-analysis
   requirement in `thesis/3_Methodology.md` §3.1 design logic — do not only record
   confirming instances.
4. **Never apply a greenwashing-indicator code on tone alone.** If no concrete
   indicator basis exists, leave the RQ2 indicator cell blank, even if the passage
   reads as promotional.
5. Page-precise coding requires the report PDFs (still pending). This codebook does
   not require re-derivation once PDFs arrive — pilot coding (Stage 9) will test
   these definitions against real text and refine them into v2, not replace them.

## 9. Known gaps to test in pilot coding (Stage 9)

- Whether COERCIVE/NORMATIVE/MIMETIC are cleanly distinguishable in practice, or
  frequently co-present in a single unit (the Literature Review already flags that
  mimetic and coercive pressures are often entangled — Álvarez-Etxeberria et al., 2023;
  Manshoven & Van Opstal, 2022).
- Whether the OMISSION code is workable without a pre-built materiality-matrix or
  SDG-mapping reference for H&M and Inditex specifically (Garcia-Torres et al.'s method
  requires constructing this — may need to be built as a preparatory step before full
  coding, not invented ad hoc during coding).
- Whether PROPRIETARY WITHHOLDING is codeable at all without supplier-level data that
  may not appear in either company's public sustainability reports.
