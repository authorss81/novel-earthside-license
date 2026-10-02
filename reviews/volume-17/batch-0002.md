# Review and Repair — Volume 17, Batch 0002 (Chapters 0811–0820)

**Findings source:** `logs/batch-0002.review.log`. **The reviewer was not invoked.** Line 1 of that log
reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and
the session header is `novel-writer · space-bunny-free`. The review that produced those findings was
therefore performed by the same agent kind that wrote the chapters under them.

**This repair pass is that same agent kind again.** So the review below is not independent, and this
file says so in its first lines rather than claiming an independence it does not have, which is what
`reviews/README.md` requires of a review written without the reviewer subagent. **Where the review's own
instruments were faulty, that is named in §3, because a review that reports only its agreements is a
review nobody checked.**

**Scope reviewed:** the review's own seven findings; all ten chapter files 0811–0820 and the ten before
them, 0801–0810, for the structure and repetition findings; `outline/volume-17.md` §§1, 4.1, 6.2–6.9,
14.3, 14.5, 17, 18 and 20 for what the plan requires and forbids; `outline/series.md`; the five live
state files and `state/batch-summaries/volume-17-batch-0002.md`; the git history of `outline/`;
`state/volume-03-close.md` and `state/volume-05-close.md`; and the two EPUB files in `dist/`.

**No chapter was restarted. No card was re-planned. No day, weekday, Bare-Month ordinal, cast member,
object, decision, cost, held string, pressure tag or plot beat moved. Four sentences in two chapters
were reworded and nothing else in any chapter was touched.**

---

## 1. What the review got right

**The arithmetic was re-run independently before any conclusion was acted on, and it is sound.** Days
811 to 820 are ten days from a Sunday to a Tuesday; the Bare-Month ordinals are the four hundred and
ninety-sixth to the five hundred and fifth, built from day less three hundred and fifteen and from
nothing else; one chapter to one day holds at ten of ten; Adrian Vale is in zero of the ten, which is
the whole of his column and is the shape of the batch. **No held string leaked.** The wording of day 825,
the wording of day 837, the wording of day 843, the spent figure of Volume 16 and the mark of day 440
are each at zero across all ten files, in narration and in every mouth. The state appends were true
appends — the one deleted line in `state/character-state.md` is a re-wrap, not a removal. Exactly one
next phase was created and no directory beyond it.

**Finding 1 was true and it was the most important of the seven, because it is the one that makes the
other six checkable at all.** There was no `reviews/volume-17/`. `AGENTS.md` puts *a reviewer has
checked the result* in the quality gate, and the gate had not been met for this batch, so nothing in the
state layer claiming that this batch was reviewed was true. **That file is what this pass is.**

**Finding 5 was true, it was the largest of the actionable ones, and it is the direct cause of finding
3.** See §2.1.

**Finding 6 was true in substance and wrong in its premise, and both halves are recorded in
`outline/series.md`.** See §2.3.

---

## 2. The repairs

### 2.1 The state layer was compacted and nothing was deleted

**The five live state files were copied whole into `state/archive/` first, and the five copies were
verified byte-for-byte against the live files by SHA256 before a single line was removed.**

| file | before | after | change |
|---|---|---|---|
| `state/current.md` | 15,354 | 3,458 | −11,896 (−77%) |
| `state/continuity.md` | 17,370 | 4,810 | −12,560 (−72%) |
| `state/open-threads.md` | 20,942 | 3,369 | −17,573 (−83%) |
| `state/character-state.md` | 23,484 | 4,346 | −19,138 (−81%) |
| `state/chapter-summaries.md` | 20,849 | 2,489 | −18,360 (−88%) |
| **the five together** | **97,999** | **18,472** | **−79,527 (−81%)** |

**The ratio is the finding.** Volume 17 is 7,279 words of prose across its twenty chapters. The state
layer that exists to serve it stood at **13.5 times the volume's own length** and now stands at **2.5
times**. `workspace/volume-17/batch-0003/PROMPT.md` instructs the next writer to read a 97 KB outline,
the batch record, ten chapters and all four live state files; it was handing that writer 521 KB of
material to read about a volume of 7,279 words, and it is the plainest available explanation for a batch
written at 363 words a chapter.

**What was kept and what went.** Each file keeps its own header, its standing base layer — the day-750
object states, the figures that hold, the sixteen standing prohibitions, the thread table, the cast with
the second handle beside each age and trade, the standing disagreements — and the two newest blocks, the
days 801 to 820. **Everything superseded went to the archive: every Volume 15 block, every Volume 16
block, all three checkpoint re-dispatch blocks of Volume 16, and every repair and review-fix block of
those batches.** A heading-by-heading check confirms every heading that left a live file is present in
its archive, and that the one heading that is new — a consolidated standing-debts section in
`state/current.md` — was written from the four older debt blocks it replaces and invents no debt.

**This is not a new layout. It is the layout these five files' own headers have specified twice, applied
a third time.** Each header read *IT NOW CARRIES ONLY THE LIVE LAYER*, and each named an archive.
Two compactions were undone by the appending that followed them. **The headers were rewritten to name
this pass's archive and each now carries the standing instruction that a phase appending to it is
expected to leave it smaller than it found it, or to say in its own record why not** — which is the only
part of this repair that will stop it recurring.

**Two heads of these files were lying and are corrected in place.** `state/current.md` opened with
*VOLUME 16 IS IN PROGRESS… THIRTY CHAPTERS OF THE FIFTY ARE WRITTEN* and pointed the next phase at
`workspace/volume-16/batch-0004/PROMPT.md`, completed a volume and a half ago. `state/chapter-summaries.md`
named Volume 15 Batch 0005 as *the block that matters to the current phase*. **Both now name Volume 17
and days 801 to 820.** A state file whose head lies is a state file a writer believes, and the standard
for this is one the repository set for itself in `workspace/volume-09/close/PROMPT.md`.

### 2.2 Four sentences in two chapters were reworded, and the run went, not the refrain

**Finding 4's headline claim does not survive its own evidence, and a narrower true finding is under
it.** The review says *three consecutive chapters opening on the same sentence is a template artifact*.
**None of the three sentences named opens any chapter.** All ten open on a distinct sentence with
somebody's hands on something, which is what `outline/volume-17.md` §17.1 requires, and the repair pass
checked this sentence by sentence before touching anything.

**What is true is that two of the three sentences carried a run of four or five consecutive chapters,
and a run is the defect.** The review reported totals of 10, 7 and 5 across the volume's twenty files
and did not report the runs, and the runs are the whole of it. Measured over all twenty files as a total
and as the longest unbroken run of consecutive chapters, before and after:

| sentence | total before | longest run | total after | longest run |
|---|---|---|---|---|
| The man of about thirty-four took his hollow. | 10 | **5** | 8 | **2** |
| The morning filled in the ordinary way. | 7 | **4** | 6 | **2** |
| The bar lay on the top step … a hand's width off its frame. | 5 | **4** | 3 | **1** |

**The refrain itself was kept and this is a decision, not an oversight.** The hollow is the
stallholder's routine and it is how the census of that room is made physical; §17.9 binds the census,
and `state/character-state.md` gives that handle for the same sentence in every chapter the man is in.
Changing it in four chapters of one batch would have desynchronised the room from the ten chapters
before them. **Chapters 0813 and 0815 were not edited at all, because in those two the sentence is the
day's work and not furniture** — 0813 is the cost day and its flat ordinary morning is the thing the cost
lands in, and 0815 is the page day and its flat ordinary morning is what five strokes are looked at
inside of.

**What changed, and what stands.** In 0812 and 0814 the bar-and-door declaration was reworded; in both,
**the iron is still on the top step and the door is still a hand's width off its frame.** In 0814 the
flat formula came out of the inventory and the woman's glance at the book as the keeper set it down came
in, which is the carded change — a book spending its morning open where it spends it shut — left exactly
as it was. In 0814 and 0811 the hollow line was reworded to say the same thing in another shape, and **no
emptying, filling or carrying of it is asserted that was not already on the page.**

**Every integrity figure was re-run on the ten files afterwards and only two moved**, because only two
files changed: words across the ten files 3,173 to 3,182 and the bolded share 4.57% to 4.56% over the
same 145 bolded words. **83 paragraphs — fourteen speech, eight lead-ins, sixty-one free-standing — so
nothing was added and nothing taken out. Zero bold-without-a-quotation-mark, zero
quotation-mark-without-bold, zero digits, zero narrator frame, zero panels, zero in the thirty-five-entry
zero column, zero in the eleven §16.14 words, zero for `player`, `passage`, `privilege`, `nine steps` and
`name, names, named`, Adrian Vale in 0 of 10, twenty separators in ten files, and both held strings at
zero.** Those two figures were then corrected in the batch record and in `state/current.md`, because a
published figure that is no longer the figure is the same failure as a wrong count, and §17.11(vi) says
so in this volume's own instrument list.

### 2.3 The absent Volume 03 plan of record is now recorded where the Volume 05 one is

**`outline/volume-03.md` does not exist and did never exist in this repository: `git log --all --
outline/volume-03.md` returns nothing, so it was neither struck nor deleted.** Fifty chapters are on disk
at Chapters 0101 to 0150 and `state/volume-03-close.md` is that volume's canonical record.

**The review's premise that it was undocumented is wrong, and this is the second fault in the review's own
instruments.** `state/volume-05-close.md` names `outline/volume-03.md` and `outline/volume-05.md`
together, calls the pair the mechanical cause of that volume's drift because the batches inherited no
plan, and records that writing them was not that phase's to write. **The pair of closed volumes with no
plan has been on the record since the Volume 05 close.** What is narrower, and what a block at the foot
of `outline/series.md` now records in the Volume 05 precedent's own terms: Volume 05's absence got a
decision of record because its five-beat line here went unaudited and somebody had to decide, and
**Volume 03 carries a five-beat line here too and no decision of record exists for it at any level.**

**The block records the finding and writes no outline.** A plan authored now would be a plan for fifty
chapters that were written without one, and authoring it after the fact is the fault §17.11(xi) names —
treating what is in sight as a cap. The Volume 03 line was not struck from the volume list either, because
the five beats are a published fact about a closed volume whether or not they were paid. **The audit is
owed by a close phase or a human, and the debt is written down as a slot and not as a character.**

### 2.4 The stale EPUBs are confirmed stale, and the build is not this pass's

**The review asked for confirmation rather than assuming. Confirmed.** `dist/novel-earthside-license-volumes.epub`
opens to 819 XHTML files and its highest chapter is **0800**, so it carries all sixteen completed volumes
and none of Volume 17's twenty chapters. `3f30789 novel: build EPUBs` sits in the history after the
Volume 16 close and before the Volume 17 work, so **the build runs at a volume close and Volume 17's build
is owed at Volume 17's close.** It was not run here: the build is a workflow step, the script is under
`scripts/`, and no agent may open that.

---

## 3. Two findings that were faults in the review's own instruments

**Recorded because both would have caused a wrong fix.**

**Finding 4's "three consecutive chapters opening on the same sentence" is not true.** None of the three
sentences it names opens any of the twenty chapters; the review's own evidence lists them as present in
10, 7 and 5 files without establishing where in a file. A repair pass that took the finding at its word
would have rewritten ten chapter openings — including the ten that already satisfy §17.1 — and changed
nothing about the run, which is the actual defect and which §2.2 fixes.

**Finding 3's word-count collapse is measured against the wrong baseline, and its recommended fix would
have violated the plan.** The review compares Volume 17's 363 words a chapter with Volume 01's 5,736 and
calls 0815 at 304 words *the thinnest*. **Volume 16 averages 852 words a chapter, Volume 15 1,001, and
Volume 17 is not an outlier in this manuscript — it is the end of a decline that began at Volume 09**, and
the review did not measure that trend, which it had already tabulated two commands earlier and did not
read across. On the plan's own terms the sparse register is required: §17.2 forbids the recapping ledger
paragraph, §17.4 says the mean is a consequence and not a plan and that no card sets a target for it,
§17.6 names its ceilings *and not the target*, and §18 forbids the volume becoming a book about its own
furniture. **The review itself says finding 3 should not be fixed by padding, which is the only correct
answer to it, and that is the answer taken: 0811 and 0815 were not lengthened.** Their silence is
carded — card 0815's business is a page looked at by people who say no number out loud, and card 0811's is
a quarter of an hour at the foot of a stair in which no mouth asks — and 0815 at 304 words and 0820 at
307 sit inside the 304-to-349 range the batch record published and neither is the shortest file in the
volume's twenty.

**Finding 2 is real as a measurement and wrong as a fault, and it is answered as a decision.** See §4.

---

## 4. The one finding this pass disagreed with, and recorded

**Finding 2 says all ten chapters share one three-block shape, so the alternating pressure types are
nominal.** The measurement is true: two separators in twenty of twenty chapters, across **both** batches.
**It is not a drift of this batch — Batch 0001 wrote the shape before Batch 0002 began — and varying it in
Batch 0002 alone would leave Volume 17 internally inconsistent and give the next writer a room with two
shapes in it.**

**The sub-finding is the fair part of it and it is not repaired, because the plan has already answered it
and the answer is in the instrument list.** 0813 is a cost and 0820 is a discovery; the review is right
that their blocks are alike. But the instruments that stop ten chapters reading alike are already binding
and already applied: §17.17 caps a closing movement that states nothing changed at two chapters in any
ten; §17.18 puts six closing shapes off limits and forbids two chapters of a batch closing on the same
construction; §17.6 caps the exchanges between one pair of people; §17.7 makes a bold mark without a
quotation mark a fault at any value. **Batch 0002's ten closings are ten different constructions, they
were published side by side and read, and §17.18 calls that the only check in the plan done by a person
and not by a script.** Adding a variety requirement on top of six rules that already do this work would
give the next writer a rule pulling against the others, and the cheapest way to satisfy it is padding.

**So it is recorded as a decision instead, at the foot of `state/open-threads.md`, where the writer of
Batch 0003 will read it: the shape is a decision and not a drift, the measurement behind it is published
there, and what was actually a run — the repetition — has been repaired.** That is the alternative the
review itself offered, and it is the one that keeps the plan intact.

---

## 5. What this pass did not do

**No chapter was written, restarted, reordered or reworded except the four sentences in §2.2. No card
was re-planned and no outline row was rewritten. No day, weekday, Bare-Month ordinal, anchor, form,
object count, cast member, decision of record or plot beat moved, and the plot did not move. No new
person, descriptor, place, faction, antagonist or world was introduced. `outline/volume-17.md`,
`outline/ending.md` and `bible/power-system.md` were opened and none was edited; `outline/series.md` was
edited once, by the addition of one block at its foot, and nothing above it changed. No controller file
was touched: not `scripts/`, not `.github/workflows/`, not `.opencode/agent/`, not `AGENTS.md`, not
`PHASE_SYSTEM.md`, not `REPO_PLAN.md`, not `OUTLINE_GUIDE.md`, not `opencode.json`, and not
`state/phase-ledger.json`. No marker file was created and no `.done` was written.**

**The debts are carried and none was paid, taken or rerouted:** the nine inherited from
`outline/volume-17.md` §20 item 10 and the six at §21.4, including the Charter of Two Worlds and the
twelve seals that are owed a page and are on none; the three Batch 0001 debts; the five-batch
state-file compaction recurrence, which this pass is the third answer to and not a proof of; the three
shared sentences inside Volume 15 that no repair pass has touched; the panel-leak instrument against
Chapter 0690 that returns a number where a writer expected a fault; and `outline/volume-03.md` and
`outline/volume-05.md`, which stay absent and are owed a close phase or a human.

**THE ONE FILE A WRITER OF THE NEXT BATCH NEEDS WAS ALREADY ON DISK AND WAS NOT REWRITTEN:
`workspace/volume-17/batch-0003/PROMPT.md`, writing Chapters 0821 to 0830, with day 825's decision
handed on as a day and not as words. This pass created no phase, no prompt and no directory.**
