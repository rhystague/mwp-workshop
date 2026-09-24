---
name: process-weekly-research-insight
description: Process a weekly research insight for this Obsidian research vault by prompting the researcher with the weekly rhythm questions, connecting the resulting insight to relevant paper notes, maps, research questions, or potential paper ideas, appending a dated entry to Insights/Weekly Insights.md, and updating linked notes with backlinks where useful. Use when Codex is asked to do the weekly research insight, weekly research reflection, research insight capture, or end-of-week research synthesis.
---

# Process Weekly Research Insight

## Overview

Treat the weekly research insight as a short pre-processing conversation before writing. Use it to surface what the researcher noticed, why it matters, and what question should carry forward, then connect the insight to the vault without turning it into heavy administration.

Read `Research-Strategies/Weekly Research Rhythm.md` before processing so the prompt structure matches the current weekly routine.

## Vault Resources

Read these only when needed:

- `Research-Strategies/Weekly Research Rhythm.md`: always read first to confirm the current weekly insight structure.
- `Insights/Weekly Insights.md`: read before appending to preserve the existing format and avoid duplicate entries.
- `Researcher Identity.md`: use when judging whether an insight connects to the researcher's core frame.
- `Research Questions.md`: use when the insight raises or sharpens a live question.
- Relevant notes in `Paper-Notes/`, `Maps/`, or `Potential-Papers/`: read when the user's answers mention a paper, concept, author, project, or idea that may already exist in the vault.

Do not invent citations, paper records, findings, quotations, page numbers, DOIs, or links. If a relevant paper or note cannot be found, state that plainly and leave the connection as a search lead rather than a confirmed link.

## Workflow

### 1. Ask The Weekly Questions First

When invoked without the user's three answers, ask the questions one at a time:

1. `What did you notice this week in your research?`
2. `This matters because?`
3. `The next question is?`

Stop after each question and wait for the answer. Do not draft, search, append, or update notes until all three answers are available.

If the user provides all three answers upfront, proceed without re-asking.

### 2. Build A Brief Insight

Turn the answers into a compact weekly insight in the researcher's voice. Preserve useful phrasing from the answers. Keep the entry short and generative:

```markdown
## Weekly research insight - YYYY-MM-DD

This week I noticed that ...

This matters because ...

The next question is ...
```

Use the current local date unless the user specifies a different date.

### 3. Find Relevant Vault Connections

Search the vault for mentioned papers, authors, concepts, projects, and live questions. Prioritize likely matches in this order:

1. `Paper-Notes/`
2. `Maps/`
3. `Research Questions.md`
4. `Potential-Papers/`

Use Obsidian wikilinks for confirmed internal connections. Mark uncertain matches as possible connections in the response rather than adding them as links.

### 4. Append The Weekly Insight

Append the dated entry to `Insights/Weekly Insights.md`. Include a short `Connections` line only when confirmed links are useful:

```markdown
Connections: [[Paper Note Title]], [[Map Note Title]]
```

Do not add a connections line when there are no confirmed useful links.

### 5. Update Linkbacks Where Useful

When a confirmed paper note, map note, research question, or potential paper idea is substantively related, add a brief linkback to that note. Prefer a small section or bullet that fits the existing note:

```markdown
- Weekly insight: [[Weekly Insights#Weekly research insight - YYYY-MM-DD]] - one concise reason this insight matters here.
```

Only update a note when the linkback will help future retrieval or synthesis. Do not scatter backlinks across weakly related notes.

### 6. Report What Changed

Briefly state:

- The insight appended.
- Confirmed notes linked.
- Any paper or concept connection that looked relevant but could not be confirmed.
- One concrete next action if the insight suggests a useful reading, map update, or paper-development move.

## Output Standards

Keep the final insight concise, dated, and easy to scan. Preserve uncertainty. Prefer research judgement, tensions, and next questions over summaries of activity.
