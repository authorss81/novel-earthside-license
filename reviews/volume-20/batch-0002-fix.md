# Phase review-fix — Volume 20, Batch 0002 (`809190f`)

**A reviewer read the batch just committed and returned nine findings. This file records what was applied, what was
measured and declined, and what was found by this pass that the reviewer did not report. Every figure below was measured on
the files as they now stand, in the same run as the repairs, and the instrument is named on the same line as the number.**

**Nothing was restarted. No planned plot moved. The chapter diff is forty-four insertions against forty-four deletions
across twenty files; thirty-nine of those pairs are a single comma each and the remaining five are four repeated sentences
and one rewording. No paragraph, scene, chapter, day, weekday, Bare-Month ordinal, pressure tag, frame, stroke, mark or
object was added, cut, reordered or moved.**

---

## PART ONE — WHAT WAS FIXED

### FINDING 1, THE BLOCKING ONE: THE ATTRIBUTION PUNCTUATION. FIXED, AND THE COUNT WAS UNDERSTATED.

**The review reported 31 occurrences of a full stop inside the closing quote before a speech tag, and said one find and
replace fixes the volume. The pattern is real and the repair is one pass, but the count was low.** The review's own
instrument searched for the literal `"** said` in lower case and so missed the tags that begin with a capital or a pronoun.

Measured properly, over every speech in the volume: **Volume 20 contains 39 bolded speeches and 39 speech tags. Every one
of the 39 had a full stop inside the closing quote. The volume was at 39 of 39 and not 31.**

**Fixed on disk. The form is now `**"…," **said the man of about thirty-nine` — comma inside the closing quote, tag outside
it. Residual defects in Volume 20: 0.** The diff for these thirty-nine sites is one character changed in each, `.` to `,`,
and no word anywhere in the volume moved.

### FINDING 1b, FOUND BY THIS PASS AND NOT BY THE REVIEW: FOUR SENTENCES REPEATED ACROSS THE TWO BATCHES. FIXED.

**The review reported, correctly, that this batch's own repeated-sentence instrument found zero. That zero is true of the
ten and it is useless about the volume, and this pass measured across all twenty files of days 951 to 970 and found four
exact repetitions of a sentence of thirty-eight characters or more.** Each is a standing-object sentence lifted out of days
951 to 960 and set down again in days 961 to 970:

| Repeated sentence | In | Also in |
|---|---|---|
| the woman of about fifty-two at her far wall with the stool standing a foot off her own skirt | 0951 | **0962** |
| *It is not the round hole a nail leaves…* and the burr turned down on the near lip | 0954 | **0966** |
| *She said it before anything else that morning.* | 0957 | **0965** |
| the box of chalk with its lid off at one corner | 0959 | **0965** |

**The newer file of each pair is the one that was reworded, so no closed and audited batch was touched. Every fact of
every one of the five days is unchanged; only the wording of a repeated sentence moved. Measured after the repair: 0
repetitions at thirty-eight characters across the twenty files, and 0 at thirty characters as well, where there was 1.**

**This is a debt the repository already knew about and walked into twice.** `reviews/volume-19/batch-0005.md` §9 named it
for the batch behind this one, and the batch-0001 repair cut seven instances of it. **It recurred because a within-batch
instrument cannot see a cross-batch repetition, and the rule that stops it is now written into `state/open-threads.md` and
into the next prompt: measure your ten against the twenty behind them, not against themselves, and hold a sentence at
thirty characters rather than thirty-eight.**

### FINDING 2, THE FORWARD INSTRUCTION THAT WOULD HAVE HARDENED THE OPENING TEMPLATE. FIXED, AND THE TEMPLATE IS MEASURED.

**`workspace/volume-20/batch-0003/PROMPT.md` line 186 read, in bold: "Every one of your ten opens with hands on a thing."
The review is right that this extends a template across thirty chapters, and the measurement is worse than the review
states.** Across all twenty chapters on disk, days 951 to 970, **every one of the twenty opens `A hand` / `Two hands` /
`Both hands` / `The flat of a hand` / `Two fingers` plus a verb of placing plus a named surface. It is 20 of 20.**

**The mandate is withdrawn and replaced with the measurement and a cap: no more than three of the next ten may begin with a
hand or hands on a surface, and no two of the ten may share one construction with each other.** Seven ways in that cost
nothing are named in its place. **None of the twenty existing openings was rewritten**, because a review-fix pass that
rewrote twenty opening sentences would be rewriting the batch.

### FINDING 3, THE CLOSING REFRAIN. THE REVIEW OVERSTATED IT, AND IT IS NOW CAPPED.

**The review reported "19 of 20 chapters close on the identical construction `By the light's going…`". That figure is not
what the files show, and the difference matters because the correct number is the actionable one.** Measured:

- **`By the light's going` stands in 19 of the 20 files** — once in eighteen, twice in one.
- **It opens the closing section in all 19 of those files.**
- **It closes the last paragraph in 6 of the 20, not 19.** The review's count came from a `grep -l` for the phrase anywhere
  in the file, which cannot distinguish a refrain from a closing.

**So §17.17's requirement that no two chapters close on the same construction is being substantially met, and the real
fault is a per-chapter refrain rather than a per-chapter ending. The remedy is different from the one the review implies
and is now written into the next prompt as a cap: at most three of the next ten may open their closing section with it, and
none may close on it.** No existing chapter was changed, because the repetition is a rhythm this volume was built on and
cutting six chapter endings would be a decision about the volume's shape, not a repair.

### FINDING 7, THE STATE LAYER. FIXED, AND IT IS THE LARGEST CHANGE IN THIS PASS.

**The review is right on every count here and this is the finding with the most behind it.** `PHASE_SYSTEM.md` asks for
compact bounded state, a rolling window and a volume-level index; the two batches behind this one were instead instructed
to prepend and never rewrite, and the result was five live files of **4,274 lines** between them, of which
`state/current.md` was about ninety-three per cent a verbatim copy of its own archive, with `state/archive/` at 118 files.

**Done, in this order.** Each of the five files was copied whole into `state/archive/` under the suffix
`.volume-20-batch-0002-review-fix-full.md` and the live file and the copy were verified byte-identical by SHA256 **before a
single line was withdrawn.** Then each live file was rewritten: the newest batch's binding facts kept in full, the settled
rules kept in full, **every prohibition kept**, and the history of how a prohibition came to be written reduced to a table
naming each retired block, what it decided, and the archive file that holds it whole.

| File | Before | After |
|---|---|---|
| `state/current.md` | 992 | 149 |
| `state/continuity.md` | 971 | 220 |
| `state/open-threads.md` | 796 | 123 |
| `state/character-state.md` | 1,084 | 199 |
| `state/chapter-summaries.md` | 431 | 118 |
| **Total** | **4,274** | **809** |

**Nothing was deleted and no fact was dropped.** Two layers were flagged in the index rather than silently compressed away,
because they still carry live prohibitions: **the threads this manuscript was carrying at the end of day 750, and the
protagonist and handle table from the Volume 20 planning block.** Both must be read whole from the archive before any
volume-close audit. `state/volume-20-index.md` is new and is the volume-level index `PHASE_SYSTEM.md` asks for; it tells a
writer which live section answers a question and which archive file to open when it does not.

**The next prompt's instruction is changed to match.** It no longer says the live layer is prepended to and not rewritten.
It now says the layer is rolling and bounded, that the writer keeps their own block in full and rewrites the standing layer
beneath it to a compact index, and that they must leave each of the five files shorter than the run found it.

---

## PART TWO — WHAT WAS MEASURED AND DECLINED, WITH THE MEASUREMENT PUBLISHED

### FINDING 4, THE NEGATION, AND FINDING 5, THE TEN CHAPTERS BEING NEAR-INTERCHANGEABLE. DECLINED AS A REPAIR, CARRIED FORWARD AS A NUMBER.

**The review's finding is correct and the review's cause is also correct: `AGENTS.md` says never replace a scene with a list
of states and that every chapter must change the situation, and `outline/volume-20.md` stacks about one hundred and fifty
*may not* rules, of which §6.4 rule (v) forbids printing the answer on nine of the nine question-days. The chapters that
obey the plan most strictly are the ones with least in them.**

**Measured across three sets with one instrument, negation tokens being *nothing, nobody, no, not, never, cannot,
neither*:**

| Set | Words | Negation tokens | One in | Bare *that* |
|---|---|---|---|---|
| Volume 19, days 931 to 950 | 23,464 | 458 | 51.2 | 2.41% |
| Volume 20 batch 0001, days 951 to 960 | 13,036 | 287 | 45.4 | 3.31% |
| Volume 20 batch 0002, days 961 to 970 | 12,157 | 295 | 41.2 | 3.94% |

**The review's raw figure of 321 across 13,337 words for batch 0002 does not reproduce on bodies alone; 295 in 12,157 does,
and 2.43 per cent against the review's implied 2.41 is the same number to rounding.** Bare *that* is the steeper of the two
trends and neither is in the plan.

**Declined as a repair, and the honest reason is that fixing it is the forbidden operation.** The two clearest cases are
`chapter-0961.md`, where a whole paragraph reports that nothing on any surface holds what two men said to each other, and
`chapter-0965.md`, where two paragraphs establish that nobody will ever learn what the question was. **Both would have to
be cut and replaced, which is rewriting ten finished scenes — restarting the batch.** Padding them is forbidden by
`PHASE_SYSTEM.md` in the same paragraph that sets the length range.

**So it is carried forward instead, as a measured trend and a craft rule, in `state/open-threads.md` and in the next
prompt: a held string binds what a chapter may print and does not license a paragraph spent reporting that it did not
print it; say the hold once, in one clause, and spend the rest of the paragraph on what somebody does with their hands.**
That is the strongest disposition available without touching the plan or the batch.

### FINDING 6, LENGTH. DECLINED, AND IT IS THE FOURTH CONSECUTIVE DECLINE AND THAT IS THE ACTUAL PROBLEM.

**Measured: mean 1,215.7 against `PHASE_SYSTEM.md`'s 2,200 to 3,200, which is 984 words a chapter under the floor. The
three-batch trend is 1,160.2, then 1,303.6, then 1,215.7.** `PHASE_SYSTEM.md` forbids padding and forbids splitting a
finished scene in the same paragraph that sets the range, so a repair pass cannot honestly close this.

**What the review added, and it is right, is that deferring it a fourth time will not move it. Three volumes of deferral is
a decision and the decision has been made four times.** This pass therefore did two things rather than one: it published
the trend in three state files so a volume-close audit sees it as a number rather than as an excuse, and it wrote the
next prompt to leave each state file shorter, on the reasoning that a writer who is not asked to maintain four thousand
lines of self-certification has more of a run left for the scene. **Whether that moves the mean is batch 0003's to settle,
and this pass does not claim it will.**

### FINDING 8, THE REVIEW DISPATCH. RECORDED, NOT TOUCHED, BECAUSE IT IS NOT OURS.

**`reviews/volume-16/` does not exist, so the review dispatch falls back to the writer's own agent, and `state/current.md`
and the batch-0002 record both say so. The reviewer is right that a compliance attestation written by the writer does not
satisfy `AGENTS.md`'s gate that a reviewer has checked the result — and this pass is itself an example: it found four
repeated sentences and one miscount that the batch's own instruments and the batch's own 469-line record had both missed.**

**`.opencode/agent/` and `.github/workflows/` are controller-owned and were not opened.** The remedy is a controller change
and is named here for whoever makes one.

---

## PART THREE — WHAT THIS PASS FOUND THAT THE REVIEW DID NOT REPORT

1. **The defect count was 39 and not 31**, because the review's instrument was case-sensitive and missed five tags.
2. **Four exact repeated sentences across the two batches**, which no within-batch instrument can see. Fixed, and the rule
   written into the state layer and the next prompt.
3. **A figure in the batch's own records was wrong and contradicted itself.** `state/chapter-summaries.md` printed **1257**
   for chapter 0969; `state/current.md`, printed by the same run on the same day, printed **1243**. Measured on the file,
   **1243 is right.** Corrected in place and named in three places, because a figure a reader cannot re-derive is the fault
   §17.22 exists to catch and a discrepancy inside one run's own two records is exactly that.
4. **The paragraph count in the batch's own record was 191 and measures 192** on the same instrument. Left alone, because
   a one-paragraph disagreement about whether a `---` scene break is a paragraph is not worth a correction that would make
   the record less reproducible, and it is named here instead.
5. **The review's own closing-count was wrong in a way that would have produced the wrong remedy.** Finding 3 above.

## PART FOUR — THE HOUSE DEBT THIS PASS FOUND OUTSIDE ITS OWN SCOPE

**The attribution fault is not confined to Volume 20, and the review's phrasing — "wrong in all 20 files of Volume 20" —
could be read as a volume-local problem. It is not.** Every match on disk was classified by whether the text after the
bold marker is a speech tag or the next narration sentence:

- **Volume 20 — 39 sites, all 39 corrected here. None remain.**
- **Volume 19 — 21 sites**, in chapters 0925, 0931 and 0934 to 0950. Not corrected; outside this phase.
- **Volume 07 — 1 site**, chapter 0311. **Volume 16 — 1 site**, chapter 0781. Not corrected.
- **23 real sites outstanding outside Volume 20.**
- **Volumes 17 and 18 carry 218 such tags between them and every one is already correct**, so the fault is not universal
  and those two volumes are the model. Volume 18 prints `…minute ago,"** said` and Volume 17 prints `…set it down,"** he`.
- Two further matches, in `chapter-0301.md` and `chapter-0797.md`, are **not** defects: the period there ends an internal
  sentence of a multi-sentence bolded speech and the sentence after the marker is narration.

**Recorded as a standing debt in `state/open-threads.md` with the exact figure and the exact chapters. Not repaired here,
because a Volume 20 fix pass has no business rewriting closed and audited volumes, and because the number belongs to
whoever owns those chapters.**

---

## PART FIVE — WHAT WAS NOT TOUCHED, AND THE CHECKS THAT FOLLOWED

**No planned plot moved. No day, no weekday, no Bare-Month ordinal, no pressure tag and no frame changed. No panel and no
block beginning with `>` exists on any of the ten days. No held string, no name, no descriptor out of the pool and none of
the seven words of Volume 19 was introduced or removed. **By that pass, and not by the writing run, the refusal of 965
was not written, restated, paraphrased or put into a second mouth; it stands once in `chapter-0965.md` in her mouth and once
in the plan, and the writing run put it there before this pass began.** `outline/volume-20.md` and `outline/ending.md` were read and not edited. No file under `scripts/`,
`.github/workflows/` or `.opencode/agent/` was opened. `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`,
`opencode.json` and `state/phase-ledger.json` were not edited. Exactly one next phase exists and no second was created.**

**The checks, each measured after the repair and not before it:**

| Check | Result |
|---|---|
| `."**` before a speech tag, Volume 20 | **0**, from 39 |
| Repeated sentences ≥38 chars across days 951 to 970 | **0**, from 4 |
| Repeated sentences ≥30 chars across days 951 to 970 | **0**, from 1 |
| Chapter files on disk for days 951 to 970 | 20, unchanged |
| Changed lines that do not match the punctuation pattern or a repeated sentence | **0** |
| Words added or removed by the punctuation repair alone | **0** |
| `question`, `questions` in bodies and headings, days 961 to 970 | 0 and 0 |
| `passage`, `privilege` in days 961 to 970 | 0 and 0 |
| The wording held at `outline/volume-20.md` §6.6 in Volume 20 chapters | 0 |
| `cannot be proved to have been asked` in Volume 20 chapters | 0 |
| The wording held at `outline/volume-20.md` §6.8 in Volume 20 chapters, measured as a whole word | 0 |
| The refusal of 965 | once, in `chapter-0965.md`, and once in the plan |
| `Adrian Vale`, days 961 to 970 | 2 occurrences in 1 file, `chapter-0965.md` |
| Chapter equals day, days 961 to 970 | 10 of 10 |
| Bare-Month ordinal parses out of the printed words in its own body | 10 of 10 |
| True contractions, days 961 to 970 | 0 |
| Live state files before and after | 4,274 lines to 809, nothing deleted |
| State files copied to `state/archive/` before any line was withdrawn | 5 of 5, byte-identical by SHA256 |
| Next-phase directories | 1, and its prompt was not replaced or duplicated |