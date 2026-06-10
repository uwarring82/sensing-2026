# The Stele Blueprint

**Building artefacts that do not know their finder — a transferable pattern**

`Handbook · v0.1 · 2026-06-10 · CC BY 4.0 · Local Stewardship: U. Warring, Freiburg`

> **Identity card.** This is a construction pattern for teaching companions and other
> documents that must remain legible to readers who share none of their maker's context.
> It was extracted from one worked example — *Sensing 2026*
> (https://uwarring82.github.io/sensing-2026/) — and from the companion essay
> *The Stone That Did Not Know Its Finder* (T(h)reehouse +EC). It is a Handbook: an
> interface for builders, under local stewardship, offered as one route among many. It
> claims no authority in learning science and is not a compliance standard.

---

## Why a blueprint inside the artefact

The Rosetta decree's closing clause ordered its own inscription in three scripts and
its erection in temples across the realm. The replication instruction lived in the
payload — and it is the reason sister copies existed, centuries later, to restore the
broken original. This file is that clause for this class of artefact: it travels with
the worked example so that a finder can replicate the *class*, not merely admire the
*instance*. Pattern P10 below is the rule this document exists to satisfy.

## The core in one sentence

Build the artefact so that a finder who shares none of your context can still enter,
align, and verify: give the same subject in parallel registers, thread them with a
small set of recurring anchors, start from one register the finder is guaranteed to
read, and put declared context, stated boundaries, and a self-identity on every part
that can travel alone.

## Scope and non-goals

This is a **structural** pattern about encoding and recoverability. It is agnostic
about measured learning outcomes — whether any particular build earns its keep is for
its readers to say. It is not a pedagogy theory, not a compliance regime, and not a
substitute for subject expertise. Conformance means the **core patterns only**
(P1–P6); everything else is optional. Recoverability, not completeness: a small, clean
artefact that passes the core conforms fully.

---

## The patterns

Required core: **P1–P6**. Recommended extensions: **P7–P10**.
Each pattern carries an *as built* pointer into the worked example, including honest
gaps — the as-built column doubles as the open-task ledger.

### P1 · One subject, parallel rooms

**Problem.** Any single register excludes the reader who cannot enter by it, and
compression for a known reader strips exactly what an unknown one needs.
**Rule.** Build at least two, ideally three, genuinely different registers for the
same material — a narrative room (the *why*), a hands-on room (push and drag), a
reference room (definitions and limits). Partial redundancy across rooms is the
encoding, not waste.
**As built.** Lecture arc, interactive workshop, reference library, plus a curated
resources annexe.

### P2 · Anchors as cartouches

**Problem.** Parallel rooms without fixed crossing points cannot be aligned; what is
learnt in one room goes unrecognised in another.
**Rule.** Fix a small set — five to seven — of anchor ideas, named identically
everywhere and recurring in every room. The anchors are locks; each room's treatment
of them is a key.
**As built.** Six anchors thread all rooms under the same names and numbering.

### P3 · The Greek band

**Problem.** A finder needs one register they already read, or there is no entry at
all.
**Rule.** Make the first register the reader's guaranteed context — their lived
experience of the subject — and say explicitly that it is the entry.
**As built.** The course begins from the student's own senses: everyone arrives
already running a sensor suite.

### P4 · A boundary on every card

**Problem.** The expert's "too obvious to write" is precisely where the finder walks
off the edge; misuse travels further than use.
**Rule.** Every concept card states the one thing the concept does **not** imply —
its most common misuse — alongside its definition and load-bearing relations.
**As built.** Each reference card carries definition, equations, and the single common
misuse.

### P5 · Declared context

**Problem.** The context gap to a reader you will never meet cannot be closed.
**Rule.** Declare it instead: every surface states the level, audience, and date it
assumes, so a finder can measure their distance rather than guess it.
**As built.** The library states its assumed working level; pages carry their dates.

### P6 · Shards carry identity

**Problem.** Pages are saved, forwarded, printed, and found alone; an orphaned shard
without identity is rubble.
**Rule.** Any file that can plausibly travel alone carries a minimal identity: what it
is, what version, what licence, where home is.
**As built.** The index footer carries licence, version, and provenance; per-page
licence/version/provenance footers on every travel-capable sub-page shipped in site
version 2026.06.1 — the gap this ledger first tracked, now closed.

### P7 · Degrade gracefully *(recommended)*

**Rule.** Core content must survive the least-capable decoder you can cheaply serve:
offline use, no scripts (static fallback), plain print. No remote dependency for
substance.
**As built.** Single-file pages work offline; script-injected content has `noscript`
fallbacks carrying the full substance.

### P8 · Curate, and say so *(recommended)*

**Rule.** Tiered guidance — one *must*, a few *should*, more *can* — is legitimate
because it is disclosed: declare the sorting rule, present the path as one among many,
cap the must-tier's cost and annotate exceptions.
**As built.** Per-anchor MUST/SHOULD/CAN tiers, sorted by declared effort-to-payoff,
with the two heavyweight exceptions annotated as such.

### P9 · Annotations carry the payload *(recommended)*

**Rule.** External links rot. Write each pointer so its claim survives the link's
death — state what the source shows and why it is here — and prefer persistent
identifiers.
**As built.** Every resource entry carries a "why this" note; DOIs are canonical where
they exist.

### P10 · Imprint the blueprint *(recommended, recursive)*

**Rule.** The artefact links its own construction pattern, in its own repository, so
the next builder starts from structure rather than archaeology.
**As built.** This file, linked from the site footer.

---

## Transferring to another subject — a thirty-minute exercise

1. Name the subject and the finder you cannot meet (the student before week one; the
   colleague after you leave).
2. Choose the Greek band: which lived experience of this subject does *every* finder
   already have? (Statistics: everyday judgement under uncertainty. Law: a dispute
   everyone has had. Music theory: a tune everyone can hum.)
3. Fix five to seven anchors. Name them once, permanently.
4. Choose the rooms — narrative, hands-on, reference — and accept the redundancy.
5. Write the cards: definition, load-bearing relations, and the boundary (P4) for each
   anchor.
6. Declare context and identity on every surface (P5, P6); add tiers with their sorting
   rule (P8).
7. Copy this file into the new repository, update the as-built column, and link it from
   the artefact (P10).

## Conformance checklist

Core: **C1** two or more genuinely different rooms · **C2** fixed recurring anchors
(5±2) · **C3** declared guaranteed-entry register · **C4** boundary stated per concept
· **C5** context declared per surface · **C6** identity on every travel-capable shard.
Extensions: **C7** offline/no-script survival · **C8** curation disclosed · **C9**
payload-carrying annotations and persistent identifiers · **C10** blueprint imprinted.

**Genre-scoped self-test.** As a single-file handbook, this document is exempt from the
artefact-level patterns (P1–P3, P8) and must pass the document-level ones: identity
(header card) ✓ · boundaries (non-goals) ✓ · declared context ✓ · graceful degradation
✓ — plain Markdown, itself the most decoder-robust register available · imprint and
provenance ✓. Pending at v0.1: nothing.

## Maintenance invariants

A version stamp and dated changelog on every revision. The required core stays small —
resist inflation; a heavier core thins the archive of future builds. Review cycles end
by declared condition, not by exhaustion. **Lock criterion:** the core checklist green
on the worked example *and* one independent transfer to another subject attempted,
whatever its outcome teaches.

## Provenance and changelog

Extracted 2026-06-10 from *Sensing 2026* (worked example) and *The Stone That Did Not
Know Its Finder* v0.2 (T(h)reehouse +EC,
https://threehouse-plus-ec.github.io/website/archives/the-stone-that-did-not-know-its-finder.html).
Informed by an internal encoding discipline maintained with full apparatus elsewhere;
where this blueprint and that document seem to differ, the document is right and the
blueprint is wrong.

- **v0.1** (2026-06-10) — first extraction from the worked example.
