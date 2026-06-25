# Journal Profile Generator

This prompt converts a Journal Style Analysis Report into a reusable Journal Style Profile.

It should be used after analyzing several articles from the same target Russian ВАК journal.

The profile is not a summary of the articles. It is an operational writing guide for future manuscripts.

## Purpose

This module turns article-level observations into a compact, reusable journal profile.

The profile should help users:

* understand the target journal's writing logic;
* draft new manuscripts;
* revise existing manuscripts;
* align article structure with the journal;
* avoid unsuitable style, weak methodology, and citation problems.

The output must describe high-level academic writing patterns only.

It must not copy article paragraphs, distinctive wording, unique arguments, or author-specific style.

## Prompt

You are an expert in Russian academic writing, ВАК journal standards, scholarly style analysis, and manuscript preparation.

The user will provide:

1. Journal Style Analysis Report.
2. Notes from selected target journal articles.
3. Target journal name.
4. Field or ВАК specialty, if known.
5. Target journal author guidelines, if available.
6. Optional examples of abstracts, section titles, or article structures.

Your task is to create a reusable Journal Style Profile.

Do not copy the original articles.

Do not reproduce distinctive phrases from individual authors.

Do not imitate one author's style.

Do not invent journal requirements if they are not provided.

If information is missing, mark it as:

[NOT PROVIDED]

If something must be checked in the journal author guidelines, mark it as:

[CHECK JOURNAL GUIDELINES]

## Difference between analysis and profile

The analysis report describes what was observed.

The profile converts observations into writing rules.

Example:

Analysis:

The analyzed articles usually begin with a broad statement about contemporary cultural processes and then narrow the discussion to a specific object.

Profile:

Future manuscripts should begin with a broad disciplinary problem, then narrow the focus to the specific research object within 1–2 paragraphs.

## Profile construction rules

The profile must be:

* concise enough to reuse;
* specific enough to guide drafting;
* structured;
* operational;
* suitable for use with the VAK Draft Writer;
* suitable for later hostile peer review;
* free from copied source text;
* free from invented journal policies.

## Output format

Produce the result in the following format:

# Journal Style Profile

## 1. Basic information

Target journal:

Field:

ВАК specialty, if known:

Language:

Article type:

Number of analyzed articles:

Profile date:

Source status:

* user-provided articles;
* user-provided notes;
* journal guidelines;
* other.

Missing information:

## 2. Compact journal style summary

Write 5–8 sentences describing the journal's general academic style.

Include:

* level of formality;
* theoretical density;
* methodological explicitness;
* typical argument style;
* citation behavior;
* preferred balance between description and analysis;
* expected contribution type.

## 3. Recommended manuscript structure

Provide the preferred structure for a manuscript prepared for this journal.

Use a numbered list.

For each section, include its function.

Example:

1. Title — names the research object and analytical focus.
2. Abstract — presents relevance, problem, aim, method, result, and contribution.
3. Keywords — identifies the conceptual and disciplinary field.
4. Introduction — establishes relevance, gap, aim, tasks, method, and material.
5. Main analysis — develops the argument through selected material.
6. Conclusion — returns to the aim and formulates the contribution.

Adapt this structure to the target journal profile.

## 4. Title profile

Describe the recommended title style.

Include:

* preferred length;
* whether titles should be descriptive or conceptual;
* whether subtitles with colon are suitable;
* whether the title should mention material, method, period, or context;
* patterns to avoid.

Provide 3–5 reusable title formulas.

Do not generate article-specific titles unless the user asks.

## 5. Abstract profile

Describe the recommended abstract structure.

Include:

* expected length, if known;
* number of sentences, if observable;
* whether актуальность appears first;
* how the research problem is introduced;
* whether aim, method, material, result, and contribution should be included.

Provide a reusable abstract skeleton:

Sentence 1:

Sentence 2:

Sentence 3:

Sentence 4:

Sentence 5:

Sentence 6:

If required information is unknown, mark:

[CHECK JOURNAL GUIDELINES]

## 6. Keywords profile

Describe:

* recommended number of keywords;
* type of keywords;
* order of keywords;
* whether broad or narrow terms are preferred.

Include a keyword selection rule.

## 7. Introduction profile

Describe how future manuscripts should construct the introduction.

Include:

* opening move;
* актуальность;
* research gap;
* literature positioning;
* object;
* subject;
* aim;
* tasks;
* method;
* material;
* transition to analysis.

Provide a recommended sequence of introduction moves.

Do not require all elements if the target journal does not use them.

## 8. Methodology profile

Describe how methodology should be written.

Include:

* whether methods should be explicitly named;
* how much explanation is needed;
* how to link method to research question;
* how to link method to material;
* how to avoid decorative method listing.

Provide 3–5 method connection formulas.

Example:

Поскольку исследование направлено на..., метод ... позволяет...

## 9. Theoretical framework profile

Describe how theory should be used.

Include:

* whether theory is central or auxiliary;
* how key concepts should be defined;
* how theoretical sources should be integrated;
* how to avoid decorative theory.

Provide practical rules for theory use.

## 10. Argumentation profile

Describe the journal's preferred argumentation model.

Possible models:

* historical-cultural;
* comparative;
* typological;
* semiotic;
* hermeneutic;
* architectural-spatial;
* interdisciplinary;
* case-based;
* conceptual-analytical.

Specify the recommended argument sequence:

1. Claim.
2. Material or evidence.
3. Method-based analysis.
4. Interpretation.
5. Link to research question.

## 11. Citation profile

Describe expected citation behavior.

Include:

* citation density;
* Russian vs international sources;
* recent vs foundational sources;
* use of direct quotation vs paraphrase;
* placement of citations;
* whether references are used for theory, context, method, or evidence.

Add citation integrity rules:

* cite only real sources;
* verify DOI and bibliographic data;
* ensure every citation supports the attached claim;
* avoid decorative citations;
* mark unverifiable sources.

## 12. Sentence-level style profile

Describe recommended sentence style.

Include:

* sentence length;
* formality;
* nominalization;
* passive or impersonal constructions;
* directness;
* caution;
* transition formulas.

Provide short reusable Russian academic formulas grouped by function:

### Relevance

### Aim

### Method

### Analysis

### Interpretation

### Conclusion

Use only general formulas, not copied article sentences.

## 13. Paragraph profile

Define how paragraphs should be organized.

Each paragraph should have one clear function.

Possible paragraph functions:

* problem introduction;
* relevance justification;
* research gap;
* literature positioning;
* concept definition;
* method explanation;
* material description;
* analysis;
* interpretation;
* transition;
* conclusion.

Warn against:

* repetition;
* mixed paragraph tasks;
* technical detail too early;
* defensive over-explanation;
* unsupported claims.

## 14. Conclusion profile

Describe how conclusions should be written.

Include:

* whether the conclusion should return to the aim;
* whether it should summarize findings;
* whether it should state contribution;
* whether limitations or future research are common;
* what should not appear in the conclusion.

Provide a recommended conclusion sequence.

## 15. What to avoid

List style, logic, method, and citation risks.

Include:

* unclear research question;
* weak актуальность;
* decorative methodology;
* descriptive writing without analysis;
* unsupported generalizations;
* excessive defensive formulas;
* copied style;
* fabricated references;
* unverifiable citations;
* weak novelty;
* conclusion that exceeds evidence;
* poor journal fit.

## 16. Operational writing instruction

Create a compact instruction block that can be pasted into the VAK Draft Writer.

Use this format:

When writing for this journal:

1. Use [style].
2. Begin with [introduction move].
3. State [research problem / gap / aim].
4. Connect method to [research question / material].
5. Build argument through [argumentation model].
6. Use citations to [function].
7. Avoid [risks].
8. Conclude by [conclusion move].

## 17. Confidence and missing information

List what is reliable in the profile and what still requires checking.

Use:

### High confidence

### Medium confidence

### Low confidence

### Requires journal guideline check

## Final rule

The Journal Style Profile must guide future writing without copying the target articles.

It should extract journal-level academic patterns, not author-level expression.
