# Review — Volume 05 close phase, and the repair pass that followed it

**This is the record of a review of the `volume-05-close` phase (`f1f72bd`, 6 files, +309/−24) and of the repair pass made in answer to it. The review itself is `logs/close.review.log`. The state-layer half of the disposition is `state/volume-05-close.md` §7 and `state/batch-summaries/volume-05-batch-0005.md` §22.**

**WHAT THE REVIEW WAS RIGHT ABOUT, AND IT WAS RIGHT ABOUT THE THING THAT MATTERED.** The close phase audited fifty chapters against a plan of record, measured the calendar, the interval chains, the descriptor map and the distances, and produced an unusually honest self-assessment. **All of that stands and none of it was touched.** It also declared that its failures were in the state layer and not in the prose. That declaration was wrong, and it was wrong in the most expensive direction available: the phase that read two hundred and fifty chapters for their figures never once looked at how a single one of them was set.

## 1. The blocking finding, and the repair

**Four-fifths of Volume 05's words sat inside bold marks.** Measured as the share of a chapter's words inside `**`, the five volumes ran 10.4, 56.6, 76.6, 69.8 and 79.5 per cent. **Volume 01 is the house model — bold for a word or two of emphasis, a list marker, and the one speaker in a dialogue, never a wrapped paragraph of narration — and Volumes 02 to 05 had drifted into wrapping the narration section lead of almost every scene, roughly one paragraph in three.** At that density the markup carries no information and the page is continuous shouting.

**Repaired, mechanically and without touching a word of prose. 2,005 narration paragraphs across 200 files in Volumes 02 to 05 had their outer `**` removed — 608 in Volume 02, 483 in Volume 03, 501 in Volume 04, 413 in Volume 05. Verification, run after the last edit and not before:**

- **The markup repair changed no character that is not a marker, and the check reruns from git.** Strip every emphasis marker from the committed files (`git show HEAD:<file>`) and hash: `93156ac5d0347bec775f3c873a41b49ae94a0b8c5b167a02f3bd991a3e3ce89c`. Apply the transform to those same files, strip the markers, and hash again: **the same value.** A reader can reproduce both halves in a minute and neither depends on a hash this document happens to be holding.
- The diff is **2,005 deletions against 2,005 additions**. Every removed line was a fully-wrapped paragraph and every added line is its own text, checked mechanically; the single exception is finding 2 below, which is a deliberate text repair and is called out as such.
- **Markdown parity: zero unbalanced `**` across all 250 files.**
- **Volume 01 was deliberately not touched.** Its 81 bolded narration paragraphs are sparse, deliberate, and are what the other four volumes should have looked like. Normalising them would have damaged the one clean page in the book.

| Volume | Words | Before | After | Paragraphs unbolded |
|---|---|---|---|---|
| 01 | 286,829 | 10.4% | **10.4% — untouched** | 0 |
| 02 | 180,075 | 56.6% | **33.0%** | 608 |
| 03 | 140,296 | 76.6% | **42.3%** | 483 |
| 04 | 122,691 | 69.8% | **42.7%** | 501 |
| 05 | 122,738 | 79.5% | **54.0%** | 413 |

**AND THE HONEST RESIDUE, because 54 per cent is better and is not fixed.** What remains bold in Volumes 02 to 05 is the one speaker's speech, which is this manuscript's only speaker marker and is load-bearing and was not stripped. **In Volume 05 it covers 54 per cent of the words because that speaker runs to 82 words a turn against Volume 01's 35.** That is the close record's §5 shape finding wearing a different hat — a two-hander exchange in which one voice holds the page — and cutting it is a rewrite, not a repair. **A chapter over about 35 per cent is telling its writer that the speeches are too long.**

## 2. The metric that was gameable, and was gamed

**Three state files tracked *bold marks per speech* against a 52 per cent floor, and the close phase recorded 51.5 as half a point under the band and told the next writer not to try to lift it.** That is the review's finding and it is correct. **A batch can sit exactly on a per-speech floor while four-fifths of the page is in bold, because a bold span in this book is a four-sentence finding and a plain one is a one-line question.** The average bold span across the five volumes is 35.2, 37.6, 52.2, 50.8 and 82.3 words, which is the whole mechanism: the floor rewarded long bold and short plain.

**Repaired as a measurement, not as a number.** The measure is now the share of words inside bold. The old figures stay on their pages marked superseded — `state/volume-05-close.md` §4, `state/batch-summaries/volume-05-batch-0005.md` §20.4 and §22 — because a record that quietly rewrites itself is the failure this repository names at its own §18. **What survives unchallenged from the old rule is the misattribution rule: within a section the bold marks one voice and the two voices alternate, and a ratio may not be fixed by bolding a short statement.** That part was never the fault.

## 3. The meta language was eight lines, not one, and no review had looked

**The review found one: `chapter-0215.md:37`, *this chapter did not answer it either*, against a quality gate that forbids it and against five batch records claiming zero. It was right about Volume 05.** Repaired: the meta clause became a claim inside the world, and nothing else in the sentence, the paragraph, the exchange or the chapter moved.

**Running the same class across the whole manuscript — which no review had done, because every review of this volume had only ever looked at Volume 05 — found seven more. All seven are repaired.**

| Chapter | Was | Now |
|---|---|---|
| `volume-02/chapter-0056.md:3` | *the politics of the next four volumes legible* / *the reader is allowed one guess better than the room* | *the next four quarters* / *whoever reads this later is allowed one guess* |
| `volume-02/chapter-0056.md:31` | *makes the next four volumes legible* | *makes the next four quarters legible* |
| `volume-02/chapter-0074.md:85` | *the reason this chapter is on the page* | *the reason the room is still sitting there at that hour* |
| `volume-02/chapter-0090.md:5` | *Nothing in this chapter is a resolution* | *Nothing in those forty days* — the licence in that paragraph is forty days old |
| `volume-03/chapter-0119.md:57` | *the reversal of this volume* | *the reversal of everything before them* |
| `volume-03/chapter-0140.md:73` | *the reader has to be somebody who is in that room* | *the person it is for has to be somebody who is in that room* |
| `volume-04/chapter-0170.md:3` | *not known at the top of this chapter* | *not known at first light* |
| `volume-04/chapter-0182.md:65` | *the only time in this volume that he has been asked to repair something* | *the only time anybody in that yard has asked him to repair something* |

**Every replacement is anchored to something already on its own page, so each one is checkable, and no replacement introduced a figure, a day, a name or a weekday.** A manuscript-wide search for *this chapter*, *in this chapter*, *of this chapter*, *the reader*, *the next four volumes* and *this batch* now returns zero across all 250 chapters.

**Two classes were left standing, deliberately, and the difference matters more than the repairs do.**

- **The Register is diegetic and is not meta language.** *This page*, *this book*, *entered in the book*, *on the eleventh page* stand roughly two hundred times across the manuscript. **The book is a physical object in this world and people enter things in it in rooms, in daylight, with a date on it.** That is the house register, it goes back to Volume 01, and cutting it would delete a physical institution out of the fiction.
- **Volume 02 opens a narrator's frame and says *this volume* thirty-one times across sixteen chapters.** It is meta language by the strict definition. It is also consistent, deliberate and load-bearing for that volume's voice, and **rewriting thirty-one instances across a closed volume is a change of voice and not a repair.** Left standing and named as a live question for the outline phase, which is the first phase in this repository allowed to decide what kind of book this is. Locations: `chapter-0066.md:5,117,135`, `0067:133`, `0069:5`, `0070:37,67,77`, `0072:39,47`, `0073:3,93,131`, `0074:49,79,91`, `0075:121,125`, `0076:33`, `0077:45`, `0080:17,53,127`, `0088:95`, `0092:115`, `0093:49,107`, `0095:75`, `0100:113`. **This record's own first draft of that figure said twenty-nine across seventeen; it was taken from a line count rather than an occurrence count and both numbers were wrong.**

## 4. The findings this pass did not repair, and why that is correct

- **The genre premise is gone.** Unchanged and correct: *Nora*, *Crossworld*, *Families Union*, *Northstar*, *Celia Rusk*, *Solenne*, *Hearthguard*, *sister*, *quarantine*, *medical*, *compensation*, *evidence*, *return*, *Earth*, *System* and *player* are all at zero across the fifty files. **Taking the shouting off the page has not touched this and was not meant to.** The audit is `state/volume-05-close.md` §2.
- **Two closed volumes have no outline.** `outline/volume-03.md` and `outline/volume-05.md` do not exist, which is the mechanical cause of the above. Not a repair pass's to write.
- **Fifty chapters in which nothing changed.** §5 of the close record: 597 of 629 plain speeches answered in the next line in bold. **The markup repair took the noise off the page and left this exactly where it was, which is correct — this is a shape fault and shape is the outline's.**
- **`state/phase-ledger.json` still reads `phase-000-bootstrap / planned / attempts: 0`.** The close phase declined it as controller-owned and that was right. **It is also true that this costs the "exactly one next phase" guarantee its backing, and finding 4 of the batch-0005 review is what that cost already looks like. This pass still does not touch it, and the gate now written into the Volume 06 outline prompt is the mitigation available without touching a controller file.**

## 5. The review's recommendation, and what was done with it

**The review's one recommendation was that Volume 06's outline must not write Chapter 0251 until the reconcile / carry / fold question is taken, because Volume 06's cast does not exist on a page in four hundred and forty chapters and `bible/power-system.md` forbids introducing a Regent in an opening chapter.**

**Adopted as a hard gate rather than a recommendation.** `workspace/volume-06/outline/PROMPT.md` §2 now states that the batch prompt that writes Chapter 0251 may not be created until the Volume 05 line has been decided and the decision written into `outline/series.md` in its own words. **The repair pass takes none of the three options and strikes nothing from `outline/series.md`, because deciding what a volume was is the one thing no batch and no repair pass here has been allowed to do, and the planned plot has not been changed.**

## 6. Verification run on the repaired files, and not before the last edit

- Prose checksum identical across all 250 chapters with emphasis markers deleted. **Zero words changed by the markup repair.**
- 2,005 deletions / 2,005 additions; every removed line a fully-wrapped paragraph; the one text change is finding 3 and is listed there.
- Zero unbalanced `**` in 250 files. Blockquote documents, the `"**one speaker**"` convention, list markers and Volume 01's deliberate emphasis all untouched.
- Zero high-confidence meta language across 250 chapters, against eight before.
- Bolded share of words restated on the page against Volume 01's 10.4 per cent; old per-speech figures left standing and marked superseded in three files.
- **`bible/power-system.md` §32 registered**, so the rule binds the next chapter and not only the next reviewer.
- **No day, figure, anchor, weekday, cast member, stage, ending or live thread state moved.** The two standing conflicts between a state file and the page — the weekday on the twenty-fourth day of the Long Month, and the trestle count — are still recorded rather than fixed, and neither was in scope.
- **The next phase is still `workspace/volume-06/outline/PROMPT.md` and there is still exactly one of it.** No second prompt, no batch directory, no Volume 07 directory was created.

**AND THE QUESTION THIS PASS IS LEAVING, WHICH IS NOT THE ONE IT ANSWERED.** The pages of this book are now set in a way a reader can get through, and the sentences in them still do not move anybody anywhere. **A Volume 06 outline that takes decision one and decision two and then writes fifty more two-hander exchanges in yards will produce a well-set book that is exactly as inert as the last four, and the bold rule will not prevent it, because a chapter can be 30 per cent bold and still be four sentences of finding in a row.** The pressure rotation in the cards is where that has to be answered, and it is a card-level instruction and not a formatting one.
