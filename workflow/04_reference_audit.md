# Workflow 04: Reference Audit

This workflow explains how to audit references before continuing with peer review, structural reconstruction, and final manuscript polishing.

It is designed for Russian-language academic manuscripts prepared for ВАК journals and related scholarly publications.

## Purpose

The purpose of this workflow is to check whether the manuscript's references are real, complete, relevant, and correctly connected to the claims they support.

This step should detect:

* fabricated references;
* fake DOI numbers;
* incomplete bibliographic records;
* unverifiable sources;
* decorative citations;
* citation-claim mismatches;
* unsupported claims;
* missing in-text citations;
* bibliography entries that are never cited;
* high-risk claims that require stronger evidence.

## Core rule

A reference is not acceptable only because it looks academic.

A reference must be:

1. real;
2. verifiable;
3. bibliographically correct;
4. cited in the manuscript;
5. relevant to the claim;
6. strong enough for the claim type.

If a reference cannot be verified, mark it clearly.

Do not invent missing bibliographic details.

Do not invent DOI numbers.

Do not replace suspicious references with invented sources.

## Required input

Before starting the reference audit, prepare:

1. Current manuscript draft.
2. Full reference list.
3. In-text citations.
4. Any DOI numbers.
5. Any URLs.
6. Source PDFs or source records, if available privately.
7. Target journal reference style.
8. Reference audit checklist.
9. Citation integrity rules.

Use:

```text
prompts/04_reference_reality_checker.md
checklists/reference_audit_checklist.md
rules/citation_integrity_rules.md
```

## Step 1. Extract all references

Create a list of every bibliography entry.

For each reference, record:

| No. | Reference | Source type                            | DOI / URL | Status | Notes |
| --: | --------- | -------------------------------------- | --------- | ------ | ----- |
|   1 |           | article / book / chapter / web / other |           |        |       |
|   2 |           | article / book / chapter / web / other |           |        |       |
|   3 |           | article / book / chapter / web / other |           |        |       |

Classify source types:

* journal article;
* monograph;
* book chapter;
* conference paper;
* dissertation;
* official document;
* web source;
* database entry;
* report;
* archival source;
* other.

## Step 2. Check bibliographic completeness

For journal articles, check:

* author names;
* article title;
* journal title;
* year;
* volume;
* issue;
* page range or article number;
* DOI, if available;
* URL, if required;
* database record, if relevant.

For books, check:

* author or editor;
* title;
* city;
* publisher;
* year;
* edition, if relevant;
* page count or cited pages, if required.

For chapters, check:

* chapter author;
* chapter title;
* book title;
* editor;
* publisher;
* year;
* page range.

Use markers:

```text
[VERIFY AUTHOR]
[VERIFY TITLE]
[VERIFY YEAR]
[VERIFY JOURNAL]
[VERIFY VOLUME]
[VERIFY ISSUE]
[VERIFY PAGES]
[VERIFY PUBLISHER]
[VERIFY DOI]
[VERIFY URL]
```

## Step 3. Check whether each source is real

For each source, verify whether the bibliographic record exists.

Possible verification channels:

* official publisher page;
* journal website;
* Crossref;
* eLIBRARY;
* CyberLeninka;
* Google Scholar;
* university library catalogue;
* national library catalogue;
* Scopus or Web of Science, if available;
* official DOI resolver;
* official document repository.

If the source cannot be found, mark:

```text
[UNVERIFIABLE SOURCE]
```

If the source looks suspicious, mark:

```text
[POSSIBLE FABRICATED REFERENCE]
```

Do not use suspicious sources until manually verified.

## Step 4. Check DOI numbers

DOI numbers must not be guessed.

For every DOI, check:

* DOI resolves;
* DOI leads to the same article;
* author names match;
* title matches;
* journal or publisher matches;
* year matches;
* volume, issue, and pages match.

If DOI is missing, do not invent one.

If DOI is uncertain, mark:

```text
[VERIFY DOI]
```

If DOI leads to another article, mark:

```text
[DOI MISMATCH]
```

## Step 5. Match in-text citations and bibliography

Check two directions.

### Direction A

Every in-text citation must have a bibliography entry.

### Direction B

Every bibliography entry must be cited in the manuscript.

Problems to detect:

* in-text citation missing from bibliography;
* bibliography entry never cited;
* author-year mismatch;
* spelling mismatch;
* transliteration mismatch;
* duplicate entries;
* wrong year;
* same source listed twice;
* Russian and English versions duplicated.

Use this table:

| Problem                                    | Location | Required action                                    |
| ------------------------------------------ | -------- | -------------------------------------------------- |
| In-text citation missing from bibliography |          | Add verified bibliography entry or remove citation |
| Bibliography entry not cited               |          | Cite properly or remove entry                      |
| Year mismatch                              |          | Verify and correct                                 |
| Author mismatch                            |          | Verify and correct                                 |
| Duplicate entry                            |          | Merge or remove                                    |

## Step 6. Check citation-claim alignment

A real source can still be misused.

For every cited claim, ask:

```text
Does this source actually support this exact claim?
```

Classify support:

* directly supported;
* partially supported;
* weakly supported;
* unsupported;
* source unavailable;
* citation mismatch.

Use:

```text
prompts/05_citation_claim_alignment_checker.md
```

This step may be done after the reference reality audit, but obvious mismatches should be marked immediately.

## Step 7. Identify decorative citations

A citation is decorative if it is included only to make the text look scholarly.

Warning signs:

* citation appears after a broad paragraph with many claims;
* source is not discussed;
* citation does not support a specific sentence;
* source belongs to another field;
* citation is used only to increase bibliography size;
* citation is placed mechanically at the end of a paragraph.

Required action:

* attach citation to a specific claim;
* remove the citation;
* replace with a verified relevant source;
* revise the claim;
* remove the unsupported claim.

## Step 8. Identify high-risk claims

Some claims require stronger evidence.

High-risk claim types:

* causal claims;
* health claims;
* active longevity claims;
* broad historical claims;
* universal cultural claims;
* social effect claims;
* claims about all architecture, all culture, or all older adults.

High-risk words:

```text
causes
proves
ensures
determines
directly influences
improves
leads to
обеспечивает
доказывает
определяет
напрямую влияет
приводит к
улучшает
```

If evidence is insufficient, revise the claim.

Weak:

```text
Traditional architectural elements improve active longevity.
```

Stronger:

```text
Traditional cultural elements can be analyzed as part of an architectural environment that supports social interaction, mobility, orientation, and everyday practices associated with active longevity.
```

## Step 9. Active longevity source check

Claims about active longevity require field-appropriate sources.

Acceptable support may come from:

* gerontology;
* environmental psychology;
* public health;
* urban studies;
* age-friendly environment research;
* social participation research;
* mobility and everyday practice studies.

Architectural or cultural theory sources may support:

* symbolic meaning;
* cultural memory;
* spatial organization;
* architectural form;
* environmental affordances.

They usually cannot support direct claims about:

* biological aging;
* life expectancy;
* health improvement;
* medical outcomes;
* direct causal effects on longevity.

If the manuscript lacks empirical health evidence, avoid direct medical claims.

## Step 10. Assign reference risk levels

Use four risk levels.

### Low risk

The source is real, complete, relevant, and supports the claim.

### Medium risk

The source is probably real but needs bibliographic correction or clearer claim connection.

### High risk

The source is incomplete, weakly relevant, or attached to a claim it does not fully support.

### Critical risk

The source may be fabricated, DOI is wrong, or the citation supports a major unsupported claim.

Use this table:

| Reference | Reality status                     | Bibliographic status  | Claim support                  | Risk level                     | Required action |
| --------- | ---------------------------------- | --------------------- | ------------------------------ | ------------------------------ | --------------- |
|           | verified / unverified / suspicious | complete / incomplete | direct / partial / weak / none | low / medium / high / critical |                 |

## Step 11. Repair references

Possible repair actions:

* verify source;
* correct author names;
* correct title;
* correct year;
* correct journal information;
* correct DOI;
* add missing page range;
* remove duplicate entry;
* remove unverifiable source;
* replace with verified relevant source;
* narrow the claim;
* remove unsupported claim.

Do not:

* invent a source;
* invent DOI;
* invent pages;
* keep an unverifiable source silently;
* attach an unrelated citation;
* hide the problem with cautious language.

## Step 12. Produce the audit report

The final Reference Audit Report should include:

1. Audit decision.
2. Overall risk level.
3. Input checked.
4. Reference status summary.
5. Verified or likely usable references.
6. Incomplete references.
7. Unverifiable references.
8. Possible fabricated references.
9. DOI problems.
10. In-text citation and bibliography matching problems.
11. Citation-claim alignment warnings.
12. Active longevity citation warnings.
13. Required manual verification list.
14. Repair plan.
15. Final recommendation.

Use example:

```text
examples/reference_audit_report_example.md
```

## Step 13. Reference audit decisions

Use one of the following decisions.

```text
Reference audit passed
```

Use only when all sources are real, complete, cited correctly, and support the claims.

```text
Minor reference correction required
```

Use when sources are real but formatting or small metadata corrections remain.

```text
Manual verification required
```

Use when some sources are not yet verified.

```text
Major reference repair required
```

Use when many references are incomplete, mismatched, or weakly connected to claims.

```text
Do not submit
```

Use when fabricated, unverifiable, or unsupported references remain.

## Step 14. Continue to citation-claim alignment

After reference reality is checked, continue with a deeper citation-claim audit.

Use:

```text
workflow/05_citation_claim_alignment.md
prompts/05_citation_claim_alignment_checker.md
```

Reference reality and citation-claim alignment are different.

A source can be real but still not support the manuscript's claim.

## Safe storage

Safe to store in repository:

* reference audit workflow;
* checklist;
* fictional audit example;
* citation integrity rules.

Do not store:

* private bibliography with unpublished work;
* copyrighted PDFs;
* full article texts;
* paid database exports;
* private supervisor comments;
* confidential reviewer reports.

## Final checklist

Before leaving this workflow, confirm:

* every reference has been checked for reality;
* DOI numbers are verified or marked;
* incomplete references are marked;
* unverifiable references are marked;
* possible fabricated references are removed or flagged;
* in-text citations match bibliography;
* bibliography entries are actually cited;
* decorative citations are identified;
* high-risk claims are marked;
* active longevity claims have appropriate source warnings;
* repair plan is written.

## Final rule

A manuscript with polished language but unverifiable references is not submission-ready.

Reference integrity must be established before hostile peer review and final polishing.
