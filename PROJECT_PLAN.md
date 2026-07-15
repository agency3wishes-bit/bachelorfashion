# Project Plan — Greenwashing in Fast Fashion (H&M Group vs. Inditex, 2022–2025)

Topic-specific instantiation of `workflow` (Thesis Workflow Playbook). Working order:
research design → literature evidence → document corpus → methodology → coding →
results → discussion → final introduction → conclusion → abstract → full audit.

## Stage 16 (post-audit addendum, 2026-07-15): reconciliation with the approved thesis-proposal presentation

The author shared their supervisor-approved thesis-proposal presentation ("Drivers of
Greenwashing in the Fast Fashion Industry"). Comparison against this repo's thesis
found the overall qualitative multi-case document-analysis design and case selection
(H&M/Zara-Inditex) consistent, but three foundational sources anchoring the
presentation — Delmas & Burbano (2011), DiMaggio & Powell (1983), Marquis & Toffel
(2012, later published as Marquis, Toffel & Zhou, 2016) — were absent from the
30-source approved corpus. Author approved adding all three (2026-07-15). Actioned:
- New source notes: `research/source_notes/S31_DelmasBurbano_2011.md`,
  `S32_DiMaggioPowell_1983.md`, `S33_MarquisToffelZhou_2016.md` (WebSearch-verified,
  DIRECT/PARTIAL/UNVERIFIED tagged; primary PDFs blocked by this environment's proxy,
  consistent with the rest of the corpus).
- `resources/approved_source_corpus.md` updated: S31–S33 added (27 CORE-T + 6 METH
  = 33 total), with the S33 citation-choice note (citing the 2016 peer-reviewed
  published version, not the 2012 working paper the presentation showed).
- `thesis/2_Literature_Review.md`: DiMaggio & Powell now the opening citation for
  §2.3's coercive/normative/mimetic triad (with precise original definitions);
  Delmas & Burbano added to §2.1 (driver taxonomy, a distinct contribution from the
  existing definitional sources) and cross-referenced in §2.3/§2.5; Marquis, Toffel
  & Zhou added to §2.5 as a large-N (4,750 firms, 45 countries) complement to Lee &
  Lee (2022)'s single-country selective-disclosure finding.
- `thesis/5_Discussion.md`: DiMaggio & Powell's original mimetic-isomorphism
  definition now grounds §5.1/§5.3's existing "genuinely mimetic vs. competitive
  signaling" distinction; Marquis, Toffel & Zhou's scrutiny/norms mechanism now
  complements the §5.2 Living Wages/proprietary-withholding finding and the §5.4
  theoretical-implications summary.

**Resolved 2026-07-15 (author-directed):** RQ wording lightly tightened to read
closer to the presentation's phrasing while keeping the comparative, firm-specific,
evidence-groundable structure (see `CLAUDE.md` §1 and `thesis/1_Introduction.md`
§1.2 for the exact locked text); study period reconfirmed at 4 years (2022–2025)
after the author considered and reversed a 3-year alternative. Also actioned per
author instruction:
- **"Legitimacy gap" terminology** added in `thesis/2_Literature_Review.md` §2.4,
  introduced explicitly as this thesis's own adopted label for the
  legitimacy-performance divergence Bernini and La Rosa (2024) / Forliano et al.
  (2025) already establish — not attributed to any specific approved source, since
  no source note in the 33-source corpus was confirmed to use this exact term.
- **Four-step "Integrated Conceptual Framework"** (Drivers → IB Filter → Strategy →
  Outcome) now structures §2.7's closing synthesis paragraph, explicitly flagged as
  this thesis's own synthesis rather than an externally cited model.
- **H&M "Conscious" / Zara "Join Life" illustrative pair** added in three places,
  using only real, already-coded evidence (no new research): `thesis/1_Introduction.md`
  §1.1 (brief motivating illustration); `thesis/4_Results.md` §4.3 (surfaces the
  Join Life 61%-vs-50%-commitment figure at Inditex, 2022, p. 187 — already in the
  coding matrix but previously unused in the chapter prose — explicitly distinguished
  from the adjacent INCONSISTENT METRIC coding, which concerns the "preferred fibres"
  terminology realignment on the same page, not the Join Life figure itself);
  `thesis/5_Discussion.md` §5.2 (paired interpretation contrasting H&M's Conscious-label
  retirement under external pressure against Inditex's target-exceeding, unflagged
  Join Life figure, read through Marquis, Toffel & Zhou's 2016 scrutiny-and-norms
  mechanism).
- Per author instruction, the remaining presentation-specific sources not already
  in the corpus (Fletcher, 2014; McNeill & Moore, 2015; Fernández-Stark et al., 2022;
  Salminen & Rajavuori, 2019; Hahn & Lülfs, 2014) were **not** added, since no genuine
  analytical need for them arose in executing the above.

## Stage 17 (2026-07-15): primary-source verification of H&M page-cited claims

The author pushed the six H&M Group primary report PDFs into the repo (Sustainability
Disclosure 2022/2023, Progress Report 2024, Annual & Sustainability Report 2024/2025,
plus the 2022 combined Annual Report). This lifted the long-standing hard dependency
(playbook adaptation #3) that had kept the H&M coding grounded in the coding matrices
rather than in directly-read primaries. A multi-agent verification pass (43 distinct
H&M `(H&M Group, YEAR, p. X)` claims across Ch.4 and Ch.5, one agent per claim reading
the cited PDF pages) checked every quoted string, every asserted number, and every
cited page against the actual reports.

**Result: 30 CONFIRMED, 12 PARTIAL, 1 MISMATCH, 0 UNVERIFIABLE — no fabricated
evidence.** All 13 defects were corrected in place, each traced to a specific primary
page. The substantive ones:
- **Scorecards (MISMATCH, Ch.4 §4.4 / Ch.5 §5.3):** the thesis had scrambled the 2023
  and 2024 third-party-scorecard details — the "11 companies" Leading figure is from
  2024 (p.20), the "130 participating companies" from 2023 (p.15); CDP was A in 2024
  but A− in 2023; the scorecards were mis-cited to pp.30–31 (they are on p.15; only the
  Levi's Screened Chemistry comparison is on p.31). Untangled and re-grounded to the
  correct year/page for each.
- **Communities/grievance conflation (PARTIAL→fixed, Ch.4 §4.4, §4.5 / Ch.5 §5.2):** a
  reconciled "38 raised / 33 resolved" grievance table had been attributed to Affected
  communities (ESRS S3); it is in fact the national-monitoring-committee table for
  Workers in the value chain (S2). Removed the misattribution; the affected-communities
  "no targets" quote was also re-cited from pp.110–111 to its true page 112.
- **Business conduct overreach (PARTIAL→fixed, Ch.4 §4.2):** the 2024 report does set
  Business-conduct targets (corruption/bribery), so the "no targets" finding was
  narrowed to Consumers and Affected communities for 2024, with Business conduct valid
  only for 2025 (p.118 added to the cite).
- **Minor but real:** effluent 90% is disclosed in narrative as well as the table (not
  "only in the data table"); the "aims to deliver living wages" quote had dropped an
  "s"; the minimum-wage quote had its clause order reversed; the biodiversity "no
  targets" quote sits on p.87 not p.86 (cite widened to 86–87); the "only two sections
  without a KPI table" count is accurate only under "no quantified progress figure at
  all" (Own workforce has a 76/100 metric), so the wording was tightened; a
  community-investment figure had been mislabelled as capital expenditure.

**Not verifiable this pass — flagged for the author:** the four Inditex Annual Reports
(2022–2025) are NOT in the repo, so every `(Inditex, YEAR, p. X)` claim in Ch.4/Ch.5
remains grounded in the coding matrices only, not a directly-read primary. If the
author uploads those PDFs, the identical verification pass should be run on the Inditex
side before final submission.

## Stage 18 (2026-07-15): Inditex primary verification + NGO primary confirmations

Author supplied the Inditex sustainability-statement text extractions (2022 full
report, 2023 annual-accounts volume that also carries the NFI statement, 2024 NFI,
2025 NFI) and several NGO primaries. Actioned:

**Inditex verification** — same multi-agent pass as the H&M Stage-17 one, over 39
distinct `(Inditex, YEAR, p. X)` claims across Ch.4/Ch.5/Ch.6, each checked against
the mapped text file (quotes/numbers strict; pages best-effort, as text extractions
lack clean footers). **Result: 36 CONFIRMED, 3 PARTIAL, 0 MISMATCH, 0 UNVERIFIABLE
— no fabricated evidence.** All 3 PARTIALs corrected:
- Join Life (2022, p.187): 61%/50% figures verbatim-correct, but it is Inditex's
  **group-wide** Join Life standard, not "Zara-brand" (the 61% is "of our [Inditex]
  products", not Zara-specific). Corrected in Ch.1 §1.1, Ch.4 §4.3, Ch.5 §5.2.
- AR3T quote (2022): source reads "Avoid, Reduce, Restore, Regenerate **and**
  Transform" (thesis had a comma); fixed.
- Care for Water (2025, p.144): source reads "to **making** it a benchmark…";
  re-quoted the verbatim fragment "a benchmark for the textile and leather sector".

**NGO primary confirmations** (author-supplied screenshots/PDF):
- Fashion Transparency Index 2022 (H&M 66%, p.13) and 2023 (H&M 71%, p.19) — DIRECT.
- What Fuels Fashion? 2024 — H&M 61% (p.21) and Zara/Inditex 41% (p.20 full
  distribution) — DIRECT; a fully-confirmed cross-company pair for 2024.
- Changing Markets Synthetics Anonymous 2.0 (full PDF) — DIRECT. Two corrections:
  (1) the "~96% of H&M's claims misleading" figure does NOT appear anywhere in this
  2.0 report (full-text-searched) — it is from the 2021 predecessor, not in hand, so
  it was removed from the thesis; (2) Inditex is the **second**-highest disclosed
  synthetic-fibre volume (178,030t), after Nike — not "the largest," as an earlier
  draft said. §5.2 re-grounded in the report's actual H&M-reprimand language.

**Still snippet-level (flagged in §5.2/§5.6):** Zara/Inditex FTI 2023 = 50%; H&M
What Fuels Fashion? 2025 = 71%/#1-of-200. Both need their own primaries.

## Stage 19 (2026-07-15): final manuscript assembly

Content was already complete; this stage assembled the submission document.
- `thesis/7_References.md` — APA 7 reference list, alphabetical, 50 entries: all 33
  cited academic corpus sources + 5 H&M reports + 4 Inditex reports + EU Strategy,
  CSRD, Green Claims Directive, ACM decision, Fashion Revolution (FTI 2022/2023, WFF
  2024) and Changing Markets Synthetics Anonymous 2.0. All 33 academic sources
  confirmed cited in-text before inclusion.
- **H&M 2024a/2024b disambiguation:** H&M has two 2024 documents both cited as
  "(H&M Group, 2024)". Per APA, split into 2024a (Annual & Sustainability Report,
  the pp.102–103,105 citation) and 2024b (Sustainability Progress Report, all other
  2024 page-cites) across Ch.4/Ch.5 — verified 1× 2024a, 18× 2024b, zero bare.
- `thesis/00_Title_Page.md` — title page + acknowledgments placeholder + declaration
  placeholder.
- `thesis/THESIS_FINAL.md` — single assembled manuscript in template order (title →
  acknowledgments → abstract → auto-generated ToC → Ch.1–6 → references), with the
  per-chapter internal draft/editorial notes stripped. ~22,400 words of body text.

**Remaining human steps (cannot be done here — no pandoc/Word):** paste
`THESIS_FINAL.md` into the Universität Wien Word template and apply the required
formatting (Times New Roman 12pt, 1.5 line spacing, 1-inch margins, decimal heading
styles); let Word generate the ToC pagination; write the Acknowledgments and the
signed Declaration of Authorship; final human read-through; and the supervisor check
on the presentation-vs-thesis scope evolution (4-year window, tightened RQ wording).

## Stage status

| # | Stage | Status | Output |
|---|-------|--------|--------|
| 1 | Research design | ✅ done | RQ1/RQ2 verbatim in `CLAUDE.md` §1; `research/coding/codebook_v1.md` |
| 2 | Literature evidence matrix (30 cards) | ✅ done | `research/source_notes/S01–S30.md` |
| 3 | Literature Review Map | ✅ done | in `resources/approved_source_corpus.md` |
| 4 | Document corpus (both companies, all 4 years + external) | ✅ done | `resources/document_corpus.md` |
| 5 | Final Table of Contents | ✅ locked | `thesis/OUTLINE.md` |
| 6 | Introduction Draft 1 | ✅ done (written last, after Ch.2–5, per author's staging) | `thesis/1_Introduction.md` |
| 7 | Literature Review | ✅ done | `thesis/2_Literature_Review.md` |
| 8 | Methodology (before coding) | ✅ done | `thesis/3_Methodology.md` |
| 9 | Pilot coding → Codebook v2 | ✅ done | `research/coding/pilot_coding_report.md`, `research/coding/codebook_v2.md` |
| 10 | Full coding (4 matrices) | ✅ done | `research/coding/HM_coding_matrix_2022-2025.md`, `research/coding/Inditex_coding_matrix_2022-2025.md`, `research/coding/cross_case_institutional_pressures.md`, `research/coding/cross_case_competitive_disclosure.md` |
| 11 | Results | ✅ done | `thesis/4_Results.md` |
| 12 | Discussion | ✅ done | `thesis/5_Discussion.md` |
| 13 | Conclusion | ✅ done | `thesis/6_Conclusion.md` |
| 14 | Introduction rewrite (final) | ✅ not needed — Ch.1 was already written last (after Ch.2–5) and cross-checked against Ch.6 for consistency during the Stage 15 audit | `thesis/1_Introduction.md` |
| 15 | Abstract (150–200 words) + full audit | ✅ done | `thesis/0_Abstract.md`; audit findings and fixes logged in the session record — see verdict below |

**Stage 15 audit verdict: B (Ready after minor corrections — corrections already applied).**
Four-dimension audit (citation/corpus compliance, structural compliance, evidence
linkage/scope boundary, cross-chapter consistency) found zero Critical issues. Fixed
in place: the Ch.3 citation-permission gap in `resources/approved_source_corpus.md`
(S02/S17/S27 lacked Ch.3 in their permitted-chapters column despite their own source
notes recommending it; S21/S24 lacked Ch.6); four single-source paragraphs in Ch.2
(now multi-sourced via genuine, verified corroboration, not forced citation); a
Ch.4/Ch.5 boundary ambiguity around NGO-triangulation data (resolved with a forward
-pointer in Ch.4 §4.1); APA7 "et al." formatting inconsistency (fixed for every
3+-author citation, project-wide); non-standard repeated-"p." page citations in
Ch.4 (fixed to "pp." with comma-separated pages); missing chapter-closing
summary/transition in Ch.3 and Ch.4 (added); a stale Ch.3 limitations paragraph
still describing the codebook as "pending pilot testing" after Stage 9/10 completed
(corrected); a Ch.3 tense inconsistency (standardized to past tense for completed
procedural steps); and British/American spelling inconsistency in the thesis's own
authorial prose across all chapters (fixed via automated pass that preserved all
direct quotations from the — genuinely British-English — H&M/Inditex source
documents untouched). Two Optional findings (a one-word heading variance in §2.2;
Ch.3 running ~13% over its page budget) were left as-is per the stop rule, since
CLAUDE.md explicitly treats "could be shorter" and trivial subheading wording as
invalid reasons for a rewrite.

## Environment adaptations (playbook §4–5, documented deliberately)

1. **No Zotero / claude-scientific-writer skills installed.** The thesis-writing skill's
   `zotero-research-lookup` steps are substituted with multi-agent WebSearch evidence
   gathering. This is a deliberate substitution, not a skipped step.
2. **Publisher full-text domains blocked (403 via proxy); WebSearch works.**
   Research phase runs at abstract/snippet level with per-claim verification tags
   (DIRECT / PARTIAL / UNVERIFIED). Exact page numbers are mostly unavailable at this
   stage; each card lists page-level gaps. **Upgrade path:** author uploads article
   PDFs and the 8 corporate reports → notes upgraded with page-precise evidence
   (append, don't rewrite — playbook §6).
3. **Corporate report sites also blocked for direct fetch.** Stage 4/9/10 coding
   requires the author to upload the 8 report PDFs (H&M 2022–2025; Inditex 2022–2025).
   Page-precise coding is impossible from search snippets — this is a hard dependency.

## Model assignment (multi-agent mode)

- **Fable (main session):** planning, outlining, review gates (CLAUDE.md protocol),
  argument-heavy prose (Ch.2, 5, 6), final consistency pass, all merge decisions.
- **Sonnet subagents:** 14 CORE-T source cards (2 blocks each ≈ deeper search);
  evidence-matrix consolidation; formulaic first drafts (Ch.3, Ch.4 skeleton).
- **Haiku subagents:** 6 METH source cards (well-known methods papers, lighter
  extraction); mechanical consistency checks (references, tense, numbering).

## Institutional template (received 2026-07-14 — Universität Wien Bachelor Thesis Template)

Confirmed: Times New Roman 12pt, 1.5 line spacing, 1-inch margins, decimal-numbered
headings, front matter order (Title → Acknowledgments [voluntary] → Abstract 150–200
words → ToC → Lists of Figures/Tables if any). Supervisor: Dr. Aveed Raha. The
template's own chapter/subheading labels are an explicitly editable skeleton ("update
the heading titles according to your research... this table can be adjusted"), so
`thesis/OUTLINE.md`'s more specific subheadings are compliant, not a deviation. No
page/word limit is stated in the template itself (the ~35–40 page estimate in this
plan remains our own working target, not an institutional rule). **Citation style is
not specified in this document** — still pending the separate citation/notes document
the author is sending; APA 7 remains provisional until then.

## Open questions for the author (blockers marked ⚠)

1. ✅ RQ1/RQ2 verbatim — locked 2026-07-14, see CLAUDE.md §1.
2. ✅ Codebook v1 → `research/coding/codebook_v1.md`; piloted and refined into
   Codebook v2 (`research/coding/codebook_v2.md`) — see
   `research/coding/pilot_coding_report.md` for the pilot findings.
3. ✅ Citation style resolved (APA 7 in-text, confirmed via the Pottosina exemplar
   thesis) — see `resources/citation_style_notes.md`.
4. ✅ Article PDFs + corporate report PDFs all in hand — see `resources/document_corpus.md`.
5. ✅ FY2025 report titles confirmed for both companies — see `resources/document_corpus.md`.
6. ✅ NGO/industry assessment approved 2026-07-15 (Fashion Transparency Index primary,
   Changing Markets Foundation secondary) — see `resources/document_corpus.md` §"External
   / context documents" and `thesis/5_Discussion.md` §5.2 for how it is used, with its
   PARTIAL-verification caveats carried throughout.
7. ✅ `thesis/3_Methodology.md` §3.3 (Data Collection and Document Selection) drafted in full.
8. ✅ Stage 10 full coding (237 rows: 122 H&M, 115 Inditex) plus two cross-case
   synthesis matrices — underpins Ch.4 (Results) and Ch.5 (Discussion). Headline
   cross-case findings (scope 1+2 vs. scope 3 DISPROPORTIONAL EMPHASIS in both firms
   in some years; Inditex's "Living Wages" zero-wage-outcome-metric pattern across
   all 4 years, the strongest PROPRIETARY WITHHOLDING candidate in the corpus; H&M's
   SYMBOLIC Biodiversity disclosure throughout vs. Inditex's fully quantified
   trajectory from 2024; Inditex's 2025 ESRS materiality exclusion of "Affected
   Communities") are now written up in Ch.4/Ch.5 rather than pending — see
   `research/coding/cross_case_institutional_pressures.md` and
   `research/coding/cross_case_competitive_disclosure.md` for the full underlying detail.

## Remaining items outside this session's authority

- **NGO figure verification (in progress, 2026-07-15):** author supplied text
  extracts of the FTI 2022, FTI 2023, and "What Fuels Fashion?" (2024/2025) reports,
  plus a screenshot of the FTI 2023 Executive Summary chart pages (pp. 19–20).
  Confirmed DIRECT so far:
  - **H&M FTI 2022 = 66%** (tied with The North Face and Timberland; industry
    average 24%) — "TOP 10 SCORES IN 2022 (%)" table, p. 13. Zara/Inditex confirmed
    absent from that table (so below 54%), no exact 2022 figure readable.
  - **H&M FTI 2023 = 71%** — Executive Summary "KEY RESULTS / Highest Scoring
    Brands" chart, p. 19 (between United Colors of Benetton 73% and C&A 68%);
    screenshot read directly. Industry average **26%** confirmed (p. 18, "Overall
    average score across the 250 brands reviewed in 2023").
  Still PARTIAL (WebSearch snippet-level only):
  - **Zara/Inditex FTI 2023 = 50%** — a mid-pack score, so not shown on the p. 19
    highest/lowest chart; needs the report's per-brand data table / raw dataset or a
    Zara brand-profile page to confirm.
  - **"What Fuels Fashion?" 2024/2025** H&M figures (61%; 71% / #1 of 200) and the
    absence of a comparable Inditex figure — chart pages for these two editions not
    yet supplied as screenshots.
  - **Changing Markets Foundation "Synthetics Anonymous"** ~96%-of-H&M-claims figure
    and Inditex "largest synthetic-fibre user" claim — report not yet supplied.
  **Still outstanding:** author to supply the FTI 2023 raw-data table / Zara profile
  page, screenshots of both "What Fuels Fashion?" chart pages, and the Changing
  Markets report page(s), to close the remaining PARTIAL tags.
- **Author sign-off**: `thesis/OUTLINE.md` and `resources/document_corpus.md` are
  both marked as needing final author sign-off in their own header notes — this is
  a human-judgment step, not a drafting task.
- **Final read-through**: the thesis is complete and has passed the Stage 15 audit,
  but a full human read-through before submission is still the author's own
  responsibility, not a substitute this session can provide.
