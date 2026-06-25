# Workflow 06: Hostile Review

This workflow explains how to simulate a strict hostile peer review before submitting a Russian-language academic manuscript to a ВАК journal or related scholarly publication.

The purpose is not to make the manuscript sound more cautious.

The purpose is to find the strongest reasons a reviewer could reject it.

## Purpose

A hostile review tests whether the manuscript can survive serious academic criticism.

It should identify:

* unclear research question;
* weak актуальность;
* weak research gap;
* object-subject confusion;
* aim-task mismatch;
* decorative methodology;
* unsupported claims;
* citation problems;
* weak connection between method and conclusion;
* lack of material;
* unclear novelty;
* unsuitable journal fit;
* excessive defensive writing;
* logical breaks;
* conclusions that exceed evidence.

## Core rule

The reviewer should be strict but competent.

The review should attack the manuscript's logic, evidence, structure, and scholarly contribution.

It should not focus only on grammar.

A manuscript can be grammatically correct and still fail as an academic article.

## Required input

Before running hostile review, prepare:

1. Current manuscript draft.
2. Target journal style profile.
3. Reference audit report.
4. Citation-claim alignment report.
5. Research question.
6. Object and subject.
7. Aim and tasks.
8. Methodology.
9. Material description.
10. Target journal requirements, if available.

Use:

```text id="6w8cun"
prompts/06_hostile_peer_reviewer.md
checklists/hostile_review_checklist.md
rules/vak_article_logic.md
rules/method_question_alignment.md
rules/paragraph_task_rules.md
rules/citation_integrity_rules.md
```

## Step 1. Confirm review mode

Use hostile review after the manuscript has already passed at least a basic draft stage.

Do not use hostile review too early if the manuscript is only a skeleton.

Choose one mode:

### Mode A. Full manuscript hostile review

Use when the full article draft is available.

### Mode B. Introduction-only hostile review

Use when the introduction contains the main research logic and needs stress testing.

### Mode C. Methodology hostile review

Use when the main risk is method-question mismatch.

### Mode D. Conclusion hostile review

Use when the conclusion may exceed the evidence.

### Mode E. Journal-fit hostile review

Use when the manuscript may not match the target journal.

## Step 2. Test the research question

Ask:

```text id="h6v25o"
What exact research question does this manuscript answer?
```

Reviewer attack questions:

* Is the question explicit?
* Is it narrow enough for one article?
* Does the article actually answer it?
* Does the question match the material?
* Does the question match the method?
* Does the conclusion answer the same question?
* Is the question only a topic disguised as a question?

Common rejection reason:

```text id="e8omdx"
The manuscript has a topic but no clear research question.
```

Required repair:

Rewrite the research question before revising the rest of the manuscript.

## Step 3. Test актуальность and research gap

Ask:

```text id="v11lox"
Does the manuscript explain why this problem matters and what remains unresolved?
```

Reviewer attack questions:

* Is актуальность specific?
* Does the literature review create a real gap?
* Is the gap stated clearly?
* Is the gap connected to the aim?
* Is the gap invented or unsupported?
* Does the manuscript rely on empty relevance formulas?

Weak:

```text id="7prbl1"
Актуальность темы не вызывает сомнений.
```

Stronger:

```text id="y823ht"
Актуальность исследования обусловлена необходимостью анализа способов трансформации традиционных культурных элементов в современной архитектурной среде.
```

Common rejection reason:

```text id="lki7rr"
The manuscript does not demonstrate a clear research gap.
```

## Step 4. Test object, subject, aim, and tasks

Ask:

```text id="8le559"
Do object, subject, aim, and tasks form one coherent research chain?
```

Reviewer attack questions:

* Is the object broader than the subject?
* Is the subject specific enough?
* Does the aim follow from the research gap?
* Are tasks concrete?
* Does each task correspond to a section or analytical step?
* Are tasks completed in the article?
* Does the conclusion return to the aim?

Common rejection reasons:

```text id="33tctm"
Object and subject are confused.
```

```text id="c7l21r"
The aim is too broad for one article.
```

```text id="1lvoll"
The tasks are decorative and do not organize the research.
```

## Step 5. Test methodology

Ask:

```text id="xjy3gi"
Can the selected method actually answer the research question?
```

Reviewer attack questions:

* Are methods only listed?
* Is each method explained?
* Is each method applied in the analysis?
* Does the method match the material?
* Does the method match the claim type?
* Does the method support the conclusion?
* Are there methods named but never used?

Weak:

```text id="luo3ph"
The article uses comparative, semiotic, and historical-cultural methods.
```

Stronger:

```text id="pf4mlt"
Comparative analysis is used to identify differences between traditional and contemporary architectural forms; semiotic analysis makes it possible to interpret cultural elements as signs; historical-cultural analysis connects these signs to cultural memory and continuity.
```

Common rejection reason:

```text id="9gb05i"
The methodology is decorative and does not explain how the findings were produced.
```

## Step 6. Test material

Ask:

```text id="oijm3b"
What exactly is being analyzed?
```

Reviewer attack questions:

* Is the material named?
* Are cases, texts, objects, images, or documents clearly identified?
* Are selection criteria explained?
* Is the material sufficient for the research question?
* Is the material sufficient for the conclusion?
* Are examples only illustrative?
* Does the material allow comparison?

If material is missing, mark:

```text id="jz4x0q"
[AUTHOR MUST PROVIDE MATERIAL]
```

Common rejection reason:

```text id="1kzfjy"
The manuscript makes claims without clearly defined research material.
```

## Step 7. Test evidence and claims

Ask:

```text id="7zicnq"
Does each major claim have appropriate evidence?
```

Reviewer attack questions:

* Are claims supported?
* Are claims too broad?
* Are claims causal without evidence?
* Are claims based on narrow material?
* Are theoretical claims supported by theory?
* Are empirical claims supported by data?
* Are health or active longevity claims supported by field-appropriate sources?

High-risk words:

```text id="cey5t1"
proves
ensures
causes
determines
directly influences
improves
обеспечивает
доказывает
определяет
напрямую влияет
улучшает
```

Common rejection reason:

```text id="i5mdyp"
The conclusions exceed the evidence presented in the manuscript.
```

## Step 8. Test active longevity claims

Claims about active longevity are high-risk.

Ask:

```text id="i6v8wq"
Does the manuscript make direct health, biological, or life-expectancy claims?
```

Reviewer attack questions:

* Is active longevity defined?
* Is the connection to architecture explained?
* Are the sources field-appropriate?
* Does the manuscript use gerontology, public health, environmental psychology, or age-friendly environment research?
* Does the manuscript make claims that only empirical data could support?
* Does the manuscript confuse cultural interpretation with health evidence?

Weak:

```text id="t43e1b"
Traditional architectural elements improve active longevity.
```

Stronger:

```text id="3gq8ps"
Traditional cultural elements can be analyzed as part of an architectural environment that supports social interaction, mobility, orientation, and everyday practices associated with active longevity.
```

Common rejection reason:

```text id="266qpx"
The manuscript makes health-related claims that are not supported by the selected method or evidence.
```

## Step 9. Test citation integrity

Ask:

```text id="2n55kj"
Are references real, relevant, and correctly attached to claims?
```

Reviewer attack questions:

* Are all references real?
* Are DOI numbers verified?
* Are there possible fabricated references?
* Does every in-text citation appear in the bibliography?
* Is every bibliography entry cited?
* Do citations support the exact claims?
* Are citations decorative?
* Are sources from the correct field?

Use markers:

```text id="x3mkm3"
[VERIFY REFERENCE]
[VERIFY DOI]
[UNVERIFIABLE SOURCE]
[SOURCE REQUIRED]
[POSSIBLE FABRICATED REFERENCE]
```

Common rejection reason:

```text id="eym9oy"
The manuscript uses citations as decoration rather than as evidence.
```

## Step 10. Test literature review

Ask:

```text id="bldsf8"
Does the literature review synthesize scholarship or only list authors?
```

Reviewer attack questions:

* Are sources grouped by research direction?
* Does the literature review create the gap?
* Are important fields missing?
* Are sources recent enough?
* Are Russian and international sources balanced, if appropriate?
* Are references used analytically?
* Does the literature review prepare the method?

Weak:

```text id="84iqh8"
Ivanov studied X. Petrov studied Y. Sidorov studied Z.
```

Stronger:

```text id="mtasvz"
Existing research can be divided into several directions. However, these approaches do not fully explain...
```

Common rejection reason:

```text id="4m6t8w"
The literature review is descriptive and does not establish the manuscript's contribution.
```

## Step 11. Test article structure

Ask:

```text id="n3ni4y"
Does the section order help the argument develop logically?
```

Reviewer attack questions:

* Does the introduction establish the problem?
* Does methodology appear before analysis?
* Are key concepts defined before use?
* Does the analysis follow the tasks?
* Does the conclusion appear only after evidence?
* Are sections balanced?
* Are paragraphs ordered logically?

Recommended structure:

```text id="ewxg2v"
Introduction
↓
Literature review / theoretical framework
↓
Methodology and material
↓
Main analysis
↓
Discussion or interpretation
↓
Conclusion
```

Common rejection reason:

```text id="o2cw2o"
The manuscript contains useful material but is structurally disorganized.
```

## Step 12. Test paragraph logic

Ask:

```text id="efff74"
Does each paragraph have one clear task?
```

Reviewer attack questions:

* Does the paragraph introduce a problem?
* Define a concept?
* Present evidence?
* Analyze evidence?
* Interpret results?
* Transition to the next step?
* Or does it mix several tasks at once?

Common rejection reasons:

```text id="hwe7n9"
The paragraphs are repetitive.
```

```text id="sx5758"
The manuscript describes material but does not analyze it.
```

```text id="pydxpy"
The text introduces technical detail before the research problem is clear.
```

## Step 13. Test novelty and significance

Ask:

```text id="5weocm"
What exactly is new in this manuscript?
```

Reviewer attack questions:

* Is novelty specific?
* Is novelty overstated?
* Does novelty follow from the analysis?
* Is the contribution theoretical, methodological, material-based, interpretive, or practical?
* Does the manuscript claim that no one has studied the topic before without proof?

Weak:

```text id="3ievqd"
This topic has not been studied before.
```

Stronger:

```text id="bnbxer"
The novelty lies in interpreting traditional cultural elements not only as decorative forms, but as components of architectural environment connected to spatial practices.
```

Common rejection reason:

```text id="5rcnjg"
The manuscript does not clearly state its scholarly contribution.
```

## Step 14. Test target journal fit

Ask:

```text id="lpy9fs"
Why should this manuscript be published in this target journal?
```

Reviewer attack questions:

* Does the topic fit the journal field?
* Does the article match the journal's article type?
* Does it follow the journal's structure?
* Does the citation style match?
* Does the manuscript match the journal's ВАК specialty?
* Are official author guidelines checked?
* Does the manuscript appear too interdisciplinary for the journal without clear framing?

Common rejection reason:

```text id="5b7zya"
The manuscript does not clearly fit the target journal's scope.
```

## Step 15. Produce the hostile review report

The hostile review report should include:

1. Simulated editorial decision.
2. Main rejection risks.
3. Research question assessment.
4. Method-question mismatch.
5. Object-subject-aim-task consistency.
6. Logical breaks.
7. Identification gaps.
8. Theoretical framework problems.
9. Literature review weaknesses.
10. Evidence and material problems.
11. Citation risks.
12. Novelty assessment.
13. Paragraph-level problems.
14. Likely reviewer questions.
15. Required revision actions.
16. Final recommendation.

Use example:

```text id="p4r54w"
examples/hostile_review_report_example.md
```

## Step 16. Assign rejection risk level

Use one of the following levels.

```text id="5tvfyc"
Low risk
```

The manuscript is coherent and only needs polishing.

```text id="6a04cu"
Medium risk
```

The manuscript is promising but needs targeted revision.

```text id="jzh9iq"
High risk
```

The manuscript has serious logic, method, evidence, or citation problems.

```text id="rwv99t"
Critical risk
```

The manuscript should not be submitted because it contains unsupported claims, unverifiable references, or a broken research design.

## Step 17. Hostile review decisions

Use one of the following decisions.

```text id="2l94o6"
Acceptable after minor revision
```

Use only when the argument is stable and problems are local.

```text id="3a3x5f"
Major revision required
```

Use when logic, structure, method, or evidence need substantial repair.

```text id="4m8no4"
Rebuild before submission
```

Use when the manuscript has a promising topic but the structure and argument must be reconstructed.

```text id="f6v5yr"
Do not submit
```

Use when the manuscript contains critical reference, evidence, or method failures.

## Step 18. Convert review into repair plan

After hostile review, do not immediately polish style.

First create a structural repair plan.

Use:

```text id="5vv6w5"
workflow/07_structural_reconstruction.md
prompts/07_structural_reconstruction_planner.md
```

Hostile review identifies the damage.

Structural reconstruction decides how to repair it.

## Safe storage

Safe to store in repository:

* hostile review workflow;
* hostile review checklist;
* fictional hostile review example;
* prompts and rules.

Do not store:

* private manuscript drafts;
* confidential supervisor comments;
* reviewer correspondence;
* real reviewer reports;
* copyrighted article PDFs;
* full target journal texts.

## Final checklist

Before leaving this workflow, confirm:

* research question has been attacked;
* object, subject, aim, and tasks have been tested;
* methodology has been tested against the question;
* material has been tested against the conclusion;
* citations have been checked for risk;
* high-risk claims have been identified;
* active longevity claims have been stress-tested;
* logical breaks have been listed;
* likely reviewer objections have been written;
* required revisions have been prioritized;
* final hostile review decision has been recorded.

## Final rule

A useful hostile review is not polite reassurance.

It is a controlled rejection simulation that shows what must be fixed before submission.
