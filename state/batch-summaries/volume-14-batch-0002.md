# Volume 14, Batch 0002 Record — Chapters 0661 to 0670, days 661 to 670, one chapter to one day

**A batch of ten days that keeps grit on a board through two mornings of thumbs, washes a face while leaving the wall above it out of it, says out loud that two same pages cannot be told apart, shows a shut without showing past it, leans a board on the wrong stack, names carrying as a cost twice, washes a board with nothing decided, asks four times which surface to go by, keeps two unspoken words to the tenth hour, and keeps a stall's face turned in. THE PANEL COUNT ON THESE TEN FILES IS ZERO, scope: these ten files only, instrument: a block between blank lines whose first character is `>`. The wall says nothing on all ten.**

**Every pass below was run twice — once in file order and once in reverse with the index rebuilt — and both numbers are on the same row with the reading and the scope on that same line. All runs below agree. No repairs were made to any chapter after the passes; the one edit (0661, one clause de-metaphored) was made before the passes and the passes were run on the files as they stand.**

## 1. Cards first

Ten cards were written at the head of this batch's block in `state/current.md` before `chapters/volume-14/chapter-0661.md` existed. No card file was written or will be written under `outline/`; `outline/batches/volume-14-batch-0001.md` remains the only one. No card supplies a want, moves a day, adds a cast member, or widens a prohibition; wants for 0661 and 0665 are taken from `outline/volume-14.md` §4.1. **Two repeats from eight frames, named in the open: Frame 1 on 0661 (wharf board under grit; third party about four past the yard) and 0670 (stall board face in with row census; third party about four past the row); Frame 2 on 0662 (board against wall; third party a comparing room) and 0669 (page against door with room as instrument; third party the keeper alone). No chapter has become the other.**

## 2. Day map, re-derived, reading on the same line

**Instrument: weekday computed as (day − 1) mod 7 from day 1 Tuesday; Bare-Month ordinal found by walking backwards over number tokens only (cardinal tens + hyphen + ordinal unit, irregular tens and units included), resolved to integer, compared to day − 315. No table transcribed.**

| Ch | Day | Weekday re-derived | Bare-Month ordinal on the page | Resolves to | Day − 315 | Panels |
|---|---|---|---|---|---|---|
| 0661 | 661 | Thursday | three hundred and forty-sixth | 346 | 346 | 0 |
| 0662 | 662 | Friday | three hundred and forty-seventh (×2) | 347 | 347 | 0 |
| 0663 | 663 | Saturday | three hundred and forty-eighth | 348 | 348 | 0 |
| 0664 | 664 | Sunday | three hundred and forty-ninth | 349 | 349 | 0 |
| 0665 | 665 | Monday | three hundred and fiftieth | 350 | 350 | 0 |
| 0666 | 666 | Tuesday | three hundred and fifty-first | 351 | 351 | 0 |
| 0667 | 667 | Wednesday | three hundred and fifty-second | 352 | 352 | 0 |
| 0668 | 668 | Thursday | three hundred and fifty-third (×2) | 353 | 353 | 0 |
| 0669 | 669 | Friday | three hundred and fifty-fourth | 354 | 354 | 0 |
| 0670 | 670 | Saturday | three hundred and fifty-fifth | 355 | 355 | 0 |
| both runs | ten distinct days, no gap, no double | 10 of 10 | month's name in 10 of 10, 12 occurrences | all correct | 10 of 10 | 0 in ten files |

No ordinal after the 385th; no ordinal for a month; no span; length/long/short applied to that month at zero (the two tokens of *length* in 0661/0665 are a yard's length carrying a board, not the month; the fourteen *eighth* tokens are hours of the day, not documents — published as instrument false positives, neither repaired).

## 3. Traps

**Round-figure trap days 663, 664, 665, 668, 670 print none of their listed figures, scope: these ten files, reading: no elapsed count from any anchor at §14.5 appears in narration or mouth.** Day 665, the hardest, prints none of its four and prints neither half of the same-figure pair in one sentence: the Bare-Month 350th stands in its own sentence and no flood-day 350th stands anywhere in the file. **Same-figure trap: zero sentences carrying both halves of any pair, both runs.** No elapsed figure for the four-hundred-mile road at any day; no counting since the fourth of the four said no at any value.

## 4. Bolded share, per file, consequence not target

**Instrument, as a command, from the repository root:**

```
cd /home/runner/work/novel-earthside-license/novel-earthside-license
python3 - <<'EOF'
import re, glob
tot = b = 0
for f in sorted(glob.glob('chapters/volume-14/chapter-066[1-9].md') + glob.glob('chapters/volume-14/chapter-0670.md')):
    t = open(f).read()
    w  = len(t.split())
    bw = len(' '.join(re.findall(r'\*\*(.*?)\*\*', t, re.S)).split())
    tot += w; b += bw
    print('%-6s words=%-5d bold=%-4d share=%.2f' % (f[-7:-3], w, bw, 100*bw/w))
print('TOTAL  words=%d  bold=%d  weighted=%.2f' % (tot, b, 100*b/tot))
EOF
```

| Ch | Words | In bold | Share | Subject |
|---|---|---|---|---|
| 0661 | 1162 | 77 | 6.63 | grit, a stack, a barrow |
| 0662 | 970 | 83 | 8.56 | a board down and up, a wall left out |
| 0663 | 1100 | 85 | 7.73 | two same pages, four meanings |
| 0664 | 898 | 83 | 9.24 | a shut shown |
| 0665 | 897 | 74 | 8.25 | a board on the wrong stack |
| 0666 | 724 | 79 | 10.91 | a knife, two costs |
| 0667 | 766 | 71 | 9.27 | a board washed, nothing decided |
| 0668 | 802 | 82 | 10.22 | a question four times |
| 0669 | 819 | 69 | 8.42 | a keeper alone |
| 0670 | 740 | 66 | 8.92 | a face turned in |
| all ten, forward | 8878 | 769 | 8.66 weighted | range 6.63–10.91 |
| all ten, reverse rebuilt | 8878 | 769 | 8.66 weighted | SAME |

Reading on the same line: 8.66 weighted over 8878 words sits above Batch 0001's 8.32 over 14847 and the plan's 7.95 on the fifty behind; the top (10.91, a wharf morning with two men naming costs) and bottom (6.63, grit and a stack) are two subjects and not two qualities.

## 5. Markers

Prose paragraphs 98; speech paragraphs 20; bold paragraphs 20 with quotation marks on all 20 and bold-without-quotation 0; first-person-restricted 0 of 0; longest consecutive speech run 1 against a ceiling of 4; no exchange with two bold marks; every bold mark on its chapter's carded voice, twice in all ten chapters in two separate sections (wharf man 0661/0665, washer 0662/0667, keeper 0663/0669, carrier 0664, tradesman 0666, stallholder 0668/0670). Paragraphs of 3+ sentences 35, of which 32 carry a physical action read not swept; every chapter carries at least one; the three without action are named in the current.md block. Titles 15–19 words, at most one And each. *Own* range 0–6 per chapter. No bare tens word, no room count, no dozen, no passage/privilege, no man of about thirty-seven, nine steps never said.

## 6. Adrian

In 0661 and 0665 only, per the map. Nobody asks him anything, he asks nothing, nobody thanks him, nobody tells him he was right, on both. Physical causes: 0661 a shifted stack and a rolled barrow the wharf man must catch; 0665 a board leaned on the wrong stack and a barrow handle touched. Neither is a decision, word, document, notice or panel. Both wants not obtained, per §4.1. Neither day carries a page read out, a decision taken, a hand into a place, a name spoken, the volume's question, or the last image.

## 7. Objects, both directions, nothing repaired

Direction one: nil — every set the per-chapter column intends is named. Direction two additive names (second handles, passers-through, standing facts) publish in current.md; none prints a differing count. The *eighth-hour* tokens are hours, not documents; no eighth of notices or documents is asserted anywhere. The bare piece of door and the second slate are never on one shelf and never called one kind of place. The stallholder is the man in every occurrence.

## 8. Closings, read by a person

Ten closing sentences side by side in current.md with the reading: ten different constructions, each a thing somebody does, each new to its chapter, none on the five off-limits positions, none a thesis restated, at most the rotation's share of quiet.

## 9. What was not done

No chapter past 0670; no new person/descriptor/name/place; no notice; no document moved; nothing under the date; no second word; chalk never out; second slate never touched; wall silent on all ten; zero panels; `outline/ending.md` unopened; ending untouched; no new enemy; no plan or calendar file edited; no controller file touched. `state/chapter-summaries.md` written by this batch with the conflict published at the head of the block.

## 10. Review findings and repairs

**This section records what a review of this batch found and what was done. No review has run yet; the section stands to receive it. The one pre-pass edit (0661: "no chapter of any life he has lived" → "he has never said where it came from to any person in that yard") is recorded here so a reviewer does not find it unannounced.**

**THE NEXT PHASE IS `workspace/volume-14/batch-0003/PROMPT.md`, WRITING CHAPTERS 0671 TO 0680, DAYS 671 TO 680, AND NOTHING ELSE.**
