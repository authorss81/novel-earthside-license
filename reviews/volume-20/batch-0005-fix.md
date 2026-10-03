# Reviews — Volume 20, Batch 0005 — Review-Fix

**A repair pass over the ten finished days of `chapters/volume-20/chapter-0991.md` to `chapter-1000.md`. The file of
record for the batch is `reviews/volume-20/batch-0005.md` and it is not superseded by this one; §9 of that record asked for
these findings to land here and not in it. Twenty-two findings were returned by an independent reader and **eighteen are
applied**, of which nine are prose and nine are figures. Four are looked at and left standing and they are named at §4 so
a later reader does not take them for oversights. Every figure below was re-measured with the instrument published beside
it, in the same run as the prose change, and the reading and the scope are on the same line as the number.**

**NO CHAPTER OF THIS BATCH IS REWRITTEN. NO DAY IS MOVED, NO WEEKDAY, NO BARE-MONTH ORDINAL, NO PRESSURE TAG, NO FRAME AND
NO OBJECT STATE WAS CHANGED TO SATISFY A FINDING.** Nine sentences and four clauses were changed across eight of the ten
files. **The three held wordings of day 994 were not touched, and they were re-measured after the edits that were made in
the same file they live in.** The four held strings that belong to other days were not touched and were re-measured across
the same scope.

---

## 0. THE CALENDAR, RE-DERIVED, AND THE INSTRUMENT

Two figures and two figures only, from `outline/volume-20.md` §14.1: **day one is a Tuesday, and the Bare-Month ordinal is
the day less three hundred and fifteen.**

```
cd /home/runner/work/novel-earthside-license/novel-earthside-license
python3 - <<'EOF'
WD=['Monday','Tuesday','Wednesday','Thursday','Friday','Saturday','Sunday']
IDX={w:i for i,w in enumerate(WD)}
def weekday(d): return WD[(d-1+IDX['Tuesday']) % 7]
def bm(d): return d-315
for d in range(991,1001):
    print(d, weekday(d), 'BM', bm(d))
EOF
```

| Ch | Day | Weekday | BM | Ordinal as printed in the body | Parses back to day−315 |
|---|---|---|---|---|---|
| 0991 | 991 | Friday | 676 | six hundred and seventy-sixth | 676 ✓ |
| 0992 | 992 | Saturday | 677 | six hundred and seventy-seventh | 677 ✓ |
| 0993 | 993 | Sunday | 678 | six hundred and seventy-eighth | 678 ✓ |
| 0994 | 994 | Monday | 679 | six hundred and seventy-ninth | 679 ✓ |
| 0995 | 995 | Tuesday | 680 | six hundred and eightieth | 680 ✓ |
| 0996 | 996 | Wednesday | 681 | six hundred and eighty-first | 681 ✓ |
| 0997 | 997 | Thursday | 682 | six hundred and eighty-second | 682 ✓ |
| 0998 | 998 | Friday | 683 | six hundred and eighty-third | 683 ✓ |
| 0999 | 999 | Saturday | 684 | six hundred and eighty-fourth | 684 ✓ |
| 1000 | 1000 | Sunday | 685 | six hundred and eighty-fifth | 685 ✓ |

**Ten of ten agree with the instrument, and ten of ten parse back out of the printed words of their own bodies to the day
less three hundred and fifteen**, the parser mapping the irregular English ordinals (`eighth`, `ninth`, `twelfth`,
`twentieth`) onto their cardinals explicitly. **Neither end of the volume's range was used to derive any middle day.**

---

## 1. THE NINE PROSE FINDINGS, ALL APPLIED

### 1.1 A THUMB ON THE WRONG MAN, `chapter-0994.md`, and it is on the volume's climax day

**This is the drift the batch's own prompt named in advance and warned about: that row has nine people in it and a sentence
of staging goes wrong. The reader found it and it is the single worst thing in this pass.**

> The man of about thirty-nine who trades on a board was about nine feet off from him at the near end of that bench with
> **his own thumb going along the foot of his own board. He went on along the foot of that board from the top of the
> middle of it to the foot of it**, and he did not look up and did not answer it.

**The thumb is not his and has never been his.** Instrument for the ownership claim, which is a reading of fifty files and
not a count: every chapter of `chapters/volume-20/` in which a hand goes along the foot of a board with a thumb is that of
**the man of about thirty-four who keeps a stall two stalls along**, and no other — `0953, 0955, 0959, 0962, 0963, 0966,
0968, 0972, 0973, 0975, 0976, 0978`, in all twelve. **The tradesman's own instrument is the cloth on the face of his own
board** — `0968, 0972, 0973, 0976, 0978` — and *the top of the middle of it to the foot of it* is the stallholder's ritual
in its fixed phrasing, at `0972` and `0975`.

**`chapter-0994.md` contradicted itself about it, twice, on the same page.** Line 9 stages the tradesman *with his own board
lying face out on the wood with the cloth over his own shoulder*, and the woman of about fifty-two describes him at line 35
as *a man at the near end of that bench with the cloth over his own shoulder*. He was given a stranger's habit in the two
sentences that follow the one thing he says into the middle of that room and gets no answer to.

**Applied.** The tradesman now works his own board with his own cloth, the stallholder keeps the thumb in his own hand at
the middle of that bench, and the paragraph is re-led so the room is doing something in each of its sentences:

> The man of about thirty-nine who trades on a board was about nine feet off from him at the near end of that bench with
> his own board lying face out on the wood in front of him and the cloth off his own shoulder. He came down the face of
> that board with the cloth from the top of the top column, and the cloth stopped at the foot of the middle column where
> it stops every morning, and he did not look up and did not answer it. Nobody in that room answered it. The stallholder in
> the middle of that bench went along the foot of his own board with his own thumb twice and did not turn about at it.

### 1.2 THREE RUNS OF THREE SENTENCES OPENING *NOBODY*, IN 0991, 0994 AND 0997 — §16 item 2

**`outline/volume-20.md` §16 item 2 is explicit: three sentences beginning *nobody* in a row is a summary of an absence and
not a room, and §17.18 carries the same rule whole.** Instrument: sentences of the body with `---` read as whitespace and
bold markers stripped, split on a full stop or a question mark followed by a capital, and a sentence counted as opening in
*nobody* when its first token is one. **Measured before the repair: three chapters of ten carried a run of three, and they
are the memory day, the climax and the resolution.**

| Ch | The three sentences, as they stood |
|---|---|
| 0991 | *Nobody in that room said a word back to either of them.* / *Nobody in that room told either of them that what he had said was right or that it was wrong.* / *Nobody asked the man of about thirty-nine…* |
| 0994 | *Nobody in that room answered it.* / *Nobody in that room turned about at it.* / *Nobody in that room said a word about what Adrian Vale had said…* |
| 0997 | *Nobody in that room asked him to make it so that way.* / *Nobody in that room thanked him for answering her.* / *Nobody in that room told him that what he had said was right…* |

**Each run has been broken with the work the room is doing, and each break is a person doing their own established act.**
On 991 the tradesman takes the cloth off his own shoulder and goes down his own board and says nothing at all. On 994 the
stallholder goes along the foot of his own board with his own thumb and the keeper puts her own hand flat on the page in
front of her. On 997 the keeper squares the sheet on the wood with the heel of her own hand. **No required descriptor
handle and no piece of standing geometry was cut to do it and no held string was traded against it.**

**After: 0 chapters of 10 carry a run of three or more.** The strictest per-sentence reading — clauses opening *nobody*, *no
one* or *not one* inside one sentence, counting `^`, a comma and *and* as openers — returns **a worst case of 3, against
the ceiling of 3 §16 item 2 sets**, and that worst case is one sentence in 0994 and two in 0997.

### 1.3 A PRONOUN THAT LANDS ON THE WRONG WOMAN, `chapter-0997.md`, IN THE RESOLUTION

> She went down that column of figures and back up it. […] The second book lay open **beside her register** […]

**The last person named in the paragraph above is the woman of about sixty-nine with her tin.** She keeps no register, she
is not the one with the six strokes against her, and every other chapter of this batch names the keeper for exactly this
act — `0991:51` *The keeper went down that column of figures and came back up it*, `0994:73` *The keeper went down that
column and came back up it*, `0995:13` *She went down the column that holds figures*, correctly following *The keeper*.
The sentence as printed handed the keeper's register to a woman carrying a tin, and the paragraph then said *her register*
about it. **Applied: `The keeper went down that column of figures and back up it.`**

### 1.4 THE WOMAN OF ABOUT FIFTY-TWO PUT BACK AGAINST HER OWN FAR WALL, `chapter-0993.md`

> The woman of about fifty-two set that stool down against the wall along the far side of that room **and stood looking at
> it**, and then she put her own hands back at the sides of her dress and left it standing there.

**She is at the far end of that bench and not against her own far wall, and `state/continuity.md` carries that as standing
geometry for any writer after this batch.** She is at the far end of that bench in `0991`, `0994`, `0995`, `0997` and
`0999`, and in 0995 and 0999 the chapter does both — stool to the wall, then the bench. 0993 did the stool and stopped.
**Applied:** she sets the stool down, goes the length of that room to the far end of that bench, and stands with her own
back to the wood behind the far end of it. The stool is still where she put it, which is the chapter's business and is
unchanged.

### 1.5 THE BLOCK OF WRITING DATED TO A WEEKDAY IT WAS NOT PUT UP ON, `chapter-0997.md`

> The block of writing was on that wall where it has stood **since the Wednesday morning** […]

**It went up on day 983 and day 983 is a Thursday** — `chapter-0983.md:5` opens *It was Thursday, the six hundred and
sixty-eighth day of the Bare Month* — and the instrument at §0 returns 989 Wednesday, 996 Wednesday, 997 Thursday. **On
either reading the block has stood there fourteen days and not since a Wednesday.** This is the one object in the volume
that §6.7 fixes a day for, and the sentence was the chapter's own statement of how long it had been there. **Applied:
*where it has stood for the fourteen days since it went on*.**

### 1.6 A COUNT OF THE LINES IN THE GRIT THAT THE VOLUME HAD ALREADY CONTRADICTED, `chapter-1000.md`

> There are two lines in the grit at the store's end of that row **and four going up from them at four joints** toward the
> far end of that market.

**`chapter-0952.md` is titled *Six Joints Going Up The Row* and its body has her making *a line at every joint*; `0978:13`
has *a stroke in the grit of that row about the length of a hand at every joint along it* and *she stopped at a dozen
places*; `0992:37` has her stop at *a dozen joints*; and `1000:17`, seventeen lines below the sentence being repaired, has
her *stopped at every joint along it*.** The figure of four joints is the plan's own count of day 920 and the chapter
stated it as an enumeration of the whole row. **The plan's §2 itself says the day-920 page records that one of them *is not
the first of them and will not be the last, so there are more than five*** — so the enumeration contradicted the plan as
well as the manuscript. **Applied:** the count of two at the store's end of that row stands, because it is true and it is
what the last image needs, and the rest of the row is no longer enumerated:

> There are two lines in the grit at the store's end of that row and lines going up from that end of it joint after joint
> toward the far end of that market, and there are more of them than anybody has ever counted.

**The sixth line of the plan's card survives intact** — it is the newest one, made before the light, a foot to one side of
the older line at that end of the row, and nobody stops. **Nobody has asked her what any of them are for and no chapter of
this volume may ask her.**

### 1.7 TWO CLOSINGS ON ONE CONSTRUCTION, `chapter-0994.md` and `chapter-0999.md` — §17.17

**§17.17: no two chapters of a batch may close on the same construction.** These two closed on the same sequence — the dust
that came up that stair, a hand put flat on a bare surface, the dust taking the shape of that hand, the shape still there
when the light goes off that bench — and they share the verbatim span *the dust that had come up that stair* and an
identical terminal formula. **0994's closing is recast onto the shade of his own shoulder**, which is that chapter's own
consequence and is the one real thing that happens to him in the volume:

> The shade of his own shoulder lay on that wood from the seventh hour to the going of the light without once lifting off
> it, and her hand's print was standing in that shade when the light went.

### 1.8 THE SAME FOUR PASSERS-BY IN THE SAME ORDER WITH THE SAME PROPS, `chapter-1000.md` against `chapter-0992.md`

Eight days apart, the same four figures in the same order — a woman with a basket on her own arm up the near walking
space, a man with a coil over his own shoulder up the far side, a boy down the middle of the flags with his own hands in
his pockets, and a woman going the other way who stopped. **Only the middle verbs differed. The census is required on both
days by §14.5, so the repair is in the figures and not in the census. Applied:** four people this volume has not put on that
row — an old man with a stick, a woman with a hoop over her shoulder, two boys after one another, and a man going down —
two of whom get something off the surface and two of whom do not.

### 1.9 THE REST, ALL SMALL AND ALL APPLIED

| Where | What was wrong | What it is now |
|---|---|---|
| `0998:45` | The closing sat on two wheel lines cut in the crust at the store's end of that row — the one place in the volume where the barred lines are — and its last beat was a statement that nothing had changed, which §16 item 16 bars | A heap of shavings at the foot of that walking space with the grain of them lying one way, and about an inch gone off the near side of that trestle foot, and that heap the only thing on that walking space that had not been there at the light |
| `0999:29`, `1000:17` | *about as long as it takes to look at a row of trestles from end to end and be doing nothing else while you do it* — **26 identical tokens, three files, `0987`, `0999` and `1000`**, and the batch's shared-run table has a 35-token floor and so could not return it | 1000 measures the shade of the awning coming a hand's width off the stones. **The clause now stands in `0987` and `0999` and not in `1000`.** |
| `0994:59`, `0994:67` | *Nobody in that room asked him one word about any part of it* — the same fifty-character sentence twice in one file. **The record's repeated-sentence instrument was scoped to strings occurring in more than one file and so could not return it** | The second is now *And nobody in that room was told that anybody else's account of that morning was the right one, or that there was a right one* |
| `0998:7`, `1000:9` against `0998:17`, `1000:39` | The rag is one movable rag and stands folded on the stone lip of that step, and it was also folded over the rim of a bucket standing at that same step in two chapters | The rag is off the bucket in both. **There is one rag and it is on the lip, as `0956:5` says when it matters** |
| `0994:35` | *running a thread you could follow with your eye from the lip of that step **all the way across the flags**, and the thread stopped in the joint of the flags **a foot short of the walking space*** — a thread cannot cross the flags and stop short of them | *from the lip of that step to the near joint of them* |
| `0994:35` | *this bench*, in a speech on the volume's climax day, where the demonstrative is *that bench* in all nine other chapters | *that bench* |
| `0998:7` | *and it is out of the weather **where** it has lain every morning of that flood* — two contradictory places in one clause | *and it has lain out of the weather on that step every morning of that flood* |
| `0991:33` | A sixty-two-word chain of four negatives doing §16 item 2's work in a sentence | Split at the join, into three sentences |
| `0995`, `0997` | *as long as it takes to read a thing twice* stood twice in 0995 and twice in 0997 including in a closing | Both instances in 0997 and one in 0995 re-measured |
| `0993`, `0995`, `0999` | *at any hour of that day*, which §19.3 names as the negation formula a Volume 20 batch reaches for first | Three different shapes: *before the light went or after it*, *at any point of that morning*, *while the light was on that wall* |
| `0995:closing` | Three of ten closings opened on *The light* | 0995's closing now opens on the dust in the sill. **Two of ten** |

---

## 2. THE FIGURES AFTER THE REPAIR, RE-MEASURED

| Ch | Words | Paragraphs | Speech paragraphs | Panel lines | Digits | Title words |
|---|---|---|---|---|---|---|
| 0991 | 1937 | 30 | 2 | 0 | 0 | 8 |
| 0992 | 1406 | 22 | 2 | 0 | 0 | 7 |
| 0993 | 1404 | 22 | 1 | 0 | 0 | 8 |
| 0994 | 2162 | 40 | 7 | 0 | 0 | 8 |
| 0995 | 1651 | 28 | 0 | 0 | 0 | 8 |
| 0996 | 1295 | 25 | 0 | 0 | 0 | 9 |
| 0997 | 1684 | 28 | 0 | 0 | 0 | 7 |
| 0998 | 1414 | 22 | 0 | 0 | 0 | 9 |
| 0999 | 1464 | 24 | 1 | 0 | 0 | 7 |
| 1000 | 1312 | 22 | 0 | 0 | 0 | 7 |

**Total 15,729, mean 1,572.9, shortest 1,295, longest 2,162, spread 867.** Paragraphs 263, of which 46 are scene rules and
13 are speech paragraphs. **Panel lines 0 across all ten** and the only panel in this volume is on 0983 and is on disk.
**Digits in bodies 0 across all ten.** Titles seven, eight or nine words of title text, and **0 of them contain *question*
in any form**, and none names the panel's rule, the decision, the refusal of 965 or the word of 985.

**THE LENGTH THREAD, and this pass did not move it deliberately.** `PHASE_SYSTEM.md` asks for about 2,200 to 3,200 words an
ordinary chapter and this batch measures **1,572.9**, which is 627.1 a chapter under the floor, and 183.4 a chapter above
the batch behind it at 1,389.6. Batch 0001 measured 1,305.9, 0002 1,217.3, 0003 1,339.0, 0004 1,389.6, 0005 1,572.9. **The
165 words this pass added went on opening out scenes that already had room, and no paragraph was added that was not carrying
something and no finished scene was split to reach a number.**

**SENTENCES.** Counted on the whole batch with `---` read as whitespace and bold markers stripped: **475 sentences at a
mean of 33.0 words, a median of 32 and a longest of 87, with 106 at forty-five words or over, which is 22.3 per cent, and 4
at eighty words or over.** Those four are speeches and one of them is the held cost of 994. **No sentence of eighty words or
over is narration and no held wording was cut.**

**REPEATED SENTENCES.** Instrument: the sentence strings of a body whitespace-normalised, the speaker marker stripped, and
any string of thirty characters or more occurring in more than one file, over all fifty files of days 951 to 1000. **0 at
thirty characters and 0 at thirty-eight.** Run in the same run as every other figure here, after every prose change.
**The same instrument scoped to strings occurring twice inside ONE file returns 0 at thirty characters across these ten,
and it returned one — the doubled sentence at `0994:59` and `0994:67` — before §1.9.**

**SHARED RUNS, ON THE TOKEN THE RECORD PUBLISHES** — a run of letters with any apostrophe kept inside it, lowercased, and
a hyphen splitting a token into two. Measured over all fifty files of days 951 to 1000, every pair:

| Run | Pair | What it is |
|---|---|---|
| **37** | 0991 with 0997 | the tin under her right arm and the stick in her pocket and two feet short of the near end of that bench |
| 37 | 978 with 991 | the light thinning along the ground and four hundred yards of flags |
| 37 | 992 with 999 | the middle column standing a thumb deeper than the two ends and the cloth stopping at the foot of it |
| 36 | 992 with 995 | the thread of water out of the crack and the joint of the flags a foot short of the walking space |
| 36 | 994 with 995 | the night's hard clear run and the sun over the roof line at the far end of that market |
| 36 | 995 with 999 | the woman of about fifty-two at the far end of that bench with her own shoulder to the wood behind it |
| 35 | 968 with 971 | the keeper at the far end of that bench with her own hand flat on the page |
| 35 | 973 with 990 | the bare board under the date standing clear of the near plank |
| 35 | 986 with 996 | the trough's ice and the stallholder's own board face in |
| 35 | 994 with 1000 | the same weather clause |
| 35 | 995 with 1000 | the same weather clause |

**Volume maximum 37, batch maximum 37, and eleven pairs at thirty-five or over** — the same eleven, the same lengths, and
all eleven are standing geometry: a position clause about a board, a door, a window, a trough, a woman at a bench, or a
morning's weather. **This pass verified every row of that table against the instrument and did not change it.** One thing
the table could not see, and §1.9 fixed, is the twenty-six-token trestles clause, which is below the table's floor.

**THE TWO HOUSE FIGURES A REVIEWER HAS RAISED TWICE, MEASURED AGAINST ALL FOUR COMPARATORS.** True contractions, a run of
letters, an apostrophe and one of *t re ll ve d m*, both case flags, bodies, heading line out: **0 in 15,729 words**, and
the same reading returns **0, 0, 0 and 0** on days 951 to 960, 961 to 970, 971 to 980 and 981 to 990, all five measured in
this run. **Zero true contractions is the register of this manuscript and nothing was changed to reach it.**

*his own*, whole words, same reading and scope: **172 in 15,729 words, one in every 91.4**, against **146.7**, **141.5**,
**100.7** and **102.9** on the four sets behind it, all five measured in this run. **THE FIGURE THE RECORD PUBLISHED FOR
THE FOUR SETS BEHIND WAS 146.7, 139.9, 97.7 and 99.3, and this run's instrument returns 146.7, 141.5, 100.7 and 102.9.**
The first reproduces exactly and the other three come back between 1.4 and 3.2 words further apart than published. **The
difference is the instrument and not the prose, and the interpretive claim that the phrase has been thickening was
withdrawn by the batch behind this one and is not reopened on a fifth point.**

**THE TWO FIGURES THAT TURN ON THE RECORD, MEASURED AGAINST ALL FOUR COMPARATORS.** Negation tokens being *nothing, nobody,
no, not, never, cannot, neither*, whole words, both case flags, non-letter on each side, bodies with the heading line out:
**287 in 13,059 words, 295 in 12,173, 214 in 13,390, 240 in 13,896 and 248 in 15,729** — one in **45.5, 41.3, 62.6, 57.9,
63.4**. Bare *that*, same reading and scope after `---` scene rules are dropped, bold markers stripped, either case:
**3.32, 3.95, 3.15, 4.01 and 4.37 per cent**. **A negation token every 63.4 words is 5.5 words further apart than the 57.9
behind it, so this batch is the least dense of the five on negation, and bare *that* is 0.36 points heavier than the batch
behind it.** Read as negations per thousand words the five points are 21.98, 24.23, 15.98, 17.27 and **15.77**. **THE CASES
AN OUTSIDE READER COULD ARGUE THE OTHER WAY ARE PUBLISHED RATHER THAN ARGUED: this run's instruments return 3.32, 3.95,
3.15 and 4.01 on the four sets behind it where the chain in the live state layer publishes 3.30, 3.93, 3.14 and 4.00, so
the first two come back between 0.02 and 0.07 points above the figures published for them and the third and fourth
reproduce to within a hundredth of a point.** **Neither figure was moved by cutting a required descriptor handle or a piece
of standing geometry, and no held string was traded against either one.**

**CLOSINGS.** Ten closings on ten different subjects. **The similarity ratio between any two is at most 0.173, between 0997
and 1000.** Checked against §17.17's ten off-limits shapes and none of them is on one: no closing is the room's figure, no
closing is *about four people a day*, no closing is the strip of ground, the bar or the sockets, no closing is a page that
says a number, no closing is a name in a column or the space on that board or a wet sleeve, **no closing is a question or
the answer to one — and that includes 994, which does not close on the act or the name, 997, which does not close on what he
answered, and 1000, which does not close on the sixth line** — and **no closing is the grit or a line in it, which is now
true of 0998 as well as of 1000**, and no closing is the tin.

**THE CENSUS.** *about four* is printed **7 times across 6 days** of these ten — 991, 992, 994 twice, 998, 999 and 1000 —
and **7 of the 7 carry the word *people* inside the phrase**, which is what §14.5 requires. **Measured as `about four`
followed within thirty characters by `people`: 7 of 7, and 0 breaches.** It was never reduced, never given to anybody and
never used as a count of anybody, and **the headcount of that room is in no mouth and in no narration on any of the ten
(`about nine people` at 0) and no mouth reaches any figure by asking anybody anything.**

---

## 3. THE HELD STRINGS, RE-MEASURED AFTER THE EDITS

**The instrument is the one `reviews/volume-20/batch-0005.md` §3.1 publishes**: a script reads `outline/volume-20.md`, takes
the blockquote out of the subsection that owns each held string, joins a multi-line blockquote with a single space,
normalises internal whitespace, **strips the full stop from the end of the key**, and counts literal occurrences across a
named scope. **The stripping of the full stop is what makes the check meaningful, because the manuscript prints a held
wording inside a bolded speech marker with the comma inside the closing quote and the tag outside it.**

Scope for this run, **volume-20 chapters, this record, the run record, the batch summary, the five live state files and the
volume index**, measured after every edit in §1 was made:

| Held string | Where the plan holds it | Characters as the plan prints it | Occurrences | Files |
|---|---|---|---|---|
| the decision's wording | §6.6, day 975 | **43** | **1** | **1**, `chapter-0975.md` |
| the panel's wording | §6.7, day 983 | **257** | **1** | **1**, `chapter-0983.md` |
| the cost of day 994 | §6.9 | 159 | **1** | **1**, `chapter-0994.md` |
| the question of day 994 | §6.9 | 51 | **1** | **1**, `chapter-0994.md` |
| the one thing said once on day 994 | §6.9 | 140 | **1** | **1**, `chapter-0994.md` |
| the refusal of day 965 | §6.10, day 965 | **124** | **1** | **1**, `chapter-0965.md` |

**The three wordings of day 994 live in one file and this pass edited that file nine times over for other findings, and
they are still at one occurrence each in one file each. That is the measurement of the hold and not an assertion of it.**

**The word at §6.8 is one word of eight letters and its instrument is a whole-word match with a non-letter on each side,
because a span of eight characters would print it. Measured across the same scope: 1 occurrence in 1 file, and the file is
`chapter-0985.md`. On days 991 to 1000: 0, in bodies and in headings.**

**And this pass's independent reader reported the same six strings at one occurrence each in their owner chapter and nothing
in `state/`, `reviews/`, `workspace/` or `outline/batches/` carrying any of them, and reported the held name at 0 across the
whole of `chapters/volume-20/`. This pass did not re-measure that name, because it does not sit in a blockquote this pass
was able to read, and declines to publish a figure for it.**

---

## 4. FOUR LOOKED AT AND LEFT STANDING, NAMED SO A LATER READER DOES NOT TAKE THEM FOR OVERSIGHTS

1. **A count of *about four* without *people* in `chapter-0983.md:23` — *She stood there about four minutes.*** §14.5 says
   no chapter may print *about four* without *people*, and this is the only breach of it anywhere in Volume 20; all seven
   printed on days 991 to 1000 are clean. **It is one clause and it is a four-word fix and this pass did not make it**,
   because `reviews/volume-20/batch-0004.md` publishes *A WOMAN ALONE IN FRONT OF IT FOR ABOUT FOUR MINUTES* in its §1 card
   table and again at its §9, and a repair pass on batch 0005 does not own another batch's run record or its chapter.
   **The volume close owns both and the fix is to read *She stood there about as long as it takes to say something twice***
   and to amend the two sentences in that record. **It is named here so it is not rediscovered as new.**
2. **`chapter-0995.md:27` glosses the volume's motive in narration** — *He had asked for his own name on a page for
   thirty-one volumes and had never got it, and the one thing in this room that looked like a way of getting it was six
   strokes with a day against each of them*. §16 item 8 bars the day-994 thing being set beside the day-154 sentence and
   §12 and §16 item 18 bar the finding in a **mouth**, and this is narration and it is a man's private thought on the day
   whose card is a person alone in front of a thing. **Left standing.**
3. **`chapter-0998`'s closing used to sit on two lines cut in the crust at the store's end of that row**, which is where the
   barred lines are, and §17.17(ix) bars the grit and a line in it. **It has been moved anyway, at §1.9, and not because a
   reader forced it: two closings in one batch on lines at the same end of the same row would have weakened the last image
   of the volume, which is 1000's.**
4. **`chapter-0999.md:9`'s plaster figure was wrong and is now right.** The block of writing went up on day 983, so on 0999
   the plaster beside it has been that colour for sixteen days and the chapter said twelve, having been copied from 0995
   where twelve is correct. **Applied: sixteen.** The separate *morning running* figure is a different quantity and runs
   cleanly across the volume — ninth at 0991, eleventh at 0993, twelfth at 0994, thirteenth at 0995, fifteenth at 1000 —
   and was not touched.

---

## 4A. THE LIVE STATE LAYER, AND WHAT IT COST TO KEEP IT HONEST

**Five live files, and every figure in them that this repair changed has been re-measured and rewritten.** What was wrong and
is now right: `state/current.md` published the *nobody*-chain figure as **1** and its instrument returns **3**, and that figure
was republished from there into this batch's own record; `state/chapter-summaries.md` carried the wrong thumb on the tradesman
at 994 in prose; `state/character-state.md` carried it twice more; `state/continuity.md` and `state/chapter-summaries.md` both
carried the enumeration of four at four joints in the grit, which four chapters contradict. **The five-point figure series are
re-measured in all three files that carry them** — 1,572.9 for the mean, and one in 63.4 on negation, 3.32/3.95/3.15/4.01/4.37
on bare *that*, and one in 91.4/146.7/141.5/100.7/102.9 on *his own*.

**The compaction, and whether it worked.** Size as found at the start of this pass, and size now, on the same files:

| Live file | Found | Now | Against the found size | Against its own archive |
|---|---|---|---|---|
| `state/current.md` | 16,109 | **15,932** | **−177** | −1,287 |
| `state/continuity.md` | 18,534 | **18,526** | **−8** | −1,888 |
| `state/open-threads.md` | 17,060 | **17,043** | **−17** | −213 |
| `state/character-state.md` | 20,302 | **19,539** | **−763** | **+1,154** |
| `state/chapter-summaries.md` | 21,126 | **20,559** | **−567** | −14 |

**All five are shorter than they were found. Four of the five are also shorter than their own pre-compaction archive copy.
`state/character-state.md` is the exception at +1,154 against its archive, and the reason is that its archive is 18,385 bytes —
which is to say the batch-0005 compaction itself made that file 1,917 bytes larger than the copy it took, and this pass has
brought it back below what it found but not below that copy.** Getting it lower would mean cutting prohibitions out of the
handle table and the manner rules, **and `AGENTS.md` and this layer's own rule are both explicit that the prohibitions are the
whole reason the file exists and are not compressible. So it is recorded here rather than solved by deleting a rule.**

**All five archive copies verify by SHA256**, each recorded hash in each live file matching the file it names, checked again at
the end of this pass and unchanged from the hashes the batch-0005 writing run recorded. Nothing was deleted.

---

## 5. WHAT THIS PASS DID NOT DO

**`outline/ending.md` was read and was not moved, not amended and not planned against.** No controller file was opened and
none was edited: nothing under `scripts/`, `.github/workflows/` or `.opencode/agent/`, and not `AGENTS.md`,
`PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json` or `state/phase-ledger.json`. `outline/volume-20.md`
and `outline/series.md` were read and not edited. **No day past 1000 and no chapter past 1000 exists. No panel line was
added, no seventh stroke went into any column of either book, no leaf was turned, no second nail went into that outside
wall, the bar stayed on the top step out of its two sockets on all ten mornings, no rope was lifted, no post of that fence
was moved and its totals are printed on no day of this batch, no satchel and no tin was opened, the trough's ice was not
broken and no heat was fetched for it, the tally-board was not turned over and its two lines of grey grit were not counted,
and the gate at the far end of that shut road is not mentioned on any of these ten days.**

**No name was spoken and no name was printed. No ordinal for a month was converted into a span. The stair was not counted
on any of the ten days — `nine steps` stands at 0 — and no person in these chapters stands on a step that does not exist.
The descriptor pool is at 0: the nineteen descriptors at zero in the last two volumes, *man of about thirty-seven* and *man
of about thirty* all return 0 on the same reading, and *woman of about fifty-four* returns 1, in the keeper's own mouth on
994, and 0 on days 995 to 1000. `assembly`, `council`, `quorum`, `seal`, `charter`, `crossing`, `witness`, `passage`,
`privilege`, `office`, `licence`, `license`, `earthside` and `player` all return 0 in the ten bodies and the ten headings,
`crossing` included.**

**AND THE NEXT PHASE IS STILL A VOLUME CLOSE, AND WHAT IT IS FOR IS A QUESTION FOR THE OWNER OF `outline/series.md` AND NOT
FOR A BATCH PROMPT, AND THIS PASS DID NOT WRITE IT AND CREATED NO DIRECTORY.** Volume 20 runs to day 1000 and its fifty
chapter files are on disk and `outline/volume-20.md` §13 lists what it leaves the world holding.