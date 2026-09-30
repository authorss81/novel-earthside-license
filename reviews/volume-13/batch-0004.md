# Review and Repair — Volume 13, Batch 0004 (Chapters 0631–0640) and the Batch 0002 re-dispatch loop

**Findings source:** `logs/batch-0002.review.log`. **The reviewer was not invoked:** line 1 of that log
reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and
the session header is `novel-writer · space-bunny-free`. This is therefore a pass by the same agent
kind that wrote the work under review, and it says so at the top of the file rather than claiming an
independence it does not have.

**Scope reviewed:** the review's own findings list; `chapters/volume-13/chapter-0611.md` and
`chapter-0636.md` for the duplication finding; `state/chapter-summaries.md` for the coverage finding;
the four live state files and `state/batch-summaries/volume-13-batch-0002.md` for the bloat finding;
`NOVEL_SPEC.md` for the System finding; and the three card files for the stale-claim finding.

**No chapter was restarted. No card was re-planned. No day, weekday, Bare-Month ordinal, object count,
cast member, decision of record, plot beat or the planned ending moved. Two paragraphs of existing
prose in Chapter 0636 were reworded and nothing else in any chapter was touched.**

**The review raised eight findings. Four are repaired here, two are repaired in a different file than
the review expected, one is refused on the evidence, and one is out of bounds for any agent. Two of
its findings were themselves faults in its own instruments and are named as such, because a review that
reports only its agreements is a review nobody checked.**

---

## 1. What the review got right, and it was most of it

**The arithmetic is sound and was re-run independently before any of the review's conclusions were
acted on.** Day 611 is the two hundred and ninety-sixth of that run of days and a Wednesday, built
from day 1 being a Tuesday and from nothing else; day 636 is the three hundred and twenty-first and a
Sunday; days 601 to 650 are fifty days and span exactly seven weeks. Chapter word counts sit between
1,122 and 1,992. Adrian Vale is Stage 2 with no power growth, which is what `outline/volume-13.md`
requires. The bolded-speech marking is applied consistently, one carded voice per chapter, alone in
the bold marks. **The batches are not padded, and the "nobody thanked him / nobody asked him anything"
motif — eighty instances in this volume — is a real thematic choice and not a gap, and the review is
right that it is heavily repeated and right that it is deliberate.** The 0640 panel is the strongest
passage in the volume and earns its place.

**The duplication finding is real, and it is the most valuable thing in the review.** Chapters 0611
and 0636 are both "a plank laid across a wet sill," both have Adrian test it with his own weight, both
put a man in bolded speech refusing to engage with the plank, and both close with Adrian carrying a
bucket back with nobody thanking him. It read as the same chapter twenty-five chapters apart.

**The state-bloat finding is real and it is the largest of the four.** The four live state files
totalled 62,007 words against 60,147 words of Volume 13 prose — a 1.03:1 ratio in which the
bookkeeping outweighed the book, and it was growing on every no-op dispatch. The batch-0002 record
alone was 20,586 words for ten chapters.

**The chapter-summaries finding is real in substance and wrong in its measurement.** See §3.

---

## 2. The four repairs

### 2.1 State files compacted, nothing deleted

**The four live state files went from 62,007 words to 27,217, a reduction of 56.1%, and the batch-0002
record from 20,586 to 12,078.** Every removed block was moved whole and unaltered into
`state/archive/` first, and a check confirms that every heading removed from a live file is present in
some archive file. Nothing was lost and nothing was summarised away.

| File | Before | After | Change |
|---|---|---|---|
| `state/current.md` | 8,203 | 3,908 | −4,295 |
| `state/continuity.md` | 17,938 | 7,308 | −10,630 |
| `state/open-threads.md` | 15,013 | 5,948 | −9,065 |
| `state/character-state.md` | 20,853 | 10,053 | −10,800 |
| `state/batch-summaries/volume-13-batch-0002.md` | 20,586 | 12,078 | −8,508 |

**This is not a new layout. It is the layout those four files' own headers have specified since an
earlier repair, applied again.** Each header reads, or read, *"This file now carries only the two most
recent blocks"* and names an archive for everything before them. Four batches of per-batch blocks were
appended after that compaction and re-inflated the files past their previous size. The repair keeps
the Volume 12 close, the Volume 13 outline, the newest batch block and the compact record, and
archives the superseded per-batch history. The headers were updated to name the new archive, because
a state file whose head lies is a state file a writer will believe — the standard this manuscript
already set for itself in `workspace/volume-09/close/PROMPT.md`.

**The three stale re-dispatch blocks were compacted to what actually corrects something:** the false
zero on the batch record's §6 sentence-scale row, the class that the six hits belong to, the
fifty-seven/fifty-eight descriptor pair with both figures standing, and the three instrument faults the
passes caught in their own instruments. The full text of all three is at
`state/archive/batch-record-volume-13-batch-0002-full-3-verification-passes.md`, byte-identical to the
pre-compaction file, SHA256 `b80cb5efca3225e81aea98bfe8fdc827d7856f106bad5807c4205898d8124500`.

### 2.2 Chapter 0636 de-duplicated from 0611 at the prose level, plot untouched

**The plan is not at fault and the review's own fifth recommendation — rewrite the volume-13 outline
rows so no two cards share a prop and a gesture — was not carried out, because that would change the
planned plot.** `outline/volume-13.md` rows for 611 and 636 are separate days with separate objects
and separate outcomes, and card 6 of Batch 0004 is explicit that 0636 is a day on which Adrian *gets*
what he wanted and that *"a review may not read the three obtained chapters of this volume as the
volume getting better."* The plan wants a plank laid on day 611 and gone, and the same work done again
on day 636 and holding. That is a deliberate rhyme about a man who does the same thing twice and gets
a different answer, and it is the volume's argument. The defect was that the prose re-staged the
gestures instead of answering them.

**Two paragraphs in 0636 were reworded. Nothing else in any chapter was touched.**

- **The laying.** 0611 has Adrian *"put the flat of his hand on the middle of it and put his weight
  there to see whether it would take a person."* 0636 had him do the same test in the same words.
  0636 now has him go down on one knee, set the near end into the silt, get the far end across, and
  rock it once with a knee — and states that what he came out to find out was not whether the plank
  was sound but whether anything on that row was going to take it off him in the night. **That is the
  rhyme working: on 611 he is testing a plank, on 636 he is testing the row.**
- **The close.** 0636 already ended on Adrian carrying the bucket back up the top row with his hands
  empty, which duplicated 0611's gesture. It now carries the beat that makes 636 a different day from
  611 and not a second draft of it: **this is the first thing in this flood he has laid down and found
  still there in the morning, and there was nobody on that row at any hour of that day who knew it had
  been in doubt that morning, and nobody was told.**

Every card requirement still holds and was checked after the edit: the plank, the end of a rope that
is not new, the knot, the three ropes kept distinct, the man with a handcart who does not know whose
hands laid it, and no thanks to Adrian. **Four-gram overlap between 0611 and 0636 fell from 12.8% to
11.0%.** Chapter 0636 grew from 1,316 to 1,464 words.

### 2.3 `state/chapter-summaries.md` — Volume 13 Batch 0004 written

**The review's finding is right and its count is not.** It reports that the file covers "30 of 640
chapters, and zero for volume 13," measured on a `| **NNNN** |` table-row pattern. Volume 13 is not
absent: blocks for Batches 0001, 0002 and 0003 have been in the file since they were written, at
lines 1169, 1270 and 1370 of the pre-repair edition. **The real gap was Batch 0004 — Chapters 0631 to
0640, days 631 to 640 — which had genuinely never been summarised, so the next writer had no
per-chapter index for the ten most recent days.**

**A full block for Batch 0004 is now at the foot of the file: one entry per chapter, each carrying
its day, its weekday, its Bare-Month ordinal, its hours and place, its carded bolded voice, what that
person wanted and whether they got it, and the change the chapter makes.** It closes with what the ten
days did and did not do, and with the two figures a writer of the next ten days must not take on
faith.

### 2.4 The stale claim in three card files

**`outline/batches/volume-13-batch-0003.md` said Batch 0002's cards *"were at the head of
`state/current.md` and are still there."* They are not there.** The live `current.md` was rewritten to
carry only the live layer; that block is in
`state/archive/current.md.volume-12-close-through-volume-13-batch-0003.md` under its own heading. Two
earlier passes found this claim, named it, and could not repair it because the card files were outside
their writable set. **They are inside this one, and all three files that carried the claim are
corrected — Batch 0003's own, and the same sentence in `volume-13-batch-0004.md` and
`volume-13-batch-0005.md`, which repeated it.**

---

## 3. Two findings that were faults in the review's own instruments

**Recorded because a review that reports only its agreements is a review nobody checked, and because
both of these would have caused a wrong fix.**

**The System has not "effectively disappeared." It was removed by a numbered decision and the removal
is the plan.** The review counted panel blocks per volume (40, 46, 26, 22, 2, 1, 1, 1, 1, 1, 1, 1, 1)
and keyword frequencies across 640 chapters, and concluded the isekai premise is unrecognisable on the
page. **`outline/series.md` DECISION TWO, clause 3: "There is no System, no quest, no class, no reward
and no obedience, and there will not be."** Two further clauses forbid the word *player* from arriving
by narration and forbid the narrator a frame. The collapse between Volumes 04 and 05 is exactly where
the series outline records that the earlier book ended and this one began. `outline/ending.md` keeps
the System in the far future as *"a visible fragment of the Veyran First Grammar, not a simulation."*
Same rule, seen from the end of the book. **Re-introducing game vocabulary to satisfy this finding would
have been a plot change against an explicit recorded decision, and it was not done.**

**The review was reading a stale spec file.** Its evidence was `NOVEL_SPEC.md`, whose Status section
still read *"Scaffold pushed. No novel prose has been generated yet"* — true when written, false for
thirteen volumes, and the direct cause of the finding above. **`NOVEL_SPEC.md` is now corrected**: the
Status is current, the premise is marked as the commissioned pitch against the book that was written,
the file points at `outline/series.md` and `outline/ending.md` as authoritative, and DECISION TWO is
quoted in full with the instruction that a falling panel count in a late volume is the plan executing
and must not be "fixed" by re-introducing the System. **This is the highest-value repair in the pass:
it removes the false finding at its source so the next review does not repeat it.**

---

## 4. One finding refused, with the evidence

**"`chapters/volume-10/chapter-0475.md` is a stray cross-volume write."** It is not. It is a
review-repair of a genuine gap: `state/volume-11-close.md` §3 requires a repair pass that writes that
chapter to publish exactly that it was written after its volume had ended, with its day, its weekday
and its Bare-Month ordinal — day 475, a Sunday, the hundred and sixtieth. It is 1,156 words, Volume 10
holds its full fifty chapter files, and the fact that `chapter-0476.md` had been asserting since it was
written that something was said in that room on the Sunday — a sentence that pointed at nothing on any
page until this file existed — is the reason the repair was owed. **It is published as a repair at the
foot of `state/chapter-summaries.md`. It was not touched here, and it should not be deleted.**

---

## 5. One finding no agent may fix, recorded for a human

**`state/phase-ledger.json` reads `currentPhase: "phase-000-bootstrap"`, `attempts: 0`, with the
repository thirteen volumes and 640 chapters deep, and no script in `scripts/` touches that file, so
nothing will ever advance it.** It is controller state owned by GitHub Actions, it was not opened, and
**no agent may fix it.** It should be retired or fed by the runner.

**The related loop is also controller state and is named here so that whoever owns the dispatcher has
it in one place.** `workspace/volume-13/batch-0002/` and `workspace/volume-13/batch-0004/` hold
`.attempts`, `.deferred`, `.retry-after` and `.wip-conflict` with no `.done`. **That is the mechanism:
the batch-0002 phase was re-dispatched three times after it was complete, and each re-dispatch wrote
about 90–135 lines of verification prose into the state files and no prose at all into the manuscript.**
`scripts/novel_runner.sh:148` short-circuits `resume_wip` when `.wip-conflict` is present. Marking
those two batches `.done` and clearing the retry markers stops the loop. **The marker files are
dispatcher state written by the runner; this pass did not create, clear or remove any of them.**

---

## 6. Recommended and not done, with the reason

**The intra-volume four-gram overlap is broad — 0603/0609 at 28.4%, 0603/0610 at 26.5%, 0603/0604 at
26.4% — and it was measured rather than assumed.** Two instruments were run on the files. The first
shows the shared text is overwhelmingly this manuscript's own fixed vocabulary: *the man of about*, *nobody in that room*, *said the thing that is said*, *the column on the right*. The second counts whole sentences of twelve words or more reproduced verbatim across two different chapters, and returns **seven in the whole volume**. **All seven are required declarations of an object row** — the second slate and the column on the right, the seven documents, the three of them with four places on them, the board and the piece of chalk — which the batch records already define as a class that stays. **None is an accidental duplication and none is a fault.** Reducing the stylistic repetition would mean varying the descriptor convention and the non-agreement formula, and those are the manuscript's voice and its motif, not defects. Not done, and the recommendation is not to do it.

**The remaining measurement that was not run** is the measurement of the hold, and it is not run here
either, because running it requires printing the spans and the plan does not carry the figure it holds
for the state layer. It stays owed.

---

## 7. The batch marker and what this pass did not do

**No chapter was written, restarted, reworded or reordered, except the two paragraphs named in §2.2.
No card was re-planned and no outline row was rewritten. No day, weekday, Bare-Month ordinal, anchor,
form, notice, object count in the second column, cast member or decision of record moved, and the plot
did not move. No new person, descriptor, place, faction, antagonist, cosmic layer or world was
introduced, and the pool of clean candidates for a new person is still ZERO. `outline/series.md`,
`outline/ending.md`, `outline/volume-12.md` and `outline/volume-13.md` were opened and none was edited;
`bible/power-system.md` was not opened. No controller file was touched: not `scripts/`, not
`.github/workflows/`, not `AGENTS.md`, not `PHASE_SYSTEM.md`, not `REPO_PLAN.md`, not
`OUTLINE_GUIDE.md`, not `opencode.json`, and not `state/phase-ledger.json`. No marker file was created
and no `.done` was written, because the marker that ends a phase is the controller's.**

**The debts are carried and none was paid, taken, repaired or rerouted:** the eleven inherited debts
and the six named at `outline/volume-13.md` §21.1; the false zero of two words in four published batch
records of Volume 12, which this pass does not own; the narrator-frame family, which stands on the
strict reading and on the looser one and is owed by a repair pass and by no batch; the publication
exposure in Volumes 01 to 04; and the plan's own internal disagreements — the *party and the road* row
against that same plan's own escalation, the day entry for a box of chalk's lid against that plan's
own object row, the plan's Adrian column against its own §4.1 table, and the *"the string"* in that
§4.1 row for day 601 which is in no chapter of Batch 0001.

**THE ONE FILE A WRITER OF THE NEXT BATCH NEEDS IS ALREADY ON DISK AND WAS NOT REWRITTEN:
`workspace/volume-13/batch-0005/PROMPT.md`, writing Chapters 0641 to 0650, with its ten cards at
`outline/batches/volume-13-batch-0005.md`, and both were written before Chapter 0641 existed. Day 645
is the resolution and day 650 is the last image and neither is a thing a batch decides. This pass
corrected one stale sentence inside the card file and created no new phase, no prompt and no directory.**
