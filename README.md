# Foresight Strategy 2026 — Advanced Strategies Workspace

## Purpose

This workspace supports the University of Houston **Advanced Strategies: Translating Foresight into Action (HDCS 6331), Fall 2026** course and the Team 4 strategy project.

The goal is to preserve source material, keep Team 4 work traceable to evidence, and maintain a lightweight working knowledge base that can later support search, analysis, visualization, and AI-assisted querying.

## Course context

Instructor: Andy Hines  
Course: Advanced Strategies / HDCS 6331  
Semester: Fall 2026  
Team: Team 4  
Applied project: strategy development for the City of Boomtown around innovation in public services.

The course is organized in four modules:

1. **Preparing — Where are we now?**
2. **Visioning — Where do we want to go?**
3. **Strategizing — How might we get there?**
4. **Creating the Future — Making it happen**

### Current course position

As of **October 1, 2026**, the course is in **Week 6: Implications**, the first week of the Strategizing module.

The Fall 2026 schedule shows:

- Week 5, Sept. 24: Visioning Approaches; Strategy Schools include Entrepreneurial, Cognitive, and Learning; team assignment: Preferred Future.
- Week 6, Oct. 1: Implications; discussion submission: Strategic Thinking Self-Assessment; team assignment: Implications.
- Week 10, Oct. 29: Strategy Books; **Your Strategy School** is due then.

The Learning School is course content now, but the separately graded **Your Strategy School** assignment is not due until Week 10 unless Canvas contains a newer instruction.

## Storage architecture

### Google Drive = source of truth for original files

Drive contains or will contain the full course archive and Team 4 source material, including PDFs, PPTX, DOCX, and XLSX files.

Drive root:

`/Advanced Strategies 2026/`

Current structure:

- `Course Archive/`
  - `Assignments/`
  - `Discussions/`
  - `Presentations/`
  - `Readings/`
  - `course_image/`
  - `externalFiles_20230403080240/...`
- `Team 4/`
  - `Assignments/Final Submissions/`
  - `Assignments/Templates & Drafts/...`
  - `Class Slide Decks/`
  - `Initial Foresight Report/`
  - `Project Research/`
  - `Working Data/`
- `Indexes/`

Migration is still in progress. The course archive structure exists in Drive and a first batch of course files has been uploaded. The Team 4 working-data workbook is also in Drive. Do not assume every source binary has already been migrated until the migration checklist is complete.

### GitHub = lightweight longitudinal working record

Repository:

`sss2808/foresight-strategy-2026`

GitHub URL:

`https://github.com/sss2808/foresight-strategy-2026`

The repository exists and is currently **public**. Keep it limited to non-sensitive, lightweight working material. Do not commit copyrighted course binaries, private notes, or large source files simply because they exist in Drive.

Use GitHub for:

- `README.md` — this orientation document
- `HANDOFF.md` — compact cross-chat handoff
- `course/` — syllabus/schedule notes, assignment map, weekly status
- `team4/` — structured Team 4 summaries, current-state model, preferred future, implications, strategy development
- `data/` — small structured CSV/JSON extracts suitable for analysis
- `indexes/` — source manifests and Drive-path indexes
- `analysis/` — Python notebooks/scripts for search, graphs, STEEP analysis, etc.
- `checkpoints/` — dated project-state snapshots
- `ideas/` — parked product/research ideas

Large originals stay in Drive and should be represented in GitHub by metadata, notes, hashes, and Drive paths or links where appropriate.

## Source archive status

### Course archive

The reconstructed course archive contains about **148 files**. Major groups include:

- 29 assignment files
- 3 discussion files
- 38 presentation files
- 66 reading files
- Fall 2024 and Fall 2026 syllabus/schedule files
- supporting course images and Canvas-export material

The source came from eight split ZIP archives. All eight parts are available, including Part 06.

Important handling rule: **preserve original files unchanged**. Exact duplicates have been identified, but nothing should be deleted until hashes and provenance are intentionally reviewed.

Known exact duplicate examples include:

- `Assignments/W14 Case for Change template(1).pptx` and `Assignments/W14 Case for Change template.pptx`
- duplicated Pero Micic vision PDF in Discussions and Canvas externalFiles
- duplicated Maurer change white paper
- duplicated Seattle Libraries scan spreadsheets

Duplicates account for only a small fraction of archive size. Most archive bulk comes from large images embedded in PowerPoint decks.

### Team 4 archive

The Team 4 source archive was split into **13 independent ZIP files**, plus a manifest and README. The manifest identifies **37 project files** distributed across:

- final submissions through Week 5
- assignment templates and drafts
- class slide decks
- initial foresight report
- Fort Worth/Boomtown research material
- scanning library

The Team 4 archive is available in the ChatGPT Library and is being migrated to Drive in its original folder structure.

## Team 4 project state

Team 4 has substantially completed the first two course phases.

### Preparing

Completed or substantially developed:

- reframed domain and focal question
- Pilot's Checklist
- current-state business model
- environmental scanning
- drivers and current assessment
- extensive Fort Worth planning, budget, infrastructure, and public-engagement research

### Visioning

Completed or substantially developed:

- evaluation of inherited vision
- revised vision language
- Preferred Future submitted Oct. 1
- emerging preferred-future concept referred to as **Boomtown Trust**

The preferred future combines themes such as:

- AI and automation as civic infrastructure
- networked government and cross-sector delivery
- public-private partnerships with accountability
- participatory governance
- resilient and adaptive infrastructure
- changing workforce and demographic needs
- quality of life and quality of place
- long-term public investment mechanisms

### Strategizing

This is the current phase.

The main unresolved question has shifted from **what future do we want?** to **how might Boomtown get there?**

Near-term work should emphasize implications, options, strategic pathways, wind tunneling, and eventually goals/initiatives rather than continuing to add unrelated future ideas.

## Structured Team 4 data

A structured workbook has been created from the Team 4 Miro current-state business model:

`/Advanced Strategies 2026/Team 4/Working Data/Team4_Current_State_Business_Model_Enriched.xlsx`

It converts Miro sticky-note material into atomic rows and includes structured views for:

- canvas items
- partners
- resources
- value propositions
- customer segments
- relationships and channels
- finance
- current-state assessment
- key activities
- evidence register
- gap register

The workbook also separates:

- current-state facts
- opportunities
- aspirational/future ideas
- evidence-backed versus unverified claims

The next enrichment pass was intended to focus on **Customer Relationships + Channels, Key Partners, and Value Propositions**, but this work is paused while current course assignments take priority.

## Evidence rules

When analyzing Team 4 material:

1. Do not silently convert aspirational ideas into current-state facts.
2. Preserve the difference between Team 4 language and externally verified evidence.
3. Cite the underlying Fort Worth/Boomtown source where possible.
4. Keep old versions when they show project evolution unless an exact duplicate is intentionally deduplicated.
5. Treat Drive originals as authoritative binary sources.
6. Use GitHub for summaries, structured data, scripts, indexes, and project history.
7. Do not overwrite prior-week reasoning just because a later version exists. Preserve longitudinal development.

## Parked ideas / future product backlog

These are promising ideas, but they are **not the current assignment priority**.

### Searchable hit library

Build a searchable source/hit library hosted somewhere lightweight such as PythonAnywhere, conceptually similar to Kerko or another faceted bibliographic/search interface.

Possible functions:

- full-text or metadata search
- filters by STEEP category, week, source type, driver, implication, confidence, and project stage
- source previews and citations
- links back to Drive originals
- export to CSV/JSON

### GPT / retrieval layer over the project corpus

Create a query interface over structured Team 4 and course material so users can ask questions such as:

- What evidence supports this strategic option?
- Which drivers connect to this implication?
- Which Team 4 claims are still unverified?
- What changed between Week 2 and Week 6?

### Domain visualization

Create interactive visualizations of the domain and strategy system, potentially including:

- nodes and edges among drivers, actors, services, implications, options, and initiatives
- filters by STEEP category or evidence status
- current state versus preferred future
- influence/dependency views

### STEEP radar views

Create STEEP radar or comparable multivariate views to summarize balance, concentration, gaps, or evidence coverage across Social, Technological, Economic, Environmental, and Political dimensions.

### MiroFish / simulation experiments

Explore whether MiroFish or a similar agent/simulation framework can use the Boomtown domain, stakeholders, preferred future, and strategic options to test reactions or explore scenario dynamics.

These are exploratory ideas, not validated deliverables. Keep them parked until coursework priorities are handled.

## Current migration status

Completed so far:

- Drive workspace and major folder structure created.
- First course-archive batch uploaded, including the Fall 2026 schedule and syllabus, assignment templates, discussion files, and supporting files.
- Team 4 enriched current-state workbook uploaded to `Team 4/Working Data/`.
- GitHub repository `sss2808/foresight-strategy-2026` created.
- GitHub handoff structure initialized.

Still to do:

1. Finish migrating the remaining course archive binaries into Drive.
2. Finish migrating the Team 4 archive into Drive while preserving original paths.
3. Build a compact source manifest/index that maps Drive files to project roles.
4. Add small structured extracts to GitHub only when they are useful for analysis.
5. Keep GitHub synchronized with major project-state changes.
6. Return to current coursework before building apps or visualizations.

## Handoff instructions for another GPT

When taking over this project:

- Read this README first.
- Read `HANDOFF.md` second.
- Treat Google Drive as the primary source repository for original files.
- Treat `sss2808/foresight-strategy-2026` as the shared lightweight working record.
- Check whether migration is complete before assuming a missing file does not exist.
- Read the Fall 2026 schedule and syllabus before interpreting due dates.
- Use the Team 4 final submissions and enriched workbook to understand project evolution.
- Preserve provenance and version history.
- Do not delete duplicate or old files without explicit approval.
- Do not confuse future/product ideas with coursework deliverables.
- Current priority is the course assignment due today; infrastructure ideas are parked.

## Writing preferences

For deliverables:

- use short, direct sentences
- use active voice
- avoid em dashes
- avoid corporate or marketing language
- avoid unnecessary adjectives
- avoid jargon where ordinary language works
- keep one item per table cell when possible
- preserve the user's language unless accuracy or clarity requires a change

## AI disclosure

The course syllabus permits AI use but requires disclosure of the tool, date, and estimated Human/AI contribution. Any assignment drafted with AI should preserve enough process history to make that disclosure accurately.