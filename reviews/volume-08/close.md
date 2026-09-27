# Review and Repair — Volume 08 Close, commit `527e699`

**Findings source:** `logs/close.review.log`. **The reviewer was not invoked:** line 1 of that log reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session header is `novel-writer · space-bunny-free`, so this is a second pass by the same agent that wrote the close record, and it is the fifth review in a row in this repository done by the agent under review. `state/phase-ledger.json` is controller-owned and was not touched; see §7.

**Scope reviewed:** the Volume 08 close phase only — `state/volume-08-close.md` (new, 309 lines), `bible/power-system.md` §51 (new, 104 lines), `outline/series.md` *DECISIONS OF RECORD, VOLUME 09* (new, 68 lines), and the appended blocks in five state files. **No chapter was written, restarted or repaired. No plot, no beat, no ending, no day, no weekday, no month day, no anchor, no notice, no form, no object count and no cast member moved. `outline/volume-08.md` was not opened. `outline/ending.md` was not opened. No new final enemy was introduced. The antagonist ladder and the relationship milestones are untouched. Every figure the repairs moved is republished with the figure it replaced, in the file it was wrong in, and not only here.**

**The review raised ten findings. Eight are repaired, one is declined with a reason that is the runner's and not a writer's, and one is confirmed with nothing to do. Three further faults were found by this repair while verifying the review's arithmetic, and all three are in the same class as the ones the review named: a published count that does not reproduce under the instrument the same block published beside it.**

---

## 1. What the review got right, and it was most of it

**The day map is exact and was the finding most worth protecting.** I recomputed all fifty rows of §51 item 2 from day 1 being a Tuesday and from nothing else, checked every row three ways, and found **zero mismatches**: chapter equals day, weekday matches, and the Bare-Month ordinal equals day less 315 on all fifty. **The one row that is wrong about a weekday was not in the table — it was in the prose of item 4's trap column, which called day 440 a Saturday when the table six lines above it says Sunday, and the table is right.** The review found that and it is the kind of fault a count cannot see, because the count and the sentence are both about day 440 and only one of them was checked.

**All twenty-one interval-anchor rows in §51 item 3 recompute correctly at both ends.** §51 uses the next free number, amends nothing in §§32 to 33B, and the section number is the only one taken.

**The hold is verified clean and I re-ran it independently rather than taking the review's word for it.** I extracted all six bolded spans of Chapter 0357 programmatically, without printing any of them, and searched every `.md`, `.json`, `.sh`, `.yml` and `.txt` file in the repository outside `.git`, `node_modules` and `logs`. **Each of the six is in exactly one file, which is `chapters/volume-08/chapter-0357.md`.** The seven-word answer is not in `state/volume-08-close.md`, not in `outline/series.md`, not in `bible/power-system.md`, not in any of the five state files, not in the handoff, not in the close prompt, and not in the new prompt this repair wrote. The name spent in Chapter 0392 is not written in the chapter either, so *the name is on no file in this repository* is true and stays true.

**The close record has the required shape** — an inheritance paragraph, §1 to §6 as specified, plus §7 and §8 — and no month length, no seventh form and no ordinal-for-a-month language anywhere in the files the phase wrote.

**And the review's judgement on the ten-word run is right and I have applied it, which is the whole of §6 below.**

---

## 2. BLOCKING — the successor prompt was named in six files and never written. **Repaired.**

**`workspace/volume-09/outline/PROMPT.md` did not exist.** It is deliverable 5 of `workspace/volume-08/close/PROMPT.md` — *the one next phase, and exactly one, and you make it at the end of this run* — and it is named as the next phase by `state/volume-08-close.md:298`, by `outline/series.md` under Decision Three, and by `state/open-threads.md:686`, `state/character-state.md:935`, `state/chapter-summaries.md:308`, `state/current.md` and `state/continuity.md`. `workspace/volume-09/` did not exist at all. All five state files agreed on the path and none of them was wrong, and the file was simply not there.

**The consequence the review names is worse than a re-run and it is worth stating in the file it happened in.** `scripts/novel_runner.sh` calls `ensure_next_phase` only when `has_other_incomplete_phase` returns false, and it seeds `workspace/continuation/next/` with a prompt that says *if the current volume is complete, plan the next volume and write its first 10 to 20 chapter batch* — **one run that would plan Volume 09 and write Chapters 0401 onward together, and the outline gate this close spent four decisions building would have been gone, and `outline/volume-09.md` would never have existed.** A phase whose last act is to name its successor and does not make it has not handed anything on, and on this repository's dispatcher the cost of that is not a wrong prompt but the same wrong prompt forever.

**The file is written: a Volume 09 outline phase, ten to twenty cards, no chapter, four decisions to work inside, the candidate line audited and not adopted, §51 as a closed calendar, the corrected descriptor pool, the four instrument rules, the protagonist decision, seven debts carried, the hold, and exactly one next phase at `workspace/volume-09/batch-0001/PROMPT.md`.** It carries the corrected figures from this repair rather than the ones the close published, because a writer who inherits a false count inherits a decision made on it. **Its plot is not written anywhere in it: the line is a candidate and it says so, the document that puts the cast on a page is named as this phase's first act and is not chosen, and the number of chapters Adrian Vale is in is left to that phase as the close left it.**

---

## 3. BLOCKING — the completion marker, and this one is declined, and the reason is the runner's. **Not repaired, deliberately.**

The review's first finding is that `workspace/volume-08/close/.done` does not exist, that the dispatcher selects the first `PROMPT.md` lacking it, that all 43 other phase dirs have one, and that the consequence is the close re-running and re-appending four decisions and five state blocks on top of the ones just written. **The diagnosis of the symptom is right and the prescribed repair would break the phase, so this one is declined and the reason is published here so that the next reader does not "fix" it either.**

**`scripts/novel_runner.sh` writes that file itself, at line 302, and it writes it after this fix invocation returns:** the order in the script is the review, then this repair, then `commit_changes "novel: save review fixes $phase_id"`, then `ensure_next_phase`, then `touch "$phase_dir/.done"`, then `commit_changes "novel: complete $phase_id"`. **The marker is the last thing the runner does to a phase and it is created by the controller, not by the phase.** This is not an inference: `state/archive/continuity.md.volumes-01-to-06.md:846` records the same thing from an earlier run, in the words *the runner touches `.done` after the review and fix invocations return* and *do not create it by hand*.

**And the reason for the prohibition is mechanical, and it is the reason I am not touching it: if `.done` already existed when the runner got there, `commit_changes "novel: complete $phase_id"` would find nothing to change, print *Completion marker produced no commit*, and `exit 0` — before `clear_wip` runs, which means the WIP branch is never cleared.** A hand-written marker converts a clean completion commit into a silent early exit. **The file being absent right now is the normal state of a phase whose runner has not finished, and it is not a fault in the tree; the same absence was recorded and correctly left in `state/current.md:90` on an earlier phase of this volume.**

**What this repair did do about the actual danger the review identified, which is the re-run and not the marker, is remove the reason for one.** With `workspace/volume-09/outline/PROMPT.md` on disk, `has_other_incomplete_phase` returns true, `ensure_next_phase` returns early, and the generic continuation prompt is **not** seeded. **The re-run is still prevented by the runner's own marker, which is the only thing that should prevent it, and the fallback that would have destroyed the outline gate no longer exists even if the marker did.** Two of the review's two blocking findings are therefore closed, and one of them is closed by declining the prescribed repair.

---

## 4. Figures that did not reproduce under the instrument the same block published beside them. **Repaired, and the withdrawals are published in place.**

This is the review's findings 6, 7 and 8 and the review is right on all three, and I reproduced every number before changing one. **The instrument, re-published here so the figures below can be checked: a word-bounded count, the token bounded by whitespace, punctuation or a line end, case-sensitive, over whole files, taken over all 400 chapter files. I implemented the strip-punctuation reading and it reproduces nine of the thirteen published figures exactly and every file denominator exactly, which is what told me the reading was the right one and the four that moved were arithmetic and not a different instrument.**

### 4.1 The vocabulary row — four counts one instance high. `outline/series.md`, Decision Two

| Token | Published | Measured | Files (published = measured) |
|---|---|---|---|
| *man* | 6,613 | **6,612** | 398 |
| *thing* | 5,177 | **5,176** | 400 |
| *asked* | 4,535 | 4,535 | 398 |
| *hundred* | 3,873 | 3,873 | 392 |
| *person* | 3,247 | **3,246** | 387 |
| *page* | 3,028 | 3,028 | 370 |
| *road* | 1,988 | **1,987** | 333 |
| *column* | 1,052 | 1,052 | 239 |
| *form* | 832 | 832 | 207 |
| *roll* | 527 | 527 | 172 |
| *fence* | 124 | 124 | 23 |
| *boundary* | 127 | 127 | 54 |
| *boundaries* | 0 | 0 | 0 |

**Nine of thirteen reproduce exactly. Four are one instance high and every one of the four is high by exactly one, which is the signature of a hand-copied tally rather than a misread instrument.** The first edition is withdrawn in the file and not deleted. **This is the block's own Decision Five against itself two paragraphs earlier — a record that says its instrument is published when it is not is worse than a wrong figure, because it teaches the reader to trust it — and a block that breaks its own rule immediately after stating it is the fault the rule exists for.**

### 4.2 The crowded descriptors — three counts that do not reproduce on the denominator they were published against. `outline/series.md` Decision Four, and the same four in `state/volume-08-close.md` §7.7

| Descriptor | Published | Measured on 400 files | Published files | Measured files | Measured on **350** files |
|---|---|---|---|---|---|
| *woman of about thirty-four* | 351 | **362** | 142 | **147** | **351 in 142 — exact** |
| *man of about thirty-four* | 283 | **341** | 108 | **139** | **283 in 108 — exact** |
| *man of about forty-four* | 162 | 162 | 85 | 85 | **162 in 85 — exact** |
| *man of about thirty-nine* | 133 | **177** | 69 | **93** | **133 in 69 — exact** |

**The review's finding is right that the figures are wrong for what they were published as, and this pass found out *why*, and the why changes what a later writer must be told. All four of the published figures reproduce EXACTLY on the 350 chapter files of Volumes 01 to 07 — every one of them, to the instance and to the file count.** `outline/volume-08.md` §20.8 prints the identical four and correctly labels them *the four descriptors the 350-file map says are crowded*. **The close phase carried them out of that file and printed them as 400-file figures, in a sentence whose whole purpose was to say that a 400-file figure is the best guard this repository has against a merge nobody can see.**

**So the fault is not arithmetic and not a careless copy. It is a true count attached to the wrong denominator — the same disease as §4.3 below, and the worse of the two, because a reader who re-runs the published instrument cannot reproduce the published number and concludes the instrument is broken rather than that the sentence was.** The three that moved are corrected to their 400-file figures. **`man of about forty-four` stands at 162 in 85 on both denominators, and that one figure in four reproducing by accident is precisely what let a denominator swap survive a review of ten findings.**

**`outline/volume-08.md` §20.8 IS NOT AT FAULT AND IS NOT AMENDED BY THIS PASS, and that is the finding that matters most in this subsection: its four figures are right and they are about 350 files.** A repair pass that had "corrected" §20.8 to the 400-file numbers would have destroyed a correct plan-layer figure to match a wrong state-layer one, and the review's phrasing — *materially off* — is exactly the phrasing that invites that. The decision that the crowded four may not be given to a new person survives and is stronger, because on the correct denominator they are busier than either edition said.

The review's figures for the first two match mine exactly; its figure for *man of about thirty-nine* is two instances below mine, because of whether the search admits a following hyphenated segment. Under the strict word-bounded reading of the block's own published definition it is **177 in 93**, and that is the figure now published, with the definition beside it so a reader can get it or not. The twelve pool figures and all thirty-five zeros in the line-availability list reproduce exactly on 400 files, as does *man of about thirty-seven* at zero across Volumes 07 and 08, and *labor* at zero against *labour* at 55 in 36.

### 4.3 A pool described with the count of the crowd in it — a fault this repair found and the review did not. **Repaired.**

**The close block wrote *nineteen descriptors are at zero across Volume 08's fifty files* and then listed twelve.** **Nineteen is a true figure about a different thing: it is the number of distinct descriptors standing ON Volume 08's fifty files. Twelve is the number of Volume 07's descriptors that are at zero in them, and it is the size of the pool.** I measured all three numbers on the block's own published descriptor instrument: **29 distinct descriptors on Volume 07's fifty files, which reproduces `outline/volume-08.md` §20.8's map row for row including the row count, 19 on Volume 08's fifty, and 12 in the pool — and the twelve measured are the twelve the block listed.**

**The sentence is corrected to twelve, and the reason is published beside it, because a pool described with the crowd's count is a pool a writer will draw a returning person out of.** A descriptor map is the instrument that keeps a new person from being merged into an old one, and the sentence that sizes the pool is load-bearing. **This is the ninth class of the same fault: a count that is true, attached to the wrong noun.**

### 4.4 The bold-mark counts — wrong, and one of the two claims made about them is false. `outline/series.md`, fault (3)

The block published *an odd number of bold marks* in four files and gave them as **599, 3707, 1393 and 4362**, adding that *every one of those four figures is odd* and that *the additions this block and the four state blocks made are all even*. **Both claims are false and the figures belong to no measurement I can reproduce.**

| File | Published | `0ad1535` | Parity at `0ad1535` | Additions | At `527e699` |
|---|---|---|---|---|---|
| `outline/series.md` | 599 | **665** | odd | +139 | 804, even |
| `bible/power-system.md` | 3707 | **4320** | even | +194 | 4514, even |
| `state/current.md` | 1393 | **842** | even | +28 | 870, even |
| `state/character-state.md` | 4362 | **1901** | odd | +94 | 1995, odd |

**Two of the four are odd, not four. Three of the four additions are even and the block's own is odd at +139 — and because 665 was odd, adding 139 made `outline/series.md` even, so the block published an inherited odd count and evened its own file by accident and not by design, which is the more interesting half of the fault and the half the first edition got backwards.** `state/character-state.md` is off by 2,461, which suggests the figures came from a different file or a different instrument; the corrected ones are published with the commit they were measured at, and all three sets are given so a reader can see the inherited state, the phase's contribution and the state at the end of the run.

**The fault is real and it is inherited: one file of the four carries an odd number of bold marks at `527e699` and it is `state/character-state.md` alone.** It is not repaired here, and §4.5 says why.

### 4.5 A line pointer to a line that had not existed for two volumes. **The pointer is repaired; the fault itself is carried, not repaired.**

**Fault (4) of the same block published a stray quotation mark at `state/character-state.md:2260`.** `state/character-state.md` is **935 lines long** and has not been that long since the Volume 08 Batch 0003 review repair pass moved everything before Volume 07 to `state/archive/character-state.md.volumes-01-to-06.md`. **Re-measured on the file as it stands: exactly one line carries an odd number of straight double quotation marks, it is line 223, and it carries one. And it is the same line as the bold-mark fault — line 223 carries nine bold marks where the bold spans on that line come to eight, so one of the nine is unpaired, and that one unpaired mark is the entire odd count in the file.** So faults (3) and (4) are one line and one pair of characters, and the block published them as two.

**The pointer is corrected to `:223` and the two are published as one. The two characters are not repaired here, and the reason is the same reason the close gave for the nineteen quotation marks: the file is a live state file that a writer reads before planning anything, and a repair pass that guesses which of the nine bold marks on line 223 is the stray one has made a worse file than the one it was sent to fix.** It is routed, with the line, the count and the co-location published, to a Volume 06 review repair pass. **A stale pointer is the expensive kind of this fault, because it does not fail visibly: the fault is still there and the reader who follows the pointer is sent to a line that does not exist and concludes there is nothing to fix.**

---

## 5. Factual errors inside §51. **Repaired, and none of them moved a day.**

1. **The day-440 trap row called day 440 a Saturday.** Day 440 is a **Sunday** — 401 is a Wednesday and 440 − 401 = 39 = 5 × 7 + 4 — and §51's own table says Sunday six lines above. The row's substance survives, because a Sunday still puts a round figure at the end of a week, and the corrected row says *a Sunday* and *at the end of a week*.
2. **Item 4's heading declared FIFTEEN round figures over a table of EIGHTEEN rows.** The table is 401 ×3, 407, 418, 424, 425 ×2, 429, 435, 440 ×2, 441, 443, 445, 448, 449, 450. **Seventeen are multiples of fifty and the eighteenth is the one multiple of twenty-five, which the item already said was named at the end.** The heading, the count in it and the rule sentence are corrected to eighteen, and the row count is now stated where a reader can check the rows against the number. `outline/volume-08.md` §14.6 makes the same kind of declaration with 7 rows over 7 rows, so the pattern was followed correctly and the count slipped.
3. **Item 2's stated reason for day 450 did not derive the result.** *Because 449 is not a multiple of seven and neither is 400* is not an argument that produces a Wednesday; 449 is a Tuesday and 400 is a Tuesday and the sentence is simply false as a derivation. **The result was right and the reason was not, which is the worst combination, because a reader who checks the weekday finds nothing wrong and a reader who checks the reasoning finds everything wrong.** Corrected to the derivation that works: **450 − 401 = 49 = 7 × 7, and a day seven multiples of seven after another is the same weekday.**
4. **Item 2 called day 425 *the midpoint of this range* and item 4's day-425 row called it *the midpoint of the range*.** A fifty-day range has two middle days, 425 and 426, and its midpoint is 425.5. Both are corrected to *the nearer of the two middle days*, and the correction says why the distinction matters: neither of the two may be called the midpoint.

**No row of either table moved, no day moved, no month day moved, no anchor moved, and §51 still amends nothing in §§32 to 33B and still takes only the next free section number.**

---

## 6. The hold, and the one thing the review found that the letter of the rule does not cover. **Repaired.**

**The seven-word answer and the six-word refusal remain in `chapters/volume-08/chapter-0357.md` and `chapter-0393.md` and nowhere else in this repository, and I re-verified that after making every repair below.** No repair introduced a leak and no repair had to remove one.

**What the review found is a different speech in the same room on the same day: a ten-word verbatim run of the woman of about twenty-nine's line, reproduced in `state/volume-08-close.md:23` and `state/character-state.md:899` — the ten words that say what she would write and what she would not.** The review is right that the rule as written covers only the man's answer, so no prohibition was broken, **and it is right that this is the same leak by another route, because the prompt's own test is *a sentence in your own words that reproduces it is the same leak by another route*, and the aggravating fact is that the run sat one line away from a description of a different event four days later in a different register which reads almost the same, in the two files a writer reads before planning anything.** **The run is not quoted in this record either, and that is deliberate: the first draft of this section quoted it in order to name it, and the check at the end of this pass found the review record reproducing the exact fault the review found, which is the whole of the finding in one sentence.** A review of a leak that commits the leak is the clearest evidence that the rule has to be a rule and not a warning.

**Both are paraphrased. What is now in those two files is a statement of what she said she would do and not do, in the record's own words, and the *not* is the whole of it — which is the part that matters, because the part that mattered was never the wording.** The paraphrase is recorded in both files rather than made silently, with the reason, on the same principle the rest of this repair follows: **a silent correction is the third version of the same fault, and a writer who has read the first edition and the second deserves to be told that the sentence changed and why.**

**And the standing rule this produces, which is a decision and not a repair: the hold covers a held sentence and a state file may not copy a mouth at all, because the antagonist of this volume is a method and the method is a name at the top of a piece of paper, and a repository that printed a page would be doing the thing the volume is about.** A page in this book costs something to produce and a file in this repository is not a page.

---

## 7. The debts, all carried, all re-measured, none repaired. **Seven, not five, and the close published five.**

**Every one of the seven is at the line number this record gives it, and this repair took none of them and repaired none of them, because a repair pass that quietly takes a routed item to save itself a line is how nineteen quotation marks became a four-volume debt.** Re-measured on the files:

1. Nineteen stray closing quotation marks in Chapters 0281 to 0290, at `0281:37,65,81`, `0282:31,39,57`, `0283:47,53`, `0284:13,39`, `0285:39`, `0286:63`, `0287:25,41`, `0288:43`, `0289:31,49`, `0290:9,25`. Nineteen lines, every one at exactly that number. **Unpaid, Volume 06.**
2. `chapters/volume-07/chapter-0341.md:149`, *the word on the slate has sixteen days left on it*, where 342 − 341 = 1. Still there, still on line 149. **Unpaid, Volume 07.**
3. A thirty-nine-word run shared by `chapters/volume-06/chapter-0254.md` and `chapter-0262.md`. **Unpaid, Volume 06.**
4. An unmarked first-person paragraph at `chapters/volume-04/chapter-0175.md:47`. **Unpaid, Volume 04.**
5. ***About two hundred rooms* on five people and a woman across nine chapters of Volume 08**, where the state layer once said zero. **Carried with the rule decided and the attribution unpaid, Volume 08.**
6. Three sentences in `chapters/volume-08/chapter-0364.md:3` and `chapter-0396.md:29` and `:63` putting the shut road above or at the top of this city. **Unpaid, Volume 08, and one of the three is a woman's speech in a room with a date on the door.**
7. Two figures in `bible/power-system.md` §50 item 9 that are Batch 0005's ten files and read as a conflict beside the close record's fifty-file figures. **A figure and not a fault; the close names which is which and neither is wrong.**

**The eighth, found by this repair and added to the list: the stray quotation mark and the unpaired bold mark on `state/character-state.md:223`.** See §4.5. **Unpaid, Volume 06, and it is the one item on this list whose published pointer was itself wrong, which is why it is worth two lines here.**

**And the seven debts are in the new successor prompt by name, at their length, with the string to assert and the replacement published for the one that is a single word, so that the outline phase inherits debts and not surprises.**

---

## 8. What this repair changed, and what it did not

**Changed, in full:** `bible/power-system.md` §51 items 2 and 4 (four corrections, no day moved); `outline/series.md` — Decision Two's vocabulary row, Decision Four's crowded descriptors and the pool count, and fault (3)'s counts and fault (4)'s pointer; `state/volume-08-close.md` — the two crowded-descriptor figures in §7.7 and the paraphrased sentence in §1; `state/character-state.md` — the paraphrased sentence. **Created:** `reviews/volume-08/close.md` and `workspace/volume-09/outline/PROMPT.md`. **Appended:** one review-repair block to `state/continuity.md` and one to `state/current.md`.

**Not changed, and each for a reason stated above:** no chapter file; no day, weekday, month day, form, notice, anchor, interval table or object count; no cast member and no descriptor decision; `outline/volume-08.md`; `outline/ending.md`; the antagonist ladder; the relationship milestones; the four decisions of record, except that two of their published figures are corrected and their first editions withdrawn in place, **which is a correction and not a re-decision — the voice is still confirmed, the candidate line is still a candidate, the calendar is still §51's, and the cast is still the pool;** and the six debts this repair did not take.

**Not touched, because they are controller-owned:** `scripts/novel_runner.sh`, `.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json`, `state/phase-ledger.json`, and — the one that matters most for the finding in §3 — **`workspace/volume-08/close/.done`, which the runner writes and which a phase may not write.**

**The next phase is `workspace/volume-09/outline/PROMPT.md`, and it is a Volume 09 outline phase and not a batch and not a close. It writes no chapter. `state/current.md`, `state/continuity.md`, `state/open-threads.md`, `state/character-state.md` and `state/chapter-summaries.md` all name it and none of them disagrees with any other.**
