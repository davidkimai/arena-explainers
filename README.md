# arena-explainers

Concept-first visual explainers for ARENA chapters.

This repo is the public-facing student version. It keeps the focus on the actual learning artifacts: chapter pages you can open, study, and share.

## What this repo is for

ARENA notebooks are strong. They can still feel dense on first contact.

This repo is for the layer that comes before implementation:
- the main idea
- the key mechanism
- the contrast case
- the wrong intuition
- the mental model worth carrying into the exercises

The goal is simple:

> understand the chapter before you start tracing code line by line

## Current explainers

- **Intro to Mechanistic Interpretability**  
  Local: `site/mech-interp/index.html`  
  Live: https://davidkimai.github.io/arena-explainers/mech-interp/

- **CNNs & ResNets**  
  Local: `site/cnns-resnets/index.html`  
  Live: https://davidkimai.github.io/arena-explainers/cnns-resnets/

- **Linear Probes**  
  Local: `site/linear-probes/index.html`  
  Live: https://davidkimai.github.io/arena-explainers/linear-probes/

- **Landing page**  
  Live: https://davidkimai.github.io/arena-explainers/

## Design standard

Each explainer should help a student answer these before opening the notebook:
- What is the chapter really about?
- What is the simplest version of the mechanism?
- What contrast actually makes it click?
- What should I expect to see once I inspect the code or plots?
- What would I say if another student asked for the two-minute explanation?

The repo optimizes for:
- clarity over sprawl
- intuition before implementation
- visual structure over walls of text
- discussion-ready understanding over passive summary

## Repo structure

```text
arena-explainers/
├── README.md
└── site/
    ├── index.html
    ├── mech-interp/
    │   └── index.html
    ├── cnns-resnets/
    │   └── index.html
    └── linear-probes/
        └── index.html
```

## How to use it

1. Pick the chapter page.
2. Read the mechanism first.
3. Use the diagrams and contrast cases to build the mental model.
4. Then open the ARENA notebook and verify the story in code.

## For students

These pages are meant to be lightweight companions, not replacements for ARENA.

Use them to:
- get oriented quickly
- review before exercises
- recap after finishing a notebook
- explain the chapter to someone else

If a page helps you predict what the notebook is about to show you, it is doing its job.
