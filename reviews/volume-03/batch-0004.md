# Review — Volume 03, Batch 0004 (Chapters 0131–0150)

Reviewer output: `logs/batch-0004.review.log`. Batch record: `state/batch-summaries/volume-03-batch-0004.md` (§16 is this pass, written after the fact and cross-referencing this file).
Scope reviewed: `chapters/volume-03/chapter-0131.md` … `chapter-0150.md`, the state files they update, `bible/power-system.md`, and the handoff `workspace/volume-03/close/PROMPT.md`. **No chapter was restarted and no chapter was rewritten. Every fix is surgical, the planned plot is unchanged, and nothing in `outline/series.md` or `outline/ending.md` moved.**

**This is the first pass on this batch. The reviewer was not invoked:** `logs/batch-0004.review.log:1` reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session header is `novel-writer · space-bunny-free`. **That is the same gate failure as Volume 03 Batches 0001 and 0002 and as five Volume 02 batches, and it is controller-owned: `.opencode/agent/` and the workflow are not edited by a phase. It is recorded and left alone.** The log ends mid-command, so the review's own account stops before it had written its findings down; everything below was finished by re-running its checks against the files and reading what it had already printed.

The batch arrived self-certified, and its §11 is the reason this pass was worth running. §11 says a grep for the writer's own unit of work *returns nothing in any of the twenty*, that *every clock recomputed from day 90 + N* and *all twenty agree with the arithmetic*, and that *the weekday of every day in the batch recomputed from day 1*. **All three statements were false. Nineteen findings in two passes — thirteen in the first and six more in a second pass run against the first pass's own repairs — of which seventeen are on the twenty pages and five are in the state layer, and nine of them are one fault: a figure copied out of a neighbouring chapter instead of computed, in a sentence that reads perfectly.**

## What the review got right, and it is most of the batch

The prose is finished fiction. Paragraphs of two to six sentences with one-line beats used deliberately; no chapter ends mid-action; the texture-breakers are real and are in the right places — a quay, a shut stall and a market, a gate and two hundred steps of a river wall, nine kitchens and four miles of a road, a fork and a barrow, a passenger boat — and the six room-over-a-market scenes do not outnumber the scenes that happen somewhere else. **Nobody in the volume got stronger, which is the volume's whole argument:** Adrian refuses the post and then refuses the honest version of it, says the reason once, says out loud what it costs permanently, and nobody thanks him. A woman of twenty-nine stands up who was not asked and is made the account of a thing in a room. A notary of fifty asks to be asked, gets asked by a person, and says no — to the opening, not to being asked. A Hearthguard is asked properly after twenty-seven days and asks not to be thanked. **The hearing is four hours and one room and it is exempt from the length band, and 4,908 words is a departure that §12 names rather than dresses up.** All of that was preserved and none of it was touched.

---

## Findings 1–2 — two claims in §11 that were false, found by re-running the check and not by reading

### 1. Meta language in five places across four chapters, where §11 reported the grep clean

| Page | Was | Now |
|---|---|---|
| `chapter-0143.md:13` | *it has not been moved **in this batch** and is not going to be* | *since the day that date is on* |
| `chapter-0144.md:11` | *spoken zero times **in this batch*** | *spoken zero times **since the fortieth day of this flood*** |
| `chapter-0144.md:93` | *the whole of what **this volume** is* | *the whole of what **a hearing** is for* |
| `chapter-0146.md:11` | *the whole of **this chapter*** | *the whole of **the finding*** |
| `chapter-0149.md:89` | *the reason **this batch's** last two days are not a rescue* | *the reason **the last two days before the sixty-fourth** are not a rescue* |

**The lesson is not the words.** The writing run had already grepped for *batch*, *volume*, *chapter* and *series*, caught four instances, rewritten two sentences to remove *the volume's question*, and then written in §11 that the grep returns nothing. **A check list that says *clean* is a claim about twenty files, and it is the most expensive sentence in a state layer, because the phase after this one reads it and does not re-run it.** §11 now says what the grep returns and what it caught, in both runs.

### 2. A weekday wrong inside a chapter whose opening weekday is right

`chapter-0134.md:75`: a notary of fifty says *I am not going to be angry in a room **on a Sunday** about four lines and a chair.* The chapter is the forty-fourth day of the month after this one, which is the hundred and thirty-fourth day of the flood, and **day 134 is a Tuesday** — recomputed from day 1 being a Tuesday, and confirmed independently by Chapter 0049 (day 49 a Monday), Chapter 0100 (day 100 a Wednesday) and Chapter 0134's own opening sentence. It is now a Tuesday.

**All twenty opening weekdays were re-computed from day 1 and all twenty are correct**, including the four two-day chapters, and so is every weekday word inside the twenty that refers to its own chapter's day or to a dated day before it: Chapter 0135's *on Sunday* is day 132, Chapter 0139's *since Friday morning* and *since Saturday* are days 137 and 138, Chapter 0147's *Saturday* and *Sunday* are days 145 and 146, Chapter 0148's Monday through Thursday are days 147 to 150 and its *on a Saturday* is day 145, and Chapter 0150's *the ordinary work of a Tuesday* is day 134, the day the clerk filled in the form. **The point is that §11's weekday claim was half true: the openings had been done and the insides had not.**

---

## Findings 3–6 — the copied-figure family, which is nine of the eleven on the pages

**The batch's voice keeps the flood's day count in the shape *in a hundred and thirty-eight days*, so a figure lifted out of the wrong chapter is indistinguishable, on the page, from a figure that is right. That is why these survived a run that had already caught four faults of this family in an earlier batch, and why a reading cannot find them and a subtraction can.**

### 3. The batch's headline figure was Chapter 0138's day number, and it had been carried into eight files

*In a hundred and thirty-eight days* stood four times in Chapter 0150 — which is the hundred and fifty-fourth day — and had propagated to `state/current.md`, `state/open-threads.md`, `state/continuity.md`, `state/character-state.md`, `state/chapter-summaries.md`, `state/batch-summaries/volume-03-batch-0004.md`, `bible/power-system.md` §23 and `workspace/volume-03/close/PROMPT.md`. **Chapter 0138 is the hundred and thirty-eighth day. The figure was walked backwards out of the wrong chapter and then believed in eight files.**

The four instances are now four different numbers, because they are four different measurements, and every one of them is recomputed from a day that is on a page:

| Page | Measurement | Anchor, on the page | Figure |
|---|---|---|---|
| `chapter-0150.md:3` | the first asking in | the fifth asking, written on a slate on the thirty-first and not delivered | **thirty-three days** |
| `chapter-0150.md:97` | six askings inside | the twenty-sixth, on which she entered that she would like to be asked, to the sixty-fourth | **thirty-eight days** |
| `chapter-0150.md:99` | her own answer, in her mouth | the slate on the thirty-first | **thirty-three days** (was twenty-eight) |
| `chapter-0150.md:101` | her name said in a room | she last said it herself in a room on the hundred and sixteenth day, which is Chapter 0116's page | **thirty-eight days** |
| `chapter-0150.md`, ledger | days spent building the instrument | the flood | **a hundred and fifty-four days** (was a hundred and thirty-eight) |

**Thirty-eight is now right twice over and by two different routes**, which is a coincidence of this batch and not a method. The state layer now carries both figures with both anchors named, and `state/current.md` already said *the notary's not-knowing, carried for thirty-eight days* while six other files said a hundred and thirty-eight — **a state layer disagreeing with itself in seven places about one figure is how this was found.**

### 4. The same corruption, smaller, three more times — and one that made a sequence checkable

- `chapter-0146.md:85` and `chapter-0147.md:81`: *nobody has asked her a sixth time **in a hundred and twenty-five days*** and ***in a hundred and twenty-six days*** were elapsed counts from the slate on the thirty-first day with *a hundred and* stuck on the front. They are now **twenty-five** and **twenty-six** days, and with Chapter 0150's thirty-three **the three chapters now carry a sequence a reader can check: twenty-five, twenty-six, thirty-three.**
- `chapter-0136.md:79`: a man of thirty-two's entry said he had not asked one person one question *in a hundred and thirty-five days* in a chapter that is the hundred and thirty-sixth, **and whose next sentence says a hundred and thirty-six.** It is a hundred and thirty-six.

### 5. One elapsed count with its anchor named in the same sentence, and the sentence was wrong

`chapter-0150.md`: *I lost it in about four minutes in this room **on the second day of the month after this one** and it has not come back in **a hundred and thirty-two days**.* The second day of the month after this one is the ninety-second day of the flood, the page says so, and a hundred and fifty-four less ninety-two is sixty-two. **It is now sixty-two days.**

**The other hundred and thirty-two in the same chapter was left alone**: a woman of twenty-nine says she has been in a room in this city three times in a hundred and thirty-two days and has written a roll in it every week for seventy-nine of those. Seventy-nine cannot be a fraction of sixty-two, the figure is internally consistent, and it has no anchor to check it against. **A repair pass that changes a figure it cannot derive is how a batch acquires two wrong figures instead of one.** The same reasoning left *about a hundred and thirty days ago* in `chapter-0148.md` alone, where the figure is soft and points at a precedent this page does not date. **Both are on the record so that neither is re-opened.**

### 6. A figure five days after the chapter — and a state file had introduced it

`chapter-0144.md`, on the hundred and forty-fourth day: Marrow says a woman of twenty-four *has been right for **a hundred and forty-nine days***. It is a hundred and forty-four days. **This figure was written into §11 item 8 of the batch summary as the record of an earlier repair in the same chapter** — the repair that stopped the Hattie Park counter being spoken — so a state file had got the arithmetic wrong while getting the rule right, and then certified itself.

`chapter-0137.md` had the same shape: *a hundred and thirty-eight days of this city have been walking towards* on the hundred and thirty-seventh day, and **that sentence is the one the writing run put there when it cut *the volume's question* out of it.** It is a hundred and thirty-seven days. Chapter 0138's parallel sentence is on the hundred and thirty-eighth and is right and was not touched.

---

## Findings 7–8 — the prose

### 7. A byte-identical line in two chapters

*** "Say it,"** said a woman of about thirty-four who keeps a stall by the wharf.*** stood in `chapter-0136.md` and `chapter-0143.md`. Chapter 0136 keeps it, where it answers Adrian giving four reasons. Chapter 0143 now reads ***"Then say it,"***, which answers Marda Rood's *I am sixty-one and I am going to say what I do have.*

### 8. The nineteen-second refrain, which the scan will keep returning

*Nobody said anything for about nineteen seconds* stood **thirty-three times across sixteen chapters** and no chapter repeated the bare sentence twice inside itself after this pass. **It is the batch's unit of a silence and a motif and not a fault, and it is now declared as one in §11** — once bare in each of twelve chapters, a specific trailing clause on the other uses — *so that the next reviewer does not treat a motif as a duplication and spend a pass cutting it thirty-three times.* Eight bare instances were given a physical beat: a market going on under the floor, a slate put down face up, a boy turning his own slate over to look at the back of it, a hand flat on a page that is not turned over, four people looking at a barrow and nobody at the woman holding it, an empty road in both directions, a fire going over and a damper opened by nobody named, a girl not looking up, water going along a reach, a man who said he would go not getting up, and a clerk sitting on a quay edge like anybody waiting for a boat.

---

## Findings 9–10 — the state layer's own record of this batch

### 9. Six blockquotes in §8, and three of them were not the page's speeches

§8 prints six passages as the words people said. Three were verbatim. Three were not:

- The woman of twenty-nine's answer had **a whole clause inserted** — *and this city has spent a hundred and thirty-two days finding out what a piece of paper is* — and two further alterations: *what it is* for *what a piece of paper is*, and *for the next four hundred years* for *for four hundred years*.
- The woman of about sixty-one with a barrow was made to open with ***A stone that has had a page taken down is a stone that can be corrected***, **which is a sentence that is nowhere in the book.** Her page's sentence begins *And there is a difference and it took me four years and a barrow to get to it.*
- The Hearthguard's had its first sentence dropped and its second promoted into its place.

**All six are now the page's words, verbatim.** A scan of every quoted span of more than seventy characters across `state/current.md`, `state/continuity.md`, `state/chapter-summaries.md`, `state/character-state.md`, `state/open-threads.md` and the batch summary now returns **nothing that is not on a page**. **A blockquote is a claim that a person said exactly that, and a summary that improves a speech is a summary that cannot be used to check a figure, because it will always agree with itself.**

### 10. One word, in an earlier batch's quotation, found by the same scan

`state/character-state.md` had Tamsin Quill saying *I did not bring him down here to use him **for him***; the page says ***for it***, and the sentence after it had been dropped. **This is not this batch's page. It was repaired in the state file and nowhere else, because a quotation is repaired where the error is** and a review pass does not rewrite another batch's prose to match a state file that was wrong about it.

---

## Finding 11 — the two faults this pass did NOT fix, and why

Both were carried by the writing run in §14 and both were re-checked here and are **exactly as they were**:

1. **`reviews/volume-03/batch-0003.md` is not on disk.** Four state files record nine findings in it. **Still missing.** This pass did not write it: reconstructing a review record is the close phase's job by `workspace/volume-03/close/PROMPT.md`, and a pass that widens its own scope is how a repair becomes a rewrite. **It is the one fault in this repository that a later phase must not inherit silently, and the close phase is the phase that was told about it.**
2. **Chapters 0121 to 0130 carry a weekday two days out.** Chapter 0130 says day 130 is a Wednesday and Chapter 0100 says day 100 is a Wednesday, thirty days apart. **Still true.** The close phase owns the repair and has the arithmetic in front of it.

**Both are recorded in `state/batch-summaries/volume-03-batch-0004.md` §14, in `state/current.md`, in `state/continuity.md` and in `state/open-threads.md`, and the close phase will find them where it expects them.**

---

## The second pass, run against the first pass's own repairs

**A verification pass was run over the thirteen repairs above and it returned six more findings, four of them in the repairs themselves. That is the honest shape of a repair pass and it is recorded here rather than quietly folded in: the first pass declared three checks clean that were not, and one of them was the class of fault the whole pass exists to eliminate.**

### 14. The interior of three chapters was still on the prompt's drifted day map — seventeen weekday words

`workspace/volume-03/batch-0004/PROMPT.md` §"the day map" is two days out: day 133 is a Saturday, days 147–148 are Sat–Sun, 149–150 are Mon–Tue, 151–152 are Wed–Thu, and the last line of that section says **Day 154 is a Saturday**. The writing run corrected the twenty opening sentences to the founding rule and corrected nothing inside them. This pass found nine figures and one weekday, cleared the rest of the weekday words as dated back-references **without doing the subtraction**, and the verification pass did the subtraction:

| Chapter | Days | True weekdays | The interior said |
|---|---|---|---|
| 0147 | 147–148 | **Monday, Tuesday** | *the Saturday afternoon*, *not told until the Sunday*, *on the Saturday or before*, *in a gateway on the Sunday*, *could not get there on Saturday*, *on the Sunday she was in a kitchen*, *on the Sunday afternoon* |
| 0148 | 149–150 | **Wednesday, Thursday** | *started at the seventh hour on the Monday*, *at about the second hour of the afternoon on the Monday*, *took it at about the fourth hour of the afternoon on the Monday*, *sent for on the Tuesday morning*, *finished at about the seventh hour on the Tuesday* |
| 0149 | 151–152 | **Friday, Saturday** | *on the Thursday morning she came into a room* — the day **before** she stepped off a quay — and *on a Saturday* three times where the day meant is the hearing, which is a **Monday** |

**Seventeen words, all recomputed from day 1 and not from the neighbouring sentence. All seventeen are now correct, and the two day-count figures the two-day ledgers carry with *and then* are untouched, because they were never weekday words.**

**This is the same fault as the two-day drift in Chapters 0121 to 0130, in the three chapters whose openings had just been fixed, and the same reviewer that found the 0121–0130 drift cleared these.** A clearance is a check. A check is a subtraction. A reviewer who writes *verified* in a state file without the arithmetic has added a fault and called it a clearance, and this repository now has that twice.

### 15. Chapter 0147's ledger gave one day's figure where the chapter's other six counts carry both

The ledger of a two-day chapter in this batch writes *thirty-one days and then thirty-two*, *in seven days and then in six*, *seventy-eight days and then seventy-nine*. The notary's gap was the only count in the paragraph with a single figure, so *twenty-six days* was the day-147 figure standing alone in a paragraph that closes on day 148. **It now reads *twenty-six days since that slate was written and then twenty-seven, and nobody has asked her a sixth time in either of them*** — the chapter's own idiom — and the sequence a reader can check is twenty-five at 0146, then twenty-six and then twenty-seven at 0147, and thirty-three at 0150.

### 16. Two clauses this pass itself wrote were wrong against the room they are in

Both in Chapter 0142, and both were added by this pass in finding 8:

- ***The boy of nine turned the slate over and looked at the back of it as if it were somebody else's.*** Chapter 0142 had already narrated the turn — *he turned round and picked it up and turned it over and looked at it and put it down again, face up* — so this re-narrated it; and the back of that slate carries **his own six words**, while the chapter's whole point is that the **front** is blank because *the front is for other people*. The clause inverted the chapter. **It is now *the slate lay face up on the step with the writing turned away from all of them.***
- ***The man who had said it put a hand flat on the page and did not turn it over.*** The speaker of *I have not looked at it for about four days* is **the boy of nine** — the next line says *he said* and the paragraph after says *he is nine* — and the slate he has not looked at **is on a wall**, and there is no page in the scene at all. **It is now *the boy of nine looked at the middle of the road the whole time.***

**The finding is not the two clauses. It is that a repair pass which adds a physical detail to a sentence is writing a new sentence, and a new sentence has to be checked against the room it is in — which is a reading, and this pass had been treating its own repairs as arithmetic.**

### 17. A docker of fifty-eight who cannot read stood in Chapter 0143's party for one line and was not one of the party

She appears once in Chapter 0143, having the drafted page read out to her twice, three lines after the girl of seventeen had read it twice, at a fork nine miles up a road. The chapter's party is the woman of about thirty-four who keeps a stall by the wharf and the girl of seventeen, and the keeping household. **The clause now belongs to the stall woman by the wharf, who is in the scene from its first line**, and the beat is better for it: *had it read out to her twice as well, and did not pretend she had not.*

### 18. Two state figures nobody had checked against a page

- `state/batch-summaries/volume-03-batch-0004.md` §13 called it *the question he spent **a hundred and thirty-nine days** walking towards* — Chapter 0139's day number, in a file about Chapter 0150, where the page says a hundred and fifty-four. **Now a hundred and fifty-four.**
- `state/character-state.md` said he put the table back *on **the second day of the hearing***. There is one hearing and one clock and it is one day. **Now the day of the hearing, which was the sixty-fourth day of the month after this one and there is only the one.**

### 19. Two figures checked and deliberately left, and the one ledger in this batch that owes an audit

Chapter 0134's ledger says *the box is eighteen days in a room with a door* — right, day 134 less day 116 — and then that *the four lines are nineteen days old* and *the not-knowing is nineteen days old*, when the wish and the not-knowing were both entered on the twenty-sixth day of the month after this one, which is the day the box came up, and both are eighteen. It also says *one of them has been on the water for thirty-eight days*, where the case on the water left on the eighth day and the box was seventy-two days on the water, and 38 has no anchor at all.

**None of the three was changed.** Each needs a decision about what that ledger is counting, and only a reading of Chapters 0111 to 0133 can settle it, and this pass had already demonstrated what happens when an arithmetic repair is made without the reading (finding 16). **They are on the record here, in §16 item 19 of the batch summary, and in `state/current.md`, and the audit of that one ledger is owed before Volume 04 quotes it.**

---

## The two rules this pass adds

1. **A check list that says *clean* is a claim about twenty files, and it is the most expensive sentence in a state layer.** §11 said the meta grep was clean and the clocks were recomputed and the weekdays were done, and all three were partly or wholly untrue, and the writing run that wrote them had itself found four faults of two of those families. **Re-run the check; do not quote it.** This is the same rule the Batch 0001 review reached from the direction of a canon claim, the Batch 0002 review from the direction of a state file that normalised a page error, and the Batch 0003 review from the direction of a check list that found eight faults and then found four of its own class again.
2. **An elapsed count is that chapter's own day number subtracted from the day the thing happened; the day a thing happened has to be opened in the file and not remembered; and where two elapsed counts sit in one sentence, the event each is measured from has to be named in that sentence.** Nine figures in this batch were a number copied out of a neighbouring chapter, and every one of them was in a sentence that read perfectly. **Where a figure cannot be derived, it is left alone and written down as left alone**, which is the only honest position available to a repair pass and the reason two of this batch's figures are still odd on purpose.

---

## Re-checks run after the repair, all clean

- **Bold-span parity: all twenty even** — 0131 to 0150: 54, 64, 68, 66, 64, 60, 60, 64, 96, 82, 62, 78, 90, 76, 82, 52, 64, 50, 98, 108.
- **Meta terms: nothing.** *batch*, *volume*, *series* return nothing in the twenty; *chapter* returns nothing outside the twenty H1 headings.
- **Banned terms: nothing.** *Owen* 0, *Ovin Sarr* 0, *knock* 0, *of this month* 0, *of next month* 0, *of the month before this one* 0. All 265 instances of *of the month* are the in-world *of the month after this one* and its own relatives.
- **Opening weekdays: all twenty recomputed from day 1 and correct**, the four two-day chapters included. **And every weekday word inside the twenty now recomputed too, which is finding 14 and which the first pass of this review cleared without doing the arithmetic.**
- **Duplicated paragraphs over 120 characters across the twenty: none**, and the only shared sentence is the declared refrain.
- **Every weekday word in the twenty, not only the openings, adjudicated one at a time: thirteen are not one of their own chapter's days and all thirteen are correct.** Chapter 0135's *asked for a sixth time on Sunday* is day 132; Chapter 0139's *since Saturday morning* (twice), *since Friday morning*, *twice since Friday* and *I thought on Friday* are days 138 and 137; Chapter 0148's two *on a Saturday* are the market's Saturday and a Saturday four days before the chapter; Chapter 0149's four *on a Monday* are the hearing, which is a Monday; Chapter 0150's *the ordinary work of a Tuesday* is day 134, the day the clerk filled in the form. **That is the whole check, and it is thirteen arithmetic sums, and the first pass of this review wrote them up as clearances without doing them.**
- **Every *a hundred and NN days* figure in the twenty: three are not their own chapter's day, and all three are accounted for.** Chapter 0137's *built in a hundred and thirty-seven days by a city that had spent a hundred and thirty-six days refusing to* is a deliberate pair; Chapter 0148's *about a hundred and thirty days ago* is finding 5's documented exception; Chapter 0150's *a hundred and thirty-two days* is the other one. Every other figure in the twenty equals a day its chapter covers.
- **Quotations over seventy characters in the six state files and the batch summary: all on a page.**
- **Word counts re-taken on the files after the repairs and again after the second pass:** 2,858, 2,518, 2,458, 2,533, 2,460, 2,303, 2,470, 2,516, 3,193, 2,616, 2,351, 2,424, 3,096, 2,509, 2,470, 2,237, 2,340, 2,766, 3,083 and 4,908 — **minimum 2,237, maximum 4,908, mean 2,705.4, median 2,512.5**, a hundred and seventy-four and a half under the 2,687 to beat. Ten chapters changed: eight up by between eleven and forty-five words, Chapter 0147 down by one and Chapter 0150 down by eight, net a hundred and ninety-two on fifty-four thousand. **Every one of the ten is a repair and not an addition, and §12 carries both the post-review figures and the superseded ones.**

## The gate, which is controller-owned and which this pass does not fix

`logs/batch-0004.review.log:1` — the reviewer is configured as a subagent and the review prompt executes under the writer agent, **and the log was cut off before it could write its findings down.** That is the fourth Volume 03 batch and the ninth batch overall in which this has happened. It is a fact about `.opencode/agent/` and the workflow, both of which a phase must not edit. **It is recorded, and the practical consequence is on the record above: a review that runs as a second pass by the same agent finds mechanical faults reliably and has now twice found a state layer agreeing with a page that is quietly wrong.** No phase can fix the gate. A later phase can stop paying for it by re-running the checks instead of reading the check list, which is rule one above.
