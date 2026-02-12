Letter to Coding Agent
To: Coding Agent
From: Keith (Instructional Designer / Course Lead)
Subject: Build “Design Curator Cards” assignment repo (theory + practice + examples) for first-year students
Objective
Create a single, polished template repo I can link in Canvas. The repo must make it obvious what students do, why it matters, and how to submit. Students are first-year, just learned Visual Studio Code + basic AI use.
This repo must teach:
How LLMs work (short mental model)
Why context + token discipline matters
How to learn a topic quickly (autodidactic loop)
Responsibility: AI is not an alibi
Design history content: Bauhaus → International Typographic Style → one reaction (New Wave or Grunge)
Non-negotiables
No build system. Keep it static HTML/CSS (beginner-proof).
Repo must include starter templates AND a complete example (A-level).
Repo must include copy/paste prompt pack and “explore → pin → promote” workflow.
Students must feel the role shift: human = curator (judgment, taste, responsibility), AI = assistant.
Repo Experience (what the student sees)
1) README.md = the assignment handout (single source)
Write it like a student-facing handout with these sections:
A) Why this matters (short, punchy)
Include these ideas:
LLMs are next-token predictors; they only “think” with what’s in the context window.
Tokens are budget; long/vague prompts cause drift and confusion.
AI moves humans up the value chain: from implementor → curator/editor/strategist.
In a job, you can’t say “AI told me.” You own what you ship.
B) Learning in Motion (autodidactic loop)
Teach a simple 5-step loop they can reuse:
Orient → Map → Vocabulary → Evidence → Synthesize
C) The Deliverable (tiny and doable)
Students build a one-page site with 3 Curator Cards:
Bauhaus
Swiss Style
Reaction to Swiss (choose: New Wave OR Grunge)
Each card must include:
80–120 words (museum label tone)
5 vocabulary tags (domain terms, not vibes)
2 real example links
1 sentence: “Not to be confused with ___ because ___.”
1 line: “Accountability Note: I verified this.”
D) Submission checklist + grading rubric
Keep it brutally scannable (checkboxes, A/B/C criteria).
2) docs/ = a beautiful landing page mirroring the README
Enable GitHub Pages from /docs. Make a clean landing page that:
summarizes the assignment
links to templates
shows the example output inline (so they can see what “good” looks like)
includes the prompt pack and the expert critique flow
Style: simple Swiss-grid inspired layout (but don’t overdo it).
Templates + Example (the core value)
Required repo structure
Implement exactly this structure:
/docs
  index.html
  style.css
  assets/ (optional)

/starter
  index.html
  style.css
  AGENTS.md
  CURATOR_NOTES.md
  PROMPT_LOG.md
  CLAIMS.md
  README_STUDENT.md (short submission instructions)

/example
  index.html
  style.css
  AGENTS.md
  CURATOR_NOTES.md
  PROMPT_LOG.md
  CLAIMS.md
  README_STUDENT.md
Notes
/starter is what students copy into their own repo.
/example is a complete “A-level” reference.
Keep the starter site extremely simple: three cards, clean typography, mobile friendly.
The “Explore → Pin → Promote” Workflow (must be taught + enforced)
CURATOR_NOTES.md (starter template)
Include headings and a few placeholder bullets:
What I think I know
What I’m unsure about
Vocabulary I need
Pinned concept map (from AI)
Pinned vocabulary list (from AI)
Confusions & boundaries (from AI)
This is “manage YOUR context.”
AGENTS.md (starter template)
Short (15–25 lines). Must include:
audience + tone
hard constraints (word count, tags, banned vague words)
controlled vocabulary (15–25 terms with one-line definitions)
verification rule (“If unsure: write VERIFY”)
This is “manage the LLM context.”
Prompt Pack (industry patterns, copy/paste)
Create a file: /docs/prompt-pack.html or a README section with these prompts students can copy.
Exploration prompts (intake)
Concept map
Controlled vocabulary
Confusions & boundaries
Search query builder
Micro-draft test label
Production prompts (write + refine)
Draft the three labels with schema
Self-audit against constraints
Rewrite 10% shorter (token discipline)
Named Expert Critique prompts (Renaissance “superpower”)
This is essential: students select ONE expert and run critique + implementation.
Provide a menu of experts:
Walter Gropius
Josef Müller-Brockmann
Armin Hofmann
Wolfgang Weingart
April Greiman
David Carson
Add a bright warning:
No fake quotes, no invented facts. Expert mode is a critique lens, not a history simulator.
Responsibility / Verification (make it real but lightweight)
CLAIMS.md template
Have students write:
Claim:
Source link(s):
Confidence: High/Medium/Low
Notes:
Require at least one claim per card.
Also require in README reflection:
“One AI claim I didn’t trust at first and how I verified it.”
Provide A-level example content (we need this filled in)
Include these real example links in the /example (and cite them clearly on the page)
Use credible museum sources where possible.
Put the URLs in the repo (not just citations). Here are solid candidates:
BAUHAUS (example links)
- https://www.moma.org/collection/works/189319
- https://www.moma.org/collection/artists/399

SWISS STYLE (example links)
- https://www.moma.org/collection/works/7233
- https://www.moma.org/collection/works/6775

NEW WAVE / REACTION (example links)
- https://www.cooperhewitt.org/design-topics/women-in-design/april-greiman/
- https://www.moma.org/collection/artists/2330
(You may add 1–2 more optional links, but keep the student requirement at 2 per card.)
Acceptance Criteria (how I will judge your repo)
✅ A first-year student landing on the repo must be able to answer in 60 seconds:
What am I building?
What files do I need?
What are the constraints?
What prompts do I run first?
What does “good” look like?
✅ Starter kit must be copy/paste usable:
student can copy /starter into a new repo and deploy to GitHub Pages quickly
✅ Example must be genuinely excellent:
labels are within word counts
uses real domain vocabulary (grid, hierarchy, negative space…)
includes “not to be confused with…”
includes accountability note
includes CLAIMS.md with verification
✅ Keep it DRY:
same CSS structure between starter and example
no unnecessary tooling
minimal friction
Implementation tips (make it “amazing”)
Add a “Start Here” box at the top of README + docs homepage.
Add a 10-line checklist students can follow.
Include one fully-written sample Curator Card in the README so they instantly see the target.
Keep pages visually calm: the design of the repo is part of the lesson.