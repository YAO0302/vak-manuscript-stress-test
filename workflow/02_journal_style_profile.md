# Workflow 02: Journal Style Profile

This workflow explains how to turn target journal article analysis into a reusable Journal Style Profile.

It is designed for Russian-language academic articles intended for ВАК journals or related scholarly publications.

## Purpose

The purpose of this workflow is to create a practical writing profile for a target journal.

The profile should help the author understand:

* how the journal structures articles;
* how introductions are written;
* how abstracts are organized;
* how methodology is presented;
* how citations are used;
* how arguments are developed;
* how conclusions are formulated;
* what style should be avoided.

The profile should guide writing and revision.

It should not copy journal text.

## Core rule

A Journal Style Profile is not a collection of copied phrases from published articles.

It is a high-level operational description of the journal's writing expectations.

Allowed:

* structural patterns;
* general style tendencies;
* section order;
* citation behavior;
* argumentation model;
* abstract logic;
* introduction logic;
* conclusion logic;
* safe reusable formulas written independently.

Not allowed:

* copied paragraphs;
* copied sentences;
* large excerpts;
* imitation of one author;
* reuse of copyrighted text;
* uploading source PDFs to the public repository.

## Required input

Before starting this workflow, prepare:

1. 3-10 target journal articles;
2. metadata for each article;
3. article style analysis report;
4. official journal author guidelines, if available;
5. target manuscript topic;
6. target manuscript field;
7. target ВАК specialty, if known.

Use the previous workflow:

```text
workflow/01_target_journal_articles.md
```

Use the analyzer prompt:

```text
prompts/01_article_style_analyzer.md
```

## Recommended article sample

Minimum:

```text
3 articles
```

Better:

```text
5-7 articles
```

Maximum for one coherent profile:

```text
10 articles
```

Do not mix different journals in one profile.

Do not mix unrelated article types unless the target manuscript also requires such variation.

## Step 1. Review the style analysis report

The style analysis report should include:

* general journal style;
* common article structure;
* title patterns;
* abstract structure;
* keyword patterns;
* introduction structure;
* methodology presentation;
* literature review behavior;
* citation style;
* argumentation pattern;
* paragraph structure;
* conclusion structure;
* common formulas;
* avoid list.

If the analysis report is weak, repeat the analysis with better article selection.

## Step 2. Separate style from content

Do not confuse journal style with article topic.

Style means:

* how the article is organized;
* how arguments are introduced;
* how methodology is written;
* how citations are distributed;
* how conclusions are framed;
* how formal academic Russian is used.

Content means:

* the specific topic;
* the author's research material;
* the article's specific findings;
* the cited sources;
* the author's original argument.

The style profile should extract style, not content.

## Step 3. Identify stable patterns

Look for patterns that appear across several articles.

Stable patterns may include:

* abstracts begin with relevance;
* introductions include object, subject, aim, and tasks;
* methodology is briefly stated in the introduction;
* literature review groups sources by research direction;
* conclusions return to the aim;
* citations are dense in the literature review but lighter in analysis;
* articles use formal but not overly complex Russian.

Do not treat one unusual article as the journal norm.

## Step 4. Identify journal-specific requirements

If official author guidelines are available, record:

* article length;
* abstract length;
* keyword number;
* formatting rules;
* citation style;
* bibliography style;
* author information format;
* originality requirements;
* ethics policy;
* AI-use policy, if available.

Official guidelines override style inference from published articles.

## Step 5. Build the profile structure

Use this template:

```text
templates/journal_style_profile_template.md
```

The profile should include:

1. Basic information.
2. General journal style.
3. Typical article structure.
4. Title pattern.
5. Abstract pattern.
6. Keyword pattern.
7. Introduction pattern.
8. Methodology pattern.
9. Theoretical framework pattern.
10. Argumentation pattern.
11. Citation behavior.
12. Sentence-level style.
13. Paragraph-level style.
14. Conclusion pattern.
15. What to avoid.
16. Operational writing instruction.
17. Confidence and missing information.

## Step 6. Generate the profile

Use:

```text
prompts/02_journal_profile_generator.md
```

Input should include:

* article style analysis report;
* article metadata;
* journal guidelines, if available;
* target manuscript topic;
* target manuscript field;
* intended article type.

The output should be a reusable Journal Style Profile.

## Step 7. Check the profile for safety

The profile must not include:

* copied article paragraphs;
* copied article sentences;
* large excerpts;
* paywalled content;
* private author drafts;
* unverifiable claims about the journal;
* fake citation requirements;
* invented official guidelines.

If any copied text appears, remove it.

Replace copied text with high-level description.

## Step 8. Check profile usefulness

A useful profile should answer:

* How should the title be written?
* How should the abstract be structured?
* How should актуальность be introduced?
* How should the research gap be formulated?
* Where should object, subject, aim, and tasks appear?
* How should methodology be explained?
* How should literature be reviewed?
* How should claims be supported?
* How should the conclusion be written?
* What style should be avoided?

If the profile is too vague, revise it.

## Step 9. Add confidence levels

Every profile should include confidence levels.

Use:

```text
High confidence
```

For patterns that appear in most analyzed articles.

Use:

```text
Medium confidence
```

For patterns that appear in several articles but may vary.

Use:

```text
Low confidence
```

For patterns inferred from limited evidence.

Use:

```text
Requires manual check
```

For official requirements that must be verified from journal guidelines.

## Step 10. Convert profile into writing rules

The profile should produce operational instructions such as:

```text
Begin the introduction with a specific academic problem, not a broad historical statement.
```

```text
State object, subject, aim, tasks, material, and methods in the introduction unless the journal profile shows a different pattern.
```

```text
Do not list methods mechanically. Explain how each method answers the research question.
```

```text
Use citations to support specific claims, not as decoration.
```

```text
Conclude by returning to the aim and summarizing supported findings.
```

## Step 11. Use the profile for drafting

After the profile is ready, use it with:

```text
prompts/03_vak_draft_writer.md
```

The draft writer should receive:

* target journal style profile;
* research topic;
* object;
* subject;
* aim;
* tasks;
* material;
* methods;
* verified references;
* author notes.

If key research information is missing, the draft must mark it clearly.

Use markers such as:

```text
[AUTHOR MUST PROVIDE]
[SOURCE REQUIRED]
[VERIFY REFERENCE]
[RESULT REQUIRES EVIDENCE]
```

## Step 12. Update the profile after testing

The first profile may not be perfect.

Update it after:

* drafting an abstract;
* drafting an introduction;
* running hostile peer review;
* checking references;
* comparing with official journal guidelines;
* receiving human supervisor feedback;
* receiving reviewer comments.

Do not treat the first profile as final.

## Example profile summary

A compact profile may look like this:

```text
The target journal uses formal Russian academic prose with a clear ВАК-style structure. Articles usually begin with актуальность, move to a research gap, and then state object, subject, aim, tasks, material, and methods. Methodology is often brief but should be explicitly connected to the research question. Literature review paragraphs synthesize research directions rather than list authors mechanically. Conclusions return to the aim, summarize supported findings, and state scholarly contribution. The style should be precise, non-colloquial, and free from excessive defensive formulas.
```

## Common profile problems

### Problem 1. Profile is too generic

Weak:

```text
The journal uses academic style.
```

Better:

```text
The journal usually structures introductions through актуальность, literature positioning, research gap, object, subject, aim, tasks, methods, and material.
```

### Problem 2. Profile copies article wording

Fix:

Remove copied wording and describe the pattern in your own words.

### Problem 3. Profile mixes several journals

Fix:

Create separate profiles for separate journals.

### Problem 4. Profile ignores official guidelines

Fix:

Check the journal website and add verified requirements.

### Problem 5. Profile imitates weak writing

Fix:

Use the profile to identify expectations, not to reproduce poor academic habits.

## Journal Style Profile Checklist

Before using the profile, check:

* target journal is clearly named;
* article sample is representative;
* article type is identified;
* field is identified;
* structure is described;
* abstract pattern is described;
* introduction pattern is described;
* methodology pattern is described;
* citation behavior is described;
* conclusion pattern is described;
* avoid list is included;
* official guidelines are checked or marked as missing;
* no copyrighted text is copied;
* no fake requirements are invented;
* confidence level is stated.

## Safe storage

Safe to store in repository:

* profile template;
* fictional profile example;
* high-level style profile written by the user;
* workflow notes;
* checklists;
* prompts.

Do not store:

* article PDFs;
* full article texts;
* copied excerpts;
* private drafts;
* supervisor comments;
* reviewer correspondence;
* paywalled material.

## Final output of this workflow

At the end of this workflow, you should have:

1. a completed Journal Style Profile;
2. a compact style summary;
3. journal-specific writing rules;
4. an avoid list;
5. confidence levels;
6. missing information list;
7. next-step instructions for drafting.

## Final decision

Use one of the following decisions.

```text
Ready for draft generation
```

Use when the style profile is specific, safe, and operational.

```text
Profile needs revision
```

Use when the profile is too vague or incomplete.

```text
Need more target articles
```

Use when article sample is too small or not representative.

```text
Need official journal guidelines
```

Use when formatting, citation, or submission requirements are unknown.

```text
Do not use this profile
```

Use when the profile contains copied text, mixed journal patterns, or unreliable assumptions.

## Final rule

A Journal Style Profile should make writing easier, safer, and more consistent.

It should guide the manuscript toward the target journal without copying the target journal.
