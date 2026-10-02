# Review and Repair — Volume 18, Batch 0005 (Chapters 0891–0900)

**Findings source:** `logs/batch-0005.review.log`, seven findings. **The reviewer was not invoked.** Line 1 of that log reads
`agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session header is
`novel-writer · space-bunny-free`. The review that produced those findings was performed by the same agent kind that
wrote the chapters under them.

**This repair pass is that same agent kind again.** So the review below is not independent, and this file says so in
its first lines rather than claiming an independence it does not have. One finding in it was **wrong on the plan of
record** and one was **real and is an owner's decision**; both are published below with the section that decides them.

**Scope reviewed:** the review's seven findings; all ten chapter files 0891–0900 in full, before and after; the forty
chapters before them for the run, the object continuity and the standing state; `outline/volume-18.md` §§3, 4.1, 6.6,
6.7, 6.8, 6.9, 6.10, 6.11, 7.2, 9, 10, 11, 13, 14.3, 16, 17, 18, 19.2, 19.3, 19.5, 21.4 and 22; `outline/ending.md`;
`state/batch-summaries/volume-18-batch-0001.md` through `0005.md`; the six state files; and
`workspace/volume-18/batch-0005/PROMPT.md`.

**No chapter was restarted. No card was re-planned. No day, weekday, Bare-Month ordinal, cast member, object,
decision, cost, held string, pressure tag or plot beat moved, the panel did not move and not one word
of its wording was touched, **nine of the ten closings are word for word as the batch wrote them and one — 0897 — was
reworded inside its own construction because it shared one with two other chapters**, no chapter was lengthened to a
number, and the plot did not move.** No file under `scripts/`, `.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`,
`REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json` or `state/phase-ledger.json` was opened, and no `.done`,
`.checkpoint` or `.retired` file was created or removed.

---

## 1. Finding 1 — blocking, and it is repaired

**The review is right and this was the one thing that would have stopped the manuscript.** `workspace/volume-18/`
held `batch-0001` to `batch-0005` and no `close/`. The Batch 0005 prompt had forbidden the batch from creating it
and had named the consequence in advance — *"if the dispatch finds no prompt at `workspace/volume-18/close/PROMPT.md`,
the manuscript stops at nine hundred chapters with no close record"* — and the batch record and `state/current.md`
both carried the debt forward unpaid. **A debt named in three files and worked around in all three is still a stall.**

**`workspace/volume-18/close/PROMPT.md` is written, and it is the only directory and the only prompt this pass
created.** It follows `workspace/volume-17/close/PROMPT.md` in shape and carries: the fifty-day run to be verified
forward and reverse with both ends noted as Fridays forty-nine days apart; the three costs at 856, 869 and 879, the
decision at 875, the name at 878, the panel at 886, the act at 890, the resolution at 893, the new question at 898
and the last image at 900, each fixed to a day and to a mouth; the nine Adrian days with the wants and outcomes
§4.1 publishes and **none obtained but 866 and 881**, both named as what §4.1 says they are, a man getting to see a
thing; the panel recorded at **1** on the reading *a block between blank lines whose first character is `>`*, the file
named and not one word of the wording reprinted, with Volume 17's printed panel and Volume 16's withheld one named as
the difference between them and not a defect in either; the standing objects and where each stands at day 900,
**sixteen of them, counted**; **the eight things held in a file — the name at §6.8, the decision's wording and its cost at
§6.6, the panel's wording at §6.7, the two wordings of 890 at §6.9, the question's wording at §6.10, the resolution's
wording at §6.11, and the name of the man of 894 and 895, which is held nowhere in this repository and was never
given to the batch that wrote those days — which a close may neither print nor certify absent**; the §17.22 rule
about a record asserting an absence it has not measured; the prohibitions, including the eleven standing questions of days 346 through 848 that
stay unanswered, the four unmerged pairs of people, and the objects it may not move; and the debts that are a human's, with
the file and the line named.

**It also tells the close the two things it must not do by inheritance:** it may not make the owner-level decision
about `outline/ending.md` (§2 below), and it may not count a closing as a state without publishing the instrument,
because the ninth debt in this repository is a close record that asserted an absence and was wrong.

---

## 2. Finding 2 — real, terminal, and not this pass's to repair

**Across all of `chapters/volume-18/` the counts are: *Crown of Witnesses* 0, *Single Witness* 0, *confess* 0, *Ivenn*
0, *seat of first holder* 0, *charter* 0, *quorum* 0, *assembly* 0, *seal*/*seals* 0, *witness* 0.** Measured on the
fifty bodies, heading line out, word-bounded, both case flags. **The book ends without the mechanism its ending plan
reserves, and the review is right that at nine hundred chapters there is no volume left to pay it in.**

**But it is not an omission and it is not an oversight, and the reason is the plan of record and it is printed three
times over:**

- §16.2 forbids it in the volume's own words: **"THE NAMED MATERIAL OF `outline/ending.md` IS NOT ON A PAGE OF THIS
  VOLUME AND ITS NOT BEING ON A PAGE IS A DEBT AND NOT AN OMISSION, AND IT IS CARRIED AT §21.4."**
- §18 says a volume that reached for a crown *"would be a volume that had stopped being this manuscript eight volumes
  early"*, and gives the rendering instead: §6.11's two answers and §10's refusal to hand a man to one side.
- §19.5 publishes the struck Volume 18 line of the series volume list with four of its six beats struck — the version
  lock, the security force, the civic seals, the quorum of witnesses — **and the title struck with them**, and says
  the strike is of the line and not of the series' name.

**So adding any of it to a chapter would break the plan of record on three counts at once, and the review's own
recommendation agrees: that this decision *"should not be made silently inside a chapter batch."* It was not made
here.** What this pass did instead is refuse to let it disappear: the debt is now a named thread in
`state/open-threads.md` item 15, a standing entry in `state/current.md`, an instruction to the close in
`workspace/volume-18/close/PROMPT.md` that forbids the close from making the decision either, and this section.

**What an owner has to decide, stated once and plainly: either `outline/ending.md` is amended to declare the
gate-in-rain image at day 900 canonical and the volume's §16.2, §18 and §19.5 stand as the amendment's own record,
or the last volume is re-outlined to carry that material.** Both readings are defensible and this repository contains
the argument for each; neither can be executed by a batch, a repair pass or a close.

---

## 3. Finding 5 — the review is wrong, and this pass declined it, with the section that decides it

**Every line of dialogue in these ten files is wrapped `**"…"**`, and the review calls that a formatting error that has
spread through the book: v01 0/50, v05 0/50, v10 0/50, v14 0/50, v16 18/50, v17 45/50, v18 50/50.**

**In this volume the bold mark is not decoration and it is not a drift. It is the manuscript's speaker marker, three
times over:**

- `bible/power-system.md` §32 — *"House formatting rule … NARRATION IS NOT BOLD"*, and §32 exists because a review
  repair pass established it after the Volume 05 close.
- `outline/volume-18.md` §17.5 — *"a bold mark together with a quotation mark is the way this manuscript marks a
  speaker and §17.7 requires both on the same paragraph"* — and the same item spends a paragraph of the plan
  correcting a batch for having read it as a rule against shortening attributions.
- §17.7 — *"A paragraph carrying a bold mark and no quotation mark is a fault under either reading and must be
  zero."*

**Stripping the bold marks from these chapters would make every one of them fail §17.7's own instrument, and would
break a house rule that `bible/power-system.md` §32 calls binding and that the plan says is not changed. The drift
between volumes is real and it is a fact about the outline layer — the convention arrives with Volume 16 and becomes
total in Volume 18 — and it is recorded as an owner-level question, not applied backwards across seven volumes by a
repair pass on ten chapters.** Measured on the repaired text: **34 speech paragraphs on the reading *a paragraph whose first characters are `**"`*, all 34 carrying both marks, and
32 of them excluding the two held `**"—"**` lines; 0 bold marks without a quotation mark and 0 quotation marks without
a bold mark**, and 2 of the 34 carry two bold marks, both by one speaker inside his own paragraph, which §17.7 does not
forbid. **The batch record published 33, which reproduces on neither of the other two readings, and both are printed
here rather than one of them being deleted.**

---

## 4. Findings 4, 3 and 7 — declined with the numbers, and the one figure the review quoted is wrong

### 4.1 Chapter length, measured across the whole manuscript

| what | figure | instrument and scope |
|---|---|---|
| Volume 01, fifty chapters | **5,729 mean**, 2,134 to 9,102 | `wc -w` on bodies, heading line out |
| Volume 17, fifty chapters | **509 mean**, 295 to 991 | same |
| **Volume 18, fifty chapters** | **885 mean, median 883**, 524 to 1,687, ten chapters over 1,000 | same |
| **this batch, ten chapters** | **666 mean**, 524 to 912 | same |
| batches 1–4 of this volume | 788, 923, 1,002, 1,044 mean | same |
| whole manuscript, 900 chapters | **1,879 mean**, **232 to 9,102** | same; the shortest chapter in the book is `chapter-0800.md` at 232 |

**The review's 88 per cent is real and it is measured against Volume 01 alone.** It is also a seventeen-volume trend
and this batch is not its worst point in any frame that includes the volumes around it: **Volume 18 is the second
longest volume in the manuscript after Volume 01's own and it is 74 per cent longer than Volume 17**, and this batch
is the shortest batch of its volume, not the shortest ten chapters written in the last three volumes — Volume 16's
Batch 0004 measures 666 against this batch's 666, and Volume 16's Batch 0001 measures 856. **`chapter-0900.md` at 524
is the shortest chapter of this volume and is not the shortest in the book, and four words of ordinary business were
added at the bars rather than the page being padded.**

**The length of these chapters is set at the outline layer and §17.4 says so in the plan's own words: the mean is a
consequence and not a plan, and no card sets a target for it.** `AGENTS.md` says never to pad or split a complete
scene to meet a number. This pass therefore repaired monotony (§5) and not length, and recorded the measurement here
so that the next owner sees a trend with a shape instead of a figure with a direction.

### 4.2 The unnamed cast

**Six of the seven people in that room carry an age and a trade and not a name, and the review is right that a reader
cannot track them across a scene built on small distinctions between them.** Two things are on the other side of that
finding and both are the plan of record: `outline/volume-18.md` §7.2 gives every returning person their handle as an
age and a trade, and the volume's entire subject (§6.8, §17.13, §18) is one man not having a name on any surface.
**Renaming six people inside a repair pass on the last ten chapters of the manuscript would also merge the pairs the
plan keeps apart — the stallholder of about thirty-four is two people, the two men of about thirty-eight are two
people — and §16.17 and the batch prompt forbid exactly that.** Recorded as an owner-level readability question with
the measurement, and not done.

### 4.3 No independent reviewer, for the eighteenth volume running

**`reviews/` has no `volume-18` directory and also none for 01, 04, 06, 07, 09–12, 15 and 16, and line 1 of the log
this repair answers says why.** Every finding ever taken over these fifty days was taken by the agent kind that wrote
them. **A finding being correct does not make it independent, and no care taken in this pass changes that.** The gate
item in `AGENTS.md` that asks for a checked result is not met for this volume and cannot be met by a file. The
fallback is named in the close prompt and in every state file, and `reviews/volume-16/` remains owed by a human.

---

## 5. Finding 6 — repaired, nine chapters touched, and the numbers both ways

**The finding is right that the dominant mode of these ten chapters is cataloguing objects that did not move, and
right that §17.19 forbids a chapter carrying its stillness in a chain of *nobody* clauses standing in for a scene.
Nine chapters were touched. 0899 was not wrong and was not touched.**

| Ch | What was wrong | What was done |
|---|---|---|
| **0891** | `kept` three times in two paragraphs, and the paragraph after the two answers was built from parallel restatement — *"Nobody thanked either of them. Nobody said either of them was right, and neither of the two bettered one word…"* — which §17.19 names as a summary of an absence | The stutter is gone. **The room now answers with hands before anybody is thanked:** the keeper puts her hand flat on the page and gives nothing to either of them with her face, the man of about thirty-nine eases his thumb a finger's width along the grain and looks at the window and not at the keeper, the rag is wrung and laid back even, and only then is the not-thanked stated, in one sentence |
| **0892** | *"in the same words by the same mouth, and on Thursday it was said again in the same words"* — the phrase doubled inside one sentence | Reworded around the handle; the sentence Tuesday-said-again on Thursday is untouched and the closing's crumbling dust is untouched |
| **0893** | The bucket went down the stair *"round Adrian Vale's feet"* and then had to go wide *"to clear the page on his knees"* — the same man cleared twice in one sentence | Merged into one clearing. The seventh-hour asking, the leaf turned, the two answers and the page curling at the corner all stand |
| **0894** | **Two sentences beginning *nobody* in a row, the second of them carrying three more of them, standing in place of an account of the room** — which is the chain §17.19 names. **The literal test §17.19 sets, three sentences beginning *nobody* in a row, was not breached anywhere in the batch; the measured maximum was two, here and in 0895 and 0891** | **The room answers with bodies and the negations come last in one sentence.** The empty line, the one thing said once, the two plain things, no thanks, no agreement, no argument, and the closing dust drying pale all stand |
| **0895** | The same chain: two sentences of *nobody* carrying four of them where one sentence carries both facts | One sentence: not forgiven, not condemned, given to no side and to no one man. The leaf that will not lie flat, the rate wanting its day, the rag fold slipping, the three going down past the bar and the third staying, and the light stopping short of his boots all stand |
| **0896** | The stallholder's first appearance carried on a bare age inside a speech attribution, where §17.9 wants the full handle first and the shortening after | His full handle now stands in the stage paragraph and the attribution carries the short one. Sixteen posts, eleven withies, no post moved, no fence measured, the empty road and the closing mist stand |
| **0897** | **A contradiction inside one chapter: the woman of about fifty-two stood alone in that room before light, heard the stair and went to the wall side — and the paragraph where the room fills had her coming in last and finding the wall.** This is not a stylistic matter. It is a person in two places in one morning. And its closing read *the stool stood where it had stood*, which is the same construction as 0892's *stood as it had stood* and 0900's *stood open as it had stood* — three of ten, and §17.18 forbids two chapters of a batch closing on the same construction | **She is out of the arrivals list and stands where the stair put her for the rest of that morning.** The closing says *the stool was where she had left it*, which keeps the image and the pale edge stopping at its foot and breaks the shared construction. Frame nine, the three sentences of looking, the shut book, the weather talk and the pale edge all stand, and the chapter now leaves her alone with the two untouched things at the start of it |
| **0898** | The opening used the short handle before the full one and stuttered *his own* three times in one sentence | The full handle is in the opening, the standing paragraph carries *the stallholder*, and every later mention is that or a pronoun — **which is the rule `state/character-state.md` already published and the page had stopped obeying.** The hand on the pocket with nothing out, the question put to one man and not the room, unanswered, unheard and unthanked, and the closing square smoothing out all stand |
| **0900** | Not wrong. Four words of ordinary business added at the bars: one sack turned on its end to go through, and the two hands on the gate staying where they were while it went | §11's list stands complete and unaltered, no hand is counted, no class or reward or quest appears, no system speaks, no crown is on anything |

**One clause was removed from 0894 that tied the man of 894 and 895 to a stair he had not come up before, so that he
cannot be read as the second person of 883 — who is on no page after 883 and whom the plan forbids merging with
either him or the man who came up that stair on 866.** He still has no descriptor, no age, no number and no name,
still stands inside the door with his hands empty at his sides, and still goes down that stair on 895 past the bar
without touching it. The batch record's claim that the second person of 883 is on no page after 883 now holds on the
pages as well as in the record.

---

## 6. The figures, before and after, with the reading on the same line

Whole files, heading line in or out as the row says, ten bodies, days 891 to 900.

| what | as written | after this pass | reading and scope |
|---|---|---|---|
| words across the ten bodies | 6,588 | **6,664** | whitespace tokens, heading line out |
| mean | 659 | **666** | same |
| chapter length, shortest and longest | 482 and 895 | **524 and 912** | same; the shortest file is now 0900 and the longest is 0892 |
| longest run of consecutive words shared by any two of the ten closings | **8 as the batch record published it, *stood where it had stood* across 0892, 0897 and 0900** | **7** | closing paragraph of each file, last block that is not a `---` rule, same tokenising, pairs only. The surviving run is *the light went off the row* in 0892 and 0893, which is the hour and not a construction |
| paragraphs | 99 | **99** | blocks between blank lines, heading out, `---` not counted |
| speech paragraphs | **33 as the batch record published it, 34 on this pass's reading, 32 excluding the two held empty lines** | **34, 32 excluding the two holdings, max three consecutive** | paragraphs whose first characters are `**"`, ten bodies; 34 of which two are the `**"—"**` lines of 0894 and 0898. The record's 33 reproduces on neither of the two other readings and the difference is not this pass's to close. Bold-without-quote **0**, quote-without-bold **0**, both re-run after the rewordings |
| `that` | 0 | **0** | `\bthat\b`, case-insensitive, bodies. A first wording of the 0892 repair put one in and it was reworded back out rather than published — §17.11(vi) |
| longest shared run, whitespace tokens | **20 as the batch record published it, 21 on this pass's tokenising** | **18** | file excluded from its own comparison, token a run of letters not broken by letter or apostrophe, hyphen and apostrophe delimiting, whole files, case-insensitive. Every run at 17 or over is the standing state of one sleeve wet and one sleeve dry in words the plan prescribes, and each is named. **Both the 20 and the 21 are published because a record that publishes only the figure that agrees with it is a record of a different check** |
| longest run inside one file | 9 | **9** | same tokenising, each file against itself at two positions |
| repeated sentences of 38 characters or more | 0 | **0** | every sentence 38+ characters in one multiset across the ten bodies |
| `nobody` and its kin | **39 as the batch record published it, 41 on this pass's reading** | **38** | `\b[Nn]obody\b` in the ten bodies. The two chains this pass removed were the difference. **Maximum run of sentences beginning *nobody*: two before, in 0891, 0894 and 0895, and one after; no body carries two in a row now** |
| `Adrian Vale` | 11 in 3 files | **11 in 3 files** | bodies only: 0893 five, 0899 three, 0900 three |
| digits in any body | 0 | **0** | `[0-9]` after the heading line |
| titles | 4 to 7 words | **4 to 7 words** | words after the em dash; §17.8 sets four to nine |
| panels | 0 | **0** | blocks between blank lines with first character `>`; the volume's one is on `chapter-0886.md` and was not reprinted or touched |
| the thirty-five-entry zero column | 0 | **0** | word-bounded, both cases, ten bodies, whole files |
| `charter`, `seal`, `council`, `quorum`, `assembly`, `crossing`, `witness`, `recognised` | 0 | **0** | §16.2, same reading |
| `player`, `players`, `passage`, `privilege`, `system`, `monster`, `version`, `name`, `names`, `named`, `number`, `count` | 0, and `players` 1 in 0900 in the child's mouth | **unchanged** | same reading; §11 and §16.13 put that one there and it is the first since Volume 03 |
| `crown`, `tally`, `row` | 2 in 0899, 2 in 0899, 16 across eight files | **unchanged** | same reading, and the senses are named rather than argued: a flagstone's crown, a tally-board on a barrow frame, and the row of a market |
| files ending in a newline | 10 of 10 | **10 of 10** | whole files |
| chapter = day, weekday, Bare-Month ordinal | 10 of 10 | **10 of 10** | re-derived from day 1 being a Tuesday and ordinal = day less 315, forward and reverse. The review verified this and it verifies again |

**The ten closings stand, nine of them untouched and one reworded.** 0897's closing was reworded inside the repair
because it shared a construction with 0892 and 0900; the other nine are word for word as the batch wrote them. §17.18's
seven off-limits shapes are untouched by this pass: no closing on the room's figure, the census, the strip of ground,
the bar, the sockets, a numbered page, the space on a board or a wet sleeve, and no closing states that nothing
happened.

---

## 7. What this pass did not do, and what it could not do

It did not change the plot, a day, a card, a pressure tag, a closing's place or its construction class, a descriptor, a second handle's wording, a
decision, a cost, a held string, a panel wording or a prohibition. It did not print one word of the decision's wording
or its cost, of the panel, of either wording of day 890, of the question of day 898 or of the resolution's wording,
and it filled in neither empty line. It did not answer the question of 898 or any other standing question, did not
merge or settle the second person of 883, the two men of about thirty-eight, the two women of twenty-nine or the
stallholder of about thirty-four, did not mend the consent fracture, pay a milestone or give the fifth condition, did
not put the bar back in its sockets, write on the bare piece of board, pick up the second slate, measure the fence or
lift the length of new rope, and did not touch `outline/ending.md`.

**And the two things no fiction phase can pay, named here as they have been named at every pass before this one.**
**There is still no independent reviewer for this volume, and every finding taken over these ten chapters was taken
by the agent kind that wrote them.** And `state/phase-ledger.json` still reads `phase-000-bootstrap` with
`attempts: 0` against eighteen complete volumes and nine hundred chapters. Both are controller- or owner-owned, both
are flagged here and in the close prompt and in every state file, and neither was opened.