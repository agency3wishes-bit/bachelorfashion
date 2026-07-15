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

**Not yet resolved — flagged for the author, not actioned unilaterally:** the
presentation's RQ wording (broader, industry-causal framing: "what drives... to
greenwash," "how is selective disclosure used as a mechanism") differs from this
thesis's locked RQ wording (comparative, firm-specific: "how are pressures reflected
in H&M/Inditex's communication... how do responses compare"), and its stated study
period ("3 Years") differs from the locked 2022–2025 (4 fiscal years) window. These
may be an intentional, defensible refinement already implicit in how the thesis
evolved past the presentation stage — but since the presentation was supervisor-
approved, the author should confirm this evolution is expected/acceptable before
final submission, rather than have it surface as a surprise inconsistency to the
supervisor.

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

- **NGO figure verification**: every Fashion Transparency Index / Changing Markets
  Foundation figure used in `thesis/5_Discussion.md` is tagged PARTIAL, verified only
  via WebSearch snippets because this environment's proxy blocks direct fetch of
  both NGOs' domains (confirmed via `curl $HTTPS_PROXY/__agentproxy/status`). The
  author (or a future session with unblocked network access) should independently
  pull the primary PDFs and confirm the exact figures before they are treated as
  settled in any final submission.
- **Author sign-off**: `thesis/OUTLINE.md` and `resources/document_corpus.md` are
  both marked as needing final author sign-off in their own header notes — this is
  a human-judgment step, not a drafting task.
- **Final read-through**: the thesis is complete and has passed the Stage 15 audit,
  but a full human read-through before submission is still the author's own
  responsibility, not a substitute this session can provide.
