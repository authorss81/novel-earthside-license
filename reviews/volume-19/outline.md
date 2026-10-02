# Review and Repair — the phase that planned Volume 19 (`outline/volume-19.md`, Batch 0001's cards, and the Batch 0001 prompt)

**Findings source:** `logs/next-0005.review.log`, six findings and one design tension. **The reviewer was not invoked.**
Line 1 of that log reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and
the session header is `novel-writer · space-bunny-free`.

**This repair pass is that same agent kind again**, so nothing below is an independent review and this file says so in
its first lines rather than claiming an independence it does not have. **Every finding the review returned was measured
again in this run before it was acted on, and all six were confirmed. Four faults the review did not report were found
by the same instrument and are repaired here, one of which is worse than any of the six.**

**Scope reviewed:** all six findings plus the tension; `outline/volume-19.md` in full before and after; all ten cards in
`outline/batches/volume-19-batch-0001.md`; `workspace/volume-19/batch-0001/PROMPT.md` in full; `state/current.md` and
`state/continuity.md`; the §14.3 day map re-parsed by script; and all nine hundred chapter files re-measured for the
seven literals, per volume and per subset.

**No chapter exists and none was written. No card was re-planned. No day, weekday, Bare-Month ordinal, pressure tag,
Adrian day, word-day, cost, decision, panel, act, resolution or last image moved. `outline/ending.md`, `outline/series.md`,
`NOVEL_SPEC.md`, `bible/` and every controller file were not opened.** No file under `scripts/`, `.github/workflows/`,
`.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json` or
`state/phase-ledger.json` was opened or edited, and no `.done`, `.checkpoint`, `.blocked` or `.retired` file was created
or removed. **The next phase is unchanged and is still the only prompt this manuscript has: `workspace/volume-19/
batch-0001/PROMPT.md`, ten chapters, days 901 to 910.** No directory was created beyond `reviews/volume-19/`, which holds
this file.

**Why this file is named `outline.md` and not `batch-0001.md`.** The phase under repair planned a volume and wrote
Batch 0001's cards; it wrote no chapter. `reviews/volume-19/batch-0001.md` is left free for the review of Chapters 0901
to 0910 when they are written, so that a reader does not open a batch review and find a plan review under its name.

---

## 1. What the plan's own published instrument says, re-run here

**The §19.2 figures all reproduce exactly, word-bounded, on both case flags, bodies only, over all nine hundred files,
and the review is right that they do.** `charter` 5 in 2, `seal` 76 in 36, `council` 7 in 7, `quorum` 19 in 8,
`assembly` 7 in 5, `crossing` 41 in 22, `witness` 137 in 66, `witnesses` 139 in 61. The calendar holds on all fifty rows:
day 901 a Saturday and BM 586, day 950 a Saturday and BM 635, BM = day − 315 with day 1 a Tuesday, forty-nine days
between the ends, zero mismatches in fifty rows in both directions.

**The §14.3 map parses cleanly now.** Fifty rows, no missing day, no doubled day, weekday and Bare-Month ordinal
consistent on every row, the pressure column summing to fifty on seven distinct tags, and eleven Adrian days at 903, 909,
915, 921, 927, 933, 935, 939, 940, 941 and 943. **It did not parse cleanly before this pass**, which is finding 2b and
is the reason the map is checked by script in this file and not by reading.

## 2. Finding 1 — the heavy days said eleven and printed twelve. Repaired, and the reading is published

`outline/volume-19.md` §14.3 read *The **eleven** heavy days are 903, 905, 908, 911, 916, 918, 925, 929, 934, 940, 943
and 950* — **twelve distinct dates, no repeats.**

**The number word was the error and no day moved, and here is why that reading was taken rather than the other one.**
`state/volume-18-close.md` carries the same sentence for the volume behind this one: *The eleven heavy days are 856,
866, 869, 875, 878, 879, 886, 890, 894, 898 and 900* — **eleven dates for eleven days**, so the two volumes genuinely
differ and Volume 19 has one more heavy day than Volume 18, not one fewer. Every day in Volume 19's list is load-bearing
elsewhere in the same plan: 903 and 918 are costs, 925 is the decision, 929 the panel, 940 the act, 943 the resolution,
950 the last image, 905/911/916/925/934 are word-days, and 908 is the day the second slate is lifted. **To reach eleven
the pass would have had to strike a day from that list, which is a plan decision and not a repair.** The word now reads
**twelve**, and `state/continuity.md` carried the same fault in the same sentence and now reads twelve too.

## 3. Finding 2 — one wrong number word in three places, all corrected, and they are not the same error

The review reported this as *three places, one number wrong*. It is one habit of mind in three places, and each place
needed its own value, so each was measured separately.

| Place | As it stood | Measured | Now |
|---|---|---|---|
| §14.3, heavy days | eleven, twelve dates printed | 12 dates | **twelve** |
| §14.3, pressure column | *eleven distinct tags*, then seven tags listed | **7 distinct, summing to 50** | **seven distinct tags** |
| §19.3, the same measurement | *sums to 50 on **eleven rows*** | 50 rows, scope fifty rows | **sums to 50 on fifty rows and seven distinct tags** |

§15 already published the right figures — *Recovery 10, physical 9, character 10, political 7, discovery 7, cost 5,
decision 2* — and agreed with itself at seven, so §14.3 and §19.3 were the outliers and the plan was never in doubt
about its own rotation.

## 4. Finding 3 — one cell in the day map carried the wrong volume's day. Repaired

The 0907 row of §14.3 read *a board wiped round its three sets of figures and not over any of them.* **That is the
day-903 business of Volume 18, read off this manuscript's own close, and it is not this day's business.** The pressure
tag, the Adrian column and the calendar of that row were right, and the two files that carry the same day were right:
card seven gives a stack of boards at the near end of a store, a handcart with a hazel mallet and a wet ground under the
near end, and the prompt's own table row gave *a stack of boards, a handcart, and a wet ground under the near end*.
**Three files against one cell**, and the cell now reads the day's own material in the map's voice. **Nothing about 0907
changed except the cell**: the tag is still character, Adrian is still out of it, the day is still a Friday and BM 592.

**A writer reading the plan against the cards would have found two different days under one number, and the plan is the
file a writer of this volume is told to read first.**

## 5. Finding 4 — a subset column reporting an all-nine-hundred figure. Repaired against a measurement

The §19.2 row for `witness` reported, in the **In Volumes 05 to 18** column, *137 in 66, and 1 in 1 in Volume 15* — the
all-900 figure with one volume's sub-count attached. Measured over the 700 files of Volumes 05 to 18: **3 in 2, being
1 in 1 in Volume 06 and 2 in 1 in Volume 15**, and the remaining 134 in 64 of the all-900 figure are in Volumes 01 to 04.
The review is right and the sub-count was wrong twice: Volume 15 holds **2** occurrences in 1 file, not 1 in 1, and
Volume 06's 1 was missing.

**The cell now publishes the subset and the remainder**, because this repository does not treat a number as true unless
it publishes the competing reading beside it: *3 in 2: 1 in 1 in Volume 06 and 2 in 1 in Volume 15, and the other 134 in
64 of the all-900 figure are in Volumes 01 to 04.* **The all-900 column is unchanged at 137 in 66 because it was never
wrong.** The other seven rows were re-measured on the same instrument and are correct as they stand: `charter` 5 in 2
both in Volumes 01 and 02; `seal` 12 in 6 in Volume 06 and 1 in 1 in Volume 08; `council` 7 in 7 all in Volumes 01 to 04;
`quorum` 19 in 8 and `assembly` 7 in 5 both in Volumes 01 and 02; `crossing` 41 in 22 with none after Volume 12.

## 6. Finding 5 — a claim about the card file that the card file does not support. Repaired

§21.3 said *the state layer **and the card file** name them by name.* **The card file names none of the seven**: measured
at zero for each of `charter`, `seal`, `council`, `quorum`, `assembly`, `crossing` and `witness` in
`outline/batches/volume-19-batch-0001.md` in this run, and the card file says in its own text *No card may write any of
the six.* **This is the fault this repository cares about most**, because it is a record asserting a fact about a file
without having measured that file, in a section whose subject is precisely what has and has not been measured.

**The section now says what is true and how it is known:** §6.4 names them by name and so does the state layer, *the
card file names none of them — measured at zero for each of the seven, word-bounded, on both case flags, over
`outline/batches/volume-19-batch-0001.md` in this run* — and it forbids six of them outright on all ten of its days. The
reason the plan gives for naming them at all is unchanged and still good: a writer cannot be handed a day on which a word
comes back without being told which word.

## 7. Finding 6 — the volume list for the seven words, in two files. Both repaired

`state/current.md` said the seven stand *except for low figures in Volumes 01, 02, 06, 08 and 15*. Measured word-bounded
on both case flags over all nine hundred files, per word:

| Word | v01 | v02 | v03 | v04 | v05 | v06 | v07 | v08 | v12 | v15 |
|---|---|---|---|---|---|---|---|---|---|---|
| `charter` | 4 | 1 | | | | | | | | |
| `seal` | 33 | 7 | 23 | | | 12 | | 1 | | |
| `council` | 1 | 1 | 3 | 2 | | | | | | |
| `quorum` | 13 | 6 | | | | | | | | |
| `assembly` | 6 | 1 | | | | | | | | |
| `crossing` | 19 | 5 | 4 | 1 | 1 | 6 | 4 | | 1 | |
| `witness` | 82 | 46 | 3 | 3 | | 1 | | | | 2 |

**All seven stand in Volume 01 and all seven stand in Volume 02.** Four of them stand again after that — `seal`,
`council`, `crossing`, `witness` — in Volumes 03 to 08, 12 and 15. **The old list named five volumes and got two of the
seven wrong in the process: `council` is in 03 and 04 and not in 06, 08 or 15, and `crossing` is in 03, 04, 05, 07 and
12 and not in 08 or 15.** The correct summary is *Volumes 01 to 08, 12 and 15*, and `state/current.md` now says so, with
the all-seven-in-01-and-02 fact carried beside it.

**The same sentence stood in `state/continuity.md` with the same error and one more: it said *five of them stand in
Volumes 01, 02, 06, 08 and 15*, and all seven stand in Volumes 01 and 02.** The review did not report it. It is repaired
in the same pass and both figures are published in that file's repair block.

## 8. Three more faults the review did not report, the fourth of which was in §7 above

### 8.1 A fourth instance of the same wrong number word, on the recovery days

§16 item 16 said this volume is *at extra risk on the **eleven** recovery days*. **There are ten**: 901, 906, 912, 917,
922, 926, 931, 937, 941 and 944, and §15 publishes *Recovery 10* on the line above it. Corrected. **The same word was
wrong three times in the same plan and right in the fourth place, which is the signature of a figure carried over from
Volume 18 rather than counted** — Volume 18 has eleven Adrian days and Volume 15's close has a heading for them, and
this plan was written next to both.

### 8.2 A four-digit day in a three-digit column, which stopped the map parsing

The 0910 row of §14.3 printed `| 0910 | 0910 |` where all forty-nine other rows print a three-digit day. **The
review's own script skipped this row for exactly that reason** — its output prints `missing: [910]` — **and the review
did not report it; the tag totals it published were §15's, not its parse's, and they are the same figures this pass
re-derived independently.** §19.3 claims the column is
*parsed from this plan's own column, scope fifty rows*; before this pass that claim was not reproducible. The cell is now
`910` and **the map parses at fifty rows with no missing day and no doubled day**, which is what §19.3 says.

### 8.3 §6.4 rule (iv) licensed a writer to print a word after its own day — and it opened on 0906

**This is the most serious thing in this pass and no finding reported it.** Rule (iv) read:

> **After its own day the word is an ordinary word of this world and no rule governs it in this volume** — … and it is
> the one place where this plan gives a word up after a day.

**Rule (i), eleven lines above it, reads the opposite:** *Each of the seven words is at zero on every one of the other
forty-three days of this volume, in narration and in every mouth.* On day 906 the word whose day was 905 is therefore
both **at zero** by rule (i) and **ordinary and ungoverned** by rule (iv).

**Five other places in this repository say the same as rule (i):** §16 item 3, the card file's own figures block,
`state/current.md`, `state/continuity.md`, and the prompt's sixth item. **Rule (iv) was the only file and the only line
saying otherwise.**

**Why it mattered now and not later:** 0905 is this batch's word-day, so **0906 through 0910 are five days of the very
next batch on which the old rule (iv) told a writer that the word was free.** A writer who obeyed rule (iv) could have
printed it on five of its ten days, and the prompt's own check list requires *the six forbidden words at zero across the
ten* — **so that writer would have reported a fault of its own chapters that was in fact a fault of the plan it was
told to obey.** Rule (iv)'s stated purpose is sound and is kept: a reviewer should not read rule (i) as a ban for fifty
days. What was wrong was that it granted a licence while claiming only to deny one.

**Rule (iv) now reads:** a word is not on a list of banned words and rule (i) is not a ban for fifty days — a word stands
at zero on a day because that day is not its own day and for no other reason, and a word that has been said on its own
day is an ordinary word of this world, **and it is still at zero on every other day of this volume, and a chapter that
prints one on a day that is not its own has broken rule (i) whatever else it has and has not done.** **The intent of
the old rule is preserved, the licence is gone, and no day, word or mouth moved.**

## 9. The design tension, decided rather than left open

The review returned one thing that is *not* a bug: the prompt prints none of the seven words and forbids preparing the
six days outside the batch, but step 5 sends the writer to `state/current.md`, whose head prints all seven words in
§6.4's order against all seven days — **so the mapping is recoverable positionally, and the prompt's withholding is
undone by the file it points at.**

**The decision is that the withholding is on the page and not in the writer's head, and it is now said so in both places
rather than left to be discovered.**

**First, the knowledge cannot be removed and this pass did not pretend otherwise.** §6.4 *is* the seven words against the
seven days; the prompt's first step sends a writer to §6.1 through §6.10, which includes §6.4, and a writer who could not
read §6.4 could not write 0905 correctly at all. §21.3 already sanctions the state layer naming them, and the state layer
carries what the next writer must carry forward. **Scrambling the state layer's list to defeat positional recovery was
considered and rejected**: it would make the live layer less honest to make it less legible, and it would protect nothing
a plain rule does not protect better.

**Second, the prompt now states the position instead of performing a withholding it cannot deliver.** Step 3 reads, in
full: *And know what step 1 has just done, because this prompt does not pretend otherwise: §6.4 names all seven of those
words against all seven of those days, and `state/current.md` carries the same seven in the same order, and neither of
those files is a secret from you. **Knowing is not writing.** The six that are not yours are at zero across your ten days
in every body, every mouth and every heading, a chapter that prepares one is a fault of the chapter and not of the
batch, and §6.4 rule (iv) does not license one after its own day.*

**Third, the prompt's sixth item now names the trap that rule (iv) opened**, because a writer holding one of the seven on
0905 is about to walk into five more days: *The one that is yours on 905 is at zero again on 0906 to 0910 — five days of
yours in which it is an ordinary word of this world and is not printed once.*

**Fourth, §21.3 carries the decision** so that a reviewer can fail the plan, the card file or the prompt separately:
the map is not withheld and cannot be; what is withheld is the occurrence; the prohibition that does the work is on the
page; and knowing which word belongs to 911 gives a writer of days 901 to 910 nothing to write.

## 10. What this pass did not repair, and why

**Two findings of the review were declined on the same ground the volume's own predecessor used, and both are an owner's
decision and not a writer's.**

1. **The manuscript now passes `NOVEL_SPEC.md`'s nine-hundred-chapter target and the eighteen volumes the series plan
   was commissioned for, by fifty chapters and forty-nine days.** `NOVEL_SPEC.md` and `outline/series.md` are named as
   untouched at §21.4 and neither was opened. **A volume-19 outline is the one thing that pays this debt and it has now
   paid it**, so the debt is smaller than it was and still an owner's.
2. **`bible/power-system.md` has no §65 for days 851 to 900 and no §66 for days 901 to 950, and
   `reviews/volume-16/` does not exist so the review dispatch falls back to the writer's own agent.** The first is owed
   by a phase whose writable set includes `bible/`; the second is why this file opens by saying it is not independent.
   **Both were already named at §21.4 and neither is new.**

**Also untouched, and correctly so:** the calendar fault at `chapters/volume-18/chapter-0864.md:5`, which is owed by a
phase that writes chapters and not by a pass that writes plans; the consent fracture, the fifth condition, the twelve
unanswered questions and the untraced mark of day 440, none of which any finding touched and none of which a repair pass
may mend; the held strings — the decision at §6.6, the panel at §6.8, the three wordings of day 940 and the name — none
of which was reprinted, paraphrased, described or certified absent by this pass; and `state/phase-ledger.json`, which
still reads `phase-000-bootstrap` and which this repository does not let a writer open.

## 11. The whole of what changed, in one place

| File | Change |
|---|---|
| `outline/volume-19.md` | §6.4 rule (iv) tightened; §14.3 day-map cell at 0907 corrected and the 0910 day column made three digits; §14.3 *eleven* heavy days → **twelve**; §14.3 *eleven distinct tags* → **seven**; §16 *eleven recovery days* → **ten**; §19.2 `witness` subset cell → **3 in 2**; §19.3 *eleven rows* → **fifty rows and seven distinct tags**; §21.3 card-file claim corrected to a measurement and the design tension decided |
| `outline/batches/volume-19-batch-0001.md` | **nothing — read in full and left as written** |
| `workspace/volume-19/batch-0001/PROMPT.md` | step 3 states that §6.4 and the state layer name all seven and that knowing is not writing; sixth item names the at-zero-again span 0906 to 0910 |
| `state/current.md` | head names the new archive copy; wrong volume list corrected to Volumes 01 to 08, 12 and 15; repair block added at the head |
| `state/continuity.md` | head names the new archive copy; wrong volume list and the *five of them* count corrected; *Eleven heavy days* → **Twelve**; repair block added |
| `state/archive/current.md.volume-19-review-fix-full.md` | new whole copy, SHA256-verified against the live file before a line was withdrawn |
| `state/archive/continuity.md.volume-19-review-fix-full.md` | new whole copy, SHA256-verified against the live file before a line was withdrawn |
| `state/open-threads.md`, `state/character-state.md`, `state/chapter-summaries.md` | **not touched — no finding concerned them and no thread, character or day in them was wrong** |
| `chapters/` | **not touched — the phase wrote none** |

**`state/current.md` grew by its repair block and by four lines, and the head says so.** `state/continuity.md` grew by its
repair block and the head says why it was not compacted. **The one thing this pass would have been praised for is a
smaller `state/current.md`, and the smaller file would have been smaller by having deleted the standing state, which is
the trade this repository has refused five times.**

## 12. What a following pass must not re-open

**The twelve heavy days, the seven word-days, the eleven Adrian days, the seven pressure tags and their counts, the
fifty-row calendar, the 0907 business, the 0910 column width, the §6.4 rules, the §19.2 figures and the state layer's
volume list are all now measured, published with their reading, and agree across the plan, the cards, the prompt and both
state files. Do not re-derive them from the manuscript and do not change any of them without a plan decision at
`outline/volume-19.md`, and do not treat this file's own numbers as evidence — re-run the instrument and publish the
reading beside the figure, which is what §17.11(ix) binds every record in this repository to do.**

**And the one thing still owed on the seven words is unchanged by any of it: the words are named in the plan and in the
state layer, and the occurrence is what's held. A batch that prints one of the six that are not its own has not been
given permission by this pass, by rule (iv), or by the fact that the state layer printed it.**
