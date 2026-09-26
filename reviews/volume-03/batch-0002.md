# Review — Volume 03, Batch 0002 (Chapters 0111–0120)

Reviewer output: `logs/batch-0002.review.log`. Writer pass: `logs/batch-0002.log`.
Scope reviewed: `chapters/volume-03/chapter-0111.md` … `chapter-0120.md`, the state files they update, `bible/power-system.md`, `bible/terminology.md`, and the handoff `workspace/volume-03/batch-0003/PROMPT.md`. **No chapter was restarted and no chapter was rewritten. Every fix is surgical, the planned plot is unchanged, and nothing in `outline/series.md` or `outline/ending.md` moved.**

**This is the first pass on this batch. The reviewer was not invoked:** `logs/batch-0002.review.log:1` reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session header is `novel-writer · space-bunny-free`. **That is the same gate failure as Volume 03 Batch 0001 and as five Volume 02 batches, and it is controller-owned: `.opencode/agent/` and the workflow are not edited by a phase. It is recorded and left alone.**

The batch arrived self-certified. Its summary §5 says *no claim of an independent review is made*, §11 lists twenty-nine checks run and eleven defects found, and §11 closes with the sentence that turned out to be the whole problem: **a change list is not evidence.** This review found **seven defects in the current phase, of which three were written into files the next batch is instructed to treat as binding, and it rejected one finding of its own.** Two of the seven reverse something the writer's own self-repair had recorded as done.

## What the review got right, and it is most of the batch

The prose is finished fiction. No meta voice, no duplicated paragraphs, paragraphs of two to six sentences with one-line beats used deliberately. Banned filler is essentially absent. Number discipline holds: the licence runs 61→70, the palm-line 110→119, the fee 52→61, the hearing 43→34, and the day-of-week and day-25+N / day-90+N conversions are correct wherever spot-checked. One System panel in ten chapters, in plain language, put its cost in the grammatical position a cost goes, answered by a non-Adrian in four seconds and paid within a day. **Adrian gains nothing: no working, no mark, no roster, and the volume's midpoint is paid for by his own competence rather than a fault in him.** Chapter 0116 is a real mid-batch reversal, 0118 is a genuine emotional payoff that settles nothing, 0119 is a genuine reversal that is not a victory, and 0120 closes with earned forward pull. No chapter ends mid-action. **All of that was preserved and none of it was touched.**

---

## Findings 1–3 — three faults a state file hid rather than caught

**These three are the reason this pass was worth running, and they share one shape: the state layer was quietly right and the page was quietly wrong, or the state layer repeated a page that was wrong. A state file that agrees with a wrong page is not a check, and four files agreeing with each other is not four checks.**

### 1. The word count in the batch's payoff was wrong on the page, and four state files had normalised it

`chapters/volume-03/chapter-0118.md:83` closed the chapter with *a slate with a child's handwriting on it in two blocks, one of which is **eighteen** words long.* The block is the second one, and the same chapter says **twenty-eight** at line 29 and counts it. Under the binding convention, the block is 28 orthographic words.

The damage was in the spread, not the page:

| File | Was | Now |
|---|---|---|
| `chapters/volume-03/chapter-0118.md:83` | eighteen | **twenty-eight** |
| `chapters/volume-03/chapter-0120.md:85` | *are not the eighteen* | **fixed in the slate repair, finding 2** |
| `state/chapter-summaries.md` | *not the twenty-eight* | left as it was, and it is now true |
| `state/continuity.md`, word-count device | twenty-eight | correct, no change |
| `state/character-state.md` | twenty-eight | correct, no change |
| `bible/terminology.md` | twenty-eight | correct, no change |

`state/chapter-summaries.md` had silently rewritten the page's *not the eighteen* into *not the twenty-eight*. **That is the fault worth naming: a summary that quietly corrects a page error cannot be used to find one, because it will always agree.** The page is now fixed and the state layer follows it.

### 2. Two slates were conflated in the last line of the batch

Chapter 0118 goes out of its way to establish that the six-word question and the twenty-eight-word answer are on **different slates**: the answer is written *on the flat of a slate that has nothing on the other side*, and a girl of seventeen says *it is not* the same slate when she is asked how she knows.

`chapters/volume-03/chapter-0120.md:85` then closed the batch with *a slate face down on a bench … the back of it has a child's handwriting on it, and the six words on the back of it are not the eighteen.* **The distinction the previous chapter insisted on was erased in the last line of the batch**, and the batch's final image is the one a reader keeps.

**Fixed on the page.** The face-down slate now has nothing on the other side and the six words are on the back of another of the boy's three, and nobody turned either of them over. The irony improves: the boy leaves the answer face down, and the answer to the other question is face down somewhere else, and there are four slates in a city of nine hundred people and one of them belongs to a docker who cannot read.

### 3. A question the book had already answered was denied unanswered three times, and the denial was carried into the next batch's prompt as binding

`chapters/volume-03/chapter-0110.md:43–55` — a boy of nine asks *who is going to be told?* on the sixth mile, and a man of thirty-two **answers it in about four seconds**: *That is the hearing.* Then *We will stand there.*

Against that: `0111:107` (*nobody answered it, and it has not been answered since*), `0118:13` (*nobody has answered it*), `0120:85`, and — as instruction, not narration — `workspace/volume-03/batch-0003/PROMPT.md:46` and `:89`. **A later batch would have inherited it.**

**Fixed in all five places, and the true version is the better one.** The answer exists, it is on the boy's slate and in no book, it has never been entered anywhere, and it has not been improved on or repeated. What remains open is not the answer but the fact that there is nowhere to put it, which is the same beat with a person in it.

---

## Findings 4–7 — four faults in the prose

### 4. A person merge, and it is the same merge this series has already made once

`chapters/volume-03/chapter-0118.md:13` enumerated *three questions asked in this city* and gave the first to the boy of nine: *on the thirty-fifth day of the new month, which was the sixtieth day of the flood, and it was three words and it was about a man he had never met.*

Those are **Curtis Okonkwo's**. `chapters/volume-03/chapter-0104.md:9`: *Curtis Okonkwo, twenty, of the second list, who came out of a floor on the twenty-fifth day of this flood and has said three words since, on a stair on the thirty-fifth day of the new month, which was the sixtieth day of the flood.* Chapter 0060 adds that he asked a question that *is not the same question* the boy asked.

**The batch summary §7 item 7 congratulates itself for not merging Curtis with a woman of twenty-nine. The same merge was made with a nine-year-old, two sections later, by a writer who had read §7 item 7.** Fixed on the page, and **§7 item 7 now says so, because two merges in two consecutive batches is the class of fault and not the instance.**

### 5. Chapter 0120 re-ran an event that had already happened, and five state files recorded the duplicate as canon

The season of ninety-one acres out of a hundred and forty **was settled in on day 85** — `chapters/volume-02/chapter-0085.md:3, 9, 89, 113`: *at a gateway, in daylight, at about the eighth hour of the morning … a number was said once and then not said again*, said by **Elsa Skell, forty-four, who works the bottom field**. Chapter 0120 itself carries the contradiction in its own ledger: *The field was not paid on the first of March, which was the eighty-fifth day of this flood, and that is thirty-five days ago.*

**The batch's closing beat was a second settlement presented as a first.** The review's own observation is the diagnosis: the irony sitting in plain view — the rule under the eleventh line has been empty since the day a person settled it in — was unused.

**Fixed on the page, and the repair is better than the beat it replaced.** Chapter 0120 now says the season **has been settled in a second time in thirty-five days**, names the first settlement on its own terms, and a man of thirty-two states the difference as the entry: the first was a person and could be asked whether she would have it, this one is a rule under a line and cannot be asked anything, and **the rule under the eleventh line was ruled and empty on the first of March as well.** The woman of twenty-four's line now says explicitly that she is *not* counting the first of March, because on that day the woman settled it in herself. A story about a rule deciding a field is a good scene; a story about a rule re-deciding a field that a person already decided, in front of that person, while everybody in the room knows it, is a better one and costs eleven lines.

**Propagated to** `state/current.md`, `state/continuity.md` item 20, `state/chapter-summaries.md`, `state/character-state.md` (Elsa Skell), `state/batch-summaries/volume-03-batch-0002.md` §1/§2/§5, `state/open-threads.md` item 13, `bible/power-system.md` §21.6, `bible/terminology.md`, and the Batch 0003 prompt item 8.

### 6. A duplicated line with the speaker swapped, and a run length that was not checkable

`chapters/volume-03/chapter-0119.md:27` and `:31` — the woman of about thirty-four says *I have been asked for a translation three times in nineteen days and the answer is the same every time*, and then says it again four lines later with *this is the fourth* swapped in. **The batch summary records cutting this exact defect out of Chapter 0113 during the writing run.** Line 31 is rewritten.

`chapters/volume-03/chapter-0115.md:93` said the twenty-fifth reading had not been taken *for the fifth day in a row*. It has not been taken since the first of March, which is the eighty-fifth day of the flood, so on day 115 it is the **thirtieth** day. Now thirty.

**And the batch summary's own claim about that figure is withdrawn.** §11 item 10 said the change made the figure *checkable on the page*. It did not — the figure was not checkable from anything, and the claim about the check was itself an unverified check. **A claim that a figure is checkable is a figure and has to be checked.**

### 7. A convenient monopoly, a shape collapse, and a count that contradicted its own chapter

Three smaller prose faults, all fixed:

- **`chapters/volume-03/chapter-0119.md:59`** — *I am the only man in four hundred miles who can do this*, two lines below a Crown Law scholar who has read every book that office keeps. It contradicted the chapter's own better argument at line 23 and the prompt's stated midpoint. Replaced with the defensible and more frightening version: **he is the only person *in that room*, and nobody teaches what he knows, and that is what makes it dangerous rather than rare.** Line 89 carried the same claim and is fixed the same way.
- **`chapters/volume-03/chapter-0119.md:73`** collapsed the third instrument of the seventeenth day of the new month into its second answer of the twenty-second. **Chapter 0116:39 keeps them apart on the page**, and `PROMPT.md:64` forbids collapsing them. Now three shapes, named separately, in the order the notary says them.
- **`chapters/volume-03/chapter-0114.md:3`** said forty men stood under the near gate and `:23` said there were thirty-nine of them, and `:73` said forty turned up. The ledger, the two speeches and the closing paragraph now all say thirty-nine. **The one surviving "forty" is a claim about what the whole crew is owed, which includes the man who did not come, and that is correct.**

**Also fixed on the page from the same review:** `chapters/volume-03/chapter-0112.md:71` said *nobody in Aurel has ever heard of Nine Elms*, which contradicts a Crown letter sent **to Nine Elms by name** (`state/continuity.md`, Political weather) and Darrel Quist riding out to Nine Elms in daylight on the levy horse (`chapters/volume-02/chapter-0069.md:21`). The line now uses the letter — an office that already has the village by name and has a letter about an undertaking that is void, and a letter is a thing it can hold and a chalk mark is not.

---

## The finding this review REJECTED, and it is the one to carry forward

**The review reported: `chapters/volume-03/chapter-0120.md:33` puts the woman of forty-eight's owed question on the hundredth day of the flood, and the page for it is `chapters/volume-03/chapter-0106.md:21`, day 106, and "Chapter 0100 does not mention her."**

**Chapter 0100 is `chapters/volume-02/chapter-0100.md`, and it does mention her, and it is the hundredth day of the flood.** Volume 02 runs to Chapter 100, so Chapters 0051–0100 live in the `volume-02` directory and Chapters 0101 onward live in `volume-03`. Chapter 0100's third line: *a question that this city owes to a woman of forty-eight in a fourth house eleven miles away was entered on that page as unasked, on purpose, with a date on it.* Chapter 0106 refers back to it.

**The page was right, the review read a Volume 03 path for a Volume 02 chapter, and nothing was changed.** This is the third time in this repository that a *the earlier chapter does not say this* finding has turned out to be a path error. **The rule that follows: find the file before concluding that a fact is not on the page.** It is now written into `state/current.md`, into `state/batch-summaries/volume-03-batch-0002.md` §13, and into the two standing instructions at the head of the Batch 0003 prompt.

---

## What the review raised that was NOT fixed, and why

**Two structural findings. Neither is an error on the page, and fixing either would have meant restarting finished chapters or inventing a relationship beat the batch did not earn. They are recorded as flags on Batch 0003 in `state/current.md`, `state/batch-summaries/volume-03-batch-0002.md` §9, `state/open-threads.md` items 34 and 35, and at the head of the Batch 0003 prompt.**

**1. Tamsin Quill has not appeared in Chapters 101–120, and is pointedly absent from Chapter 0119** — which reads aloud the line-one public act she carried privately for seven years and said in a yard in `chapters/volume-01/chapter-0024.md:87`. For the volume's primary slow-burn relationship, twenty chapters of silence around the volume's own hearing is a cost, and 0119 is the worst chapter in the batch to spend it in. **She is the one person in this city with a standing to speak about a form with one place for the count and one place for the assent, because she keeps the private copy of the eleven-line boundary table that the form turns on.** Flagged, with the instruction that her scene may not be a speech about Adrian and may not be a reconciliation.

**2. Five of the ten chapters share one shape** — 0111, 0115, 0117, 0119, 0120, each a room over a market, about nine people, a woman of twenty-four, a girl of seventeen writing, nobody improving on anything. *About four people* ~20×, *nobody improved on it* ~12×, *It is entered that* ~13×, *Nobody said anything for about nineteen seconds* 5×. **It is a real and consistent house voice, it matches Batch 0001, and it is not a fault. Across ten chapters it has become a rhythm rather than a texture.** Chapters 0110 and 0116 are the batch's two texture-breakers and there were only two. Flagged with a number: **this batch wants three or four, and a room-over-a-market scene may not outnumber the scenes that happen somewhere else.**

**De-duplicating the house voice across ten finished chapters was considered and rejected.** The phrases are the book's texture and the frequency count is the finding; editing them out of a finished batch to improve a statistic would be the same error as a state file that quietly corrects a page.

---

## The gate, which is controller-owned and which this pass does not fix

- **The reviewer is not being invoked.** `logs/batch-0002.review.log:1`. Same line as Batch 0001 of this volume and as five Volume 02 batches. Recorded in `state/open-threads.md` item 36. `.opencode/agent/` and the workflow were not edited.
- **`state/phase-ledger.json` is stale and unused.** Still `phase-000-bootstrap`, `status: "planned"`, one entry, after fourteen batches and a hundred and twenty chapters. Not edited.
- **The checks in the batch summary were run against the summaries and not against the page**, which is how findings 1 and 4 got through a self-certifying pass that lists twenty-nine checks. **Findings 1, 4 and 5 are all cases where the page and the state layer agreed with each other and were both wrong**, or where a state file was right and the page was wrong and the self-check read the state file. **The check that would have caught all three is the one §11 does not list: read the sentence, count the words, and open the earlier chapter by path before believing a date.**
- **The repair pushed Chapter 0120 to 3,200 words, exactly the top of the `PHASE_SYSTEM.md` band.** It was trimmed twice to get there and the figure is honest, and **a repair of this kind can quietly undo a length discipline.** The prompt now says to re-count after a repair rather than at the end.

## Re-checks run after the repair pass, all clean

- **`grep -o '\*\*' | wc -l` per file: all ten even.** A repair introduced one odd span in Chapter 0120 and it was caught on read-back.
- **No duplicated paragraph over 120 characters across the ten files.**
- **Every claimed word count re-counted from the page:** nineteen (0113), thirteen (0114), four for *mind the low stone* (0114), four for *What is this about* (0117), five for *A figure and a decision* (0120), twenty-six and twenty-eight for the two blocks (0118). **All seven are correct.**
- **Lengths re-taken after the repair:** 2,721, 2,549, 2,556, 2,663, 2,725, 3,090, 2,575, 2,634, 3,077, 3,200 — median 2,692, all inside the band.** `state/batch-summaries/volume-03-batch-0002.md` §12 and the Batch 0003 prompt both carry the post-repair figures and say so.
- **The Batch 0003 prompt's four inherited errors are fixed** — *two days* → five (the box came up on day 116), *six weeks* → five, a *man of thirty-nine with a hand that will not close* → thirty-one with the man of thirty-nine named as a different person, and the six-words-unanswered error from finding 3.
