# Document Corpus Table (Stage 4) — DRAFT

*Built from web-search verification (WebFetch to all three domains below is blocked
in this sandbox, so entries rest on search snippets and directly-surfaced PDF URLs,
not a rendered page view). Confidence is marked per entry. Items marked ⚠ need the
author's own confirmation or the actual PDF upload before this table is signed off
per the playbook's "lock before mass-drafting" rule. Nothing below is invented —
where a title/date could not be verified, that is stated explicitly rather than
guessed.*

## Fiscal-year comparability note (read first)

H&M Group's fiscal year runs **1 December–30 November**, labelled by the year it
mostly falls in (e.g. "FY2024" = Dec 2023–Nov 2024). Inditex's fiscal year runs
**1 February–31 January**, labelled by the year it *begins* (e.g. "FY2024" = Feb
2024–Jan 2025). A same-numbered "FY2024" for the two companies therefore covers
different, only partially overlapping 12-month windows (roughly a 2-month lag,
Inditex's later) — flag this explicitly in Section 3.2/3.3 as a comparability
caveat, not an error to fix; the coding matrix should record each report's actual
covered period, not just its label.

## H&M Group — IN HAND / CONFIRMED (updated 2026-07-14: 5 documents across 3 of 4 years)

| Year (label) | Title | Reporting period | Status | Local file |
|---|---|---|---|---|
| 2022 | H&M Group **Sustainability Disclosure 2022** (90 pp.) — dedicated companion document covering Circularity/Climate/Nature, Fair & Equal, Supply Chain Management | 1 Dec 2021 – 30 Nov 2022 | ✅ In hand, verified authentic | `data/reports/HM_Group_Sustainability_Disclosure_2022.pdf` |
| 2023 | H&M Group Annual and Sustainability Report 2023 (or its "Sustainability Disclosure 2023" companion) | 1 Dec 2022 – 30 Nov 2023 | ⚠ **Still missing** — only a 2-page press release announcing publication was uploaded | `data/reports/HM_Group_2023_PRESS_RELEASE_not_full_report.pdf` (not usable for coding) |
| 2024 | H&M Group Annual & Sustainability Report 2024 (85 pp.; Sustainability report pp. 53–110) **+** H&M Group Sustainability Progress Report 2024 (34 pp.; Climate, Water, Chemicals/water pollution, Biodiversity/ecosystems/land-use, Resource use and circularity, Social impact and human rights) | 1 Dec 2023 – 30 Nov 2024 | ✅ Both in hand, verified authentic | `data/reports/HM_Group_Annual_Sustainability_Report_2024.pdf` + `data/reports/HM_Group_Sustainability_Progress_Report_2024.pdf` |
| 2025 | H&M Group Annual & Sustainability Report 2025 (98 pp.; Sustainability statement pp. 58–128) | 1 Dec 2024 – 30 Nov 2025 | ✅ In hand, verified authentic | `data/reports/HM_Group_Annual_Sustainability_Report_2025.pdf` |

**Naming note (confirmed across the uploaded documents):** H&M Group's reporting model
has multiple components each year — the Annual and Sustainability Report *and* a
separate, deeper sustainability-only document, named "Sustainability Disclosure" in
2022/2023 and renamed "Sustainability Progress Report" from 2024 onward. The 2024
Progress Report's own "How we report" page confirms this structure explicitly and
notes the 2024 Annual Report is "aligned with the upcoming [CSRD] requirements but
does not claim to be compliant" — directly usable evidence for the codebook's
COERCIVE/anticipatory-pressure coding (cf. Álvarez-Etxeberria et al., 2023 in Ch.2.3).

**Still needed for full H&M coverage:** the 2023 Annual and Sustainability Report or
its "Sustainability Disclosure 2023" companion — the one real gap left in the H&M
side of the corpus.

## Inditex — PARTIALLY CONFIRMED ⚠

Naming changed across the period — this is a real, confirmed fact, not
inconsistency in this table. By FY2024 the sustainability statement is published
as a component of the group Annual Report rather than a standalone document.

| Year (label) | Title | Reporting period | Official URL | Confidence |
|---|---|---|---|---|
| 2022 | ⚠ Inditex Group Annual Report 2022, containing a "Statement on/of Non-Financial Information" component — **exact component title unconfirmed for this specific year** | 1 Feb 2022 – 31 Jan 2023 | Not directly retrieved; inferred from adjacent years' pattern | ⚠ Unconfirmed — needs direct verification or PDF upload |
| 2023 | Statement of Non-Financial Information 2023 (component of Inditex Group Annual Report 2023) | 1 Feb 2023 – 31 Jan 2024 | https://static.inditex.com/annual_report_2023/en/Statement%20of%20Non-Finantial%20Information%202023.pdf | Confirmed (direct PDF URL; note publisher's own filename typo "Non-Finantial") |
| 2024 | Consolidated Statement of Non-Financial Information and Sustainability Information (component of Inditex Group Annual Report 2024) | 1 Feb 2024 – 31 Jan 2025 | https://www.inditex.com/itxcomweb/api/media/d6d06b5c-4a2f-431d-915f-ce8ca9e95181/Sustainabilityreport2024.pdf | Confirmed (direct PDF URL) |
| 2025 | ⚠ Full Inditex Group Annual Report 2025 with sustainability statement — **publication not confirmed as of this draft.** Only the FY2025 financial results release was found (https://www.inditex.com/itxcomweb/api/media/1da2c9d1-dbca-49fb-9563-982a8a27fae6/INDITEXFullYear2025.pdf), which does not itself constitute the sustainability disclosure document. | 1 Feb 2025 – 31 Jan 2026 | Check https://static.inditex.com/annualreport2025/en/ closer to submission | ⚠ Unconfirmed — may not exist yet |

## External / context documents (empirical data or context — NOT academic corpus)

Per `CLAUDE.md` §1, these are empirical/context sources, never citable as academic
support for theory claims — they feed Chapters 3–5 as primary evidence or
regulatory/industry backdrop, not the Literature Review.

| Document | Issuer | Date | Official URL | Confidence | Role |
|---|---|---|---|---|---|
| EU Strategy for Sustainable and Circular Textiles (COM(2022) 141 final) | European Commission | 30 March 2022 | https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A52022DC0141 | Confirmed (EUR-Lex + Commission PDF header) | Coercive-pressure context for RQ1; study-period framing |
| Commitment decision for H&M regarding sustainability claims | Dutch Authority for Consumers and Markets (ACM) | September 2022 | https://www.acm.nl/en/publications/commitment-decision-handm-regarding-sustainability-claims | Confirmed (title, date, substance); ⚠ exact case/zaaknummer not found — do not cite a case number until independently verified | External-challenge context for RQ2 (H&M specifically); coercive-pressure context for RQ1 |

⚠ **NGO/industry assessment for triangulation** (PROJECT_PLAN.md mentions "a few
industry or NGO assessments" as a category, without naming specific ones yet) —
**not selected**. Candidates such as the Fashion Revolution Transparency Index or
Changing Markets Foundation reports were not searched/verified in this pass and
are not proposed here; naming a specific NGO source is left for explicit author
approval, consistent with not silently expanding the evidence base.

## Inclusion / exclusion criteria (draft, pending Section 3.3 finalisation)

- **Inclusion**: primary, company-published annual/sustainability disclosure
  documents covering fiscal years overlapping the 2022–2025 window, for both
  H&M Group and Inditex, in English.
- **Exclusion**: press releases, marketing microsites, and social media content
  are excluded from the core coding corpus (may be referenced qualitatively in
  Discussion, not coded) unless a specific claim under EXTERNAL CHALLENGE
  requires cross-referencing them.
- Authenticity/credibility/representativeness/meaning screening (Morgan, 2022,
  per `thesis/3_Methodology.md` §3.5) applies once PDFs are in hand: confirm each
  document is the genuine, current, primary-source version (not a draft, translated
  excerpt, or third-party mirror).

## What's still needed from the author

1. Confirm or correct the ⚠-flagged Inditex 2022 and 2025 entries (or upload the
   actual PDFs — fastest path).
2. Upload all 8 (or 7, if Inditex 2025 doesn't exist yet) confirmed report PDFs.
3. Decide whether to include any NGO/industry assessment for triangulation, and if
   so, which — do not assume one.
4. Sign off on this table (or request corrections) before it is treated as locked
   per the playbook's Stage 4/8 sequencing.
