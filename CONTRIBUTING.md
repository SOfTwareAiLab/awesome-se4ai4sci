# Contributing

Thank you for helping maintain this list. The rules below keep entries consistent, verifiable and machine-readable, so that the list can serve as the basis for a future systematic survey.

## What belongs here

An entry qualifies if it does at least one of the following:

- builds, evaluates or critiques an AI system that does scientific work (hypothesis generation, experiment design, code, execution, analysis, writing);
- documents a failure, risk or research-integrity threat of such systems;
- supplies a software engineering technique for any stage of the scientific assurance chain (intent, workflow, implementation, execution, evidence, claim);
- forms part of the SE4Science or research software engineering foundations that the agenda builds on;
- is a benchmark or evaluation study of AI research agents.

The list is deliberately strict about what counts as in-field. Work with no scientific setting is included only when it is a primary reference for a technique the vision paper names for a chain stage or its research agenda, or when it applies LLMs or agents to such a technique (for example property-based testing, metamorphic testing, sandboxing, capability restriction or provenance). A few canonical surveys of neighbouring fields are kept under Foundations and Related Areas.

Not included: general LLM, agent or AI-safety papers that only document model behaviour with no scientific setting, general code-generation benchmarks, misuse and biosecurity evaluations, science-knowledge question-answering benchmarks that do not exercise a research workflow, mathematics-only systems (kept only as context), scientific software packages without a verified agent interface (these belong in [SOFTWARE.md](SOFTWARE.md), not in README), and items without a resolvable identifier or official page.

## Where a chain entry goes

Each of the six stages of the Scientific Assurance Chain separates its entries into three groups:

- **Where it breaks**: documented failures of AI systems doing scientific work at that stage (incidents, audits, case studies, and evaluations whose headline is the failure).
- **Existing foundations**: techniques, tools, standards and evidence from software engineering, scientific computing and metascience that were not built for AI-driven science but could be adapted.
- **SE4AISci work**: techniques, tools, protocols and assurance-targeted benchmarks built for AI-driven scientific workflows.

Pick the stage whose assurance problem the work addresses, then the group. A failure study that spans several stages goes under Cross-cutting failures.

## Verification standard

Before adding an entry, confirm the following from a live registry or official page (DOI, arXiv, ACL Anthology, OpenReview, publisher, or the project site):

- title, first author, venue and year;
- the paper link resolves;
- the code link, if given, exists and matches the paper by name, owner or the paper's own metadata.

Years follow the year the publisher cites for the version of record (the issue year) for journal articles, and the first arXiv version for preprints. If a peer-reviewed version exists, cite it and link the preprint only when the peer-reviewed version is not openly accessible.

## Entry format

One line per entry, placed in the section where its main contribution lies. Add the same entry to a second section only when it is a seed case for that section.

```
- Title (Venue Year) [[paper]](link) [[code]](link)
```

For venues and communities:

```
- Name [[website]](link)
```

For related awesome lists:

```
- [Name](link)
```

Rules:

- Title in plain text, exactly as published. No description after the links.
- Venue and year in parentheses. Use the venue abbreviation readers recognise (ICSE, ICLR, Nature, PNAS). Use `arXiv` for preprints and the series name for workshops. Put the year last and reuse the spelling already in the list (for example `Findings of ACL 2025`, `NeurIPS Datasets and Benchmarks 2025`, `TOSEM 2026`, `PLOS ONE 2021`).
- Prefer peer-reviewed work in well-known venues or arXiv preprints. Entries from regional or low-visibility journals are accepted only when the work is widely cited or is the primary source for a documented failure.
- `[[paper]]` is required for papers. `[[code]]`, `[[website]]` or `[[data]]` are optional and only when the link exists and matches.
- No em-dashes, no emojis.
- Entries within a list are ordered by year descending, then by title ignoring case. Venues and lists are alphabetical.
- Each work appears once, in the section where its main contribution lies. The only exception is the six grounding cases of the vision paper, which appear both in their assurance-chain stage and in their home section. Each stage heading names its grounding case.

## Pull requests

- One topic per pull request. Several entries for the same section are fine.
- Update the "updated" badge at the top of README.md.
- Keep the section titles and the three group labels under each stage unchanged. They follow the wording of the SE4AISci vision paper.
- Run a link check locally before opening the pull request, for example with `lychee README.md`, or state in the description that each link was opened by hand.

## Suggesting without a pull request

Open an issue using the "Suggest an entry" template with the title, the link and the section you think it belongs to. A maintainer will verify and add it.
