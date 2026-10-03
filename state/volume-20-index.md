# state/volume-20-index.md — THE VOLUME-LEVEL INDEX

**Created on the review-fix pass of batch 0002 of Volume 20, brought up to date on the review-fix pass of batch 0003, and
brought up to date again on the writing run of batch 0004. `PHASE_SYSTEM.md` asks for exactly this: "If the continuity files
grow too large, create a volume-level index and retrieve only relevant sections." The five live state files were 4,274 lines
between them before the batch-0002 pass, 687 after the batch-0003 compaction, 813 after that pass added its prohibitions,
and **808 now, after the batch-0004 compaction; this index is how a writer finds the rest without loading all of it.**
**The previous version of this file ended in the middle of a sentence, at a line the batch-0003 writing run left
unfinished, and that is repaired here.**

**HOW TO USE THIS FILE.** Read this index first. It tells you which live section answers your question and which archive
file to open when the live layer does not carry enough. **Open a chapter when a state file tells you what a chapter says.**

## THE VOLUME IN ONE BLOCK

**Volume 20 is chapters 0951 to 1000, days 951 to 1000, and it is a flood.** A room over a market, a stair of eleven steps,
a bench, two books that hold two accounts of one day and have never been compared, six strokes in a column that holds
figures and no seventh. Nine questions are asked across the fifty days and none of them is written down. Adrian Vale is in
nine of the fifty days and obtains something on **one** of them, and that one is 985 and is not the one he was after. **Day 951 is a Sunday; the Bare-Month ordinal is the day
less 315; no middle day may be derived from either end of the range.** **Forty chapters are written, days 951 to 990, and ten remain.**

| Batch | Chapters | Days | Written | Record | Batch summary | Next-phase prompt |
|---|---|---|---|---|---|---|
| 0001 | 0951–0960 | 951–960 | yes, and repaired once | `reviews/volume-20/batch-0001.md` | `state/batch-summaries/volume-20-batch-0001.md` | — |
| 0002 | 0961–0970 | 961–970 | yes, and repaired on this pass | `reviews/volume-20/batch-0002.md`, and `reviews/volume-20/batch-0002-fix.md` | `state/batch-summaries/volume-20-batch-0002.md` | `workspace/volume-20/batch-0003/PROMPT.md`, written and since run |
| 0003 | 0971–0980 | 971–980 | **yes, and repaired on that pass** | `reviews/volume-20/batch-0003.md`, and `reviews/volume-20/batch-0003-fix.md` | `state/batch-summaries/volume-20-batch-0003.md` | **`workspace/volume-20/batch-0004/PROMPT.md`, written and ready** |
| **0004** | **0981–0990** | **981–990** | **yes** | **`reviews/volume-20/batch-0004.md`** | **`state/batch-summaries/volume-20-batch-0004.md`** | **`workspace/volume-20/batch-0005/PROMPT.md`, written and ready** |
| 0005 | 0991–1000 | 991–1000 | **no** | — | — | **the last ten days of Volume 20** |

**Card files exist for batch 0001 only, at `outline/batches/volume-20-batch-0001.md`. Batches 0002, 0003, 0004 and 0005 had
none and their prompts carried their own cards, and batch-0005's says so in its own first lines. Do not stop for the want of
a card file. Forty chapters are written and ten remain.**

**AND THE FRAME POOL IS NOW EMPTY, MEASURED.** All eighteen frames at `outline/volume-20.md` §17.20 have been drawn somewhere in
this volume across its four written batches, **so every one of batch 0005's ten cards is a repeat and §17.20 requires all ten
of them to be named in its card file rather than hidden, and `workspace/volume-20/batch-0005/PROMPT.md` names them all with the
day each was last drawn.**

## WHAT IS IN EACH LIVE STATE FILE, AND WHERE THE REST IS

| You want to know | Go to | It is at |
|---|---|---|
| What the last ten days changed in the world | `state/continuity.md` | "The two states that changed on days 971 to 980", and "the four states that moved" in `state/open-threads.md` |
| Where every standing object is, at day 990 | `state/continuity.md` | "Where the standing objects stand at day 990" |
| **The three things the last batch added: the sheet, the block on the wall, and the cloth on the second book** | `state/continuity.md` | "The three states that changed on days 981 to 990" |
| The geometry of that stair | `state/continuity.md` | "The geometry of that stair" — **eleven steps, the ninth from the top is not the bottom one, no chapter counts it end to end, and 977 names the bottom step as the eleventh and the last** |
| Whose board is which, and whose cloth it is | `state/continuity.md` | "What the review-fix pass on days 971 to 980 settled" item one |
| What went out of that room and cannot be got back | `state/continuity.md` | "The three things that went out of that room and cannot be got back", in `state/current.md` |
| Which threads are open and which this volume may not settle | `state/open-threads.md` | "The threads this volume may not settle", and the three days 981 to 990 opened |
| The debts about the writing itself | `state/open-threads.md` | "The three threads about the writing before those four rules" — the length shortfall, the prose going hollow, the attribution punctuation |
| The four rules a repair pass added | `state/open-threads.md` | "The four rules a repair pass on days 971 to 980 added" — figure-with-its-pair, no asserted absence, no held string in a record, and every object belongs to somebody |
| Which files a writer run may edit at all | `state/open-threads.md` | "And one rule about who may edit which record, added by a repair pass on days 961 to 970" — a writing run does not amend a reviewer's artifact, and a run that finds its own work done says so once and writes no chapter |
| Who these people are, and their second handles | `state/character-state.md` | the handle table |
| Where each person stands on the days that mattered | `state/character-state.md` | the four people who are in days 971 to 980 and not in the room, and the keeper and the tradesman above them |
| The prose rules this volume's first batch broke | `state/character-state.md` | "The two manner rules this volume's first batch broke" |
| What each of the forty written days was | `state/chapter-summaries.md` | the per-day table |
| What the ten unwritten days are for | `state/chapter-summaries.md` | "Volume 20 — chapters 0991 to 1000" |
| What the last run measured | `state/current.md` | "The batch that wrote chapters 0981 to 990", and the three debts beneath it |
| **The one place two clauses of the plan had to be read together, and the reading** | `state/current.md` | "The one place two clauses of the plan had to be read together" — §6.5 against §6.4 against frame sixteen, and what it means for the sheet |

## THE ARCHIVE, AND WHEN TO OPEN IT

**`state/archive/` holds every version of every state file this repository has ever run, and nothing was deleted on this
pass.** The five live files were copied whole and verified by SHA256 immediately before the compaction, so every older
layer is still readable in full. **Open an archive copy when the live layer does not carry enough, and not otherwise.**

| What you need that the live layer does not carry | Open |
|---|---|
| Everything this repository decided before day 961, in one file per state file | `state/archive/current.md.volume-20-batch-0002-review-fix-full.md` and its four siblings with the same suffix |
| What the first repair pass on days 951 to 960 changed, block by block | the same five files, which contain it whole |
| **The threads this manuscript was carrying at the end of day 750, and the prohibitions Volume 15's fifty days left standing — all still live** | `state/archive/open-threads.md.volume-20-batch-0002-review-fix-full.md` and `.../continuity.md....md`, and **read these whole before any volume-close audit** |
| The volume planning blocks, including the protagonist and the handles that are not people | `state/archive/character-state.md.volume-20-batch-0002-review-fix-full.md` |
| Volume 19's plan and its per-day entries | `state/archive/continuity.md.volume-20-batch-0002-review-fix-full.md` |
| The batch-0001 review-fix block as it was written before this compaction | any of the five `*.volume-20-batch-0002-review-fix-full.md` copies |
| Everything this repository decided before day 971, and the batch-0003 block as the writing run left it | any of the five `*.volume-20-batch-0003-writing-full.md` copies |
| The five live state files exactly as the batch-0003 review-fix pass found them | any of the five `*.volume-20-batch-0003-review-fix-full.md` copies |
| **The five live state files exactly as they stood before the batch-0004 compaction** | any of the five `*.volume-20-batch-0004-writing-full.md` copies |

## THE PLAN IS THE PLAN OF RECORD AND THE STATE LAYER IS NOT

**`outline/volume-20.md` wins over every state file and over every prompt.** Where a state file and the plan disagree, the
plan is right and the state file is stale. **`outline/ending.md` is read and never written by a batch phase.** The plan
holds the eighteen frames, the nine questions, the descriptor pool, the §17 items and the six held strings, and a writer
who reads only this index will still miss all of them.

## THE SIX HELD STRINGS, AND WHERE THEY LIVE

**Nothing below may be printed in any chapter, in any prompt, in any record or in any summary, on any day but the day the
plan gives it.** Their wording is in `outline/volume-20.md` and nowhere else, which is the whole mechanism.

1. The decision's wording and its cost — §6.6, day 975. **Written once, in `chapters/volume-20/chapter-0975.md`, and once in the plan. A review-fix on batch 0002 found it standing in `reviews/volume-20/batch-0002-fix.md` and removed it: §20 item 6 bars a held string out of a batch record, and a record quoting a string to prove it absent is quoting it.**
2. The panel's wording — §6.7, day 983. **Written once, in `chapters/volume-20/chapter-0983.md`, in a block of its own, and once in the plan. `outline/volume-20.md` §21.3 gives it as 257 characters and this repository's extraction returns 257.**
3. The word under the day cut across the head of the second slate — §6.8, day 985. **Written once, in `chapters/volume-20/chapter-0985.md`, in that man's mouth and nowhere else in the volume. `outline/volume-20.md` §21.3 gives it as six characters and it is eight; its instrument is a whole word, and a whole-word instrument does not care how many characters it is.**
4. The three wordings of day 994 — §6.9. Not written.
5. The refusal of 965 — §6.10. **Written once, in `chapters/volume-20/chapter-0965.md`, and once in the plan.**
6. The name of the man who came up that stair on 866 — held at `outline/volume-18.md` §6.8. Not written.

## THE NEXT PHASE, AND IT IS THE ONLY ONE

**`workspace/volume-20/batch-0005/PROMPT.md`. Chapters 0991 to 1000, days 991 to 1000, Friday to Sunday. It is written, it
carries its own ten cards with all ten frame repeats named, and it is the only next phase that exists.** Volume 20 runs to day
1000 and **these are the last ten days of it**: the question of day 898 asked a second time and not remembered on 991, the act
on 994, the morning after on 995, the fence on 996, the resolution on 997 and the last image on 1000. **It decides none of them
and it says so in its own closing section.** **Volume 20 ends at 1000, and no phase after this one may be created by a batch:
`AGENTS.md` requires exactly one, and what may follow this batch is the record and the summary and the rolling of the live
state layer and nothing else.**