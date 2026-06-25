# VAK Manuscript Stress Test

AI-assisted workflow for Russian ВАК journal writing, reference auditing, hostile peer review, and manuscript reconstruction.

## What this project does

This project provides a structured workflow for preparing Russian-language academic manuscripts for ВАК journals and related scholarly publications.

It helps researchers:

* analyze the writing style of selected target journal articles;
* extract a reusable journal style profile;
* generate or revise academic drafts;
* audit references and detect suspicious or fabricated citations;
* simulate hostile peer review;
* identify methodological, logical, and structural weaknesses;
* reconstruct the manuscript argument;
* rewrite key sections without defensive over-explanation.

## Core workflow

1. Upload selected articles from a target ВАК journal.
2. Extract the journal's writing structure, rhetorical logic, and academic language patterns.
3. Generate or revise a manuscript draft according to the journal style profile.
4. Check whether references are real, consistent, and relevant.
5. Simulate a hostile peer review and identify possible rejection reasons.
6. Create a structural reconstruction plan.
7. Rewrite key sections with direct, clear, argument-forward academic prose.
8. Run a final coherence and submission-readiness check.

## Repository structure

The repository is organized into several folders.

```text
vak-manuscript-stress-test/
├── docs/
├── workflow/
├── prompts/
├── templates/
├── rules/
├── checklists/
├── phrasebank/
└── examples/
```

### docs/

Project documentation and usage guidance.

Key files:

* `docs/how_to_use.md`
* `docs/copyright_and_ethics.md`
* `docs/limitations.md`
* `docs/repository_map.md`

### workflow/

Step-by-step workflow from target journal analysis to final submission readiness.

Key files:

* `workflow/00_full_pipeline.md`
* `workflow/01_target_journal_articles.md`
* `workflow/02_journal_style_profile.md`
* `workflow/03_draft_generation.md`
* `workflow/04_reference_audit.md`
* `workflow/05_citation_claim_alignment.md`
* `workflow/06_hostile_review.md`
* `workflow/07_structural_reconstruction.md`
* `workflow/08_argument_forward_rewrite.md`
* `workflow/09_final_coherence_polishing.md`

### prompts/

Reusable AI prompts for each stage of the manuscript stress-test workflow.

Key files:

* `prompts/01_article_style_analyzer.md`
* `prompts/02_journal_profile_generator.md`
* `prompts/03_vak_draft_writer.md`
* `prompts/04_reference_reality_checker.md`
* `prompts/05_citation_claim_alignment_checker.md`
* `prompts/06_hostile_peer_reviewer.md`
* `prompts/07_structural_reconstruction_planner.md`
* `prompts/08_argument_forward_rewriter.md`
* `prompts/09_final_coherence_polisher.md`

### templates/

Reusable templates for ВАК-style article components.

Key files:

* `templates/journal_style_profile_template.md`
* `templates/vak_article_structure.md`
* `templates/abstract_template.md`
* `templates/introduction_template.md`
* `templates/methodology_template.md`
* `templates/conclusion_template.md`

### rules/

Rules for academic logic, Russian academic style, citation integrity, paragraph structure, and method-question alignment.

Key files:

* `rules/banned_defensive_formulas.md`
* `rules/method_question_alignment.md`
* `rules/paragraph_task_rules.md`
* `rules/citation_integrity_rules.md`
* `rules/russian_academic_style.md`
* `rules/vak_article_logic.md`

### checklists/

Practical checklists for auditing and final review.

Key files:

* `checklists/reference_audit_checklist.md`
* `checklists/hostile_review_checklist.md`
* `checklists/final_submission_checklist.md`
* `checklists/method_question_fit_checklist.md`
* `checklists/logical_break_checklist.md`

### phrasebank/

Reusable Russian academic phrases.

Key file:

* `phrasebank/academic_russian_phrases.md`

### examples/

Fictional examples showing expected outputs.

Key files:

* `examples/style_profile_example.md`
* `examples/hostile_review_report_example.md`
* `examples/reference_audit_report_example.md`
* `examples/rewritten_section_example.md`
* `examples/final_coherence_report_example.md`

## Main modules

* Journal style profiling
* Russian academic writing adaptation
* ВАК manuscript structure
* Reference reality audit
* Citation-claim alignment check
* Hostile peer review simulation
* Method-question alignment check
* Argument-forward rewriting
* Final manuscript coherence check

## Who this is for

This project is intended for:

* PhD students writing in Russian;
* international researchers publishing in Russian ВАК journals;
* researchers in humanities, cultural studies, philosophy, art history, architecture, and social sciences;
* authors who want to test a manuscript before submission.

## What this project does not do

This project does not generate fake references.

This project does not redistribute copyrighted journal articles.

This project does not imitate individual authors.

This project does not replace human academic judgment, supervisors, reviewers, or editors.

This project extracts high-level academic writing patterns and helps users audit, revise, and strengthen manuscripts.

## Copyright and ethics

Users should analyze only articles they have lawful access to.

Uploaded journal articles should be used locally or inside the user's own AI workspace. They should not be committed to this public repository.

The project is designed to support responsible academic writing, not plagiarism, ghostwriting, or citation fabrication.

## Current status

Version: v0.1 draft.

The first version focuses on prompts, workflows, templates, rules, and checklists.

## Roadmap

* v0.1: Core workflow and main prompts
* v0.2: Russian academic phrasebank
* v0.3: Cultural studies, architecture, philosophy, and art history templates
* v0.4: Examples of journal style profiles and review reports
* v0.5: Optional scripts for local document processing
