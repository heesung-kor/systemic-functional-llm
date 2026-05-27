# Mood and Modality: Calibrating Stance

Mood and modality are the interpersonal resources that position the speaker relative to the listener and to the proposition. AI defaults to declarative mood and median modality everywhere, which produces a flat, hedged, authority-free voice.

---

## 1. Mood structure

Every English finite clause has two functional components:

| Component | Role |
|---|---|
| **Mood** | Subject + Finite — the part that carries interactivity |
| **Residue** | The rest (Predicator, Complement, Adjuncts) |

The Mood block is where the clause's interpersonal work happens. The order of Subject and Finite determines speech function.

---

## 2. Speech functions (the four basic moves)

| Function | Direction | Realized as |
|---|---|---|
| **Statement** | Give information | Declarative (Subject before Finite) |
| **Question** | Demand information | Interrogative (Finite before Subject, or wh-) |
| **Command** | Demand action | Imperative (no Subject, or "you" Subject) |
| **Offer** | Give goods/services | Modulated declarative or interrogative (*shall I, would you like*) |

AI default: nearly all clauses are statements. The other three functions are nearly absent.

Each function does work the others cannot:
- A **question** transfers the cognitive load to the reader at a chosen point.
- A **command** concentrates attention and signals authority.
- An **offer** invites collaboration without surrendering agency.

Use them where they belong. A response with one well-placed question often reads as more confident, not less, because it signals the writer knows what the reader needs to think about.

---

## 3. Minor and elliptical clauses

Not every utterance is a full clause. Minor clauses (no Subject + Finite) and ellipsis carry meaning by omission:

> *Done.*
> *Not yet.*
> *If so, restart the service.*

AI default: every sentence is a full independent clause. Adding minor clauses where the meaning supports them breaks the monotony of the declarative chain.

---

## 4. Modality: probability and obligation

Modality is the system of intermediate values between yes and no. Two main types:

### Modalization — probability and frequency
The likelihood or commonness of a proposition.

| Value | Probability | Frequency |
|---|---|---|
| Low | might, could, may | sometimes, occasionally |
| Median | will, would, probably | usually, often |
| High | must, certainly | always, invariably |

### Modulation — obligation and inclination
The pressure for action.

| Value | Obligation | Inclination |
|---|---|---|
| Low | may, allowed to | willing to |
| Median | should, supposed to | want to |
| High | must, required to | determined to |

---

## 5. The median trap

AI prose defaults to median modality across the board:
> *This can be useful. You should probably try. It will generally work.*

The result is a voice with no commitment direction. Every claim is hedged the same amount.

**Correction**: pick one of these strategies per claim, not all three:

1. **Commit high** when the claim is well-supported: *This is correct. Use it.*
2. **Mark genuine uncertainty low**: *I am not sure — this might be specific to the test setup.*
3. **State directly without modality** when the proposition is presented as fact: *The cache lives in memory.*

The model should be willing to commit and willing to admit uncertainty. The failure mode is the bland middle.

---

## 6. Modality as voice projection

Modality also signals whose voice is in play:

> *Some studies suggest...* (low engagement, weak attribution)
> *Halliday argues that...* (named attribution)
> *This means...* (direct authorial commitment)

A response that defaults to *some say / it has been argued* shifts authority off the writer. Sometimes appropriate (genuine plurality); often a hedge against committing.

---

## 7. Polarity

The Finite carries polarity (positive or negative). Negation has its own pragmatics:

> *The cache is not invalidated.* (denies an expectation)
> *The cache stays valid.* (positive — different presupposition)

AI default: prefers negation because it sounds careful. Sometimes the positive version is sharper.

---

## 8. Diagnostic questions

When revising for interpersonal flatness:

1. Are all clauses statements? If yes, where would a question or imperative do more work?
2. What is the modality value of each commitment? Is it the same throughout?
3. Whose voice is projected at each turn — the writer's, or an unnamed "some say"?
4. Where is the polarity negative when it could be positive?

Variation across these four is the difference between a response that has a voice and one that recites.
