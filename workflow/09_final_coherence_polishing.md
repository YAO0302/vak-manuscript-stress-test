# Workflow 09: Final Coherence Polishing

This workflow explains how to perform the final coherence and submission-readiness polish for a Russian-language academic manuscript prepared for a ВАК journal or related scholarly publication.

This step should be used after draft generation, reference audit, citation-claim alignment, hostile review, structural reconstruction, and argument-forward rewriting.

## Purpose

Final coherence polishing checks whether the manuscript works as one complete academic article.

It verifies that:

* title matches the argument;
* abstract matches the final manuscript;
* introduction matches the conclusion;
* research question is answered;
* object, subject, aim, and tasks are consistent;
* methodology matches the material;
* analysis supports the conclusion;
* citations support claims;
* Russian academic style is clear;
* target journal requirements are checked;
* no unresolved evidence markers remain.

This is not only language polishing.

It is the final logic, evidence, style, and submission-readiness check.

## Core rule

Do not polish a manuscript into submission if its logic is still broken.

Final polishing should not hide unresolved problems.

If the manuscript still contains missing material, unverifiable references, unsupported claims, or unresolved markers, it is not submission-ready.

Use markers honestly:

```text id="k0nkah"
[AUTHOR MUST PROVIDE MATERIAL]
[SOURCE REQUIRED]
[VERIFY REFERENCE]
[VERIFY DOI]
[VERIFY SOURCE SUPPORT]
[RESULT REQUIRES EVIDENCE]
[METHOD REQUIRES CLARIFICATION]
```

Do not remove these markers unless the underlying problem is actually fixed.

## Required input

Before starting this workflow, prepare:

1. Latest manuscript draft.
2. Journal Style Profile.
3. Structural Reconstruction Plan.
4. Argument-Forward Rewrite Report.
5. Reference Audit Report.
6. Citation-Claim Alignment Report.
7. Hostile Peer Review Report.
8. Target journal author guidelines.
9. Final submission checklist.
10. Verified reference list.

Use:

```text id="7h8sd9"
prompts/09_final_coherence_polisher.md
examples/final_coherence_report_example.md
checklists/final_submission_checklist.md
rules/vak_article_logic.md
rules/russian_academic_style.md
rules/citation_integrity_rules.md
rules/paragraph_task_rules.md
```

## Step 1. Confirm final polishing readiness

Final coherence polishing should begin only when:

* the research question is stable;
* article structure is stable;
* methodology is written;
* material is identified or explicitly marked;
* main analysis is written;
* conclusion is written;
* references have been audited;
* citation-claim alignment has been checked;
* hostile review risks have been addressed;
* structural reconstruction is complete.

If these conditions are not met, return to the earlier workflow.

Do not use final polishing to compensate for unfinished research logic.

## Step 2. Check the full manuscript chain

A complete manuscript should follow this chain:

```text id="0ngclo"
Research problem
↓
Research question
↓
Object and subject
↓
Aim
↓
Tasks
↓
Material
↓
Method
↓
Analysis
↓
Findings
↓
Conclusion
```

Check:

* Is the research problem specific?
* Is the research question explicit?
* Is the object broader than the subject?
* Does the aim follow from the research question?
* Do the tasks lead to the aim?
* Is the material sufficient?
* Does the method fit the material?
* Does the analysis use the method?
* Do findings follow from the analysis?
* Does the conclusion answer the research question?

If one link is weak, mark it before style polishing.

## Step 3. Check title, abstract, and conclusion consistency

The title, abstract, and conclusion must describe the same article.

Check the title:

* Does it match the actual object?
* Does it match the subject?
* Does it avoid unsupported claims?
* Does it match the target journal style?

Check the abstract:

* Does it contain relevance?
* Does it state the research gap?
* Does it state the aim?
* Does it mention material and method?
* Does it state only supported results?
* Does it match the conclusion?

Check the conclusion:

* Does it return to the aim?
* Does it answer the research question?
* Does it avoid new concepts?
* Does it avoid new sources?
* Does it avoid unsupported claims?

High-risk mismatch:

```text id="o6uy4g"
Title promises active longevity effects.
Abstract discusses cultural symbolism.
Conclusion discusses architectural health benefits.
```

Required fix:

Make all three parts describe the same argument.

## Step 4. Check introduction and conclusion alignment

The introduction opens the research problem.

The conclusion must close that same problem.

Check:

* Does the conclusion answer the problem introduced in the introduction?
* Does the conclusion address the stated aim?
* Are all tasks completed?
* Does the conclusion avoid claims not prepared in the introduction?
* Does the conclusion avoid new theoretical concepts?
* Does the conclusion avoid new evidence?

Strong alignment:

```text id="2q9rxw"
Introduction:
The article asks how traditional cultural elements are transformed in contemporary architectural environments associated with active longevity practices.

Conclusion:
The analysis shows that these elements are transformed from decorative or symbolic references into spatial components connected to social interaction, mobility, orientation, and everyday practices.
```

Weak alignment:

```text id="da95dr"
Introduction asks about cultural transformation.
Conclusion claims architecture improves health outcomes.
```

## Step 5. Check object, subject, aim, and tasks

Use this table:

| Element | Final version | Problem | Required action |
| ------- | ------------- | ------- | --------------- |
| Object  |               |         |                 |
| Subject |               |         |                 |
| Aim     |               |         |                 |
| Task 1  |               |         |                 |
| Task 2  |               |         |                 |
| Task 3  |               |         |                 |
| Task 4  |               |         |                 |
| Task 5  |               |         |                 |

Check:

* object is broader than subject;
* subject is precise;
* aim is achievable;
* each task is completed;
* no task is decorative;
* tasks match section order;
* conclusion returns to aim.

If a task is not completed in the article, remove it or add the missing section.

## Step 6. Check methodology, material, and analysis

The methodology must match the material and analysis.

Check:

* Is the material clearly named?
* Are selection criteria explained?
* Are methods explained?
* Are methods actually used in the analysis?
* Does the analysis apply the method to the material?
* Does the method produce the type of result claimed?
* Does the conclusion stay within the method's limits?

Weak final problem:

```text id="yl9qtu"
The article names semiotic analysis but the main body only describes examples.
```

Required fix:

Add analytical application:

```text id="x8ueci"
The cultural element should be interpreted as a sign, compared with its traditional function, and connected to its contemporary spatial role.
```

## Step 7. Check claim scale

The scale of the conclusion must match the scale of the evidence.

Check:

* Does one case support only one case-level conclusion?
* Do several cases support a comparative conclusion?
* Does the manuscript avoid universal claims?
* Does it avoid claiming all architecture works the same way?
* Does it avoid claiming direct active longevity effects without empirical data?

Weak:

```text id="sidqzd"
The analyzed building proves that traditional Chinese architecture improves active longevity.
```

Stronger:

```text id="lbn38r"
The analyzed case shows one possible way in which traditional cultural elements can participate in the formation of architectural environments associated with social interaction, mobility, and everyday practices.
```

## Step 8. Check active longevity claims

Claims about active longevity remain high-risk at the final stage.

Acceptable claim without empirical health data:

```text id="mq2zks"
Architectural environment can be analyzed through parameters associated with social interaction, mobility, orientation, and everyday practices.
```

High-risk claim:

```text id="ycvxwm"
Traditional architecture improves active longevity.
```

Critical-risk claim:

```text id="m8zqvm"
Traditional cultural symbols extend the life expectancy of older adults.
```

Final rule:

If the manuscript does not include empirical health evidence, avoid direct biological, medical, or life-expectancy claims.

Use environmental and practice-based mechanisms.

Recommended mechanism:

```text id="80ljl4"
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

## Step 9. Check citation and reference integrity

Before final submission, confirm:

* every source is real;
* every DOI is verified;
* every in-text citation appears in the bibliography;
* every bibliography entry is cited;
* every citation supports the exact claim;
* no decorative citations remain;
* no unverifiable sources remain unmarked;
* no fabricated references remain;
* high-risk claims have field-appropriate sources.

Use markers if needed:

```text id="vvw9c2"
[VERIFY REFERENCE]
[VERIFY DOI]
[VERIFY SOURCE SUPPORT]
[UNVERIFIABLE SOURCE]
[POSSIBLE FABRICATED REFERENCE]
[SOURCE REQUIRED]
```

A manuscript with unresolved reference problems is not submission-ready.

## Step 10. Check paragraph coherence

Every paragraph should perform one clear task.

Use this table:

| Paragraph | Function | Problem | Required action |
| --------- | -------- | ------- | --------------- |
| 1         |          |         |                 |
| 2         |          |         |                 |
| 3         |          |         |                 |
| 4         |          |         |                 |
| 5         |          |         |                 |

Possible paragraph functions:

* problem introduction;
* relevance justification;
* literature synthesis;
* research gap;
* concept definition;
* method explanation;
* material description;
* evidence presentation;
* analysis;
* interpretation;
* transition;
* section conclusion;
* final conclusion.

Check:

* Does the first sentence show the paragraph's function?
* Does the paragraph avoid repetition?
* Does the paragraph connect to the previous paragraph?
* Does the paragraph prepare the next paragraph?
* Does the paragraph support the research question?

If the paragraph has no clear task, rewrite or remove it.

## Step 11. Check section transitions

The manuscript should not feel like separate fragments.

Check transitions between:

* relevance and literature review;
* literature review and research gap;
* research gap and aim;
* aim and method;
* method and analysis;
* analysis and interpretation;
* interpretation and conclusion.

Useful Russian transition formulas:

```text id="v3i8sx"
Это позволяет перейти к рассмотрению...
```

```text id="x9tefm"
В связи с этим необходимо уточнить...
```

```text id="qv0uac"
На этом основании можно обратиться к анализу...
```

```text id="ts7kiz"
Следовательно, дальнейший анализ должен учитывать...
```

```text id="m7a5vz"
Данный вывод подготавливает анализ...
```

Use transitions only when they clarify logic.

Do not add empty transitions.

## Step 12. Check Russian academic style

The final manuscript should be formal, clear, precise, and readable.

Reduce:

```text id="8cgej4"
актуальность темы не вызывает сомнений
на сегодняшний день
в наше время
очень важный
огромную роль
нельзя не отметить
представляется возможным говорить о
данная проблематика
настоящее исследование не претендует на
мы не утверждаем, что
```

Prefer:

```text id="o0t6bf"
актуальность исследования обусловлена
анализ показывает
полученные результаты позволяют
научная значимость заключается в
связь данной проблемы рассматривается через
```

Check:

* no colloquial language;
* no artificial complexity;
* no empty academic decoration;
* no excessive defensive formulas;
* no unsupported universal claims;
* key terms are used consistently.

## Step 13. Check defensive formulas

Do not use defensive language as the main structure of the argument.

Avoid excessive use of:

```text id="r4ttqo"
This article does not claim that...
This study does not attempt to...
We do not argue that...
Настоящая статья не ставит целью...
Мы не утверждаем, что...
Это не означает, что...
```

Use positive analytical framing.

Weak:

```text id="hznt4p"
Настоящая статья не ставит целью доказать прямое влияние архитектуры на активное долголетие.
```

Stronger:

```text id="qw3dj8"
В статье связь архитектурной среды с активным долголетием рассматривается через параметры социальной активности, мобильности, ориентации и устойчивых повседневных практик.
```

## Step 14. Check terminology consistency

Key terms should not shift meaning across the manuscript.

Check terms such as:

* traditional culture;
* traditional cultural elements;
* cultural heritage;
* cultural memory;
* architectural environment;
* public space;
* spatial practices;
* active longevity;
* active aging;
* age-friendly environment.

Problem:

```text id="m1l0nv"
The manuscript uses traditional culture, cultural heritage, cultural memory, and cultural code as if they are identical.
```

Required fix:

Define the main term and explain related terms only when necessary.

## Step 15. Check abstract last

The abstract should be finalized only after the manuscript is stable.

Final abstract structure:

```text id="iwviny"
relevance
↓
research gap
↓
aim
↓
material and method
↓
main result
↓
contribution
```

Russian skeleton:

```text id="3m9bmy"
Актуальность исследования обусловлена [specific reason]. Несмотря на наличие исследований, посвященных [general topic], недостаточно изученным остается [specific gap]. Цель статьи состоит в [aim]. Материалом исследования выступают [material], анализ которых осуществляется с использованием [methods]. Проведенный анализ показывает, что [main supported result]. Научная значимость статьи заключается в [specific contribution].
```

Check:

* abstract does not include unsupported results;
* abstract does not include claims absent from the article;
* abstract matches the conclusion;
* abstract length matches journal rules.

## Step 16. Check title and keywords last

Finalize title and keywords after the abstract.

Title check:

* specific;
* not too broad;
* no unsupported causal claims;
* matches article content;
* matches target journal style.

Keyword check:

* 5-8 keywords unless journal requires otherwise;
* includes central concept;
* includes object;
* includes subject;
* includes field;
* includes method or theoretical frame if appropriate.

Example keywords:

```text id="pgbyxh"
традиционная китайская культура; архитектурная среда; активное долголетие; культурная память; пространственные практики; семиотический анализ
```

## Step 17. Check target journal requirements

Official journal guidelines override inferred style.

Check:

* article length;
* abstract length;
* keyword number;
* heading format;
* citation style;
* bibliography format;
* file format;
* author information;
* affiliation format;
* originality requirements;
* ethics policy;
* AI-use policy, if available;
* submission system requirements.

If requirements are unknown, mark:

```text id="t9i8r6"
[JOURNAL GUIDELINES REQUIRED]
```

## Step 18. Produce the Final Coherence Report

The Final Coherence Report should include:

1. Final decision.
2. Overall readiness score.
3. Research logic chain check.
4. Title-abstract-conclusion consistency.
5. Introduction-conclusion alignment.
6. Object-subject-aim-task check.
7. Methodology-material-analysis check.
8. Active longevity claim check.
9. Citation and reference check.
10. Paragraph coherence check.
11. Russian academic style check.
12. Target journal fit check.
13. Remaining markers.
14. Final revision priorities.
15. Submission decision.

Use example:

```text id="y2oz0j"
examples/final_coherence_report_example.md
```

## Step 19. Final decisions

Use one of the following decisions.

```text id="0lz9rz"
Ready for submission
```

Use only when all major checks are passed.

```text id="vztiy0"
Ready after minor formatting corrections
```

Use when the argument, references, and style are ready, but journal formatting remains.

```text id="13pi5z"
Minor revision required
```

Use when only small local revisions remain.

```text id="dt36gt"
Major revision required
```

Use when research logic, method, material, evidence, or conclusion still need repair.

```text id="2abz91"
Do not submit
```

Use when unresolved markers, unverifiable references, unsupported claims, or major logical breaks remain.

## Step 20. Continue to final submission checklist

After final coherence polishing, use:

```text id="dlu1rj"
checklists/final_submission_checklist.md
```

This checklist is the final gate before journal submission.

Do not submit if the checklist fails.

## Safe storage

Safe to store in repository:

* final coherence workflow;
* final coherence prompt;
* fictional examples;
* checklists;
* rules;
* phrasebank.

Do not store:

* private manuscript drafts;
* unpublished dissertation chapters;
* copyrighted journal articles;
* full target article texts;
* supervisor comments;
* reviewer correspondence;
* confidential research data.

## Final checklist

Before leaving this workflow, confirm:

* title matches manuscript content;
* abstract matches conclusion;
* introduction and conclusion are aligned;
* research question is answered;
* object and subject are consistent;
* aim and tasks are completed;
* methodology matches material;
* analysis supports conclusion;
* active longevity claims are controlled;
* references are verified;
* citations support claims;
* paragraphs have clear tasks;
* Russian academic style is clear;
* defensive formulas are minimized;
* target journal requirements are checked;
* all unresolved markers are fixed or explicitly reported.

## Final rule

Final coherence polishing is successful only when the manuscript reads as one complete, evidence-supported academic argument.

If the article only sounds polished, but the logic is unstable, it is not ready.
