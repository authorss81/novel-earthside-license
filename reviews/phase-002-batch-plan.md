# Review — phase-002-batch-plan (Batch 0001, Chapters 1–10)

Reviewer output: `logs/phase-002-batch-plan.review.log`. Fix pass: `logs/phase-002-batch-plan.fix.log`.
Scope: `chapters/volume-01/chapter-0001.md` … `chapter-0010.md`, `outline/volume-01.md`,
`outline/batches/volume-01-batch-0001.md`, `workspace/volume-01/batch-0002/PROMPT.md`, `bible/`, `state/`.

No chapter was rewritten. Fixes are surgical, the planned plot is unchanged, and the
System-panel budget (Chapters 1, 2, 7, 10 only) is unchanged.

## Verified compliant — no action needed

- System panel budget exactly correct: 4 / 3 / 0 / 0 / 0 / 0 / 4 / 0 / 0 / 4 blocks.
- No cohort member or the narration asserts this is a game; game vocabulary stays in Adrian's mouth.
- Nobody dies in the batch.
- The five lock sites stay distinct and are named consistently.
- Adrian never performs a working; locals run the Chapter 9 closure and the Chapter 10 binding.
- The Chapter 1 private design-note joke pays off in Chapter 7 and echoes in Chapter 3.
- The writer's canon additions to `outline/volume-01.md` and `bible/characters.md` match the prose.

## Fixed

| # | Finding | Fix |
|---|---|---|
| 1 | **Blocking.** `workspace/volume-01/batch-0001/` had no `.done`, so the runner would re-dispatch the finished batch and spawn a second `batch-0002`. | Added `workspace/volume-01/batch-0001/.done`. Dispatch order re-verified: `batch-0002` is next. |
| 4 | Verbatim 94-word duplicate shared by `ch7:181` and `ch8:181`. | Removed from Chapter 7. A re-scan of all paragraphs ≥120 chars across all ten files now returns zero duplicates. |
| 5 | The same paragraph was out of order in Chapter 7 — it referenced a voice that speaks 30 lines later. | Replaced with a Chapter 7-native beat about the sentence now being in a book nobody can revise. |
| 6 | `Renna Sesh` at `ch5:71` and `ch9:103`; canon is **Ord**, and "Sesh" collided with Sesh Brack. | Both corrected to Renna Ord. |
| 7 | Pronoun slip, `ch10:183` — Vail's action then "He put out his hand." | Now "Adrian put out his hand." |
| 8 | Owen's **leg** at `ch10` was never established; Mina's Chapter 5 triage lists five injuries and no leg. | Changed to his **scalp**, which Chapter 5 does establish, and which Chapter 10 already calls a scalp wound. `state/open-threads.md` and `state/character-state.md` updated; his shoulder stays reserved for Chapter 25. |
| 9 | Chapter 6 was missing a required beat: Owen's insistence, the room treating him as a crank until he nearly leaves, and Adrian making retrieval refusable. | Written as a full scene. Owen puts his coat on at four; the room turns on him because *one man and a rope* was said aloud in front of six people who were taken without asking; Sesh Brack stops him in the yard by naming the cost of each direction; Adrian refuses to dismiss a light he cannot see and makes the retrieval a question the wall's owners get asked in public. No workway, no panel, nobody dies. |
| 10 | The **thin black line on the palm** was canonised in the outline but never established in prose — the chapters gave a bleeding cut, then a "clean absence", then a "pale ghost". | Established in Chapter 8, where the overload happens: under the cut, Vask identifies a black line on a person, "not a punishment and not a reward", invisible because nobody steps over a hand. Carried explicitly through Chapter 9 and Chapter 10 as **separate from** the pale mark, which is the shape that decays and goes into the stone. |
| 11 | Scale contradiction: a thumbnail mark claimed to be "the same size" as a seam 18in × 3 fingers. | Rewritten as **proportion, not size** — "the way a coin fits the die it was struck from" — with the thumbnail covering the seam's lip exactly. Scale rule added to `outline/volume-01.md`, `state/continuity.md`, and `bible/terminology.md`. |
| 12 | The Chapter 0012 card turned on a leaked name coming out of a 310-year-old customs report that cannot contain an Earthside name. | Mechanism swapped for one the prose supports: the six names Adrian asked for in Chapter 5, written by Priya and posted on the loft wall above the market in Chapter 6. The old report stays — it is genuine, and that is *why* new gossip sounds like a roll. Marrow's complicity stays plausible and unproven. Turn, consequence, and ending of the card are unchanged. |
| 13 | The Chapter 0019 card moved the voice into the main breach, contradicting Chapters 7–8 and the five-sites rule. | The voice now arrives in the black line in the chapel stone, its home since Chapter 7; the gate is only being measured and does nothing. Added a hard constraint to the batch-0002 brief stating where the voice lives and that the main breach does not speak. |
| 14 | `Narrow Mark`, `holder of the pull`, and `socket` were absent from the bible. | All three added to `bible/terminology.md` with their limits, plus an extension to `Black line` separating the chapel-stone line from the palm line. |
| 15 | Timeline slip, `ch9:255` — 2 p.m. plus "eleven hours" is not first light. | Now "at first light tomorrow, in about sixteen hours". This exposed a **one-day drift** across the batch: the crier in Chapter 6 sets the tide for Thursday and the hearing for the day after, so Chapter 9 is Thursday pre-dawn and Chapter 10 is Friday. Chapter 10's three day-counts and one weekday reference were corrected, and a full day map was added to `state/continuity.md`. |
| 16 | `ch10:247` — Owen tells the permanent record "I was the second one." He was the **first** of the six out. | He begins the false claim, Mina corrects him from the front bench, Adrian confirms it, and Owen tells the clerk to put the true version in because he will get it wrong again. The ledger now receives an accurate sentence, and the batch's thesis is served rather than undercut. |
| 17 | Prolepsis used thirteen times, including two that broke Chapter 4's tight POV and one that leaked structure into the prose. | Cut five: `ch4` ×2 (both POV breaks, now present-tense), `ch6` ×2 (the "funniest thing that ever happened" flash-forward and the "problem in nine months" structure leak), and the Chapter 10 four-year flash-forward about the clerk. The remaining instances are in-character predictions in dialogue, which are load-bearing for the forward pull. |
| 18 | `ch2:63` spent a persistent headache that the card reserves for Chapter 4 with the nosebleed. | Replaced with an ordinary Stage 0 cost: he stares into the breach, nothing happens, and he is sick over the edge into water that does not change. The Chapter 4 pair is now the only place either appears. |
| 19 | No durable review artefact; the log is untracked. | This file. |

### Additional defect found during the fix pass

- `state/character-state.md` attributed Owen's Chapter 9 mistake to **"Mira's tear"** — a
  character who does not exist, at a site that is the outer tear and nobody's. Corrected.
- `state/character-state.md` and `state/current.md` still described Owen as "unwounded" and
  Priya's record as "nothing published". Both corrected.

## Not fixed — controller-owned

- **#2, stale `state/phase-ledger.json`.** The ledger still reads `phase-000-bootstrap` / `planned`.
  `state/phase-ledger.json` is GitHub-Actions-owned and is listed as never-edit in the writer
  agent definition, and the phase prompt's instruction to update "the phase ledger" is a prompt
  bug, not a writer error. The ledger is also not read by the runner — phase selection comes from
  the filesystem — so this is bookkeeping drift rather than a functional break. Left untouched.
- **#3, `phase-002-batch-plan` matching the `PLANNING_TIMEOUT_SECONDS` case.** The fix is in
  `scripts/novel_runner.sh`, which is controller-owned, and changing dispatch or timeout logic is
  forbidden. The batch completed under the planning timeout regardless. A later phase prompt
  should either stop telling the writer to update the ledger or the runner's case list should be
  corrected by whoever owns it.

## Note for the next reviewer

`state/current.md` now records a two-day-early prompt, `phase-003-batch-write`, which does not
exist as a directory. The runner dispatches from `workspace/`, so this is cosmetic, but the
phase name in that file should be corrected by the controller rather than the writer.
