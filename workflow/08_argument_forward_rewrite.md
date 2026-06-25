# Workflow 08: Argument-Forward Rewrite

This workflow explains how to rewrite a Russian-language academic manuscript after structural reconstruction.

It is designed for ВАК-style journal articles and related scholarly publications.

## Purpose

Argument-forward rewriting turns a reconstructed article plan into clear academic prose.

It should strengthen:

* research problem;
* research question;
* argument structure;
* methodology explanation;
* evidence presentation;
* analysis;
* paragraph logic;
* conclusion;
* Russian academic style.

This workflow should not merely polish grammar.

It should make the manuscript argue more directly.

## Core rule

Write what the article argues.

Do not build the manuscript around what the article does not claim.

Avoid defensive formulas such as:

```text
This article does not claim that...
This study does not attempt to...
We do not argue that...
Настоящая статья не ставит целью...
Мы не утверждаем, что...
Это не означает, что...
```

Use positive analytical framing instead.

Weak:

```text
Настоящая статья не ставит целью доказать прямое влияние архитектуры на активное долголетие.
```

Stronger:

```text
Связь архитектурной среды с активным долголетием рассматривается через параметры социальной активности, мобильности, ориентации и устойчивых повседневных практик.
```

## Required input

Before starting this workflow, prepare:

1. Current manuscript draft.
2. Structural reconstruction plan.
3. Hostile peer review report.
4. Reference audit report.
5. Citation-claim alignment report.
6. Target journal style profile.
7. Rebuilt research question.
8. Rebuilt object and subject.
9. Rebuilt aim and tasks.
10. Rebuilt methodology and material section.
11. List of claims to narrow or remove.
12. List of required sources and verification markers.

Use:

```text
prompts/08_argument_forward_rewriter.md
rules/banned_defensive_formulas.md
rules/russian_academic_style.md
rules/paragraph_task_rules.md
rules/vak_article_logic.md
rules/method_question_alignment.md
phrasebank/academic_russian_phrases.md
```

## Step 1. Confirm rewrite readiness

Do not start argument-forward rewriting if the structure is still broken.

The manuscript is ready for this workflow only if:

* research question is clear;
* object and subject are consistent;
* aim and tasks are rebuilt;
* material is identified or clearly marked;
* methodology is connected to the question;
* major unsupported claims are identified;
* active longevity claims are controlled;
* section order is stable.

If these are not ready, return to:

```text
workflow/07_structural_reconstruction.md
```

## Step 2. Define the core argument

Before rewriting, state the article's core argument in one compact paragraph.

Template:

```text
This article argues that [main claim]. It analyzes [object] through [subject], using [methods] on [material]. The analysis shows [main finding]. The article contributes by [specific contribution].
```

Russian version:

```text
В статье обосновывается, что [main claim]. Объектом исследования является [object], а предметом выступает [subject]. На материале [material] с использованием [methods] выявляется [main finding]. Научная значимость исследования заключается в [specific contribution].
```

If this paragraph cannot be written clearly, the manuscript is not ready for argument-forward rewriting.

## Step 3. Replace defensive framing

Identify and remove unnecessary defensive formulas.

### Defensive version

```text
This article does not claim that architecture directly improves life expectancy.
```

### Argument-forward version

```text
The article examines architectural environment through spatial and social parameters associated with active longevity practices.
```

Russian version:

```text
В статье архитектурная среда рассматривается через пространственные и социальные параметры, связанные с практиками активного долголетия.
```

## Step 4. Rewrite from problem to argument

A strong rewritten introduction should move in this order:

```text
specific relevance
↓
research problem
↓
literature context
↓
research gap
↓
object and subject
↓
aim and tasks
↓
material and method
↓
article logic
```

Do not begin with broad historical statements.

Weak:

```text
Traditional Chinese culture has existed for thousands of years and has always played an important role in architecture.
```

Stronger:

```text
Актуальность исследования обусловлена необходимостью анализа того, каким образом элементы традиционной китайской культуры изменяют свои функции при включении в современную архитектурную среду.
```

## Step 5. Rewrite актуальность

Актуальность should explain the specific academic reason for the article.

Avoid:

```text
Актуальность темы не вызывает сомнений.
```

Use:

```text
Актуальность исследования обусловлена [specific academic reason].
```

Example:

```text
Актуальность исследования обусловлена необходимостью анализа способов трансформации традиционных культурных элементов в современной архитектурной среде и определения их значения для формирования устойчивых повседневных практик.
```

## Step 6. Rewrite the research gap

The research gap should follow from the literature review.

Weak:

```text
This topic has not been sufficiently studied.
```

Stronger:

```text
Несмотря на наличие исследований, посвященных архитектурной символике, культурной памяти и возрастоориентированной среде, недостаточно раскрытым остается вопрос о том, каким образом элементы традиционной китайской культуры трансформируются в современной архитектуре и участвуют в формировании пространственных условий, связанных с практиками активного долголетия.
```

## Step 7. Rewrite object, subject, aim, and tasks

Use clear ВАК-style formulations.

### Object

```text
Объектом исследования является современная архитектурная среда Китая.
```

### Subject

```text
Предметом исследования выступают способы трансформации элементов традиционной китайской культуры в современной архитектурной среде, рассматриваемые через параметры пространственной организации, социальной активности, мобильности и повседневных практик.
```

### Aim

```text
Цель статьи состоит в выявлении способов трансформации элементов традиционной китайской культуры в современной архитектурной среде и определении их значения для формирования пространственных условий, связанных с практиками активного долголетия.
```

### Tasks

```text
Для достижения поставленной цели решаются следующие задачи:
1. уточнить понятие традиционных культурных элементов применительно к архитектурной среде;
2. определить методологические основания анализа их трансформации;
3. охарактеризовать материал исследования и критерии его отбора;
4. выявить способы трансформации традиционных элементов в современной архитектурной форме;
5. интерпретировать связь данных элементов с параметрами социальной активности, мобильности, ориентации и повседневных практик.
```

Use these only if the manuscript actually completes these tasks.

## Step 8. Rewrite methodology as analytical procedure

Methodology should not be a decorative list.

Weak:

```text
В статье используются сравнительный, семиотический и историко-культурный методы.
```

Stronger:

```text
Сравнительный анализ используется для сопоставления традиционных и современных архитектурных форм; семиотический анализ позволяет рассмотреть культурные элементы как систему знаков; историко-культурный подход обеспечивает интерпретацию этих элементов в контексте культурной памяти и преемственности; пространственный анализ необходим для выявления связи архитектурных элементов с маршрутами движения, зонами взаимодействия и сценариями повседневного использования среды.
```

A rewritten methodology should include:

* material;
* selection criteria;
* method;
* reason for method;
* analytical procedure;
* expected type of result.

If material is missing, keep:

```text
[AUTHOR MUST PROVIDE MATERIAL]
```

Do not invent material.

## Step 9. Rewrite literature review as synthesis

The literature review should not list authors mechanically.

Weak:

```text
Ivanov studied cultural memory. Petrov studied architecture. Sidorov studied active longevity.
```

Stronger:

```text
В существующей литературе можно выделить несколько направлений исследования данной проблемы. Первое направление связано с анализом культурной памяти, второе сосредоточено на архитектурной символике, третье рассматривает возрастоориентированную среду. Вместе с тем указанные подходы не позволяют в полной мере раскрыть связь трансформации традиционных культурных элементов с повседневными пространственными практиками.
```

Each literature paragraph should perform one task:

* group sources;
* identify approach;
* show limitation;
* prepare the research gap.

## Step 10. Rewrite analysis sections

The main analysis should follow this pattern:

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

Weak:

```text
The building has traditional elements. This shows that culture is important for active longevity.
```

Stronger:

```text
В анализируемом объекте [AUTHOR MUST PROVIDE MATERIAL] традиционный культурный элемент проявляется через [specific form]. Семиотический анализ позволяет рассмотреть данный элемент как знак, связанный с [meaning]. В современной архитектурной среде его функция изменяется: он не только сохраняет связь с культурной памятью, но и участвует в организации [spatial function]. Это позволяет интерпретировать данный элемент как компонент среды, связанный с [social interaction / mobility / everyday practices].
```

## Step 11. Control active longevity claims

Claims about active longevity require special care.

Do not write:

```text
Architecture improves longevity.
Traditional cultural elements improve health.
Cultural symbols ensure active longevity.
```

Unless the manuscript contains empirical health evidence, avoid direct medical, biological, or life-expectancy claims.

Use mechanism-based wording:

```text
Архитектурная среда может формировать условия для социальной активности, мобильности, ориентации и устойчивых повседневных практик.
```

or:

```text
Традиционные культурные элементы могут быть рассмотрены как часть архитектурной среды, поддерживающей социальное взаимодействие, мобильность, ориентацию и устойчивые повседневные практики, связанные с активным долголетием.
```

## Step 12. Rewrite paragraph by paragraph

Every paragraph should have one clear task.

Use this table while rewriting:

| Paragraph | Task | Problem | Rewrite action |
| --------- | ---- | ------- | -------------- |
| 1         |      |         |                |
| 2         |      |         |                |
| 3         |      |         |                |

Possible paragraph tasks:

* introduce problem;
* justify relevance;
* synthesize literature;
* identify gap;
* define concept;
* explain method;
* describe material;
* present evidence;
* analyze evidence;
* interpret result;
* transition;
* conclude.

If a paragraph has no task, remove it or rewrite it.

## Step 13. Remove repetition

Argument-forward rewriting should reduce repetition.

Common repeated elements:

* актуальность repeated several times;
* same research gap stated in multiple places;
* method repeated without use;
* active longevity warning repeated defensively;
* conclusion repeated before analysis;
* same claim appearing in abstract, introduction, and conclusion without development.

Repair actions:

* merge repeated paragraphs;
* keep the strongest version;
* move one version to the correct section;
* replace repetition with analysis.

## Step 14. Rewrite transitions

Transitions should show logical movement.

Useful Russian formulas:

```text
Это позволяет перейти к рассмотрению...
```

```text
На этом основании можно обратиться к анализу...
```

```text
В связи с этим необходимо уточнить...
```

```text
Следовательно, дальнейший анализ должен учитывать...
```

```text
Данный вывод подготавливает анализ...
```

Avoid mechanical transitions that do not explain the logic.

## Step 15. Rewrite conclusion

The conclusion should return to the aim and state supported findings.

It should not introduce new concepts, new sources, or broader claims.

Conclusion skeleton:

```text
Проведенный анализ был направлен на [aim]. В результате исследования установлено, что [main supported result].

Во-первых, [finding 1]. Во-вторых, [finding 2]. В-третьих, [finding 3].

Таким образом, [answer to research question]. Научная значимость исследования заключается в [specific contribution]. Дальнейшее изучение данной проблемы может быть связано с [future direction].
```

Avoid:

```text
This article does not claim to solve all aspects of the problem.
```

Use:

```text
Дальнейшее изучение данной проблемы может быть связано с расширением корпуса анализируемых архитектурных объектов и уточнением критериев оценки средовых параметров.
```

## Step 16. Rewrite abstract last

Do not finalize the abstract before the manuscript argument is stable.

A final abstract should include:

```text
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

```text
Актуальность исследования обусловлена [specific reason]. Несмотря на наличие исследований, посвященных [general topic], недостаточно изученным остается [specific gap]. Цель статьи состоит в [aim]. Материалом исследования выступают [material], анализ которых осуществляется с использованием [methods]. Проведенный анализ показывает, что [main supported result]. Научная значимость статьи заключается в [specific contribution].
```

## Step 17. Maintain evidence markers

Do not remove warning markers unless the issue is fixed.

Keep markers such as:

```text
[SOURCE REQUIRED]
[VERIFY REFERENCE]
[VERIFY DOI]
[VERIFY SOURCE SUPPORT]
[AUTHOR MUST PROVIDE MATERIAL]
[RESULT REQUIRES EVIDENCE]
```

A fluent sentence with unresolved evidence is still not submission-ready.

## Step 18. Apply Russian academic style

Use formal, clear Russian academic prose.

Prefer:

```text
анализ показывает
исследование направлено на
полученные результаты позволяют
актуальность обусловлена
научная значимость заключается в
```

Reduce:

```text
очень важный
на сегодняшний день
нельзя не отметить
актуальность темы не вызывает сомнений
данная проблематика
представляется возможным говорить о
```

A good academic sentence should make the argument clearer.

It should not create fog.

## Step 19. Produce the rewritten section report

For each rewritten section, include:

1. Section name.
2. Original problem.
3. Rewrite strategy.
4. Rewritten text.
5. Remaining evidence markers.
6. Citation warnings.
7. Claim risk warnings.
8. Paragraph task map.
9. Next required action.

Use example:

```text
examples/rewritten_section_example.md
```

## Step 20. Argument-forward rewrite decisions

Use one of the following decisions.

```text
Rewrite completed
```

Use when the section is clear, direct, and evidence-safe.

```text
Rewrite completed with markers
```

Use when the prose is improved but author input, sources, or verification are still needed.

```text
Rewrite blocked by missing material
```

Use when the section cannot be written without research material.

```text
Rewrite blocked by unsupported claims
```

Use when the claim cannot be supported by current evidence.

```text
Return to structural reconstruction
```

Use when rewriting reveals that the article structure is still unstable.

## Recommended rewrite order

Use this order:

1. Methodology and material.
2. Main analysis.
3. Literature review.
4. Introduction.
5. Conclusion.
6. Abstract.
7. Title and keywords.
8. Final style polish.

Reason:

The introduction, conclusion, and abstract depend on the final structure of the analysis.

## Safe storage

Safe to store in repository:

* argument-forward rewrite workflow;
* rewrite prompt;
* fictional rewritten examples;
* rules;
* phrasebank.

Do not store:

* private manuscript drafts;
* unpublished dissertation chapters;
* supervisor comments;
* real reviewer reports;
* copyrighted journal articles;
* copied text from target articles.

## Final checklist

Before leaving this workflow, confirm:

* defensive formulas are removed or minimized;
* positive analytical framing is used;
* research problem is clearer;
* method is explained as procedure;
* main analysis follows claim-material-method-interpretation logic;
* active longevity claims are controlled;
* unsupported claims are marked;
* citations are not decorative;
* paragraphs have clear tasks;
* conclusion does not exceed evidence;
* abstract is updated only after the argument is stable.

## Final rule

Argument-forward rewriting does not make the manuscript weaker.

It makes the manuscript more precise, more direct, and more defensible.
