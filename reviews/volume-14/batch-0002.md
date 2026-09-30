# Review and Repair — Volume 14, Batch 0002 (Chapters 0661–0670)

**Findings source:** `logs/batch-0002.review.log`. **The reviewer was not invoked:** line 1 of that log reads
`agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session
header is `novel-writer · space-bunny-free`. This was therefore a pass by the same agent kind that wrote the work
under review, and it says so at the top of this file rather than claiming an independence it does not have. That
is the fourth consecutive volume to say it, and `reviews/volume-13/batch-0004.md` already published the fact.

**Scope reviewed:** the review's own findings list; all ten chapter files; the batch record
`state/batch-summaries/volume-14-batch-0002.md` for the false-certification finding; the four live state files; and
`workspace/volume-14/batch-0003/PROMPT.md` for the finding that the prompt is the mechanism behind the batch.

**No chapter was restarted. No card was re-planned. No day, weekday, Bare-Month ordinal, object count, cast member,
descriptor, decision of record, plot beat or the planned ending moved. Not one bolded turn was altered: 769 bolded
words stand across the ten files before and after. No panel was added. No prohibition was widened.**

**The review raised eleven findings. Eight were repaired here, one was partly repaired and partly refused with both
halves published, one was refused on the evidence, and one was out of bounds for any agent. The record the review
was pointing at also certified four things that were false on the page, and every one of those is corrected in
place with the pre-repair figure printed beside the post-repair one, because a corrected count that does not say
what it was is the fault twice.**

---

## 1. The arithmetic was sound, and it was re-run before any conclusion was acted on

Day 661 is a Thursday and the three hundred and forty-sixth of that run of days; day 670 is a Saturday and the
three hundred and fifty-fifth; days 661 to 670 are ten distinct days with no gap and no double. That was rebuilt
from day 1 being a Tuesday and from nothing else, and **it reproduces after the repairs, ten of ten, because no
repair added a date and no repair removed one.** Zero `>` panel blocks across the ten files, before and after. Zero
bare digits in prose, before and after. No ordinal for a month, no span, no day after the 385th, and *length*,
*long* and *short* at zero as applied to the month. No round figure printed on any trap day, and **no sentence
carrying both halves of any Bare-Month/flood-day pair, before or after.** No *passage*, no *privilege*, no *rooms*,
no *dozen*, no man of about thirty-seven, and the stair never said to be nine steps.

**Two things in the review's log were themselves wrong and are named here, because a review that reports only its
agreements is a review nobody checked.** Its duplication extractor reported seven excess repeats and was right, and
its `grep -c` on the present-tense restatements reported nine while counting *lines* rather than occurrences — nine
lines, and the occurrences are what this pass then removed. **And the review's own word-count table caught a real
error in the batch record that the record did not catch in itself: Chapter 0661 is 1,159 words, not the 1,162 its
§4 published, and the ten total 8,875 rather than 8,878.** Both figures were re-measured here from `git show HEAD:`
on the same instrument and both corrections are published in §4 of the record with the wrong ones beside them,
because a corrected count that does not say what it was is the fault twice. **The other nine rows of that table
reproduce cell for cell and the bolded column reproduces exactly at 769 across all ten files.**

## 2. Finding one — the prose was mechanically degenerate, and the batch record certified it

This is the finding that mattered and all three of its parts were real.

**The unmoored restatements.** Nine sentences, one in each of nine files, opened a chapter by re-describing its own
protagonist in a bare present-tense fragment with no grammatical subject and nothing for it to attach to:
*He has a tally-board and a knife and a barrow…* The sentence before it had already said all of it. **The outline
mandates the device at §20.6 and the batch applied it as a string instead of as an instruction.** All nine were
re-moored into the tense of the narration around them, and **every piece of identifying content survived** — age,
trade, and the objects that belong to that person are still there, because the handle is a fact and never was a
sentence. Check: `\b(?:He|She) has (?:a|an|her|his|one|two|nineteen|not)\b`, ten files, **9 → 0**.

**The duplication.** Seven sentences of nine words or more repeated word for word. Three of them sat *consecutively*
inside one paragraph pair in 0662 and 0667, including one of forty words. The batch record's §1 called its two
repeats *frames* and said *no chapter has become the other*; **that reading is withdrawn, because three consecutive
identical sentences is a copy and not a frame.** One side of each pair was rewritten — 0662/0667, 0663/0669,
0663/0664, 0668/0670 — and the pairs remain pairs, with the same two subjects, the same third parties, the same
days and the same two bolded voices, and now with no sentence in common. Check: whole-sentence match at nine words
or more across the ten files, **7 excess → 0**.

**The closing frame.** Eight of ten chapters ended `[X] stayed…, and [X] found that the morning had…, and he or
she kept…`. The record's §8 said *ten different constructions* and carried no table to check it against. **All eight
were rewritten; the two that were already distinct were left alone.** §8 of the record now carries all ten side by
side. Check: `found that the morning` in the last sentence, **8 → 0**.

## 3. Finding two — four narrator-frame violations against the series' own decision of record

`outline/series.md` DECISION ONE: *the narrator may not say this chapter, this volume, in this batch or the reader.*
The review found four, and there were four. Three in 0664 — *the reason is not given and the chapter does not
supply it*, *this volume does not enter it*, *the chapter says so in narration and not in any mouth* — and one in
0670, *the chapter does not count it either*. The last of those is the narrator describing its own compositional
choice, which is the worst of the four.

**All four are rewritten, in the world's own terms and not in the narrator's.** The reason the carrier opens nothing
is now *on no page in that room and nobody asked him for it*. The inland town is unentered because *this city has
not sent a man to it in this flood*. The absence of the four-day cooling is now *not one mouth in that room said
so*. The row in 0670 does not count itself. The frame around 0664's cooling sentence — *for the seventh volume
running* — went with it, because a narrator does not get to count volumes. Check: **4 → 0.**

## 4. Finding three — the batch record was not a trustworthy instrument, and it is corrected in place

| The record claimed | The page | What this pass did |
|---|---|---|
| §8: *ten different constructions* for the closings | one construction, eight of ten | §8 rewritten with all ten published side by side and a check that can be run |
| §4: a weighted mean compared against two other batches' means | `series.md` publishes the mean as a consequence and forbids exactly this comparison | the comparison is withdrawn in its own words; both runs published; 8.34 published and read against nothing |
| §4: Chapter 0661 at 1,162 words and the ten at 8,878 | 1,159 and 8,875 on the same instrument at the same commit | corrected with both figures on the row; the other nine rows reproduce |
| §5: a full marker table | no cell for the narrator frame, and four violations standing | §5 now says which check was missing and why a check not in the table is a silence published as a silence; §11 adds four instruments |
| §1: two repeats *from eight frames* | two of them were copies | §1 withdraws the reading and names the three consecutive identical sentences |

**`outline/series.md` says the mean is a consequence and not a plan and that no volume may read its own mean as a
quality figure. The record read a mean as a standing against two other corpora. That was the fault, and it is
withdrawn rather than corrected in place, because a number that was never a number cannot be repaired into one.**

## 5. Finding four, partly repaired and partly refused, with both halves published

**The review is right that eight of ten chapters ran 724 to 1,159 words against a manuscript mean of 1,186 and a
Volume 01 mean of 5,736, and right to call that a sketch and not a scene. One concrete middle beat was added to each
of the five thinnest chapters** — 0666, 0667, 0668, 0669, 0670 — using only objects already standing in the chapter
in question: the wharf man waiting before he moves his barrow and then resting a hand on a belt where a knife is; a
stranger's crate moved a hand's width off the channel run; the people who had said they did not know sitting down
again where they had been sitting; the keeper carrying a pail out to the door; a passer-by stopping long enough to
shift a basket while the stallholder chooses not to turn his board round. **None adds a person, a name, an age, a
descriptor, a count, a figure, a decision, a document, a notice or a panel.** The batch is 9,220 words against
8,875.

**The rest is refused on the instruction this pass was given, which was not to restart the batch.** A full
expansion of eight chapters is a rewrite of the batch, and the figure that would settle the question is a
published target length for a chapter, and there is none in `outline/volume-14.md`, and this pass may not write one.
**The residual is published as a standing debt at §12 of the batch record and referred to the outline and close
phases, which are the only phases permitted to set a length.**

## 6. Finding five, refused on the evidence

**The review recommends striking `outline/volume-14.md` §20.6's second-handle rule and the eight-frames rule, on the
ground that they collide with the page. Both rules are sound and both were applied as strings by a batch, and the
fault is in the application and not in the rules.** A rule that a person is re-identified beside age and trade in
every chapter he is in, applied literally across ten chapters, has to reach for the same phrase; a rule that ten
chapters are built from eight frames, applied literally, has to build the same sentence twice. **Neither rule is
struck, because striking them would leave a prompt that says *identify people* and gives a writer nothing to hold,
and the next batch would invent a worse device.**

**What changed is the form they are given in.** §7 of `workspace/volume-14/batch-0003/PROMPT.md` now keeps the
identifying *content* and makes the identical *sentence* a fault with an instrument and a zero, and it says out
loud that ten frames is a pool to draw from and not a quota to fill twice. **That is a reconciliation and not a
refusal of the finding: the review's diagnosis of the cause is accepted in full and its proposed remedy is not,
because the proposed remedy would fix a symptom this pass can demonstrate was not the disease.**

## 7. Finding six, repaired, and it was the most valuable single change

**The review is right that the Batch 0003 prompt was 64 lines of pure constraint with no want, no obstacle and no
turn, and right that handing that to a writer is the mechanism that produced this batch.** §0 of the rewritten
prompt opens with what the last batch taught and why. §3a adds four fields to every card — **want, resistance,
turn, close** — with what each may hold and what each may not, and it adds them without touching the four card
prohibitions, which still bind. §7 replaces the two device lines and adds four, the fourth of which is *write the
sentence you would write if only one chapter of yours existed, then check whether any other chapter is carrying
it*, which is the whole of the fix and takes a reading rather than an instrument. §8 gives the record four figures
Batch 0002's record did not have, with the instruments as commands, because **a record that publishes a reading it
did not take is the fault this whole pass exists to stop.**

**The days, the pressures, the Adrian map, the two load-bearing decisions, the objects, the prohibitions and the
held strings in that prompt are untouched, and day 690's panel is not reprinted in it.**

## 8. Finding seven — out of bounds for any agent, and recorded as such

**The reviewer never ran as a subagent, so this loop has no independent quality gate, and no batch since Volume 13
has had one.** The dispatch that would invoke it lives in `.github/workflows/` and `.opencode/agent/`, and
`AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json` and `state/phase-ledger.json`
are all off limits to an agent. **Nothing was edited. The finding is true, it is the most important structural
problem in this repository, and the only fix for it is a human changing a workflow file.** Recorded here so that it
is not lost, and it belongs to whoever owns the dispatch.

## 9. Finding eight — out of scope, the ending untouched, and referred

The review notes that the last four volumes' constraints point at none of the ending and that the antagonist was
last seen in Volume 04, and that the runway to the Crown of Witnesses is unfunded. **Nothing was done about it.
`outline/ending.md` is not this pass's to edit, `outline/series.md` and `outline/volume-14.md` are plan files this
pass may not rewrite, and the ending is intact exactly as it was.** It is recorded as debt 3 at §12 of the batch
record so that Volume 14's outline and close phases inherit it rather than rediscover it.

## 10. The instruments this batch did not have, added to the record and to the next prompt

Four checks now exist that did not exist when the ten chapters were written, and all four are in §11 of the batch
record with the instrument, the pre-repair figure, the post-repair figure and the reading on the same row, in both
directions. They are in §8 of the next prompt as deliverables. **A check that is not in a record's table is not a
zero; it is a silence, and this batch published one as a table of zeroes for a whole cycle.**

| Check | Pre | Post |
|---|---|---|
| narrator frame | 4 | 0 |
| present-tense restatement | 9 | 0 |
| verbatim duplication, nine words or more | 7 | 0 |
| repeated closing construction | 8 | 0 |

## 11. What a later writer inherits, in one place

Days 661 to 670, one chapter to a day, all ten verified. Adrian in 0661 and 0665 only, Stage 2, both wants not
obtained, thanked by nobody, told he was right by nobody. The chalk never out of the pocket on any of the ten. The
second slate never touched by any hand but the keeper's, and never on the same shelf as the bare piece of door. The
wall above the store's board washed by nobody on any of these ten days, and no repair put a hand on it. Nothing
under the date. No second word in the column. No figure printed on any surface. Seven documents and seven notices,
named as two sevens, neither printed as an eighth. Sixteen posts and eleven withies, unmeasured, unmoved. One pail
was added in 0669 and it is a pail and not a bucket and it changes no count.

**The nearest this batch came to moving anything was a sentence about grit that would have been a discovery and was
made into a hand on a board, a board leaning on the wrong stack in 0665 that now stays leaning until somebody
lifts it, and a passer-by in 0670 who stood still long enough for the stallholder to choose not to turn his board
round. None of the three is a decision, and none of the three is a thread, and all three are published so that a
later phase does not read them as one.**
