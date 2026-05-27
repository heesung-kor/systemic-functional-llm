# Grammatical Metaphor: Nominalization Patterns and Recovery

Grammatical metaphor (Halliday) is the realization of a meaning through a grammatical form that is not its congruent one. The most common case in English — and the largest single contributor to AI register — is **ideational metaphor**: realizing processes as nouns instead of verbs (nominalization).

This file is dedicated to nominalization because it is the deepest AI default. Eliminating it transforms more drafts than any other single intervention.

---

## 1. What nominalization is

A *congruent* realization aligns the grammatical category with the semantic category:
- Process → verb (*implement*, *decide*, *fail*)
- Participant → noun (*team*, *system*, *user*)
- Attribute → adjective (*fast*, *brittle*)

A *metaphoric* realization breaks the alignment. The most common move is process → noun:

| Congruent (verb) | Metaphoric (noun) |
|---|---|
| we implemented | the implementation |
| the team decided | the team's decision |
| it failed | the failure |
| we improved performance | the improvement of performance |

The metaphoric form is grammatically legal — but it changes what the clause can do.

---

## 2. What nominalization does

Nominalization has four systemic effects, all of which AI prose accumulates.

### 2.1 Hides the agent
*We implemented the feature* names an Actor. *The implementation of the feature* drops it. In academic and corporate registers, this hides accountability.

### 2.2 Compresses information
*The team decided that the migration would proceed despite the risk* (15 words) becomes *the team's decision to proceed with the migration despite the risk* (12 words). Compression is real — and so is the cost of unpacking it.

### 2.3 Abstracts the event
A verb tense locates an event in time: *implemented* (past), *implements* (present), *will implement* (future). A nominalized process loses tense entirely. *The implementation* could be any time. Abstraction.

### 2.4 Strips finite verbs
Nominalization removes finite verbs from clauses, replacing them with thin support verbs (*be*, *have*, *make*, *give*, *take*, *do*). A nominalization-heavy sentence has a real event-meaning in a noun phrase and a stand-in verb that does no work:

> *The implementation [event] of the feature led to [thin verb] an improvement [event] in performance.*

Two real events, hidden in nouns. The only finite verb is *led to*, which carries no event content.

---

## 3. The recovery technique

The repair is almost mechanical. For each nominalization:

1. **Identify the hidden process** (the noun that names an event).
2. **Restore it as a verb.**
3. **Restore the Actor** (or another participant) as the Subject of that verb.

Worked examples:

> *The deployment of the change resulted in a degradation of latency.*

Hidden processes: *deploy*, *change*, *degrade*. Hidden agent: who deployed?

> *We deployed the change, and latency degraded.*

---

> *The team's evaluation of the proposal indicated significant concerns.*

Hidden processes: *evaluate*, *concern*. Hidden agent: the team. Hidden Phenomenon: the proposal.

> *The team evaluated the proposal and raised significant concerns.*

---

> *There was a recognition by the leadership that the rollout required postponement.*

Three nominalizations: *recognition*, *rollout*, *postponement*. Plus an agentless passive.

> *Leadership recognized that we had to postpone the rollout.*

---

## 4. When nominalization is appropriate

Nominalization is not always wrong. It is appropriate when:

1. **The process is the topic of discourse.** *Implementation strategy* is fine as a topic — it is *being talked about*, not being narrated.
2. **The reader needs the noun for further reference.** Once you have introduced *the migration*, you can refer to it as such.
3. **The agent is genuinely unknown or irrelevant.** *The data was corrupted* is fine when the cause is unknown.
4. **You need to compress for genuine reasons.** Long lists, summary tables, captions.

The failure mode is not nominalization itself — it is reflexive nominalization where the verb form would be sharper.

---

## 5. Beyond nominalization: other ideational metaphors

Grammatical metaphor at the ideational level includes other moves:

- **Attribute → noun**: *the redness of the LED* (vs *the LED is red*)
- **Circumstance → noun**: *the location of the cache* (vs *where the cache is*)
- **Conjunction → noun**: *the reason for the failure* (vs *because it failed*)

All four follow the same pattern: a semantic category encoded in a non-congruent grammatical form. All four hide finite verbs, strip agency, and abstract events.

---

## 6. Interpersonal grammatical metaphor

Modality can also be realized metaphorically. The congruent form is a modal verb:

> *The migration must complete by Friday.*

The metaphoric form is a separate clause:

> *It is essential that the migration complete by Friday.*
> *I require that the migration complete by Friday.*

The metaphoric forms add layers of clause structure and disperse the modality across multiple words. Sometimes useful for emphasis; often pure verbosity. AI prose loves *it is important / essential / necessary / critical that...* — a metaphoric realization of a simple modal *must*.

**Correction**: collapse to the modal verb when the metaphoric layer adds nothing.

> *It is important that you restart the service.*
> → *Restart the service.*

---

## 7. Diagnostic test

Count the finite verbs in a paragraph. Count the nominalized event-nouns (the noun forms of verbs — *-tion*, *-ment*, *-ance*, *-ness*, gerunds standing in for events, etc.).

If event-nouns outnumber finite verbs, the paragraph is over-nominalized. Convert at least the most central events back to verbs and restore their agents.

This single intervention — finite verbs over event-nouns — does more to remove AI register than any other transformation.
