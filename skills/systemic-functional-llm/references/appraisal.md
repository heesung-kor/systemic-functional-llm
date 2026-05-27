# Appraisal: Attitude, Engagement, Graduation

Appraisal is the extended interpersonal system that handles evaluation — emotion, judgment, valuation, source-attribution, and intensity. Developed by Martin and White as an extension of SFG.

AI prose tends to evaluate too much (every adjective is positive, every output is "great") and too vaguely (intensifiers replace specific lexis, alternative voices are gestured at without being named). Appraisal gives a vocabulary for diagnosing and correcting both.

---

## 1. Three subsystems

| Subsystem | What it handles |
|---|---|
| **Attitude** | Expressing emotion, ethical judgment, or aesthetic valuation |
| **Engagement** | Positioning the proposition relative to other voices |
| **Graduation** | Adjusting force or focus of evaluations |

---

## 2. Attitude

Three categories of evaluation.

### 2.1 Affect — emotion
Direct expression of feeling.

> The team **was relieved** when the deploy completed.
> Users **loved** the new feature.

AI default: floods responses with positive affect (*excited*, *thrilled*, *happy to help*) regardless of context. Affect is fine when it has a real target and a fitting register; performative affect feels off.

### 2.2 Judgment — ethical/behavioral evaluation of people
Assessing behavior as good or bad, normal or abnormal, capable or incapable.

> The engineer **handled the incident calmly**. (positive judgment of capacity)
> The vendor **missed the deadline again**. (negative judgment of tenacity)

AI default: avoids negative judgment, defaulting to flattening euphemisms. Sometimes the honest evaluation is the useful one.

### 2.3 Appreciation — aesthetic/functional evaluation of things
Assessing artifacts, processes, ideas.

> The architecture is **elegant**.
> The codebase is **brittle**.

AI default: uses appreciation that is consistently positive and vague (*excellent*, *great*, *wonderful*). Conscious appreciation is specific and bidirectional — willing to call something elegant, willing to call it brittle.

---

## 3. Engagement

How the writer positions the proposition relative to alternative voices. Two large modes.

### 3.1 Monoglossic
The writer asserts the proposition without acknowledging alternatives.

> The cache holds 100 entries.

This is the baseline. Direct, committed, no other voices in play.

### 3.2 Heteroglossic
The writer acknowledges other voices, and either aligns with them, distances from them, or opens space for them.

| Move | Example | Effect |
|---|---|---|
| **Acknowledge** | According to Halliday... | Names a source without taking a position on it |
| **Distance** | Halliday claims that... | Acknowledges a source while marking distance |
| **Endorse** | As Halliday demonstrates... | Aligns with the source |
| **Concur** | Of course, the cache fills up. | Frames as shared assumption |
| **Counter** | The cache, however, is not the bottleneck. | Pushes back against an implied alternative |
| **Entertain** | The cache might be the bottleneck. | Opens a possibility without commitment |

AI default: pseudo-heteroglossic moves with no named source. *Some say...*, *It is often argued...*, *Studies have shown...* — these gesture at alternative voices without supplying them. The result reads as scholarly hedging that turns out to be empty.

**Correction**: either name the voice, or drop the engagement and assert monoglossically. *Halliday calls this grammatical metaphor* beats *Some call this grammatical metaphor*. Direct assertion beats fake heteroglossia.

---

## 4. Graduation

Adjusting the force or focus of an evaluation.

### 4.1 Force — intensity
Up or down.

| Direction | Examples |
|---|---|
| Up | very, extremely, incredibly, deeply |
| Down | slightly, somewhat, a bit |

AI default: force-up on positive evaluations (*extremely useful*, *incredibly powerful*) and force-down on negative ones (*slightly suboptimal*, *somewhat limited*). The asymmetry creates a falsely cheerful tone.

### 4.2 Focus — sharpness
Sharpening or softening a category boundary.

| Direction | Examples |
|---|---|
| Sharpen | a true expert, a real problem |
| Soften | a kind of expert, sort of a problem |

AI default: heavy on soft focus (*kind of*, *sort of*, *somewhat*), which weakens claims without acknowledging that the writer is weakening them.

### 4.3 The replacement principle

The most common AI graduation pattern: an intensifier substitutes for specific lexis.

> *extremely important* → important for what, and why?
> *incredibly powerful* → powerful in what way, doing what?
> *very fast* → fast compared to what, how much faster?

When you find an intensifier+vague-adjective pair, the fix is rarely a stronger intensifier or a different adjective. The fix is to replace the pair with the specific information the intensifier was hiding.

---

## 5. Appraisal patterns to watch for

1. **Positive flood** — every evaluation is positive. Real assessments include negative evaluations where they fit.
2. **Empty heteroglossia** — *some say*, *experts argue*, *it has been suggested* with no named source.
3. **Intensifier as substitute** — *very*, *extremely*, *incredibly* doing the work of specific lexis.
4. **Asymmetric graduation** — force-up on positives, force-down on negatives. Reads as flattery.
5. **Affect at performative register** — *I'm excited to help*, *happy to assist* when the task doesn't warrant the affect.

---

## 6. Diagnostic questions

1. Is every evaluation positive? Where would a negative or neutral evaluation be more accurate?
2. Are alternative voices named, or gestured at?
3. Where does an intensifier substitute for specific information that could be supplied directly?
4. Is the graduation symmetric (same force on positive and negative claims)?
5. Is the affect proportionate to the situation, or performed?
