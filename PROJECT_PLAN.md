# Project Plan — Greenwashing in Fast Fashion (H&M Group vs. Inditex, 2022–2025)

Topic-specific instantiation of `workflow` (Thesis Workflow Playbook). Working order:
research design → literature evidence → document corpus → methodology → coding →
results → discussion → final introduction → conclusion → abstract → full audit.

## Stage status

| # | Stage | Status | Output |
|---|-------|--------|--------|
| 1 | Research design | ✅ done (per author) | ⚠ RQ1/RQ2 verbatim + codebook v1 still needed in repo |
| 2 | Literature evidence matrix (20 cards) | 🔄 in progress (multi-agent) | `research/source_notes/S01–S20.md` |
| 3 | Literature Review Map | ✅ drafted | in `resources/approved_source_corpus.md` |
| 4 | Document corpus (8 reports + external) | ⏳ | `resources/document_corpus.md` |
| 5 | Final Table of Contents | ✅ drafted, needs sign-off | `thesis/OUTLINE.md` |
| 6 | Introduction Draft 1 | ⏳ | `thesis/1_Introduction.md` |
| 7 | Literature Review | ⏳ | `thesis/2_Literature_Review.md` |
| 8 | Methodology (before coding) | ⏳ | `thesis/3_Methodology.md` |
| 9 | Pilot coding → Codebook v2 | ⏳ | `research/coding/codebook_v2.md` |
| 10 | Full coding (4 matrices) | ⏳ | `research/coding/` |
| 11 | Results | ⏳ | `thesis/4_Results.md` |
| 12 | Discussion | ⏳ | `thesis/5_Discussion.md` |
| 13 | Conclusion | ⏳ | `thesis/6_Conclusion.md` |
| 14 | Introduction rewrite (final) | ⏳ | — |
| 15 | Abstract (150–200 words) + full audit | ⏳ | — |

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
2. ⚠ Codebook v1 (categories + operational definitions) → `research/coding/codebook_v1.md`.
3. ⏳ Citation style + writing-conventions document (author is sending this) — will
   confirm or correct the provisional APA 7 assumption and any other conventions.
4. Article PDFs + 8 corporate report PDFs for page-precise evidence (see adaptation 2–3).
5. Confirm availability/titles of FY2025 reports for both companies (H&M FY ends 30 Nov;
   Inditex FY ends 31 Jan — verify what the "2025" document actually is for each).
