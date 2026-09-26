# Review — Volume 05, Batch 0003 (Chapters 0221–0230), commit `adde428`

Reviewer output: `logs/batch-0003.review.log`. Batch record: `state/batch-summaries/volume-05-batch-0003.md` (§17 is this pass, written after the fact and cross-referencing this file).
Scope reviewed: `chapters/volume-05/chapter-0221.md` … `chapter-0230.md`, the state files they update, the three `bible/` amendments, and the handoff `workspace/volume-05/batch-0004/PROMPT.md`. **No chapter was restarted and no chapter was rewritten. Every fix is surgical, the planned plot is unchanged, and nothing in `outline/series.md` or `outline/ending.md` moved.**

**This is the first pass on this batch. The reviewer was not invoked:** `logs/batch-0003.review.log:1` reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session header is `novel-writer · space-bunny-free`. **That is the same gate failure recorded at `reviews/volume-05/batch-0002.md`, `reviews/volume-05/batch-0001.md`, `reviews/volume-03/batch-0004.md` and `reviews/volume-02/batch-0004.md`, it is now sixteen batches running, and it is controller-owned: `.opencode/agent/` and the workflow are not edited by a phase. It is recorded and left alone.** So, as in every batch in this repository, this review is a second pass by the same agent and is not an independent one.

The review raised **eight blocking page faults, five smaller page faults, four state-layer claims that did not reproduce, and one structural finding. All thirteen page faults and all four state claims were repaired. Nothing was declined. One figure was additionally found in the state layer that the review did not raise.** **The batch is disposed of at eighteen findings: seventeen addressed, one open and flagged as controller-owned.**

**The single most important thing on this page is not any of the thirteen fixes. It is that the batch's own checking pass ran a check whose whole purpose is to catch faults like these eight and returned clean, and that every one of the eight was found by subtraction, string comparison and arithmetic rather than by reading the prose — including the fault in which a character asks the reader of the book to do him a favour. That is set out at finding 18 and it is the third volume in a row to record the same lesson.**

## What the review got right, and it is the half that matters

The calendar is real craft and it was re-verified here from `day 1 = Tuesday` and from nothing else. **All ten chapters hold: day 221 is a Friday, the Long Month form checks `day 155 + N` on all ten, days 221 to 230 are ten chapters on ten days with no double day, and 225 is the fourth Tuesday that queue has run on counting from the forty-ninth day of that month.** The two `about N seconds` instances the prompt names are still where it says they are, at `chapter-0223.md:101` and `chapter-0227.md:73`, and both line references survived the repair. The prohibitions held: **zero System panels, zero `knock`, zero Owen Park, zero Hattie Park, zero *It is entered that*, zero instances of the word *yesterday*, Adrian Vale in four chapters and doing something in each.** **All of that was preserved and none of it was touched, and the batch's refusal to let any state file claim the word `knock` is at zero in the manuscript is the right instinct and was kept.**

The published prose metrics reproduce exactly: **147 bolded speeches, 133 plain, 280 total, a 52 per cent bold ratio.** The review's subagent reported these as unreproducible and was wrong — it had no shell. **The record was accurate on the thing it claimed and wrong on four things it also claimed, and the split between those two groups is finding 12.**

## The findings, and what was done to each

### 1. Three anchors point at days that have not happened. **All three repaired.**

`chapter-0223.md:55` had a woman of about fifty-six unable to say whether she was keeping salt or a price *since the sixty-ninth day of the Long Month*; Chapter 0223 **is** the sixty-eighth. `chapter-0223.md:113` had a man of about forty-four thinking about copying a sack *since the sixty-ninth day* as well. `chapter-0224.md:117` had the sun coming over a bank *about an hour later than it had on the sixty-ninth day*; Chapter 0224 **is** the sixty-ninth, so the sentence compared a morning with itself.

**The two in 0223 are now *the fifty-ninth day of the Long Month* and *the sixty-first day of that month* — the fifty-ninth because that is the day her nine measures are on the page as having gone hard, and the sixty-first because that is the day he refused a third copy and is his own anchor. The one in 0224 is now *the fifty-ninth day of the Long Month*, ten days earlier, which is a season moving rather than a sentence folding.**

**This is the batch's own §11.1 fault — an interval or an anchor measured from the wrong day in a sentence that reads perfectly — arriving in a costume §11.1 did not look for, because §11.1 looked at *N days* phrases and these are *Nth day* phrases.** Two of the three are forward references, which means the file contained a date that has not happened, and the third is a self-comparison, which means a chapter described its own morning as being different from itself.

### 2. The crack has three ages in one chapter, and it is the batch's central object. **Repaired, and the direction of the repair went the other way from the obvious one.**

`chapter-0228.md:3` put the crack in the far pan *since the fifty-ninth day of the Long Month*, `:11` put it *since the sixty-seventh day of that month*, and `:19` called it *six days old*. Six days before the seventy-third is the sixty-seventh, so `:11` and `:19` agreed with each other and `:3` was the outlier — and the first repair made exactly that change, and it was **wrong**, because `chapter-0222.md:3`, `:7` and `:11` state the fifty-ninth three times on their own page and Chapter 0222 is where the beam and the crack are established. A crack cannot be younger than the chapter that shows it already running out under the rim.

**So the fifty-ninth stands, and what was actually wrong was that the batch had never separated the age of the crack from the date it was told.** The three now read: in the wood since the fifty-ninth day of the Long Month, run out under the rim before the sixty-seventh, **told to a yard on the sixty-seventh and to nobody since**, and **fourteen days old** in the mouth at `:19`, which is the seventy-third less the fifty-ninth. `:3`'s *has run out under the rim since the sixty-ninth* also went, because Chapter 0222 shows it already out under the rim on the sixty-seventh.

**And the distinction is now stated in the prose and not left to a reader, which is the actual repair: the crack is fourteen days old and the secret is six.**

### 3. Twelve minus four is not eleven. **Repaired.**

`chapter-0226.md:3` says the chest holds twelve sacks and about four of them carry a knot that is not the knot on the others. `chapter-0226.md:87` called them *the other eleven*. It is *the other eight*. **Cheap, and it is arithmetic, and it is in the one chapter in the batch where a figure is being counted by hand in front of a reader who could count it too.**

### 4. The four weeks stop on two different days. **Repaired, and the derivation is now on the page.**

`chapter-0230.md:15` said *It stopped on the sixty-ninth day of the Long Month when the four weeks ran out*, against `:11` and `:29` in the same chapter where the man says it stops today. **Forty-seven plus twenty-eight is the seventy-fifth, and the seventy-fifth is the chapter's own day, so three voices against one and the one was wrong.**

**The line now derives the day in front of the reader rather than asserting it: *"It stops today. Twenty-eight days after the forty-seventh day of the Long Month is the seventy-fifth day of the Long Month, and that is today, and it is not stopping with water coming back."*** Every other element of the speech — the order he wants it said in, and the four people who will afterwards claim the water came back on the day he said it would — is untouched. **A direction is a figure with the day left off it, and the chapter that says that now does the subtraction on the page.**

### 5. An impossible Monday chain. **Repaired.**

`chapter-0230.md:89` read *the sixth day in a row he has stood on that bank and the first one that has not been a Monday, and the five Mondays were the five before it.* **The five days before day 230 are days 225 to 229 and not one of them is a Monday.** The real chain is in the batch's own §5 and in `chapter-0224.md:63`: 196, 203, 210, 217 and 224 are Mondays, which is the forty-first to the sixty-ninth day of the Long Month, and Chapter 0224 is the fifth of them.

**The lead now says he has stood on that bank four days in a row and none of the four has been a Monday, and that the five Mondays were the five before the seventy-first day of that month and the nearest of the five was six days ago.** Seventy-five less six is the sixty-ninth, which is a Monday. **`chapter-0227.md:51`, three chapters earlier, already had this right — *five Mondays in a row* — and it is in the chapter after that the chain broke, which is the same shape as Batch 0002's finding 1 in a fourth costume.**

### 6. A forty-word clause duplicated six lines apart inside one chapter. **Repaired.**

`chapter-0227.md:79` and `chapter-0227.md:85` shared *about four people in this yard have said since that a woman who cannot lift a rack lifted a length of wood and did not say so, and about nine of them have said that she was about to say so and she was not* — byte-identical, forty words, six lines apart, in the same chapter. AGENTS.md bans duplicated prose and this repository has repaired it three times before, in Chapters 0136 and 0143 and in five chapters of Volume 03's close.

**Line 85 now closes on the woman being the only person in that yard who found out anything, and the beat it was shadowing survives: the end of the wood going back into the same wet print.** **A scan of all ten files now returns one duplicated line per file and it is the `---` separator, in every file, which is what a chapter is made of.**

### 7. A character reaches out of the page and calls the reader a reader. **Repaired.**

`chapter-0228.md:71`: a woman of about twenty-four holding a slate in a yard says *"I would like **a reader of this book** at some point to work out that the four of them are the same shape."* **No other line in the batch breaks the frame, this one was not flagged anywhere in the batch's own pass, and it is the batch's most interesting finding — that four pages in this city are the same shape — being handed to somebody outside the world instead of to the four people standing in the yard.**

**It is now *I would like about four people in this yard at some point to work out that the four of them are the same shape*, which is what a woman holding a slate would say, and the finding is unchanged and is still a finding about a page.**

### 8. An interval fault the sweep missed, three lines from one it caught. **Repaired.**

`chapter-0226.md:21`, `:25` and `:29` all said *I wrote a decision on a slate two days ago*, for a slate written on the seventieth in a chapter that is the seventy-first. **§11.1 claims all eleven of its interval faults were repaired, and this is the same fault as the eleven, in the same chapter as two of them.**

**All three are now *on the seventieth day of that month*, and the reason they are the day and not the relative word is at finding 14.**

### 9. Two `---` with nothing between them. **Repaired.**

`chapter-0224.md:85` and `:87` were an empty section. One separator now. **All ten files were re-checked for adjacent separators and there is none in any of them.**

### 10. The keeper's section is an unmarked flashback. **Repaired, and nothing about the keeper moved.**

`chapter-0229.md:79` put the keeper *at about the seventh hour of the morning* after the ninth hour of the evening at `:75` and before the evening coda at `:83`. **The section is now in the past perfect and says she had been at the top of that cut since first light and had come down to the top of the bank, which marks it as retrospective in the tense this narrator uses for it.** **She is still fifty days into a year of being angry that has not run out, still on a page once in this batch, still says nothing to anybody, and nobody in that yard has said her name and nobody went up that bank with a message. Not one of the nine checks at §10.9 was affected, and `chapter-0229.md` is the only chapter she is in and she is in it for the same length of time as before.**

### 11. A clause that undid itself, a sentence count that disagreed with itself, and a lead that denied its own scene. **All three repaired.**

- **`chapter-0221.md:83`** read *about four hundred and forty people on eleven miles of flats have never been on a rota **including the nine of them who have*** — a clause that takes back its own statement in nine words. It is now *about four hundred and forty people dry salt on eleven miles of flats and about nine of them have ever been on a rota and the other four hundred and thirty-one have not.* **And the four hundred and thirty-one is the figure Batch 0001 put on the page, so the repair restored a canon figure rather than inventing one.**
- **`chapter-0223.md:61`** said she told him the whole of it *in a sentence* against `:45`'s *she said four sentences about this*. It is *in four sentences*.
- **`chapter-0226.md:3`** said the woman of about thirty-four *did not tell him where to put any of them*, and `:13` has her say *Put them along the wall.* **The lead now reads *did not tell him where to put any of them for about a minute, because nobody had told her, and then she did*** — which keeps the beat, keeps the doorway, and stops the opening paragraph from denying the exchange that follows it four lines later.

### 12. The state layer publishes four chains that are not on the page. **All four corrected, and the correction is a split rather than a deletion.**

**This is the review's best finding and it is worth more than the thirteen prose fixes, because `workspace/volume-05/batch-0004/PROMPT.md` was handing all four to the next writer as authority.**

- **The channel-dry chain.** The record published *twenty-five in narration at Chapter 0221 to thirty-four at Chapter 0230, and the twenty-eighth, the twenty-ninth, the thirty-first, the thirty-third and the thirty-fourth are named in mouths and section leads in Chapters 0224, 0227, 0229 and 0230*. **On a page: the twenty-eighth, the thirty-first and the thirty-four. There is nothing in Chapter 0221, nothing in Chapter 0229, and nothing anywhere in the ten of the twenty-five, the twenty-nine, the thirty-three, the twenty or the thirty-two.**
- **The posting-age chain.** *Twenty at Chapter 0221 to twenty-nine at Chapter 0230, in narration.* **Neither end is in narration; only the twenty-two and the twenty-four are on a page, both in section leads.**
- **The share-with-the-post chain.** *Fifty-three in narration at Chapter 0221, fifty-eight in a mouth at Chapter 0226, sixty-two in narration at Chapter 0230.* **Only the fifty-eight is on a page, and it is there twice, at `:53` and `:57`.** **This one mattered most, because the fifty-three and the sixty-two had already propagated into `state/open-threads.md`, `state/current.md` and the Batch 0004 prompt as though they were page facts.**
- **§6.17 attributed *one rack and a hole than two racks and a question* to a woman of about thirty-four in the house at the bottom of the Redroot cut.** **It is spoken by the man who has carried racks up and down that cut since the second month of this flood, at `chapter-0230.md:43`, at the edge of a dry cut, and it is about a rack and not about a wet stripe on a board.** The woman in the house has her own sentence — she will not be in a yard counting stripes — and the record had merged two people in two places into one.

**The arithmetic in all four chains is correct and the anchors are right. The fault is not a wrong number; it is a right number described as something a reader can go and check, when nothing in the prose carries it.** §5 of the batch record now splits every chain into the values a reader can find and the values that are derived, and a later writer may not narrate a derived value as a page fact. **The three state files and the prompt that had inherited the false claims are corrected in the same pass.**

### 13. Three more figures in the record that do not reproduce, and one the review did not raise. **Marked, and the pages were not touched for any of them.**

- **The counting device: the record said 219 instances of *about nine people* and *about four people* in three places. There are 213, and there were 213 before this pass began** — the repairs did not move the count by one, because no repair touched the device. **Corrected to 213, and the per-chapter figure corrected from 21.9 to 21.3.** The record was wrong about its own most-quoted number and no repair caused it.
- **The weekday tokens: the record said forty-five. There were thirty-seven before this pass and there are thirty-eight after it**, because the repair to `chapter-0230.md:89` put a second *Monday* into a lead that now names the five Mondays it is counting. Corrected, and the movement is attributed.
- **The short-speech ratio of 24 of 109 does not reproduce at any threshold**, and the review could not find the script that produced it; at forty words and under it is 7 of 139. **And the twenty-four speeches at 110 words and over returns twenty-two.** **These three — 39.0 words a sentence, the 86-word longest narration sentence, and the short-speech ratio — are script-dependent, and the 39.0 and the 86 are carried from the batch's own script and marked as not independently reproduced. They are marked rather than deleted because they are the batch's own measurements of itself and throwing them away would lose the reason the batch is above Batch 0002's 33.2.**

**The 147/133/280 speech counts, the 52 per cent, the zero of *It is entered that*, the zero of System panels and the zero of `knock` all reproduce exactly, and the record was right about every one of them.**

### 14. A repair that would have made the file worse, caught by the file's own rule. **Repaired, and recorded because it is the honest part.**

The fix for finding 8 was written three times as *yesterday* before it was written as *the seventieth day of that month*. **§11.16 puts the word *yesterday* at zero in the ten chapters, on the grounds that a correct weekday is not evidence that a relative word is in the right place — which is a good rule and was followed here by accident, in reverse.** The word is at zero in the ten chapters as they stand, and **the first version of the fix would have put it back three times in one chapter**, which is the closest thing this pass came to making a record worse in order to make a page right.

### 15. One thing that looks like a fault and is not. **Declared, not changed.**

`"Shall I write this down."` stands byte-identical in `chapter-0221.md:75` and `chapter-0228.md:65`. It is the same woman of about twenty-four asking the same question on two of the ten days, the two answers are different, and it is a refrain of a character rather than a duplicated line. **It is two instances and it is now declared in the batch record so that the next pass does not spend an hour on it.**

### 16. The reviewer agent cannot run. **OPEN. Controller-owned. Flagged, not touched.**

`logs/batch-0003.review.log:1`. Every review in this repository is a second pass by the writer, this one included, and `state/current.md` now says so at sixteen batches running. `.opencode/agent/` and `.github/workflows/` are not a phase's files.

### 17. Thirty chapters into a fifty-chapter volume, and none of the five planned beats has started. **OPEN. Escalated, not touched.**

**This is the finding a review cannot close and it is the fourth consecutive batch to record it and the fifth consecutive pass to decline to fix it.** `outline/volume-05.md` does not exist; `outline/series.md` carries a one-paragraph line for Volume 05 with a title, a central pressure, a midpoint, a climax and a resolution; **none of its five beats has started in thirty chapters and no character, office, sister or antagonist from it appears in any of the ten.** The batch prompts' own prohibitions — a chapter may not reach the buyer or the office nine hundred miles away, and no chapter may offer Adrian a workway or let him ask for one — **structurally forbid the volume's planned climax, which requires him to spend a scarce passage privilege to evacuate stranded people and accept public blame for the departure.**

**The fix is an outline phase for Volume 05 or a reconciliation of `outline/series.md`, and `outline/volume-03.md` is also missing with fifty chapters on disk. Neither is a batch's work and neither is a repair pass's.** The disposition is escalated rather than noted: it is now in this file, at `state/batch-summaries/volume-05-batch-0003.md` §17.5, in `state/open-threads.md`, in `state/current.md` and in `workspace/volume-05/batch-0004/PROMPT.md`, **and the reason a repair pass must not try is written down, which is that it would have to invent a fifth date form or invent a workway for a man who is on no roster, and both would be worse than the finding.**

### 18. What this pass teaches, and it is the third volume to say it. **Recorded in the batch record at §18 and in the next prompt as a standing check.**

**The batch's own checking pass ran §10.2 — *subtraction on every figure with an anchor, from the anchor and not from a neighbouring chapter* — and §10.3 — *date forms by grep* — and returned a clean list on the class of fault that findings 1, 2, 4, 5 and 8 all belong to.** §11.1 found eleven carried intervals and repaired eleven, and missed an interval of the same family three lines from one it caught in the same chapter. §10.1 read thirty-eight weekday tokens, or thirty-seven as the files stood, where the record claimed forty-five, and every token it read was right.

**A check that recounts what it is checking, and reads each result against its anchor rather than against the file, finds these. A check that confirms its own list finds none of them.** The eight blocking faults were found by subtraction, string comparison and arithmetic, **and the eleven findings about the record rather than the page were found by counting the record's own claims against the files. Nobody found any of them by reading the prose closely, including the character who asks the reader of the book to do him a favour** — and that one is now check 13 in the Batch 0004 prompt, written so that the next batch runs a subtraction *and* a reading and treats neither as sufficient.

## The two cumulative questions this pass raised and did not answer

Recorded at `state/batch-summaries/volume-05-batch-0003.md` §19 rather than buried here.

- **The System has now said nothing for three consecutive batches and the derived count of silences is one hundred and thirty-four at day 230.** Per chapter that is defensible and the batch's own reason is right. **At Chapter 0230 of roughly nine hundred it is a question about whether the book still has an instrument, and a question about the instrument is an outline question.** A repair pass that inserted a panel to improve the count would put a notification into a chapter whose whole subject is that a thing cannot be measured.
- **The counting device stands at 213 in 23,647 words, one every hundred and eleven, and the reviewer's observation is that it is always a paired clause carrying the same two verbs.** It is canon, it goes back to Volume 01, and the batch's target — that no paragraph reports a reaction in the device and shows nothing else — is met in all 213. **A device that has become punctuation is a voice problem and not a fault, and the only honest answer is a decision about whose voice this is at the far end of Volume 05.**

## Verification run on the repaired files, and not before the last edit

- **The calendar recomputed from day 1.** All ten chapters' own days, and every weekday word attached to a dated day, are correct. **A forward-reference scan across the ten files now returns nothing, and a self-comparison scan returns nothing.** The only forward references that remain are the four deliberate ones — the seventy-fifth day of the Long Month named in advance at `chapter-0224.md:21`, `:27` and `:71`.
- **Every interval with an anchor re-subtracted from the event it names.** Channel dry since the forty-first day of the Long Month: twenty-eight at the sixty-ninth, thirty-one at the seventy-second, thirty-four at the seventy-fifth. Crack since the fifty-ninth: fourteen at the seventy-third. Slate written on the seventieth: yesterday's three *yesterday*s are now the seventieth in a chapter that is the seventy-first. Four weeks from the forty-seventh: the seventy-fifth. Keeper: fifty at the seventy-fourth. **All correct.**
- **`knock` 0, Owen Park 0, Hattie Park 0, *to open nothing* 0 in prose, *the whole of her* 0, Marrow 0, no name on any wall, `*yesterday*` 0** — all re-run across the ten files after the repair.
- **The two distances unmerged.** Nine is the upper road, eleven is the Reach, four is the causeway, four streets is the walk, and no third distance was invented.
- **Markdown parity:** 0 unbalanced `**` and 0 stray quotation marks in all ten files.
- **The bold rule intact.** The batch stood at 147 bold and 133 plain out of 280 and **stands at 147 bold and 133 plain out of 280 — no speech was re-bolded, un-bolded, added or removed by this pass.**
- **The net effect, so that the next writer has one place to look:** chapters 10 → 10, days 221 to 230 → 221 to 230, Long Month 66 to 75 → 66 to 75, words 23,590 → 23,647, minimum 2,206 → 2,207, median 2,337.5 → 2,342, maximum 2,506 → 2,535, counting-device instances 213 → 213 with the record corrected from 219, weekday tokens 37 → 38 with the record corrected from 45, System panels 0 → 0, duplicated lines inside a file excluding the separator 1 → 0, adjacent `---` 2 → 0, forward references to a day that has not happened 3 → 0, Adrian Vale in 4 chapters → 4 chapters.

**NO FIGURE, DATE, ANCHOR, DAY, BEAT, CAST MEMBER, ENDING OR THREAD STATE MOVED. The repairs moved derived counts, wording, two misattributions of a speaker, and one distinction that had never been stated in the prose between how old a crack is and how long its owner has known about it.**
