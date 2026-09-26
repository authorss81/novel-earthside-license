# Review — Volume 05, Batch 0001 (Chapters 0201–0210), commit `b270afa`

Reviewer output: `logs/batch-0001.review.log`. Batch record: `state/batch-summaries/volume-05-batch-0001.md` (§16 is this pass, written after the fact and cross-referencing this file).
Scope reviewed: `chapters/volume-05/chapter-0201.md` … `chapter-0210.md`, the state files they update, `bible/power-system.md`, and the handoff `workspace/volume-05/batch-0002/PROMPT.md`. **No chapter was restarted and no chapter was rewritten. Every fix is surgical, the planned plot is unchanged, and nothing in `outline/series.md` or `outline/ending.md` moved.**

**This is the first pass on this batch. The reviewer was not invoked:** `logs/batch-0001.review.log:1` reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session header is `novel-writer · space-bunny-free`. **That is the same gate failure recorded at `reviews/volume-03/batch-0004.md` and it is controller-owned: `.opencode/agent/` and the workflow are not edited by a phase. It is recorded and left alone.** So, as in every batch in this repository, this review is a second pass by the same agent and is not an independent one.

The review found **eight findings: three continuity faults, two house-style faults, three claims in the batch record that do not reproduce against the files, an unidentified speaker, and three local prose faults grouped as one.** All eight are disposed of below. **Seven were repaired and one was checked and declined**, and the declined one is recorded as declined rather than quietly dropped.

**And the repair found three more on its own, in the same family as finding 1, and they are set out at the end of this file. The batch is disposed of at eleven findings: ten repaired and one declined.**

## What the review got right, and it is most of the batch

The prose is finished fiction. The ten days are ten consecutive days with no double day, the day map is arithmetic from `day 1 is a Tuesday` and nothing else, and the batch's real discipline is that **nobody got stronger**: a page went up on a wall and made no wage, a man put the only functioning thing in this city ninth on a page on purpose and said so out loud for nine days, a man said no on a document he is a party to and found a second hole in his own sentence on the day he used the right, a woman found out that the price she named was the small half of what she got, and Adrian Vale said his own name in a room and could not answer the question he was fetched for. **The codas run 24 to 44 words, one image each, and ten of ten are bold, which is the house form and not a fault: 46 of Volume 04's 50 chapter-final lines are bold.** The texture-breakers are real and in the right places — a bar of chalk and a wet cloth, a rod put back in a different hole, a bell rang twice on a rail, a board with a date washed onto the top of it. **All of that was preserved.**

**And the review's own verified-clean list was re-run rather than trusted, and it holds:** word counts, `knock` at zero, `a person who does not want to be asked` at zero, `in about nine seconds` at zero, Marrow, Owen Park and Hattie Park unmentioned, `Adrian` once, the posting-age chain 4 to 9, the causeway chain 7 to 13, the unpaid-days figures at 119 and 125, the Long Month subtraction on all ten chapters, the keeper's age of about thirty-eight in both volumes, and the two distances.

## The findings, and what was done to each

### 1. `chapter-0201.md:81` — the recorder's gender is flipped. **Repaired.**

*"the **man** of about twenty-four who has written down every decision this city has made since the second day of this flood wrote the two numbers down separately"* — she is a **woman** on the page in `volume-03/chapter-0140.md`, `volume-04/chapter-0182.md`, `:0188.md`, `:0196.md`, `:0199.md` and inside Volume 05 at `:0204.md`, `:0206.md`, `:0207.md`, **and eighteen lines later in the same chapter** at `:0201.md:99`. One word changed: `man` → `woman`.

**The second half of this finding is a state-layer finding.** The batch record's §10.10 claims the phantom check returned *"No phantom. No two people merged."* It did return that, and the check had not been run over the sentence the reviewer found. **The audit at §10.10 has been rewritten to include the two people it omitted — a man of about twenty-nine from the settlement's workroom, who wrote nine of the eleven lines, and a man of about thirty-nine who trades on the Open Hand board, who carries the opening exchange and the argument about a figure and the question about administration — and to say that the check missed them.**

### 2. `chapter-0209.md:9` put a name on a wall that `chapter-0206.md:63` rules out. **Repaired.**

Chapter 0206 has the man of about thirty-four say, in a yard on the fifty-first day of the Long Month: *"there is not one name on that wall. There is not one name on it anywhere."* Chapter 0210 has him say the page *"did not put a name on a wall."* Chapter 0209 said the page Adrian Vale is on *"has been on a wall for eight days"* — and eight days before day 209 is day 201, which is the posting.

**The page his name is on is the compact, dated the forty-fifth day of the Long Month, day 200, and it is not on a wall.** The sentence now reads: the page *"was written down nine days ago in a room with a date on the door, and the front of it is on the back of a slate in this city and on about nine other things, and not one of the ten of them is on a wall."* That is what Chapter 0208 puts face up on the boards of a stall by a wharf, and it agrees with `bible/power-system.md` §27.3 and §27.11. **The repair makes the chapter stronger: the name he was fetched by is on a copy in nine hands and a word in four mouths and on no wall at all, which is the batch's own finding that a page can be taken down and a word cannot.**

### 3. The slate's hang date was given three ways and rested on an undefined week. **Repaired.**

- `chapter-0204.md:29` fused the *asking* — the seventh hour of the evening on the thirtieth day of the Long Month, day 185 — with the *hanging*, as if they were the same night.
- `chapter-0210.md:11` said *"Saturday morning of last week"* and *"nine days"*, which needs weeks to run Tuesday to Monday.
- `workspace/volume-05/batch-0002/PROMPT.md:40` asserted the forty-sixth day of the Long Month.

**One date now: the Saturday morning of the forty-sixth day of the Long Month, day 201** — three days before Chapter 0204 and nine days before Chapter 0210 — and the asking and the hanging are two things sixteen days apart, as they now read in 0204. **And all nine week-relative phrases in the batch that carried a figure are day anchors:** the forty-fourth for the nine sentences in a room, the forty-fifth for the reading of the compact and the copying of a page, the forty-sixth for the wall and the slate. `day 1 is a Tuesday` fixes every weekday; **no week-start convention exists in this repository and the batch no longer needs one.** The prompt at line 40 was already right and is unchanged on the date.

### 4. Every speech in the batch was bolded. **Repaired.**

All 260 speech lines in the ten chapters were `"**…**"`. Volumes 01–04 bold selectively: `volume-04/chapter-0161.md:21` is plain and `:23` is bold, and across Volume 04 only 59 of every 100 speech lines are bold, with short lines plain (31 per cent bold) and long lines not (80 per cent bold). **Volume 05 was at 100 per cent in both bands, which is what the review means by bold marking all speech regardless of content, and it voided the semantics §5 of the batch record asserts.**

**The ten files now stand at 173 bold and 87 plain, and the rule is restored to what §5 always said it was: bold marks a figure, a cost, a finding or a refusal in a mouth, and plain marks the rest of the conversation.** Twenty-one of the 103 short speeches are bold against 20 of the 100 in Volume 04; 95 per cent of the long ones against 80. Each of the 87 lines was chosen by hand against that rule, not by script.

**Verified as formatting only:** every file was diffed against its pre-repair copy with all `**` stripped and **not one word of prose differs**, and the batch's word count was 23,966 before and 23,966 after. `**` and `"` parity is even in all ten files.

### 5. All ten chapters opened on a day-and-weekday recap ledger. **Repaired.**

Line 5 of every file was *"It is a <Weekday>. The queue's day is a Tuesday. The posting has been up N days… The causeway has had nothing on it for N days."* — the same construction, ten times out of ten. `state/batch-summaries/volume-04-batch-0002.md:95` records the identical fault in Volume 04 and the identical remedy: *"All twenty chapters carried a bolded `**It is a <weekday>.**` ledger paragraph in the second block. All twenty were unbolded and rewritten as ordinary narrative in the review repair pass."*

**All ten were rewritten as ordinary narrative, in the present tense, with each day's figures kept in narration and no paragraph opening on a weekday. The ledger construction is now in none of the ten.** Every figure survived: the posting-age chain 4, 5, 6, 7, 8, 9; the causeway chain 7, 8, 9, 10, 11, 12, 13; the anchors for the causeway in 0201 and 0202; the hundred and forty paid and not paid in 0201; the nine hundred measures of salt; the chalk on the ledge; the keeper at thirty days into her year. **No opening, scene, beat, day or ending moved, and the eleven words about the ninth line being the top of a page in `chapter-0201.md` are untouched.**

### 6. Three claims in the batch record did not reproduce. **Corrected where they stood; the prose was not bent to fit them.**

- **§7.2** claimed a grep for a whole bold line *"returns the section leads only"*. It returns the section leads **and all ten codas**. **A bold coda is the house form** — 46 of Volume 04's 50 — so this is a claim error, not a prose fault, and the claim is corrected.
- **§7.3** claimed the codas carry *"no figure in it and no population in it"*. `chapter-0201.md`'s coda carries *about four people* and `chapter-0210.md`'s carries the man of forty-two and nine miles. **Both were left on the page and the claim was corrected, because the first is the sentence `bible/power-system.md` §27.1 rests on and the second is the last image of the batch, and each is one image and one population, which is what the instruction asks for.**
- **§7.4** named 0201, 0205 and 0208 for the *about N seconds* motif. 0205 has none. The three instances are `chapter-0201.md:91`, `chapter-0208.md:63` and `chapter-0209.md:21`, one in each of three chapters. Corrected.

### 7. An unidentified speaker, and an unaudited co-author, in Chapter 0201. **Repaired.**

The chapter opened an exchange with two unattributed speeches, and then at `:91`–`:97` had *"the man who wrote the page"* answer a question while the speech itself referred to *"the man who wrote the sentence against it"* in the third person and to *"he is standing about nine feet from you"*, so the reader could not tell whether the man who wrote the page was answering or being answered about.

**Two fixes.** A sentence now identifies the opening exchange: a man of about thirty-nine who trades on the Open Hand board is in the yard, has not been in the room on the Thursday, reads all of it standing back from the wall and says the first thing anybody says about it, and the man who had written the page answers him. And the answer to *then who administers that* is **now in the first person** — *"I put that line in myself in a room on Thursday with my name and the date on it … and I am standing about nine feet from you"* — so that the man of about thirty-four who keeps a stall is answering his own sentence, which is what the scene's closing sentence already said was in the room. **The co-author, the man of about twenty-nine from the workroom who wrote nine of the eleven lines, is in the cast audit at §10.10 of the batch record now and was not before.**

### 8. Three local prose faults in Chapter 0210. **Two repaired, one declined.**

- `chapter-0210.md:55` began a sentence in a lower case in the middle of the digger's speech. **Repaired.**
- `chapter-0210.md:91` said about nine people were paid on the last Tuesday *and that one week of that went on the last Tuesday*, which cancels itself. **Repaired** to *one week of that is still in the chest*, which is what Chapter 0204 puts on the page: a chest with two weeks in it on day 200, a payment on day 204, and one week left.
- `chapter-0210.md:77` says **a man of forty-two** where the finding says every other instance in the batch is *a man of about forty-two*. **Declined, and this is a finding of fact that does not hold.** Counted: the bare form is **six** and the *about* form is **nought** across the ten chapters, and across the manuscript it is **seventy-nine bare against twenty-four with *about***. **The bare form is the house form, the sentence is correct as it stands, and it was not changed.** A reviewer finding is evidence and is not a ruling; this is the first finding in this batch's family that was checked and declined, and it is recorded rather than dropped.

## The three the repair found on its own, in the same family as finding 1

**Finding 1 sent the look at a descriptor, and a descriptor is where this manuscript's phantoms come from:** `state/volume-03-close.md` §4 records that the device produced a phantom ninth stall-keeper off one wrong word in Chapter 0149. **Every *man or woman of about N* descriptor in the ten chapters was extracted and mapped to its trade, and there were three drifts on top of the gender flip, all three of them the same fault — a neighbouring character's age written onto a person who already has one — and all three are repaired.**

9. **`chapter-0207.md:45` — the workroom man is about twenty-four and he is about twenty-nine.** In a speech in which the man of about thirty-four who keeps a stall is *quoting* another man, he says *A man of about twenty-four from a workroom said on that same Saturday that a page with a price under every line and no figure under any price is a list of intentions*. **He is about twenty-nine, on the page in `chapter-0201.md:19` and `chapter-0205.md:21` in this batch and in sixteen chapters of Volume 04, and `bible/characters.md` has him at twenty-nine. The wrong age had also been copied into `state/continuity.md` and `state/character-state.md`, so the state layer and one chapter agreed with each other and both differed from the other sixteen — which is how a state file becomes a second source of a phantom.** Repaired on the page and in both state files.
10. **`chapter-0203.md:29`, `:53`, `:73` — the woman who keeps a public register is about thirty-nine and she is about twenty-nine.** **There is one woman who keeps a public register in this manuscript and she is about twenty-nine: eleven occurrences across Volume 03, Volume 04 and Volume 05, and `bible/characters.md`.** She is doing the same work in the same chapter that she does everywhere — a thing written on a slate and carried to the room over a market to be put on the table where about two hundred and forty people saw the last one. Three one-word repairs.
11. **`chapter-0210.md:55` — the water-counter is about thirty-four and she is about fifty.** The digger says *one of them is a woman of about thirty-four who counts water on the fingers of her left hand*. **She is a water-count of about fifty, on eleven pages of Volume 04, on `chapter-0201.md:33` of this batch and in `bible/characters.md`, and the wrong age collided with the four women of about thirty-four this batch is full of, which is exactly the merge the device produces.** One two-word repair.

**The descriptor map as the ten chapters now stand:** fifty the water-counter, fifty-two the digger, fifty-six the shopkeeper, fifty-nine the woman who keeps that house, forty-four the cost column, thirty-eight the keeper of the Redroot gate, thirty-nine the man on the Open Hand board, thirty-four the man who keeps a stall and three women who are not each other, twenty-nine the workroom man and the woman who keeps the register, twenty-four the recorder who keeps the record, and the man of forty-two at the back of his own yard. **No two of them are one person and no one of them is two.**

## The structural note, which is not a defect in this phase

`outline/volume-05.md` does not exist, nor does `outline/volume-03.md`, and Volume 05 now has ten chapters and an invented day map ahead of any outline. The batch was right to write days rather than invent a volume, and `workspace/volume-05/batch-0002/PROMPT.md` says three times that the subject of Volume 05 belongs to an outline phase. **It is flagged, not fixed, because it is not this phase's work to decide what Volume 05 is.**

`state/phase-ledger.json` still reads `phase-000-bootstrap / planned` while `state/current.md` reports this batch complete and repaired. **That file is controller-owned and was not touched.**
