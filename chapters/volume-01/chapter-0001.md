# Chapter 0001 — The First Rule

The build server had been gone since four o'clock, and by two in the morning Adrian had run out of things to do about that.

He had a workroom with one lamp on a scissor arm, three dead monitors, a fourth that flickered because the cable under the desk had been pinched for a year, and a plant he had bought in a fit of optimism eighteen months ago that now existed as a stick in a dry pot. There was a window that looked out onto a carpark and a service alley and, if you craned, the underside of the overpass. Somewhere in the first week of March, sunlight had actually reached this desk. He had noticed because it had made him squint, and he had thought at the time: this is the wrong building for a person who wants to believe work matters.

The coffee had gone cold twice. He drank it anyway, because the microwave was in the kitchen and the kitchen was where Marisol held her calls, and Marisol was on a call with someone in Toronto who kept saying *let us circle back*.

He was trying to finish the onboarding for *A Crown of Ash*.

The game was a historical-fantasy multiplayer title about a succession crisis in a made-up empire. Adrian had spent two years on its permission layer: who could take what, who had to sign for it, what happened when two people wanted the same land, and how the game was going to tell a man holding a sword that the man with the sword did not get to decide where the boundary was. He had argued for a long time about that boundary, in meetings that were mostly him talking and someone above him saying *we hear you*.

At 1:14 a.m. he had found a commit that removed the entire `permissions/` tree.

Not edited. Removed. Not even stubbed, not even flagged as deprecated. Someone had gone into the repository and deleted two hundred and eleven files, and the diff of the deletion was clean, and the message under it was `Takedown — see ticket`.

The ticket did not exist. He had checked. He had checked twice, once in the tracker and once by guessing the URL, and the second one gave him a login page and a feeling in the base of his stomach that he did not like at all.

At 2:06 a.m. somebody at Morrowglass had sent an all-hands calendar invitation for nine o'clock, subject line `Re: A Crown of Ash — all-hands`, and then, eleven minutes later, changed the subject to `A Crown of Ash — cancelled`. Adrian sat with both of them in his inbox like two versions of the same event.

He opened the onboarding document on the flicker monitor. It was a permissions screen he had been refining for six weeks, and it was the only thing in the project that had ever made him feel like a person rather than a component. The screen asked a player to accept three conditions before a server would let them take anything. It was not a wall of legal text. It was, he had told the room more than once, the only honest part of the product.

He had a rule he had written into the design ledger six months ago, in a document called `ACOA_PERM_LEDGER_LOCAL_ONLY`, whose filename he had chosen specifically to make sure nobody would ever open it by accident. The rule was this: never ask anyone to accept a term whose cost they cannot see. He had a joke underneath it, a note-to-self, the sort of thing he would never put in a build:

> a door with nobody on the far side is not a door, it is a receipt

The cursor blinked in the middle of the permission screen he was supposed to be finishing.

Then the flicker monitor changed.

It was not a window. It was not a new tab. There was no taskbar entry, no title bar, no browser chrome, and he had a rule against installing anything on the office machine, so it was not something that should have been able to appear at all. The text simply arrived in the middle of the dark field of the dead canvas, in a pale grey that was not quite white, laid out with a small amount of care and no branding at all.

> A LIMITED EARTHSIDE TEST
>
> Put your name in. The body follows.
>
> There is no promise of a road back.

He read it three times.

His first thought was that it was a build leak. Some renderer bug had decided to draw the permissions UI in a place with no permissions to govern, and the words had come out of the string table where he kept the tone rules. He had written those rules. He knew the strings. Those were not his strings.

His second thought was Ravi. Ravi had left in January for a studio that was definitely doing a live-service thing, and Ravi's idea of a prank had historically involved renaming Adrian's local branches, which had once cost him a full day and produced the phrase *I am not paid enough for this*.

He leaned forward. He put his hand on the keyboard, and the cable under the desk pinched, and the monitor flickered, and the text was still there.

There was no header. No publisher. No version, no client, no ticket, no copyright line. He checked the task manager, which he had never once in four years had a reason to open on a build machine, and it showed the same processes it had shown an hour ago. He opened the folder where the build lived and the folder was empty. He hit refresh. Empty. He went hunting for the filename he had half-invented and Windows told him, politely, that it could not find it.

It had no target. That was the first thing he actually understood about it, and it arrived in his chest before his head. He had spent his entire professional life putting targets in. A permission with no target is not a permission for a place. A permission with no date cannot be scheduled. A permission with no way to run it twice is not a service, it is a *one-shot*, and no responsible system has ever shipped a one-shot to a person without a preview.

And there was no second one. There was no "and then." There was no way to find out what would happen before he agreed, because there was nothing to agree *to* except a sentence that asked him for his name.

He typed: `what is this`

The field did not respond. He typed: `who are you`

Nothing.

He got up. He walked the length of the workroom and back, past the dead monitors and the plant and the mug, and he put his hand on the door handle to see whether the office still felt like a building, and it did, it was freezing and smelled of the carpet cleaner and somebody's leftover curry, and when he came back the text was still there and he sat down and understood that he had already decided something, and that the deciding had happened in the part of his body that is older than his reasons.

His phone had lost signal at some point in the last hour. He noticed it while he was in the middle of a thought about the acceptance screen and took it personally, the way he took things personally, which is to say he made a small noise of disgust and put it in his drawer.

He thought about his sister. Nora would be awake, she was always awake at unreasonable hours because she ran a mutual-aid logistics rota and believed sleep was a privilege granted by competent people. He had three missed calls from her, all on the eleventh, all of them the same shape: *call me when you can. no rush. call me when you can.* He had typed back *sorry, deep in a build, you know how it is* and then had not called, and he was not going to call now, not at two in the morning, not to say *I have accepted a door from nowhere on a night when the project was cancelled and my job may not exist.*

So he typed his name.

His legal name. Not Vale, not adrian.vale, not the handle he used on the forums where he argued with people about tutorial design. Full, first and last, the way it would appear on a form that mattered, typed with the shift key down for the second half because he had always thought that if he was going to do something irreversible he should at least have to hold the capital key down while he did it.

His name went into the field under the last line, and the three lines above it did not change, and did not thank him, and did not add a sixth thing about what would happen next.

He thought, with the clarity people sometimes get in the last second before something, that this was the first time in his adult life he had been asked to agree to something he could not audit, and that he had spent his whole working life building systems specifically so that nobody would ever have to agree to one of those, and that the moment someone put one in front of him his first instinct had been to look for the *publisher* rather than the *price*.

He pressed enter.

There was no success message. He had wanted one. He had wanted a spinner and a cheerful line and a small green confirmation, because that is what a well-designed system gives you, and instead the text simply stayed on the screen for another half second, unmoving, unbilled, unanswered, and then the lamp on the scissor arm went out.

Not flickered. Went out, all at once, the way a lamp goes out when the circuit is cut rather than when the bulb fails.

The workroom was not dark. There was light coming from the monitor still, pale grey, from the sentence that was still on it, and there was the green standby dot on the tower, and there was a stripe of orange sodium streetlight through the window, and Adrian turned around in his chair because the sound had changed.

Running water.

Not a tap. Not a toilet two floors down. Not a rain gutter. The sound was close and enormous and moving, a whole weight of liquid going over stone somewhere within a few feet of his head, and it had a texture that tap water never has, a drag and a slap and a hiss of spray, and under it, further off, something made of metal was taking the weight.

He stood up. The chair went over behind him and he did not pick it up.

The lamp came back on.

The monitor showed the permissions screen, his document, his cursor still blinking in the middle of the sentence he had been editing for six weeks. The folder was empty and the folder had always been empty of the file he had invented. The coffee was cold. The phone in the drawer showed one bar and then, as he watched, none at all.

He put his right hand flat on the desk to steady himself and felt something under it that was not on the desk.

It was on his palm, low on the heel, the size of a thumbnail, and it was warm the way a fresh stamp is warm, and when he lifted his hand there was a pale mark there with a fine branching line in it, like the pattern in a river delta seen from a very great height, or like a thing that had been pressed into his skin rather than drawn on it.

It did not hurt. That was somehow the most frightening part. He had braced for pain and gotten a temperature instead, an ordinary human warmth in a place where nothing had been warm all night.

The running water did not stop. It got closer.

Adrian Vale stood in the middle of a dead build in a building where nothing had ever happened, with a name on a screen he could no longer find and a mark on his hand that had no publisher behind it, and he thought, with a clarity that would embarrass him later: *I should have asked who pays for this.*

Then the sound of the water came up around the walls, and the floor of the workroom was cold under his shoes, and the room was four floors above a carpark that had never held any water at all.
