# Pilot Coding Report (Stage 9)

*Applies Codebook v1 (`research/coding/codebook_v1.md`) to matched FY2024 sections of
both companies, per `PROJECT_PLAN.md` Stage 9. Topics piloted: climate/emissions,
materials & circular economy, workers in the value chain — the three topics Stage 9
specifies. Feeds Codebook v2 (`research/coding/codebook_v2.md`), not the final coding
matrices (Stage 10), which will follow the same template across the full 2022–2025
corpus once v2 is locked.*

## 1. Scope of this pilot

| | H&M Group | Inditex |
|---|---|---|
| Document | Sustainability Progress Report 2024 | Group Annual Report 2024 — Consolidated Statement of Non-Financial Information and Sustainability Information (ESRS-structured) |
| Reporting period | 1 Dec 2023 – 30 Nov 2024 | 1 Feb 2024 – 31 Jan 2025 |
| Local file(s) | `data/reports/HM_Group_Sustainability_Progress_Report_2024.pdf` | `data/reports/Inditex_Sustainability_2024_part1.pdf` (E1 Climate change) + `part2.pdf` (E5 Resource use/circular economy, S1 Own workforce, S2 Workers in the value chain) |
| Sections read | pp. 8–28 (Climate, Water, Chemicals, Biodiversity, Materials/Circularity, Waste, Own workforce) | Internal pp. 143–166 (E1 Climate change), pp. 193–200 (E5 Resource use and circular economy), pp. 219–232 (S1 Own workforce, partial), pp. 250–265 (S2 Workers in the value chain) |

**PDF-page/internal-page offset confirmed for the Inditex 2024 3-part split**
(needed for Stage 10 full coding, not just this pilot): internal page = PDF page + 85
in `part1.pdf` (verified directly: PDF p.3 = internal p.88 Index page; PDF p.58 =
internal p.143, "E1. Climate change" heading). `part2.pdf` internal page = PDF page +
185 (part1's 100 pages + the same +85 offset). Record this in `resources/document_corpus.md`
so Stage 10 coders don't have to re-derive it.

## 2. Pilot coding matrix

Columns per Codebook v1 §7. "Institutional Pressure" and "Response" are RQ1 codes;
"GW Indicator(s)" and "Competitive Signal(s)" are RQ2 codes; "Decoupling" is the
cross-cutting axis.

| # | Company | Year | Document | Page | Topic | Extract (paraphrase) | Inst. Pressure | Response | GW Indicator(s) | Competitive Signal(s) | Decoupling | Evidence | Counter-evidence | Interpretation | RQ |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| P1 | H&M | 2024 | Sustainability Progress Report 2024 | p.8–9 | Climate (scope 1+2) | Scope 1+2 emissions down 41% vs. 2019 baseline; 96% renewable electricity; coal-fired energy units in the supply chain down from 118 to 27 since 2022 | NONE (no explicit regulatory/peer reference in this unit) | SUBSTANTIVE | — | — | — | Quantified, baseline-referenced, year-over-year comparable figures | None identified in this unit | A concrete, verifiable claim; no indicator basis for a GW code | RQ1 |
| P2 | H&M | 2024 | Sustainability Progress Report 2024 | p.8–9 | Climate (scope 3) | Scope 3 emissions down 23.7% vs. 2019 baseline, but **up 3% vs. 2023** | NONE | MIXED | — | — | MEANS-ENDS (partial) | The report itself discloses the 2023→2024 increase alongside the 2019 baseline figure | The +3% YoY figure is disclosed, not hidden — argues against WEAK SUBSTANTIATION or MISMATCH | A genuine mixed result, transparently reported; the baseline-vs-YoY framing invites scrutiny but is not itself a violation since both numbers are given in the same unit | RQ1 |
| P3 | H&M | 2024 | Sustainability Progress Report 2024 | p.18–20 | Materials (recycled content) | 89% of materials recycled or sustainably sourced (target 100% by 2030); 29.5% recycled materials specifically (target 30% by 2025) | NORMATIVE (Textile Exchange "Leading" status referenced) | SUBSTANTIVE | — | COMPETITIVE FRAMING ("Leading" status is an industry-benchmark ranking) | — | Two distinct, separately quantified metrics (broad "sustainably sourced" vs. narrower "recycled") with named baseline/target years | The 89% figure bundles "recycled" and "sustainably sourced" without disclosing the split between the two in this unit | The 89%/29.5% pairing is more precise than Inditex's equivalent (P6) — worth a direct cross-case comparison at Stage 10, not a violation on its own | RQ2 |
| P4 | H&M | 2024 | Sustainability Progress Report 2024 | p.21–22 | Circularity (resell) | Resell services account for 0.6% of turnover; offered in 30% of selling markets | NONE | SUBSTANTIVE | DISPROPORTIONAL EMPHASIS (candidate — see note) | — | — | A precise, denominated percentage (turnover share) is disclosed, which is unusually transparent for a resell metric | The dedicated sub-section length devoted to resell narrative vs. its 0.6%-of-turnover materiality was not measured quantitatively in this pilot (would require a page/word-count-share method, per Garcia-Torres et al., 2017) | Flagged as a DISPROPORTIONAL EMPHASIS *candidate*, not confirmed — Stage 10 needs the page/word-share method actually applied, not an impression | RQ2 |
| P5 | H&M | 2024 | Sustainability Progress Report 2024 | p.25–27 | Workers (own workforce) | Global Framework Agreement with IndustriALL/IF Metall; employee satisfaction 76/100 (up from 75) | NORMATIVE (global union framework agreement = industry/labour-norm conformity) | SUBSTANTIVE | — | — | — | Named counterparties (IndustriALL, IF Metall), a agreement type that is independently verifiable, plus a tracked satisfaction metric with a prior-year comparator | 1-point year-over-year satisfaction gain is a small movement reported without a stated methodology/sample size in this unit | A real, named agreement — clearly SUBSTANTIVE; the satisfaction score alone (no methodology) would border WEAK SUBSTANTIATION if presented in isolation, but the agreement anchors the unit | RQ1 |
| P6 | Inditex | 2024 | Group Annual Report 2024 (Sustainability Statement) | internal p.163 | Climate (scope 1+2 vs. scope 3) | Total emissions 9,962,965 t CO₂eq (2024) vs. 10,528,872 t CO₂eq (2018 baseline) — a ~5.4% total reduction. Scope 1+2 down from 495,584 to 60,912 t CO₂eq (~87.7% reduction, tracking toward the 95%-by-2030 target); scope 3 down only from 10,033,288 to 9,902,054 t CO₂eq (~1.3% reduction) | COERCIVE (SBTi/Paris Agreement-aligned target approved 2024, ESRS-structured disclosure) | MIXED | DISPROPORTIONAL EMPHASIS | — | MEANS-ENDS | The report's own table (p.163) discloses all four figures side by side, so the scope 3 stagnation is not hidden from a reader who reaches the table | The section's narrative framing ("Towards net-zero emissions" graphic, p.146; "we reduced... scope 1,2 and 3 emissions by 5%... as compared to 2018," p.162) foregrounds the combined 5% figure and the scope 1+2 trajectory, while scope 3 — ~99% of total emissions — is not separately headlined in the same prominent way | A textbook case for testing DISPROPORTIONAL EMPHASIS: the underlying data is fully disclosed (this is not MISMATCH or OMISSION), but the *prominence* given to the fast-moving, small-denominator scope 1+2 figure versus the slow-moving, 99%-of-total scope 3 figure is disproportionate to their respective materiality. Counter-evidence (the table itself) must be logged alongside the finding per Methodology §3.1's negative-case-analysis requirement | RQ2 |
| P7 | Inditex | 2024 | Group Annual Report 2024 (Sustainability Statement) | internal p.157 | Climate (self-consumption) | Self-consumption (on-site solar/wind) produced 9,962 MWh in 2024, against total energy consumption of 1,670,262 MWh (internal p.165) — self-consumption covers well under 1% of total consumption | COERCIVE/NORMATIVE (Energy Policy approved Feb 2025; RE100/CDP references) | SUBSTANTIVE (the 9,962 MWh figure itself is precise) | UNCLEAR BOUNDARY (candidate) | COMPETITIVE FRAMING ("aim to triple... capacity by 2027") | — | Both figures (9,962 MWh and 1,670,262 MWh total) are independently disclosed in the same report, allowing the ratio to be computed | The self-consumption sub-section (p.157) is presented as a headline "Lower-impact consumption" initiative without stating its ~0.6% share of total consumption in the same unit — a reader must cross-reference p.165 to see the true scale | Not coded MISMATCH (no contradiction — the 92%-renewable figure on p.165 is achieved mainly via purchased renewable electricity/PPAs/certificates, not self-consumption, and the report does not claim otherwise). Flagged UNCLEAR BOUNDARY because the initiative's narrative doesn't scope its own materiality against the total it's part of | RQ2 |
| P8 | Inditex | 2024 | Group Annual Report 2024 (Sustainability Statement) | internal p.165 | Climate (renewable energy share) | Renewable energy share of total consumption: 92% (2024) vs. 93% (2023) — a slight **decline** year-over-year despite the overarching narrative of continuous progress | NONE | MIXED | — | — | — | The 2023 and 2024 figures are both disclosed in the same table, so this is transparent, not hidden | The report frames renewable sourcing throughout as steadily advancing; this single-point dip is not separately flagged or explained in the surrounding narrative | A minor, disclosed data point that could support a CONTRADICTION code only if the surrounding narrative *explicitly* claimed continuous year-on-year increase — on this pilot read it does not make that explicit claim, so CONTRADICTION is not applied; logged as MIXED only | RQ1 |
| P9 | Inditex | 2024 | Group Annual Report 2024 (Sustainability Statement) | internal p.200 | Materials (lower-impact fibres) | 73% of fibres classified "lower-impact" in 2024 (target 100% by 2030); within that, 0% next-generation fibres achieved against a 25%-by-2030 sub-target, and 39%/40% for conventional recycling | NORMATIVE (Textile Exchange/Canopy/GOTS/GRS third-party standards referenced as the qualifying criteria) | MIXED | INCONSISTENT METRIC (candidate, cross-case) | — | — | The breakdown table itself discloses the 0%-of-25% next-generation-fibres shortfall, and the sub-category percentages | The 73% headline aggregates several sub-categories (organic, recycled, "other preferred options") of very different verification strength; the 0% progress on next-generation fibres is stated but not narratively addressed | Flagged INCONSISTENT METRIC as a **cross-case candidate**: Inditex's "lower-impact fibres" (73%, a broad multi-category definition) is not the same construct as H&M's "recycled materials" (29.5%, P3) or "sustainably sourced" (89%, P3) — Stage 10 must not compare these headline percentages directly without noting the definitional mismatch | RQ2 |
| P10 | Inditex | 2024 | Group Annual Report 2024 (Sustainability Statement) | internal p.197–198 | Circularity (Zara Pre-Owned, clothing collection) | Zara Pre-Owned (repair/resale/donation) live in 14 markets; clothing collection programme recovered 19,484 tonnes of garments/footwear in 2024 (20,259 t in 2023); 57% reused, 43% recycled/downcycled | NORMATIVE | SUBSTANTIVE | OMISSION (candidate) | — | — | The tonnage collected and reuse/recycling split are both precisely quantified | No denominator is given anywhere in this unit (e.g., % of total garments sold/produced) — unlike H&M's resell figure (P4), which is explicitly stated as 0.6% of turnover | Flagged OMISSION as a candidate: the *type* of metric disclosed (absolute tonnes) differs from H&M's (% of turnover), which limits direct comparability rather than indicating concealment — this is a comparability gap, not confirmed evidence of a materially negative topic being hidden. Needs the OMISSION operationalisation fix noted in §3 below before this can be coded with confidence | RQ2 |
| P11 | Inditex | 2024 | Group Annual Report 2024 (Sustainability Statement) | internal p.260–262 | Workers in value chain ("Living wages" Priority Impact Area) | The "Living Wages" PIA reached 86,268 people in 2024 (100,454 cumulative since 2023) — the smallest reach of the five PIAs (vs. 1,313,217 for "Health" in 2024 alone). No wage-level figures, living-wage benchmark (e.g. Asia Floor Wage, Fair Wage Network), or wage-gap data are disclosed anywhere in this unit or the surrounding S2 section | NORMATIVE (ACT initiative, industry collective-bargaining norms referenced) | SYMBOLIC | WEAK SUBSTANTIATION | — | POLICY-PRACTICE (candidate) | The PIA is named "Living wages" and describes "necessary conditions for collective bargaining" and "responsible purchasing practices," but reports zero wage-outcome metrics | The Health PIA in the same S2 section *does* report a concrete audit-based mechanism (Corrective Action Plans) with a people-reached figure an order of magnitude larger, showing the company is capable of more granular reporting elsewhere in the same document | This is the clearest pilot instance of a policy/programme named after an outcome (paying living wages) while reporting only process metrics (people "reached" by dialogue/training activities) rather than any wage-level result — a good test case for POLICY-PRACTICE DECOUPLING, though "candidate" status is retained pending a second reporting year's data (2025) to confirm this is a pattern, not a one-year artefact | RQ1/RQ2 |
| P12 | Inditex | 2024 | Group Annual Report 2024 (Sustainability Statement) | internal p.251 | Workers (own workforce) — Ethics Line | 791 cases recorded via the Ethics Line in 2024 (280 concerning own workforce); 4 discrimination cases confirmed; "no inherently severe human rights-related incidents... confirmed" | COERCIVE (OECD Guidelines/UN Guiding Principles referenced as the compliance framework) | SUBSTANTIVE | — | — | — | A precise case count and confirmed-case count are both disclosed, which is more granular than a narrative-only grievance-mechanism description | The report does not disclose how many of the 791 total cases were *investigated but not confirmed* vs. dismissed without investigation — the ratio of reported-to-confirmed is not explained | Genuinely SUBSTANTIVE (real numbers, named mechanism); the confirmed/unconfirmed ratio gap is noted as a limitation of the disclosure, not elevated to a GW indicator without a comparison point | RQ1 |

**Total: 12 pilot rows** (5 H&M, 7 Inditex) across the three Stage-9 topics. This is a
deliberately small, illustrative pilot — Stage 10 (full coding) will cover the entire
corpus, not just these units.

## 3. Findings on Codebook v1 §9's open questions

### 3.1 Is COERCIVE/NORMATIVE/MIMETIC cleanly distinguishable?

**Partially.** Rows P6, P7, and P9 show COERCIVE and NORMATIVE pressure genuinely
co-occurring in a single unit (an SBTi-approved target sitting inside an
ESRS-mandated disclosure that *also* cites third-party voluntary standards like
Textile Exchange/Canopy). No pilot unit forced a MIMETIC-vs-COERCIVE judgment call,
so entanglement was only tested for the COERCIVE/NORMATIVE pair here — the
COERCIVE/MIMETIC entanglement flagged in the Literature Review (Álvarez-Etxeberria et
al., 2023) should be re-tested at Stage 10 with units that explicitly reference peer
practice ahead of regulation.

**Fix for Codebook v2:** allow a unit to carry **more than one Institutional Pressure
code** (already implicit in Codebook v1 §2's "not mutually exclusive" language for
RQ1 pressure vs. response, but not stated for pressure-type combinations themselves).
Add an explicit rule: *record all clearly present pressure types for a unit, ordered
by which is most textually prominent; do not force a single choice.*

### 3.2 Is OMISSION codeable without a pre-built materiality/SDG-mapping reference?

**Not reliably, on this pilot's evidence.** Row P10 shows the practical failure mode:
what looked at first glance like a candidate OMISSION (Inditex not stating a
denominator for its clothing-collection tonnage) turned out, on reflection, to be a
**metric-type mismatch** (absolute tonnes vs. H&M's percentage-of-turnover), not
necessarily a concealed topic — Inditex was not shown anywhere in this pilot to have
*calculated but withheld* a percentage-of-total figure; it may simply not compute one
at all under its own reporting model. Concluding OMISSION would require establishing
that the missing figure (a) is calculable from data the company has, and (b) is
disclosed by the *other* case company or an external framework as material.

**Fix for Codebook v2:** split OMISSION into two more precisely bounded sub-tests
before coding:
1. **Cross-case topic omission** — a topic present in one company's materiality
   coverage for a given theme is entirely absent from the comparable section of the
   other company's report (testable now, from the two corpora directly, without
   external frameworks).
2. **Metric-denominator omission** — a company reports an absolute figure without any
   accompanying scale/denominator (production volume, turnover, headcount) where the
   *same company* discloses denominators for comparable metrics elsewhere in the same
   report (testable from internal consistency, not cross-case or external benchmarks).
Both are lighter-weight than the original Garcia-Torres et al. (2017) SDG-mapping
method, which remains open as a Stage-10-only enhancement if time permits, not a
pilot blocker.

### 3.3 Is PROPRIETARY WITHHOLDING codeable from these public reports?

**Not tested in this pilot** — no unit in either company's climate, materials, or
S2 sections surfaced a plausibly-competitively-sensitive category (e.g., supplier
pricing, sourcing costs) that was present in one report and absent in the other.
This is consistent with Codebook v1's framing of PROPRIETARY WITHHOLDING as a
**cross-case, Ch.4.4-stage judgment**, not a per-unit code — it cannot be
meaningfully tested by reading FY2024 sections of both companies in isolation; it
requires the completed four-matrix comparison. **No change to Codebook v2 needed
here** — defer to Stage 10 as originally planned.

## 4. Additional findings not anticipated in Codebook v1 §9

- **DISPROPORTIONAL EMPHASIS is workable, but needs an explicit measurement rule.**
  Row P6 (Inditex scope 1+2 vs. scope 3 framing) is the strongest pilot evidence that
  this code captures something real and codebook-consistent with the RQ2 scope
  boundary in `CLAUDE.md` §1 (communication/disclosure pattern, not a fraud claim).
  But applying it currently relies on a qualitative impression of "which figure is
  headlined." Codebook v2 should add a lightweight operational test: *does the
  report's own narrative sentence state the small-denominator figure without, in the
  same or an immediately adjacent sentence, stating the large-denominator figure's
  trend?* This keeps the code text-anchored rather than tone-based, consistent with
  the "golden rule" in Codebook v1 §4.
- **MIXED response code needs a stricter trigger.** Rows P2 and P8 were both coded
  MIXED for "a real metric that also contains an unfavourable data point," but neither
  involves scope-narrowing language ("in select markets," a pilot programme) as
  Codebook v1's definition specifies. **Fix:** split MIXED into two documented
  sub-patterns for Codebook v2 — (a) *scope-narrowed* (matches the original
  definition) and (b) *self-disclosed unfavourable trend* (a transparently reported
  YoY reversal or decline alongside a longer-term positive baseline comparison). Both
  remain "MIXED," but the distinction matters because (b) is, if anything, evidence
  *against* selective disclosure (the company reported the bad number itself) and
  should not be conflated with (a) in the Results write-up.
- **The coding matrix template (Codebook v1 §7) works as designed** — no column
  needed changing. The "Counter-evidence" column was essential in nearly every row
  above (P2, P6, P7, P8, P9, P10, P12) and confirms Methodology §3.1's
  negative-case-analysis design decision was the right call.

## 5. Disposition

Per `CLAUDE.md` §5 (stop rule): Codebook v1's core structure (unit of analysis, RQ1
pressure/response tables, RQ2 indicator/competitive tables, decoupling axis, matrix
template) already does its job and is **not rewritten wholesale**. Codebook v2
(`research/coding/codebook_v2.md`) applies only the three targeted fixes identified
above (multi-pressure-code allowance; OMISSION split into two sub-tests; MIXED split
into two sub-patterns) plus the DISPROPORTIONAL EMPHASIS operational test. Stage 10
full coding should proceed on Codebook v2.
