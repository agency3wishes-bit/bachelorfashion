# Citation Style Notes

## ⚠ RESOLVED 2026-07-14: actual style is APA in-text, NOT the German "Vgl./footnote" style below

A real bachelor thesis by a colleague (Vita Pottosina, same supervisor Dr. Aveed Raha,
same Universität Wien template, Feb 2026) was provided as a structural example. Its
citation practice is standard **APA 7 in-text citation**: `(Author, Year)`,
`(Author et al., Year)`, `(Author, Year, p. X)` for page-specific claims — never
footnotes, never "Vgl.", never Nachname+Vorname-with-full-first-name in-text.
Its reference list is APA-formatted entries (Surname, Initial(s). (Year). Title.
*Journal, Vol*(Issue), pages. https://doi.org/...) — matching the format already
used in `resources/approved_source_corpus.md` — but presented as a **numbered list in
citation order** rather than strict alphabetical APA order.

**Conclusion:** the handwritten "Zitierregeln" notes (Section 1 onward below) describe
a generic German/Austrian academic-writing convention that does **not** match what
this supervisor's actual accepted theses use. Treat the exemplar thesis as
authoritative over the generic handout for citation *format* specifically. The
handout's underlying principles (§5 below — always cite AND include in the reference
list; mark direct quotes; genuinely paraphrase indirect citations, don't lightly edit)
remain valid general academic-integrity guidance regardless of format.

**Practical upshot:** `thesis/2_Literature_Review.md` and `thesis/3_Methodology.md`
are already written in APA in-text format — **no citation-format rework needed**.
Two adjustments worth making before final assembly: (1) add page numbers to
specific/quoted claims once source PDFs are available, matching the exemplar's
practice (e.g. "(Jana, 2021, p. 2)"); (2) present the final References chapter as a
numbered list in citation order, matching the exemplar's convention, rather than
strict alphabetical order.

---

## Original handwritten notes (German/Austrian "deutsche Zitierweise") — reference only, format NOT used here

Source: author-provided handwritten course notes ("Zitierregeln"), 2026-07-14.
Preserved below for its plagiarism-avoidance principles; its specific citation
*format* (footnotes, "Vgl.", full first names) does not apply to this thesis — see
resolution above.

## 1. Citation forms (Zitierformen)

Two components:
- **Vollbeleg** (full reference) — the complete bibliographic entry, appears once in
  the Literaturverzeichnis (reference list) at the end of the thesis.
- **Kurzbeleg** (short reference) — used at every citation point in the body text.
  Contains: author, [year], citation location (page).

Kurzbeleg can be placed in two ways (pick ONE and use it consistently throughout —
⚠ open question for the author, see below):
- **Fußnote (footnote):** a superscript number in the body text; the short reference
  appears in the footnote at the bottom of the page.
- **Text (in-text):** the short reference appears directly in the body text, in
  parentheses, immediately after the cited/quoted material.

## 2. Direct vs. indirect citations (Direkte und indirekte Zitate)

- **Direktes Zitat (direct quote):** source is quoted verbatim (wörtlich). Enclosed in
  quotation marks „…" (or set in letter-spaced/*gesperrt* type for emphasis in some
  formats). **No "Vgl."** prefix.
  - In-text: `"Bei solchen Applikationen liegt immer strukturelle Ungleichheit vor" (Nestor 2015, S. 57).`
  - Footnote: body text has quotation marks + superscript number; footnote reads
    `Nestor (2015), S. 5.` (no "Vgl.")
- **Indirektes Zitat (indirect/paraphrased citation):** source is paraphrased in one's
  own words (sinngemäß, eigene Worte). **Always prefixed with "Vgl."** (= "vergleiche",
  equivalent to "cf.").
  - In-text: `Daher ist in diesem Fall von ungleichen Strukturen auszugehen (Nestor 2015, S. 57).`
    — note: some examples show "Vgl." omitted in the parenthetical in-text form but
    present in the footnote form; **when in doubt, include "Vgl." for every indirect
    citation, in-text or footnote** — safer and matches the explicit rule statement.
  - Footnote: `Vgl. Nestor (2015), S. 57.`

**Critical plagiarism rule (from the notes' own worked example):** merely adding a
citation to text that is still copied near-verbatim from the source is NOT a valid
indirect citation and constitutes plagiarism — if the wording isn't genuinely
paraphrased into the author's own words, it MUST be marked as a direct quote (in
quotation marks). The notes' handwritten conclusion: **"bessere => paraphrasieren"**
(better: paraphrase properly rather than lightly edit).

## 3. In-text/footnote short-reference format by case

| Case | Format | Example |
|---|---|---|
| One author | `Vgl. Surname (Year), S. Page.` | — |
| Two or three authors | Surnames joined by `/` | `Vgl. Dawes/Solomon/Malhotra (2014), S. 19.` |
| More than three authors | `Surname u.a. (Year), S. Page.` (u.a. = "und andere" = et al.) | `Vgl. Bogner u.a. (2012), S. 416.` |
| Two+ sources, same author & year | Suffix a/b/c on the year | `Vgl. Egan (2015a), S. 34.` / `Vgl. Egan (2015b), S. 22.` |
| No author given | `o. V.` (= "ohne Verfasserangabe", without author) | `Vgl. o. V. (2008), S. 12.` |
| No year given | `o. J.` (= "ohne Jahr", without year) | `Vgl. Zelazny (o. J.), S. 5.` |
| Citation spans 2 pages | `S. [page] f.` (f. = "and the following page") | `Vgl. Bühl/Rost (2008), S. 217 f.` |
| Citation spans 3+ pages | `S. [page] ff.` (ff. = "and the following pages") | `Vgl. Indesit (2000), S. 97 ff.` |

Note: our corpus (S01–S30) is entirely peer-reviewed journal articles with confirmed
authors and years — the o.V./o.J. cases will not apply, but multi-author formatting
(3-author "/"-joined vs. 4+-author "u.a.") applies throughout and is a **mechanical
reformat** from the APA "and"/"&" style currently used in the drafted chapters.

## 4. Literaturverzeichnis (reference list) format

General rule: **Surname, Firstname (Year): Title, [venue-specific details].**
Placed at the end of the thesis; one entry per source actually cited.

⚠ **This uses full first names, not initials** (e.g. "Cucalores, Robert" not
"Cucalores, R."). Our 30-source corpus was compiled from DOI/publisher metadata,
which frequently gives only initials — full first names will need to be looked up
per source before the final reference list is built (flagged as a to-do, not urgent
until Ch.7 assembly).

By source type (from the notes' worked examples):
- **Book:** `Surname, Firstname (Year): Title, Place.`
  e.g. `Cucalores, Robert (2015): SEO Strategies, Albany, NY.`
- **Journal article:** `Surname, Firstname (Year): Title, in: Journal abbrev., Vol. Jg., Issue H., pp. Pages.`
  e.g. `Baetge, Jörg (1989): Möglichkeiten der Früherkennung negativer Unternehmensentwicklungen, in: ZfbF, 41. Jg., H. 4, S. 792–811.`
  — **this is our corpus's dominant type; all 30 sources should follow this pattern**
  once full first names are resolved.
- **Chapter in edited volume:** `Author (Year): Title, in: Editor(s) (Hrsg.): Book Title, Place, pp. Pages.`
  e.g. `Meffert, Heribert (1985): Wettbewerbsorientierte Marketingstrategien im Zeichen schrumpfender und stagnierender Märkte, in: Raffée, Hans/Wiedmann, Klaus-Peter (Hrsg.): Strategisches Marketing, Stuttgart, S. 475–490.`
- **Website:** `Author/Org (Year): Title, URL: [link], Stand: [access date].`
  e.g. `Statistik Austria (2007): ÖNACE 2008 – Implementierung, URL: http://…, Stand: 30.8.2015.`
  — relevant for corporate reports / EU documents / ACM decision (empirical/context
  sources, not the academic corpus).
- Multiple authors in the reference list: same `/`-joined or `u.a.` convention as
  in-text (e.g. `Backhaus, Klaus u.a. (2011): Multivariate Analysemethoden…, 13. Aufl., Berlin.` —
  note "13. Aufl." = 13th edition, included when relevant).

## 5. Plagiarism types (Plagiate) — for awareness, not an action item

- **Vollplagiat** (full plagiarism) vs. **Teilplagiat** (partial plagiarism).
- Avoidance checklist per the notes: (1) every claim has both a Literaturverzeichnis
  entry AND an in-text/footnote citation; (2) direct vs. indirect must be visibly
  marked (quotation marks for direct); (3) indirect citations must be **genuinely**
  rendered in one's own words, not a lightly-edited near-copy of the original.

## 6. Status (updated 2026-07-14)

~~Open questions about Fußnote-vs-Text and whether this style applies~~ — **resolved**:
see the top of this file. This German-format section (§1–5 above) does not govern
this thesis; APA in-text citation is confirmed instead, per the exemplar thesis.

Remaining real open item: full first names for all 30 corpus authors are not needed
under APA (initials are correct APA practice) — so this is no longer a to-do either.

## 7. Impact on existing drafts

None. `thesis/2_Literature_Review.md` (complete) and `thesis/3_Methodology.md`
(partial, §3.1–3.2) are already written in APA in-text format and require no
citation-format rework. See resolution at the top of this file.
