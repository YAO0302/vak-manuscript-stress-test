# Workflow 03: Draft Generation

This workflow explains how to generate or revise a Russian-language ВАК-style academic manuscript draft using a Journal Style Profile, author-provided research information, verified sources, and structured writing rules.

This workflow should be used after the target journal articles have been analyzed and a Journal Style Profile has been created.

## Purpose

The purpose of this workflow is to create a controlled academic draft that follows:

* the target journal style profile;
* Russian academic writing standards;
* ВАК-style article logic;
* verified research information;
* citation integrity rules;
* method-question alignment rules;
* paragraph task rules.

Draft generation is not the final step.

The draft must still pass reference auditing, hostile peer review, structural reconstruction, argument-forward rewriting, and final coherence checking.

## Core rule

Do not invent research.

Do not invent references.

Do not invent data.

Do not invent DOI numbers.

Do not invent article results.

If required information is missing, mark it clearly.

Use markers:

```text
[AUTHOR MUST PROVIDE]
[SOURCE REQUIRED]
[VERIFY REFERENCE]
[VERIFY DOI]
[RESULT REQUIRES EVIDENCE]
[AUTHOR MUST PROVIDE MATERIAL]
[METHOD REQUIRES CLARIFICATION]
```

## Required input

Before generating a draft, prepare the following:

1. Target journal style profile.
2. Manuscript topic.
3. Field and ВАК specialty, if known.
4. Research problem.
5. Research question.
6. Object of research.
7. Subject of research.
8. Aim.
9. Tasks.
10. Material.
11. Methodology.
12. Verified or draft reference list.
13. Author notes.
14. Any supervisor requirements.
15. Target journal author guidelines, if available.

Use:

```text
templates/journal_style_profile_template.md
templates/vak_article_structure.md
templates/abstract_template.md
templates/introduction_template.md
templates/methodology_template.md
templates/conclusion_template.md
```

## Main prompt

Use:

```text
prompts/03_vak_draft_writer.md
```

The draft writer should receive:

* Journal Style Profile;
* research information;
* verified references or draft bibliography;
* manuscript structure requirements;
* writing rules;
* evidence warnings;
* target journal requirements.

## Step 1. Check input completeness

Before drafting, check whether the following are known.

| Element            | Status | Notes |
| ------------------ | ------ | ----- |
| Topic              |        |       |
| Target journal     |        |       |
| Field              |        |       |
| ВАК specialty      |        |       |
| Research problem   |        |       |
| Research question  |        |       |
| Object             |        |       |
| Subject            |        |       |
| Aim                |        |       |
| Tasks              |        |       |
| Material           |        |       |
| Methods            |        |       |
| References         |        |       |
| Journal guidelines |        |       |

If essential information is missing, do not silently fill it.

Mark it.

Example:

```text
Материалом исследования выступают [AUTHOR MUST PROVIDE MATERIAL].
```

## Step 2. Select draft mode

Choose one of the following modes.

### Mode A. Generate full draft

Use when the author has provided enough information.

Required:

* topic;
* object;
* subject;
* aim;
* tasks;
* material;
* method;
* main argument;
* references.

### Mode B. Generate article skeleton

Use when research information is incomplete.

Output:

* title options;
* abstract skeleton;
* introduction skeleton;
* section plan;
* methodology skeleton;
* conclusion skeleton;
* missing information list.

### Mode C. Revise existing draft

Use when the author already has a manuscript.

Input:

* existing draft;
* target journal profile;
* hostile review report, if available;
* reference audit report, if available;
* revision goal.

### Mode D. Generate only one section

Use when only one section is needed.

Possible sections:

* title;
* abstract;
* introduction;
* methodology;
* literature review;
* theoretical framework;
* main analysis;
* conclusion.

## Step 3. Build the article logic chain

Before writing, stabilize this chain:

```text
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

If the chain is unstable, draft only a skeleton and request missing author information.

Use:

```text
rules/vak_article_logic.md
rules/method_question_alignment.md
checklists/method_question_fit_checklist.md
```

## Step 4. Draft the title

A good title should identify:

* object;
* subject;
* analytical focus;
* field context.

Avoid overly broad titles.

Weak:

```text
Traditional Culture and Active Longevity
```

Stronger:

```text
Transformation of Traditional Chinese Cultural Elements in Contemporary Architectural Environments Associated with Active Longevity Practices
```

For Russian manuscripts:

```text
Трансформация элементов традиционной китайской культуры в современной архитектурной среде в контексте практик активного долголетия
```

Do not include claims in the title that the article cannot support.

## Step 5. Draft the abstract

Use:

```text
templates/abstract_template.md
```

Recommended abstract structure:

```text
Актуальность
↓
Research gap
↓
Aim
↓
Material and method
↓
Main result
↓
Contribution
```

Abstract skeleton:

```text
Актуальность исследования обусловлена [specific reason]. Несмотря на наличие исследований, посвященных [general topic], недостаточно изученным остается [specific gap]. Цель статьи состоит в [aim]. Материалом исследования выступают [material], анализ которых осуществляется с использованием [methods]. Проведенный анализ показывает, что [main supported result]. Научная значимость статьи заключается в [specific contribution].
```

Do not write a final abstract before the article logic is stable.

## Step 6. Draft keywords

Use 5-8 keywords unless the journal requires another number.

Recommended keyword types:

* central concept;
* object;
* subject;
* method;
* field;
* cultural context;
* social or spatial concept.

Example:

```text
традиционная китайская культура; архитектурная среда; активное долголетие; культурная память; пространственные практики; семиотический анализ
```

## Step 7. Draft the introduction

Use:

```text
templates/introduction_template.md
```

The introduction should include:

1. specific relevance;
2. literature context;
3. research gap;
4. object;
5. subject;
6. aim;
7. tasks;
8. material;
9. methods;
10. transition to analysis.

Recommended Russian structure:

```text
Актуальность исследования обусловлена [specific reason].

В научной литературе можно выделить несколько направлений изучения данной проблемы: [direction 1], [direction 2], [direction 3]. Вместе с тем недостаточно раскрытым остается вопрос о [research gap].

Объектом исследования является [object]. Предметом исследования выступает [subject]. Цель статьи состоит в [aim]. Для достижения поставленной цели решаются следующие задачи: [tasks].

Материалом исследования выступают [material]. Методологическую основу исследования составляют [methods].
```

Avoid:

```text
Актуальность темы не вызывает сомнений.
```

## Step 8. Draft methodology

Use:

```text
templates/methodology_template.md
```

The methodology must explain:

* what method is used;
* why this method fits the research question;
* what material is analyzed;
* how the material is selected;
* how the analysis is performed;
* what type of result the method can produce.

Weak:

```text
В статье используются сравнительный, семиотический и историко-культурный методы.
```

Stronger:

```text
Сравнительный анализ используется для сопоставления традиционных и современных архитектурных форм; семиотический анализ позволяет рассмотреть культурные элементы как систему знаков; историко-культурный подход обеспечивает интерпретацию этих элементов в контексте культурной памяти и преемственности.
```

## Step 9. Draft literature review

The literature review should not list authors mechanically.

It should group sources by approach.

Recommended structure:

1. Research direction 1.
2. Research direction 2.
3. Research direction 3.
4. What remains insufficiently studied.
5. How the current article addresses the gap.

Weak:

```text
Ivanov studied X. Petrov studied Y. Sidorov studied Z.
```

Stronger:

```text
В существующей литературе можно выделить несколько направлений исследования данной проблемы. Первое связано с..., второе сосредоточено на..., третье рассматривает.... Вместе с тем указанные подходы не позволяют в полной мере раскрыть...
```

If sources are not verified, mark them:

```text
[VERIFY REFERENCE]
```

## Step 10. Draft theoretical framework

Use this section only if the article needs explicit theoretical concepts.

Define only concepts that will be used in the analysis.

Possible concepts:

* traditional cultural element;
* cultural memory;
* architectural environment;
* spatial practice;
* active longevity;
* symbolic form;
* semiotic interpretation.

Do not introduce theory as decoration.

Weak:

```text
The article mentions many theorists but does not use their concepts.
```

Stronger:

```text
В рамках настоящей статьи традиционные культурные элементы рассматриваются как визуальные, символические и пространственные формы, сохраняющие связь с культурной памятью и получающие новые функции в современной архитектурной среде.
```

## Step 11. Draft main analysis

The main analysis should apply the method to the material.

Each analytical unit should follow:

```text
claim
↓
material
↓
method application
↓
interpretation
↓
connection to research question
```

Recommended unit structure:

1. State the analytical claim.
2. Present the material.
3. Apply the method.
4. Explain what the material shows.
5. Connect the result to the research question.

Example structure:

```text
В анализируемом объекте [AUTHOR MUST PROVIDE MATERIAL] традиционный культурный элемент проявляется через [specific form]. Семиотический анализ позволяет рассмотреть данный элемент как знак, связанный с [meaning]. В современной архитектурной среде его функция изменяется: он не только сохраняет связь с культурной памятью, но и участвует в организации [spatial function]. Это позволяет интерпретировать данный элемент как компонент среды, связанный с [social interaction / mobility / everyday practices].
```

## Step 12. Control active longevity claims

Claims about active longevity are high-risk.

Do not claim:

```text
architecture directly extends life
traditional elements improve health
cultural symbols ensure longevity
```

unless the manuscript has empirical evidence.

Use safer mechanism-based wording:

```text
Архитектурная среда может формировать условия для социальной активности, мобильности, ориентации и устойчивых повседневных практик.
```

Use:

```text
rules/method_question_alignment.md
rules/citation_integrity_rules.md
checklists/logical_break_checklist.md
```

## Step 13. Draft conclusion

Use:

```text
templates/conclusion_template.md
```

The conclusion should:

* return to the aim;
* summarize supported findings;
* answer the research question;
* state contribution;
* avoid new sources;
* avoid new concepts;
* avoid unsupported claims.

Conclusion skeleton:

```text
Проведенный анализ был направлен на [aim]. В результате исследования установлено, что [main supported result].

Во-первых, [finding 1]. Во-вторых, [finding 2]. В-третьих, [finding 3].

Таким образом, [answer to research question]. Научная значимость исследования заключается в [specific contribution]. Дальнейшее изучение данной проблемы может быть связано с [future direction].
```

## Step 14. Apply Russian academic style rules

Use:

```text
rules/russian_academic_style.md
phrasebank/academic_russian_phrases.md
```

The draft should be:

* formal;
* precise;
* clear;
* analytical;
* non-colloquial;
* not artificially complicated;
* free from empty academic decoration.

Avoid:

```text
Актуальность темы не вызывает сомнений.
На сегодняшний день данная проблема является очень важной.
Настоящая статья не ставит целью доказать...
```

Prefer:

```text
Актуальность исследования обусловлена...
Проведенный анализ показывает...
Связь данной проблемы рассматривается через...
```

## Step 15. Apply paragraph task rules

Use:

```text
rules/paragraph_task_rules.md
```

Each paragraph should have one clear task.

Possible paragraph tasks:

* introduce problem;
* justify relevance;
* synthesize literature;
* identify gap;
* define concept;
* explain method;
* present material;
* analyze evidence;
* interpret result;
* transition;
* conclude.

If a paragraph has no task, remove or rewrite it.

## Step 16. Mark missing information

Never hide missing information.

Use clear markers.

Examples:

```text
[AUTHOR MUST PROVIDE MATERIAL]
[SOURCE REQUIRED]
[VERIFY REFERENCE]
[RESULT REQUIRES EVIDENCE]
[METHOD REQUIRES CLARIFICATION]
```

The presence of markers means the draft is not submission-ready.

Markers are useful because they prevent false precision.

## Step 17. Draft output format

A useful draft generation output should include:

1. Draft status.
2. Missing information list.
3. Proposed title options.
4. Abstract.
5. Keywords.
6. Article structure.
7. Draft text.
8. Citation warnings.
9. Claim risk warnings.
10. Next-step instructions.

## Step 18. Draft readiness decision

Use one of the following decisions.

```text
Ready for reference audit
```

Use when the draft has a stable argument but citations still need checking.

```text
Skeleton only
```

Use when author information is incomplete.

```text
Needs author input before drafting
```

Use when material, aim, or method is missing.

```text
Needs structural repair before reference audit
```

Use when the logic chain is unstable.

```text
Do not treat as submission-ready
```

Use when the draft contains unverified references, unsupported results, or unresolved markers.

## Common draft generation problems

### Problem 1. AI invents references

Fix:

Remove invented references and mark:

```text
[SOURCE REQUIRED]
```

### Problem 2. AI invents material

Fix:

Replace with:

```text
[AUTHOR MUST PROVIDE MATERIAL]
```

### Problem 3. Draft sounds academic but has weak logic

Fix:

Run:

```text
prompts/06_hostile_peer_reviewer.md
```

### Problem 4. Conclusion exceeds evidence

Fix:

Run:

```text
templates/conclusion_template.md
checklists/method_question_fit_checklist.md
```

### Problem 5. Active longevity claims are too strong

Fix:

Reframe through social interaction, mobility, orientation, and everyday practices.

## Post-draft workflow

After draft generation, continue in this order:

1. Reference reality check.
2. Citation-claim alignment check.
3. Hostile peer review.
4. Structural reconstruction.
5. Argument-forward rewriting.
6. Final coherence polishing.
7. Final submission checklist.

Use:

```text
prompts/04_reference_reality_checker.md
prompts/05_citation_claim_alignment_checker.md
prompts/06_hostile_peer_reviewer.md
prompts/07_structural_reconstruction_planner.md
prompts/08_argument_forward_rewriter.md
prompts/09_final_coherence_polisher.md
checklists/final_submission_checklist.md
```

## Safe storage

Safe to store in repository:

* draft generation workflow;
* templates;
* checklists;
* fictional examples;
* public writing rules.

Do not store:

* private manuscript drafts;
* unpublished dissertation chapters;
* copyrighted article PDFs;
* full target journal articles;
* private supervisor comments;
* reviewer correspondence;
* personal data;
* confidential research material.

## Final checklist before moving to reference audit

Before running reference audit, confirm:

* title matches the manuscript;
* abstract matches the draft;
* keywords match the topic;
* introduction contains research logic;
* methodology is explained;
* material is identified or marked;
* citations are present only where needed;
* unverified references are marked;
* high-risk claims are marked;
* conclusion does not obviously exceed evidence;
* no fake DOI numbers are included;
* no invented sources are included.

## Final rule

A generated draft is not a finished article.

It is a structured working version that must be tested, audited, attacked, reconstructed, and polished before submission.
