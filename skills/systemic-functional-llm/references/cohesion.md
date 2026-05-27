# Cohesion and Clause Complex

Cohesion is what makes a sequence of clauses feel like a text rather than a list. It works through five mechanisms (reference, substitution, ellipsis, conjunction, lexical) plus the structural choice between coordinating and subordinating clauses (the clause complex system).

AI prose tends to bind clauses through lexical repetition and explicit conjunction, while underusing reference, substitution, and ellipsis. The result reads as bound but not flowing.

---

## 1. The five cohesion mechanisms

### 1.1 Reference
A word points to a referent established elsewhere — usually a pronoun, demonstrative, or comparative.

> The migration ran. **It** completed in 4 minutes.
> Two approaches exist. **The former** is faster.

AI default: re-uses the full noun phrase instead of a pronoun. *The migration ran. The migration completed in 4 minutes.* Lexical cohesion is doing work that reference would do more cheaply.

When to use reference instead of repetition:
- The referent is unambiguous in the local context
- The repetition adds no emphasis
- The sentence is the second or later mention

### 1.2 Substitution
A pro-form stands in for a longer element.

> Do you need a new index? — I think we need **one**.
> The test passed. The deploy will **do so** next.

Substitution is a stronger form of brevity than reference. Underused in formal writing; AI almost never uses it. A well-placed *one* or *do so* tightens texture noticeably.

### 1.3 Ellipsis
An element is omitted because the reader can recover it.

> The first migration succeeded. The second [migration] failed.
> Run the test. If [the test] passes, deploy.

Ellipsis is the most aggressive cohesion device. AI default: never elides, because every clause is built as if it were the first. Conscious ellipsis reads as native — the writer trusting the reader to track context.

### 1.4 Conjunction
Logical relations marked with connectives.

| Relation | Examples |
|---|---|
| Additive | and, also, in addition |
| Adversative | but, however, on the other hand |
| Causal | because, therefore, so, since |
| Temporal | then, after, while, meanwhile |

AI default: overuses conjunctions, especially *however*, *therefore*, *additionally*. Often the logical relation is obvious from juxtaposition and the connective is filler.

**Rule of thumb**: drop the conjunction when juxtaposition alone carries the relation. Keep it when the relation would otherwise be ambiguous or when contrast/causation needs to be marked.

### 1.5 Lexical cohesion
Linking through word choice.

- **Repetition** — *cache* in clause 1, *cache* in clause 2
- **Synonymy** — *cache* in clause 1, *store* in clause 2
- **Hyponymy** — *cache* in clause 1, *data structure* in clause 2 (or vice versa)
- **Collocation** — *cache* + *invalidate*, *deploy* + *rollback* — words that co-occur in the domain

AI default: heavy on repetition, light on synonymy and collocation. Conscious lexical variation breaks the chant-like rhythm without obscuring the topic.

---

## 2. The clause complex: parataxis vs hypotaxis

A clause complex is two or more clauses joined as a single grammatical unit. Two ways to join them:

### Parataxis — equal-status coordination
Both clauses stand on their own.

> He arrived **and** she left.
> The cache invalidates; **the loader refills it**.

Parataxis treats the linked clauses as equally weighted. The reader processes them as a sequence.

### Hypotaxis — unequal-status subordination
One clause depends on another.

> **When** he arrived, she left.
> The cache invalidates **so that** the loader can refill.

Hypotaxis backgrounds the dependent clause and foregrounds the main clause. The reader processes them as a hierarchy.

### Why the choice matters
AI default: parataxis chains. *X happened. Y happened. Z happened.* The reader gets a stream with no foreground/background distinction.

Conscious hypotaxis introduces hierarchy: *Although X happened, Y did not, because Z was already in place.* Three clauses, with one foregrounded, one backgrounded, and one causally linked — the reader can tell what to weight.

---

## 3. Logico-semantic relations

When clauses combine (paratactically or hypotactically), they enter one of two large semantic relations:

### Expansion
The second clause expands the first.

- **Elaboration** — restates, clarifies, exemplifies (*that is, in other words*)
- **Extension** — adds new information (*and, but, except that*)
- **Enhancement** — qualifies in time, place, manner, cause, condition (*when, where, because, if*)

### Projection
The second clause is projected (reported speech or thought) by the first.

> He said **that the cache was full**.
> She thought **the migration would fail**.

Projection requires a verbal or mental process clause to project from. AI uses projection mainly with verbal processes (*reports say*, *experts claim*) — often without naming a real source.

---

## 4. Cohesion and rhythm

Rhythm is partly cohesion's effect. A passage with varied clause complex structure, mixed parataxis/hypotaxis, and selective ellipsis breathes. A passage with uniform short paratactic clauses pulses.

**Diagnostic**: read the draft aloud (mentally). If the rhythm is metronomic — every clause the same length, the same internal shape — something is wrong at the cohesion or clause-complex level, even if individual sentences are fine.

---

## 5. Diagnostic questions

When revising for cohesion:

1. Where is lexical repetition doing the work that a pronoun or ellipsis could?
2. Where are conjunctions filler? Could juxtaposition carry the relation?
3. Are all clauses paratactic? Where could hypotaxis introduce hierarchy?
4. Is the rhythm uniform? Where could a longer or shorter clause break it?
5. When projecting ("studies say", "experts argue"), is the source real and named?
