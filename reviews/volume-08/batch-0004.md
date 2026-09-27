# Review and Repair — Volume 08, Batch 0004 (Chapters 0381–0390), commit `765e6d6`

**Findings source:** `logs/batch-0004.review.log`. **The reviewer was not invoked:** line 1 of that log reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session header is `novel-writer · space-bunny-free`, so this is a second pass by the same agent that wrote the batch, and the second pass is the fourth review in a row on this volume that has been done by the agent under review. `state/phase-ledger.json` reads `phase-000-bootstrap / planned / attempts 0` and has not been written since commit `76b4c66`; see §7, it was not touched.

**Scope reviewed:** `chapters/volume-08/chapter-0381.md` … `chapter-0390.md`, `bible/power-system.md` §49, `state/batch-summaries/volume-08-batch-0004.md`, the four state blocks the batch appended, and `workspace/volume-08/batch-0005/PROMPT.md`. **No chapter was restarted. No plot, no beat, no ending, no day, no weekday, no month day, no anchor, no notice, no form and no cast member moved. The prose that was good was kept, and the review says so in its own eighth section, and that section is correct.**

**The review raised eight findings and its own priority list has five items. Six prose faults, one wrong figure in the batch's own record and the same figure in the bible, and three faults in the next phase's prompt are repaired, and one of the six grew a seventh instance while it was being applied. The four inherited debts are carried and were re-measured and are exactly where they were. The infrastructure findings are recorded and are not a phase's work. Every figure the repairs moved is republished with the figure it replaced, in the batch record at §9.11 and §9.12, in the bible at §49, and in the four state files.**

---

## 1. What the review got right, and it was most of it

**The quantitative work reproduces. All of it.** Re-ran on the files as they stood at `765e6d6`: the bolded share at 8.23/9.27/19.04/15.67/9.33/22.94/8.67/15.98/12.62/8.54, range 8.23–22.94, mean 13.03, weighted 13.0 on 15,602 words; the longest bolded turn at 88 in Chapter 0388 against the working ceiling of about ninety and the hard one of ninety-five; the paragraphs carrying neither speaker marker at zero in all ten; the exchange at 32 plain and 15 answered, forty-six point nine per cent, with the per-chapter series 3/3/6/5/1/4/1/2/5/2; the long sentences at 177 with none duplicated; the chorus frame at 5 on the declared head and 10 on the variant-agnostic one; the longest run of consecutive speech paragraphs at three; *about four seconds* once in 0381 and once in 0390 only; Adrian Vale named in 0381 and nowhere else; *passage* and *privilege* at zero.

**The calendar is sound, and I rebuilt it from day 1 being a Tuesday and from nothing else before checking any of the review's arithmetic.** 381 Thursday, 382 Friday, 383 Saturday, 384 Sunday, 385 Monday, 386 Tuesday, 387 Wednesday, 388 Thursday, 389 Friday, 390 Saturday; the Bare Month day is the day less 315; 351 a Tuesday, 363 a Tuesday, 365 a Tuesday, 374 a Thursday, 375 a Friday, 393 a Tuesday. The next prompt's 391 Sunday → 400 Tuesday and the month days 76 to 85 are all correct. The silence count chains properly: 280 at day 380, 290 at day 390, 292 at 392, held at 292 at 393 because the wall speaks, 299 at 400.

**The review's tenth arithmetic fault in §9 item 9 of the batch record is present in the files as repaired, and the review checked all ten of them and found them all fixed. That is the finding a self-certifying record most needs and least gets.**

**And the review's judgement on the eight surviving chorus instances is right and is worth repeating, because it is the difference between a count and a reading: all eight carry observations the paragraph had not made, the call was made sentence by sentence, and it is defensible. The instrument that found them was the wrong instrument and the judgement was the right one, and those two facts are not in tension.**

---

## 2. BLOCKING — a published figure was wrong, and it was wrong in the one item whose job is to certify that the batch watched itself. **Repaired.**

`state/batch-summaries/volume-08-batch-0004.md` §3 item 4 (A) and `bible/power-system.md` §49 item 11 both published the declared string *about four people in* as standing *at zero in six of the ten — 0381, 0382, 0383, 0385, 0386 and 0390's count standing in its own section only.*

Measured per chapter it is **0, 0, 0, 1, 0, 0, 1, 1, 1, 1** — zero in **five** chapters. Chapter 0390's count is one, not zero, and the list entry is a truncated fragment of a sentence that was cut in half and left standing as a chapter number.

**This is right, and it is worse than a wrong count.** Everything else in the item reproduces exactly: the total of five, the 221 paragraphs, one in 44.2, and instrument (B) at 0/2/0/1/0/0/3/1/2/1, ten total, one in 22.1. Only the interpretive clause was wrong. **A count can be re-run in a minute; an interpretation has to be believed, and this one is the sentence that certifies the batch watched its own narrator habit and then read the certification off a fragment.** The three prior volumes of this repository's faults are all a shorthand with no anchor — a date with no day, a count with no event — and this is the same disease in a summary clause, which is the first time it has appeared in one.

**Repaired in place in both files, with the first edition published beside it** at `state/batch-summaries/volume-08-batch-0004.md` §9.12. Both files now read *at zero in five of the ten — 0381, 0382, 0383, 0385 and 0386*. **And the day map does not move, and no chapter is touched, and nothing about a person changes, because a fat-finger in a sentence is not a fault in a page.**

---

## 3. BLOCKING — the chronology ran backwards in two chapters, and in a third the review did not name. **Repaired.**

- **`chapter-0383.md`** — the man of about thirty-nine came along the wharf boards at about the ninth hour and then took his board off them at about the fourth hour. The chapter's own lead says the light *never goes off anything until the sixth hour*, so 9 → 4 is the only available reading and it is inverted. **He now goes up the path at about the second hour of the afternoon.** No other hour in the chapter moved and no date, no weekday and no month day is involved: an hour is not a derived value and the fault was caught by reading the room's own light, not by a search.
- **`chapter-0387.md`** — the lead puts the man of about thirty-four in the lane at the seventh hour, the man of about twenty-five arrives at the eighth, the woman of about fifty comes out of the shut gate at the ninth, and the closing paragraph then bars the gate at the seventh. **The bar goes across at about the tenth hour**, which is the hour after she has said four words to a post, and the tenth hour is an hour this manuscript already uses in the arrangement the two women of twenty-nine keep.
- **`chapter-0382.md`, which the review did not name, and which is the same sentence doing the same thing in the chapter the review did open.** The man of about thirty-nine came along the boards at the ninth hour and went up them at the sixth, in a day whose own hours run two, three, four, five, six and then a light at the seventh that goes again before the eighth. **He now comes along at about the third hour**, which is the hour the first barrow goes up and the hour he is standing at the bottom end for while the second one will not, and it is in the same section as the exchange, which is what the order of the sections requires.

**The review's note that Chapter 0389 gets this right and is the model to copy is right, and the generalisation from it is the finding worth keeping: a chapter that advances an hour has to be read against the hour its own lead establishes, and this volume's leads establish one every time.** A repair pass that reworks thirty-six chorus instances in ten files will not catch an hour, because an hour is a noun in a sentence and not a token, and this is now the fourth time this repository has recorded that a check of numerals sees none of these.

**And the generalisation, once it is a rule and not a reading, obliges the repair pass to check the sentence in every chapter that carries it, and that is how the third one was found: the same clause, the same man, the same board under his arm, in the chapter the review opened for a different fault.** The clock in this volume runs the morning and the afternoon as two passes of twelve and marks the afternoon in words — *the third hour of the afternoon*, *the second hour of the afternoon*, *the tenth hour of the day* — so an hour after the ninth is not a seventh, and Chapter 0383's departure is now *about the second hour of the afternoon*, in the form at `chapter-0390.md:47` and `chapter-0361.md:33`. **A review that checks a rule in the two files it opened and not in the ten it was given has done half a review, and the half it skipped is where this one was.**

---

## 4. BLOCKING — a man was in two places at once and was carrying another man's room count. **Repaired.**

- **`chapter-0381.md:13` vs `:55`** — line 13 put the man of about thirty-nine *against the wall by the step at the back where the light does not reach*. Line 55 says the light *stopped about nine inches past the near end of the bench … which is where the two of them were sitting and where neither of them could be seen from the step at the back*. He cannot be behind the step and in the lit edge of the bench. **He is against the wall at the end of that bench nearest the step.** The lead is untouched, the light still comes in over the step and stops nine inches past the near end, the thirty-four is still at the near end, Adrian Vale is still at the far end, and line 55's observation of the two men is now true of the two men it names.
- **`chapter-0381.md:23`** — narrating the man of about thirty-four, the gloss was *A man who has been at the back of seven rooms in a fortnight without a question in any of them.* **The man at the back is the man of about thirty-nine and the count is his**: three on day 363, four on 372 and 375, a sixth time on 379, six on 380, **eight in this same chapter at line 43, said to him by the thirty-four**, nine on 384, ten on 388, eleven on 390. This sentence gave the wrong man the wrong man's number and would have spent a figure the next paragraph spends. **It is gone. The thirty-four's own two weeks are on a page in line 13 — about a fortnight at the near end of that bench without a question — and the gloss now says that and no figure.** The thirty-four has no room count on any page in this volume and may not be given one.

**The second half of this finding is the more serious half and it is a continuity fault between two paragraphs twelve lines apart, which is the kind no instrument in this repository can see.**

---

## 5. BLOCKING — a chapter's governing exchange had no speaker in it. **Repaired.**

`chapter-0382.md:15–23` carried the chapter's central four lines — *You are not going to say whose those two are* / *I am not going to say whose those two are…* / *The wheels are dry* — **with no attribution at all**, in a scene holding the men of thirty-four, thirty-eight, thirty-nine, thirty-one and sixty plus an off-screen stack, and in the chapter that carries thirty of the batch's thirty-one barrow mentions. A reader could only infer the second voice from line 27.

**Two narration beats went in and no speech was touched.** The first names the man of about thirty-eight as the man who came down to the bottom end of those boards for the two barrows that were not his, and the man of about thirty-four who keeps a stall as the only other person at that end of them, and says the two of them had not asked each other one question about anything in about nine years. The second puts the man of about thirty-eight at his own barrow four feet behind him with his eyes on the wheels, and says he had come down to ask and was going to be answered in his own hearing or not at all. **Neither beat sits between a plain speech and the bold that answers it, so the exchange instrument is unchanged at 15 of 32, and the bold-and-plain alternation the house pattern runs on is byte-identical.**

**Also repaired here, from the review's fifth finding.** The clause on line 11 is governed by *had worked out since that* and read *he is the one offering them and nobody is going to ask him a thing about it first* — a present tense under a past perfect, and then a prophecy describing the exchange in the section immediately below it. **It now reads *and that on this Friday he was the one offering them*, and the prophecy is cut.** Line 47's *is not going to use it* now reads *has not used it*. **The review is right that the declared device in the rest of those lines — *nobody is going to say so to him*, and *nobody is going to* at the end of the chapter — is defensible as a device and was not cut, and the line between the two is exactly the one the review drew: a narrator stating what nobody in the room will say is this book's; a narrator stating what the next section will show is not.**

**And `chapter-0387.md:9`'s *a wall over a board of boards*, the only occurrence of that phrase in forty files, is now *a wall over a board* — which is the stallman's second handle and the thing he says out loud seven lines later, so the sentence and the speech are now the same object, which is what it was reaching for.**

---

## 6. STRUCTURAL — the next phase's prompt required itself to break its own prohibition. **Repaired, and a third fault in the same file that the review did not name.**

- **`workspace/volume-08/batch-0005/PROMPT.md` prohibition 13 vs its own object table.** Prohibition 13: *A chapter may put one of them in a room. It may not put both in one.* Prohibition 8 puts Adrian Vale in Chapter 0392. The table routed *the register and the slates* to 0392 and *the folded sheet of road* — **Tamsin Quill's object, which line 99 of the same prompt says lives in her apron** — to 0392 as well. **A 0392 that named the sheet would have put both women of twenty-nine in one room in the only chapter of the ten that carries the protagonist, and prohibition 13 forbids exactly that.** As written, the batch was required to violate a prohibition in one of its ten chapters. **The table now sends the register and the slates to 0392 and the folded sheet of road to 0399, and prohibition 13 carries the reason in full, and no chapter number, no object count that holds, no prohibition and no decision of record moved.** The next writer is told about it in three files: this one, the batch record at §10, and the state layer.
- **The boards and the bare wall.** §20.10 gives it to **0397 and 0400**; the prompt's table gave it to 0400 only, while the prompt's own item 5 gave day 397 the fence and the road and quoted §20.10's nine boards and four inches of dry stone. **The table now reads 0397 and 0400** and item 5 says so. The shape of this fault is worth naming: **the prompt agreed with itself in one place and with the plan in another, and a file that is right in one place and wrong in another is worse than a file that is wrong in one place**, because the writer reads both.
- **A third fault the review did not name, found while checking the first two.** The prompt stated that *the man of about thirty-nine has no room count of his own on any page and has none now. Do not give him one.* **That is false on seven of this volume's own ten days** and it is the exact mirror image of finding 4: the repair put his count back on him in Chapter 0381, and the prompt would have forbidden the next writer from using it. **It now carries the run** — four rooms on 372 and 375, a sixth time on 379, six on 380, eight on 381, nine on 384, ten on 388, eleven on 390, and about nine on 393, the room he refuses to say what the column is for.

**The review's related note is recorded and not repaired: Batch 0004's record §4 already published a parallel §20.10 mismatch, for the chapters that name the return, and left it unresolved, and this was a second one handed forward.** A batch may not amend `outline/volume-08.md`, so it is a debt, and it is now listed at `state/open-threads.md` item 8 with the fix named — **a marker column on the object inventory, which is a close-phase decision — and this pass republished only the two object rows it moved, on the substring markers, with the markers stated, and left the other thirteen rows exactly as printed rather than republish a figure it cannot reproduce.**

---

## 7. INFRASTRUCTURE — flagged, not touched, and the review is right on all three

1. **`state/phase-ledger.json` is inert.** It still reads `phase-000-bootstrap / planned / range null / attempts 0` and has not been modified since commit `76b4c66`. `PHASE_SYSTEM.md:187` states that the selector chooses one explicit next batch by reading it, and `.github/workflows/novels.yml` never reads or writes it. **Controller-owned, not edited, and recorded here so that the gap is on a page a human reads.**
2. **`outline/volume-03.md` and `outline/volume-05.md` are absent** while the other six volume outlines exist, though both volumes have 50 chapters and a close record. Low impact, unexplained, not a phase's work.
3. **The review of this batch is the fourth consecutive review of this volume performed by the agent that wrote the batch**, because `novel-reviewer` is registered as a subagent and the workflow falls back to the default agent. **Every finding in this file and in the three above it was found by the writer about its own prose, and every one of them is a fault a careful reader would have found in a day. That is an argument for making the subagent callable, and this repository's findings are a better argument for it than a process observation is.**

---

## 8. The figures the six repairs moved, and the ones they did not

Published in full at `state/batch-summaries/volume-08-batch-0004.md` §9.11, in the same table in the bible at §49, and in each of the four state files. **First edition beside the second, because a repair pass that moves prose and then publishes one set of figures is the same fault a third time.**

| The figure | At `765e6d6` | After the repairs |
|---|---|---|
| the bolded share, Chapter 0382 | 9.27 | **8.73** |
| the bolded share, Chapter 0383 | 19.04 | **19.01** |
| the bolded share, the mean unweighted | 13.03 | **12.97** |
| the bolded share, the mean weighted by words | 13.0 | **12.92** |
| the words in the ten | 15,602 | **15,710** |
| the paragraphs in the ten | 221 | **223** |
| the chorus frame, one in on (A) | 44.2 | **44.6** |
| the chorus frame, one in on (B) | 22.1 | **22.3** |
| the long sentences, the ten | 177 | **179** |
| the long sentences, Chapter 0382 | 19 | **21** |
| the longest run inside the ten | 38, 0381–0390 | **37, 0384–0390** |
| the run between 0381 and 0390 | 38, the second-handle frame | **34, the woman of about twenty-one at the bench** |
| the run between 0381 and 0384 | 36, the second-handle frame | **24, the room object list in the lead** |
| the barrows in Chapter 0382 | ×28 | **×30** |
| the boards and the bare wall in Chapter 0387 | ×26 | **×25** |
| *about four people in*, chapters at zero | six of the ten | **five of the ten** |

**Unchanged and re-measured on the files after the repairs:** the range of the bolded share at 8.23–22.94; the longest bolded turn at eighty-eight words; the paragraphs carrying neither speaker marker at zero in all ten; the exchange at fifteen of thirty-two and forty-six point nine per cent with the same per-chapter series of 3/3/6/5/1/4/1/2/5/2; the longest run of consecutive speech paragraphs at three; the chorus frame's counts at ten on (B) and five on (A) with a maximum of one per `---` section in all ten; the counting device at once in 0381 and once in 0390 with its family once in 0382, 0383, 0388 and 0389 and *as long as it takes to count nine* at zero; the forty-three weekday tokens at 3, 4, 6, 4, 4, 1, 4, 3, 3 and 11; the *holder*, *passage*, *privilege* and *volume* checks at zero across the ten; Adrian Vale named in Chapter 0381 and in no other of them; and the day map, the seven notices, the three hundred days with both anchors in the sentence, the eighty-fifth day of the Bare Month as the last day any chapter may print, and the 292 silences at day 393.

**Six of the fifteen moved because the repairs added about a hundred and five words of attribution and narration, and none of them moved because a chapter got shorter.** Two moved because a word was changed and two because a phrase was cut, and those four are the honest cost of the repairs rather than a consequence of them.

---

## 9. What the repairs did not touch, which is the half that matters

**No day, no weekday, no month day, no anchor, no form, no notice, no object count that holds, no cast member, no decision of record, no second handle, no section boundary, no bold span and no line of dialogue. The set of bold spans across the ten files is byte-identical to `765e6d6` apart from none — no speech was edited at all.** `outline/ending.md` was not opened. No new final enemy was introduced and no antagonist ladder was extended.

**The seven notices still stand at 351→355, 354→358, 359→363, 362→366, 366→370, 371→375 and 389→393, and 389 is the seventh and the last and the woman who wrote it still says out loud that there is not going to be an eighth in this flood.** The three hundred and eighty-fifth day of this flood and its two anchors are untouched. The Bare Month still ends where it ended, on the eighty-fifth day, and no chapter of the ten printed a day after it. Adrian Vale performed no working, opened no threshold, is not offered a workway, is aged nowhere, and is in Chapter 0381 and in no other of the ten, in any form. The wall said nothing on all ten days and the volume's one panel is still fixed to day 393. The day-154 sentence is not said, restated, paraphrased or improved on, and the man who is right about it is still the man of about thirty-nine in Chapter 0393. *About two hundred rooms* is at zero across the ten files. Nobody counted the days since the fourth of the four said no. The two women of twenty-nine are never in one room. The ninth line did not move. The town four hundred miles inland was not entered and the page the copy was made from was not fetched.

**And the four inherited debts — the nineteen stray closing quotation marks in Chapters 0281 to 0290, `chapters/volume-07/chapter-0341.md:149`, the forty-word near-duplicate between `chapters/volume-06/chapter-0254.md` and `chapter-0262.md`, and the unmarked first-person paragraph at `chapters/volume-04/chapter-0175.md:47` — were re-measured by this pass and all four are still exactly where they were, at the same line numbers. A repair pass that quietly takes a routed item to save itself a line is how nineteen quotation marks became a four-volume debt, and this pass had six concrete faults in front of it and did not take one.**

**The volume's own name is still a man's answer spoken once in Chapter 0357 and written down in no file, and this file does not have it either.**

---

## 10. And the next phase, by path

**`workspace/volume-08/batch-0005/PROMPT.md`, and it is a BATCH and it is the LAST batch of Volume 08, and it is not the close.** It writes Chapters 0391 to 0400, days 391 to 400, from a Sunday to a Tuesday, and it decides nothing. It carries the three repairs from §6 above, and a writer is told about all three in the prompt itself, in the batch record and in the state layer: **the register and the slates are in 0392 and the folded sheet of road is in 0399 and not in 0392; the boards and the bare wall are in 0397 and 0400; and the man of about thirty-nine has a room count and it runs.** After it comes the Volume 08 close, which is the only phase after an outline phase permitted to decide anything, and which now has three findings waiting for it: the lead is in four rooms of this batch's ten, the protagonist is in one chapter of this batch's ten, and the object inventory has no marker column.
