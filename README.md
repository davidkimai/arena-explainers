# arena-explainers

High-clarity learning companions for **ARENA** chapters.

This repo exists to turn dense technical material into the kinds of artifacts that help people **understand faster, remember longer, and discuss more deeply** before they ever touch the code.

It is designed for ARENA participants who want to move from:
- “I can follow the notebook if I go line by line”
- to “I can already see the core mechanism, the contrast, the analogy, and the mental model.”

## What this repo is for

**arena-explainers** is a dedicated GitHub Pages repo for chapter-by-chapter educational content built around the ARENA curriculum.

For each chapter, the goal is to create a compact set of learning assets that make the material feel:
- **more intuitive**,
- **more visual**,
- **more memorable**,
- and **more discussable**.

The repo is meant to help students reach **intuitive mastery before implementation**.

Not mastery in the sense of “I memorized the words.”

Mastery in the sense of:
- “I know what problem this idea solves.”
- “I know the simplest contrast case.”
- “I know the wrong intuition and the right one.”
- “I can explain it to another participant in plain language.”
- “I can enter the code already knowing what I’m looking for.”

---

## Core framing

If this repo becomes genuinely great, it should feel like:

> **the best place to get the idea before doing the exercises**

That means the attractor is not “more content.”

The attractor is:
- **clean mental models**,
- **intuitive contrasts**,
- **visual explanations**,
- **Anki-ready compression**,
- and **discussion-ready framing**.

This repo should help ARENA participants walk into a chapter already able to say:
- what the central paradigm is,
- why it matters,
- what it is often confused with,
- and what the code is trying to reveal.

---

## The most compelling attractors for this repo

If I wanted this to become the top intuitive explainer repo for ARENA, these are the strongest frames I’d want surfaced immediately in the README:

### 1. Learn the concept before the implementation
ARENA material is excellent, but often dense. Many participants benefit from seeing the **conceptual spine** first, then the formalism, then the code.

This repo exists to provide that spine.

### 2. Turn “I followed it” into “I actually get it”
A lot of technical study creates a fake sense of progress. You can reproduce notebook steps without having a durable mental model.

This repo is for converting:
- procedural familiarity
- into conceptual fluency.

### 3. Make the hidden structure visible
The hardest part of technical learning is often not the facts, but the **structure**:
- what’s central vs peripheral,
- which contrasts matter,
- what the canonical examples are,
- and which analogy makes the system click.

This repo tries to expose that structure directly.

### 4. Help students speak the ideas, not just run them
Great ARENA participants don’t just execute notebooks. They can:
- ask sharper questions,
- compare mechanisms,
- critique assumptions,
- and explain ideas to others.

These explainers are built to support that kind of discussion-level understanding.

### 5. Build chapter assets that compound
A good explainer page is useful once.
A great educational repo compounds because each chapter adds reusable patterns for future chapters.

Over time, this repo should become a library of:
- teaching primitives,
- intuitive contrasts,
- visual explanation patterns,
- and memory-friendly chapter summaries.

---

## What gets created for each chapter

Each chapter can include some or all of the following:

### 1. Visual explainers
Browser-friendly pages that translate a chapter into:
- intuitive mechanisms,
- diagrams,
- contrasts,
- tables,
- and synthesis summaries.

### 2. Anki decks or Anki-ready flashcard content
Built around:
- core definitions,
- high-yield distinctions,
- mechanism recall,
- common confusions,
- and “explain it in your own words” prompts.

### 3. Intuitive slides
Short, discussion-friendly slide decks for:
- cohort review,
- peer teaching,
- local study groups,
- or fast chapter recap before exercises.

### 4. Chapter framing notes
Short written guides that answer:
- What is the chapter really about?
- What should you notice first?
- What are the key contrasts?
- What makes this chapter hard?
- What should feel intuitive before you code?

### 5. Discussion scaffolds
Prompts and framing to help participants have better technical conversations, not just consume material passively.

---

## Educational design principles

This repo should use a few best-practice learning principles consistently.

### Contrast over isolated explanation
Complex concepts become intuitive faster when you show:
- what they are,
- what they are **not**,
- and which nearby concepts people confuse them with.

Examples:
- induction heads vs simpler attention patterns
- representation vs computation
- bigram prediction vs in-context learning
- “I can run the notebook” vs “I can predict what the notebook will reveal”

### Analogy, but only when it clarifies mechanism
We want analogies that act like scaffolding, not decoration.

Good analogies preserve causal structure.
Bad analogies only create vibes.

The goal is to make complex ideas feel graspable without flattening them into nonsense.

### Cognitive load reduction
Many learners get stuck not because the material is impossible, but because too many ideas are introduced at once.

So the repo should prefer:
- fewer ideas per section,
- tighter information hierarchy,
- visible “main thing vs detail” separation,
- and progressive disclosure.

### Retrieval over passive review
People remember what they are forced to reconstruct.

So chapter materials should encourage:
- recall,
- prediction,
- self-explanation,
- and comparison.

Not just rereading.

### Visual structure as pedagogy
The layout itself should teach.

That means:
- emphasizing central mechanisms,
- visually separating primary vs secondary ideas,
- using tables for comparisons,
- and making conceptual dependency visible.

### Pre-code intuition first
The strongest framing for this repo is:

> **understand the mechanism first, then verify it in code**

That ordering makes the exercises feel like discovery, not transcription.

---

## What “great” looks like

A great chapter explainer should let a participant answer these before opening the notebook:

- What is the main idea of this chapter?
- Why does it matter?
- What is the simplest version of the mechanism?
- What is the key contrast case?
- What are the most common wrong intuitions?
- What should I expect to see once I inspect the code or visualizations?
- What would I say if another student asked me for the two-minute explanation?

If a page does that, it is doing its job.

---

## Current focus

### Intro to Mechanistic Interpretability
A visual explainer built from lecture material, notes, and slide content to make the chapter’s core ideas feel concrete before coding.

Live page:
- https://davidkimai.github.io/arena-explainers/mech-interp-week4/

---

## Repo structure

```text
arena-explainers/
├── README.md
├── site/
│   ├── index.html
│   └── <chapter-slug>/
│       └── index.html
└── .github/
    └── workflows/
        └── pages.yml
```

- `site/index.html` is the landing page
- each chapter lives under `site/<chapter-slug>/index.html`
- GitHub Pages deploys the site via GitHub Actions

---

## Contribution pattern for new chapters

For each ARENA chapter, aim to produce:

1. **One high-clarity explainer page**
   - main idea
   - key mechanisms
   - contrast cases
   - intuitive analogies
   - visual diagrams

2. **One compressed memory layer**
   - Anki cards or flashcard-ready prompts
   - “must-know” distinctions
   - short retrieval questions

3. **One discussion layer**
   - prompts for peer explanation
   - likely confusions
   - questions worth debating

### Suggested workflow

1. Read the chapter materials
2. Identify the chapter’s conceptual spine
3. Extract the most important contrasts
4. Build the intuitive explanation first
5. Add visuals and memory aids
6. Only then compress into slides / cards / recap assets

---

## Editorial standard

This repo should optimize for:
- **clarity over completeness**,
- **structure over sprawl**,
- **intuition before formalism**,
- **discussion-readiness over passive summary**,
- and **visual learning over walls of text**.

If a page is accurate but still hard to internalize, it should be improved.
If a page is polished but not educationally useful, it should be rewritten.

The bar is:

> Can this help an ARENA participant intuitively master most of the chapter before touching the code?

That is the standard.

---

## Why this matters

ARENA is designed to help talented people build the skills, confidence, and community needed to contribute to technical AI safety.

This repo is a complement to that mission.

It tries to make the learning layer itself better:
- faster to grasp,
- easier to remember,
- easier to explain,
- and easier to carry into serious technical work.

If it succeeds, participants should not just complete chapters.
They should feel like they can **think with the ideas**.

---

## Future direction

Over time, this repo can become a chapter-by-chapter library of:
- intuitive AI safety explainers,
- chapter diagrams,
- concept-first slide decks,
- Anki decks,
- and reusable pedagogical patterns for technical learning.

The ambition is simple:

> Make ARENA concepts feel intuitive, visual, and discussable before the code ever starts.
