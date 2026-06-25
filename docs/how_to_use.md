# How to Use

This guide explains how to use the VAK Manuscript Stress Test workflow.

The project is designed for Russian academic writing, especially manuscripts prepared for ВАК journals and related scholarly publications.

## 1. What you need before starting

Prepare the following materials:

1. Several articles from the target ВАК journal.
2. Your manuscript draft or research plan.
3. Your bibliography or reference list.
4. Target journal requirements, if available.
5. Your research information:

   * topic;
   * research question;
   * object of research;
   * subject of research;
   * aim;
   * tasks;
   * methods;
   * material;
   * expected contribution.

Recommended number of target journal articles:

3–10 articles.

Do not upload these articles to this public GitHub repository.

Use them only in your local workspace or private AI workspace.

## 2. Recommended workflow

Use the project in this order:

1. Analyze target journal articles.
2. Create a journal style profile.
3. Generate or revise the manuscript draft.
4. Audit references.
5. Check citation-claim alignment.
6. Simulate hostile peer review.
7. Create a structural reconstruction plan.
8. Rewrite key sections with argument-forward prose.
9. Run the final submission check.

## 3. Step 1: Analyze target journal articles

Use:

```text
prompts/01_article_style_analyzer.md
```

Upload or provide the selected target journal articles to your AI tool.

Then ask the AI to analyze:

* article structure;
* abstract pattern;
* introduction logic;
* methodology language;
* argumentation model;
* citation behavior;
* conclusion pattern;
* sentence-level academic style.

The output should be a Journal Style Analysis Report.

Important rule:

Do not ask the AI to copy the style of a specific author.

Ask it to extract high-level journal writing patterns.

## 4. Step 2: Create a journal style profile

Use:

```text
templates/journal_style_profile_template.md
```

Take the results from the style analysis and fill in the template.

The journal style profile should describe:

* general journal style;
* preferred article structure;
* title pattern;
* abstract pattern;
* introduction pattern;
* methodology pattern;
* theoretical framework pattern;
* argumentation model;
* citation behavior;
* paragraph structure;
* conclusion pattern;
* risks to avoid.

This profile becomes the main instruction for drafting and revising future manuscripts for that journal.

## 5. Step 3: Generate or revise a manuscript draft

Use the journal style profile together with your own research information.

Provide the AI with:

```text
Topic:
Research question:
Object:
Subject:
Aim:
Tasks:
Methods:
Material:
Expected contribution:
Target journal style profile:
```

Ask the AI to generate or revise:

* title;
* abstract;
* keywords;
* introduction;
* methodology;
* article structure;
* conclusion.

Do not allow the AI to invent references, data, or results.

If the evidence is missing, the AI should mark it as missing instead of fabricating it.

## 6. Step 4: Audit references

Use:

```text
prompts/04_reference_reality_checker.md
checklists/reference_audit_checklist.md
```

Provide the AI with:

* manuscript draft;
* bibliography;
* DOI links, if available;
* source PDFs or links, if available;
* target journal requirements, if available.

The reference audit should check:

* whether each reference appears real;
* whether DOI, year, journal, volume, issue, and pages are consistent;
* whether every in-text citation has a bibliography entry;
* whether every bibliography entry is cited;
* whether each citation supports the claim attached to it;
* whether any reference looks fabricated or unverifiable.

Important rule:

The AI must not invent missing references.

Every unverifiable source must be marked for manual checking.

## 7. Step 5: Check citation-claim alignment

For every important claim, ask:

```text
Does the cited source actually support this claim?
```

Classify claims as:

* supported;
* partially supported;
* weakly supported;
* unsupported;
* requires stronger evidence;
* citation does not match claim.

This step is especially important for broad claims about:

* culture;
* architecture;
* health;
* active longevity;
* social behavior;
* tradition;
* identity;
* historical influence;
* causality.

## 8. Step 6: Simulate hostile peer review

Use:

```text
prompts/06_hostile_peer_reviewer.md
checklists/hostile_review_checklist.md
```

Provide:

* manuscript draft;
* journal style profile;
* research question;
* object;
* subject;
* aim;
* tasks;
* methods;
* material;
* bibliography;
* reference audit report.

Ask the AI to simulate strict reviewers.

The review should identify:

* possible rejection reasons;
* method-question mismatch;
* logical breaks;
* weak novelty;
* unsupported claims;
* identification gaps;
* theoretical framework problems;
* weak literature review;
* target journal mismatch.

The output should be a Hostile Peer Review Report.

## 9. Step 7: Create a structural reconstruction plan

After the hostile review, ask the AI to create a reconstruction plan.

The plan should specify:

* what to move;
* what to remove;
* what to expand;
* what to merge;
* what to rewrite first;
* which claims need evidence;
* which sections are not ready.

Do not begin rewriting before the structure is clear.

## 10. Step 8: Rewrite with argument-forward prose

Use:

```text
prompts/08_argument_forward_rewriter.md
rules/banned_defensive_formulas.md
```

The goal is to rewrite the manuscript without turning it into defensive prose.

Avoid unnecessary formulas such as:

* "we do not claim that...";
* "this article does not attempt to...";
* "this does not mean that...";
* "our purpose is not to prove...";
* "мы не утверждаем, что...";
* "это не означает, что...";
* "настоящая статья не ставит целью...".

Preferred strategy:

State the positive analytical claim directly.

Weak version:

```text
Мы не утверждаем, что традиционная китайская культура напрямую определяет активное долголетие.
```

Stronger version:

```text
Связь между элементами традиционной китайской культуры и активным долголетием рассматривается через параметры среды, влияющие на повседневные практики, социальное взаимодействие и восприятие пространства.
```

## 11. Step 9: Final submission check

Before submission, check:

* Does the manuscript have a clear research question?
* Does the method answer the research question?
* Are object, subject, aim, and tasks consistent?
* Does every paragraph have a clear function?
* Are references real and verified?
* Do citations support the claims?
* Is the novelty clear?
* Does the conclusion answer the research question?
* Does the article fit the target journal?
* Does the text avoid defensive over-explanation?

## 12. Recommended prompt order

Use this order in your AI tool:

```text
1. prompts/01_article_style_analyzer.md
2. templates/journal_style_profile_template.md
3. prompts/04_reference_reality_checker.md
4. checklists/reference_audit_checklist.md
5. prompts/06_hostile_peer_reviewer.md
6. checklists/hostile_review_checklist.md
7. rules/banned_defensive_formulas.md
8. prompts/08_argument_forward_rewriter.md
```

## 13. What not to do

Do not:

* upload copyrighted journal PDFs to this public repository;
* copy paragraphs from target journal articles;
* imitate one author's distinctive style;
* generate fake references;
* submit AI-generated text without checking it;
* use citations that do not support the claim;
* use hostile review as a reason to add excessive defensive language;
* hide weak logic behind complex academic wording.

## 14. Minimal example workflow

Example use case:

1. The user selects 5 articles from a target ВАК journal.
2. The user uploads them to a private AI workspace.
3. The AI creates a Journal Style Analysis Report.
4. The user fills the Journal Style Profile Template.
5. The user provides a draft article.
6. The AI checks the bibliography.
7. The AI simulates hostile peer review.
8. The AI proposes a structural reconstruction plan.
9. The AI rewrites the introduction and methodology.
10. The user manually verifies sources and revises the final manuscript.

## 15. Final rule

This workflow is not a substitute for research.

It is a stress-test system.

It helps identify weak logic, weak method, weak evidence, weak references, and weak structure before submission.
