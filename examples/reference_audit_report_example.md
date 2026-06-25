# Reference Audit Report Example

This is an example of a Reference Reality Audit Report.

It shows what the output may look like after using:

```text id="yairbq"
prompts/04_reference_reality_checker.md
```

This example is fictional. It does not verify real sources and does not include real bibliographic records.

## Manuscript topic

Transformation of elements of traditional Chinese culture in contemporary architecture and their relation to active longevity.

## Target field

Cultural studies, architecture theory, humanities.

## 1. Audit decision

Decision:

Do not submit yet.

The reference list requires verification before the manuscript can be considered submission-ready. Several citations appear relevant, but the manuscript contains potential citation-claim mismatches, unsupported active longevity claims, incomplete bibliographic data, and unverifiable source records.

The main risk is not the number of references. The main risk is whether the references are real, accurate, and actually support the claims attached to them.

## 2. Overall risk level

Overall reference risk:

High.

Reasons:

1. Some references lack complete bibliographic data.
2. Some in-text citations do not clearly match bibliography entries.
3. Several claims about active longevity require stronger field-specific support.
4. Some sources appear to support general cultural theory but are used for health-related claims.
5. DOI or URL verification is incomplete.
6. Some references may be unverifiable without manual checking.

## 3. Input checked

Checked materials:

* manuscript draft;
* in-text citations;
* reference list;
* major claims connected to citations.

Not checked:

* full text of every source;
* official journal database records;
* Crossref records;
* eLIBRARY records;
* Scopus or Web of Science indexing;
* publisher websites.

Manual verification still required before submission.

## 4. Reference status summary

| Category                                       | Number | Status                                       |
| ---------------------------------------------- | -----: | -------------------------------------------- |
| Clearly usable references                      |      8 | likely acceptable after formatting check     |
| Incomplete references                          |      5 | require bibliographic repair                 |
| Unverifiable references                        |      4 | require manual verification                  |
| Citation-claim mismatches                      |      6 | require claim revision or source replacement |
| High-risk active longevity claims              |      3 | require stronger evidence                    |
| Possible duplicate entries                     |      2 | require cleanup                              |
| Possible fabricated or AI-generated references |      2 | must be verified before use                  |

## 5. Verified or likely usable references

The following references appear structurally usable, but still require final verification against official records.

### Reference A

Status:

Likely usable.

Function in manuscript:

Supports a theoretical claim about cultural memory.

Risk:

Low to medium.

Required action:

Check exact title, year, page range, and publication data.

### Reference B

Status:

Likely usable.

Function in manuscript:

Supports a claim about semiotic interpretation of cultural forms.

Risk:

Low.

Required action:

Confirm whether the source is cited consistently in the text and bibliography.

### Reference C

Status:

Likely usable.

Function in manuscript:

Supports a claim about architectural symbolism.

Risk:

Medium.

Required action:

Confirm whether the source discusses architecture specifically or only general symbolism.

## 6. Incomplete references

### Reference D

Problem:

Missing page range.

Risk:

Medium.

Required action:

Add verified page range or article number.

Do not invent page numbers.

Use:

```text id="nof91z"
[VERIFY PAGES]
```

### Reference E

Problem:

Journal issue number is missing.

Risk:

Medium.

Required action:

Check the official journal page or database record.

Use:

```text id="8u6fa3"
[VERIFY ISSUE]
```

### Reference F

Problem:

Publisher information is incomplete.

Risk:

Medium.

Required action:

Verify publisher, city, year, and edition.

Use:

```text id="qekia8"
[VERIFY PUBLISHER]
```

## 7. Unverifiable references

### Reference G

Problem:

The title appears plausible, but no reliable record has been confirmed.

Risk:

High.

Required action:

Search official databases, publisher website, library catalogues, Crossref, eLIBRARY, CyberLeninka, or other relevant academic databases.

Mark as:

```text id="q2lk4d"
[UNVERIFIABLE SOURCE]
```

### Reference H

Problem:

Author name and title appear inconsistent between in-text citation and bibliography.

Risk:

High.

Required action:

Verify the author, title, year, and source type.

Mark as:

```text id="mdsl32"
[VERIFY AUTHOR]
[VERIFY TITLE]
[VERIFY YEAR]
```

### Reference I

Problem:

The source may be real, but the manuscript gives no DOI, URL, publisher page, or database record.

Risk:

Medium to high.

Required action:

Verify the bibliographic record manually.

## 8. Possible fabricated or AI-generated references

### Reference J

Warning signs:

* title sounds generic;
* journal information is incomplete;
* DOI is absent;
* no database record has been confirmed;
* the source appears too perfectly aligned with the manuscript claim.

Risk:

Critical until verified.

Required action:

Do not use this reference unless it is verified.

Mark as:

```text id="y4jk3b"
[POSSIBLE FABRICATED REFERENCE]
```

### Reference K

Warning signs:

* DOI format appears plausible but has not been verified;
* article title and journal title may not match;
* page range looks artificial.

Risk:

Critical until verified.

Required action:

Check DOI resolution and official publication record.

Mark as:

```text id="jv08f2"
[VERIFY DOI]
[POSSIBLE FABRICATED REFERENCE]
```

## 9. DOI audit

### DOI problem 1

Problem:

A DOI is listed, but it has not been checked.

Required action:

Verify that the DOI resolves to the same source.

Check:

* author;
* title;
* journal;
* year;
* volume;
* issue;
* page range.

### DOI problem 2

Problem:

One DOI may belong to a different article.

Required action:

Do not keep the DOI unless it matches the exact reference.

Mark as:

```text id="0qg8r6"
[DOI MISMATCH]
```

### DOI rule

Never guess DOI numbers.

If DOI is unknown, leave it absent or mark it for verification.

## 10. In-text citation and bibliography matching

Detected issues:

1. Some in-text citations do not appear in the bibliography.
2. Some bibliography entries are not cited in the manuscript.
3. One author name is spelled differently in two places.
4. One year differs between the citation and bibliography.
5. Two entries may describe the same source.

Required actions:

* match every in-text citation with a bibliography entry;
* remove unused bibliography entries;
* correct author spelling;
* correct year mismatch;
* merge duplicate entries;
* use consistent transliteration.

## 11. Citation-claim alignment problems

### Problem 1. Cultural theory source used for health claim

Claim:

```text id="4fm7li"
Traditional cultural elements improve active longevity.
```

Problem:

The attached source discusses cultural symbolism, not health or longevity.

Risk:

High.

Required fix:

Revise the claim.

Better version:

```text id="smd6ue"
Traditional cultural elements can be analyzed as part of an architectural environment that supports social interaction, orientation, and everyday practices associated with active longevity.
```

Additional source needed:

A verified source on environmental factors, social participation, aging, or active longevity.

### Problem 2. Architectural description used as causal evidence

Claim:

```text id="og6mfg"
The spatial design directly increases the active lifespan of older adults.
```

Problem:

Architectural description alone cannot support a direct causal health claim.

Risk:

Critical.

Required fix:

Remove direct causality or add empirical evidence.

Better version:

```text id="vkm07l"
The spatial design creates conditions that may support mobility, social interaction, and everyday activity.
```

### Problem 3. Broad historical claim with weak support

Claim:

```text id="2h4nj7"
All contemporary Chinese architecture preserves traditional cultural memory.
```

Problem:

The claim is too broad and not supported by the cited source.

Risk:

High.

Required fix:

Narrow the claim.

Better version:

```text id="h2t6e4"
In the analyzed examples, selected traditional cultural elements are used to construct visual and symbolic links with cultural memory.
```

## 12. Active longevity citation warning

Claims about active longevity require field-appropriate support.

Acceptable supported claim types:

* architectural environments may support social interaction;
* spatial organization may influence mobility practices;
* familiar cultural symbols may affect perception of place;
* everyday practices can be considered in relation to environmental design.

High-risk unsupported claim types:

* architecture directly extends life expectancy;
* traditional symbols improve health;
* cultural memory causes longevity;
* architectural design proves active aging outcomes.

Required action:

All active longevity claims must be checked against sources from:

* gerontology;
* environmental psychology;
* urban studies;
* public health;
* social participation research;
* age-friendly environment studies.

## 13. Reference function audit

Each source should have a clear function.

| Source      | Current function       | Problem            | Required action                |
| ----------- | ---------------------- | ------------------ | ------------------------------ |
| Reference A | cultural memory theory | acceptable         | verify bibliographic details   |
| Reference B | semiotic analysis      | acceptable         | check page reference if needed |
| Reference C | architecture symbolism | partially relevant | connect more precisely         |
| Reference D | active longevity       | incomplete         | verify source and claim        |
| Reference E | health claim support   | weak               | replace or narrow claim        |
| Reference F | background citation    | decorative         | remove or use analytically     |

## 14. Decorative citation problems

Several citations appear at the end of broad paragraphs but do not clearly support a specific claim.

Problem pattern:

```text id="5z8pse"
A paragraph makes five claims and ends with three citations.
```

Required fix:

Attach each citation to the exact claim it supports.

If a citation does not support a claim, remove it.

If a claim lacks support, add a verified source or revise the claim.

## 15. Required manual verification list

Before submission, manually verify:

1. All DOI numbers.
2. All page ranges.
3. All journal titles.
4. All author names.
5. All publication years.
6. All Russian source records.
7. All translated or transliterated titles.
8. All in-text citation and bibliography matches.
9. All active longevity claims.
10. All sources suspected of being AI-generated.

## 16. Repair plan

### Step 1. Remove critical risks

Remove or verify all sources marked:

```text id="1yx9qf"
[POSSIBLE FABRICATED REFERENCE]
[UNVERIFIABLE SOURCE]
[DOI MISMATCH]
```

### Step 2. Fix bibliography structure

Correct:

* author names;
* years;
* article titles;
* journal titles;
* volume;
* issue;
* page range;
* DOI;
* URL;
* publisher information.

### Step 3. Fix citation-claim alignment

For every cited claim:

1. identify the exact claim;
2. check whether the source supports it;
3. classify support level;
4. revise claim or replace source;
5. remove decorative citations.

### Step 4. Strengthen high-risk claims

For claims about active longevity:

* use field-appropriate sources;
* avoid direct health-effect claims without empirical evidence;
* frame claims through social interaction, mobility, orientation, and everyday practices.

### Step 5. Final pass

Confirm:

* every source is real;
* every citation supports the attached claim;
* every bibliography entry is cited;
* no fake DOI remains;
* no unsupported broad claim remains.

## 17. Final recommendation

The manuscript should not be submitted until the reference list has been fully verified.

The strongest repair strategy is not to increase the number of references. The strongest repair strategy is to make every citation perform a clear function and support a specific claim.

Final status:

```text id="m8gam4"
Reference audit not passed.
Manual verification required.
Submission not recommended yet.
```
