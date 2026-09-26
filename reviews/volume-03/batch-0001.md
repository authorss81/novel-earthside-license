# Review — Volume 03, Batch 0001 (Chapters 0101–0110)

Reviewer output: `logs/batch-0001.review.log`. Writer pass: `logs/batch-0001.log`. First self-pass: `logs/batch-0001.fix.log`.
Scope reviewed: `chapters/volume-03/chapter-0101.md` … `chapter-0110.md`, the state files they update, `bible/power-system.md`, `bible/terminology.md`, and the handoff `workspace/volume-03/batch-0002/PROMPT.md`. No chapter was rewritten. Fixes are surgical, the planned plot is unchanged, and nothing in `outline/series.md` or `outline/ending.md` moved.

**This is the review of the first batch of Volume 03, and it is the fourth batch in a row in which the review has been produced under the writer agent.** `logs/batch-0001.review.log:1` reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session header is `novel-writer · space-bunny-free`. **The findings below are real and two of them reverse the writer's own self-repair, which is the strongest evidence available that the pass was worth running. But the gate is still not a real gate, and the reason is controller-owned: `.opencode/agent/` and the workflow are not edited by a phase.**

The batch arrived with a twenty-nine-item self-repair pass already applied and self-certified. This review found **six defects in the current phase, of which three were written into files the next batch is instructed to treat as binding, and two of the three were regressions introduced by that self-repair.**

## Faults in the review gate itself

**1. The reviewer is still not being invoked.** Same log line as Batches 0003 and 0004 of Volume 02, and the same session header. **Controller-owned:** recorded in `state/open-threads.md` item 27 and left alone. This is the fourth batch in a row.

**2. `state/phase-ledger.json` is stale and unused.** Still `phase-000-bootstrap`, `status: "planned"`, `attempts: 0`, one entry, after thirteen batches and a hundred and ten chapters, while `state/current.md` reads *Next phase: `workspace/volume-03/batch-0002/PROMPT.md`*. Both are true on disk simultaneously. **Controller-owned and flagged only; the file was not edited.** The root cause is an instruction conflict — `AGENTS.md` tells writers to update the ledger, the operating instruction forbids it — and it is not fixable inside a phase.

**3. The writer's own change list was wrong twice, and both times it was wrong in the direction of making itself look correct.** §10 items 3 and 13 of the batch summary are the two cases, and they are the two findings below that reverse it. **The rule that follows is the one Batch 0004's review set: a change list is not evidence. `reviews/<volume>/<batch>.md` and the page are.**

## Regressions introduced by the repair pass

**4. "I do not know" is four words, and the repair changed it to three.** `chapters/volume-03/chapter-0109.md:65` and `bible/terminology.md:690`, with the figure propagated into four state files. **The page was right and the repair broke it.** `git show 6099815:chapters/volume-03/chapter-0109.md` — the checkpoint, before the repair — reads *it is four words and I am not going to improve on it*. Under the batch's own binding convention (`PROMPT.md:69`, *an orthographic word is one word*), *I / do / not / know* is **four**. §10 item 3 recorded the change as an intentional fix: *"which is three. **Fixed to three.**"*

| File | Was | Now |
|---|---|---|
| `chapters/volume-03/chapter-0109.md:65` | three words | **four words** |
| `bible/terminology.md:690` | three words | **four words** |
| `state/continuity.md`, word-count device, Volume 03 Batch 0001 | **three** | **four**, with the count of the sentence spelled out |
| `state/current.md` | three words | **four words** |
| `state/character-state.md` | three words | **four words** |
| `state/chapter-summaries.md` | three words | **four words** |
| `state/batch-summaries/volume-03-batch-0001.md` §10 item 3 | *Fixed to three* | **REVERSED**, with the reversal and its reason on the page |

**This was the most expensive of the six.** A word count is the one figure in this book that a reader is invited to check, the wrong figure was in the bible and would have been inherited as canon, and the batch summary asserted the correction as fact.

**5. "Nine more lines" did not parse to nine, and the repair that made it parse introduced a person merge.** `chapters/volume-03/chapter-0106.md:21`. The page lists *the four who read the join-line* (four lines) and then, beside them, *a woman of seventy who keeps a floor* — **who is Nyla Ferrow, seventy, keeper of the lock chapel, and who is one of the four.** Nine lines, **eight people**. The chapter's own argument on the next line is *a list that enters a person twice is a list of a person and not of a debt*, so the list broke its own rule in the same breath as stating it. A second proximity sat in the same clause: *a woman of fifty-eight who sets bones* is Hesper Saye, and Renna Ord, fifty-eight, is one of the four and stands one clause away.

**Fixed on the page, not in the summary.** The woman of seventy is now stated to be **inside** the four; the four are stated to be **four lines and not one line**; the bone-setter is identified by **her low room by the salt wharf**, which Renna Ord does not keep; and the count is **nine lines and nine people**, so the page is **twelve and twelve**. No person was invented and no debt changed. `state/continuity.md` item 20 and §10 item 13 of the batch summary were corrected to match, and both now record that the first repair was also wrong.

## Canon claims not supported by the pages

**6. "Nineteen lines" on the second page of the stone was real but unwritten.** `state/continuity.md:1364` and `state/open-threads.md:86` asserted the count; the prompt carried it forward as binding. **The finding that it was fabricated was half right, and the half that was wrong is the half that mattered.**

The page does support nineteen, and not eighteen. Chapter 0106's second page is **twelve named people**. Chapter 0110 puts the count under them **in six lines** and then records the woman of sixty-one asking for three more things by name: *a line under it that says it is a count and not a debt, and put the date on that line, and put the word nobody on the line above it.* Twelve plus six plus that seventh line is **nineteen**, and the word *nobody* is on the sixth line, which is the line the chapter already calls the finding. **A later writer reading only *in six lines* would have corrected a correct number to eighteen, which is exactly the failure this batch's own arithmetic is about.**

What was genuinely wrong is that **no chapter ever said the total.** The number existed only in a state file, which meant it was a canon claim with no page behind it — and *nineteen* is a loaded figure in this series, being the nineteen lines a person may be asked to turn up for and the instrument's second page of nineteen reasons, so a bare *nineteen* in a state file invited a false echo in a batch whose subject is numbers nobody can check.

**The fix is to put it on the page rather than to change it.** `chapters/volume-03/chapter-0110.md` now carries, where the count goes on the page: *the second page of that stone is nineteen lines long from the top of the first name to the bottom of that seventh one, and it was counted twice on the way down, and it was nineteen both times.* `state/continuity.md` and `state/open-threads.md` now give the derivation and **say in terms that a later writer may not lower it to eighteen**, and the Batch 0002 prompt carries the derivation rather than the bare figure. **Nothing in the scene changed: the seventh line, the two counts and the road were already there.**

**7. Chapter 0118 is day 118, not day 120, and the answer is sixty-eight days late, not fifty-four.** `workspace/volume-03/batch-0002/PROMPT.md:44` and `:86`. The prompt's own day map puts 0118 on **day 118**, the twenty-eighth day of the month after this one. Tam Crane was asked on the fiftieth day, so 118 − 50 = **sixty-eight**. *Fifty-four* is day 104's figure and looks copied from Chapter 0104's *hundred and fourth day*, and it contradicted the prompt's own calendar rule at line 67. **Both sites are now dated and counted: the answer is unwritten on the hundred and eleventh day, which is sixty-one days, and it is written on the hundred and eighteenth, which is sixty-eight days late.** The line at `:44` had also been self-contradictory — *unwritten on the hundred and twentieth day* while naming Chapter 0118 as where it is written.

**8. A second day-120 figure was in the fiction and not in the prompt.** `chapters/volume-03/chapter-0110.md:51`, a Hearthguard's line: *Forty-four days from today, counted from the hundred and twentieth day of this flood.* **Chapter 0110 is day 110.** Forty-four days from 110 is 154, which is the Registry hearing and is correct on the same page twice more, so only the day was wrong. **Now the hundred and tenth day of this flood.** This one is the same confusion as finding 7 and it was not in the review's list; it is recorded here because the next reviewer will otherwise find it and think this pass missed it.

## Wording

- `PROMPT.md:41` — *The consequence has not yet been stated **in this batch** and it is **the batch's** sharpest ordinary pressure* was self-referential inside the Batch 0002 prompt. Now *not yet stated* and *this batch's*.
- `PROMPT.md:55` — *it has not moved one sixteenth of an inch at any point in **the hundred and twenty days he has been in this world*** ran the line's age together with the length of his stay. The line is **day minus one** — one hundred and ten at 0111, one hundred and nineteen at the end of 0120. The bullet now says so, and adds the two figures are not to be run into one another.
- `PROMPT.md:5` against §12 of the batch summary — two adjacent documents named two different benchmarks. Volume 02 Batch 0004's 3,104–4,239 was named as the run to avoid; Volume 02 Batch 0005's 2,296–3,902, median 2,647, was named as *the figure to beat*, which is the figure Batch 0001 was itself written against. **Both documents now name all three figures and say which one governs**: this batch's own **2,985** is the number to beat, Volume 02's 2,647 is what it was written against, and 3,104–4,239 is the run to stay out of.

## Word counts, re-taken

The repairs in findings 4, 5 and 8 changed the length of three chapters, so §12's figures were stale. Re-counted with `wc -w` on the files as they now stand: **3,268, 3,001, 3,385, 2,605, 2,969, 3,235, 2,907, 2,811, 2,939, 3,192** — minimum 2,605, maximum 3,385, mean 3,031, **median 2,985, unchanged.** The median is **three hundred and thirty-eight words** above Volume 02 Batch 0005's 2,647 and the minimum is three hundred and nine above its 2,296, so the drift is still going the wrong way and is still being written against. §12 now says the count is re-taken after a repair, which is the rule Batch 0004 set and this batch's repairs are the first thing to need it.

## Verified clean

Word counts are as claimed in §12 above and the median is unaffected by the repairs. All ten files have even bold-span counts. No duplicated long paragraph across the ten. **No banned date form in any of the ten** — the four forms *of this month*, *of the month*, *of next month*, *of this new month*, and any spelled-out ordinal that cannot exist. No instance of *Owen Park* in `chapters/volume-03/`. No instance of Mina Okoye's sentence, and none in a third mouth. No instance of the knocks. No instance of *in this series* or *this chapter* in the narration. The twenty-nine interface offers are consistent across the ten chapters and the silence count runs twelve, thirteen, fourteen, fifteen, (speaks), sixteen, (speaks), seventeen, eighteen, nineteen. **Five times out of six** for Peth Lomas is backed by `state/continuity.md` and `state/character-state.md`. The Four Elms shrine is canon. The *Live into Volume 03, Batch 0002* open-threads block does have 28 numbered items. `outline/volume-03.md` is genuinely absent, as the prompt says, and that is a gap for an outline phase and not a fiction problem.

## What was not touched, and why

**The planned plot.** Nothing in the batch's spine, its turn, its findings, its ending or the handoff's day map was changed. Finding 7 moved a day in a *future* chapter card and two figures in a prompt; finding 8 corrected a day in a past chapter. **No chapter was restarted and no prose was replaced** — the repairs are three words, one clause group, one sentence in Chapter 0110 and one figure in Chapter 0109.

**`state/phase-ledger.json`.** Controller-owned. Flagged, not edited.

**The Void, both names, the four readers, the twenty-three refusals, the five lock sites, the seven Crown shapes, the hearing on day 154, and the ending.** All untouched and all still binding. **The volume's engine is unchanged: the page is spent, five rooms have failed to explain it in the same place, and no chapter in this series may show it working.**
