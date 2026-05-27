# LLM_SFG

A skill package that uses Systemic Functional Grammar (SFG) to strip predictable AI patterns — over-nominalization, hollow hedging, median-modality defaults, monotonous Themes — out of LLM responses.

## Background

The idea began in applied linguistics. SFG treats grammar not as a set of rules but as a *system of choices for making meaning*, and that lens, once you apply it to LLM output, turns out to diagnose the AI register with surprising precision. The recurring "AI feel" is not a stylistic mystery; it is the model defaulting to the highest-frequency option in every choice system at once.

## Layout

```
LLM_SFG/
├── README.md
└── skills/
    └── systemic-functional-llm/
        ├── SKILL.md                    # Core spine — choice principle, three metafunctions, pre-writing routine, seven AI patterns
        └── references/
            ├── ai-pattern-catalog.md   # Twelve AI patterns with diagnosis and correction
            ├── transitivity.md         # Process-type selection
            ├── mood-modality.md        # Stance and certainty calibration
            ├── theme-rheme.md          # Information structure and rhythm
            ├── cohesion.md             # Five cohesive devices and clause complex
            ├── appraisal.md            # Attitude / Engagement / Graduation
            └── grammatical-metaphor.md # Recovering from nominalization
```

## Usage

Copy `skills/systemic-functional-llm/` into Claude's skills directory. The skill then triggers whenever the model writes prose of more than a few sentences — articles, documents, emails, long answers, drafts, rewrites.

## Core principle

Language is **a system of choices for making meaning**. What we call the AI tone is the model collapsing every choice system to its most frequent default. This skill makes those defaults visible and trains the LLM to choose deliberately — to pick the option that serves the meaning, rather than the option that dominates the training distribution.
