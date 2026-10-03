# state/volume-20-index.md — THE VOLUME-LEVEL INDEX

**Created on the review-fix pass of batch 0002 of Volume 20. `PHASE_SYSTEM.md` asks for exactly this: "If the continuity
files grow too large, create a volume-level index and retrieve only relevant sections." The five live state files were
4,274 lines between them before this pass and are 809 now, and this index is how a writer finds the rest without loading
all of it.**

**HOW TO USE THIS FILE.** Read this index first. It tells you which live section answers your question and which archive
file to open when the live layer does not carry enough. **Open a chapter when a state file tells you what a chapter says.**

## THE VOLUME IN ONE BLOCK

**Volume 20 is chapters 0951 to 1000, days 951 to 1000, and it is a flood.** A room over a market, a stair of eleven steps,
a bench, two books that hold two accounts of one day and have never been compared, six strokes in a column that holds
figures and no seventh. Nine questions are asked across the fifty days and none of them is written down. Adrian Vale is in
nine of the fifty days and obtains something on **one** of them. **Day 951 is a Sunday; the Bare-Month ordinal is the day
less 315; no middle day may be derived from either end of the range.** Twenty chapters are written. Thirty remain.

| Batch | Chapters | Days | Written | Record | Batch summary | Next-phase prompt |
|---|---|---|---|---|---|---|
| 0001 | 0951–0960 | 951–960 | yes, and repaired once | `reviews/volume-20/batch-0001.md` | `state/batch-summaries/volume-20-batch-0001.md` | — |
| 0002 | 0961–0970 | 961–970 | yes, and repaired on this pass | `reviews/volume-20/batch-0002.md`, and `reviews/volume-20/batch-0002-fix.md` | `state/batch-summaries/volume-20-batch-0002.md` | `workspace/volume-20/batch-0002/PROMPT.md` |
| 0003 | 0971–0980 | 971–980 | **no** | — | — | **`workspace/volume-20/batch-0003/PROMPT.md`, written and ready** |
| 0004 to 0007 | 0981–1000 | 981–1000 | **no** | — | — | to be created one at a time, one phase only |

**Card files exist for batch 0001 only, at `outline/batches/volume-20-batch-0001.md`. Batch 0002 had none and its prompt
carried its own cards, and batch 0003's does the same. Do not stop for the want of a card file.**

## WHAT IS IN EACH LIVE STATE FILE, AND WHERE THE REST IS

| You want to know | Go to | It is at |
|---|---|---|
| What the last ten days changed in the world | `state/continuity.md` | "The four states that changed on days 961 to 970" |
| Where every standing object is, at day 970 | `state/continuity.md` | "Where the standing objects stand at day 970", eleven items |
| The geometry of that stair | `state/continuity.md` | "The geometry of that stair" — **eleven steps, the ninth from the top is not the bottom one, and the stair is never counted** |
| What went out of that room and cannot be got back | `state/continuity.md` | "The two things that went out and did not come back" |
| Which threads are open and which this volume may not settle | `state/open-threads.md` | "The threads this volume may not settle", and the two this batch opened |
| The two debts about the writing itself | `state/open-threads.md` | "The two threads about the writing" — the length shortfall and the prose going hollow |
| Who these people are, and their second handles | `state/character-state.md` | the handle table |
| Where each person stands on the days that mattered | `state/character-state.md` | "The staging of 965", "The four people who are in days 961 to 970 and not in the room", and the two restaged mornings |
| The prose rules this volume's first batch broke | `state/character-state.md` | "The two manner rules this volume's first batch broke" |
| What each of the twenty written days was | `state/chapter-summaries.md` | the two per-day tables |
| What the thirty unwritten days are for | `state/chapter-summaries.md` | "Volume 20 — chapters 0971 to 1000", the fourteen heavy days with a written/ahead column |
| What the last run measured | `state/current.md` | "The batch that wrote chapters 0961 to 970, and the review-fix pass on it" |

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

## THE PLAN IS THE PLAN OF RECORD AND THE STATE LAYER IS NOT

**`outline/volume-20.md` wins over every state file and over every prompt.** Where a state file and the plan disagree, the
plan is right and the state file is stale. **`outline/ending.md` is read and never written by a batch phase.** The plan
holds the eighteen frames, the nine questions, the descriptor pool, the §17 items and the six held strings, and a writer
who reads only this index will still miss all of them.

## THE SIX HELD STRINGS, AND WHERE THEY LIVE

**Nothing below may be printed in any chapter, in any prompt, in any record or in any summary, on any day but the day the
plan gives it.** Their wording is in `outline/volume-20.md` and nowhere else, which is the whole mechanism.

1. The decision's wording and its cost — §6.6, day 975. Written on disk already.
2. The panel's wording — §6.7, day 983. Not written.
3. The word under the day cut across the head of the second slate — §6.8, day 985. Not written.
4. The three wordings of day 994 — §6.9. Not written.
5. The refusal of 965 — §6.10. **Written once, in `chapters/volume-20/chapter-0965.md`, and once in the plan.**
6. The name of the man who came up that stair on 866 — held at `outline/volume-18.md` §6.8. Not written.

## THE NEXT PHASE, AND IT IS THE ONLY ONE

**`workspace/volume-20/batch-0003/PROMPT.md`. Chapters 0971 to 0980, days 971 to 980, Saturday to Sunday. It is written,
it carries its own ten cards, and it is the only next phase that exists.** Volume 20 runs to day 1000, so **thirty
chapters remain after it and no phase has been created for any of them.**