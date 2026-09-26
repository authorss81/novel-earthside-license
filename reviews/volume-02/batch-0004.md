# Review — Volume 02, Batch 0004 (Chapters 81–90)

Reviewer output: `logs/batch-0004.review.log`. Writer pass: `logs/batch-0004.log`. First self-pass: `logs/batch-0004.fix.log`.
Scope reviewed: `chapters/volume-02/chapter-0081.md` … `chapter-0090.md`, the state files they
update, `bible/power-system.md`, `bible/terminology.md`, and the handoff
`workspace/volume-02/batch-0005/PROMPT.md`. No chapter was rewritten. Fixes are surgical, the
planned plot is unchanged, and nothing in `outline/volume-02.md` or `outline/ending.md` moved.

**This is the second review of this batch and it is the one with an artefact behind it.** The first
pass was made inside the writing run by the same model that wrote the ten chapters
(`logs/batch-0004.review.log:1` — `agent "novel-reviewer" is a subagent, not a primary agent. Falling
back to default agent`, session header `novel-writer · space-bunny-free`), there was no review file
and no separate commit, and the batch summary described it as *reviewed once, and the review was
independent*.

**That description was false and has been corrected in `state/current.md` and §11 of the batch summary.**
It mattered, because one of the twelve items the first pass reported as fixed was not
fixed, and it was only found because somebody looked at the page again.

## Faults in the review gate itself

**1. The reviewer is still not being invoked.** Same log line as Batch 0003, and the same session
header. The review prompt executes under the writer agent. **Controller-owned:** `.opencode/agent/`
and the workflow are not edited by a phase, so this is recorded in `state/open-threads.md` and left
alone. It is the third batch in a row this has happened.

**2. `state/phase-ledger.json` is stale and unused.** Still `phase-000-bootstrap`, `planned`,
`attempts: 0`, one entry, after ten batches and ninety chapters, while `state/current.md` reads
*Current phase: phase-003-batch-write*. Both are true on disk simultaneously.
**Controller-owned and flagged only; the file was not edited.**

**3. The first pass's self-report was the only audit trail, and it was wrong.** §11 item 1 of the
batch summary read *the seventy-eight is gone.* `git diff` shows the first pass never touched
Chapter 0081 at all. This is the second time a batch summary in this repository has asserted a repair
that the page does not carry — the first was Batch 0003's *first pass was a review*.

**The rule that follows: a change list is not evidence.**
`reviews/<volume>/<batch>.md` and the page are.

## Confirmed and fixed on the page

| # | Finding | Fix |
|---|---|---|
| 1 | `chapter-0081.md:57` — *has been in this world **seventy-eight days***, four lines above *fifty-six days* three times in the same chapter. Correct figure is **fifty-six** (out of the chapel floor on the twenty-fifth day of the flood, day 81). | **fifty-six**. This is the item the first pass reported as done. |
| 2 | `chapter-0090.md:77` — *Twelve named persons … and there is now a column for where **eleven** people are.* The list's own entries enumerate twelve. The 11→12 correction had reached four state files and not the line it was correcting. | **twelve**. |
| 3 | `chapter-0090.md:71` — *said, **in nine words**, that a stone is somebody's and you do not step on a thing that is somebody's.* The sentence is **fifteen** words. This is the batch's own binding device. | **fifteen**, and the corrected figure is now in the continuity list. |
| 4 | `chapter-0082.md:89` — *he has been quoting it for **nine days***, for a sentence said on the forty-first day of the new month, which is day 66. Day 82 − 66 = **sixteen**. | **sixteen days**, and the sentence now names the flood day in the same breath, which is the habit §12 of the batch summary asks for. **See "Checked and not actioned" below: the review also called this an invented back-reference and it is not.** |
| 5 | `chapter-0085.md:35` — *said it **about six weeks ago in a market to about nine people***, four lines after the chapter had correctly placed the same sentence under the near gate to about forty men on the twenty-first day of the new month, and contradicting `chapters/volume-01/chapter-0046.md:55`. | **thirty-nine days ago, which was the forty-sixth day of the flood, under that gate to about forty men.** |
| 5a | `chapter-0085.md:41` — *about nine people in that room had known it for **two months***, for a sentence Renna Ord names in the next line as one she has known since the twenty-first day of the new month. Thirty-nine days, not two months. | **thirty-nine days**. |
| 6 | `chapter-0081.md:55` — *on the forty-fifth day of the new month she told a woman of twenty-four **and not the man***, against `chapters/volume-02/chapter-0070.md:189`, which has her saying the second half of it **to him** on that day. The woman of twenty-four had it on the thirty-seventh. | The sentence now gives the woman of twenty-four the thirty-seventh and the man the forty-fifth, and the nine-word count moves with the second half, where Chapter 0070 puts it. |
| 7 | `chapter-0090.md:113–127` — the added close contradicted the scene above it four times. Renna had already put the date on a slate and said the date was the only thing on it; the refusal then claimed *nobody ever walks down that road at all* (refuted by the date on the slate), told the girl to *put the date on the slate* (already done), and closed on *the girl of seventeen wrote the date and nothing else*, while the roll-call credited the docker with having put a date on a slate. Four statements, one slate. | **The beat stays and the reasoning is rebuilt.** Her no is now about the *wall* getting an answer — if a girl writes down what she thinks those eight mean, then in about nine months somebody will read it and believe it, and the seven further down the road will never be walked to — which is consistent with a date already on a slate. She points at the slate rather than ordering it filled. The entry says she wrote nothing at all. |
| 8 | `chapter-0090.md:3` — *a wall above a market and **eight stones nobody has looked at***. One of the eight was read on the thirty-fifth day of the new month. | **seven stones nobody has looked at.** **This is the whole of finding 8 — see "Checked and not actioned".** |
| 9 | `chapter-0084.md:3` — *nine miles up the Reach road in a chapel over a market in a salt town **nine miles up the Reach road***, a duplicated clause, and a salt town where canon puts the **Weighers' chapel at Dray**, which is not the Salt Weavers' chapel in Saltwake and was too small. | The duplication is gone and the chapel is named, with the reason it is not the other one. |
| 10 | `chapter-0081.md:23` — *The first page, **the first page's own first page**, the four words and the four words*, a duplicated phrase, and no first page in the roll-call at `:93` or in the batch summary. | *And the first page of them carries the four words and the four words.* The list now matches the roll-call at `:93` exactly. |
| 11 | `chapter-0090.md:125` — *I have been told no four times in ninety days.* Nothing on the page records four refusals **of** her; her three refusals of the fortieth day of the new month are refusals she made. | **Now anchored to the count that is on the page**: `chapters/volume-02/chapter-0063.md:65` has her refusing a thing in about eleven seconds and having said the rule four times in sixty-three days. |

## Two more of the same classes, which the review did not name

These were found while checking the two classes this batch has the most of. Both are recorded because
the next reviewer will otherwise find them and think this pass missed them.

| # | Finding | Fix |
|---|---|---|
| 22 | `chapter-0082.md:23` — Hesper Saye says it is *the first finding in **ninety** days* that was a shape and not a fact, on **day 82**. A man has been in this world eighty-two days. This is the elapsed-count fault of §12 of the batch summary, on the page, in one of the ten chapters. | **eighty-two days**, which is the chapter's own day and the verified Batch 0003 rule. |
| 23 | `state/character-state.md` attributed the *first finding in seventy-eight days that is a shape and not a fact* to **Hesper Saye**, in two places. `chapters/volume-02/chapter-0078.md:113` has it said by **a woman of twenty-nine**, and the entry immediately below says so in as many words: *the words of a woman of twenty-nine who has never once claimed a sentence that is not hers.* That is Nadia Brandt, and the batch has already fixed two person merges of exactly this shape. | Both entries corrected. **The sentence is Nadia Brandt's, said on the fifty-third day of the new month, and it is not in Saye's mouth anywhere in the book.** Saye has her own finding, on the fifty-seventh day, with her own count. |

## Checked and not actioned, because the finding was wrong

Acting on these would have damaged canon, so they are recorded instead of fixed.

**12. `chapter-0090.md:139` — "the nineteen shapes are counted three incompatible ways."** Only one of the three was wrong, and it was not this one. The document on the wall is a fixed text, printed in `chapters/volume-01/chapter-0050.md:82` and again in `chapters/volume-02/chapter-0060.md:13`: *And the eight of the nineteen that are not the same as the others, and are further down the road, and are in a different order.* `chapters/volume-02/chapter-0080.md:135` already used the correct form, and so does Chapter 0090's closing paragraph. The one impossible statement was the opening line's *eight stones nobody has looked at*, and that is finding 8. **The correct form, now written into the continuity file: eleven of the nineteen are the same, eight are different, all eight are further down the road, seven of the eight have never been looked at, and the eighth is a name.**

**13. `chapter-0082.md:89` — "an invented back-reference; the sentence is nowhere on the page."** It is on the page, in different words. `chapters/volume-02/chapter-0066.md:105` has Nadia Brandt telling two men *you are both wrong and you are wrong in the same way … you are arguing about whether being useful is safe*, and `state/chapter-summaries.md:207` records the finding as hers: *being useful is not safe and is not unsafe, it is a description.* Day 66 **is** the forty-first day of the new month, and day 66 **is** a room with two men arguing about the wrong thing. **The date and the company were right and only the elapsed count was wrong.** The sentence has been made findable by naming the room and the flood day, which is a legibility fix and not a change of event.

**14. The 11→12 slip "has propagated into `state/current.md` and the new prompt."** It reached the prompt (finding 15 below) and not `state/current.md`, which never carried a count of the named persons. `state/continuity.md` and `state/character-state.md` were already correct, as was the page except for the one line.

**15. `chapter-0081.md:55` — the nine-word count is now a back-reference, and the first pass's removal of it would have broken the batch's own device.** Removing a count is not the same as removing an error. The count has been moved to the sentence it belongs to and is listed in the continuity file as a back-reference, so that no later chapter treats it as a countable sentence of its own.

## The next-phase prompt was rewritten, not patched

`workspace/volume-02/batch-0005/PROMPT.md` had six defects, and one of them would have cost a writer two volumes of dates.

**16. The calendar contradicted itself three ways and contradicted nine chapters of canon.** The prompt said day 91 was *the sixty-sixth day of the new month* and day 95 *the seventieth*, and separately said *the new month ended on day 85, so day 86 onward has no Nth day of the new month available* and *There is no Nth day of the new month after day 90 and a chapter that uses one is wrong.* **Chapters 0086 to 0090 all use the sixty-first to the sixty-fifth day of the new month and `state/continuity.md` makes those binding.** The root cause was `batch-0004/PROMPT.md:62`, which said *the last day of the new month is day 85* while its own day map assigned days 86–90 to the sixty-first to sixty-fifth. **The prompt now states the rule (the Nth day of the new month is day 25 + N; the sixty-fifth is day 90; nothing on the page establishes a sixty-sixth), states the forward form (the Nth day of the month after this one is day 90 + N, so day 91 is the first and day 100 is the tenth), and says in terms that the *ended on day 85* figure was wrong.**

**17. The Tuesday was mis-dated, and it moved a scene out of the batch.** The prompt said *The Tuesday was the sixty-fifth day of the new month … this is the Monday after it.* Day 90 is a **Sunday**. `chapter-0088.md`, on the Friday of day 88, says the argument about the nineteen words is *on Tuesday*, which is **day 92**. **The prompt was telling the batch that the argument had already happened and might only be reported.** It is now staged in Chapter 0092, and Chapter 0091 opens the day before it with nothing said and nothing entered.

**18. The previous batch's lengths were wrong.** The prompt said *Batch 0004 was written to that band at 3,019–3,795*, which matches nothing, including the batch summary's own §10 — and §10 was wrong too, giving 4,141 for the close and a median of 3,240, where 3,240 is not the median of that list. **Both files now carry the counts a reader gets by running `wc -w`: 3,104 to 4,239, a mean of 3,360 and a median of 3,270, with the two over-band chapters named as the two that carry a complete scene.**

**19. The 11→12 slip was in the new prompt too.** *naming eleven people is a column for where eleven people are* — now **twelve**, in both halves of the sentence.

**20. The instrument had said nobody five times.** `chapters/volume-02/chapter-0075.md:151` records **four** offers. The fifth is what Chapter 0094 stages, so the prior count is four and the prompt now says so, with the five-week window the four came in made explicit.

**21. The prompt asked for five chapters.** `AGENTS.md` requires the next prompt to be a detailed **ten to twenty** chapter prompt, and splitting the sealing of the Void, the stage and the cost across a five-chapter boundary buys no pacing. **The prompt is now Chapters 91–100 — the whole remainder of Volume 02 — with a card for every day, and it tells the next writer to create a Volume 02 close rather than another Volume 02 batch.** The five cards that existed are kept and repaired. The five new ones implement the close `outline/volume-02.md` and the last line of the old prompt already specified: two Wayhouses and an Open Hand exchange under local law with a public refusal honoured, the Concord's quarterly description going out in a wooden case with the honest useless form inside it and Roke's eighth column answered with a question and not a name, the licence's review date, and a final image that is a road.

**One plan conflict was resolved in the prompt rather than left to the writer.** The old Chapter 0091 card gave the saying of the name to Adrian. `outline/volume-02.md` gives it to Ivenn Marrow, in *Major factions* and again in *Concrete resolution*. **The outline is the plan, and it is the better scene: the most useful man in every room is the one who names the thing, and the man who already has nineteen words on a slate is not going to be handed the shape as well.** The prompt now assigns it to Marrow and says why.

## State files

- **`state/continuity.md` — the word-count list claimed to be exhaustive and was not.** It declared that *every claim of the form it is N words in Chapters 81–90 has been counted* and then left out four claims the reviewer named, and two more that nobody had named. **It is now every count in the batch, in chapter order, with the counting convention stated — an orthographic word is one word, so a hyphenated compound is one word — and with a separate short list of the four counts that are back-references to sentences not quoted on the pages that cite them, or that are deliberately never spoken.** Two entries are new to the list and were not in any finding: **four** for *nobody has asked them* (0086 and again at 0090) and **fifteen** for the boy of nine (0090, which said nine). The convention has one exception in the whole series, Chapter 0078's thirty-six, which only works if *seventy-eight* is two; that is a Batch 0003 figure and is flagged rather than re-counted.
- **`state/current.md`** — the paragraph claiming Batch 0004 was *reviewed once, independently, and repaired* is corrected, and it now points at this file.
- **`state/batch-summaries/volume-02-batch-0004.md`** — §10's figures corrected, §11 retitled so that it no longer claims independence, its item 1 corrected to say the first pass did not do what it reported, and a new §13 recording this pass and the four traps a later writer inherits.
- **`state/open-threads.md`** — the two controller-owned faults are carried forward as flags and are not fixed here.

## Standing findings for whoever writes the next batch

1. **A change list is not evidence.** Check the page, not §11.
2. **An elapsed count is that chapter's own day minus the day the thing happened, and the day the thing happened is looked up, not remembered.** Put the flood day in the same sentence as the new-month day.
3. **The word-count device is exact and the convention is now written down.** Count the sentence as it stands, including its hyphens.
4. **A fixed document printed in two chapters outranks a later chapter's paraphrase of it.** The nineteen shapes are the case in point, and the closing paragraph of Chapter 0090 is right where its opening line was wrong.
5. **Check whether a back-reference is real before calling it invented.** One of the four findings in this pass that would have cost canon was exactly that mistake, and it was made about a scene that exists in Chapter 0066.
