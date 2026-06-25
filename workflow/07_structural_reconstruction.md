# Workflow 07: Structural Reconstruction

This workflow explains how to rebuild the structure of a Russian-language academic manuscript after hostile peer review, reference audit, and citation-claim alignment.

It is designed for ВАК-style journal articles and related scholarly publications.

## Purpose

Structural reconstruction is used when the manuscript has a promising topic but the article logic is weak.

This workflow helps rebuild:

* research question;
* object and subject;
* aim and tasks;
* section order;
* methodology;
* material presentation;
* literature review logic;
* main analysis;
* conclusion;
* citation and evidence placement;
* paragraph sequence.

Structural reconstruction should happen before final rewriting.

Do not polish weak structure.

Rebuild it.

## Core rule

A manuscript should not be revised sentence by sentence if its structure is broken.

If the research question, method, material, analysis, and conclusion do not fit, the article needs reconstruction before style polishing.

The goal is to restore this chain:

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

## Required input

Before starting this workflow, prepare:

1. Current manuscript draft.
2. Hostile peer review report.
3. Reference audit report.
4. Citation-claim alignment report.
5. Target journal style profile.
6. Research question.
7. Object and subject.
8. Aim and tasks.
9. Methodology.
10. Material description.
11. List of major reviewer risks.

Use:

```text
prompts/07_structural_reconstruction_planner.md
examples/hostile_review_report_example.md
examples/final_coherence_report_example.md
rules/vak_article_logic.md
rules/method_question_alignment.md
checklists/logical_break_checklist.md
checklists/method_question_fit_checklist.md
```

## Step 1. Decide whether reconstruction is needed

Structural reconstruction is needed if one or more of the following problems appear:

* research question is unclear;
* aim does not follow from the research gap;
* object and subject are confused;
* tasks are decorative;
* methodology is listed but not applied;
* material is missing or unclear;
* examples are described but not analyzed;
* conclusion exceeds evidence;
* references do not support claims;
* active longevity claims are too strong;
* article sections appear in the wrong order;
* paragraphs repeat or mix several tasks;
* the manuscript sounds academic but does not argue clearly.

If problems are only local, use normal revision.

If problems affect the whole article, use reconstruction.

## Step 2. Extract the current structure

Create a map of the current manuscript.

Use this table:

| Current section   | Current function | Main problem | Keep / move / rewrite / delete |
| ----------------- | ---------------- | ------------ | ------------------------------ |
| Title             |                  |              |                                |
| Abstract          |                  |              |                                |
| Introduction      |                  |              |                                |
| Literature review |                  |              |                                |
| Methodology       |                  |              |                                |
| Main analysis     |                  |              |                                |
| Discussion        |                  |              |                                |
| Conclusion        |                  |              |                                |
| References        |                  |              |                                |

Questions:

* What is each section doing?
* Does each section have a clear function?
* Does the order help the argument?
* Which section contains material that belongs elsewhere?
* Which section repeats earlier points?
* Which section lacks evidence?
* Which section should be rewritten completely?

## Step 3. Identify the core argument

Before rebuilding sections, define the core argument in one paragraph.

Template:

```text
This article argues that [main claim]. It examines [object] through [subject], using [methods] on [material]. The analysis shows [main finding]. The contribution is [specific contribution].
```

Russian version:

```text
В статье обосновывается, что [main claim]. Объектом исследования является [object], а предметом выступает [subject]. На материале [material] с использованием [methods] выявляется [main finding]. Научная значимость исследования заключается в [specific contribution].
```

If the core argument cannot be stated clearly, reconstruction must begin with the research question.

## Step 4. Rebuild the research question

A strong research question should be:

* explicit;
* narrow;
* answerable;
* connected to material;
* connected to method;
* answered in the conclusion.

Weak question:

```text
How does traditional Chinese culture influence active longevity?
```

Stronger question:

```text
How are elements of traditional Chinese culture transformed in contemporary architectural environments associated with active longevity practices?
```

Questions:

* Is the question too broad?
* Does it contain several different studies?
* Can the method answer it?
* Can the material answer it?
* Does the conclusion answer it?

## Step 5. Rebuild object and subject

The object should be broader than the subject.

Example:

```text
Object:
Contemporary architectural environment of China.

Subject:
Transformation of traditional Chinese cultural elements in contemporary architectural space in relation to spatial organization, social interaction, mobility, and everyday practices.
```

Check:

* object is not identical to subject;
* subject is not broader than object;
* subject can be analyzed through the selected method;
* subject does not promise unsupported results;
* subject connects to the conclusion.

## Step 6. Rebuild aim and tasks

The aim should answer the research question.

Recommended aim:

```text
The aim of the article is to identify the ways in which traditional Chinese cultural elements are transformed in contemporary architectural environments and to determine how these elements participate in shaping spatial conditions associated with active longevity practices.
```

Russian version:

```text
Цель статьи состоит в выявлении способов трансформации элементов традиционной китайской культуры в современной архитектурной среде и определении их значения для формирования пространственных условий, связанных с практиками активного долголетия.
```

Recommended tasks:

```text
1. Clarify the concept of traditional cultural elements in relation to architectural space.
2. Define the methodological basis for analyzing their transformation.
3. Describe the material and selection criteria.
4. Identify how traditional elements are transformed in contemporary architectural form.
5. Interpret their relation to social interaction, mobility, orientation, and everyday practices.
```

Russian version:

```text
1. Уточнить понятие традиционных культурных элементов применительно к архитектурной среде.
2. Определить методологические основания анализа их трансформации.
3. Охарактеризовать материал исследования и критерии его отбора.
4. Выявить способы трансформации традиционных элементов в современной архитектурной форме.
5. Интерпретировать связь данных элементов с параметрами социальной активности, мобильности, ориентации и повседневных практик.
```

## Step 7. Rebuild the section order

Recommended ВАК-style structure:

```text
Title
Abstract
Keywords
Introduction
Literature review / theoretical framework
Methodology and material
Main analysis
Discussion or interpretation
Conclusion
References
```

For a manuscript about traditional Chinese culture, architecture, and active longevity, a possible structure is:

```text
1. Introduction
2. Literature review and theoretical framework
3. Methodology and material
4. Transformation of traditional cultural elements in contemporary architecture
5. Architectural environment and active longevity practices
6. Conclusion
```

Do not place conclusions before evidence.

Do not introduce methods after analysis.

Do not use theoretical concepts before defining them.

## Step 8. Rebuild the introduction

The introduction should contain:

1. specific relevance;
2. literature context;
3. research gap;
4. object;
5. subject;
6. aim;
7. tasks;
8. material;
9. methods;
10. transition to the article structure.

Recommended structure:

```text
Актуальность исследования обусловлена [specific reason].

В существующей литературе можно выделить несколько направлений изучения данной проблемы: [direction 1], [direction 2], [direction 3]. Вместе с тем недостаточно раскрытым остается вопрос о [research gap].

Объектом исследования является [object]. Предметом исследования выступает [subject]. Цель статьи состоит в [aim]. Для достижения поставленной цели решаются следующие задачи: [tasks].

Материалом исследования выступают [material]. Методологическую основу исследования составляют [methods].
```

Avoid:

```text
Актуальность темы не вызывает сомнений.
```

## Step 9. Rebuild the literature review

The literature review should create the research gap.

It should not list authors mechanically.

Recommended grouping:

1. Studies on traditional culture and cultural memory.
2. Studies on contemporary architecture and symbolic form.
3. Studies on architectural environment and everyday practices.
4. Studies on active longevity or age-friendly environments.
5. Research gap.

Strong pattern:

```text
Existing research can be divided into several directions. The first direction examines [topic]. The second direction focuses on [topic]. The third direction addresses [topic]. However, these approaches do not fully explain [specific gap].
```

Russian version:

```text
В существующей литературе можно выделить несколько направлений исследования данной проблемы. Первое направление связано с [topic]. Второе направление сосредоточено на [topic]. Третье направление рассматривает [topic]. Вместе с тем указанные подходы не позволяют в полной мере раскрыть [specific gap].
```

## Step 10. Rebuild methodology and material

The methodology section must connect research question, material, and analytical procedure.

It should explain:

* what material is analyzed;
* why this material was selected;
* what methods are used;
* what each method does;
* how analysis proceeds;
* what type of result the method can produce.

Strong method structure:

```text
Material:
[AUTHOR MUST PROVIDE MATERIAL]

Selection criteria:
[criteria]

Methods:
comparative analysis;
semiotic analysis;
historical-cultural analysis;
spatial analysis.

Procedure:
identify elements;
classify them;
compare traditional and contemporary functions;
interpret symbolic and spatial roles;
connect results to active longevity practices.
```

Russian example:

```text
Сравнительный анализ используется для сопоставления традиционных и современных архитектурных форм; семиотический анализ позволяет рассмотреть культурные элементы как систему знаков; историко-культурный подход обеспечивает интерпретацию этих элементов в контексте культурной памяти и преемственности; пространственный анализ необходим для выявления связи архитектурных элементов с маршрутами движения, зонами взаимодействия и сценариями повседневного использования среды.
```

## Step 11. Rebuild the main analysis

The main analysis should not only describe examples.

Each analytical unit should follow this sequence:

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

Recommended subsection structure:

```text
4. Transformation of traditional cultural elements in contemporary architecture
   4.1 Visual and symbolic transformation
   4.2 Spatial transformation
   4.3 Functional transformation

5. Architectural environment and active longevity practices
   5.1 Social interaction
   5.2 Mobility and orientation
   5.3 Everyday practices
```

Do not jump directly from cultural symbol to active longevity.

Use a mechanism:

```text
traditional cultural element
↓
architectural form
↓
spatial organization
↓
social interaction / mobility / orientation
↓
everyday practices
↓
active longevity context
```

## Step 12. Rebuild active longevity claims

Claims about active longevity must be controlled.

Do not write:

```text
Traditional Chinese architectural elements improve longevity.
```

Do not write:

```text
Architecture directly extends life.
```

Use:

```text
Traditional cultural elements can be analyzed as part of an architectural environment that supports social interaction, mobility, orientation, and everyday practices associated with active longevity.
```

Russian version:

```text
Традиционные культурные элементы могут быть рассмотрены как часть архитектурной среды, поддерживающей социальное взаимодействие, мобильность, ориентацию и устойчивые повседневные практики, связанные с активным долголетием.
```

If the manuscript lacks empirical health data, avoid direct medical or biological claims.

## Step 13. Rebuild paragraph sequence

Every paragraph should have one task.

Use this table:

| Paragraph | Function             | Keep / rewrite / move / delete | Notes |
| --------- | -------------------- | ------------------------------ | ----- |
| 1         | Problem introduction |                                |       |
| 2         | Relevance            |                                |       |
| 3         | Literature direction |                                |       |
| 4         | Research gap         |                                |       |
| 5         | Method               |                                |       |
| 6         | Material             |                                |       |
| 7         | Analysis             |                                |       |
| 8         | Interpretation       |                                |       |
| 9         | Conclusion           |                                |       |

Paragraph functions may include:

* problem introduction;
* relevance;
* literature synthesis;
* gap;
* concept definition;
* method explanation;
* material description;
* evidence presentation;
* analysis;
* interpretation;
* transition;
* conclusion.

If a paragraph has no clear function, delete or rewrite it.

## Step 14. Rebuild conclusion

The conclusion should not introduce new concepts or new sources.

It should:

1. return to the aim;
2. summarize supported findings;
3. answer the research question;
4. state contribution;
5. avoid unsupported claims;
6. avoid defensive over-explanation.

Recommended conclusion skeleton:

```text
Проведенный анализ был направлен на [aim]. В результате исследования установлено, что [main supported result].

Во-первых, [finding 1]. Во-вторых, [finding 2]. В-третьих, [finding 3].

Таким образом, [answer to research question]. Научная значимость исследования заключается в [specific contribution]. Дальнейшее изучение данной проблемы может быть связано с [future direction].
```

If the conclusion exceeds evidence, narrow it.

## Step 15. Rebuild citation placement

After changing structure, citations may need to move.

Check:

* citations are placed near the exact claims they support;
* decorative citations are removed;
* unsupported claims are marked;
* active longevity claims have field-appropriate sources;
* bibliography still matches in-text citations;
* no citation is attached to the wrong paragraph.

Use markers:

```text
[SOURCE REQUIRED]
[VERIFY REFERENCE]
[VERIFY DOI]
[VERIFY SOURCE SUPPORT]
```

## Step 16. Produce the reconstruction plan

The Structural Reconstruction Plan should include:

1. Current structure map.
2. Main logic failures.
3. Rebuilt research question.
4. Rebuilt object and subject.
5. Rebuilt aim and tasks.
6. Proposed new section structure.
7. Section-by-section repair plan.
8. Paragraph-level repair plan.
9. Citation and evidence repair notes.
10. Claims to narrow or remove.
11. Rewrite order.
12. Final reconstruction decision.

## Step 17. Recommended rewrite order

Do not rewrite from beginning to end blindly.

Use this order:

1. Research question.
2. Object, subject, aim, and tasks.
3. Section structure.
4. Methodology and material.
5. Main analytical sections.
6. Literature review.
7. Introduction.
8. Conclusion.
9. Abstract.
10. Title and keywords.

Reason:

The abstract and title should be finalized only after the argument is stable.

## Step 18. Do-not-rewrite-yet list

Do not polish these before reconstruction is complete:

* abstract;
* title;
* conclusion;
* stylistic details;
* formatting;
* final bibliography format;
* minor grammar.

First fix:

* research logic;
* method;
* material;
* analysis;
* evidence;
* conclusion scope.

## Step 19. Reconstruction decisions

Use one of the following decisions.

```text
Structure is stable
```

Use when only local revision is needed.

```text
Partial reconstruction required
```

Use when several sections need reordering or rewriting.

```text
Major reconstruction required
```

Use when the research chain is unstable.

```text
Rebuild from outline
```

Use when the draft is too disorganized for sentence-level revision.

```text
Do not submit
```

Use when material, method, references, or evidence are insufficient.

## Step 20. Continue to argument-forward rewriting

After reconstruction, continue with:

```text
workflow/08_argument_forward_rewrite.md
prompts/08_argument_forward_rewriter.md
rules/banned_defensive_formulas.md
rules/russian_academic_style.md
```

Structural reconstruction decides what the article should become.

Argument-forward rewriting turns that structure into stronger academic prose.

## Safe storage

Safe to store in repository:

* structural reconstruction workflow;
* reconstruction prompt;
* fictional examples;
* checklists;
* rules.

Do not store:

* private manuscript drafts;
* unpublished dissertation chapters;
* copyrighted articles;
* supervisor comments;
* reviewer correspondence;
* confidential research materials.

## Final checklist

Before leaving this workflow, confirm:

* research question is rebuilt;
* object and subject are consistent;
* aim and tasks match;
* section order is logical;
* methodology connects to material;
* material is identified or marked;
* main analysis has a clear sequence;
* active longevity claims are controlled;
* conclusion does not exceed evidence;
* citation placement is noted for repair;
* rewrite order is defined;
* final reconstruction decision is recorded.

## Final rule

Structural reconstruction is successful only when the article's parts begin to support one argument.

If the structure still hides weak logic, reconstruction is not finished.
