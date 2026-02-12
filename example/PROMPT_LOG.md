# PROMPT_LOG.md — Prompt Record

## Prompt 1

- **Phase:** Exploration
- **Prompt name:** Concept Map
- **What I sent:**

```
Create a concept map showing how these three design movements relate to each other:
1. Bauhaus (1919–1933)
2. International Typographic Style / Swiss Style (1950s–1970s)
3. New Wave Typography (1970s–1980s)

Show: key figures, core principles, what each movement inherited from or rejected about the previous one. Use plain text with indentation — no images.
```

- **What I got back (summary):**

A clean tree structure showing the three movements with inheritance arrows. It correctly identified the Bauhaus → Swiss pipeline and the Swiss → New Wave rebellion. It listed key figures accurately. One issue: it listed "Jan Tschichold" under Bauhaus, which is debatable — he was influenced by Bauhaus but wasn't faculty. I kept the structure but removed Tschichold from the Bauhaus section.

- **What I did with it:**

Pinned the concept map to CURATOR_NOTES.md. Used it to structure my thinking about the "inherited from / rejected" relationships for each card.

---

## Prompt 2

- **Phase:** Exploration
- **Prompt name:** Controlled Vocabulary
- **What I sent:**

```
Generate a controlled vocabulary list of 20 domain-specific terms used in design history when discussing Bauhaus, Swiss Style, and New Wave Typography.

For each term provide:
- The term
- A one-sentence definition (max 15 words)
- Which movement(s) it applies to

Only include terms a design professional would use. No vague words like "creative" or "innovative."
```

- **What I got back (summary):**

25 terms, mostly good. I cut 5 that were too vague ("design philosophy," "visual language," "artistic expression," "experimental," "avant-garde"). Kept 20 precise terms. Rewrote a few definitions that were too long. Promoted the final list to AGENTS.md.

- **What I did with it:**

Selected 20 terms → promoted to AGENTS.md controlled vocabulary table. This became the constraint set for all future prompts.

---

## Prompt 3

- **Phase:** Production
- **Prompt name:** Draft Labels (with AGENTS.md)
- **What I sent:**

```
Read my AGENTS.md (pasted below) and write 3 Curator Cards.

Each card must follow this exact schema:
- Title: Movement name and date range
- Body: 80–120 words, museum-label tone
- Tags: exactly 5 domain-specific vocabulary terms
- Examples: 2 real links to museum collections
- Confusion: "Not to be confused with ___ because ___."
- Accountability: "I verified this by checking [source]."

Use ONLY the vocabulary from my controlled vocabulary list.
If you are unsure about any fact, write VERIFY instead of guessing.

---
[Full AGENTS.md pasted here]
```

- **What I got back (summary):**

Three cards, all within word count. The Bauhaus card was strong. The Swiss Style card used "revolutionary" (banned word) — caught and replaced with "systematic." The New Wave card said Weingart "invented" deconstructed typography — too strong a claim, softened to "pioneered." Two VERIFY flags appeared, both on dates I then confirmed via MoMA records.

- **What I did with it:**

Edited all three cards. Ran the self-audit prompt to confirm constraints were met. Then moved to Expert Critique.

---

## Prompt 4

- **Phase:** Critique
- **Prompt name:** Expert Critique (Wolfgang Weingart)
- **What I sent:**

```
Review my Curator Card about New Wave Typography as if you were Wolfgang Weingart.

Using only Weingart's documented writings, teachings, and known positions:
1. What would he praise about this description?
2. What would he challenge or correct?
3. Is the vocabulary appropriate to how he discussed design?
4. What's missing that he would consider essential?

If you are unsure about a fact or attribution, write VERIFY instead of guessing.

---
[New Wave card pasted here]
```

- **What I got back (summary):**

The critique flagged that my card didn't mention Weingart's insistence that he was NOT rejecting Swiss design — he was extending it. He saw himself as working within the tradition, not against it. This was a genuine insight I hadn't considered. The critique also noted I should mention his teaching at Basel, since pedagogy was central to his influence. One claim about Greiman was flagged VERIFY — I checked and it was accurate.

- **What I did with it:**

Revised the New Wave card to include "from within the Swiss tradition" language. Added "Basel School of Design" as context. This made the card significantly more accurate.

---

## Prompt 5

- **Phase:** Production
- **Prompt name:** Rewrite 10% Shorter
- **What I sent:**

```
Rewrite each of these 3 Curator Cards to be 10% shorter without losing any factual content or domain vocabulary.

Rules:
- Cut filler words, not facts
- Keep all 5 tags, 2 links, confusion line, and accountability note
- Maintain museum-label tone
- Show the word count before and after for each card

---
[All 3 revised cards pasted here]
```

- **What I got back (summary):**

Bauhaus: 118 → 107 words (cut "under one pedagogical roof" → "under one roof"). Swiss: 112 → 101 words (tightened two compound sentences). New Wave: 115 → 105 words (removed a redundant clause about rebellion).

- **What I did with it:**

Accepted most cuts. Restored one phrase in the Bauhaus card ("pedagogical roof" → I liked the specificity). Final counts: 112, 101, 105. All within range.
