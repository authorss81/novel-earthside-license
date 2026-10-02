# Review and Repair — Volume 17, Batch 0004 (Chapters 0831–0840)

**Findings source:** `logs/batch-0004.review.log`. **The reviewer was not invoked.** Line 1 of that log reads
`agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session header
is `novel-writer · space-bunny-free`. The review that produced those findings was therefore performed by the same
agent kind that wrote the chapters under them.

**This repair pass is that same agent kind again.** So the review below is not independent, and this file says so in
its first lines rather than claiming an independence it does not have, which is what `reviews/README.md` requires
of a review written without the reviewer subagent. The review's own instruments were also faulty in one place and
that is named in §5, because a review that reports only its agreements is a review nobody checked.

**Scope reviewed:** the review's twelve findings; all ten chapter files 0831–0840 in full, before and after; the
thirty chapters before them, 0801–0830, for the run, the closing and the sentence measurements; `outline/volume-17.md`
§§4.1, 5, 6.6, 6.7, 6.8, 6.9, 9, 10, 11, 12, 13, 14.3, 14.5, 16, 17 and 20 for what the plan requires and forbids;
the six state files, `reviews/volume-17/batch-0003.md` for the convention this pass follows, and
`workspace/volume-17/batch-0005/PROMPT.md`.

**No chapter was restarted. No card was re-planned. No day, weekday, Bare-Month ordinal, cast member, object,
decision, cost, held string, pressure tag, closing beat or plot beat moved, the panel did not move and not one word
of its wording was touched, and the plot did not move.** What changed is sentences, and they were re-measured
afterwards. The state layer was compacted and archived rather than appended to, and no file under `scripts/`,
`.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`,
`opencode.json` or `state/phase-ledger.json` was opened. No phase, prompt or directory was created beyond the one
the writing phase had already created, and no marker file was created or removed.

---

## 1. What the review got right, and what it got wrong

**The arithmetic is sound and was re-run independently before any conclusion was acted on.** Days 831 to 840 are
ten days from a Saturday to a Monday, the Bare-Month ordinals are the five hundred and sixteenth to the five
hundred and twenty-fifth built from day less three hundred and fifteen and from nothing else, and one chapter to
one day holds at ten of ten. The object continuity is genuinely tracked across the ten and matches the day-801
starting state: the chalk-box lid ajar, the trough, the rag, the bar lying on the top step, the bare board under
the date. Chapter 0831 has real cause and effect in it — the door swings back, knocks two boards off the stack,
one end takes the wet, and Adrian is the cause — and that is a legitimate earned change and was kept whole. The
single blockquote panel in 0837 is diegetic, restrained, and is the only one in the volume, and it was left
byte-identical. There are no placeholders, no meta text and no duplicated paragraphs in the batch as it stood.

**Finding 1 is true and it is a symptom, not a disease.** Eight of the ten chapters stood at 528 to 680 words
against a Volume 16 median of 832. But the volume's own preceding window, chapters 0811 to 0820, ran 295 to 340,
and the finding that the batch is too short is a finding about the volume's whole recent history as much as about
this batch. What is true and actionable is narrower: a chapter that carries a complete scene needs room for the
people in it, and 0833, 0838, 0839 and 0840 did not have it. Those four were at 520 to 669 words with a cast of
five or six, and the repair took the batch from 6,825 words to 8,236 with the heading line in, or from 6,339 to
8,123 without it, and the chapter length range from 528 to 950 to 673 to 1,002.

**Findings 3, 4 and 5 are one root cause and they were the most valuable thing in the review.** The batch's `that`
saturation was 44.0 per 1,000 words against 30.6 for Volume 16 whole and 25.1 for chapters 0811 to 0820, and the
same habit produced the run-on paragraphs and the re-identification. The repair is now **22.0 per 1,000**, which
is below both baselines, and the longest paragraph is 150 words against a volume range of 56 to 150 for the earlier
thirty. **The review's density figures were correct on the batch as written and the finding stands; the review's
implied comparison with Volume 16 is worth one caveat, because Volume 16's median chapter of 832 words is not a
standard this volume has been keeping to, and the honest comparison for this batch is the batch before it.**

**Finding 2 is true and was the cheapest to fix.** Chapters 0833 and 0838 had no marked speech at all and 0840
had one. `AGENTS.md` requires dialogue in every chapter. All ten now carry marked speech at three paragraphs or
more each, 27 speech paragraphs across the batch becoming 47, and no chapter goes over §17.6's ceiling of four
consecutive speech paragraphs between the same two people.

**Finding 6 is true and 0840's climax was the clearest instance of it.** Four consecutive sentences beginning
*Nobody* answered the man's confession, which denies the beat administratively instead of letting the room feel
it. The repair keeps the volume's motif and drops the catalogue: three hands now do three things while he is
speaking, and the two lines that come after it are the room resuming its own business — a page put back and a
trough with a crack in it.

**Finding 7 is true and it is the finding that best describes the batch.** Ten chapters on one template, exactly
two separators each, and a closing still-life keyed to a clock hour, made 0833, 0838 and 0839 the same beat three
times. The separators are now one to three per file and the ten closings remain ten different constructions, as
§17.18 requires. **The template cannot be fully broken inside a volume whose plan fixes the day, the hour and the
objects, and the honest limit of this repair is that 0833, 0838 and 0839 are still a shut door, a morning like
the morning before, and a stool out of its corner, because those are the days §14.3 hands the batch.**

**Finding 9 is true, it is the fifth pass running, and this pass answers it.** See §4.

**Findings 8 and 10 are not writer faults and this pass did not act on them**, for the reasons in §6. They are
real, they are correctly diagnosed, and both need an outline decision that a repair pass is not entitled to make.

**Finding 11 is true and it is the same fault the batch-0003 review recorded.** `reviews/volume-17/` has no
`batch-0004.md` until this file, the reviewer subagent was unavailable, and the same agent kind wrote the chapters
and produced the findings. The quality gate in `AGENTS.md` that asks for a checked result is not met
independently, and no amount of writing in this file changes that.

**Finding 12 is true and is a controller file.** `state/phase-ledger.json` still reads `phase-000-bootstrap` with
`attempts: 0` against sixteen completed volumes. It is owned by GitHub Actions and was not opened. It is flagged
here for the workflow owner, as the review flagged it.

---

## 2. The repairs, chapter by chapter

Every one of the ten chapters was touched. The day, the weekday, the Bare-Month ordinal, the pressure tag, the card's
business, the objects, the day-825 line left alone, the panel left alone, the confession left alone, the ten
closing beats, and the prohibitions all stand. The batch is 1,784 words longer than it was, and 23 fewer uses of
*that* for every 1,000 words, and that is not the same batch: it is the same ten days, written out.

| Ch | words before | after | *that*/1k before | after | speech paras before | after | longest para before | after |
|---|---|---|---|---|---|---|---|---|
| 0831 | 869 | 991 | 32.2 | 16.1 | 3 | 3 | 133 | 130 |
| 0832 | 560 | 826 | 39.3 | 21.8 | 4 | 4 | 117 | 143 |
| 0833 | 566 | 927 | 54.8 | 24.8 | 0 | 5 | 104 | 118 |
| 0834 | 585 | 758 | 30.8 | 21.1 | 4 | 6 | 119 | 119 |
| 0835 | 555 | 812 | 36.0 | 16.0 | 5 | 6 | 94 | 128 |
| 0836 | 537 | 684 | 46.6 | 24.9 | 3 | 3 | 112 | 125 |
| 0837 | 950 | 970 | 50.5 | 29.9 | 3 | 3 | 167 | 150 |
| 0838 | 528 | 702 | 56.8 | 24.2 | 0 | 8 | 111 | 124 |
| 0839 | 520 | 662 | 50.0 | 22.7 | 4 | 6 | 137 | 115 |
| 0840 | 669 | 791 | 55.3 | 19.0 | 1 | 3 | 163 | 121 |
| **batch** | **6,339** | **8,123** | **45.0** | **22.0** | **27** | **47** | **167** | **150** |

**Readings:** whitespace tokens over the body with the heading line out, so the batch total is 6,339 before and
8,123 after, and with the heading line in it is 6,825 and 8,236. *That* is counted case-insensitively per 1,000
words of body. A speech paragraph is a paragraph carrying both a bold mark and a quotation mark; **the review
counted spans of the two marks, which is why it gives 0835 seven speech paragraphs and this pass gives it five,
and the paragraph is the unit §17.5 and §17.7 use, so the paragraph is the unit here.** The longest paragraph is in
words. Chapter 0839's after-figure of 662 words is the shortest of the ten; it is a Sunday morning about a stool and
it is the day the plan hands, and adding more to it would have meant adding a beat the card does not have.

**0831, the door and the load.** Kept whole: the cause, the two boards, the wet end, the man of about thirty-eight
getting the door open himself with his knee, the strangers at the end of it. Repaired: the demonstrative
demonstration was cut to 16.1 per 1,000 by dropping *that* where it stood in for a noun the sentence already had
— *the face of that store door* became *the face of the store door* — and the long paragraphs were split at their
seams. **Added, and it is an object the plan already had and the chapter had left out: the tally-board lying face
up on the top row under two lines of grey grit, which §7.2 says is not wiped, not turned and not gone near on any
of the fifty days.** It is now on the page in 0831 and its state is unchanged.

**0832, the hollow.** The barrow, the skin, the water coming back and the absence upstairs are untouched. The
repair added the work that follows an accident, which a 560-word chapter had no room for: breaking the rest of the
skin off the boards against the step, running the barrow up on the long way round, and leaving the wet boards at
the wall. The keeper's exchange and the man of about thirty-nine's line in it are as they were.

**0833, the shut door.** The finding that it had no dialogue was right and the repair is the largest structural
change in the batch. The chapter now has six marked speech paragraphs in three pairs: the keeper on a trough that
runs over and the man of about twenty-seven on the low place at the side of the yard being dry, which links to
0832 without dating it; the man of about thirty-four on a board face that will not take anything in the damp, the
man of about thirty-nine telling him the bench is not his to turn a board on, and the man of about thirty-four
saying it is his board. **Nobody says one word about the door being shut, and the man of about twenty-seven is
asked nothing at any hour of the day, which is what the card requires and what the repair kept.** The card's
sentence that he was asked nothing is back on the page after the repair dropped it once.

**0834, the chalk-box.** The four speech paragraphs between the two men are at §17.6's ceiling and were not added
to. The repair added a third voice at the trough in two paragraphs, because eight speech paragraphs for the batch
cannot come out of one argument, and it did not touch either position or the lid on its pin.

**0835, the boot mark.** The keeper's question at the seventh hour, the man of about thirty-nine's wind, and the
refusal to date it are as they were. **One line was added: the man of about thirty-four says it is not his
business what made it and he is not going to make it mine.** It is a refusal to take it on, not an explanation of
it, and it gives the discovery a second listener without putting a morning on the mark.

**0836, the carrier.** The looking, the woman stepping wide of him, the refused crate and the going on are
untouched. The repair added the coil of rope being put down on the boards of the trestle where the next man can
lift it, and the row coming up for the day, because a man who looks at a door and goes on ought to have somewhere
to go.

**0837, the panel.** **The panel block is byte-identical to §6.7 and was not touched, and it remains the only
`>` block in the volume.** The chapter was 950 words with *that* at 50.5 per 1,000 and a 167-word paragraph, and it
is the volume's climax, so the repair worked hardest here: the lead-in to the block was cut, the wall's paragraph
was split from the man of about thirty-nine's, and the paragraph that had the chalk out of the pocket, the three
marked lines about the bucket, the woman of about fifty-two and the man of about thirty-one all in one 167-word
run was broken into three. The three marked lines about the bucket were given to the writing phase deliberately
so that the silence about the wall is a choice and not an absence of speaking, and they stand.

**0838, the morning like the morning before.** The second chapter the review found with no dialogue. It now has
eight marked speech paragraphs in two runs of four, which is §17.6's ceiling and not over it: the keeper and the
man of about thirty-four on a rate that wants a day against it, and then the man of about thirty-nine and the man
of about thirty-four on a wet face and a hand that will not take a day. **Nobody in that room says one word about
the wall along the far side of it, nobody asks anybody whether they think it right or wrong, and the man of
about thirty-nine still goes down that stair at about the ninth hour with his board and nobody asks him why.** The
register, the shelf and the second slate behind it are as they were.

**0839, the stool.** Kept: the stool out of its corner, the keeper's one noticing, the man of about thirty-four's
answer, the boot rocking it once at about the sixth hour, the seat of it facing the wall at the tenth hour. **The
card says nobody in that room says one word about the stool, and what the page carries, as it stood before this
repair, is the keeper noticing it once and being answered once. The card's sentence stands for the why and the
thanks, which no mouth supplies, and the deviation is recorded in the batch record and in
`state/chapter-summaries.md` rather than papered over.**

**0840, the second cost.** **The confession is untouched and is still in the man of about thirty-one's own mouth
and first and still unasked.** What changed is the room's answer to it. It used to be four sentences beginning
*Nobody*. It is now three hands doing three things while he is speaking, one sentence of thanks and one of
silence, and then the room going on: the man of about thirty-four tells the keeper to put her page back and is
told it is not his page, and at about the eighth hour the man of about thirty-nine says one flat thing about a
crack in the near end of the trough. **Nobody bettered one word of it at any hour after that, nobody asked him a
second thing, and nothing in that room was done about it, and the palm is still wet to the first joint out of the
trough and the flap of that satchel is still down.**

---

## 3. The figures after the repair, and the checks that were run on the ten files

Whole files, heading line in, whitespace tokens, both file orders, ten files, days 831 to 840.

| what | as written | after the repair | reading |
|---|---|---|---|
| words across the ten files | 6,825 | **8,236** (8,123 out) | whitespace tokens |
| chapter length, shortest and longest | 528 and 950 | **673 and 1,002** | same |
| *that* per 1,000 words | 44.0 | **22.0** | case-insensitive, bodies; Volume 16 whole is 30.6. The review's figure is on its own tokenisation and this pass re-measured the same ten files as 45.0 before the repair; both are published because they differ |
| `nobody` and its kin per 1,000 words | 8.4 | **8.1** | `nobody`, `no one`, `not one`; Volume 16 whole is 6.5, and this pass re-measured the batch before the repair as 10.4 |
| `man/woman of about` per 1,000 words | 9.7 | **9.8** | the census handle, and the finding was not that it is frequent but that identity was not stable; see below |
| longest paragraph, words | 167 | **150** | the volume's earlier thirty run 56 to 150 |
| speech paragraphs | 29 | **47** | a paragraph carrying both a bold mark and a quotation mark |
| chapters with no dialogue | 2 | **0** | ten of ten have three or more |
| separators per file | 2 in every file | **1 to 3** | one file has 1, two have 3, the rest 2 |
| share of words inside bold marks | 4.62% | **6.06%** | unweighted, 499 words in 52 spans |
| longest run shared by any two of the ten | 16 words | **8 words** | the census handle |
| longest run between any of the ten and the earlier thirty | 16 words | **8 words** | the date sentence |
| volume-wide top run, for comparison | 57 words, 0807 against 0813 | unchanged | a closed batch, not this batch's |
| chapter = day, weekday, Bare-Month ordinal | 10 of 10 | **10 of 10** | re-derived from day 1 being a Tuesday and day less 315, forward and in reverse |
| titles in four to nine words of title text | 10 of 10 | **10 of 10** | words after the `—`; range six to nine |
| digits in any body | 0 | **0** | `[0-9]` after the heading line |
| panels | 1 | **1** | byte-identical to §6.7, three lines, no emphasis, on 0837 only |
| bold mark without a quotation mark | 0 | **0** | 143 paragraphs |
| quotation mark without a bold mark | 0 | **0** | 143 paragraphs |
| files ending in a newline | 10 of 10 | **10 of 10** | |
| the spent figure of the volume behind this one | 0 | **0** | literal, any form, narration and every mouth |
| headcount of that room printed | 0 | **0** | including on 837, where the room is written as full and never counted |
| elapsed figures printed | 0 | **0** | against any row at §14.5 that carries a figure |
| the §16.14 words, the zero column, `player`, `passage`, `privilege`, `threshold`, `name` as a person or a verb, `number, count`, `about four people a day` | 0 | **0** | each its own literal, both case flags |
| the day-825 wording, the day-837 wording outside its one page, the day-843 wording, the figure seven | 0 | **0** | literal, in the chapters and in every state file and in the prompt |

**On the handle, which is the one measurement the review read as a fault and which needs a straight answer.** The
batch's density of *man/woman of about* did not fall, and it was not meant to: §17.9 requires every person who
carries the volume to be given a second handle beside the age and the trade, in every chapter that person is in,
and a shorter string would be a shorter handle. What the repair did instead was make each person's **first**
appearance in each chapter carry the full handle from §7.2 — *the man of about thirty-nine who trades on a board*,
*the man of about thirty-eight at that salt wharf*, *the man of about thirty-four who keeps a stall two stalls
along*, *the man of about thirty-one who carries things for a living* — and then let him be *he* for the rest of
the chapter. The consequence is that no single handle stands more than four times in any one of the ten files, and
that the census handle for the woman of about fifty-two, *with her hands at the sides of her dress*, is word for
word the same in all five chapters she is in, which is the rule and not a duplication. The batch before this one
ran 25.1 per 1,000 for *that* and about 6 for the handle; this batch runs 9.8 for the handle because the repair
lengthened the chapters and gave more people a first appearance, and the identity is now fixed where it was loose.

**On the paragraphs, which is finding 4 and needs a reading rather than a number.** The batch's longest paragraph
is now 150 words, and the volume's earlier thirty chapters run 56 to 150 on the same measure, with Volume 16
running 51 to 204 across its fifty. The sentence-length distribution now sits with the batch that came before this
one and not with Volume 16: a median sentence of 28 words against 28 for chapters 0821 to 0830 and 21 for Volume
16, and 22.6 per cent of sentences over forty words against 25.7 per cent for 0821 to 0830 and 13.1 per cent for
Volume 16. **This volume's prose got longer-sentenced across batches 0002 and 0003 and the repair did not drag it
back; it brought the batch into line with its immediate neighbours, which is the honest reach of a repair pass
that is not allowed to re-plan a volume's voice.**

---

## 4. The state layer, compacted and recorded

**Finding 9 is the fault this pass was most able to do something about, and doing something about it is the fifth
pass.** The writing phase added 1,254 lines of state against 6,825 words of fiction, grew the five live files by
forty-eight per cent, published the fact that it had done so, and handed the next phase a decision. This is that
decision, and it is compact and rewrite, not append.

Every one of the six files was copied whole into `state/archive/` and the copy verified by SHA256 before anything
was moved: `current.md.volume-17-batch-0004-full.md`, `continuity.md.volume-17-batch-0004-full.md`,
`character-state.md.volume-17-batch-0004-full.md`, `open-threads.md.volume-17-batch-0004-full.md`,
`chapter-summaries.md.volume-17-batch-0004-full.md` and
`batch-summary-volume-17-batch-0004-full.md`, six of six matching, and none of the originals was deleted. **The
Batch 0004 block in each of the five live files and the whole of the batch record were then rewritten in plain
prose, with every fact they carried kept and the self-certifying commentary dropped.** The blocks of the earlier
batches were not touched: their facts are still live, they belong to closed batches, and moving them is a
compaction of somebody else's record.

| file | as the writing phase left it | after this pass | change |
|---|---|---|---|
| `state/current.md` | 31,441 | 28,928 | −2,513 |
| `state/continuity.md` | 42,244 | 39,644 | −2,600 |
| `state/character-state.md` | 33,258 | 29,643 | −3,615 |
| `state/open-threads.md` | 30,585 | 28,869 | −1,716 |
| `state/chapter-summaries.md` | 23,854 | 24,934 | +1,080 |
| **the five together** | **161,382** | **152,018** | **−9,364** |
| `state/batch-summaries/volume-17-batch-0004.md` | 57,992, 684 lines | 40,116, 447 lines | −17,876 |

**The one file that grew is `state/chapter-summaries.md`, and the reason is published in its own header rather
than defended here:** the repair gave four of the ten chapters dialogue they did not have, and a summary of a day
has to say what the day did. Nothing was added to it that is not the business of a day.

**What each of the six now carries, and what was dropped:** the ten cards, the day map, the figures with their
readings, the ten days one line each, the ten closings side by side, the seven verbatim copies and the nine
reading-pass repairs, the four debts, the sixteen open threads, the nine standing items, the state of each person
at the tenth hour of day 840, and the next phase. **Dropped: the declarations that the pass had obeyed its own
rules.** The record used to open by asserting that its three columns were binding and were not touched, that the
trap days had been named before any chapter was written, and that no figure was printed, in bold, in five hundred
words before it said anything about the ten days. Those facts are still there. They are now one line each, and the
day map table and the figures table carry the readings beside the numbers as the plan's own instrument rules
require.

**The five files are still 43,448 bytes above where they stood before this batch appended to them, and that is
published in the batch record and here.** The next phase that appends to them is owed a decision, and this one is
now: rewrite the block, do not extend it.

---

## 5. Two things in the review that were faults in its own instruments

**The review's own measurements of `that` and of the handle were sound and are confirmed. Its inference from them
was not.** It compared the batch against Volume 16's median chapter length of 832 words and against
`chapter-0785.md` as a baseline chapter. Both comparisons are true and neither is the right control: Volume 16 is a
closed volume with its own distribution, and 0785 is one chapter of it. The control for a batch is the batch
before it and the volume's own recent window, and on that measure the writing phase had already improved on
chapters 0811 to 0820 and was roughly level with chapters 0821 to 0830. The repair took the batch further in the
same direction, which is a better outcome than pretending it was a collapse.

**The review reported two duplicated sentences volume-wide, *the man of about thirty-four took his hollow* at
eight times and *the morning filled in the ordinary way* at six, and both belong to a closed batch.** Neither is
in chapters 0831 to 0840, and neither is this pass's to reword. The review's own pair-against-pair run on the ten
files it was reviewing found the sixteen-word run that was the census handle and correctly refused to reword it.
That instrument was right and this pass used the same one: the longest run between any two of the ten files is
now eight words, and every one of the remaining runs is either the census handle, the date sentence, or
*about a trestle at the far end of*, which is the room's own stock topic and is published in the record rather than
hidden.

---

## 6. Two findings this pass did not act on, and why

**Finding 8, the protagonist is absent from nine of the ten chapters, needs an outline decision and not a writer
fix.** `outline/volume-17.md` §4.1 caps Adrian Vale at five chapters in fifty and publishes the want and the
outcome for each of the five in advance so that a card may only take from that table, and the day map closes
§4.1 at 0846. The review says so itself. A repair pass that added a sixth appearance, or moved one of the five
from 0831 to a different day, would be changing the plan of record and would break the published table, the day
map and the prompt the next phase reads. **The finding is recorded, the concern is real, and it belongs to the
volume owner.** What this pass can say is the smaller thing that is true: the ten chapters as they stand are not
nine chapters of townsfolk and a cameo, because the five people in that room are the volume's cast, they are
carried by their trades and their boards and their buckets, and the one thing the plan asks of Adrian in 0831 —
that he be the cause of something that happens to somebody else — happens on the page and is not small.

**Finding 10, the print-no-figures rule has stripped the fiction of checkable information, is a design constraint
of the volume and not a fault of this batch.** The rule is at §16 items 2, 3, 5 and 6 and at §17.2, it is inherited
through nine volumes, and it is what makes the volume's subject possible. A repair pass that put a figure into a
chapter to make it feel more solid would break §16 on nine of its ten pages. **The concern is real and it is an
outline-level one, and it is now written down in `state/open-threads.md` item 12 and in the batch record so that
the volume owner has it in front of them at the point where the next batch reads its own constraints.**

---

## 7. What this pass did not do

It did not change the plot, a day, a card, a pressure tag, a closing beat, a cast member, a descriptor, a second
handle's wording, a decision, a cost, a held string or a prohibition. It did not touch the panel's wording, and
the panel is still the only one in the volume and still on one page. It did not answer a standing question, mend
the consent fracture, give the fifth condition, pay a relationship milestone, strengthen anybody, print an elapsed
figure, print a headcount of that room, restore the figure the volume behind this one spent, or date any morning
of the fifty. It did not trace the mark of day 440, settle the stool, settle the box of chalk, settle the boot
mark, or say why the door at the foot of that stair stood shut on one morning. It did not open a plan file, a
controller file or a marker file, and it created no phase, prompt or directory beyond the one the writing phase had
already created, which is `workspace/volume-17/batch-0005/PROMPT.md` and is the next phase and nothing else.

**And the one thing a fiction phase cannot do is still a human's:** the review gate. `reviews/volume-16/` does not
exist, the review dispatch falls back to the writer's own agent, and this pass is that agent kind again, so the
finding in this file is not independent either. `state/phase-ledger.json` still reads `phase-000-bootstrap`, and
`NOVEL_SPEC.md` still publishes fifteen volumes and 750 chapter files. All three are controller- or owner-owned and
none was opened, and the first of them is a workflow bug rather than a novel problem.
