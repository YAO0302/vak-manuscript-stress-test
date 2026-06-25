# Workflow 01: Target Journal Articles

This workflow explains how to select and prepare target journal articles for style analysis.

It is designed for Russian-language academic articles intended for ВАК journals or related scholarly publications.

## Purpose

The purpose of this step is to collect a small set of articles from the target journal so that the AI can analyze the journal's writing style, article structure, citation behavior, argumentation pattern, and formal academic expectations.

This step does not produce the manuscript yet.

It produces the source basis for creating a reusable journal style profile.

## Core rule

Do not upload copyrighted journal PDFs, full-text articles, private drafts, or paywalled materials to a public GitHub repository.

Target articles may be used privately for analysis, but the repository should contain only:

* workflow instructions;
* prompts;
* templates;
* checklists;
* high-level style profiles;
* fictional examples;
* non-copyrighted notes;
* metadata created by the user.

## Recommended number of target articles

Use:

```text
3-10 articles
```

Recommended minimum:

```text
3 articles
```

Recommended strong sample:

```text
5-7 articles
```

Recommended maximum for one style profile:

```text
10 articles
```

Too few articles may produce a weak profile.

Too many articles may mix different article types and weaken the result.

## Article selection criteria

Select articles that match the intended manuscript as closely as possible.

Check:

* same journal;
* same academic field;
* same ВАК specialty, if possible;
* same article type;
* similar topic area;
* similar methodology;
* similar length;
* recent publication date;
* normal published research article, not editorial or announcement;
* complete article structure available.

## Preferred article types

Use:

* research articles;
* theoretical articles;
* methodological articles;
* case-study articles;
* literature-based analytical articles.

Avoid:

* editorials;
* book reviews;
* conference announcements;
* author instructions;
* news items;
* obituaries;
* short notes;
* purely bibliographic lists;
* articles outside the target field.

## Recency rule

Prefer recent articles.

Recommended period:

```text
last 3-5 years
```

Older articles may still be useful if:

* the journal style has remained stable;
* the article is highly relevant;
* the article is frequently cited;
* the journal has few recent articles in the topic area.

Do not rely only on old articles if recent examples are available.

## Field match rule

The selected articles should match the intended manuscript's field.

For a manuscript about traditional Chinese culture, architecture, and active longevity, suitable fields may include:

* cultural studies;
* architecture theory;
* urban studies;
* art history;
* design theory;
* social and cultural analysis of space;
* age-friendly environment research;
* active longevity research, if the manuscript makes such claims.

Avoid using articles from unrelated fields only because they are from the same journal.

## Journal style vs topic relevance

There are two different kinds of relevance.

### Journal style relevance

The article helps show how the journal writes.

Useful for:

* structure;
* tone;
* abstract style;
* introduction pattern;
* citation density;
* conclusion style.

### Topic relevance

The article helps support the manuscript's argument.

Useful for:

* literature review;
* theoretical framework;
* evidence;
* citation support.

A target article can be useful for style analysis even if it is not directly cited in the manuscript.

However, do not cite an article unless it actually supports a specific claim.

## Do not copy journal text

The goal is to analyze high-level patterns, not to copy language.

Allowed:

* identify section structure;
* summarize argument patterns;
* describe citation behavior;
* extract general style tendencies;
* note common academic formulas in your own words;
* create a high-level style profile.

Not allowed:

* copying full paragraphs;
* reusing author phrasing;
* rewriting the manuscript by imitating one article too closely;
* uploading full copyrighted text to GitHub;
* publishing paywalled PDFs;
* publishing large excerpts from journal articles.

## Safe metadata table

Use this table privately to organize the selected articles.

Do not include copyrighted full text.

| No. | Article title | Authors | Journal | Year | Field | Article type | Why selected |
| --: | ------------- | ------- | ------- | ---: | ----- | ------------ | ------------ |
|   1 |               |         |         |      |       |              |              |
|   2 |               |         |         |      |       |              |              |
|   3 |               |         |         |      |       |              |              |
|   4 |               |         |         |      |       |              |              |
|   5 |               |         |         |      |       |              |              |

If the article is paywalled or copyrighted, keep the file private and do not commit it to the repository.

## Recommended local folder structure

For private local work, use:

```text
private/
  target_articles/
  article_notes/
  journal_guidelines/
  draft_versions/
```

These folders should not be committed to GitHub.

The repository `.gitignore` should already block:

```text
private/
articles/
pdfs/
source_articles/
drafts/
*.pdf
*.doc
*.docx
```

## Step-by-step process

### Step 1. Choose the target journal

Record:

* journal name;
* official website;
* ВАК status or indexing status;
* accepted specialties;
* article length;
* citation style;
* abstract requirements;
* keyword requirements;
* formatting rules;
* publication ethics rules;
* AI-use policy, if available.

If the target journal is not fixed, create separate style profiles for each candidate journal.

Do not merge different journals into one profile.

### Step 2. Collect candidate articles

Find articles from the target journal that are close to your manuscript.

For each article, record:

* title;
* authors;
* year;
* issue;
* article type;
* topic;
* method;
* length;
* citation style;
* reason for selection.

### Step 3. Remove unsuitable articles

Remove articles that are:

* outside the field;
* too old;
* too short;
* editorial or non-research text;
* stylistically abnormal;
* not representative of the journal;
* impossible to verify;
* unrelated to the target manuscript type.

### Step 4. Prepare private analysis input

Prepare the selected articles for private AI analysis.

Use one of the following:

* privately uploaded PDFs;
* article text copied into a private AI session;
* personal notes made from the articles;
* metadata and section summaries.

Do not place copyrighted source text in the public repository.

### Step 5. Run article style analysis

Use:

```text
prompts/01_article_style_analyzer.md
```

The output should describe:

* general journal style;
* article structure;
* abstract pattern;
* introduction pattern;
* methodology pattern;
* citation behavior;
* argumentation pattern;
* sentence style;
* paragraph style;
* conclusion pattern;
* what to avoid.

### Step 6. Generate journal style profile

Use:

```text
prompts/02_journal_profile_generator.md
```

The output should become a reusable journal style profile.

It should not include copied paragraphs from journal articles.

It should describe operational writing rules.

### Step 7. Save only safe outputs

Safe outputs may include:

* high-level journal style profile;
* checklist notes;
* article metadata;
* personal analytical summary;
* fictional examples;
* style rules in your own words.

Do not save:

* full PDFs;
* full article texts;
* large excerpts;
* paywalled material;
* copied journal paragraphs;
* private unpublished drafts;
* reviewer correspondence.

## Article style analysis questions

When analyzing target articles, ask:

1. How does the article introduce relevance?
2. How does it formulate the research problem?
3. Does it state object, subject, aim, and tasks?
4. Where does methodology appear?
5. How are methods explained?
6. How is literature reviewed?
7. Are citations dense or selective?
8. Does the article use many Russian sources, international sources, or both?
9. How are paragraphs structured?
10. How long are sections?
11. How does the article move from theory to analysis?
12. How are conclusions written?
13. Does the article state novelty?
14. Does it state theoretical or practical significance?
15. What phrases appear frequently?
16. What style should not be copied?

## Style profile output checklist

The final journal style profile should contain:

* journal name;
* field;
* article type;
* number of analyzed articles;
* general style summary;
* typical structure;
* title pattern;
* abstract pattern;
* keyword pattern;
* introduction pattern;
* methodology pattern;
* literature review pattern;
* citation behavior;
* sentence-level style;
* paragraph-level style;
* conclusion pattern;
* avoid list;
* operational writing instruction;
* confidence level;
* missing information.

Use:

```text
templates/journal_style_profile_template.md
```

## Warning signs in selected articles

Be careful if selected articles show:

* very weak methodology;
* poor citation practice;
* unclear structure;
* fake or unverifiable references;
* excessive defensive language;
* low-quality writing;
* non-standard formatting;
* unusual article type;
* special issue style not used by normal articles.

Do not copy weaknesses from target articles.

Use target articles to understand journal expectations, not to reproduce poor academic habits.

## Copyright and ethics reminder

This workflow must follow:

```text
docs/copyright_and_ethics.md
```

Main rules:

* do not upload copyrighted PDFs to the public repository;
* do not reproduce full journal articles;
* do not copy paragraphs;
* do not generate fake references;
* do not hide unverifiable sources;
* do not treat AI output as final scholarship without author review;
* verify journal requirements manually before submission.

## Final output of this workflow

At the end of this workflow, you should have:

1. a selected set of target journal articles;
2. a private article metadata table;
3. a style analysis report;
4. a reusable journal style profile;
5. a list of journal-specific writing rules;
6. a list of risks and missing information.

## Final decision

Use one of the following decisions.

```text
Ready for style profile generation
```

Use when selected articles are relevant, representative, and sufficient.

```text
Need more target articles
```

Use when fewer than three suitable articles are available.

```text
Need better article match
```

Use when selected articles do not match the manuscript field or article type.

```text
Do not use this article set
```

Use when articles are unrelated, outdated, non-representative, or ethically unsafe to use.

## Final rule

The quality of the journal style profile depends on the quality of the target articles.

Do not analyze random articles.

Select articles that represent the journal, the field, and the manuscript type.
