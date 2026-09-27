# Review and Repair — Volume 08, Batch 0003 (Chapters 0371–0380), commit `c2c8919`

**Findings source:** `logs/batch-0003.review.log`. **The reviewer was not invoked:** line 1 of that log reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session header is `novel-writer · space-bunny-free`, so this is a second pass by the same agent that wrote the batch. `state/phase-ledger.json` reads `phase-000-bootstrap / planned / attempts: 0` after thirty commits. **Both are controller-owned, both are named in this phase's own prompt as not this repository's to touch, and neither was touched.**

**Scope reviewed:** `chapters/volume-08/chapter-0371.md` … `chapter-0380.md`, `bible/power-system.md` §48, the five state files the batch updated, and the handoff `workspace/volume-08/batch-0004/PROMPT.md`. **No chapter was restarted. No plot, no beat, no ending, no day, no weekday, no anchor and no cast member moved. The prose that was good was kept, and the two days of it that were not — a sentence frame that was saying nothing — were rewritten rather than the chapters being replaced.**

**The review raised eight findings. Three are repaired in the prose, two are repaired in the plan and the state layer, two are carried as tracked debts because a batch may not decide them, and one is controller-owned and was not touched. The review's own recommended order was followed: the prose blockers first, then the state layer, then the structural findings, then the housekeeping.**

---

## 1. What the review got right, and it was more than half of it

**The quantitative work in this batch reproduces and none of it was touched except where the review said it had to be.** Re-ran on the files: the day map stands at 371 Monday, 372 Tuesday, 373 Wednesday, 374 Thursday, 375 Friday, 376 Saturday, 377 Sunday, 378 Monday, 379 Tuesday, 380 Wednesday, rebuilt from day 1 being a Tuesday and not from the prompt's table. **The multiset of every digit string across the ten files is unchanged by this repair pass at zero lost and zero added.** The object inventory, the descriptor map, the register of the seven notices, the second handles, the 143 long sentences with none duplicated, the count of paragraphs carrying neither speaker marker at zero, the exchange at twenty of twenty, and the register line with a day on it and nothing under the day belonging to day 391 and not this batch — all stand as published, and the checks are re-run in §6 below.

**And the review's sharpest single observation was the one the batch's own record had already half-made.** It wrote, at `state/batch-summaries/volume-08-batch-0003.md` §3.4, that *a metric whose unit is a four-word phrase rewards a chapter for changing a preposition and nothing else*, and then left the metric in place. **The review read the same sentence, saw what it meant, and named the consequence: a defect that is measured, published and inherited is still a defect.** That is the finding the whole pass turns on, and it is repaired below at §3.

**Two more of the review's points were right and were already in the plan**, and are recorded because a review that only finds things the plan missed is not a review. The protagonist's absence is not accidental: `outline/volume-08.md` §4 names every chapter of Volume 08 Adrian Vale is in — 0352, 0355, 0360, 0371, 0376, 0381 and 0392 — and the batch honoured that list exactly. The outline's self-contradiction about him at the midpoint was already found, recorded and resolved *in the batch's favour* by the batch itself, in its own §6.

---

## 2. BLOCKING — the narration voice had collapsed into one frame, and the frame was restating the sentence before it. **Repaired.**

`logs/batch-0003.review.log` Finding 1: the frame `about four people … have worked out since that` stood **133 times on the clause-head and 105 times on the frame across the ten files, in 198 paragraphs, one instance in every 1.9 paragraphs, with no chapter at zero**, and every instance was a paraphrase of the sentence immediately before it, so the second half of nearly every paragraph carried no new information.

**This is right and it is worse than a style preference, because it is the manuscript's declared device being consumed by its own use.** The chorus frame is real. `outline/volume-08.md` §17 item 11 declares it a sentence and not a token, Volume 07's last ten carry it at one in 5.6 on the bare head, and it is one of the few things in the book that put a small group of un-named people in a room without turning them into a chorus with lines. **The repair therefore did not delete the device. It deleted the habit.**

**The method is the plan's own and not a new one.** §17 item 11: *stripping it means deleting the string and its clause-head and re-attaching the observation to the sentence it was standing in, and it cannot be done by substitution.* All 105 instances were read in their paragraphs and rewritten sentence by sentence. **The observation in each was kept, including the new ones**, because a great deal of real content in this batch was sitting inside the frame and the frame was the only reason it read as filler — a crease gone soft, a third column empty on purpose, a woman's nine days declined, a bench two women had been arranging for a month without speaking. **What was cut was the sentence saying that somebody in the room had worked the observation out.** Nine feet, the count of about nine people, the man of about thirty-nine's silence, the second slate, the figure of about two hundred rooms in two men's mouths: every one of these is still on the page, in the same paragraph, in the same chapter, saying the same thing.

**The chorus survives as a device at thirty-two instances in 198 paragraphs, one in 6.2, and fifteen on the declared head `about four people in`, one in 13.2.** That is below Volume 07's inherited level on the head and it is a device and not a threshold, and §17 item 11a now says so in terms a writer can be held to. **The number is published because a figure a later writer cannot reproduce is a rumour, and it is published beside the first edition's rather than instead of it.**

**Good prose was kept and was recognised as good.** The leads, which the review did not fault and which are the volume's construction, are unchanged. The dialogue is byte-identical. Chapter 0376's yard and Chapter 0377's roof — the two chapters the review itself singled out as the only ones in the batch with real physical action — are rewritten in the same register and keep every beat, including the woman of about sixty-nine's reason for not correcting a man and the figure handed back in a squall.

## 3. BLOCKING — the state layer had institutionalised the defect as a success metric. **Repaired.**

The review's second point is the one that matters most, and it is the sentence quoted in §1 above. `state/batch-summaries/volume-08-batch-0003.md` §3.4 published two counts, compared them against Batch 0001 and Batch 0002, and reported *Batch 0001 at one in 2.0, Batch 0002 at one in 1.9, and this batch is at one in 1.9, and the three are the same to one decimal place, and this record reports that as a measurement and not as a result.* **It was not a result. The growth direction was worse, 1 in 2.6 → 1 in 2.0 → 1 in 1.9, and being reported as flat, and the same paragraph contained the sentence that explains why the number was meaningless.** `workspace/volume-08/batch-0004/PROMPT.md` then called those ten chapters *the voice* and told the next writer they might not be rewritten. **So the defect was on its way to becoming the house standard, and it would have arrived there as a trend.**

**Four files were repaired, and none of them was made to agree silently.**

| File | What it said | What it says now |
|---|---|---|
| `state/batch-summaries/volume-08-batch-0003.md` §3.4 | two counts, a flat trend, and the mechanism that voids both | the first edition quoted whole and marked **SUPERSEDED**, the mechanism named as the finding, the repaired counts beside them, and a §11 that names the fault in its own record |
| `bible/power-system.md` §48 item 10 | the same two counts, and *no frame was cut to move either figure* | both editions of both the counts and the bolded share, and the sentence *a chorus frame may carry an observation into a paragraph and it may not restate one the paragraph has already made* |
| `workspace/volume-08/batch-0004/PROMPT.md` | the chorus as a trend to be reported on | §17 item 11a bound on the next batch, the question *of the instances you counted, how many restate a sentence the paragraph has already made* added to its deliverables, and the movement declared a repair of one batch and not a trend about the book |
| `outline/volume-08.md` §17 item 11 | the frame as a sentence and a count as not a target | **item 11a added**, which is the rule in one sentence and attaches no number to it |

**And the handoff prompt's instruction to read the last ten chapters as the voice was rewritten rather than deleted.** Those ten chapters are good prose and they are the immediate context, so removing them would have been its own fault. What changed is the claim: the writer is told the ten files went through a repair pass, that the version on disk is the repaired one, and that what they are copying is *a repaired voice and not a clean one*.

## 4. BLOCKING — the protagonist is in two of ten. **Carried, and the plan's contradiction closed.**

The review is right that a novel whose specification names Adrian Vale in its first line has him in seven chapters out of fifty and five out of thirty, and that he performs no working, opens no threshold, is aged nowhere, and has *passage* and *privilege* at zero across the batch.

**A batch may not fix this, and a batch that put him into two more chapters would have committed a worse fault than the one it was repairing.** `outline/volume-08.md` §4's list is binding, it was honoured exactly, and §17 item 10's rule is that he is in a room reading a page and in no chapter in which people decline to ask him. Carried as **Debt 8** at `state/open-threads.md` for the Volume 08 close, which is the only phase after an outline phase permitted to decide anything, and named in the next prompt under a heading that tells the writer it is not theirs to decide.

**What was closed, and it is a real closure, is the plan's own contradiction.** `outline/volume-08.md` §8 ended *Adrian is in that room and asks nothing and is asked nothing and is on a page because he is reading the second slate*, and §4's list does not have 0375 on it. **The batch found this, followed §4, and recorded the withdrawal in its own record — which left the plan itself still wrong, for the next writer to read and be stopped by.** §8 is now corrected in the plan: §4 governs, Chapter 0375 has no Adrian in it in any form, the claim is withdrawn, and the rule that governs his absence is named as §4's and not a licence to place him where a section is dramatic. `bible/power-system.md` §48's pointer to that contradiction now reads *closed in the plan* and names the date.

## 5. HIGH — nine of ten chapters are one room on consecutive days. **Carried.**

Chapters 0371, 0372, 0374, 0375, 0378, 0379 and 0380 are the same room over the same market on seven consecutive days; 0376 and 0377 leave it, and the review is right that those two are the only ones in the batch with physical action and forward motion, and right that a batch where the preparation is the plot has no plot.

**This is an allocation fault and not a chapter fault, and re-allocating days is a plan change.** `outline/volume-08.md` §5 names six other locations and §9 puts the road and the weather on the days that belong to Batch 0004, so the volume is not built this way. Carried as **Debt 6** for the close. The one thing a batch could do about it — make the room cost something on each day it appears — is in the review file as a chapter-by-chapter test, and the frames were being cut and re-attached in exactly those paragraphs in any case, which is the cheapest available version of that repair.

**MEDIUM, characters are told apart by their objects. Carried as Debt 7.** The review's reading is accurate: a reader tracks this batch by the chalk, the slate, the folding knife, the satchel, the second slate, the tin, the nine words and the sheet of road. **This is a fault of the descriptor map and not a breach of it** — `outline/volume-08.md` §20.8 declares the map, and §17 item 9 requires a second handle beside the age and the trade and never instead of it, and this batch obeyed that instruction in all ten chapters. The remedy is not to rename anybody and not to drop a handle, and `man of about thirty-four` and `man of about thirty-nine` are the second and third most frequent descriptors in a 380-chapter manuscript. A decision about the map belongs to an outline phase or a close.

## 6. The rest, and the checks that were run after the last edit and not before

**LOW, the double comma at `chapter-0380.md:37`. Repaired.** It sat inside a bold mark in a chapter the review otherwise did not fault. A search for `,,` across Volume 08 now returns nothing.

**MEDIUM, the state files are unbounded. Repaired, and recorded at length because it is the first move in this state layer.**

| File | Before | After | Archive |
|---|---|---|---|
| `state/current.md` | 323 KB | **95 KB** | `state/archive/current.md.volumes-01-to-06.md` |
| `state/continuity.md` | 1,072 KB | **204 KB** | `state/archive/continuity.md.volumes-01-to-06.md` |
| `state/character-state.md` | 711 KB | **260 KB** | `state/archive/character-state.md.volumes-01-to-06.md` |
| `state/chapter-summaries.md` | 642 KB | **148 KB** | `state/archive/chapter-summaries.md.volumes-01-to-06.md` |
| `state/open-threads.md` | 498 KB | **152 KB** | `state/archive/open-threads.md.volumes-01-to-06.md` |
| **live** | **3,246 KB** | **859 KB** | 2,387 KB retained whole |

**The body of each file belonging to Volumes 01 to 06 was moved to `state/archive/` verbatim and nothing was edited, abbreviated, corrected or deleted.** What is live is the whole of Volume 07 and the whole of Volume 08 to date, which is one complete volume and one in progress. Each archive header carries the reason, what is true of it, the line count, and **the SHA256 of the moved text so a later pass can prove it did not alter what it moved.**

**The integrity check, reproducible from `HEAD`:** every non-blank non-heading line of all five files was compared against the union of the live file and its archive — **zero lines lost, zero headings lost, in all five.** `state/current.md` was given a file-level header because after the cut it had none, **and its first line had been naming `volume-08-batch-0001` as the current phase, three batches after that phase ran** — a stale navigation line of the class this repository raises in every review. Its stale size claims in `state/character-state.md` and `state/chapter-summaries.md` were corrected to the new figure with the archive named.

**And the checks on the prose, all re-run after the last edit:**

- **The set of bolded speech paragraphs in all ten files is byte-identical to the first edition.** Every line of dialogue, every speaker mark, verified by extraction and set comparison. No speech was cut, rewritten or reordered.
- **The multiset of every digit string across the ten files: zero lost, zero added.**
- **No weekday token and no Bare Month day was added, changed or removed.** The single difference is a plural — *three Mondays in a row* became *the third Monday in a row* — same day, same fact.
- **Markdown bold parity: zero unbalanced `**` across all ten files.**
- **Paragraphs carrying neither speaker marker: zero in all ten**, on the published definition.
- **No paragraph carries the man of about thirty-four and a woman of about thirty-four together** — zero, on the word-bounded definition, and the check is the word-bounded one because the unbounded one returns the other.
- **Longest bolded turn: eighty-five words, in two chapters, against the working ceiling of about ninety and the hard one of ninety-five.**
- **Longest run of consecutive speech paragraphs: two in nine files and three in Chapter 0379**, within the ceiling of four.
- **Highest word-run involving any of the ten files: thirty-three words, Chapters 0374 and 0378**, the volume's room-lead frame, unchanged by the repair and the same figure the batch published. Nothing over forty appeared.
- **The bolded share moved up on four chapters and down on none**, because the repair cut narration and cut no speech. Both editions are published in the bible, in the batch record and in the next prompt. All ten remain under the ceiling of about thirty-five, and no target and no verdict is set on any of them.
- **A search for `,,` across Volume 08 returns nothing.**

**INFO, the phase ledger. Not touched, and recorded.** `state/phase-ledger.json` still reads `phase-000-bootstrap / planned / attempts: 0`. It is controller-owned and named as not a phase's in every prompt in this repository.

---

## 7. The one thing this pass found in its own work

**The failure this batch made is not a prose failure and it is the oldest one in this repository: a figure published beside a sentence that shows the figure is describing a habit, and a batch that measured the thing, named the mechanism, and then wrote *this record reports that as a measurement and not as a result*.** That sentence is the review's Finding 2 and the batch's own §3.4 and they are the same sentence.

**It is left in place and marked rather than deleted, at §3.4, in §11, and in `bible/power-system.md` §48 item 10.** A record that quietly rewrites itself is the failure this repository names, and the next writer needs to see what a well-measured batch record looks like when the measurement is the problem. **The same class of fault had already been caught in this batch's predecessor and was recorded there too, and the fact that it recurred, in a new costume, with better instrumentation, is the reason §3.4 now carries a rule and not a number.**

## 8. The next phase, and it is unchanged

**`workspace/volume-08/batch-0004/PROMPT.md`, and it is a BATCH. It writes Chapters 0381 to 0390, days 381 to 390, from a Thursday to a Saturday. No day, no chapter, no prohibition, no decision of record and no range in it moved in this pass.** It was repaired in four places: it no longer tells a writer to copy a defective habit uncritically, it binds §17 item 11a, it publishes both editions of Batch 0003's bolded share, and it carries Debts 6 and 8 by name under a heading that tells the writer they are not theirs to decide.
