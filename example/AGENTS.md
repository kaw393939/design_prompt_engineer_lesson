# AGENTS.md — AI Instructions

> This is the master instruction file for generating Design Curator Cards.
> It constrains the AI to produce museum-label-quality output within strict boundaries.

## Audience & Tone

- **Audience:** Museum visitors with general interest in design history (not experts, not children)
- **Tone:** Authoritative, precise, museum wall label. Think MoMA exhibition text — confident without being academic, specific without being dense.
- **Reading level:** Educated adult. Define specialized terms through context, not parentheticals.

## Hard Constraints

- **Word count per card:** 80–120 words (strictly enforced)
- **Number of cards:** 3 (Bauhaus, Swiss Style, New Wave Typography)
- **Vocabulary tags per card:** exactly 5 domain-specific terms
- **Example links per card:** exactly 2 (real museum or credited archive URLs)
- **Required per card:**
  - "Not to be confused with ___ because ___."
  - "I verified this by checking [source]."

## Banned Words

Do not use:

- creative, innovative, revolutionary, iconic, visionary
- interesting, unique, beautiful, amazing, stunning
- game-changing, groundbreaking, cutting-edge, pioneering
- basically, essentially, literally, incredibly
- aesthetic (when used as an adjective meaning "nice-looking")

Replace with specific domain vocabulary from the controlled list below.

## Controlled Vocabulary

| Term | Definition |
|------|-----------|
| Vorkurs | Bauhaus foundation course teaching materials, form, and color theory |
| form follows function | Design principle that visual form should be determined by practical purpose |
| geometric abstraction | Use of geometric shapes as the primary visual language |
| modular grid | Repeating spatial framework for organizing visual elements |
| sans-serif typography | Letterforms without decorative strokes (serifs) at stroke endpoints |
| mathematical grid | Precisely calculated column-and-row system for page layout |
| Helvetica | Swiss typeface (1957) designed for maximum neutrality and legibility |
| asymmetric layout | Page composition not mirrored on a central axis |
| objective photography | Photography prioritizing documentary clarity over artistic expression |
| visual hierarchy | Arrangement of elements to guide the viewer's eye by importance |
| figure-ground | Relationship between subject (figure) and background (ground) in composition |
| negative space | Intentionally empty areas that define and emphasize content |
| deconstructed grid | Grid system intentionally broken or fragmented for expressive effect |
| layered typography | Overlapping or stacked type creating depth and visual complexity |
| bitmap imagery | Digital images composed of pixel grids, characteristic of early computing |
| post-modernism | Movement questioning modernist claims to universal truth and objectivity |
| Akzidenz-Grotesk | Early sans-serif typeface (1896) that influenced Helvetica |
| chromatic contrast | Use of color relationships to create visual tension or emphasis |
| compositional tension | Dynamic relationship between elements that creates visual energy |
| typographic hierarchy | Organization of text by size, weight, and position to signal importance |

## Verification Rule

If unsure about any fact, date, attribution, or claim: write **VERIFY** instead of guessing.

Do not invent quotes. Do not fabricate anecdotes. Do not attribute ideas to historical figures without sourced evidence.
