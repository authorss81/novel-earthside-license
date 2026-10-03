# Volume 19 Close — Chapters 0901 to 0950, days 901 to 950

**This is a close and nothing else.** It writes no chapter, no day, no person, no place, no document and no panel. It
moves no day, no card, no pressure tag, no cast member, no decision, no cost, no held string and no plot beat. It
answers no question. It merges no pair of people. It mends nothing, pays nothing, gives nothing, adjudicates nothing,
and writes past 0950 nothing. **There is no day after 0950 in this volume and this record does not name one.**

**Read first, in this order, and not moved:** `outline/volume-19.md`, the plan of record; `state/current.md`,
`state/continuity.md`, `state/open-threads.md`, `state/character-state.md` and `state/chapter-summaries.md`, the live
layer, carried forward and not rewritten; `reviews/volume-19/batch-0005.md`, the record of the last ten days and of
the repair pass over them; `reviews/volume-19/batch-0001.md` through `batch-0004.md`; `chapters/volume-19/`, the
fifty files on disk; `state/volume-18-close.md`, for the shape of a close record in this repository.

**AND WHAT IS AT THIS PATH ALREADY.** Nothing. **This is the first edition.** `workspace/volume-19/close/PROMPT.md`
exists and was written by the batch-0005 run in the same commit as the ten chapters behind this one, and four files
that had told the contrary were corrected in place before this run began — `state/current.md`,
`state/chapter-summaries.md`, `state/batch-summaries/volume-19-batch-0005.md` and `reviews/volume-19/batch-0005.md`
§11.3. This record inherits the corrected text and does not repeat the false sentence.

**AND THE REVIEWER. `reviews/volume-16/` does not exist and the review dispatch in this repository falls back to the
writer's own agent, because `novel-reviewer` is registered as a subagent. Nothing in this file is an outside reader's
finding and nothing in it should be taken for one. Every finding ever taken over this manuscript has been taken by the
agent kind that wrote the pages under it, and this record is that agent kind again. It says so here rather than
claiming an independence it does not have.** `logs/batch-0005.review.log` line 1 carries the dispatch fallback, and
the finding it produced is at `reviews/volume-19/batch-0005.md` §11.5 item 1 and is owed to workflow dispatch, which
no phase may open.

**AND THE RULE THIS RECORD IS WRITTEN UNDER.** Every figure carries its reading, its instrument and its scope on the
same line as the number. Where a reading is a judgement — a closing that states a change against one that states a
state, a repeated phrase that is a descriptor handle the plan requires against one that is not — the reading, the
instrument, the scope, the cases an outside reader could argue the other way and every competing number are published,
and **no count reached by reading is printed as the word zero.** `outline/volume-19.md` §17.21 and §17.22 bind this
record, and §17.22's second clause binds it harder than the first: **a record may not publish that a held string has
appeared on exactly the number of pages it appears on unless it has run the instrument that counts it in the same run,
and a record that asserts an absence it has not measured is the failure §17.11 names.**

---

## 1. The fifty-day run, verified forward and reverse

### 1.1 The run itself

| What | Figure | Reading, instrument and scope on the same line |
|---|---|---|
| Chapter files on disk | **50** | directory listing of `chapters/volume-19/`, scope fifty files, `chapter-0901.md` through `chapter-0950.md`, no gap, no double, nothing past 0950 |
| Chapter equals day | **50 of 50** | numeric stem of the filename against the day, both orders, scope fifty files: forward by ascending index from 0901, and again with the index rebuilt from 0950 downwards — zero mismatches on both runs |
| Weekday | **50 of 50** | `weekday(d)` with day 1 a Tuesday, checked forward and in reverse — zero mismatches; and separately against the date sentence each body carries, 50 of 50 agree, scope fifty bodies |
| Bare-Month ordinal, as the pages carry it | **50 of 50** | the ordinal word-form in each body's own date sentence parsed word by word out of the printed words and set against day less 315, scope fifty bodies, **zero disagreements. One form is unusual and is named rather than left to look like a fault: 0915 carries the round form for six hundred, which is the correct English for that value.** The instrument is written out at §1.2 so that a later reader can re-derive it |
| Ordinals, range | **586 to 635** | same computation, scope fifty bodies; the highest Bare-Month ordinal printed anywhere in the fifty is six hundred and thirty-five, on 950 |
| Both ends | **day 901 a Saturday at Bare-Month 586; day 950 a Saturday at Bare-Month 635; forty-nine days apart** | same computation, scope the two ends. **49 = 7 × 7, which is `outline/volume-19.md` §14.1's trap, and no middle day of this volume was derived from either end.** Every one of the fifty rows in §1.1 was re-derived from two figures and two figures only — day 1 is a Tuesday, and the Bare-Month ordinal is the day less 315 — and the plan's own §14.3 table was validated against that derivation rather than transcribed |
| One date form only | **50 occurrences of *the Nth day of the Bare Month* and no other form** | every `X day of the Y` in the fifty bodies enumerated and counted, scope fifty bodies: **fifty occurrences, twenty-three distinct ordinal words, one month.** **Each of the fifty date sentences is a distinct phrase — no two of the fifty repeat a day — and every one of the fifty qualifies the same month.** No chapter of days 901 to 949 uses an ordinal for a month, no chapter converts an ordinal into a span, and **no chapter of the fifty says what the month is called, how many days it has, whether it is long or short, or what it does at its end** — the last of these is a reading over fifty bodies and is published as one; the first three are measured below at §1.3 |
| Titles | **4 to 8 words of title text** | words after the em dash on each heading line, scope fifty headings; none outside §17.8's four to nine |
| Digits in bodies | **0 in 50** | `[0-9]` after the heading line, scope fifty bodies; the only digits in the fifty files are the chapter numbers in the fifty headings |
| Words across the fifty bodies | **54,377 total, mean 1,087.5, shortest 770 at 0929, longest 1,705 at 0943, spread 935** | whitespace tokens, heading line out, scope fifty bodies |
| Paragraphs | **500** | blocks between blank lines, heading out, blocks that are empty or exactly `---` dropped, scope fifty bodies |
| Speech paragraphs | **128** | a surviving block containing `**"`, scope fifty bodies; per file, minimum 1 at 0936, 0938, 0939, 0941, 0942, 0944, 0945, 0946, 0947, 0949 and 0950, maximum 5 at 0901 |
| Bold marks and quotation marks | **372 and 372** | literal `**` and `"` counts, bodies only, scope fifty bodies; **bold spans carrying no quotation mark: 0** |
| Panels | **1** | a surviving block whose first character is `>`, scope fifty bodies. §4 below |
| `nobody` | **166 in 44 bodies, and 1 in 1 heading** | `\b[Nn]obody\b`, both case flags, scope fifty bodies and fifty headings counted separately. **The heading is 0912's, and its title is four words of title text inside §17.8.** Sentence-initial `Nobody`: **41 across the fifty, longest run 2, at 0941** — §16 item 2's ceiling is three in a row and it is not reached anywhere in the fifty |
| Pressure column of the plan's own map | **sums to 50 on seven distinct tags** | parsed from `outline/volume-19.md` §14.3's own column, scope fifty rows: **recovery 10, physical 9, character 10, political 7, discovery 7, cost 5, decision 2.** §15 states the same seven figures in the same order and agrees at every one. **A plan's column is not a measurement of the fiction and is not presented as one; what the fifty bodies are measured against it is at §8** |
| The Adrian column of the plan's own map | **11 rows marked, and 11 files carry him** | the column parsed from §14.3 gives 903, 909, 915, 921, 927, 933, 935, 939, 940, 941 and 943; the literal string `Adrian Vale` measured word-bounded in the fifty bodies returns **30 occurrences in exactly those 11 files, and in no other.** §4.1's nine plus 941 plus 943, and §3 below |

### 1.2 The instrument for the two date rows, written out

`outline/volume-19.md` §14.1 says a batch re-derives the run and does not transcribe the plan's table. This is what
that derivation is, so that a later reader can rebuild both rows from the files alone.

- **Scope.** `chapters/volume-19/chapter-0901.md` through `chapter-0950.md`, each read as everything after its first
  newline. Headings are excluded from body counts and measured separately.
- **Weekday.** `WD = [Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday]`, `weekday(d) = WD[(d - 1 + 1) mod 7]`,
  checked against the first `It was <Wordday>,` in the body.
- **Bare-Month ordinal.** Take the maximal run of words immediately preceding ` day of the Bare Month`, allow hyphens
  inside a word and `and` between words, drop a leading `the `, and resolve the words additively with `hundred` and
  `hundredth` multiplying the running total by one hundred. Map the cardinals *one* to *nineteen*, the tens *twenty*
  to *ninety*, and the ordinals *first* to *nineteenth*, *twentieth*, *thirtieth*, *fortieth*, *fiftieth*, *sixtieth*,
  *seventieth*, *eightieth* and *ninetieth*. **The value the words resolve to is set against `d - 315`.**
- **Why the resolution has to be additive with a special case for the hundreds, and not positional.** *six hundred
  and twenty-fifth* is 6 + 100 + 20 + 5. *the six hundredth day*, which occurs once in these fifty, at 0915, is
  6 × 100 and **a parser that adds *hundredth* as an ordinary hundred returns 106 for it and reports a fault on a page
  that is right.** **That is the whole reason this row publishes its resolution rule in full: one page of the fifty
  uses a form the other forty-nine do not, and an instrument that has not been told about it will spend a reader's
  afternoon on it.**

### 1.3 The three words nobody is told, measured

`state/volume-10-close.md` and `state/volume-12-close.md` establish the standing practice for this row and this run
re-measured it rather than carrying it forward.

| Word | Occurrences across the fifty bodies | Files | Applied to the month |
|---|---|---|---|
| **length** | **55** | 31 | **0 of the 55** |
| **long** | **44** | 27 | **0 of the 44** |
| **short** | **11** | 10 | **0 of the 11** |

**One hundred and ten occurrences and not one of them is about the month.** The fifty-five lengths are of a bar, a
bench, a sill, a page, a board, a rope, a shelf, a wall, a row of flags, the shut length of a road, the length of a
minute, the length of a hand, a finger and a thumb; the forty-four longs are of a time, a wait, a stretch of
weather, a look, two hollows in a yard and the long light on a bench; the eleven shorts are of a turn, a stack of
boards, a stick of chalk, a thumb's width short of a margin and a place a man stopped short of. **Instrument: `\bword\w*\b`,
both case flags, scope fifty bodies, and the classification of each occurrence is a reading and is named as one — the
reading is available to be disagreed with, and the whole of it is which noun each of the hundred and ten stands
next to.**

**And the three words are still not told.** No chapter of the fifty says what the Bare Month is called, how many days
it has, or whether it is long or short, and this record does not say it either. **A close record that looks as though
it has given the month a length has thrown away the cheapest protection this book has bought for a small effect.**

### 1.4 The room, and the figures that are not allowed to reach it

| What | Figure | Reading, instrument and scope on the same line |
|---|---|---|
| A headcount of that room, in any mouth or in any narration | **0 in 50** | a sweep of every numeral-plus-person-noun phrase across the fifty bodies returns **106**, and each of the 106 was read: they are the census at the foot of that stair, a count of people at a gate on a road, a count of shapes, holes, boards, books, rectangles or lines, or a phrase about two named people and not about the room. **A second sweep for *about nine people*, *nine people*, *nine of us*, *nine in that room*, *about nine in* and *there were nine* returns 0 for all six across the fifty bodies.** The one near miss is at 0901, where a mouth says about nine of them went through the gate — a gate outside the room, and the census the plan puts there |
| The two nearest figures a reader will find and mistake for a headcount | **2, and both are named** | **0941 states in a narration paragraph — not in a mouth — that about four people in that room answered the questions of that hour and about four people said nothing at all** — a partial count of a room, and **no total anywhere in the sentence or in the chapter.** **0939 states that three of them were at that bench** and that the rest of the room went on round them. **Neither is a headcount and this record does not report either as one.** §17.20's frame (4) is the shape 0941 is built on, and the plan's frame carries a total that §16 item 1 forbids; the page used the frame's second half and left the total off, and that is what a card obeying both clauses looks like |
| *About four people a day* | **30 occurrences of the string *about four* in the fifty bodies, and every one of the 30 has the word *people* inside the next thirty characters** | literal string, then a thirty-character lookahead, scope fifty bodies. §14.5 forbids printing *about four* without *people* and **not one of the thirty breaks it.** The census was never reduced to a smaller number and was never used as a count of anybody |
| The census of the room against the census of the foot of the stair | **different quantities and both are published** | 0941's four-and-four is a division of one room's answers on one morning; *about four people a day* is a walk-past count at a step. **They are not the same figure and this record does not add them, and no chapter of the fifty adds them** |

---

## 2. The seven words, their seven days, and the forty-three

**`outline/volume-19.md` §6.4 fixes seven words on seven days. `outline/volume-19.md` §21.3 names them openly in the
plan and in the state layer because a writer cannot be handed a day without being told which word belongs to it, and
this record follows that practice: the words are named here, against their own days, and nowhere else. **What is
withheld is the occurrence, not the word.** No chapter may print one of these seven on any day but its own, and the
table below is the measurement of that, taken in this run, each word measured separately, bodies and headings counted
separately.

| Word | Its own day | Occurrences in the body of that day | Occurrences across the other forty-nine bodies | Occurrences across the fifty headings | Inflected forms anywhere in the fifty bodies |
|---|---|---|---|---|---|
| `crossing` | 905 | **1** | **0** | **0** | **0** |
| `witness` | 911 | **1** | **0** | **0** | **0** |
| `assembly` | 916 | **1** | **0** | **0** | **0** |
| `council` | 921 | **1** | **0** | **0** | **0** |
| `quorum` | 925 | **1** | **0** | **0** | **0** |
| `seal` | 930 | **1** | **0** | **0** | **0** |
| `charter` | 934 | **1** | **0** | **0** | **0** |

**Instrument: word-bounded, both case flags, each of the seven measured separately, fifty bodies and fifty headings
counted separately, and the inflected column swept for `-s`, `-es`, `-ed` and `-ing` of each. The count is the whole of
the claim and no span of any of the seven is printed in this row.** §6.4 rule (i) requires zero on the forty-three days
that are not a word's own and **zero is what the forty-nine-other-bodies column returns, one word on its own day and
nowhere else.** Rule (ii) puts the saying in a mouth and not in the narrator's; **each of the seven occurrences is
inside a bold speech paragraph and none is in a narration sentence** — measured by locating each occurrence and
reading the block it stands in, seven blocks, one per word. Rule (iii) makes the cost of saying it the first speech
paragraph of that chapter; **all seven word-days carry a speech paragraph whose first characters are `**"` and each
carries the cost before the thing**, measured by reading the first two speech blocks of seven files. Rule (v) forbids
a word in a heading and **the fifty headings return zero for all seven.** Rule (vi) forbids a chapter from saying a
word has come back or how long it had been gone, and **no sentence of the fifty says either** — a reading over fifty
bodies, published as one.

**And the seven days carry a tag that is not *cost* on five of them, which §15 asks a reviewer to notice and which
this volume's own map holds:** 905, 916 and 930 are *political*, 921 is *character*, 925 is *decision*. **The
remaining two word-days, 911 and 934, are *cost*, and 903 and 918 and 940 are *cost* and carry no word.** **Seven of
the fifty days in this volume are days on which a person writes nothing at all, and that is the count `outline/volume-19.md`
§18 relies on to keep seven words from becoming a ceremony.**

---

## 3. The fixed days, each to its date and to its mouth

**All wordings are held where the plan holds them. This record prints none of them, paraphrases none, describes none
closely enough to reconstruct one, and certifies no absence about any of them beyond a count it has run.** §6.1 below
is that count. A count may be published; a span may not.

| Day | Weekday, BM ordinal | What is on the page, and what is not | Instrument and scope on the figure beside it |
|---|---|---|---|
| **903**, first cost | Monday, 588 | Named by the woman of about fifty-two, in her own mouth, and it is the **first speech paragraph of the chapter** — the paragraph's first characters are `**"`. Nobody thanked her and nothing was done about it at that hour or any other | reading of the file; the speech-paragraph position measured, one file. **This is the only day of the fifty on which a person pays a cost and is thanked on none of the fifty and holds no book** |
| **905**, the first word | Wednesday, 590 | Said once, by the stallholder, in daylight, with the date in chalk on the outside of the door at the foot of that stair behind him. His own board, his own two stalls along, and his own board is not the board of day 875. **The chalk did not come out of his inside breast pocket on this day or on any day of the fifty** | §2's row for the word, one file; the pocket measured at 0949 and §5 below |
| **908**, the surface that changes | Saturday, 593 | The keeper takes the second slate off the shelf behind the bench, turns it over, and puts it back the same afternoon. **No chapter prints what is under the day cut across the head of that slate and no mouth asks about it** — the string is at 0 across the fifty bodies and the fifty headings, and §6.1 publishes that count | block-measurement of the slate's handling read against §6.5, one file; the word under the day measured across fifty bodies and fifty headings |
| **911**, the second word | Tuesday, 596 | Said by the woman of about twenty-nine who keeps a public register, in her own mouth, the cost first, and it goes on longer than anything else said in that room that morning. **Nobody thanked her and nothing was done about it** | §2's row, one file |
| **916**, the third word | Sunday, 601 | Said by the woman of about fifty-two, in her own mouth, the cost first. **She is thanked for none of her three costs on the fifty days and pays three of them** | §2's row, one file |
| **918**, the name | Tuesday, 603 | **The first writing of that name on any surface in this manuscript, on one page, in one hand, once.** He writes it himself in the column that holds figures with a day against it, and in the same morning **the sixth stroke goes into the register in the keeper's own hand with a day against it, and it is not struck.** Nobody thanks him, the chapter does not say whose line it is, and no one in the room looks at a name while it goes in | the held name measured by literal scan, 1 occurrence in 50 bodies, 0 in 50 headings, 35 in 17 files of Volume 18 — §6.1 |
| **921**, the fourth word | Friday, 606 | Said by the man of about thirty-nine who trades on a board, in his own mouth, the cost first. **In the same chapter he asks, in the ordinary way of that stair, whether anybody would fetch a heat for the trough at the top of the step, and the man who could has the bucket standing with ice in it, and the heat is not fetched by any hand at any hour of that day** | §2's row, one file; the heat measured across the fifty bodies at §5 |
| **924**, a figure in a space | Monday, 609 | A figure goes into the space about two fingers wide at the foot of the middle column of his own board, in his own hand, and **it is a rate and not a name.** Nobody in that row is told what it is, nobody is thanked, and the chapter does not say how long the space had stood empty. **The figure is not standing in that space at 947 and nobody in that row saw it go, and it is on no surface on any of the fifty days and in no column of either book** | presence and absence measured by reading, one file at each end; the one concrete fact the page gives and does not explain is that the wood inside that space has never been wet, because the cloth stops at the middle column every morning |
| **925**, the decision | Tuesday, 610 | The nearer of the volume's two middle days, and it is a decision about a second book and not about the gate and not about the man who wrote his name in it four days ago. **She names the cost out loud first, in her own mouth, and then says the decision, in her own mouth. Nobody agrees, nobody argues, nobody improves on one word of it, nobody is thanked, and nothing whatever is done about it at any hour of the twenty-five days that follow except that the second book is on that bench** | held wording measured at 1 occurrence in the fifty bodies, 0 in the fifty headings — §6.1; the cost of that decision measured at 0 whole and 0 at each of three clause lengths |
| **929**, the panel | Saturday, 614 | §4 below. **Nobody says it is right and nobody says it is wrong, nothing whatever is done about it at any hour of that day, and it is not printed, not read aloud and not answered on any of the twenty-one mornings that follow it** | §4 |
| **933**, the gate | Wednesday, 618 | **The gate is shut for one morning and open on the next.** He draws it across the opening and puts the latch down, and about nine people are on that road that morning and **four of them do not get through it.** Nobody thanks him, nobody says he was wrong, and no mouth on that road says one word to it | read against §4.1's row, one file; **and see §5 item 4, which names what this volume's fifty bodies do and do not say about the gate after that morning, including that no chapter of days 934 to 950 mentions the gate at all** |
| **934**, the seventh word | Thursday, 619 | Said by the woman of about twenty-nine who keeps a public register, in her own mouth, the cost first, four days before the act. **Nobody thanked her and nothing was done about it** | §2's row, one file |
| **935**, the promise | Friday, 620 | **Milestone ten is paid here, as a promise and not as a repair.** Tamsin Quill comes up that stair and says one thing once and Adrian Vale says one thing once on the same morning and neither says it twice. **Neither of their names goes in a column of either book on that day and the chapter says so in a sentence of its own. No chapter of the fifty says a relationship is repaired, no chapter gives the fifth condition, and no chapter puts them in one room and one life** | the two names' absence from every column measured by reading all three entry-days at §5 item 2 and by §16 item 14's own two clauses; Tamsin Quill measured at 12 occurrences in 1 file, 935, and in none of the other forty-nine |
| **939**, seven places | Tuesday, 624 | The man who came up that stair on 866 and the man of about thirty-nine are in that room together for the first time since 878, and between them and the keeper they work out where seven books sleep at night. **The seven places are the seven places of §5, one book in each, and no place is renamed. No book is called anything and nobody is given a title — `title` and `office` stand at 0 across the fifty bodies and the fifty headings. The seven marks were drawn in the dust on the top of the bench with a finger, and at the light's going the keeper rubbed the last of the seven out and left the other six standing** | the seven places counted against §5's seven in the order the page gives them, one file; `title`, `office`, `document` and `documents` measured at 0 across the fifty bodies |
| **940**, the act | Wednesday, 625 | **The climax.** He comes up that stair in daylight with a date in chalk on the outside of the door behind him, names his own cost out loud first in his own words, says one thing once, and the woman who keeps the second book says it back in her own words on the same morning. Nobody thanks either, nobody agrees, nobody argues, nobody improves on one word of it, and nobody asks either of them a second thing at any hour of the ten mornings that follow. **His name goes into the second book in the column that holds figures with a day against it. From the morning after, no mouth in that room may treat his name as an answer to anything.** He opened nothing, closed nothing and repaired nothing | three wordings measured at 1 occurrence each in the fifty bodies and 0 in the fifty headings — §6.1. **And §16 item 18's rendering is measured across all ten of the days after it: `seat`, `steady`, `steadier` and `stable` stand at 0 across the fifty bodies, and the giving-up is rendered as ordinary behaviour** |
| **941**, the morning after | Thursday, 626 | He is asked one question in the ordinary course of an hour about the shape of a page and not about what a line says, he answers it, and **nobody acts on the answer, nobody thanks him, nobody tells him he was right and nobody tells him it was not wanted. The chapter does not report what he said** | §3's own row, one file; and §1.4's row on the partial count |
| **943**, the resolution | Saturday, 628 | **Two entries about one day stand in two books in one room and neither is read out.** A person who was not in that room and has not been in it on any of the fifty days disputes a line in the second book about a day that is not his own, names the cost first, will not say what the line says and will not ask anybody to tell him he is wrong. **The keeper does not tell him he is wrong and does not tell him he is right.** She turns the book so the leaf faces the door, he reads it standing at the bottom step, then he comes up and puts his own account of that day into the register in his own hand with the same day against it, with her hand at the foot of the same page and neither hand taken off. **Nobody is thanked and nobody is told anybody else was right, and the two entries are still standing at 950** | read against §11, one file; the non-adjudication measured — §8 below. **This close does not settle it and may not** |
| **950**, the last image | Saturday, 635 | A page read down by a keeper's hand, a surface read across by a board-man's eye along the outside face of the open door, and a third thing that is neither. **The woman of about fifty-two takes a stick of chalk out of the box on the table, is outside at the foot of that stair for a while with her back to the room, and comes back and puts the chalk in the box. By the light's going there is one mark on the bare piece of board under the date and one only, a single upright stroke, in her own hand. Nobody in that room asked her what it was and nobody thanked her. The two entries of 943 are still standing in the two open books and nobody compared one leaf with the other** | the bare board named in 26 of 50 bodies and asserted bare in 26 of those 26, and **950 is the only file of the fifty that carries a mark on it and it says in a sentence of its own that it carries one mark and one only** — §5 item 1 |

**Midpoint is 925 and climax is 940. The twelve heavy days are 903, 905, 908, 911, 916, 918, 925, 929, 934, 940, 943
and 950** — reading: `outline/volume-19.md` §1 and §14.3, scope fifty days, and the plan's own pressure column agrees
at seven tags summing to fifty. **Adrian Vale is in eleven of the fifty and in thirty-nine he is not, and his eleven
are the plan's eleven.** He obtains a thing on two of his nine days and on neither of the two extra days, nobody thanks
him on any of the eleven, nobody tells him he was right on any of them, and `outline/volume-19.md` §4.1 says in its own
words that a plan that has converted those two into a ladder has misread its own table. **This record publishes both
and reads them neither way.**

### 3.1 The standing disagreement about 943, published and not settled

**`outline/volume-19.md` §11's first clause says the disputer is a person who has not been in that room on any of the
fifty days, and §11's own middle has a keeper turning the book so he can read the line on one of them. Chapter 0943
holds both facts by stage and explains neither: he stands at the bottom step for the disputing and for the reading,
comes up for the writing, and is back at the bottom step at the light's going.** Both clauses are the plan of record,
the page is written, and **this close does not adjudicate between them and may not.** It is item 3 of §9 below.

**AND THE SECOND STANDING COLLISION, WHICH IS THREE PLACES IN THE PLAN AGAINST TWO.** `outline/volume-19.md` §3 and
§16 item 14 say that neither of the two names the consent fracture concerns goes in any column of either book on any
of the fifty days, and §6.7 and §6.9 put one of them in the second book on 918 and on 940. **Both readings are the
plan's, both are already realized on two written pages, and this volume satisfies the stricter one as well: measured
over the fifty bodies, the second book receives an entry on 918 and on 940 and on no other day, and neither of those
two names stands in any column of either book on any of the fifty.** That is a fact about what is on the pages and not
a decision about which reading governs, and **this close does not decide it and may not.**

---

## 4. The panel

| What | Figure | Reading, instrument and scope on the same line |
|---|---|---|
| Panels in Volume 19 | **1** | a surviving block whose first character is `>`, scope fifty bodies, whole files |
| The file | **`chapters/volume-19/chapter-0929.md`**, standing by itself in a block with no mark on the face of it | reading of the file, one file |
| The wording held at §6.8 | **identical on the page and in the plan, and on no third tracked file** | the two blockquote blocks compared with the markers stripped and all whitespace runs collapsed to one space: **268 characters on each side**, and **that length is the figure §6.8 publishes for itself**, which is the one independent check that can be made without printing the span. Also measured at its three line-lengths — 106, 112 and 48 characters — one occurrence each |
| Where the wording lives | **2 tracked files — `outline/volume-19.md` §6.8 and `chapters/volume-19/chapter-0929.md` — and nothing else** | the same block-level instrument over the tracked set, **1,511 files by `git ls-files`**, whitespace normalised. `logs/` is gitignored, no log is tracked, and no whole-tree file count is reproducible, so none is printed as one. **No state file, no batch record, no review record, no prompt and no summary carries it, and this record is the last of those and does not either** |
| Occurrences | **1 in the fifty bodies, 0 in the fifty headings** | literal normalised match, scope fifty bodies and fifty headings counted separately |
| Not one word reprinted here | **and not paraphrased, improved on, described closely enough to reconstruct, or certified absent** | the rule is `outline/volume-19.md` §6.8 and §16 item 3; this record measures and does not print |
| Nobody says it is right or wrong, and nothing is done about it | **holds on the day and on the twenty-one days after it** | reading of `chapter-0929.md` for the day: the chapter says so in a sentence of its own. **And `chapter-0929.md` is the only file of the fifty that contains a block beginning with `>`; no chapter of days 930 to 950 prints it, reads it aloud or answers it**, scope twenty-one bodies |
| The panel of Volume 18 | **printed on its own page at `chapters/volume-18/chapter-0886.md`**, and `state/volume-18-close.md` §4 carries it | **The divergence is published in the plan behind each volume and it is not a defect in either** |

---

## 5. Where every standing object stands at day 950

Each row is the state after Chapter 0950. The figure beside each is **how many of the fifty bodies mention the object
and which is the last body that does** — literal-string or phrase match, scope fifty bodies — so that a reader can
see how thin or how thick the evidence is for each. **A last-mention figure is a figure about the fifty days, not a
proof of a state, and where a row's state rests on the live layer rather than on a late page this says so.**

1. **The bare piece of board under the date in chalk.** Named in **26 of 50 bodies** on the wider phrase — *bare
   piece of board* in 19, *bare board* in 5 and *board under the day* in 7, with overlap — and last at 0950. **All
   twenty-six of the twenty-six assert that it carried nothing, stood clear of the wood, was empty, or had nothing on
   it whatever. 0950 is the only file of the fifty that carries a mark on it — a single upright stroke, thick at the
   top and thin at the bottom, pressed into the grain, in the hand of the woman of about fifty-two — and the chapter
   says in a sentence of its own that it carries one mark and one only.** One body at 0928 says in a sentence of its own that nothing went
   under the date on that day, and one at 0940 says that nothing went under it. **No chapter of the fifty says what
   the mark is for, and this record does not either.** The board meant nothing whatever on forty-nine of the fifty days
   and **what is on it is not a day of any month this manuscript has named** — measured: the only day-form in the
   fifty bodies is *the Nth day of the Bare Month*, fifty occurrences, and no other `X day of the Y` form.
2. **The register and the second book, on one bench.** The register is named in **33 of 50 bodies** and the second book
   or the second slate in **23**, both last at 0950. **Three entries stand in the two books across the fifty days and
   three is the whole count:** a name into the second book on 918, a name into the second book on 940, and an account
   of a day into the register on 943. **The sixth stroke went into the register on 918 in the keeper's own hand with a
   day against it, is not struck, and `seventh stroke` stands at 0 across the fifty bodies.** From 921 the register is
   named with six strokes in the column that holds figures, at 922, 925, 926 and 929 and on the bench at 950 beside the
   second book with its cover slab off its leaf. **At 950 both books lie open side by side and neither is shut and
   nobody in that room compared one leaf with the other.** **Neither of the two names the consent fracture concerns
   stands in any column of either book on any of the fifty days.**
3. **The bar on the top step, out of its two sockets.** Named in **27 of 50 bodies**, last at 0950, and a body
   naming the bar together with its sockets is **26**. **No chapter of the fifty puts it back in its sockets, lifts it
   out of the weather, or says what it was for.** Each of those three is a measurement and not a reading, and all three
   are published with what the sweep returned instead:
   - **A sweep for the bar being put back, lifted off the step or socketed returns 15 hits across 14 files, and every
     one of the fifteen is about a different object** — a bucket, a cloth, a hand, the slate, a knife, a board, a book,
     a figure and a bag. Not one is about the bar.
   - **Ten sentences across ten of the fifty name the bar and a socket in the same breath, and all ten say it is lying
     out of its two sockets** — 901, 903, 906, 908, 911, 912, 913, 917, 937 and 939. **Not one of the ten, and not one
     of the fifty, says the bar was put back.**
   - **A sweep for what the bar was for returns two candidates, and both are the word *for* inside another phrase** —
     903, where the words are *since before the flood*, and 932, where they are *dry for once*. Neither is about the
     bar's purpose.

   **And no chapter of the fifty joins any morning of this volume to the morning the bar came out of its sockets.**
   The two sockets on the far side of the door below stood empty on every one of the fifty.
4. **The gate at the far end of the shut road.** Named in **8 of 50 bodies** — 901, 902, 905, 910, 912, 914, 933 and
   939. Four of the eight assert it standing open, and 933 is the one morning this volume shut it and says so by
   having a hand draw it across the opening and put the latch down. **No chapter of days 934 to 950 mentions the gate
   at all**, so the fact that it stood open again on the next morning and on the forty-eight mornings after that rests
   on the plan at §5 and on the live layer, and **not on a page of this volume.** That is published here rather than
   left to be found, because a reader who checks will find nothing after 939 and should be told why.
5. **The trough at the top of that market step, and the heat nobody fetches.** Named in **21 of 50 bodies**, last at
   948, and the word *heat* in **7**, last at 928. **Nine passages across six of the fifty mention fetching, carrying
   or lighting a heat — 903, 909, 917, 921 three times, 926 and 928 twice each — and every one of the nine is a
   refusal, a statement that nobody has fetched one, or an asking that nobody answers**, and one of the three at 921
   is the asking itself. **No hand and no mouth fetches one on any of the fifty days and no chapter breaks the ice.**
6. **The length of new rope over the back of that chair.** Named in **6 of 50 bodies**, last at 939. **Only 927 joins
   an action verb to it, and it does so three times: once to say that the rope lay on the wood in one line and not in
   two, which told the man looking at it that the chair had not been shifted since the rope went on it, and twice to
   refuse — that he did not lift it and did not ask the man who had put it there one thing about it, and that the rope
   was not cut at any hour of that day and the chair was not shifted.** **The man of about fifty-seven is asked nothing
   on any of the fifty days.**
7. **The fence of sixteen willow posts and eleven withies.** Named in **6 of 50 bodies**, last at 946. *Sixteen posts*
   is in 3 and *eleven withies* in 3, both last at 923, and **the two counts never appear apart from each other.**
   The only sentence in the fifty that joins a measuring verb to the fence is 946, and it is a negation — a man saying
   he did not measure it and did not move a post on it and did not go back that way at all. The only sentence that
   joins a moving verb to a post is 923, and it is **he moved no post**. **No chapter of the fifty measures the fence,
   moves a post, or puts a withy on or takes one off**, and no chapter prints a different total.
8. **The satchel with the flap down.** Named in **32 of 50 bodies**, last at 950. **No chapter of the fifty opens
   it, twice over at 945 — once with the row going past and once with nobody in that yard at all — and no chapter of
   the fifty says why he opens nothing he carries.** At 945 it stands where he put it down with its flap curled and
   dried and standing out from the leather the width of a card, and it is still shut.
9. **The tally-board face up with two lines of grey grit across it.** Named in **7 of 50 bodies**, last at 946. **No
   chapter of the fifty turns it over and no chapter counts its two lines as figures.** At 930 a hand lifts it off the
   top of a stack, turns it round in the air and sets it back down face up where it was, and the two lines are not
   broken by anything.
10. **The box of chalk whose lid does not shut.** Named in **21 of 50 bodies**, last at 950. **No chapter of the
    fifty shuts it and no chapter of the fifty takes the stallholder's own piece of chalk out of his inside breast
    pocket.** A sweep of the fifty bodies for a hand going into that pocket returns 0949 alone, and on 0949 the thing
    does not come out, and **no figure for the day that pocket was last opened is printed on any of the fifty days.**
    §6.1 carries that figure's count.
11. **The two-finger space at the foot of the middle column of the tradesman's board.** Named in **10 of 50 bodies**,
    last at 947. **A figure went into it on 924 and was not standing in it at 947 and nobody in that row saw it go, and
    it is on no surface on any of the fifty days and in no column of either book.** The one concrete fact the volume
    gives about the space is that the wood inside it is paler than the wood either side of it, because the cloth
    comes down that face every morning and stops at the middle column and has never once been into the foot of it.
    **No chapter of the fifty measures that board, moves that trestle, or calls it the board of day 875.**
12. **The stool a foot further out with the dust gone off the wood of its near leg.** Named in **15 of 50 bodies**,
    last at 950. **Nobody sits on it on any of the fifty days and no chapter says why it went out of its corner or
    why it came out.** On 950 the woman of about fifty-two says out loud once that she carried it out of the room it
    came out of and set it against that wall and has stood ever since, and that nobody has ever sat on it and nobody
    has ever asked her why.
13. **The sill and the two shapes pressed into the dust of it.** Named in **5 of 50 bodies**, first at 903 and last at
    939. **No chapter of the fifty dates either shape and no chapter says which hand put the newer one down or on
    what morning** — and on 903, which is one of his nine, the man of about twenty-seven wipes the length of that sill
    six times, stops twice where Adrian Vale's own hand is, and leaves the dust standing in that end of it.
14. **The two hollows in the flags at the side of the wharf yard.** *Hollow* is named in **5 of 50 bodies**, 13
    occurrences, first at 902 and last at 946, and the pair in **the same 5**. **At 946 the water came back into both
    of the two hollows a hurdle's feet had pressed that morning and stood in them exactly as it had stood in them
    before he came** — which is that chapter's closing, and §8 argues it as one of the four closings an outside reader
    could call a statement that nothing changed. **No mouth in the fifty dates either hollow and no barrow is put over
    one.** *(Volume 18's close gives 7 of its fifty for this object; that figure is not carried here, because this row
    was measured again and returns 5 and 3, and both numbers are given rather than one being inherited.)*
15. **The board on the outside wall at the far end of that market, on one nail with the hole of the second empty
    above it.** The board or the outside wall is named in **6 of 50 bodies**, first at 901 and last at 939; *nail* in
    **10**, last at 944; and the empty second hole in **4**, first at 914 and last at 939. **No chapter of the fifty
    writes on that board and no second nail goes into that wall above it.**
16. **The door at the foot of that stair.** Named in **16 of 50 bodies** and asserted standing open in **16** — 901,
    903, 904, 905, 907, 911, 912, 915, 918, 921, 934, 936, 943, 944, 946 and 950 — first at 901 and last at 950. **No
    chapter of the fifty shuts it and no chapter of the fifty has anybody watching it.**

**And these stand with them, none moved:** the strip of ground at the foot of that stair, **never measured, never
cleared, never paved over, and never named in any of the fifty bodies — the phrase stands at 0 across the fifty, which
is a measurement about a phrase and not a claim that the ground is never referred to**; about four people a day, which
is a census and not a person and is never reduced and never used as a count of anybody; the box of chalk whose lid
does not shut, in **21 of 50 bodies** and last at 950; and the handcart with the hazel mallet bound in cord, named in
**9** and last at 946.

**AND THE SENTENCE THIS RECORD HAD TO WRITE ITSELF, because the alternative was the fault `outline/volume-19.md`
§17.22 names.** `state/volume-18-close.md` §5 gives a mention figure for every one of its objects, and a writer who
copies those numbers forward publishes figures about a volume they were never measured on. **Four objects in this
section were first written here from that file rather than from an instrument: the two hollows, the outside-wall
board, the empty second nail, and the door at the foot of the stair. All four have been measured here, and what the
other close published for its own fifty against what this close measures for this fifty is 7 against 5 for the
hollows, 5 against 6 for the board with the nail, nothing against 4 for the empty second hole alone, and 20 against 19
for the bare piece of board — the last on `bare piece of board` exactly, which is the phrase that file's own figure was
taken on.** Three of the four do not agree and one has no figure to agree with, **and no reader should take a figure
in this section from the volume behind this one.** The item numbered 1 above is measured on the wider phrase and gives
26, and both readings are published rather than one being chosen.

**The room was never counted.** No sentence of the fifty gives a headcount of that room. §1.4 above carries the sweep
and the two partial figures a reader will find.

---

## 6. The threads open at day 950, and every debt unpaid

**No standing thread of this manuscript is closed by these fifty days.** Each item names what is owed and the file
that owns it.

1. **The named material of `outline/ending.md` is on no page of this volume.** `state/volume-18-close.md` §6 item 1
   says in the file of record that at nine hundred chapters that is terminal rather than outstanding. **`outline/volume-19.md`
   §19.5 says what this volume pays of it and what it does not, and `outline/ending.md` is not amended by this record and
   is not contradicted by it.** What the fifty bodies pay is measured and named: the seven places worked out on 939, a
   book in each, **no place renamed and no book called a seal**; two books on one bench, one of which does not answer
   to the other; a man asking to be put down in a book with everybody else and the consequence thereafter rendered as
   ordinary behaviour; and one line disputed by a person who was not there and allowed to put his own account of that
   day in the other book. **The Single Witness patch, the Glass Crown's military faction, Northstar Civic's security
   force, the twelve civic seals as objects, the two civilizations as states, and the aftermath for a Crown and a civic
   are outside a manuscript that has one room in it and always has.** **The volume bought an ending's shape and not its
   cast, and no later reader may inherit that as the same thing.**
2. **The seven words of §6.4 come back, and this is a debt the volume paid and not one it opened.** Measured at §2:
   one on each of seven days, zero on the other forty-nine, zero in fifty headings, and no inflected form anywhere.
   **They are ordinary words of this world again and nothing in that room has been done about any of them.**
3. **The two accounts of one day stand and are not settled.** **This close does not settle them and a later volume may
   not adjudicate them without a plan that says so.** §11's own two clauses pull against each other and 0943 holds both
   by stage.
4. **The collision inside `outline/volume-19.md` between §3 and §16 item 14 on the one hand and §6.7 and §6.9 on the
   other.** Three places in the plan against two, already realized on two written pages. **Not decided here.**
5. **The question of day 898** — asked to one man, not answered, unheard, unthanked. **Open.**
6. **The standing questions of days 346, 396, 445, 498, 548, 598, 648, 698, 748, 798 and 848** — eleven — **and the
   family this volume asked on 914, to a different person about a different thing.** Twelve in all, **none answered on
   any of the fifty days, and this record answers none of them.** Measured: the word `witness` on 911 is a cost named
   by a person about herself and is not an answer to the question of day 848.
7. **The consent fracture** — not mended, and nobody mends it. **The fifth condition is not given on any of the fifty
   days.** Milestone ten is paid on 935 as a promise and **paying it is not mending it.**
8. **The two women of twenty-nine** — never in one room, and nothing settles whether they are one woman. **The two men
   of about thirty-eight** — two people, never merged, never settled in narration. **The stallholder of about
   thirty-four, two people in this repository** — never in one room, neither asked about the other, no descriptor
   settling it.
9. **The mark of day 440, the hand that moved it, and the woman of about fifty-four** — not traced, not investigated,
   not guessed at, not reported to a room, **for the twelfth time running.**
10. **The word near the head of the column on the right of the keeper's page** — never printed and never asked about.
11. **The word under the day cut across the head of the second slate** — never printed by any file, and on 908, when
    the slate is lifted and turned over, still not printed and asked about by no mouth.
12. **The bar, the bare board, the second slate, the fence, the rope, the satchel, the tally-board and the trough** —
    unmoved, as §5 sets out. **This close puts the bar back in no socket, writes on no board, picks up no slate,
    measures no fence, moves no post, lifts no rope, opens no satchel and fetches no heat.**
13. **The Bare Month** — not named, not dated, not given a length, and what it does at its end undecided. **Measured
    at §1.3: one hundred and ten occurrences of the three words and not one of them applied to the month.** No ordinal
    is used for a month anywhere in the fifty bodies and no ordinal is converted into a span.
14. **The seven books and where they sleep** — worked out in the dust on a bench on 939, **no book called anything and
    nobody given a title**, measured as `title` and `office` at 0 across the fifty bodies and fifty headings. **The
    keeper rubbed the seventh mark out at the light's going and left six standing, and the seven places did not change.**
15. **The rate at the foot of the stallholder's own board** — wanted and never got on any of the fifty days, and no
    chapter enters a day against it.
16. **The chalk in the inside breast pocket** — never out of it on any of the fifty days, on no surface, with no
    chapter saying when it was last out.
17. **The two shapes in the dust of the sill** — never dated, and no chapter says which hand put the newer one down.
18. **The figure that went into the two-finger space on 924** — not standing there at 947, on no surface, in no column,
    and no chapter of the fifty says who took it or where it went.
19. **The wood inside that space** — never wet, because the cloth stops at the middle column. A small fact and the only
    one the fifty days give about a place that has stood empty about nine years.
20. **The disputer of 943 is the man of about fifty-two who digs, and he is not a new person.** Measured in this run,
    word case-insensitive, whole files, over **all nine hundred and fifty chapter files on disk**: the literal string
    stands at **54 occurrences in 36 files — Volume 04 nine in eight files, Volume 05 thirty in nineteen files,
    Volume 07 seven in four files, Volume 08 seven in four files, and this volume one in one file, 0943.**
    `reviews/volume-19/batch-0005.md` §8 publishes **31 in 17** for the same string; **both figures are given and
    neither is deleted, and the difference is the scope — whole files against that record's, and a volume list that
    does not carry Volume 04.** **And the collision is larger than that record states: Volume 04 carries a *woman* of
    about fifty-two who digs at 7 occurrences in 6 files as well as the man at 9 in 8, so that both of them are on
    pages in one volume and a reader who has not read Volume 04 does not know it.** He and the woman of about
    fifty-two keep a wall in the same room on 943 and on 950. They are a man and a woman, they are distinguished by
    their sex in every sentence of both days, and no mouth asks either about the other. **It is not a prose fix:
    §11 fixes who disputes the line, and changing it would change who the volume's resolution is about.**
21. **The calendar run across the whole manuscript, and one claim of a clean sweep this close could not reproduce.**
    An earlier close found the Bare-Month ordinal wrong by ten days at `chapters/volume-18/chapter-0864.md:5`, **a
    repair pass fixed it before this volume's last batch was written, and `state/chapter-summaries.md` carries the
    correction.** That same file then published **a sweep of all nine hundred and forty chapter files for that class
    of fault returning zero.** **This close re-ran the class and cannot reproduce that as a nine-hundred-and-forty-file
    claim, and the reason is on the same line as the figure: only 96 of the 950 chapter files on disk carry the plan's
    sixth form in the shape *It was <weekday>, the Nth day of the Bare Month*, and on those 96 the weekday and the
    ordinal are correct 96 of 96 with zero faults.** The other 854 open some other way and are outside the sweep's
    scope, **so a reader must not inherit the wider zero from that record as a measured figure over the whole
    manuscript — it is a claim about 96 files wearing the clothes of a claim about 940.** Building the wider
    instrument is owed by a phase that sweeps; this close names the shape and stops. One apparent hit is named so a
    reader does not spend time on it: `chapters/volume-10/chapter-0499.md` opens on the hundred and eighty-third day
    of the Bare Month being wiped off a door and the hundred and eighty-fourth being put on the same door, **which is
    a pair of consecutive days and both of them are right.**
22. **`outline/series.md` carries a Volume 19 entry, and a decisions-of-record block with it.** `outline/volume-19.md`
    §21.4 item 1 says the series file carries no Volume 19 and has no decisions-of-record block for Volume 18 or for
    Volume 19, **and that is no longer true of the file: the entry is there and `reviews/volume-19/batch-0005.md` §9
    records that a repair pass behind that batch added it.** Named here because a reader of the plan next will find
    the plan out of date on its own debt. **And the entry carries a title, `The Line And The Person`, while the plan's
    own first line says no name is put on this volume and that the seven outlines behind it each struck their own.**
    **Which of those two files is right about the title is an owner-level question and this record raises it and
    answers it not.**

### 6.1 The held things, and what this record does with them

**The decision's wording and its cost at §6.6; the panel's wording at §6.8; the three wordings of day 940 at §6.9; and
the name, which is held at `outline/volume-18.md` §6.8 and is reprinted in this record nowhere — not even in the
measurement that counts it.** This record **may measure and publish a count and may not print a span.** It prints
none, paraphrases none, improves on none, describes none closely enough to reconstruct one, and certifies none absent.

**What was measured, and the count only, with the instrument and scope on the same line. Every figure below was
produced in the run that wrote this record, on the files as they stand at the end of that run, and no instrument used
here lives outside this repository.**

| Held thing | Count | Reading, instrument and scope on the same line |
|---|---|---|
| §6.6's decision wording | **1 in the fifty bodies, 0 in the fifty headings; and on 2 of the 1,511 tracked files — the plan and the page that carries it** | the span extracted from §6.6 at run time, matched literally against whitespace-collapsed text; 44 characters, and **the length is the length the plan's own subsection publishes.** No state file, no batch record, no review record, no prompt and no summary carries it |
| §6.6's cost of that decision | **0 in the fifty bodies, 0 in the fifty headings, and on 1 tracked file — the plan** | same instrument, 207 characters. **And at clause level as well, because a paraphrase of a clause is a print of the string in everything but the letters: three clause-length spans of 98, 47 and 54 characters return 0, 0 and 0** |
| §6.8's panel wording | **1 in the fifty bodies, 0 in the fifty headings; and on 2 tracked files — the plan and the page that carries it** | same instrument, 268 characters, **and at its three line-lengths of 106, 112 and 48 characters, one occurrence each.** §4 above |
| §6.9's three wordings of day 940 | **1 each in the fifty bodies, 0 in the fifty headings; each on 2 tracked files — the plan and the page that carries it** | same instrument, at 50, 39 and 46 characters. **The three are the cost named first, the one thing said once, and the same thing said back in another woman's words, and each appears on its own day and nowhere else in the fifty** |
| §7.2's figure for the day a piece of chalk was last out of a pocket | **0 in the fifty bodies, 0 in the fifty headings; 1 in `outline/volume-19.md` and 1 in `outline/volume-18.md`; and the bare day-figure alone stands once in `state/continuity.md` and twice in `state/character-state.md`** | the span extracted from §7.2 at run time, 67 characters, and the figure alone, 34 characters; literal match, scope the fifty bodies, the fifty headings and thirteen named files. **This is the third time this figure has been measured and it is the same figure each time: zero in the fiction, three in the state layer, and all three in pre-existing text this volume's writers did not write** |
| §6.8's name | **1 in the fifty bodies, 0 in the fifty headings; and on 19 tracked files — the plan and eighteen chapter pages: seventeen in Volume 18 from 0879 to 0899 and one in Volume 19 at 0918** | literal pair match over the tracked set. **The Volume 18 figure this returns is 35 occurrences in 17 files, which is the figure `outline/volume-19.md` §19.3 publishes for it, so the instrument is known to be measuring the same quantity that plan measured.** **In this volume the name is on exactly one page, once, in one hand, in the column that holds figures; it is on no board, on no slate, in no register, on no piece of chalk, on the bare board, in no heading, in no state file, in no batch record, in no review record, in no prompt and in no summary** |

**AND THE ONE THING THIS RECORD CANNOT INSTRUMENT, NAMED AS WHAT IT IS.** **No honest instrument for §6.8's name can
be built without printing it, so this record does not certify an absence for it from first principles and does not
claim to.** What it publishes instead, in the row above, is a literal scan over the tracked set run on the pair at
run time and never printed — and that is what it publishes, and the pair is not printed here either.

**AND THE INSTRUMENT THAT STANDS IN ITS PLACE, MEASURED IN THIS RUN, is the one `reviews/volume-19/batch-0005.md` §8
set out and this run re-derives over the fifty rather than the ten:** a capitalised-token scan of the fifty bodies and
the fifty headings against an allowed list of the names this volume prints in speech, the seven weekday names, the
Bare Month and ordinary sentence-initial capitals. **Non-sentence-initial capitalised tokens in the fifty bodies are
`Tamsin` and `Quill` on 935 and `Adrian` and `Vale` on the eleven days he is in, and nothing else that is not an
ordinary capitalised English word.** The pair's own literal count over the fifty bodies is 1 and over the fifty
headings is 0.

**And the eighth debt in this repository is a close record that asserted an absence and was wrong.** `state/volume-18-close.md`
§6.1 names it at the end of its own table, in the volume behind this one. **It is named here and not reported on, and
every row above was produced in the run that wrote them.**

---

## 7. What this record re-ran, and what it took rather than re-derived

**The five batch records of this volume were treated as starting points and not as truth. Every instrument they
publish was re-run in this close's own run, over the fifty files where the scope allowed it, and both numbers are
published wherever the two exist.**

### 7.1 The last ten days, against `reviews/volume-19/batch-0005.md` §11.4

| Figure for chapters 0941 to 0950 | §11.4, after that repair pass | Re-run in this close | Reading and scope on both sides |
|---|---|---|---|
| Words per body | 1382, 1255, 1705, 1017, 1047, 1259, 1231, 1137, 880, 1163 | **the same ten** | whitespace `split()`, ten bodies, heading line out. Total **12,076**, mean **1,207.6**, shortest 880 at 0949, longest 1,705 at 0943, spread **825** — the two agree exactly |
| Longest shared run between two bodies | 17 | **the same ten** | same definition: longest common **contiguous** token subsequence, letters-only tokenising, hyphen and apostrophe as boundaries, forty-five pairs. §11.4 names the run as a §5 standing object and not prose |
| Longest shared run between two closings | 6 | **the same ten** | same definition, ten closings, forty-five pairs |
| Repeated sentences of 38+ characters | 0 | **the same ten** | every sentence of 38 or more characters, whitespace collapsed, each paragraph split on its own, into one multiset |
| Speech paragraphs / bold marks / quotation marks | 12 / 24 / 24 | **the same ten** | same scope |
| Chapter = day, weekday, ordinal | 10 of 10 | **10 of 10, and the weekday and ordinal rows re-derived from the two figures and not from the plan's table** | §1.1 |

**The four figures in that batch record's §2 that §11.4 supersedes — the per-file word counts, the paragraph count,
the 68-to-73 eight-word figure and the 21-token shared run — were not compared against, and this close does not quote
them.** The paragraph row is the one that does not resolve: §2 published 113, that record's own instrument returned 96
and §11.4 returned 97, and **this close's own instrument over the same ten files returns 97**, which agrees with
§11.4 and leaves the other two figures standing as figures two instruments disagree about. **All three are published
and none is deleted.**

### 7.2 The whole volume, against the five records

| Figure | What each of the five records published | What this close measured | Reading and scope |
|---|---|---|---|
| Words per batch | 0001: 10,525 / mean 1052.5. 0002: 11,383 / mean 1138.3 on the rules-in reading. 0004: 11,388 / mean 1138.8. 0005 §11.4: 12,076 / mean 1207.6. **0003 publishes no total-words row and no paragraphs row** | **10,525 / 1,052.5; 11,383 / 1,138.3; 9,005 / 900.5; 11,388 / 1,138.8; 12,076 / 1,207.6. Total 54,377, mean 1,087.5** | whitespace tokens, heading line out, each ten bodies. **Four of the five reproduce their record's own figure exactly on the same instrument, and the fifth stands on this close's measurement alone because the record behind it publishes none.** The volume's mean sits 203 words a chapter above Volume 18's published 885, and §17.4 says the mean is a consequence and not a plan, so no chapter here was lengthened to a number |
| The spread of chapter length | 0005 §11.4: **825** for its ten days and it names the cause | **935 across the fifty**, shortest 770 at 0929 and longest 1,705 at 0943 | same instrument, scope fifty. **The one figure in this section that reads worst for the volume and is published because §17.22 requires it.** The cause is structural: 0943 is the resolution and has to hold a dispute, a reading and a second account in one scene, and 0929 is the day the panel is on the wall and the tradesman spends it with his hand on the plaster |
| The seven words | each of the five records measured its own ten against its own days | **one on each of seven days, zero on the other forty-nine bodies, zero in fifty headings, no inflected form anywhere** | §2. **Every batch record's own figure is consistent with this one and none of them is quoted as authority for it** |
| The panel | 0001: 0 in its ten. 0002: 0 in its ten. 0003: **1, on 0929**, 268 characters. 0004 and 0005: 0 | **1, on 0929, 268 characters** | same instrument, scope fifty. **0003's figure is the one that holds and it is reproduced exactly** |
| `at any hour of that day` | 0005 §11.2: **9 before its repair and 0 after, in its ten days** | **24 across the fifty, in 19 files; `at any hour` at 59 in 33 files** | literal, both case flags, scope fifty bodies. **This is the volume-wide figure and it is the one that reads worst: the negation formula the last batch cut out of its ten days stands twenty-four times in the forty days before them, and a later writer who inherits only §11.4 will believe the volume does not have it. That is why this row is here** |
| `his own` | 0005 §11.4: **117 across its ten days**, one in every 103 words | **441 across the fifty** | literal, scope fifty bodies, out of 54,377 words — one in every 123. **This is the volume's possessive style and §17.9 is part of the cause, and no figure here is set out to be driven lower** |
| Longest repeated window inside one body | 0002 named the ten-word descriptor handle and 0005 §11.4 published **11** for its ten days | **the maximum across the fifty is 18, at 0947**, and **the single commonest cause is a §17.9 descriptor handle** | for each body, the longest window of tokens occurring at least twice inside it; 8-token windows and upward, letters-only tokenising. **Thirty-two of the fifty bodies return a window of 12 tokens or more, and the bucket each one falls in is measured and printed here rather than left to be inferred: the stallholder's handle in 15 bodies, the carrier's in 5, the tradesman's in 2, the keeper's in 1, the wharf-man's in 4, a §5 standing object in 6, and neither a handle nor a standing object in 3** — 0911, 0922 and 934, and **assigning those three to a bucket is a reading and this record does not make it over fifty bodies.** **The floor on the other twenty-nine is set by `outline/volume-19.md` §17.9, which requires a person's descriptor in full on first appearance in a chapter, and it is the plan's and not carelessness** |
| Distinct eight-word windows standing in three or more bodies | 0005 §11.4: **58** across its ten, on the per-file-deduplicated reading, and **70** on the occurrences reading | **1,110 distinct windows in three or more of the fifty bodies, and 1,143 distinct windows occurring three or more times in total** | §11.1's two readings exactly, scope fifty bodies. **These are not comparable to a ten-day figure and are not scored against one: a fifty-body set has roughly five times the pairs a ten-body set has, and a volume-wide count of this kind is published as a shape and not as a grade. The bucket that matters is the third one §11.4 names — windows that are neither a required handle nor a standing object — and **assigning a window to that bucket is a reading, not a measurement, and this record does not make the assignment over fifty bodies** |

### 7.3 The three figures in this section that read worst for the volume, gathered

**The volume's own mean and spread, the negation formula standing twenty-four times in the forty days before the last
ten, and the 1,110-window figure with no bucket assigned to it.** None of the three is a breach of a rule this volume
breaks; all three are published because `outline/volume-19.md` §17.22 requires it and because a close that published
only the figures that read well would be the failure §17.11 names.

---

## 8. The count §17.16 and §17.17 ask for, across the fifty days and not across one batch

**Both of these are readings and not measurements, so the reading is stated first and every competing figure is
published beside it. Instrument for the whole section: the fifty closing paragraphs extracted as the last block of
each file that is not a `---` rule, read side by side against the body of the same file; the window is a sliding
window of ten consecutive chapters across the fifty, both directions.**

| Reading | Count | The chapters | Worst window of any ten | Cases an outside reader could argue the other way |
|---|---|---|---|---|
| **R1 — this close's stated reading.** A closing counts as a statement that nothing changed when its movement is an absence or a persistence and **no** fresh mark, drying, shift, arrival, sinking, scraping, filling or movement of water, light or air is stated in words different from the body's | **0 in 50 on the rule as written** | none | **0** | **Four closings are arguable and all four are given: 0946 closes on water standing in two hollows *exactly as it had stood in them before he came*, which is the closest thing in the fifty to a statement that nothing changed; 0927 closes on a door opened twice and coming back the way it comes back; 0945 closes on a satchel standing where he had put it down, with the change named being a curled flap; and 0930 closes on three people leaving things standing where they stood.** A reader who admits all four gets a worst window of **2**, at 0927 to 0936, which is at §17.16's ceiling of two in any ten and not over it |
| **R2 — the wider reading, R1 plus the two that a reader could argue hardest for**, being 0946 and 0930 | **2 in 50** | 0930, 0946 | **1**, in every ten-window that holds either of them and in none that holds both | **This row sits at the ceiling and not over it: a count of two in fifty, and a worst window of one because 0930 and 0946 are seventeen days apart and no ten-day window holds both.** The volume behind this one published a wider reading whose worst window was three and put that row in the headline rather than in a footnote; **the equivalent row here is R1 plus 0946 and 0930, and the honest statement is that on the reading this close states the count is nil and on the reading that admits the two hardest cases it is two in fifty with a worst window of one** |

**The other two checks on the fifty closings, both run here:**

- **No two chapters close on the same construction.** **This record does not certify that, because it cannot.** §17.17's
  rule is about construction and construction is a reading, and §17.22 was written because a record once published one.
  What is measured and published is the **longest run of contiguous tokens shared by any two of the fifty closings:
  15, between 0908 and 0918**, and the run is printed with the figure so that the number can be checked against the
  words — **it is *about the tenth hour the woman of about twenty-nine who keeps a public register*, which is §17.9's
  descriptor handle plus an hour and not a construction.** The three pairs behind it are 0912 with 0919 on the
  carrier's handle at 12 tokens, 0909 with 0928 on a §5 standing object at 12, and 0911 with 0918 on the keeper's
  handle at 11. **Every pair that reaches ten tokens or more is a handle or a standing object, and the formula for
  the light going appears in no pair of the fifty's closings at ten tokens or more.**
- **The seven closing shapes §17.17 puts off limits for this volume's own batches.** Measured across the fifty
  closings: **none closes on the room's figure, none on the census, none on the strip of ground, none on the bar,
  none on the sockets, and none on a page that says a number.** **And none closes on a name in a column, on the space
  on that board, or on a wet sleeve** — the seventh shape, and the three it names, added in this volume. **One closing
  names a mark on the bare piece of board, at 0950, and that is the volume's last image and not a closing on the bar
  or the sockets.**

---

## 9. What is left, and it is a human's, and this record does not do it

Each item names the file and, where the plan gives one, the section. **None of them was opened, edited, created or
removed by this close beyond being named here.**

- **The debts at `outline/volume-19.md` §21.4**, none of them repaired and none of them this record's:
  1. **`outline/volume-05.md` does not exist** and covers fifty chapters that are on disk. **`outline/volume-03.md` does
     not exist either** and its five beats stand unaudited. Named, not created.
  2. **The collision inside the plan**, item 4 of §6 above. Three places against two, realized on two pages, and not
     decided here.
  3. **The pull inside §11**, item 3 of §3.1 above. Held by 0943 by stage and explained by nothing.
  4. **`§7.2`'s figure for the day a piece of chalk was last out of a pocket**, which this volume's calendar cannot
     support, measured at 0 across the fifty bodies at §6.1 and carried forward as a figure no chapter may print.
  5. **`bible/power-system.md` has no §65 for days 851 to 900 and no §66 for days 901 to 950.** Every volume's calendar
     has been registered in that file as a new numbered section since §51, and the fifty rows for days 901 to 950 are
     at §14.3 of the plan with the derivation at §1.2 above. **Owed by a phase whose writable set includes `bible/`
     and by nobody else.** The two figures it would need are day 901 a Saturday at Bare-Month 586 and day 950 a
     Saturday at Bare-Month 635, and this record has measured both.
  6. **`NOVEL_SPEC.md`'s Status section is stale and contradicts itself.** Lines 20 to 25 claim fifteen volumes and
     750 chapters and lines 42 to 45 of the same file claim that figure was corrected. **The true figures are
     nineteen volumes and nine hundred and fifty chapters, every volume complete, and this record measured the
     nine hundred and fifty.** Named, not touched: it is a specification file and not one of the fiction, bible,
     outline, chapter, summary, continuity, character or open-thread files a phase is given.
  7. **`outline/volume-19.md` §21.4 item 1 is out of date about `outline/series.md`, in two ways, and the plan is a
     file a planning phase owns and this record is not.** Measured in this run: the series file **does** carry a
     `### Volume 19` heading and **39 occurrences of the phrase *decisions of record* across the file**, and
     `reviews/volume-19/batch-0005.md` §9 records that a repair pass behind that batch added the Volume 19 entry.
     **And the entry carries a volume-list title while the plan's own first line says no name is put on this volume.**
     Both are named at §6 item 22. Named, not touched.
  8. **`state/phase-ledger.json` still reads `phase-000-bootstrap`, `status: planned`, `attempts: 0`** after nineteen
     closed volumes and nine hundred and fifty chapters. **It is a controller file and this record neither opened nor
     wrote it, and a close may do neither.**
  9. **`reviews/volume-16/` does not exist**, and the review dispatch falls back to the writing agent because
     `novel-reviewer` is registered as a subagent. **Every finding ever taken over this manuscript has therefore been
     taken by the agent kind that wrote the pages, and that is true of this record.** Named, not repaired; the fix is
     in workflow dispatch.
  10. **The three deferral markers left in `workspace/volume-19/batch-0003/`** on a finished phase, and
     **`workspace/volume-19/batch-0002/` is absent** where 0001, 0003, 0004, 0005 and close all exist. **Both are
     dispatch history and this record created, edited, deleted and forged none of them.** A directory for a phase that
     finished must stay as it is, and a marker file is the runner's to write.
- **The named material of `outline/ending.md`, and the owner-level decision behind it.** `state/volume-18-close.md` §6
  item 1 calls it terminal rather than outstanding at nine hundred chapters, and `outline/volume-19.md` §21.4 answers
  the close's question by re-outlining the last volume rather than by amending the ending. **This volume paid what
  §19.5 says it pays and did not pay the rest, and §19.5 is where a reader must go for the list.** This record makes
  neither decision and is not permitted to.
- **The writing debt the batch behind this one added and did not fix.** The ten chapters of days 941 to 950 share a
  room-description paragraph, because §5 puts that room on every page of the volume, and the first draft of that batch
  carried three of those sentences across three files verbatim; it was measured at 42 tokens of shared run and three
  repeated sentences of 38 characters or more and was cut. **A card file for a batch that fixes the standing objects of
  a room carries that debt with it, and a later volume's writer should be handed the before-and-after figures rather
  than told by silence that the fault is gone.** This close publishes the volume-wide figure so that the next writer
  has a number to beat: **11 repeated sentences of 38 characters or more across the fifty bodies out of 1,426 such
  sentences, and 1,413 distinct.** **Five of the eleven carry a §17.9 descriptor handle or one of the plan's standing
  states**, and assigning a sentence to either bucket is a reading and is named as one; **the six that are neither are
  two instances of the negation formula, two sentences of a morning going on, and two ordinary sentences about a leaf
  being turned and a thing said into the middle of a floor.** Two of the eleven stand three times each and the two are
  *Nothing whatever was done about it at any hour of that day* and *She said it once and she did not say it again at
  any hour of that day* — **and six of the negation formula's twenty-four stand in those two sentences**, eight of its
  fifty-nine stand inside the eleven repeated sentences, and §7.3 carries both figures.

**AND THERE IS NO NEXT PHASE AFTER THIS ONE THAT THIS RECORD PROMPTS.** Volume 19 is complete at fifty chapters and
nine hundred and fifty days and `outline/volume-19.md` §22 named `workspace/volume-19/close/` as the last of its
phases. **A close does not dispatch. This record writes no prompt, no card file, no ledger entry and no marker; it
creates no directory beyond none; it edited no chapter, no batch record, no review record, no archive, no prompt, no
plan and no bible; it opened no controller file; and it created and removed no `.done`, `.checkpoint`, `.blocked` or
`.retired` file.** What it wrote is this file, and this file writes no fiction.

---

## 10. The five things a reader in a year must not inherit as settled, gathered in one place

1. **The volume bought an ending's shape and not its cast.** Seven places with a book in each; two books, one of
   which does not answer to the other; a man put down in a book with everybody else; one line disputed by a person who
   was not there. **Not the patch, not the Crown's faction, not the civic's security force, not the twelve seals as
   objects, not the two civilizations as states, and not an aftermath.** §19.5 is where that list is.
2. **The two entries of one day stand in two books in one room and nothing in this volume adjudicated them.** They
   were still standing at the light's going on 950, both books open, neither shut, and nobody in that room compared one
   leaf with the other. **A later volume may not settle them without a plan that says so, and this close could not and
   did not.**
3. **The bare piece of board meant nothing whatever on forty-nine of the fifty days, and what is on it on the fiftieth
   is not a day of any month this manuscript has named.** One mark, in the hand of the woman of about fifty-two, and
   no chapter says what it is for and this record does not either.
4. **The seven books and where they sleep were worked out in the dust on the top of a bench on 939, and no book was
   called anything and nobody was given a title.** Seven marks, one of them rubbed out at the light's going, six left
   standing, and the seven places did not change.
5. **The three words nobody is told are still not told.** One hundred and ten occurrences of them across the fifty
   bodies and not one of the hundred and ten is about the month. **What the Bare Month is called, how many days it has
   and whether it is long or short are not on a page of this volume and are not on this one.**

---

**Fifty chapters, fifty days, two Saturdays forty-nine days apart, seven words one on each of seven mornings and
nowhere else, three entries in two books, one disputed line standing, one mark under a date, and a bar on a top step
that came out of its sockets before this volume began and was not put back on any of its fifty mornings.**

**Nothing above is settled that the plan did not fix, and nothing above is a chapter.**
