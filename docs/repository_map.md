# Repository Map

This document explains the structure of the `vak-manuscript-stress-test` repository.

The repository provides an AI-assisted workflow for Russian ВАК journal writing, journal style profiling, reference auditing, hostile peer review, structural reconstruction, argument-forward rewriting, and final submission readiness checks.

## 1. Repository purpose

This repository is designed to help authors prepare Russian-language academic manuscripts for ВАК journals and related scholarly publications.

It does not replace the author, supervisor, editor, reviewer, or journal guidelines.

It helps organize a safe and repeatable workflow:

1. Analyze target journal articles.
2. Build a journal style profile.
3. Generate or revise a manuscript draft.
4. Audit references.
5. Check citation-claim alignment.
6. Simulate hostile peer review.
7. Rebuild article structure.
8. Rewrite in an argument-forward style.
9. Polish final coherence.
10. Check submission readiness.

## 2. Top-level structure

```text
vak-manuscript-stress-test/
├── README.md
├── .gitignore
├── docs/
├── workflow/
├── prompts/
├── templates/
├── rules/
├── checklists/
├── phrasebank/
└── examples/
```

## 3. README.md

### Purpose

The `README.md` file introduces the project.

It explains:

* what the project does;
* who the project is for;
* the core workflow;
* the main modules;
* ethical boundaries;
* roadmap;
* current status.

### Use

Start with `README.md` when someone wants to understand the project quickly.

## 4. .gitignore

### Purpose

The `.gitignore` file prevents private, copyrighted, or unsuitable files from being committed to the public repository.

It blocks files and folders such as:

* PDFs;
* Word documents;
* private drafts;
* dissertation files;
* source articles;
* uploaded materials;
* local editor files.

### Important rule

Do not upload copyrighted journal PDFs, private drafts, unpublished dissertation chapters, or paywalled articles to the public repository.

## 5. docs/

The `docs/` folder contains explanatory documents about how to use the repository safely.

### Current files

```text
docs/
├── how_to_use.md
├── copyright_and_ethics.md
├── limitations.md
└── repository_map.md
```

### docs/how_to_use.md

Explains the recommended way to use the whole repository.

Use this file when a new user needs step-by-step guidance.

### docs/copyright_and_ethics.md

Explains copyright and ethical boundaries.

Main rule:

Do not copy, upload, or reproduce copyrighted journal texts.

### docs/limitations.md

Explains what the workflow cannot guarantee.

Main warning:

AI can help structure, test, and revise academic writing, but it cannot guarantee publication or replace author responsibility.

### docs/repository_map.md

Explains the repository structure.

Use this file as a navigation guide.

## 6. workflow/

The `workflow/` folder contains the complete process from target article selection to final polishing.

### Current files

```text
workflow/
├── 00_full_pipeline.md
├── 01_target_journal_articles.md
├── 02_journal_style_profile.md
├── 03_draft_generation.md
├── 04_reference_audit.md
├── 05_citation_claim_alignment.md
├── 06_hostile_review.md
├── 07_structural_reconstruction.md
├── 08_argument_forward_rewrite.md
└── 09_final_coherence_polishing.md
```

### workflow/00_full_pipeline.md

Gives the complete overview of the full workflow.

Use first if you want to understand the full sequence.

### workflow/01_target_journal_articles.md

Explains how to select target ВАК journal articles for style analysis.

Focus:

* article selection;
* copyright safety;
* article metadata;
* target journal relevance.

### workflow/02_journal_style_profile.md

Explains how to convert article analysis into a reusable Journal Style Profile.

Focus:

* journal structure;
* introduction patterns;
* methodology patterns;
* citation behavior;
* conclusion style.

### workflow/03_draft_generation.md

Explains how to generate or revise a manuscript draft.

Focus:

* topic;
* object;
* subject;
* aim;
* tasks;
* material;
* methods;
* draft structure.

### workflow/04_reference_audit.md

Explains how to check whether references are real, complete, and safe to use.

Focus:

* fake references;
* DOI verification;
* incomplete bibliography;
* unverifiable sources.

### workflow/05_citation_claim_alignment.md

Explains how to check whether citations actually support the claims they are attached to.

Focus:

* citation support level;
* decorative citations;
* claim type;
* source relevance.

### workflow/06_hostile_review.md

Explains how to simulate strict academic peer review.

Focus:

* rejection risks;
* weak logic;
* method problems;
* unsupported claims;
* reviewer objections.

### workflow/07_structural_reconstruction.md

Explains how to rebuild the article structure after hostile review.

Focus:

* research chain;
* section order;
* methodology;
* material;
* analysis;
* conclusion.

### workflow/08_argument_forward_rewrite.md

Explains how to rewrite the manuscript in a direct, argument-forward academic style.

Focus:

* removing defensive formulas;
* strengthening claims;
* improving paragraph logic;
* making method and evidence visible.

### workflow/09_final_coherence_polishing.md

Explains how to check final coherence before submission.

Focus:

* title;
* abstract;
* introduction;
* conclusion;
* references;
* target journal fit;
* final readiness.

## 7. prompts/

The `prompts/` folder contains reusable prompts for AI-assisted manuscript work.

### Current files

```text
prompts/
├── 01_article_style_analyzer.md
├── 02_journal_profile_generator.md
├── 03_vak_draft_writer.md
├── 04_reference_reality_checker.md
├── 05_citation_claim_alignment_checker.md
├── 06_hostile_peer_reviewer.md
├── 07_structural_reconstruction_planner.md
├── 08_argument_forward_rewriter.md
└── 09_final_coherence_polisher.md
```

### prompts/01_article_style_analyzer.md

Analyzes selected target journal articles and extracts high-level style patterns.

### prompts/02_journal_profile_generator.md

Turns the article style analysis into a reusable Journal Style Profile.

### prompts/03_vak_draft_writer.md

Generates or revises a Russian ВАК-style manuscript draft.

Important rule:

It must not invent sources, data, DOI numbers, material, or results.

### prompts/04_reference_reality_checker.md

Checks whether references appear real, complete, and internally consistent.

### prompts/05_citation_claim_alignment_checker.md

Checks whether citations support the claims attached to them.

### prompts/06_hostile_peer_reviewer.md

Simulates a strict hostile reviewer.

### prompts/07_structural_reconstruction_planner.md

Creates a reconstruction plan after hostile review.

### prompts/08_argument_forward_rewriter.md

Rewrites sections in a direct, argument-forward style.

### prompts/09_final_coherence_polisher.md

Checks final article coherence and submission readiness.

## 8. templates/

The `templates/` folder contains reusable manuscript templates.

### Current files

```text
templates/
├── journal_style_profile_template.md
├── vak_article_structure.md
├── abstract_template.md
├── introduction_template.md
├── methodology_template.md
└── conclusion_template.md
```

### templates/journal_style_profile_template.md

Template for recording target journal style.

### templates/vak_article_structure.md

Standard ВАК-style article structure.

### templates/abstract_template.md

Template for writing the abstract.

### templates/introduction_template.md

Template for writing the introduction.

### templates/methodology_template.md

Template for writing the methodology section.

### templates/conclusion_template.md

Template for writing the conclusion.

## 9. rules/

The `rules/` folder contains writing, logic, citation, and style rules.

### Current files

```text
rules/
├── banned_defensive_formulas.md
├── method_question_alignment.md
├── paragraph_task_rules.md
├── citation_integrity_rules.md
├── russian_academic_style.md
└── vak_article_logic.md
```

### rules/banned_defensive_formulas.md

Lists defensive formulas to avoid.

Main idea:

Do not build the argument around what the article does not claim.

### rules/method_question_alignment.md

Checks the fit between research question, material, method, and conclusion.

### rules/paragraph_task_rules.md

Requires every paragraph to perform one clear task.

### rules/citation_integrity_rules.md

Prevents fake references, fake DOI numbers, decorative citations, and citation misuse.

### rules/russian_academic_style.md

Defines formal, clear Russian academic style.

### rules/vak_article_logic.md

Defines the logic of ВАК-style article elements:

* актуальность;
* research problem;
* object;
* subject;
* aim;
* tasks;
* methods;
* material;
* novelty;
* significance;
* conclusion.

## 10. checklists/

The `checklists/` folder contains practical review checklists.

### Current files

```text
checklists/
├── reference_audit_checklist.md
├── hostile_review_checklist.md
├── final_submission_checklist.md
├── method_question_fit_checklist.md
└── logical_break_checklist.md
```

### checklists/reference_audit_checklist.md

Used to check reference reality, DOI accuracy, bibliography completeness, and citation risks.

### checklists/hostile_review_checklist.md

Used to simulate strict reviewer criticism.

### checklists/final_submission_checklist.md

Used as the final gate before submission.

### checklists/method_question_fit_checklist.md

Used to check whether the selected method can answer the research question.

### checklists/logical_break_checklist.md

Used to detect missing logical links between problem, method, evidence, and conclusion.

## 11. phrasebank/

The `phrasebank/` folder contains reusable Russian academic phrases.

### Current files

```text
phrasebank/
└── academic_russian_phrases.md
```

### phrasebank/academic_russian_phrases.md

Contains Russian academic formulas for:

* актуальность;
* research gap;
* object and subject;
* aim and tasks;
* methodology;
* literature review;
* analysis;
* interpretation;
* novelty;
* significance;
* conclusion.

Important rule:

Use phrases as tools, not decoration.

## 12. examples/

The `examples/` folder contains fictional examples of expected outputs.

### Current files

```text
examples/
├── style_profile_example.md
├── hostile_review_report_example.md
├── reference_audit_report_example.md
├── rewritten_section_example.md
└── final_coherence_report_example.md
```

### examples/style_profile_example.md

Shows what a Journal Style Profile may look like.

### examples/hostile_review_report_example.md

Shows what a hostile peer review report may look like.

### examples/reference_audit_report_example.md

Shows what a reference audit report may look like.

### examples/rewritten_section_example.md

Shows how a weak section can be rewritten in an argument-forward style.

### examples/final_coherence_report_example.md

Shows what a final coherence report may look like.

## 13. Recommended use order

Use the repository in this order:

```text
1. docs/how_to_use.md
2. workflow/00_full_pipeline.md
3. workflow/01_target_journal_articles.md
4. prompts/01_article_style_analyzer.md
5. prompts/02_journal_profile_generator.md
6. templates/journal_style_profile_template.md
7. workflow/03_draft_generation.md
8. prompts/03_vak_draft_writer.md
9. workflow/04_reference_audit.md
10. prompts/04_reference_reality_checker.md
11. workflow/05_citation_claim_alignment.md
12. prompts/05_citation_claim_alignment_checker.md
13. workflow/06_hostile_review.md
14. prompts/06_hostile_peer_reviewer.md
15. workflow/07_structural_reconstruction.md
16. prompts/07_structural_reconstruction_planner.md
17. workflow/08_argument_forward_rewrite.md
18. prompts/08_argument_forward_rewriter.md
19. workflow/09_final_coherence_polishing.md
20. prompts/09_final_coherence_polisher.md
21. checklists/final_submission_checklist.md
```

## 14. Minimal workflow for quick use

If the full workflow is too long, use this shorter sequence:

```text
1. Create Journal Style Profile.
2. Draft manuscript.
3. Audit references.
4. Check citation-claim alignment.
5. Run hostile review.
6. Rebuild structure.
7. Rewrite argument-forward.
8. Run final coherence check.
9. Use final submission checklist.
```

## 15. Safety rules

Do not commit:

* copyrighted journal PDFs;
* full article texts;
* paywalled materials;
* private manuscript drafts;
* unpublished dissertation chapters;
* supervisor comments;
* reviewer correspondence;
* private data;
* fake references;
* invented DOI numbers.

Safe to commit:

* prompts;
* templates;
* workflows;
* checklists;
* fictional examples;
* high-level style profiles;
* repository documentation.

## 16. Maintenance notes

When adding new files:

1. Put prompts in `prompts/`.
2. Put workflows in `workflow/`.
3. Put templates in `templates/`.
4. Put rules in `rules/`.
5. Put checklists in `checklists/`.
6. Put phrase collections in `phrasebank/`.
7. Put fictional examples in `examples/`.
8. Put project explanations in `docs/`.

After adding major files, update:

```text
README.md
docs/repository_map.md
```

## 17. Current project status

The repository now contains the main structure for a full AI-assisted ВАК manuscript stress-test workflow.

Core modules are present:

* target journal style analysis;
* journal style profile generation;
* draft generation;
* reference reality checking;
* citation-claim alignment checking;
* hostile peer review;
* structural reconstruction;
* argument-forward rewriting;
* final coherence polishing;
* final submission checklist.

## Final rule

This repository is useful only if it protects academic integrity.

The workflow should strengthen the manuscript without copying target articles, inventing references, or hiding weak evidence.
