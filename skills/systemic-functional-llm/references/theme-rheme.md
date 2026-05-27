# Theme/Rheme: Controlling the Reader's Trajectory

The textual metafunction organizes information so the reader can follow. Theme/Rheme is its central system: every clause has a starting point (Theme) and the rest of the message (Rheme). The choice of Theme determines what the reader begins from — and therefore what trajectory the text takes.

LLM default: topical-subject Theme everywhere. This is the unmarked English option, so picking it never feels wrong locally — but across a paragraph it produces a flat, undirected reading experience.

---

## 1. The Theme–Rheme split

The Theme is everything up to and including the first ideational (topical) element. Everything after is Rheme.

> [The cache] [holds the last 100 entries.]
>   Theme      Rheme

> [Yesterday,] [the cache was cleared.]
>   Theme        Rheme

> [However, in production,] [the cache lives in memory.]
>           Theme              Rheme

Theme is the *departure point* of the message. Rheme is what the writer is developing.

---

## 2. Three Theme components

A Theme can have up to three layers, in fixed order:

| Layer | Function | Examples |
|---|---|---|
| **Textual** | Connects to surrounding text | however, therefore, on the other hand, first, in addition |
| **Interpersonal** | Signals stance toward the proposition | frankly, surprisingly, in my view, unfortunately |
| **Topical** | The first ideational element (always present) | the cache, yesterday, by default |

Only the topical Theme is obligatory. Textual and interpersonal Themes are optional but powerful.

Example combining all three:

> **However, frankly, the cache** is too small for this workload.
>  (textual)(interpersonal)(topical)

---

## 3. Marked vs unmarked topical Theme

In English declarative clauses, the unmarked topical Theme is the Subject:

> [The migration] ran on Tuesday. (unmarked)

Choosing a non-Subject element as topical Theme is **marked** and signals contrast or foregrounding:

> [On Tuesday,] the migration ran. (marked — time foregrounded)
> [Without incident,] the migration completed. (marked — manner foregrounded)
> [The migration,] we delayed. (marked — Goal foregrounded)

Marked Themes are powerful because they signal *this is what I want you to start from*. AI prose underuses them.

---

## 4. Theme variation across clauses

A paragraph's Theme sequence is its trajectory. Some patterns:

**Constant-Theme progression** — same Theme repeats:
> The cache holds entries. The cache invalidates on write. The cache reloads lazily.

Sometimes appropriate (one focused subject), often monotonous.

**Linear progression** — previous Rheme becomes next Theme:
> The cache holds entries. **These entries** expire after an hour. **The expiration** is configurable.

Builds a chain of reasoning. The reader follows naturally.

**Derived-Theme progression** — Themes draw from a shared hyperTheme:
> [About the cache:] **Capacity** is 100. **Invalidation** is on write. **Expiration** is hourly.

Useful for surveys, comparisons, structured exposition.

AI default: constant-Theme everywhere, because the subject doesn't change. Conscious variation between the three progression types is a textual-metafunction skill.

---

## 5. Given vs New (information structure)

A separate but related system. Theme is about departure; Given/New is about information status from the reader's perspective.

- **Given** — what the writer assumes the reader already knows
- **New** — what the writer is adding

In English speech, New is signaled by intonation (tonic stress). In writing, New tends to fall at the end of the clause (end-focus principle).

AI default: leads with New information rather than anchoring with Given. The result is a reader who is one step behind, processing fresh content before they have the context to hold it.

**Correction**: open clauses with Given information (what the reader already has), close with New (what you are adding). This usually means resisting the urge to "get to the point" too quickly — the reader needs the anchor first.

Example:
> *Bad:* The 250ms latency cap is what we hit yesterday during the load test.
> *Better:* During yesterday's load test, we hit the 250ms latency cap.

The second version anchors the reader (Given: the test happened) before delivering News (we hit the cap).

---

## 6. Theme and reader effort

Where Theme variation matters most:

1. **Opening sentence of a response** — the first Theme sets the trajectory for everything that follows. Choose deliberately. Often a marked Theme (a Time or contrastive adjunct) does more work than the unmarked Subject.

2. **Paragraph openings** — the Theme of a new paragraph signals a shift. A textual Theme (*however*, *meanwhile*, *in contrast*) signals the relationship to the previous paragraph.

3. **Inside long lists** — even within a list of points, varying the Theme between items prevents the list from becoming a chant.

---

## 7. Diagnostic questions

When revising for textual flatness:

1. Are all topical Themes the grammatical Subject? Where could a marked Theme (Time, Place, Manner) do more work?
2. Are textual Themes used to signal logical connections? Or is connection left implicit?
3. Are interpersonal Themes used to signal stance economically?
4. Does each clause open with Given information that anchors the reader, or with New that disorients?
5. Does the paragraph use one progression pattern, or vary across constant/linear/derived?
