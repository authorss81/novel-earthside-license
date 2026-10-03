# Reviews — Volume 20, Batch 0005 — Review-Fix, Second Pass

**A second repair pass over the same ten finished days, run against the findings of an outside reader rather than against a
first draft. The file of record for the batch is `reviews/volume-20/batch-0005.md`; the first repair pass is
`reviews/volume-20/batch-0005-fix.md`. Neither is superseded by this one, and where this one corrects a line in either of
them it says which line and why. Seven findings came back. **Four are applied: one in a chapter, and three in the records
and the state layer. Two are not applied here at all and are named at §5, because they are not this pass's to answer. One is
answered by publishing an instrument and three locations rather than by changing a page, and §4 says which and why.**

**NO CHAPTER OF THIS BATCH WAS RESTARTED. NO DAY IS MOVED, NO WEEKDAY, NO BARE-MONTH ORDINAL, NO PRESSURE TAG, NO FRAME AND NO
OBJECT STATE WAS CHANGED TO SATISFY A FINDING. ONE CHAPTER WAS OPENED AND ONE SENTENCE IN IT WAS REWRITTEN, AND IT IS THE
SENTENCE THE FINDING NAMED.** Every figure below was measured with the instrument published beside it, in the same run as
the prose change, and the reading and the scope are on the same line as the number.

**THE REWRITE WAS WORD FOR WORD, AND NOT ONE FIGURE IN THE LAYER MOVED BECAUSE OF IT.** The chapter's body-word count is
2,162 before and 2,162 after, the batch total is 15,729 on both sides of it, and the negation count, the *his own* count, the
sentence count, the shared-run table and the closing-similarity figures in §2 are identical before and after. **So the nine
files this pass edited were edited for faults that were already in them, and not because this sentence disturbed anything,
and a reader comparing §2 with the first repair pass's §2 will find one set of numbers rather than two.**

---

## 1. THE ONE PROSE FINDING, APPLIED — `chapter-0994.md`, THE VOLUME'S CLOSING DAY

> The light came in at that window about the seventh hour […] His own shoulder and his own arm took it off that wood **for
> the rest of that day**. […] The shade of his own shoulder lay on that wood **from the seventh hour to the going of the
> light** without once lifting off it […]

**Two spans for one shade.** The first sentence came down with the chapter in the writing run and the last was added by the
first repair pass at its §1.7, which recast this closing off 0999's construction and did not notice that the sentence it kept
already said the thing it was adding. **A reader found it, and it is on the last page of the volume's climax.**

**Applied, and the span is now said once:**

> His own shoulder and his own arm took it off that wood as soon as it was on.

The new sentence carries the onset and nothing else, so the terminal sentence is the only statement of how long that shade
lay there, and it stands at the seventh hour and the going of the light, which is what the chapter says about Adrian Vale
standing at that wall at its seventy-seventh line. **Two further things came out of the same edit without being asked for:
the closing no longer says the same thing twice in two sentences, and the paragraph no longer opens a past-tense scene and
then restates it in the present for its last beat while the two sentences in between are in the past.** The present-tense
final sentence is left exactly as the first repair pass wrote it, because the tense rule in `state/continuity.md` puts a
material's behaviour in the present and two other closings in this batch — 0995 and 1000 — close in it.

**AND THE THREE HELD WORDINGS OF DAY 994 WERE NOT TOUCHED, AND WERE RE-MEASURED AFTER THE EDIT.** §6.

---

## 2. THE FIGURES, RE-MEASURED AFTER THE EDIT, WITH THE INSTRUMENT ON THE SAME LINE

| What | Figure | Instrument, reading and scope |
|---|---|---|
| Body words, per file | **1937, 1406, 1404, 2162, 1651, 1295, 1684, 1414, 1464, 1312** | whitespace `split()` of the body, heading line out, ten files. **Total 15,729, mean 1,572.9, shortest 1,295 (0996), longest 2,162 (0994), spread 867** |
| Paragraphs | **263, of which 46 are scene rules and 13 are speech paragraphs** | non-empty blocks separated by a blank line, `---` counted as one block, a speech paragraph being a block whose first non-space characters are `**"` |
| Panel lines, digits in bodies | **0 and 0** | a surviving line whose first non-space character is `>`; any character zero to nine, body, heading out |
| Title words | **8, 7, 8, 8, 8, 9, 7, 9, 7, 7** | title text after the em dash, ten headings, all inside §17.8's four to nine, **and 0 of the ten contain *question* in any form** |
| Sentences | **475 or 476, mean 33.0 or 32.9, median 32, longest 87, 106 at forty-five words or over which is 22.3 per cent on either reading, and 4 at eighty words or over** | bodies with `---` read as whitespace and bold markers stripped, split on a full stop, question mark or exclamation mark followed by a capital, a quote or an opening bold marker. **The count and the mean differ by one between the two published readings — the record and the fix pass print 475 and 33.0, and a splitter that requires nothing after the terminal stop returns 476 and 32.9 — and every other figure on the line is identical on both. Both are published rather than one of them, and the four sentences at eighty words or over are four speeches, one of which is a held wording** |
| Repeated sentences of thirty characters or more | **0 across all fifty files of days 951 to 1000, 0 at thirty-eight, and 0 inside any one of these ten files** | sentence strings whitespace-normalised with the speaker marker stripped, scoped to strings occurring in more than one file, and then re-scoped to strings occurring twice inside one file |
| Longest shared run, ten files | **37 tokens, on TWO pairs: 0992 with 0999, and 0991 with 0997** | longest common contiguous token sequence, every pair, on a run of letters with any apostrophe kept inside it, lowercased, a hyphen splitting a token in two |
| Longest shared run, fifty files | **37 tokens, on THREE pairs, those two and 0978 with 0991, and eleven pairs at thirty-five or over** | same token, every pair of the fifty files |
| Highest similarity between two closings | **0.173 in the record and 0.171 on a re-measure, the pair 0997 with 1000 on both** | character ratio over the whitespace-normalised closing paragraph of each body; no other pair is within 0.02 of either |
| Worst *nobody*-clause chain | **3, against a ceiling of 3, and it stands in three chapters: 0994, 0996 and 0997** | clauses opening *nobody*, *no one* or *not one* inside one sentence, counting `^`, a comma and *and* as openers. **The count of chapters carrying a run of three or more sentences opening *nobody* is 0 of 10** |
| Negation tokens | **248 in 15,729 words, one in 63.4**, against 287, 295, 214 and 240 on the four sets behind: one in 45.5, 41.3, 62.6, 57.9 | *nothing, nobody, no, not, never, cannot, neither*, whole words, both case flags, non-letter on each side, bodies, heading out |
| Bare *that* | **4.37 per cent**, against 3.32, 3.95, 3.15 and 4.01 | the literal string `that` on the body with `---` scene rules dropped as blocks and bold markers stripped, either case, over the whitespace words of that same text. **This is a substring reading and not a word-bounded one, and it is the reading that returns the published chain exactly; a word-bounded reading returns 3.16, 3.77, 2.98, 3.93 and 4.24, and both readings are published here because the figure is worthless without its reading** |
| *his own* | **172 in 15,729 words, one in 91.4**, against 89, 86, 133 and 135: one in 146.7, 141.5, 100.7 and 102.9 | whole words, same reading and scope, five sets measured in one run |
| True contractions | **0 in 15,729 words, and 0 on each of the four sets behind** | a run of letters, an apostrophe, and one of *t re ll ve d m*, both case flags, bodies, heading out |
| `asked`, `asking`, `question` | **27, 3, and 0 in bodies and 0 in headings** | whole words, both case flags, bodies and headings counted separately |
| Census | **7 across 6 days and 7 of the 7 carry *people* inside the phrase** | `about four` followed within thirty characters by `people` |
| Barred literals | **`nine steps` 0, `gate` 0, `By the light's going` 0** | literal strings, ten bodies and ten headings |

**THE CALENDAR RE-DERIVED AND NOT TAKEN FROM ANY TABLE.** Day one a Tuesday and the Bare-Month ordinal the day less three
hundred and fifteen: 991 Friday 676 to 1000 Sunday 685, ten of ten agreeing with the printed bodies, and all ten parsing
back out of the printed words of their own bodies.

---

## 3. THE TWO FINDINGS THAT WERE DEFECTS IN THE RECORDS, AND WHAT WAS DONE IN EACH FILE

**3.1 THE SHARED-RUN CLAIM NAMED ONE PAIR WHERE THE INSTRUMENT RETURNS TWO.** `reviews/volume-20/batch-0005.md` §7 printed
*the longest run shared by any two of these ten bodies is 37 tokens, and there is ONE pair at it, `chapter-0992.md` with
`chapter-0999.md`*, four lines above its own table, which lists two pairs at thirty-seven on its own ten and three over
fifty. **The table was right and the sentence was wrong, and rule 1 at the head of `state/open-threads.md` — publish every
pair at the top length rather than one of them — is the rule the sentence broke while the table beside it obeyed.** Corrected
in the record, and the correction says two on the ten and three over fifty and names the third, `0978` with `0991`.

**`state/current.md` had inherited the one-pair claim with emphasis on it, and `state/open-threads.md` had used it as the
worked example of rule 1 — so a rule was being illustrated out of the one place the rule was broken.** Both are corrected: the
open-threads example now says what §7 published, what the instrument returns and where the correction is.

**3.2 TWO COUNTS THAT DID NOT RETURN.** `reviews/volume-20/batch-0005-fix.md` §2 printed *his own* at **171 in 15,729
words, one in every 91.4** — and 172 is the count that returns 91.4, so the count was corrected and the rate kept.
`reviews/volume-20/batch-0005.md` printed `asked` at **29 in the bodies** and a whole-word count returns **27** on every
reading tried, heading line in or out, and 30 with `asking` added; corrected to 27 with the readings published.
`state/continuity.md` printed the fifth *his own* point as **91.5** against 91.4 in the rest of the layer; corrected.

---

## 4. THE STATE LAYER, AND THE ONE FAULT THAT WAS NOT IN THE FINDINGS

**Every one of the five live files and this batch's summary carried at least one figure or claim that the chapters on disk do
not support, and all of it is corrected:**

| File | What it carried | What it carries now |
|---|---|---|
| `state/current.md` | the post-repair word list and total on one line and the pre-repair longest, spread and sentence figures on the next, so that 2,075 − 1,295 was printed as a spread of 777 | **longest 2,162, spread 867**, and the sentence line printed as 475 or 476 by one token of the splitter with 106 at forty-five words or over and 22.3 per cent on either reading |
| `state/current.md` | the closing-similarity figure as 0.175, which was the pre-repair value | **0.173 in the record and 0.171 on a re-measure, the pair named, and the instrument named** |
| `state/current.md`, `state/batch-summaries/volume-20-batch-0005.md` | **the grit row enumerated at two lines and four going up from them** — a figure the first repair pass had already removed from 1000 as contradicted by the plan's own count of day 920 and by 0952, 0978 and 0992 | **two lines at that end of the row, and lines going up from that end of it joint after joint, and more of them than anybody has ever counted**, as `state/continuity.md` and `state/chapter-summaries.md` already had it |
| `state/batch-summaries/volume-20-batch-0005.md` | **the whole pre-repair figure set**, after the repair that produced the post-repair set — the same failure as rule 1 one level out, named at `state/open-threads.md` and now naming two summaries and not three | the post-repair set throughout, with the *nobody*-chain figure at 3 and its three chapters named and the full-descriptor instrument published |
| `state/continuity.md` | `asked` at 29, the fifth *his own* point at 91.5, and 994's closing described with the shade's span said twice | 27, 91.4, and the span said once at the seventh hour |
| `state/character-state.md`, `state/chapter-summaries.md` | 994's closing described with *for the rest of that day* | described the way the chapter says it |

**THE ENUMERATION OF THE GRIT ROW IS THE ONE FINDING IN THIS FILE THAT NOBODY RETURNED, and it is here because it is the
same fault twice over: a figure that four chapters contradict was standing in two state files after the pass that removed it
from the chapter had already corrected two others.** It is named rather than quietly fixed, because a later reader should
know that the first repair pass's own claim — that it had re-measured every figure in the live layer — was one file short.

**AND THE FULL-DESCRIPTOR INSTRUMENT IS PUBLISHED FOR THE FIRST TIME, BECAUSE THE FIGURE IT GOVERNS WAS NOT REPRODUCIBLE AS
STATED.** A full-descriptor restatement is **a person who speaks more than once in one chapter and carries the whole
age-and-trade handle in the attribution of every one of those speeches.** Nobody in these ten is one. A full descriptor in
narration beside a person who is not speaking is not an attribution and is not counted, and 0994 carries the keeper's whole
handle in narration three times and the short handle once, the third of those three being put there by the first repair pass
to break a run of *nobody* sentences, and it breaches nothing.

**AND THE THREE CHAPTERES CARRYING A *NOBODY*-CHAIN OF THREE ARE NAMED, because the figure sits exactly on the ceiling and a
reader should be able to see where.** They are 0994, 0996 and 0997, and **this pass did not break them.** 0994's is a
rendering of §6.9's own four sentences — *nobody thanks anybody, nobody agrees, nobody argues, nobody improves on one word
of it* — in narration, and the batch's worst case is 3 in all three chapters, so breaking one would move no figure. The
chain of three at 0994 and the chain of three at 0997 are each a sentence the room's own silence is being reported in, and
the rule's own ceiling is three.

---

## 5. WHAT THIS PASS DID NOT DO, AND THE TWO FINDINGS IT IS NOT THE PASS TO ANSWER

**THE VOLUME-CLOSE PHASE DOES NOT EXIST AND NOBODY HAS DECIDED THAT IT SHOULD.** All nineteen earlier volumes have a
`workspace/volume-NN/close/` directory with a `.done` marker; Volume 20 has fifty chapters on disk and none. **A reader is
right that `AGENTS.md` asks for exactly one volume-close prompt where a volume is complete, and right that the question is
being settled by whatever the dispatch falls back to rather than by anybody who chose it. This pass did not write the prompt
and did not create the directory, because whether Volume 20 ends this manuscript or whether a Volume 21 is planned belongs
to the owner of `outline/series.md`, and `outline/volume-20.md` §21.4 item 2 says in its own words that whether anything
follows is not that plan's to decide.** It is now named as an open item in `state/current.md`, in `state/open-threads.md`
and at §9 of the record of record, so that it is a decision somebody has to take and not a silence a later reader has to
guess at.

**AND THERE IS STILL NO INDEPENDENT READER OF THESE CHAPTERS.** The dispatch falls back to the writer's own agent kind, so
the findings this pass worked from were returned by a reader of a different kind but not by a reader outside this
repository's own agent, and `AGENTS.md`'s line *a reviewer has checked the result* is not satisfied by that. It is stated
rather than implied, in the record of record and in this file.

**`outline/ending.md` was read and not moved. No controller file was opened and none was edited: nothing under `scripts/`,
`.github/workflows/` or `.opencode/agent/`, and not `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`,
`opencode.json` or `state/phase-ledger.json`. `outline/volume-20.md` and `outline/series.md` were read and not edited. No
planned plot moved, no chapter past 1000 exists, no panel line was added, no seventh stroke went into any column of either
book, no leaf was turned, no second nail went into that outside wall, the bar stayed on the top step out of its two sockets
on all ten mornings, no rope was lifted, no post of that fence was moved and its totals are printed on no day of this batch,
no satchel and no tin was opened, the trough's ice was not broken and no heat was fetched for it, the gate at the far end of
that shut road is not mentioned on any of these ten days, and the descriptor pool is where it was: *woman of about
fifty-four* at 1, in the keeper's own mouth on 994, and 0 on days 995 to 1000.**

---

## 6. THE HELD STRINGS, RE-MEASURED AFTER THE EDIT, AND NOT PRINTED

**The instrument is the one `reviews/volume-20/batch-0005-fix.md` §3 names: read the blockquote out of the subsection of
`outline/volume-20.md` that owns each held wording, join a multi-line blockquote with a single space, normalise internal
whitespace, strip the full stop from the end, and count literal occurrences across the scope.** Scope: the fifty chapter
files of Volume 20, both records of this batch, this file, the five live state files, the batch summary and the volume
index. **The three wordings of day 994 stand at one occurrence each in one file each, and the one file is
`chapter-0994.md`, which is the file this pass edited.** Measured after the edit, not before it. **No held wording is
printed in this file**, and the counts above are the measurement.

---

## 7. WHAT A LATER PASS SHOULD KNOW ABOUT THIS ONE

**One sentence of prose changed and it is the sentence the finding named. Every figure in the layer is the figure of the
chapters as they stand, and the two places where two readings differ — the sentence count and its mean, and the
closing-similarity ratio — are published as two readings rather than picked between. The grit-row enumeration that four
chapters contradict is out of the layer. The full-descriptor instrument and the *nobody*-chain locations are published. The
volume close is a named decision for a person and not a gap in a directory.**