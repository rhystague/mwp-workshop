---
name: paper-processing
description: Process scholarly papers into useful Obsidian research notes, reading-depth decisions, synthesis-map updates, and writing-use judgments for this research vault. Use when a paper, abstract, DOI, Zotero item, citation, PDF, highlights, or paper metadata is shared or identified and Codex needs to classify relevance, recommend reading depth, create or update a paper note, extract research implications, or connect the paper to maps, research questions, or potential papers.
---
# Paper Processing

Process papers as research judgment work, not as book-report summarization. Preserve the researcher's agency by separating what the paper says, what you infer, and how the researcher might use it.

## Vault Resources

Load these files only when the task reaches the relevant step:

- `docs/templates/Paper Note Template.md`: use when creating or updating a paper note.
- `docs/templates/Map Note Template.md`: use when proposing or creating a synthesis map.
- `Researcher Identity.md`: use when judging fit with the researcher's scholarly frame.
- `Research Questions.md`: use when connecting the paper to live questions or paper seeds.

If the user has not provided enough source material, ask for the missing abstract, DOI, Zotero metadata, highlights, or paper text. Do not invent citations, quotations, page numbers, findings, methods, or Zotero records.

## Workflow

### Default Meaning of "Process This Paper"

When the user says "process this paper" or gives a similarly broad request, treat that as permission to triage the paper only:

1. Establish source material.
2. Classify relevance.
3. Recommend reading depth.
4. Give tailored reading questions.
5. Stop.

Do not infer permission to create paper notes, update maps, revise potential papers, or otherwise write to the vault from a broad "process" request.

Proceed past the reading-depth gate only when the user explicitly says something like:

- "Create the paper note"
- "Proceed from the PDF"
- "Process fully"
- "I've read enough; make the note"
- "Go ahead and update the vault"

### 1. Establish Source Material

Identify what evidence is available:

- Paper metadata only: title, authors, venue, year, DOI, abstract.
- User-provided excerpts or highlights.
- Full paper text or PDF.
- Zotero item details.

State the evidence basis briefly when it affects confidence.

### 2. Classify Relevance

Assign one queue and give a one-sentence rationale:

- `Core Identity`: directly supports Accessible Spatial Interaction and Nonvisual Navigation.
- `Methods & Theory`: supports HCI, accessibility, spatial cognition, auditory or tactile perception, participatory design, or research design.
- `Application Areas`: supports navigation in public buildings, transport interchanges, indoor–outdoor routes, or repeated everyday journeys.
- `Wildcard`: provocative or potentially generative, but not obviously central.
- `Adjacent`: relevant to museum exploration, tactile graphics, navigation when visual attention is occupied, or other spatial interaction contexts without a clear central link.

Mark work as adjacent unless it clearly connects back to nonvisual spatial representation, sensory interaction, orientation, or navigation for blind and low-vision people.

### 3. Recommend Reading Depth

Choose one reading depth and explain why:

- `7-minute scan`: decide Keep, Skim later, Cite only, or Discard.
- `25-minute useful read`: capture concepts, methods, evidence, and possible writing uses.
- `Deep read`: reserve for spine citations, theory/framework papers, direct writing support, or papers that challenge the researcher's thinking.
- `Discard`: not worth further reading for the current research program.

Then stop and inform the user of the recommended depth. Include 2-4 reading questions tailored to the paper and queue. Do not create or update the paper note until the user indicates they have read enough or explicitly asks you to proceed from the available material.

Required stop-point response shape:

- Evidence basis
- Queue
- Recommended reading depth
- Why this depth
- 2-4 reading questions
- Ask whether to proceed

Hard stop rule: after recommending reading depth, stop. Do not create or update any note, map, synthesis, or potential-paper file unless the user explicitly gives a second instruction to proceed. The phrase "process this paper" is not permission to proceed past this gate.

### 4. Create Or Update The Paper Note

After the user confirms they have read the paper or asks you to work from the provided material:

1. Read `docs/templates/Paper Note Template.md`.
2. Create or update the relevant note in `Paper-Notes/`.
3. Keep the note compact and usable for future writing.
4. Use Obsidian wikilinks where they help retrieval.

Capture:

- One-line takeaway.
- Relevance to the research identity.
- Key contribution.
- Useful concepts.
- Method and evidence.
- Where the paper could be used.
- Researcher's reaction, tensions, and open questions.

Distinguish paper summary from assistant interpretation and possible research argument.

### 5. Update Synthesis

Add 1-3 distilled insights to relevant notes in `Maps/` when the paper changes or sharpens a reusable concept.

If no relevant map exists, propose a new map note only when the concept is likely to recur. Read `docs/templates/Map Note Template.md` before creating one.

### 6. Identify Writing Use

Decide whether the paper supports:

- A current or potential paper.
- A research question.
- A literature gap.
- An accessible interaction design or navigation evaluation argument.
- A grant, promotion, or positioning narrative.

For paper ideas, read `Researcher Identity.md`, `Research Questions.md`, and `docs/templates/Potential Paper Template.md` before creating or revising files in `Potential-Papers/`.

## Output Standards

Use concise academic working prose. Prefer claims, tensions, evidence needs, and writing affordances over exhaustive summary.

Flag weak evidence, overclaims, missing methods, unclear contribution, unsupported causal claims, and uncertain fit. Treat every paper as selectively useful rather than equally important.
