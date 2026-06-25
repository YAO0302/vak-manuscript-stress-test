# VAK Article Logic Rules

This rule file defines the internal logic of a Russian ВАК-style academic article.

It explains how актуальность, research problem, object, subject, aim, tasks, methods, material, novelty, significance, and conclusion should connect to each other.

## Core principle

A ВАК-style academic article should not be a collection of formal elements.

The elements must form one coherent research chain:

```text
Актуальность
↓
Research problem
↓
Object and subject
↓
Aim
↓
Tasks
↓
Methods and material
↓
Analysis
↓
Results
↓
Novelty and significance
↓
Conclusion
```

If these elements do not match, the article may look academic but remain logically weak.

## 1. Актуальность

Актуальность explains why the research problem matters.

It should answer:

```text
Why does this problem need to be studied now?
```

A strong актуальность is specific.

Weak:

```text
Актуальность темы не вызывает сомнений.
```

Strong:

```text
Актуальность исследования обусловлена необходимостью анализа способов трансформации традиционных культурных элементов в современной архитектурной среде и определения их значения для формирования устойчивых повседневных практик.
```

Rules:

* do not use empty relevance formulas;
* do not claim актуальность without explaining it;
* connect актуальность to the research gap;
* avoid broad historical openings;
* avoid emotional or journalistic language.

## 2. Research problem

The research problem names the unresolved academic issue.

It should be narrower than the general topic.

It should lead to the research question.

Weak:

```text
Проблема исследования связана с культурой и архитектурой.
```

Strong:

```text
Исследовательская проблема заключается в выявлении того, каким образом элементы традиционной китайской культуры изменяют свои функции при включении в современную архитектурную среду.
```

Rules:

* formulate a real unresolved issue;
* do not confuse topic with problem;
* connect the problem to literature;
* make the problem answerable within one article.

## 3. Research gap

The research gap explains what previous studies have not sufficiently addressed.

It should follow from the literature review.

Weak:

```text
Данная тема недостаточно изучена.
```

Strong:

```text
Несмотря на наличие исследований, посвященных архитектурной символике и культурной памяти, недостаточно раскрытым остается вопрос о связи трансформации традиционных культурных элементов с параметрами среды, поддерживающими активное долголетие.
```

Rules:

* specify what exactly is insufficiently studied;
* do not use vague gap statements;
* do not invent a gap without reviewing literature;
* connect the gap to the aim.

## 4. Object of research

The object is the broader phenomenon or field being studied.

It should be broader than the subject.

Formula:

```text
Объектом исследования является...
```

Example:

```text
Объектом исследования является современная архитектурная среда Китая.
```

Rules:

* object must not be identical to subject;
* object must not be narrower than subject;
* object must be connected to the article field;
* object must be analyzable through the chosen material.

## 5. Subject of research

The subject is the specific aspect of the object analyzed in the article.

Formula:

```text
Предметом исследования выступает...
```

Example:

```text
Предметом исследования выступают способы трансформации элементов традиционной китайской культуры в современной архитектурной среде, рассматриваемые через параметры пространственной организации, социальной активности и восприятия среды.
```

Rules:

* subject must be specific;
* subject must be narrower than object;
* subject must connect to method;
* subject must connect to conclusion;
* subject must not contain claims that cannot be studied with the material.

## 6. Aim

The aim states what the article intends to achieve.

Formula:

```text
Цель статьи состоит в...
```

A good aim uses analytical verbs:

* выявить;
* определить;
* проанализировать;
* уточнить;
* сопоставить;
* классифицировать;
* интерпретировать;
* раскрыть.

Weak:

```text
Цель статьи — изучить данную тему.
```

Strong:

```text
Цель статьи состоит в выявлении способов трансформации элементов традиционной китайской культуры в современной архитектурной среде и определении их значения для формирования условий активного долголетия.
```

Rules:

* aim must follow from the research problem;
* aim must be achievable within one article;
* aim must match the method and material;
* aim must be answered in the conclusion.

## 7. Tasks

Tasks divide the aim into concrete steps.

Formula:

```text
Для достижения поставленной цели решаются следующие задачи:
1. ...
2. ...
3. ...
```

Good task types:

* define a concept;
* review literature;
* justify method;
* describe material selection;
* analyze selected material;
* compare cases;
* interpret results;
* formulate conclusions.

Weak tasks:

```text
1. Изучить тему.
2. Рассмотреть проблему.
3. Сделать выводы.
```

Strong tasks:

```text
1. Уточнить понятие традиционных культурных элементов применительно к архитектурной среде.
2. Определить методологические основания их анализа.
3. Рассмотреть способы их трансформации на материале выбранных архитектурных объектов.
4. Выявить связь пространственных решений с практиками активного долголетия.
```

Rules:

* tasks must not be decorative;
* each task should correspond to a section or analytical step;
* tasks must lead to the aim;
* tasks must be completed in the article.

## 8. Methods

Methods explain how the article answers the research question.

Methods must be connected to aim, tasks, and material.

Weak:

```text
В статье используются сравнительный, семиотический и историко-культурный методы.
```

Strong:

```text
Сравнительный анализ используется для сопоставления традиционных и современных архитектурных форм; семиотический анализ позволяет рассмотреть культурные элементы как систему знаков; историко-культурный подход обеспечивает интерпретацию этих элементов в контексте культурной памяти и преемственности.
```

Rules:

* do not only list methods;
* explain why each method is needed;
* show what each method does;
* remove methods that are not actually used;
* do not claim results the method cannot produce.

## 9. Material

Material is the evidence or corpus analyzed in the article.

Formula:

```text
Материалом исследования выступают...
```

Examples:

* architectural objects;
* urban spaces;
* visual materials;
* design projects;
* planning documents;
* interviews;
* statistical data;
* theoretical texts;
* policy documents.

Rules:

* define material clearly;
* explain selection criteria;
* make sure material matches the method;
* do not draw broad conclusions from narrow material;
* mark missing material as `[AUTHOR MUST PROVIDE MATERIAL]`.

## 10. Novelty

Novelty explains what is new in the article.

Novelty may be:

* conceptual;
* methodological;
* material-based;
* interpretive;
* comparative;
* interdisciplinary;
* practical.

Weak:

```text
Научная новизна исследования заключается в том, что данная проблема ранее не изучалась.
```

Strong:

```text
Научная новизна исследования заключается в рассмотрении традиционных культурных элементов не только как декоративных мотивов, но и как компонентов архитектурной среды, связанных с культурной памятью, пространственной организацией и практиками активного долголетия.
```

Rules:

* do not overstate novelty;
* do not claim total absence of previous research without evidence;
* distinguish topic novelty from real scholarly contribution;
* connect novelty to analysis, not only to topic.

## 11. Theoretical significance

Theoretical significance explains how the article contributes to knowledge.

Formula:

```text
Теоретическая значимость исследования состоит в...
```

Possible types:

* clarifying a concept;
* refining an analytical approach;
* connecting fields;
* expanding interpretation of material;
* proposing a classification.

Rules:

* significance must follow from results;
* do not use generic claims;
* do not claim theoretical significance if the article only describes material.

## 12. Practical significance

Practical significance should be stated only when justified.

Formula:

```text
Практическая значимость результатов связана с...
```

Possible areas:

* architectural analysis;
* design principles;
* cultural heritage interpretation;
* urban environment evaluation;
* active longevity environment studies;
* educational use;
* further research.

Rules:

* do not overstate practical use;
* do not claim design or policy application without evidence;
* practical significance must follow from the article's material and method.

## 13. Analysis

Analysis is where the method is applied to material.

A strong analytical section should:

1. state a claim;
2. present material;
3. apply the method;
4. interpret the result;
5. connect the result to the research question.

Weak analysis:

```text
The article describes several examples but does not explain what they show.
```

Strong analysis:

```text
The article identifies elements, explains their function, compares them with traditional forms, and interprets their role in contemporary architectural space.
```

Rules:

* do not confuse description with analysis;
* do not present examples without interpretation;
* do not make conclusions before analysis;
* do not use theory without applying it.

## 14. Conclusion

The conclusion must return to the aim and answer the research question.

It should not introduce new evidence.

It should not exceed the material.

It should not merely repeat the abstract.

Rules:

* answer the research question;
* summarize supported findings;
* state contribution;
* avoid new concepts;
* avoid unsupported broad claims;
* avoid excessive defensive formulas.

## 15. Consistency check

Use this table to check the internal logic.

| Element      | Must connect to   | Check question                       |
| ------------ | ----------------- | ------------------------------------ |
| Актуальность | Research problem  | Why does this problem matter?        |
| Research gap | Literature review | What is insufficiently studied?      |
| Object       | Subject           | Is the object broader?               |
| Subject      | Method            | Can the method analyze this subject? |
| Aim          | Research problem  | Does the aim solve the problem?      |
| Tasks        | Aim               | Do tasks lead to the aim?            |
| Methods      | Research question | Can methods answer the question?     |
| Material     | Method            | Can the method analyze the material? |
| Analysis     | Conclusion        | Do findings support the conclusion?  |
| Novelty      | Results           | What is actually new?                |
| Significance | Results           | What does the result contribute?     |

## 16. Common logic failures

### Failure 1. Topic instead of research problem

Fix:

Formulate what exactly remains unresolved.

### Failure 2. Object and subject are identical

Fix:

Make the object broader and the subject more specific.

### Failure 3. Aim is too broad

Fix:

Narrow it to what one article can achieve.

### Failure 4. Tasks are decorative

Fix:

Make each task correspond to a section or analytical step.

### Failure 5. Method is decorative

Fix:

Explain how the method works in the analysis.

### Failure 6. Conclusion exceeds evidence

Fix:

Narrow the conclusion or add evidence.

### Failure 7. Novelty is overstated

Fix:

Define the exact type of contribution.

## 17. Final VAK logic checklist

Before submission, check:

* Актуальность is specific.
* Research problem is clear.
* Research gap follows from literature.
* Object is broader than subject.
* Subject is precise.
* Aim follows from the problem.
* Tasks lead to the aim.
* Methods are explained.
* Material is defined.
* Analysis applies the method.
* Results follow from analysis.
* Novelty is real and specific.
* Significance follows from results.
* Conclusion answers the aim.
* Claims do not exceed evidence.
* The article does not rely on decorative academic wording.

## Final rule

A ВАК article is strong when its formal elements are not merely present, but logically connected.
