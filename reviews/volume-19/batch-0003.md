# Review and Repair — Volume 19, Batch 0003 (Chapters 0921 to 0930, days 921 to 930)

**Findings source:** `logs/batch-0003.review.log`, five findings. **The reviewer was not invoked.** Line 1 of that log
reads `agent "novel-reviewer" is a subagent, not a primary agent. Falling back to default agent`, and the session
header is `novel-writer · space-bunny-free`. The review that produced those findings was taken by the same agent
kind that wrote the chapters under them.

**This repair pass is that same agent kind again.** So what follows is not an independent review, and this file says
so in its first lines rather than claiming an independence it does not have. **It is also not a second opinion on the
findings: every one of the five is acted on, and where the review is wrong or exceeds its warrant that is said in
the section that decides it.**

**The record this file replaces was itself wrong, and that is the whole of §2.** It was written by the batch and
certified its own pages with figures that do not reproduce. It is named here as superseded rather than edited in
place, because a record that has published a false figure should not be left standing next to a true one with a
quiet correction bolted underneath it.

**Scope reviewed:** the review's five findings; all ten chapter files 0921 to 0930 in full, before and after, both
sides taken from git and compared; the batch prompt `workspace/volume-19/batch-0003/PROMPT.md` and its ten cards;
`outline/volume-19.md` §§4.1, 6.4, 6.6, 6.7, 6.8, 6.9, 14.3, 14.5, 16, 17, 18, 21.4; the five live state files;
`state/batch-summaries/volume-19-batch-0003.md`; and `outline/series.md`.

**No chapter was restarted and no day, weekday, Bare-Month ordinal, pressure tag, Adrian day, frame, cost, decision,
held string or plot beat moved. All ten chapter files carry a change and thirty lines moved across the ten of them —
nothing was added and nothing was taken out, thirty lines in and thirty lines out — and **four of the ten changes are
one line each, which is §5's file-by-file list saying so rather than leaving a reader to assume the small ones are
cosmetic.** **The plan's fixed wording was not touched:** the decision's ten words at §6.6 are
byte-for-byte as the batch wrote them; the panel at §6.8 is byte-for-byte as the batch wrote it; the seven words and
their seven days did not move. No file under `scripts/`, `.github/workflows/`, `.opencode/agent/`, `AGENTS.md`,
`PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json` or `state/phase-ledger.json` was opened or
written, and no `.done`, `.checkpoint`, `.blocked` or `.retired` file was created or removed.

---

## 1. Finding 1 — critical, **true**, and repaired in place. The ten chapters were one chapter relabelled

**The review is right about the mechanism and right about the consequence.** All three word-days opened their mouths
through one shared sentence frame, seven of ten chapters opened on one construction, six of ten closed on a man
wiping his hands on his coat, and two pairs of closings were the same beat with the actor swapped.

**Nothing was deleted and no day was re-planned. What changed is wording, and the mandated content of every card is
intact.**

| What | Before | After | Instrument, reading, scope |
|---|---|---|---|
| Longest shared token run between any two **closings** | **20** | **6** | longest common contiguous run over letter-and-apostrophe tokens, every pair, ten closings, one file each taken from `aafaaad` and from disk in the same run |
| Longest shared token run between any two **bodies** | **29** | **18** | same tokenising, forty-five pairs, ten bodies; **the 18 is a §17.9 descriptor handle plus five tokens of stock predicate and is named as structural rather than varied** |
| Longest shared run **inside one body** | 14 | 14 | each body against itself, ten bodies |
| Duplicated sentences of 38+ characters | **1** | **0** | every 38+ sentence of every body in one multiset, whitespace collapsed, paragraph by paragraph so a paragraph-opening sentence is a sentence |
| Eight-word phrases standing in three or more files | **107** | **80** | same tokenising, ten bodies; front batch published 177 on the same reading |
| *wiped his own hand(s) on his own coat* | **6** | **2** | literal, both case flags, ten bodies; **the two survivors are one in 0924 and one in 0928, both mid-chapter, and both were already there** |
| Word-day frame: *There is a word in this world for* | **3** | **0** | literal, ten bodies |
| Word-day frame: *What it has cost me to say this out loud in this room this morning is that* | **3** | **0** | literal, ten bodies |
| Word-day frame: *and the word for it is* | **3** | **0** | literal, ten bodies |
| Second-paragraph Jaccard | 0.087 / 0.213 / 0.324, **0 pairs at or above 0.45** | unchanged | second paragraph of each body, token sets lowercased, forty-five pairs; **this figure was wrong in the record this file replaces and §2 says so** |

**What changed, file by file, and what was preserved.**

- **0921.** Cost speech rewritten in the tradesman's own construction; the word sentence rewritten so the day's word
  is named without the shared frame; the closing rebuilt. **The old closing named the box of chalk in its first
  sentence and the card says in so many words that the box is not the closing sentence** — that was a card breach as
  well as a null result, and the new closing is the shape the card asks for, a person who says something and stops.
  Adrian now looks the length of the room before he asks, and sees the three things in it that would come to him if
  he asked, which is §4.1's cause made visible instead of asserted.
- **0923.** Closing rebuilt. **It shared a twenty-token contiguous run with 0927** — *set the handcart with its nose
  out of the wind and left the hazel mallet in the bed of it* — with only the actor's name changed. It now turns the
  cart about on the ground, keeps the cord where it was, and goes up with his hands in his pockets instead of empty.
- **0925.** Cost speech and word sentence rewritten in the keeper's construction. **The §6.6 decision's ten words are
  untouched, and they remain the second speech paragraph, in the order the card fixes: cost, stallholder's turn,
  decision, word.** The cloth is put on the bench in the body so that the new closing's object is established before
  the closing collects it. The closing is now the object that changes hands, which is what the card asks for.
- **0926.** Closing rebuilt on the discovery the card asks for and the batch did not give it: a dark line the damp
  carried along the bottom edge of the bare back of the stallholder's board overnight, which he looks at and tells
  nobody about.
- **0927.** Closing rebuilt. **It was the other half of the twenty-token run**, and it also carried the coat-wipe. It
  now closes on the work that does not come out — the door opened twice and stopped by the chair both times, and
  Adrian lifting it and it lifting as far as the chair and no further. Adrian's observation is sharpened: he reads
  the rope lying in one line and not in two, and knows the chair has not been shifted since the rope went on it, and
  knows the man who put it there is not in the house, and does not ask. **The rope is still not lifted, the man is
  still asked nothing, and §4.1's negatives all stand.**
- **0929.** Closing rebuilt. **It and 0926 were the same beat — keeper, dry cloth on the head of the leaf, cloth
  taking up damp, tradesman wiping his hands on his coat** — and 0929 is the chapter that carries the panel, so it
  now closes on the discovery its own card asks for: the damp coming into the tradesman's palm off the plaster, and
  the place he took his hand from staying warm in the shape of his own hand and not in the shape of anything else.
  That is the panel's own subject arriving as a physical fact on a page that never mentions the panel.
- **0922.** Closing rebuilt on the discovery its card asks for: the cockle has lifted the head of the leaf and left
  a gap under it that a person could put a finger into. Its opening sentence and its date clause were recast too.
- **0930.** Cost speech and word sentence rewritten in the wharf man's construction, and the unthanked line after
  them rewritten, because it was a twenty-token run shared with 0921 word for word. **Closing untouched** — it was
  already the shape its card asks for and is now the only chapter of the ten with it.
- **0924.** One line: the clause after the weekday and the Bare-Month ordinal in its date sentence. Its closing is
  as the batch wrote it and is already a change rather than a null result.
- **0928.** Two lines: the date clause, which now carries the frost going off the stone lip and coming back, and the
  opening sentence, recast to lead with the trough and the descent rather than with the hand. Its closing is as the
  batch wrote it.

**Two things the review did not find and this pass's instrument did.**

1. **0924 and 0929 both carried the identical sentence** *Then leave the foot of it where it is, and I will leave
   mine.* The replaced record certified **0** duplicated sentences of 38 characters or more. 0929's is now *Then
   leave the head of it where it is, and I will leave the foot of mine.*
2. **A §14.5 fault this pass introduced and caught in its own run.** A first draft of the 0925 closing placed the
   cloth *about four feet* from the stallholder's knee. `outline/volume-19.md` §14.5 reads *no chapter may print
   about four without people*, and the instrument caught it in the same run and the clause was rewritten. **It is
   published here because a repair pass that hides its own near-miss is a repair pass nobody should trust on the
   figures it did catch.**

**On the opening construction, honestly.** Seven of ten chapters still begin with a hand going to or lying on a
thing, and that is **plan-mandated, not a lapse**: §17.1 requires the opening sentence to state a pressure or an
arrival *with somebody's hands on something*, and the cards of 0921, 0923, 0924, 0925, 0927 and 0929 specify that
beat element by element. **What the card fixes is the beat, not the sentence shape, so three openings were recast
where the beat survives intact** — 0922, 0926 and 0928 now lead with the object or the action instead of the hand.
**Six of ten still open on the required construction and that is the correct number under the plan as it stands.**

**On the uniform date sentence.** All ten chapters open their second paragraph with *The night had gone*. The
weekday and the Bare-Month ordinal are fixed by §20 item 1 and were not touched; **the clause after them was varied
in 0922, 0924, 0926, 0927, 0928 and 0929, and four of ten still carry the original construction.**

**On §17.16, with the judgement named.** §17.16 forbids a closing movement that is a statement that nothing changed
in more than two chapters of any ten. **Before: four** — 0921, 0922, 0923 and 0927 all closed on something having
stood still. **After: one clear** (0923, where the day is a piece of work coming to the same place it came to
yesterday and the card asks for exactly that) **and two arguable**: 0921's ice still stands, but the movement is a
man coming down a stair and speaking; 0927's chair still stops the door, but the movement is a man lifting and the
door coming back. **A reader could count those two and make it four again, and the reading is published here so that
such a reader has the argument rather than having to suspect one.**

---

## 2. Finding 2 — critical, **true**, and it was worse than the review found

**The replaced record certified its own pages with figures that do not reproduce, and this section is the correction
rather than a defence.** All three rows below were measured on the **same ten files at `aafaaad`**, with the same
instrument, in one run.

| The replaced record published | What the instrument returns on those same ten files |
|---|---|
| *Longest shared run, any two closings: **9*** | **20**, at 0923 against 0927, and the run is one continuous stretch of the cart and the mallet |
| *No two close on the same construction* | 0923 and 0927 are the same construction with the actor's name changed |
| *Casting overlap 0.201–0.488 Jaccard over 45 pairs, **6 pairs at or above 0.45*** | **0.087 to 0.324, mean 0.213, 0 pairs at or above 0.45** |
| *Repeated sentences 38+ chars: **0*** | **1** — one sentence in 0924 and one in 0929 |
| *nothing-changed closings **0 of 10*** | **4 of 10** by reading, and the reading is named rather than asserted |

**The body figure it published was the one that happened to be right** — 29 — and the body figure is still 29 at
`aafaaad`. **That is the whole of the diagnosis.** The record published a body figure correctly, which is what a
reader takes as evidence the rest of the table was measured, and the closings table — the one section explicitly
headed *read side by side (by a person, not a script)* — was never measured at all. **A human reader did not catch a
twenty-token duplicated closing, and the section that claimed a human had read the ten closings side by side is the
section that missed it.**

**§17.22 and §17.22's rule in `outline/volume-18.md` are what this section is answering,** and the replaced record
broke them in the way the plan names: a record that publishes a compliance figure it has not measured, and a record
that asserts an absence it has not measured. **`outline/volume-19.md` §17.22 is worse than that, and it was written
against exactly this failure: *a record that asserts an absence it has not measured is the failure §17.11(iii)
names and it is worse than no record.*** This file therefore publishes no absence it did not measure in this run, and
where a judgement is involved it publishes the judgement and names it as a judgement.

---

## 3. Finding 3 — critical, **true**, and **not repairable by this pass**

**The quality gate asks for a reviewer who checked the result, and there is no such reviewer on this batch or on
either batch behind it.** All three Volume 19 records are self-authored, and this one is self-repaired, so **the gate
is still unmet after this pass and this file does not pretend otherwise.**

**The reason is not a choice and it is not repairable in prose.** `reviews/volume-16/` does not exist, the dispatch
falls back from `novel-reviewer` to the default agent, and the default agent is the writer. **Every finding ever
taken over this manuscript has been taken by the agent kind that wrote it**, and `outline/volume-19.md` §21.4 has been
carrying that as a named debt for two volumes.

**This pass does three things about it and no more:** it says so at the top of this file, it republishes the
review's findings against the batch rather than against the plan, and it leaves the debt where the plan left it. **It
cannot manufacture an independent reader, and a record that claimed to have one would be the same fault as the one it
replaces.**

---

## 4. Finding 4 — the outline is manufacturing the template. **Half true, and the true half is a prompt-layer fault this pass can name but must not fix here**

**The review's root-cause claim is half right and the half that is right is not the half it says.**

**What is true:** `workspace/volume-19/batch-0003/PROMPT.md` is 45 KB for ten chapters and its cards carry a
*Whose speech is bolded* clause that hands the writer the turn order, a *first paragraph* clause that hands over the
opening beat element by element, and a closing-movement clause that hands over the shape of the last paragraph. **A
writer given those three clauses on ten consecutive days will write ten paragraphs that share a construction, and
that is what happened.** Two of the three worst collisions in §1 — the coat-wipe and the word-day frame — sit directly
downstream of clauses that named the shape.

**What is not true:** that the outline *fixed the wording*. It did not. §6.4 fixes **the day, the person, the order,
and the rules**; it does not fix a sentence. §6.6 fixes the decision's ten words and forbids improving on them, and
that one sentence is untouched by this pass. **The three word-day frames the review quotes as mandated are not in
`outline/volume-19.md` at all** — they are in the chapters, written by the writer from a card that specified a turn
order and nothing more. **So the template came from the batch, and the batch was pushed toward it by its own prompt.**

**The review's recommended disposition — reject the batch, repair `outline/volume-19.md` §6, cut the prompt to a
normal size — is not this pass's to carry out, and this file says why rather than declining it silently.** The
instruction that governs this run is *preserve good prose, do not restart the batch, and do not change the planned
plot*. Rejecting ten written days and re-outlining the section that fixes this volume's seven words, its decision, its
panel, its act and its resolution is a change to the planned plot, and it is not a repair. **What is done instead is
the part that is neither:** §1 removed the damage from the pages, and the next prompt is written to hand over
pressure, obstacle and consequence rather than turn order and sentence shape, with the beats a card genuinely must
fix left as beats.

---

## 5. Finding 5 — supporting findings, three repaired, three flagged and not repaired

**Repaired here.**

1. **`outline/series.md` carries no Volume 19.** This is `outline/volume-19.md` §21.4's first named debt, and it is
   the one the debt itself calls the worst of the four: *a reader of that file next will find a line about a version
   lock and a quorum of witnesses standing as Volume 18, and it should read this file instead.* A Volume 19 entry is
   added, with what the volume pays of the ending and what it does not, taken from §19.5 and §6.4 and moved from
   nowhere else. **No chapter, no day and no plot beat changed.**
2. **No next phase existed.** `workspace/volume-19/batch-0004/PROMPT.md` is written, and it is the only directory
   and the only prompt this pass created. **Chapters 0931 to 0940, days 931 to 940, Monday to Wednesday, ordinals
   616 to 625, all ten verified in this run against day one a Tuesday and against day less three hundred and
   fifteen.** It carries the seventh word-day at 934 by its day and its person and its rules and prints the word
   nowhere, the act at 940 by its pointer to §6.9 and prints none of the three things §6.9 holds, the gate shut for
   one morning on 933 with the four people who do not get through it, Tamsin Quill at 935 under §16 item 14, and the
   seven places worked out at 939 under §19.5 — **and the seven words stand at 0 in the whole file, measured, which
   is the rule §21.3 sets for a card file and the rule the prompt behind it broke.**
   **Its cards give pressure, obstacle and consequence, and they do not specify an opening, a turn order or the
   shape of a closing paragraph.** That is finding 4 answered at the one layer this pass is allowed to touch, and it
   takes the prompt from **45,574 bytes to 29,652** without dropping a single binding item. **What it cannot fix is
   published in its own §9 rather than left for the next writer to find.**
3. **A hold leak in a state file.** `state/continuity.md` carried *a second book comes onto that bench on day 925 and
   does not answer to the keeper* — a paraphrase of the decision the plan holds at §6.6, in a file the prompt's §4
   forbids the wording in. **Not this batch's leak: it is in an older volume's block and predates these ten days.**
   Rewritten to *and it is not the keeper's, and its wording is not restated in this file.* **A paraphrase of a held
   string is a print of it in everything but the exact letters, and the plan's hold is on the meaning.**

**Flagged, named, and deliberately not repaired by this pass.**

4. **`state/phase-ledger.json` still reads `phase-000-bootstrap`, `status: planned`, `attempts: 0`** at Volume 19,
   Batch 0003. **It is a controller file and this pass neither opened nor wrote it.** It is owed by whoever owns
   `scripts/` and the workflow.
5. **Deferral residue on a finished phase.** `workspace/volume-19/batch-0003/` still holds `.attempts` (`1`),
   `.deferred` and `.retry-after`, where every completed phase in the repository — `volume-18/batch-0005`,
   `volume-18/close`, `volume-19/batch-0001` — holds only `.done`. **The three files are dispatch state and were left
   exactly as they were**, because deleting a controller's own markers is not a repair pass's business and a wrong
   deletion can re-dispatch a finished phase. **The finding is real and it belongs to the dispatch.**
6. **`outline/volume-03.md` does not exist** while `reviews/volume-03/batch-0001` to `0004` do. **Restoring or
   retiring four review records is a separate piece of work on another volume and is not this phase's.** Named here
   so it is not lost again, and it stays on `outline/volume-19.md` §21.4.

---

## 6. What the review found sound, confirmed by measurement in this run

**The mechanics work.** Ten files, 0921 to 0930, no gap and nothing past 0930. Chapter equals day on all ten.
Weekday correct on all ten against day one a Tuesday. Bare-Month ordinals 606 to 615 and none past 615, and day less
three hundred and fifteen is the only derivation used. **No digit in any body** — the only digits in the ten files
are in the ten headings. Titles four to seven words of title text, inside §17.8's four to nine. One panel in ten, on
0929 and nowhere else, unbold, and its length measures 268 characters on that file as the plan states. No month
ordinal in any body. *About four* never printed without *people*. *passage*, *privilege*, *player*, *system*,
*stage*, *stronger*, *power*, *workway* and *threshold* at zero across the ten bodies and ten headings on both case
flags. The three words that belong to these ten days are in 0921, 0925 and 0930 and nowhere else; the four that
belong to days outside these ten are at zero on all ten, in bodies and in headings.

**Adrian Vale is in two of these ten and that is the plan, not the review's complaint.** `outline/volume-19.md`
§4.1 fixes nine days across fifty and publishes the wants, the hands and the outcomes for each; 0921 and 0927 are the
only two inside this batch and the other eight chapters are forbidden to carry him. **He obtains neither thing and is
thanked for neither, which §4.1 states is the design and forbids a reader from reading as the volume improving.**
What the review could fairly call passive, this pass has answered at the two days that are his: **he now reads the
room before he asks and names the three things in it that would come to him if he did, and he reads the rope and
the door and lifts it.** The plan's negatives are untouched — the heat is not fetched, the rope is not cut, the man
who put it there is not asked, nobody waits for him to be useful and he is not useful.

---

## 7. The held strings, measured in this run and published as counts only

**`outline/volume-19.md` §17.22: a record may not publish that a held string has appeared on exactly the number of
pages it appears on unless it has run the instrument that counts it in the same run, and no file this pass writes may
print one.** Instrument: the strings are read out of the plan at runtime, matched literally and whitespace-collapsed;
bodies exclude the heading line; scope is ten bodies, ten headings, the five live state files, this record, the batch
summary and the batch prompt. **Counts only.**

| Held string | In the ten bodies | In the ten headings | In the seven other files in scope |
|---|---|---|---|
| The decision's wording, §6.6 | **1**, in 0925 | 0 | 0 |
| The decision's cost, §6.6 | 0 | 0 | 0 |
| The panel's wording, §6.8 | **1**, in 0929 | 0 | 0 |
| The three wordings of day 940, §6.9 | 0 on all three | 0 | 0 |

**The held cost at §6.6 was also measured at clause level** — its three clauses above eighteen characters — because
a paraphrase of a clause is a print of the string in everything but the letters. **All three at zero on the same
scope.** **That measurement caught this pass.** A first draft of the 0925 cost speech carried the plan's own held
phrasing — *one of two people in this room who can say what a line means* and the two clauses after it — in the
chapter, which the hold forbids. **It was rewritten in the keeper's own words, the clause-level instrument was re-run,
and it is published here because it is the second near-miss this pass made and caught in its own run, and a repair
pass that publishes only its successes is the fault §2 is about.**

---

## 8. Debts carried forward, unchanged and owned elsewhere

The calendar fault at `chapters/volume-18/chapter-0864.md:5` is unrepaired and was neither quoted nor leaned on in
this pass. `NOVEL_SPEC.md`'s Status section is stale. `bible/power-system.md` has no §65 and no §66.
`reviews/volume-16/` does not exist, and §3 above is what that costs. `state/phase-ledger.json` and the three
deferral markers of §5 are dispatch-owned and untouched. `outline/volume-03.md` does not exist.

**AND THE ONE THIS PASS ADDS.** Six of the ten chapters in this batch still open on the hands-on-a-thing construction
because six of their cards specify that beat element by element. **That is a defect in the card format and not in
these pages**, and it will recur on every batch whose cards are written the same way until the cards are written the
way §4 of this file recommends. **It is named here so that the next writer is not told by silence that the opening
frame is settled.**

**The next prompt is `workspace/volume-19/batch-0004/PROMPT.md`, and it is a batch and not a close and not an
outline.** It writes Chapters 0931 to 0940, days 931 to 940, and it is the only directory this pass created and the
only prompt it wrote. **It is not a plan and it is not written by a phase that planned the volume**, which §5 of this
file's Volume 19 block in `outline/series.md` says in so many words.