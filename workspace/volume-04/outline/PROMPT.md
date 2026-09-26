# PROMPT — Volume 04 Outline, *The White Ledger*, Chapters 151–200

**This is an outline phase and it is not a batch. It writes no chapter prose. Volume 03 is closed at Chapter 0150 and its close record `state/volume-03-close.md` exists and is the inheritance. This phase writes `outline/volume-04.md` and the first batch's cards, and it creates exactly one next phase prompt, which is the batch that writes the prose.**

**Do not edit `scripts/`, `.github/workflows/`, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json`, or `state/phase-ledger.json`. Those are controller-owned. Only edit fiction, bible, outline, chapter, summary, continuity, character and open-thread files, and only the ones named below.**

**Do not edit Chapters 101–150, `state/volume-01-close.md`, `state/volume-02-close.md` or `state/volume-03-close.md`. There is nothing in them to repair and a repair pass that widens its own scope is how an outline becomes a rewrite.**

---

## Why this phase exists in writing rather than as a seeded stub

A review of the Volume 03 close phase found that the fallback continuation prompt in `.github/workflows/novels.yml` and in `scripts/novel_runner.sh` tells the next run to *plan the next volume and write its first 10 to 20 chapter batch, do not stop at an outline* — while `state/current.md`, `state/continuity.md` and `state/volume-03-close.md` all say there is no Chapter 0151 until an outline phase has run, and the generic stub never mentions `state/volume-03-close.md` at all. Those two instructions are in direct conflict and the generic one wins by default, because it is what dispatch hands over.

**This file is the resolution: the real prompt is authored, so the generic seed is not used.** The runner only writes its generic continuation prompt when no other incomplete phase exists, so the presence of this directory is what suppresses it. Do not delete it and do not mark it done by hand.

---

## What to read, in this order

1. `state/volume-03-close.md`, **in full and first.** It is one page and it is the volume's inheritance, and a writer who skips it will write Volume 04 as if Volume 03 had not happened.
2. The planning-state warning at the end of `state/continuity.md`, in full. It carries the five-beat check of Volume 03 against the page, and the four handoff facts below, of which two were wrong in an earlier draft and are corrected.
3. The *Live into Volume 04* block in `state/open-threads.md`, which is the current thread list.
4. `outline/series.md` and `outline/ending.md`. **Volume 04's plan is five lines in `outline/series.md` and the ending file is the authority on where this goes.**
5. `state/current.md` and `bible/power-system.md` §23. §23 is the standing rulebook for the whole manuscript's method, in twenty numbered findings, and Volume 04 is written under it.
6. Chapters 0131–0150 for voice. `state/chapter-summaries.md` and `state/character-state.md` for everything older.

---

## Deliverable 1 — `outline/volume-04.md`

One file, following the field list in `OUTLINE_GUIDE.md`: volume number, central pressure, starting state, starting relationships, starting power level, major locations, major factions, midpoint reversal, escalation sequence, volume climax, concrete resolution, new question for the next volume, final chapter image.

**The volume must resolve its own central promise.** The plan's resolution is a compact between two named communities and a rival who is still standing at the end. That is a resolution and it closes.

**The plan, verbatim from `outline/series.md`, and the outline is a plan for this and not for a version of it:**

- **Central pressure:** Jonah Pike establishes a successful, well-run player settlement that takes land, water and template access without local consent.
- **Midpoint:** Adrian's delayed response causes a local family to lose a water gate. He cannot solve the problem simply by declaring the settlement illegal.
- **Climax:** Adrian closes a profitable resource crossing and helps the Reed Commons recover the water gate, splitting the player coalition.
- **Resolution:** Redroot Commons and the Reed Commons establish a land-and-labor compact; Jonah becomes a serious rival.
- **Question:** How many people on Earth are disappearing, and who is exploiting the fear?

### The calendar has run out and this is the first thing to decide

**Day 154 is the sixty-fourth day of the month after this one, and the sixty-fifth day of that month is day 155, and nothing on a page establishes a sixty-sixth.** The two month forms in the book are the *Nth day of the new month* (days 26 to 90) and the *Nth day of the month after this one* (days 91 to 155), both sixty-five days long, and Volume 03 ended on the sixty-fourth of the second one. **So Chapter 0151 can be dated day 155 at the latest, and day 156 has no form, no name and no month.**

The outline must settle this before any card is written, in one of two ways, and say which it chose and why:

- **Carry the volume inside the sixty-five days**, using Chapter 0151 on day 155 and then a new month form established on the page by a chapter that is allowed to establish it. A month in this world beginning in the middle of a flood is a thing the manuscript can afford, and the flood has already turned the calendar over twice.
- **Or declare the second month sixty-five days and let the third month be named in prose**, in a room, by a person who has a reason to say what a month is called when the water has been up since the first of it.

**Whichever it is: the new form goes on the page in Volume 04 and not in an outline, it is registered in `bible/power-system.md` §23 as a date-form amendment, and no chapter may use a form that no page has established.** Never *of this month*, *of the month*, *of next month* or *of this new month*. *March* is a month and is never a date number.

The outline must also state the day range Volume 04 covers and the per-chapter day allocation, because the mapping is not one chapter to one day: Volume 03 ran fifty chapters across fifty-four days, and a chapter may cover two days and one did. **A weekday is a figure. Day 1 is a Tuesday. Recompute every weekday from day 1 and never from a neighbouring chapter and never from a day map.** The anchors that hold are day 49 a Monday, day 100 a Wednesday, day 130 a Friday, day 131 a Saturday, day 154 a Monday, **day 155 a Tuesday** and day 156 a Wednesday.

### Four handoff facts, and two of them were wrong the first time they were written

**All four were re-checked against the pages during the review of the close phase, and this is the corrected list. Do not take any version of it from memory.**

1. **Jonah Pike has not been on a page since Chapter 0097, which is day 97 — fifty-seven days before the close of Volume 03.** Chapter 0097 also says he *did not know it had been said and would not find out for about four months*, and that is about nine words said in a yard and is not a reason he may not appear. **He is the central pressure of this volume and he walks in.** Nine sentences, right in eight, the ninth about the seventeen, Adrian's tenth out loud and wrong, and Jonah has not answered.
2. **Redroot Commons has never been named in prose.** Zero occurrences in `chapters/`. The name is in `outline/series.md` and `outline/ending.md` and nowhere else. **The resolution of this volume is a compact between Redroot Commons and the Reed Commons, so the outline has to say where Redroot comes from, and that is a decision and it may not be made silently.** It may not be invented in a card and forgotten in prose; if it is a new place, the first chapter that names it has to be a chapter that is about somebody being told.
3. **The Reed Commons is on stage and has already refused once. An earlier draft of this handoff said it was one line in Chapter 0010 and that was false, and the correction matters because this volume's climax *and* its resolution both turn on the Commons.** It is five mentions across two chapters: three in Chapter 0010 as the receiving community with terms, a cost and a seat, and one in Chapter 0080, where **the Reed Commons' position hardened on a Thursday morning in a converted salt store, in a document that took about nineteen minutes, and it is the fourth page of a thing nobody has read end to end, and the fourth line is in it and it is Ilda Marsh's and it is in force.** Hessa Ruun is the water-count of the Reed Reach, not a notary and the closest thing the wetland has to one; she brought the answer of the meeting-ground at Verrow and read it out in about nineteen minutes, and it was a refusal of Adrian's page, refused on a principle and not on his person. Ilda Marsh is on stage across ten chapters and is seventy. Verrow is named in eight. **The Commons has a meeting-ground, a document, a named speaker and a refusal already on the record. It may not be introduced, founded, discovered or re-constituted in Volume 04, and it may not be written as a body that has never acted.**
4. **There is no water gate on a page, and a water gate is not an invented noun.** The phrase appears once in the whole manuscript, in a hypothetical in a speech at `chapters/volume-01/chapter-0029.md:65`, and it is a category in an argument rather than the name of an asset. **The category is in the bible and has been since Volume 01**: `bible/world.md` has the Reed Reach villages *maintain shared water gates* and has *Reed Common speakers record who may use a water gate*; `bible/themes.md` lists the Reed water gates as a recurring setting; `outline/volume-01.md` says the shared water gates *take the same river pressure as Saltwake's lower fields*. What has never happened is that any one of them has been given a name, a page, a keeper and a day. **The thing on the page is the fourth channel of a junction at Nine Elms: shut, the quarter gone, the fourth line of a term sheet in force, the document that would have paid for it void and no office told, and a village of nine households that has refused a fourth time with nothing under it.** The midpoint and the climax both turn on this, so the outline must decide whether that fourth channel is one of the bible's water gates or a different thing, and the decision has to be reachable in prose: **a chapter that establishes the identity has to establish it in a room, in daylight, with a date on it, and it may not be settled by narration.**

### Five things about the shape of the prose, from a review of all 150 chapters

**This is the part of the handoff a Volume 01 writer could not have had, and it is a set of instructions and not a set of permissions.**

- **A chapter may not open by summarising itself, and least of all its ending.** Chapter 0127's first sentence gives the reader the failure, the sixth attempt, the offer, the refusal and both counts. **The opening sentence of a Volume 04 chapter states a pressure or an arrival. It does not state the finding, and the finding is the thing the chapter is for.**
- **The bolded ledger paragraph is a data dump and it is in 46 of Volume 03's 50 chapters.** *The licence is N days old. The undertaking is void. The field was not paid. The fee is entered as owing. The black line in his palm is N days old and has not moved.* It recites and it does not dramatise, and it opens more chapters than anything else in the book. **Volume 04 must not open a chapter with it. The figures that matter to a chapter's argument go inside the scene, in a mouth, attached to a decision, or they do not go in.** Where a figure is genuinely load-bearing — a licence age, a day count, a palm line — it is paid for once in a chapter and then it is paid for again only when it changes.
- **The closing coda is a 200-to-400-word recap of the entire unresolved world and it is in 34 of Volume 03's 50 chapters, structurally near-identical.** This is the single largest drag on the prose in the manuscript. **Volume 04's codas are cut by at least half, and a coda may not enumerate the standing threads.** One thread, one image, one thing that changed and one thing that did not. **A chapter that ends on the sound of the book being recited has not ended.**
- **The "about N seconds" refrain is a motif and is declared as one, and it is at roughly 760 instances across 150 chapters — four seconds 181 times, nine seconds 145, nineteen seconds 119, nine minutes 134.** Declaring it did not reduce it. **Volume 04 uses it deliberately and sparingly: a motif repeated inside one chapter is two beats where there is room for one, and `Nobody said anything for about nineteen seconds` is the sentence to cut first, because it is the one that has been used as a beat inside a single chapter and Chapter 0127 did it twice.** A pause that matters is a thing a person does with their hands.
- **Characters are age and trade only, and the device is now generating errors.** Nine near-identical descriptors is a cast a reader cannot hold, and it has already produced a phantom: for four chapters of Volume 03 a state file listed a ninth person, *a man of about thirty-four who keeps a stall by the wharf*, who does not exist, produced by one wrong word in Chapter 0149. **Volume 04 gives the people who carry the volume a second handle** — a name, a habit, a piece of clothing, a thing they do with a pen — **beside the age and the trade and never instead of it.** Adrian Vale's ninth name is a thing the reader is owed in this volume and the outline should say who has it.

### What the volume inherits, and may not resolve by accident

`state/volume-03-close.md` §3 has ten items and §4 has the prohibitions. Four of them shape this outline directly:

- **The quarter.** The hearing was on day 154 and the next time this city can put anything in front of the office that held it is about five weeks from the hearing, and there is no road in this world that reaches that building. **That interval is the engine of the first movement and it is the only clock in the book running towards something.** The outline should use it and should not replace it with a faster one.
- **A man outside every office who holds nothing and who said out loud, in front of about two hundred and forty people, that a man with no mark and on no roster is the most findable person in this world, and that this is not a safety and he knows it.** He is the reason the first movement has a person in it. **A chapter that needs him to be safe is a chapter that has misread him.**
- **The provisional recognition, which is revocable, in no book, and describable as not recognised, and the compact whose fifth line is a person.** These are the instruments the volume's land-and-water arguments are conducted in, and the compact is the only one anybody in this city can end.
- **Day 198: the Hattie Park counter is spoken zero times in Volume 03, is written once in a book on a trestle in his own hand, dated and not read out, is one hundred and fourteen on the hearing day, and his room is on day 198, which is about six weeks off.** It is not due yet and the outline should say when it falls and what it costs.

**And these stay untouched: Owen Park at zero mentions and no *he died because*; the room at the far end of the Narrow Mark, unlooked at in four batches; the boards under the chapel, not lifted since the fortieth day of this flood; the chapel stone, silent for a hundred and fifty-four days; the scar; three knocks and four knocks, entered, neither deleted, unused, unreported, unmentioned; the box, thirty-eight days in a room with a door with its strap untied; the eight names, unread; the page that ends a document, which may not be explained before Volume 06; and the fourteen shapes, which never collapse into one another.**

**The word *knock* does not appear once in Chapters 131–150 and the correct number of times in Volume 04 is also zero.**

**Jonah Pike's settlement being *successful* is the hard part of the plan and the outline must not sand it off.** A settlement that is badly run is a villain with a schedule. A settlement that is well run, that pays its people on time, that has clean water and a queue that works, and that takes land without asking, is the argument this volume exists to have, and **Adrian cannot answer it by declaring it illegal, because the settlement is not obviously illegal and the four Elms matter more to a family than the law's opinion of a boundary.** He has no office, no roster, no standing, no mark, no seat and no wage, and he said so himself.

---

## Deliverable 2 — `outline/batches/volume-04-batch-0001.md`

Ten to twenty chapter cards for the first batch, using the card fields in `OUTLINE_GUIDE.md`. **Choose a range and justify it in the file.** The default is 10; a first batch of a new volume that has to establish a settlement, a rival, a date form and a lost water gate is a reasonable place to take twenty, and the volume's day budget is 46 days to 155 and however many the new month gives after that.

Each card gets a beginning that continues pressure, a goal that can be stated, resistance, a meaningful change, a completed beat and an ending that creates a new question, decision or cost. **No card may be an outline of a chapter. A card is a plan for a scene, not a summary of one.**

**Rotate the pressure across the batch.** Volume 03 ran heavily on political and procedural pressure with a great deal of recitation. Volume 04's first batch should carry at least one chapter of physical work, one of recovery, and one relationship chapter that is not about a form.

---

## Deliverable 3 — exactly one next phase prompt

**Create `workspace/volume-04/batch-0001/PROMPT.md` and nothing else.** It is the batch that writes the prose this phase has planned. It must name the chapter range, the batch goal, the beats, the files to read, the state files to update, the date and weekday rules, the prohibitions it inherits, the five prose instructions above, and the word-count band.

**Then update the state layer so that every file points at it:** `state/current.md`, `state/continuity.md`, `state/open-threads.md` and the new `outline/volume-04.md` must all end naming the same next phase. Record the new date form as an amendment in `bible/power-system.md` §23 if the outline settled it, and record the four handoff facts with the corrections above rather than the versions they replaced.

**Do not create a second next phase, a continuation directory, a volume-04 batch-0002 prompt, or any chapter file. Do not write a paragraph of Chapter 0151.**

---

## The rule this phase must not break

**An outline is a plan, and it does not answer anything.** The box is shut. The eighth column's question is on a desk nine hundred miles away and what comes back from it is a number and the reading of that number is not Adrian's. The six rooms are six and the page that ends a document is not going to be explained. The delegation has not left and nobody has been asked whether they will go and the only instruction it has is *to open nothing*, and that clause belongs to the woman of twenty-nine.

**And a card that names a place this city has never been to is a plan for a discovery, and a discovery in this book is a room, in daylight, with a date on it, and somebody in it who does not want to be asked.** Redroot Commons and the water gate are both exactly that, and the reason this volume is worth writing is that a man who has given up the only thing he is good at as a way of being needed has to go and find out about them with nothing to stand on.
