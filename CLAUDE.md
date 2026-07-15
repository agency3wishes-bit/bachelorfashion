# Thesis Review Protocol — Greenwashing in Fast Fashion (H&M Group vs. Inditex)

This file is the decision-gate review protocol for this thesis repository. Every session
that drafts, edits, or reviews thesis text MUST apply this protocol. It wins over any
generic skill checklist on every point of conflict.

## 1. Thesis context

- **Institution:** Universität Wien (University of Vienna).
  **Supervisor:** Dr. Aveed Raha. Submission: Vienna, July 2026.
- **Working title:** Greenwashing and Environmental Communication in Fast Fashion:
  A Comparative Case Study of H&M Group and Inditex (2022–2025)
  *(working — confirm against institutional template)*
- **Degree:** Bachelor's thesis, International Business
- **Formatting (per official template, confirmed 2026-07-14):** Times New Roman 12pt;
  1.5 line spacing; 1-inch margins on all sides; decimal-numbered headings (1, 1.1, 1.2 …)
  matching the pattern already used in `thesis/OUTLINE.md`. Front matter: Title page →
  Acknowledgments [voluntary] → Abstract (150–200 words) → Table of Contents → List of
  Figures [if any] → List of Tables [if any]. The template's own chapter/subheading
  labels (e.g. "2.1 Overview of Relevant Theories") are an editable placeholder skeleton
  — the template explicitly permits renaming and adding subheadings, so this thesis's
  more specific heading titles in `thesis/OUTLINE.md` are compliant, not a deviation.
  **Citation style: CONFIRMED as APA in-text** (2026-07-14), via a real exemplar thesis
  by a colleague under the same supervisor (`resources/Pottosina_example_thesis.pdf`):
  `(Author, Year)` / `(Author et al., Year)` / `(Author, Year, p. X)` for page-specific
  claims, APA-formatted reference list presented as a numbered list in citation order.
  A separately provided handwritten note describing a German "Vgl./footnote" citation
  convention does NOT match this exemplar and is not used — see
  `resources/citation_style_notes.md` for the full resolution. No rework needed on
  drafted chapters; they were already written in this format.
- **Method:** Qualitative comparative multiple-case study; document analysis;
  directed qualitative content analysis (deductive codebook)
- **Cases:** H&M Group and Inditex, reporting years 2022–2025
- **Research questions (VERBATIM — never paraphrase; locked 2026-07-14, wording lightly
  tightened 2026-07-15 to read closer to the author's supervisor-approved thesis-
  proposal presentation, while preserving the comparative, firm-specific, evidence-
  groundable structure the coded document analysis actually supports):**
  - RQ1: How do cross-border coercive, normative, and mimetic institutional pressures
    shape the environmental communication of H&M Group and Inditex (2022–2025), and
    how do their corporate responses compare in terms of substantive, symbolic, or
    mixed conformity?
  - RQ2: How is selective disclosure (e.g., omission, disproportional emphasis,
    inconsistent metrics) used as a legitimacy-seeking mechanism in the environmental
    communication of H&M Group and Inditex (2022–2025), and how do market competition
    and information asymmetry shape these patterns across the two firms?
- **Theoretical lens:** Institutional Theory (PRIMARY and only main lens).
  Supporting concepts only: Legitimacy Theory, decoupling, selective disclosure.
- **Scope boundary (critical):** The thesis analyses *communication patterns and
  disclosure quality* in corporate documents. It codes greenwashing indicators
  (mismatch, omission, unclear boundary, disproportional emphasis, inconsistent metric,
  contradiction, weak substantiation, external challenge). It does NOT assert legal
  wrongdoing, fraud, or intent. A sentence is never coded as greenwashing merely for
  sounding promotional. Claims about the companies must stay within what the coded
  documentary evidence supports.
- **Academic vs. contextual sources:** Only the 20 sources in
  `resources/approved_source_corpus.md` may be cited as academic literature.
  Corporate reports, the EU Textiles Strategy, the ACM decision, and NGO/industry
  assessments are EMPIRICAL DATA or CONTEXT — never academic support for theory claims.
  Citing any academic source outside the corpus is a protocol violation; flag proposed
  additions to the author and wait for approval.

## 2. Review principle

Valid reasons to recommend a change (closed list): factually wrong; unsupported by the
cited source's note in `research/source_notes/`; off-topic drift; illogical argument;
misclassified source; violates the scope boundary; Results/Discussion contamination
(interpretation in Ch.4 or new findings in Ch.5/6); structural defect against
`thesis/OUTLINE.md`; real grammar/APA error; anything that could realistically affect
the grade.

Invalid reasons: stylistic preference, "could be shorter," synonym swaps, re-polishing
text that already meets the standard.

## 3. Severity classification

- **Critical:** fabricated/unverifiable evidence; claim exceeds coded evidence; academic
  citation outside corpus; RQ paraphrased; Results contain interpretation.
- **Major:** single-source paragraphs in Ch.2; missing document/year/page for a finding;
  mimetic vs. competitive pressure conflated; gap statement not matching contribution.
- **Minor:** tense inconsistency (methods/results past; established facts present);
  citation format slips; weak transitions.
- **Optional:** everything else. Apply the grade-impact test first: if no realistic
  grade effect, it is Optional or omitted.

## 4. Required checks in every review

1. Section-function awareness (don't grade an Introduction for lacking Results).
2. Evidence linkage: every claim checked against the source note's verification tag
   (DIRECT / PARTIAL / UNVERIFIED). Never declare "direct support" without checking.
3. Results (Ch.4) findings each have document + year + page/section + concrete example.
4. The key conceptual distinctions: institutional (mimetic) vs. competitive pressure;
   substantive vs. symbolic response; policy vs. implementation.
5. Natural-writing check: no repetitive paragraph templates; never optimise prose
   FOR an AI detector.

## 5. Verdicts and output format

A (Ready) / B (Ready after minor corrections) / C (Substantive revision) / D (Not usable).
Fixed output: Verdict → grade-relevant issues table → source-to-claim check table →
structure/logic → required corrections → optional observations → stop decision.

**Stop rule:** if the section already does its job, say so and STOP. Do not rewrite a
READY section. Do not fabricate a rewrite for a D-verdict section missing evidence.

## 6. Prohibited behaviour

No automatic rewriting; no adding sources; no strengthening claims beyond evidence;
no fabricating page numbers, quotes, or findings; no silent corpus expansion; no
continuing to "improve" a section that already meets the standard.

## 7. Repository conventions

- Branch: `claude/awesome-fermi-yfb1xe`. Commit and push after every meaningful batch.
- Source notes: `research/source_notes/S<NN>_<author>_<year>.md` (IDs in corpus file).
- Evidence matrix: `research/evidence_matrix.md`. Coding matrices: `research/coding/`.
- Chapters: `thesis/<N>_<Name>.md`. Outline is locked once signed off — restructure
  only with author approval.
