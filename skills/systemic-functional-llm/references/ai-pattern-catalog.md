# AI Pattern Catalog

Twelve recurring AI-default patterns, with SFG diagnosis and corrective choice. Use this when a draft has the AI register but the specific pattern is unclear.

Each entry follows the same shape: **Surface → Diagnosis → Why the default fires → Correction**.

> **Warning — do not imitate the Correction examples as tonal templates**
>
> The short example sentences under each pattern's "Correction" heading are *minimal demonstrations of the principle*, not models of sentence length, rhythm, or tone to be copied. The corrections in this catalog are uniformly terse and declarative because they isolate a single fix; treating that surface as the target produces a different register — clipped, staccato, Hemingway-by-reflex — rather than escape from the AI default.
>
> Read the examples as *diagnostic aids*, not style guides. Apply the correction inside whatever sentence length and subordination structure your actual register permits. **Correction is not "write shorter" — it is "widen the variation deliberately."** A four-word minor clause alongside a twenty-five-word hypotactic sentence is what makes the textual metafunction active; a page of four-word clauses is just a new monotony.
>
> Note also that the corrective direction across this catalog (unpacking nominalizations, committed modality, mood variation, minor clauses) suits essays, blogs, and reader-facing prose. It can damage register in **academic papers, legal documents, technical specifications, and formal reports**, where nominalization, hedging, median modality, and heteroglossic balance are often genre requirements rather than AI defaults. Treat this catalog as a starting point, not an absolute rule — **select, modify, and extend its entries against your own Field/Tenor/Mode** to make it a personal guide.

---

## 1. Nominalization drift

**Surface**
> The implementation of the feature led to a significant improvement in user engagement metrics.

**Diagnosis**
Ideational grammatical metaphor. Three processes (*implement*, *improve*, *engage*) are realized as nouns. The clause's only finite verb is *led*, which carries no real event content.

**Why the default fires**
Nominalized prose looks "professional" in training data — academic and corporate registers nominalize heavily. The model imitates the surface.

**Correction**
> We implemented the feature, and engagement improved.

Rule of thumb: count finite verbs per clause. If most "events" sit inside noun phrases, unpack them.

---

## 2. Empty engagement markers

**Surface**
> It's important to note that careful consideration must be given to the trade-offs involved.

**Diagnosis**
Three layered engagement moves with no propositional content: *it's important to note* (engagement marker), *careful consideration must be given* (modulated obligation directed at no one), *the trade-offs involved* (vague reference).

**Why the default fires**
Hedged framing reduces apparent risk. The model has learned that adding stance markers signals thoughtfulness, regardless of whether the stance has a target.

**Correction**
Either state the trade-off directly:
> The trade-off: lower latency at the cost of memory.

Or, if the engagement marker is genuine, name the contrast:
> Engineers default to caching; this case argues against it because the data is small and volatile.

---

## 3. Median modality default

**Surface**
> This approach can sometimes be useful, and it may potentially help in certain situations.

**Diagnosis**
Three modality operators stacked at low-median value (*can*, *may*, *potentially*), plus two hedges of frequency (*sometimes*, *in certain situations*). Net commitment: zero.

**Why the default fires**
Low-modality language is safe — it cannot be falsified. The model is rewarded for not being wrong, so it under-commits.

**Correction**
Choose a value with intent:
- High commitment: *Use this approach for batch workloads.*
- Genuine uncertainty: *This might help if the dataset is sparse — I am not sure.*

If the answer is "it depends", make the dependency explicit, not the uncertainty.

---

## 4. Mood monotony

**Surface**
> The first step is X. The second step is Y. The third step is Z. The user should then do A. The system will respond with B.

**Diagnosis**
Five clauses, five declaratives, identical Subject-Finite-Predicator shape.

**Why the default fires**
Declarative is the unmarked mood for information delivery. The model never selects from the Mood system because the task feels purely informational.

**Correction**
Vary the speech function where the meaning supports it:
> First, X. Then Y, followed by Z. Now run A — does the system respond with B? If not, recheck the config.

Note the imperative (*run A*), the interrogative (*does the system respond*), and the minor clauses (*If not, recheck the config*). Each is a deliberate mood choice carrying its own work.

---

## 5. Topical-Theme tyranny

**Surface**
> The model processes the input. The model then generates an output. The model also handles errors. The model returns the result.

**Diagnosis**
Four sentences, all opening with the same topical Theme (*the model*). No textual Themes, no interpersonal Themes, no marked variation.

**Why the default fires**
Subject-first is the unmarked English Theme. The model never asks: *what do I want the reader to start from?*

**Correction**
> The model processes input and generates an output. If something goes wrong during generation, it is caught and surfaced as an error. Otherwise, the result is returned.

Notice the textual Theme (*if something goes wrong*), the conditional Theme structure, and the contrastive *otherwise*. Theme variation controls reader trajectory.

---

## 6. Graduation inflation

**Surface**
> This is an incredibly powerful, extremely useful, absolutely essential capability.

**Diagnosis**
Three force-up graduation operators in a single nominal group. Each intensifier amplifies a vague adjective.

**Why the default fires**
Intensifiers feel like commitment without requiring specificity. The model has learned that strong adjectives signal value.

**Correction**
Replace intensifier+vague-adjective with specific outcome:
> This capability lets us route 90% of queries without a model call.

Specificity is stronger than amplification. If you cannot specify, cut the intensifier and let the noun stand alone.

---

## 7. Clause-complex flatness

**Surface**
> The system has three components. The first component handles input. The second component handles processing. The third component handles output. Each component is independent.

**Diagnosis**
Five independent clauses, all parataxis (or stand-alone), all roughly the same length. No hypotaxis, no embedding, no rhythm variation.

**Why the default fires**
Short, equal sentences are "safe" — they read as clear. But uniform rhythm reads as monotone.

**Correction**
> The system has three components, each independent: an input handler, a processor, and an output stage. Although they share an interface, they can be swapped without coordination.

Hypotaxis (*although they share*), embedding (*each independent*), and a list inside the matrix clause break the rhythm without sacrificing clarity.

---

## 8. Tripartite parallelism

**Surface**
> This approach is faster, cheaper, and more reliable.
> The solution offers three benefits, addresses three challenges, and provides three guarantees.

**Diagnosis**
Three-item lists used as a textual reflex regardless of whether three items naturally exist. Often the third item is padded ("more reliable" when only "faster" and "cheaper" were measured).

**Why the default fires**
Tricolons are heavily represented in rhetorical training data (speeches, marketing). The model treats three as a default chunk size.

**Correction**
Match list length to what actually exists. Two items, or four, or one carefully chosen attribute. *"This approach is faster and cheaper — reliability is unchanged"* beats a fake third item.

---

## 9. Disclaimer-heavy openings

**Surface**
> As an AI, I should note that while I can offer some perspective, you may want to consult an expert. With that caveat in mind, here's what I think...

**Diagnosis**
Interpersonal scaffolding before any ideational content. Three engagement moves (self-identification, hedge, caveat) precede the actual response.

**Why the default fires**
Safety-tuned models prefix disclaimers as a hedge against overreach.

**Correction**
Move the substantive content to the front. If a caveat is genuinely needed, place it inline at the point where it bites:
> Use sparse indexes for write-heavy workloads. (For pathological skew, consult a DBA — sparse indexes can hide hot keys.)

---

## 10. Closing summary boilerplate

**Surface**
> In conclusion, we have explored several aspects of this topic. I hope this helps! Let me know if you have any further questions.

**Diagnosis**
A meta-textual closing that adds no ideational content. Pure interpersonal phatic — relationship maintenance without substance.

**Why the default fires**
Conversational AI training rewards friendly closings. The model adds them by reflex.

**Correction**
End on the last substantive sentence. If a closing is needed, make it carry meaning:
> If you change the schema, re-run the migration check before deploying.

The reader does not need to be told the response is over.

---

## 11. Cohesion via lexical repetition

**Surface**
> The model improves performance. The model reduces latency. The model handles errors better. The model is more efficient.

**Diagnosis**
Cohesion mechanism limited to lexical repetition (*the model*, *the model*, *the model*). Reference, substitution, and ellipsis are unused.

**Why the default fires**
Repetition is the simplest cohesion strategy. The model under-uses pronouns and ellipsis because they require tracking referents.

**Correction**
> The model improves performance — it reduces latency, handles errors better, and runs more efficiently overall.

Pronoun reference (*it*), ellipsis (the second and third clauses drop the subject), and conjunction tighten the texture.

---

## 12. False heteroglossic balance

**Surface**
> Some argue X. Others argue Y. There are valid points on both sides, and the answer likely depends on context.

**Diagnosis**
Engagement system used to project a balanced-debate frame without actually engaging with either position. *Some argue / others argue* is a heteroglossic move that disclaims authorial commitment.

**Why the default fires**
Safety training rewards epistemic neutrality. The model performs balance instead of analysis.

**Correction**
Either commit to a position with grounds, or surface the actual decision criterion:
> For real-time systems, X wins because of latency. For batch jobs, Y is simpler. The relevant question is the deployment context — not which is "better".

Balance for its own sake is non-analysis. The reader gets nothing.

---

## How to use this catalog

When a draft feels AI-written but the specific cause is unclear, scan these twelve patterns. The pattern that matches is the entry point. Apply the correction to that pattern; do not refactor the whole text at once. After one or two corrections the AI register usually dissipates because the patterns co-occur — fixing one pattern often pulls the others out by entailment.
