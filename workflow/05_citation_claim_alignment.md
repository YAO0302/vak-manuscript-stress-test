# Workflow 05: Citation-Claim Alignment

This workflow explains how to check whether each citation actually supports the claim it is attached to.

It is designed for Russian-language academic manuscripts prepared for ВАК journals and related scholarly publications.

## Purpose

The purpose of this workflow is to detect cases where a reference is real but is used incorrectly.

A source can be real, complete, and correctly formatted, but still fail if it does not support the manuscript's claim.

This workflow checks:

* whether each citation supports the exact claim;
* whether claims are too broad for the source;
* whether citations are decorative;
* whether citations are attached to the wrong sentence;
* whether source type matches claim type;
* whether active longevity claims have appropriate evidence;
* whether unsupported claims should be revised or removed.

## Core rule

A citation must support the exact claim it is attached to.

Do not use a source as general decoration.

Do not use a source from one field to support a claim from another field unless the connection is clearly explained.

Do not make the sentence more cautious in order to hide weak evidence.

Fix the claim, fix the evidence, or remove the citation.

## Required input

Before starting this workflow, prepare:

1. Current manuscript draft.
2. Full reference list.
3. In-text citations.
4. Reference audit report.
5. Source texts or reliable source summaries, if available.
6. Target journal requirements.
7. Citation integrity rules.

Use:

```text id="eml310"
workflow/04_reference_audit.md
prompts/05_citation_claim_alignment_checker.md
rules/citation_integrity_rules.md
checklists/reference_audit_checklist.md
```

## Step 1. Identify all cited claims

A cited claim is any sentence or paragraph that uses a citation.

For each cited claim, record:

| No. | Manuscript claim | Citation | Claim type                                                   | Location |
| --: | ---------------- | -------- | ------------------------------------------------------------ | -------- |
|   1 |                  |          | theoretical / historical / empirical / interpretive / causal |          |
|   2 |                  |          | theoretical / historical / empirical / interpretive / causal |          |
|   3 |                  |          | theoretical / historical / empirical / interpretive / causal |          |

Do not audit only the bibliography.

Audit the relationship between claim and citation.

## Step 2. Classify claim type

Each claim should be classified before checking support.

### Descriptive claim

Example:

```text id="r1fidn"
The analyzed building contains traditional decorative elements.
```

Needs:

* visual material;
* architectural description;
* plans;
* photographs;
* project documentation.

### Theoretical claim

Example:

```text id="zaq7no"
Cultural memory can be expressed through spatial and symbolic forms.
```

Needs:

* theoretical source;
* conceptual study;
* scholarly monograph;
* peer-reviewed article.

### Historical claim

Example:

```text id="aj76bi"
This architectural element derives from traditional Chinese spatial principles.
```

Needs:

* historical source;
* architectural history;
* cultural documentation;
* verified scholarly work.

### Interpretive claim

Example:

```text id="zxdxkg"
The motif functions as a sign of cultural continuity.
```

Needs:

* semiotic analysis;
* cultural theory;
* historical-cultural context;
* direct analysis of material.

### Comparative claim

Example:

```text id="y3705p"
The contemporary form transforms the traditional element.
```

Needs:

* comparable traditional and contemporary cases;
* comparison criteria;
* method explanation.

### Social practice claim

Example:

```text id="c7394p"
The spatial organization supports everyday interaction.
```

Needs:

* spatial analysis;
* urban studies;
* environmental psychology;
* observation;
* relevant literature.

### Health or active longevity claim

Example:

```text id="cyy51e"
The environment supports active longevity practices.
```

Needs:

* gerontology;
* public health;
* environmental psychology;
* age-friendly environment research;
* social participation research;
* mobility or everyday practice studies.

### Causal claim

Example:

```text id="yiqaio"
Architecture directly improves health outcomes.
```

Needs:

* empirical evidence;
* causal research design;
* field-appropriate data;
* strong methodological support.

If causal evidence is absent, revise the claim.

## Step 3. Check source function

For each citation, ask:

```text id="g0xse3"
What function does this source perform in the manuscript?
```

Possible citation functions:

* defines a concept;
* supports a historical claim;
* supports a theoretical framework;
* provides empirical data;
* supports a method;
* provides comparison material;
* supports interpretation;
* supports background context;
* supports a claim about active longevity;
* supports a claim about architecture or spatial environment.

If the function is unclear, the citation may be decorative.

## Step 4. Check exact support

For each cited claim, ask:

```text id="p4bxsj"
Does this source actually support this exact sentence?
```

Use these support levels:

```text id="oinz8g"
Directly supported
```

The source clearly supports the exact claim.

```text id="rwiv3i"
Partially supported
```

The source supports part of the claim, but the sentence is too broad.

```text id="3qo02c"
Weakly supported
```

The source is related to the topic but does not strongly support the claim.

```text id="hqrbfj"
Unsupported
```

The source does not support the claim.

```text id="hd3fhm"
Source unavailable
```

The source cannot be checked.

```text id="q7dsg8"
Citation mismatch
```

The source supports a different claim or belongs elsewhere.

## Step 5. Create an alignment table

Use this table:

| Claim | Citation | Source function | Support level                  | Problem | Required action |
| ----- | -------- | --------------- | ------------------------------ | ------- | --------------- |
|       |          |                 | Direct / Partial / Weak / None |         |                 |
|       |          |                 | Direct / Partial / Weak / None |         |                 |
|       |          |                 | Direct / Partial / Weak / None |         |                 |

Required actions may include:

* keep citation;
* narrow claim;
* move citation;
* add a stronger source;
* remove citation;
* remove claim;
* verify source;
* mark with `[SOURCE REQUIRED]`.

## Step 6. Detect decorative citations

A decorative citation does not perform a clear scholarly function.

Warning signs:

* citation is placed at the end of a paragraph with several different claims;
* the source is not discussed;
* the citation does not support a specific sentence;
* the source is included only to increase bibliography size;
* the source is from a different field;
* the source supports background but is used as proof;
* the paragraph would mean the same thing without the citation.

Required action:

* attach the citation to a specific claim;
* remove it;
* replace it with a verified relevant source;
* rewrite the paragraph so the source has a clear function.

## Step 7. Check claim scale

The scale of the claim must match the scale of the evidence.

Weak:

```text id="gkur87"
One building contains traditional elements; therefore, contemporary Chinese architecture transforms tradition in this way.
```

Problem:

One case cannot support a general claim about all contemporary Chinese architecture.

Stronger:

```text id="6duh2a"
The analyzed case demonstrates one possible way in which traditional cultural elements can be transformed in contemporary architectural space.
```

Check:

```text id="5uqyfh"
Does the evidence support the scale of the claim?
```

## Step 8. Check field match

The source field must match the claim type.

Examples:

* cultural theory source can support cultural interpretation;
* architectural theory source can support spatial or design interpretation;
* gerontology source can support active longevity concepts;
* public health source can support health-related claims;
* historical source can support historical origin claims.

High-risk mismatch:

```text id="38bixx"
A source about cultural symbolism is used to prove health improvement.
```

Required action:

* narrow the claim;
* add field-appropriate evidence;
* remove unsupported causal wording.

## Step 9. Check active longevity claims

Claims about active longevity require special caution.

Acceptable claims without direct health data:

```text id="3lcfwi"
The architectural environment can be analyzed through parameters associated with social interaction, mobility, orientation, and everyday practices.
```

High-risk claims:

```text id="ppfsy7"
Traditional architectural elements improve active longevity.
```

```text id="bqtxpo"
Cultural symbols increase life expectancy.
```

```text id="k7w95d"
Architecture directly improves the health of older adults.
```

If the manuscript does not contain empirical health evidence, use mechanism-based claims.

Recommended mechanism:

```text id="rsjg9q"
architectural environment
↓
spatial organization
↓
mobility / orientation / social interaction
↓
everyday practices
↓
active longevity context
```

## Step 10. Check citation placement

A citation should be placed near the claim it supports.

Weak pattern:

```text id="v3fmi5"
Paragraph contains five claims. Three citations appear only at the end.
```

Problem:

The reader cannot tell which source supports which claim.

Fix:

* split the paragraph;
* attach citations to specific claims;
* remove unsupported claims;
* add source explanation.

## Step 11. Check quotation and paraphrase accuracy

If the manuscript uses a direct quotation, check:

* exact wording;
* page number;
* translation accuracy;
* quotation marks;
* journal citation format.

If the manuscript paraphrases a source, check:

* no distortion of the source;
* no overgeneralization;
* no claim stronger than the source;
* correct attribution.

If page number is required but missing, mark:

```text id="rn9odn"
[VERIFY PAGE]
```

## Step 12. Check source availability

If the source text is not available, do not claim full support.

Use:

```text id="0wb45t"
[SOURCE UNAVAILABLE]
```

or:

```text id="bz04kj"
[VERIFY SOURCE SUPPORT]
```

A source cannot be treated as fully supporting a claim if only the title or abstract has been checked.

## Step 13. Repair unsupported claims

Use one of the following repair strategies.

### Strategy A. Narrow the claim

From:

```text id="zib34f"
Architecture improves active longevity.
```

To:

```text id="0z8vts"
Architectural environment can form conditions associated with social interaction, mobility, and everyday practices.
```

### Strategy B. Add a stronger source

Use when the claim is important and can be supported by verified literature.

### Strategy C. Move the citation

Use when the source supports another sentence, but not the current one.

### Strategy D. Remove the citation

Use when the citation is decorative.

### Strategy E. Remove the claim

Use when the claim cannot be supported.

### Strategy F. Mark for author verification

Use when source support cannot be checked.

```text id="xk9zj1"
[VERIFY SOURCE SUPPORT]
```

## Step 14. Produce the alignment report

The Citation-Claim Alignment Report should include:

1. Overall decision.
2. Major citation-claim risks.
3. Claim type classification.
4. Source function classification.
5. Alignment table.
6. Decorative citation list.
7. Unsupported claim list.
8. Active longevity claim warning.
9. Required source additions.
10. Required claim revisions.
11. Final decision.

## Step 15. Alignment decisions

Use one of the following decisions.

```text id="iegdhm"
Citation-claim alignment passed
```

Use only when citations support the claims.

```text id="u2cdwp"
Minor alignment correction required
```

Use when only small citation placement or wording issues remain.

```text id="zgvhct"
Major alignment revision required
```

Use when many sources only partially support claims.

```text id="3jnqeo"
Manual source verification required
```

Use when source texts are unavailable.

```text id="k8l6kn"
Do not submit
```

Use when unsupported high-risk claims remain.

## Step 16. Continue to hostile peer review

After citation-claim alignment, continue with hostile peer review.

Use:

```text id="i2dzma"
workflow/06_hostile_review.md
prompts/06_hostile_peer_reviewer.md
checklists/hostile_review_checklist.md
```

The hostile review should test whether the manuscript would survive strict academic criticism.

## Safe storage

Safe to store in repository:

* citation-claim alignment workflow;
* checklist;
* fictional examples;
* citation integrity rules.

Do not store:

* copyrighted source texts;
* private PDFs;
* full manuscript drafts;
* confidential supervisor comments;
* reviewer reports;
* paywalled materials.

## Final checklist

Before leaving this workflow, confirm:

* every cited claim has been identified;
* claim type has been classified;
* citation function is clear;
* support level is assessed;
* decorative citations are removed or repaired;
* broad claims are narrowed;
* active longevity claims are checked;
* unsupported claims are marked or removed;
* source availability is noted;
* final alignment decision is recorded.

## Final rule

A citation is successful only when the reader can see exactly which claim it supports and why that source is appropriate.
