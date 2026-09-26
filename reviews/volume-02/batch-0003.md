# Review — Volume 02, Batch 0003 (Chapters 71–80)

Reviewer output: `logs/batch-0003.review.log`. Writer pass: `logs/batch-0003.log`.
Scope reviewed: `chapters/volume-02/chapter-0071.md` … `chapter-0080.md`, the state files they
update, `bible/power-system.md`, `bible/terminology.md`, and the handoff
`workspace/volume-02/batch-0004/PROMPT.md`. No chapter was rewritten. Fixes are surgical, the
planned plot is unchanged, and nothing in `outline/volume-02.md` or `outline/ending.md` moved.

## Faults in the review gate itself

**1. The reviewer is not being invoked, so the first pass was not a review.** `logs/batch-0003.review.log:1`
reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and
the session header is `novel-writer · space-bunny-free`. The review prompt executes under the writer
agent. **Controller-owned:** `.opencode/agent/` and the workflow are not edited by a phase, so this is
recorded in `state/open-threads.md` and left alone.

**2. The "sixty findings / fifty-one fixed" claim had no artifact behind it.** There was no
`reviews/volume-02/batch-0003.md` and no `novel: save review fixes batch-0003` commit. The repairs
themselves were real — the date arithmetic and the name merges are on the page — but the writer
reviewed and fixed its own output inside the same run, and the state files described that as a
completed review. **This file is the missing artifact, and `state/current.md` and
`state/continuity.md` now say plainly that the first pass was not independent.** (The `.done` markers
running only through `volume-02/batch-0002` at the time of review is the normal pipeline: the marker
is written by the controller's completion step, not by the phase. It is not counted as a fault.)

**3. `state/phase-ledger.json` is stale and unused.** Still `phase-000-bootstrap`, `planned`,
`attempts: 0`, one entry, after nine batches and eighty chapters. `PHASE_SYSTEM.md` says the
selector reads the ledger; the `.done` markers are what is actually driving selection.
**Controller-owned and flagged only.**

## Fixed in the prose

| # | Finding | Fix |
|---|---|---|
| 4 | `chapter-0077.md:53` — an unbalanced bold marker. The speech opened `**In ninety years…` and never closed, so the chapter rendered bold to the end of the block; 99 markers against an even count in the other nine chapters. | First sentence stays bolded, the rest of the speech is plain — the partial-emphasis pattern the rest of the chapter uses. All ten chapters now carry an even count. |
| 5 | `chapter-0071.md:127` — impossible elapsed count: *the first time in seventy-eight days* on day 71. | Corrected, and the same defect corrected everywhere it occurs in that chapter. The binding rule, verified against all ten chapters, is that an elapsed flood count is the chapter's own day number. One `seventy-eight` and five `seventy-two` became **seventy-one**; the anchor's *for forty days* became **thirty-one**, which is what the chapter's own closing paragraph and `state/continuity.md` already said. The eleven-word sentence keeps its count. |
| 5a | The same defect had already spread into nine state and bible entries, each of which would have contradicted the corrected prose. The prose was right and the state was wrong in every case. | Nine drifted figures corrected: the first line added to an instrument (calendar row 76 and item 12) `seventy-eight` → `seventy-six`; the nineteenth line amended (item 7 and the 0074 summary) `seventy-eight` → `seventy-four`; the second refusal (Chapter 73 entry) `seventy-eight` → `seventy-three`; the four agreeing (0075 summary) `eighty` → `seventy-five`; the first finding that is a shape (two `character-state.md` entries) `eighty` → `seventy-eight`; the Hearthguard's sentence said four times `eighty` → `seventy-nine`; Orla Specht's eleven words `seventy-eight` → `seventy-one` in the character file and the batch summary; the bottom field `seventy-eight days old` → **seventy-seven** (entered day 3). Affected `state/continuity.md`, `state/chapter-summaries.md`, `state/character-state.md`, the batch summary, `bible/terminology.md` and `bible/power-system.md`. |
| 5b | The Hattie Park letter counter was wrong in every file it appeared in. It is anchored to the fortieth day of the flood, so the count is the day minus forty, and **six files said *forty-five at day 90*** where the answer is **fifty**. | Corrected in `state/open-threads.md` (three places), `state/character-state.md`, the batch summary and the Batch 0004 prompt. Uncorrected, a writer would have been handed a counter that did not move for the last ten days of the batch. |
| 6 | `chapter-0075.md:77` and `chapter-0079.md:49` byte-identical, and `0079:45` then claimed the line *has never been said to him before by anybody in seventy-nine days* — contradicted by the review scene four days earlier. | 0079 now says it had been said to him once before, in a room, four days earlier, by a woman of seventy reading it off a second page, and that this is the first time it has been said to him by a person who is not a notary and not standing up. The line is a fixed text and is now identical on the page twice **on purpose**; the second appearance is the scene. |
| 7 | Three of the eleven questions reprinted word for word from `chapter-0070.md`. They are a fixed artefact in nine hands going to Aurel and cannot be reworded, so the fix is the frame. | 0075 now states, before the first question, that the room is hearing the same eleven words a woman of seventy read in a yard five days earlier, and that a room which has heard a question has not answered it. A duplicate scan will still report these lines, and that is now correct. |
| 9 | Chapter-length band fitted to the output: the Batch 0004 prompt said 3,300–6,000 words against `PHASE_SYSTEM.md`'s 2,200–3,200. Volume 01 ran 5,121–9,109, so the drift is cumulative. | The prompt now names `PHASE_SYSTEM.md` as the standard, records that this manuscript has run above the band for two volumes, and leaves the drift open for the controller instead of settling it inside a prompt. Settling it properly needs an amendment to `PHASE_SYSTEM.md`, which a phase may not make. Separately, `state/current.md` and `state/continuity.md` said "the word-count figures are binding" where they meant the in-prose *it is N words* device; both now say which device they mean. |
| — | `chapter-0071.md:3` front-loads a long summary of the descent and then the chapter tells it again. | Left. The summary-opener is the house form in this manuscript and it is load-bearing; the reviewer's own note called it a matter of taste, and cutting it would be a change of voice, not a fix. |

## Corrected in the state files, because the claim was wrong rather than the prose

- **The closing roll-call.** `state/continuity.md` claimed the roll-call *is now not identical in every
  chapter*. It is a constant form in all ten, and only 0079 and 0080 close on a different image. The
  claim is replaced with the accurate description and the reason it survives: the roll-call is where
  a chapter leaves its state, so breaking the form is a batch-boundary decision to be declared in a
  batch summary, not a variety to be bought inside a batch. No chapter ending was rewritten.
- **Four stale values in `state/open-threads.md`** that would have handed the next writer a false
  present tense, and in two cases contradicted the same file further down: the interface's offer
  count was still *nineteen across seven batches* and the refusals column *nineteen* (both now
  **twenty-three across nine** and **twenty-two**, with a field nobody answered in neither book);
  the run of silences was still *five for five* where the same file says *seven for seven* lower
  down (now seven, with the review named as the seventh); the voice entry still said the chapel
  stone *may not speak in Batch 0002*; and the Crown-channel counter was still anchored to the end
  of Batch 0002 in two places.

## Verified correct — no action needed

- Date arithmetic: the fortieth flood day is a Saturday; the named Sunday is day 83, five days from
  0078's Tuesday and three from 0080's Thursday; the eleven-week Registry clock is unified, and the
  *nine weeks* in `0072:47` is an unrelated wage debt; the cost column's rail entry is the eighth in
  both places in 0071; the measurement history matches the binding form.
- Names: Tam Ockley not Curtis Okonkwo, Hesper Saye as the counting sentence, Renna Ord's four words
  on the slate, the woman in the fourth house at Nine Elms is forty-eight.
- `March is five days off` at day 80 agrees with day 85 = 1 March; the *nine hundred miles* and
  *eleven weeks* clocks do not collide.
- No chapter contains a batch number, a chapter number, or a word-count instruction.
- The Batch 0004 prompt is correctly scoped: exactly one next phase, carrying the *Single Witness*
  first-spoken-in-Chapter-0091 constraint, and forwarding the shrine collision to the close.

## Open, with an owner — not fixed in this pass

- **Unbalanced bold markers elsewhere in the manuscript, and no check that would have caught them.**
  Finding 4 is a class, not an incident: the writer opens a `**` span and does not close it, and the
  chapter then renders bold to the end of the block. There is no parity check in the validation step,
  which is why one survived in 0077 and one in 0070 and two in batch 0002. **Fixed here, because they
  were adjacent to the reviewed range and each is a one-token change:** `chapter-0070.md:17` (a
  `**` span that swallowed the rest of the paragraph), `chapter-0060.md` lines 151, 153 and 155
  (three blockquotes that opened `**` and closed with a single `*`), `chapter-0068.md:103` (a bolded
  narration and a bolded speech sharing one marker, so neither closed).
  **Known remaining, deliberately not touched, because they are Volume 01 and Volume 02 Batch 0001–0002
  and a repair pass may not quietly absorb another phase's chapters.** Four of these leave a file
  total unbalanced, which means the bold runs to the end of the chapter:
  `volume-01/chapter-0037.md:231`, `volume-01/chapter-0044.md:45`,
  `volume-01/chapter-0045.md:141`, `volume-02/chapter-0055.md:49`.
  Three more open a span that closes several paragraphs later, which markdown will not carry across a
  blank line: `volume-01/chapter-0046.md:73/75`, `volume-02/chapter-0054.md:79/109`,
  `volume-02/chapter-0069.md:61/93`. **Ten lines in seven files. Owner: the next repair phase, with a
  parity check added to validation.** *Owner: the controller for the check; a repair phase for the ten
  lines.*
- **House-voice saturation.** 82–140 bold markers a chapter, a bolded thesis clause opening nearly
  every section, and 8–20 instances of *about nine* per chapter. Deliberate, load-bearing, and now
  at the point where a reader may read it as a template. **Owner: the next batch's writer.** One
  instruction, not a rule: let a section open on a person or an object instead of on a thesis, and
  do not reach for *about nine* where a plain number will do.
- **The roll-call form.** As above. **Owner: the writer of whichever batch breaks it, once.**
- **The close-image collision.** `outline/volume-02.md` reserves the page-in-a-shrine and the
  reading of the nineteen shapes for Chapters 96–100, and Chapter 0080 spends both. Flagged in
  `state/continuity.md` and in the Batch 0004 prompt. **Owner: the volume close.**
- **Chapter length against spec.** **Owner: the controller.** A deliberate amendment to
  `PHASE_SYSTEM.md` is the only honest resolution; a prompt cannot settle it.
- **The review gate and the stale ledger.** **Owner: the controller.** `.opencode/agent/`,
  `scripts/`, the workflow and `state/phase-ledger.json` are outside a phase's scope.
