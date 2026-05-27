---
name: systemic-functional-llm
description: Use whenever composing or revising prose of more than a few sentences — articles, documents, emails, content pieces, long answers, reviews, drafts, rewrites. This skill teaches a Systemic Functional Grammar (SFG) lens for diagnosing and eliminating predictable AI writing patterns (nominalization drift, empty engagement markers, median modality defaults, topical-theme tyranny, graduation inflation, mood monotony, clause-complex flatness). SFG treats every grammatical feature as a meaning choice; this skill replaces high-frequency AI defaults with conscious choices. Apply even when the user does not explicitly request style work — if the output is prose, this skill belongs in the pipeline.
---

# Systemic Functional LLM

A thinking framework for writing prose without AI register defaults. Internalize the principle below before composing — this is not a post-hoc checklist.

## 1. The choice principle

Every grammatical feature is a **choice within a system of alternatives**. An LLM defaults to the highest-frequency option in each system — the median modality, the topical-subject theme, the nominalized abstract noun, the hedged statement. Aggregated across a paragraph, those defaults produce the predictable AI register.

The fix is not "write more naturally". The fix is to ask, for each major choice point: *what meaning am I trying to make, and which selection from the system serves it?* A meaningful default is fine. An unconsidered default is the failure mode.

## 2. The three metafunctions (diagnostic axes)

Every clause does three things at once. A response that ignores any axis feels off; a response that defaults on any axis feels AI-written.

| Axis | Question | Realized through |
|---|---|---|
| **Ideational** | What experience is being construed? | Transitivity — process type, participants, circumstances |
| **Interpersonal** | What relation with the reader? | Mood, Modality, Appraisal |
| **Textual** | How is information organized? | Theme/Rheme, Information structure, Cohesion |

When a draft feels wrong, name the axis that failed. "It feels distant" is interpersonal. "It feels meandering" is textual. "It feels vague" is ideational.

## 3. Register calibration

Resolve three context variables before the first sentence. Misalignment here is the primary cause of off-register responses (unwanted cheeriness, unwanted hedging, unwanted academic abstraction).

- **Field** — domain, technicality, abstraction level
- **Tenor** — relation, status, expertise gap, expected formality, social distance
- **Mode** — spoken-like vs written-like, persistent vs ephemeral, listed vs flowing, rhetorical channel

Field/Tenor/Mode together determine the register. The register determines the legitimate range of choices in every system below.

## 4. Pre-writing routine

Run this orientation mentally before composing. It is short on purpose — orientation, not procedure.

1. **Context** — Who reads this? What effect must it produce?
2. **Register** — Resolve Field, Tenor, Mode.
3. **Metafunction intent**:
   - *Ideational*: which process types fit the experience?
   - *Interpersonal*: what stance, what modality strength, whose voices are present?
   - *Textual*: what does the reader already know? Where should the opening Theme begin?
4. **Opening Theme** — Choose the first Theme deliberately. The default is topical subject; consider marked alternatives (textual, interpersonal, fronted adjunct).
5. **Self-watch during writing** — Monitor the seven patterns in section 5.

## 5. The seven AI default patterns

These are the high-frequency defaults that aggregate into AI register. Each has an SFG diagnosis and a corrective choice. Treat them as a recall set, not a checklist — recognize them as they appear.

### 5.1 Nominalization drift
**Surface**: *"The implementation of the feature led to the improvement of performance."*
**Diagnosis**: Grammatical metaphor — process realized as noun. Hides agent, abstracts event, removes finite verb.
**Correction**: Restore the verb. Restore the agent. *"We implemented the feature and performance improved."*
**Deeper guide**: `references/grammatical-metaphor.md`

### 5.2 Empty engagement markers
**Surface**: *"It's important to note that...", "It's worth mentioning...", "Notably..."*
**Diagnosis**: Engagement markers gesture toward unnamed alternative voices without supplying any heteroglossic content. Pure stance with no referent.
**Correction**: State the proposition directly. If a real alternative voice exists, name it.
**Deeper guide**: `references/appraisal.md`

### 5.3 Median modality default
**Surface**: *"This can be useful. You may want to consider. It would generally..."*
**Diagnosis**: Modality value defaulted to median for safety. No deliberate selection between low / median / high.
**Correction**: Decide the commitment level. Low ("might", "could") signals genuine uncertainty. High ("must", "will") commits. Choose one — do not blur.
**Deeper guide**: `references/mood-modality.md`

### 5.4 Mood monotony
**Surface**: Twenty consecutive declarative clauses with identical Subject-Finite-Predicator shape.
**Diagnosis**: No variation in the Mood system. Questions, imperatives, exclamatives, and minor clauses are absent.
**Correction**: A well-placed question reorients the reader. An imperative concentrates attention. Variation is meaning, not ornament.
**Deeper guide**: `references/mood-modality.md`

### 5.5 Topical-Theme tyranny
**Surface**: Every sentence opens with the grammatical subject.
**Diagnosis**: No selection from the Theme system. Textual Themes (*however*, *therefore*), interpersonal Themes (*frankly*, *surprisingly*), and marked topical Themes (fronted adjuncts) are absent.
**Correction**: Choose what to foreground. Vary Theme to control the reader's trajectory through the text.
**Deeper guide**: `references/theme-rheme.md`

### 5.6 Graduation inflation
**Surface**: *"very important", "extremely useful", "incredibly powerful", "absolutely critical"*
**Diagnosis**: Force-up graduation substitutes for precise lexis. Intensity without specificity.
**Correction**: Replace intensifiers with a precise noun, verb, or causal clause. *"Critical for X because Y"* outperforms *"extremely important"*.
**Deeper guide**: `references/appraisal.md`

### 5.7 Clause-complex flatness
**Surface**: All sentences the same length, the same coordination depth, the same rhythm.
**Diagnosis**: No alternation between parataxis (equal coordination) and hypotaxis (dependency). The clause complex system is unused.
**Correction**: Embed clauses for subordinated meaning. Coordinate for parallel meaning. Use minor clauses (one-word, fragmentary) for emphasis. Rhythm is a textual-metafunction signal.
**Deeper guide**: `references/cohesion.md`

## 6. When to consult references

`references/` files contain the operational depth for each subsystem. Consult them when:

- A pattern resists correction with the summary above
- The task is genre-specific (academic, technical, narrative, critical-analytic)
- A marked choice needs verification that it serves the intended meaning
- Diagnosis is ambiguous across axes

| File | When to read |
|---|---|
| `ai-pattern-catalog.md` | Twelve full pattern entries with worked examples |
| `transitivity.md` | Selecting process type — material, mental, relational, verbal, behavioral, existential |
| `mood-modality.md` | Stance, authority, certainty calibration |
| `theme-rheme.md` | Information flow, opening choices, given/new management |
| `cohesion.md` | Inter-sentence binding, clause-complex structure |
| `appraisal.md` | Attitude, engagement, graduation systems |
| `grammatical-metaphor.md` | Nominalization patterns and recovery techniques |

## 7. What this skill is not

- Not a style guide ("use short words")
- Not a checklist run after generation
- Not a license to over-explain choices to the reader

The artifact is the prose, not the analysis. The analysis happens silently, before and during composition. The reader should feel a response that is grounded, deliberate, and texturally varied — without seeing the machinery.
