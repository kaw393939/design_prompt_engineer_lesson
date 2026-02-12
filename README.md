# Design Curator Cards

> **You are building the workflow you'll use all semester.**
> This assignment is small on purpose — 3 cards, ~300 words total. The *process* is the point.

---

## Start Here

| Step | Action |
|------|--------|
| 1 | Read this entire README (10 min) |
| 2 | Copy the `/starter` folder into your own repo |
| 3 | Fill out `CURATOR_NOTES.md` (your thinking) |
| 4 | Write your `AGENTS.md` (instructions for the AI) |
| 5 | Run the exploration prompts from the [Prompt Pack](docs/prompt-pack.html) |
| 6 | Draft your 3 Curator Cards using production prompts |
| 7 | Run Named Expert Critique (pick one expert) |
| 8 | Fill out `CLAIMS.md` (verify at least one claim per card) |
| 9 | Deploy to GitHub Pages |
| 10 | Submit your repo link in Canvas |

---

## A) Why This Matters

Three ideas that will change how you work:

**LLMs are next-token predictors.** They don't "know" anything — they predict the most likely next word given the context window. Everything the AI produces depends on what you put in. Better input → better output. This is not a metaphor; it's the literal mechanism.

**Tokens are budget.** Every word you send costs tokens and occupies limited context. Long, vague prompts cause drift and hallucination. Short, precise prompts with controlled vocabulary keep the AI on target. This is a professional skill — token discipline is cost discipline.

**AI moves you up the value chain.** Without AI, you spend 80% of your time on syntax and layout. With AI, you spend 80% on judgment, strategy, and verification. Your job title shifts: from *implementor* to *curator/editor/strategist*. In a real job, you cannot say "the AI told me." You own what you ship.

> **This workflow — research → constrain → draft → verify — is the same workflow you'll use for every project this semester: the Design Museum, your Business Web Presence, and your Personal Portfolio. Learn it now on safe content.**

---

## B) Learning in Motion: The Autodidactic Loop

When you face a new domain (design history, business strategy, any topic), use this 5-step loop:

| Step | What You Do | What It Sounds Like |
|------|------------|-------------------|
| **Orient** | Skim broadly, identify the landscape | "What are the major movements?" |
| **Map** | Build a concept map — how do ideas relate? | "How does Bauhaus connect to Swiss Style?" |
| **Vocabulary** | Extract domain-specific terms | "What does *Vorkurs* mean? What's a *mathematical grid*?" |
| **Evidence** | Find primary sources — museums, archives, original works | "Show me an actual Bauhaus poster from MoMA" |
| **Synthesize** | Write it in your own words under constraints | "Explain this in 100 words using only domain terms" |

This loop is not specific to design. You will use it for Cialdini's persuasion principles, brand archetypes, and every unfamiliar domain you encounter professionally.

---

## C) The Deliverable

Build a **one-page static site** with **3 Curator Cards**:

| Card | Movement |
|------|----------|
| 1 | **Bauhaus** (1919–1933) |
| 2 | **Swiss Style** / International Typographic Style (1950s–1970s) |
| 3 | **Reaction to Swiss** — choose: New Wave Typography OR Grunge Typography |

### Each Card Must Include:

- **80–120 words** of museum-label-quality prose
- **5 vocabulary tags** (domain terms, not vibes — `grid`, not `cool`)
- **2 real example links** (museums, archives, or credited design collections)
- **1 "Not to be confused with" sentence:** *"Not to be confused with ___ because ___."*
- **1 Accountability Note:** *"I verified this by checking [source]."*

### What a Curator Card Looks Like

Here's a complete example so you can see the target:

> **Bauhaus (1919–1933)**
>
> The Bauhaus school, founded by Walter Gropius in Weimar, Germany, unified fine art, craft, and technology under one pedagogical roof. Its core principle — *form follows function* — demanded that every visual decision serve a purpose. Faculty including Moholy-Nagy, Kandinsky, and Klee developed a foundation curriculum (Vorkurs) emphasizing geometric abstraction, primary colors, and modular composition. The school's output — from typography to furniture to architecture — established the blueprint for modern design education. When the Nazis closed it in 1933, its diaspora seeded modernist thinking worldwide.
>
> **Tags:** `Vorkurs` · `geometric abstraction` · `form follows function` · `modular grid` · `sans-serif typography`
>
> **Examples:** [MoMA — Bauhaus Collection](https://www.moma.org/collection/works/189319) · [MoMA — Walter Gropius](https://www.moma.org/collection/artists/399)
>
> **Not to be confused with** Art Deco, because while both emerged in the early 20th century, Art Deco embraced ornamentation and luxury, while Bauhaus stripped design to functional essentials.
>
> **Accountability:** I verified the founding date and Vorkurs curriculum against MoMA's exhibition records.

---

## D) The Workflow Files

Your repo isn't just code — it's a thinking trail. These files are your professional documentation:

| File | Purpose | You'll Use This Again For |
|------|---------|--------------------------|
| `CURATOR_NOTES.md` | Your research thinking before prompting | Museum, Business Site, Portfolio |
| `AGENTS.md` | Instructions you give the AI | Every project this semester |
| `PROMPT_LOG.md` | Record of prompts you ran and what happened | Debugging, improving your process |
| `CLAIMS.md` | Verification log for factual claims | Team accountability in museum project |

---

## E) The "Explore → Pin → Promote" Workflow

This is how professionals work with AI — not one giant prompt, but a disciplined cycle:

1. **Explore** — Use open-ended prompts to survey the territory. Let the AI generate concept maps, vocabulary lists, timelines. Don't trust any of it yet.

2. **Pin** — Select the best outputs and paste them into `CURATOR_NOTES.md`. These become your reference. Discard the rest.

3. **Promote** — Move pinned content into your `AGENTS.md` as constraints and vocabulary. Now when you prompt for drafts, the AI works within *your* curated context.

The human decides what's good. The AI executes within those boundaries.

---

## F) Named Expert Critique

After drafting your cards, pick **one expert** and run a critique prompt:

| Expert | Known For | Best For Critiquing |
|--------|-----------|-------------------|
| Walter Gropius | Bauhaus founder, unity of art + technology | Card 1 (Bauhaus) |
| Josef Müller-Brockmann | Swiss grid systems, objective design | Card 2 (Swiss Style) |
| Armin Hofmann | Swiss typography, figure-ground | Card 2 (Swiss Style) |
| Wolfgang Weingart | Broke the Swiss grid, New Wave pioneer | Card 3 (Reaction) |
| April Greiman | Digital New Wave, hybrid media | Card 3 (Reaction) |
| David Carson | Grunge typography, anti-legibility | Card 3 (Reaction) |

**The prompt pattern:**

```
Review my Curator Card about [movement] as if you were [expert name].
Critique the accuracy, vocabulary, and tone.
Flag anything that expert would challenge.
If you are unsure about a fact, write VERIFY instead of guessing.
```

> ⚠️ **Warning:** Expert mode is a *critique lens*, not a history simulator. The AI is not channeling a dead person — it's using their documented perspective to stress-test your work. No fake quotes. No invented anecdotes. If the AI generates something you can't source, cut it.

---

## G) Submission Checklist

Before submitting, confirm every box:

- [ ] Site is live on GitHub Pages
- [ ] 3 Curator Cards with all required elements
- [ ] Word counts within 80–120 per card
- [ ] All vocabulary tags are real domain terms
- [ ] All example links work and point to real sources
- [ ] "Not to be confused with…" is factually accurate
- [ ] `CURATOR_NOTES.md` shows your research thinking
- [ ] `AGENTS.md` contains your AI instructions
- [ ] `PROMPT_LOG.md` has at least 3 logged prompts
- [ ] `CLAIMS.md` has at least 1 verified claim per card
- [ ] At least 5 meaningful git commits with descriptive messages
- [ ] `README_STUDENT.md` includes your reflection

---

## H) Grading Rubric

| Criterion | A (Excellent) | B (Solid) | C (Needs Work) |
|-----------|--------------|-----------|----------------|
| **Card Content** | 80–120 words, museum-label tone, precise vocabulary, zero unsourced claims | Minor word count variance, mostly accurate, vocabulary is functional | Vague language, missing tags, unsourced assertions |
| **Verification** | CLAIMS.md is thorough, links work, confidence levels are honest | Claims exist but sparse or surface-level | Missing or fake verification |
| **Workflow Docs** | CURATOR_NOTES shows genuine exploration; AGENTS.md is specific and reusable | Docs exist but feel perfunctory | Missing or copy-pasted without thought |
| **Expert Critique** | Ran critique, implemented feedback, documented changes | Ran critique but didn't act on it | Skipped or fabricated |
| **Code Quality** | Clean HTML/CSS, mobile-friendly, deployed, 5+ meaningful commits | Works but messy, few commits | Broken, not deployed, or single "final" commit |
| **Reflection** | Identifies a specific AI claim they challenged with evidence | Generic reflection ("AI was helpful") | Missing |

---

## Repo Structure

```
/docs
  index.html          ← Landing page (GitHub Pages)
  style.css
  prompt-pack.html     ← Copy/paste prompt pack

/starter               ← Copy this into your own repo
  index.html
  style.css
  AGENTS.md
  CURATOR_NOTES.md
  PROMPT_LOG.md
  CLAIMS.md
  README_STUDENT.md

/example               ← A-level reference (see what "good" looks like)
  index.html
  style.css
  AGENTS.md
  CURATOR_NOTES.md
  PROMPT_LOG.md
  CLAIMS.md
  README_STUDENT.md
```

---

## Looking Ahead

This is **Assignment 2 of 5**. Here's where you're headed:

| Project | What You'll Build | What Gets Harder |
|---------|------------------|-----------------|
| ~~1. Career Portfolio~~ | ~~Personal site~~ | ~~(Done)~~ |
| **2. Curator Cards** | **3 design history cards** | **Prompt discipline, verification** |
| 3. Design Museum | Team exhibit site (2–3 people) | Collaboration, git workflow, scale |
| 4. Business Web Presence | Client-facing site with CTAs | Persuasion strategy, automation |
| 5. Personal Portfolio | Your professional site | Full autonomy — you own everything |

The AGENTS.md, vocabulary lists, and verification habits you build here are the foundation for all of it.
