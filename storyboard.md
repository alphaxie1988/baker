# STORYBOARD — "You didn't stop baking. You started running the kitchen."

**Audience:** internal — colleagues being introduced to working with agents
**Art direction:** Blueprint → Recipe Card
**Scope:** 15 scenes + 1 separator + appendix
**Spine:** cake = the output · recipe = the instructions · kitchen = the tools

---

## TONE — the stance of the piece

**Objective: the reader leaves believing the shift is real, that it is in their favour, and that the work of rethinking how they work is theirs to start.**

- Not a warning. Not a sales pitch. **An invitation to rethink.**
- The shift is already here — say it plainly, once, early, and don't dwell on it.
- AI is on the reader's side of the table. It came for the parts of the job nobody wanted.
- The ask is never "be afraid." The ask is: **the way you worked for twenty years is now the slow way — so change the way you work.**
- No prediction, no hype, no condescension. Everything in the piece is something the reader could act on this week.
- The honest beats (what's lost, what shouldn't be automated, judgment doesn't transfer) exist to make the optimism *credible* — not to undercut it.

---

## COPY STANDARD — written for someone who has never worked in IT

The reader is a colleague, not an engineer. Every line on the page has been through a plain-English pass.

- **No jargon on the narrative surface.** Not "break-even", "prior art", "acceptance criterion", "granularity", "compute", "superseded", "cleared the bar", "resourced". If a word would stop a reader who does not work in tech, it is the wrong word.
- **The glossary explains, it does not label.** Every card's answer is a sentence in plain English. Where the technical term is genuinely worth knowing, it is named inside that sentence — *"a setting called temperature"*, *"making things up, confidently — called hallucination"* — never left standing on its own.
- **Two terms are defined on the page, on purpose:** *agentic AI* (at S-REV: "AI that does not just answer questions. It does the work.") and *evals* (at S10: "the same judges, the same score sheet, every batch"). Nothing else assumes prior knowledge.
- **Plain does not mean flat.** The metaphor, the rhythm, and the short declarative lines are the voice. Simplifying meant cutting jargon and long sentences, not the character.
- **One idea per beat, and no beat that restates its neighbour.** The page has been through a cut pass: the narrative lines lost about a third of their words, and four whole beats went because they said what the beat above them already said. If two lines make the same point, the sharper one stays and the other goes — do not "balance" a scene by keeping both.
- **The glossary earns its density, but not duplication.** 77 cards became 58. Every cut card was a second way of saying a card that was already there (three separate cards for "a cluttered bench", two for "look it up rather than memorise it", two for "too many tools"). Density is fine on the wall; repetition is not.

---

## ART DIRECTION — the page bakes

> **The page opens as an aged sepia plate, is reissued as a cold technical blueprint, and ends as a warm, used, stained recipe card.**

Three acts, three palettes. Scroll drives the whole system.

- **Act I — OLDEN (S0 → S-REV):** an old photographic plate. Ground `#1e1a15`, ivory ink `#e4dac6`, brass linework and accents `#c9a05a`. **The blueprint grid is all but absent** — old paper has no rulings. This is the world before you could change anything.
- **The switch — at S-REV:** the palette flips the instant the revision triangle passes the centre of the screen. The grid *arrives*, brass turns to cyan, the plate becomes a live drawing. The page is literally reissued at the moment agentic AI is named.
- **Act II — COLD (S3 → S9):** blueprint. Ground `#0b2030`, cyan grid, white patent-style line drawings, hard geometric type.
- **The one exception — the aged cutting.** S3's *prior art* half keeps the Act I palette as a scoped inset: an opaque sepia block, rotated `-.45deg`, dropped onto the blueprint page with the grid running behind it. A patent drawing cites prior art by pasting in the older drawing, so the past is quite literally pasted onto the present. Its headline is set smaller than the page's own, because it is a reproduction, not the page speaking.
- **Act III — WARM (S9 → end):** the oven comes on, the grid fades, paper warms to kraft `#efe3c9`, linework gains weight, red-pencil annotations appear. Coffee rings, a thumbprint, a smudge of flour. The document has been *used*.

The arc is **colourless past → cool technical present → warm human end.** The sepia act reads as old by desaturation, not by warmth, so it never competes with the warm ending.

Palette: paper `#f4efe4` · ink `#232323` · blueprint cyan `#1e4d6b` · annotation red `#c1442e` · crust gold `#c98a3c`
Type: technical mono for labels and measurements · warm serif for narrative lines · handwriting face for margin notes.
Every diagram is patent-drawing-style SVG — dimension arrows, leader lines, part numbers (FIG. 1, FIG. 2…). All authorable in code, no photo sourcing.

---

## SCENES

### S0 — HERO
- **Visual:** Blueprint title block bottom-right: `DRAWING NO. 001 · SUBJECT: CAKE · DRAWN BY: YOU`. Faint cyan grid. A cake in exploded technical projection, dead centre, thin white line.
- **Parallax:** grid (still) / cake (slow) / dimension lines (fast, cursor-reactive).
- **Copy:** `You used to make the cake.` + oven-dial scroll cue.

### S1 — THE HANDS LEAVE
- **Visual:** Two drawn hands over the bench. Scroll lifts them out of frame; the dough keeps being worked by nothing.
- **Parallax:** scroll-scrubbed SVG path morph.
- **Copy:** `The work still gets done. Just not by your hands.`
- **Second beat, on scroll-out:** `That isn't a threat. It's the offer — and you only collect it if you change how you work.`

### S2 — THESIS
- **Visual:** Bare paper. Type only.
- **Copy:** *Your job used to be doing the work. Now your job is making the work doable — by something that has never tasted cake.*
- **Second line, smaller:** *Which makes the way most of us have worked for twenty years the slow way. That's the whole reason this page exists.*

### S-TRAY — THE TRAY YOU ALREADY HAVE   ← NEW
> *Most of what you bake is already automated. It's the tail that eats your week.*

- **Visual:** `FIG. 2 — THE TRAY.` A shelf of every cake the bakery makes, sorted by how many people want it — cake **height encodes demand**, so the row is a decay curve drawn as cakes. The three tallest (payroll, invoices, month-end) are solid line, bracketed `AUTOMATED YEARS AGO`. A dashed vertical marks `WHERE THE ENGINEERS RAN OUT`. Everything right of it is a long tail of faint dashed cakes, bracketed `STILL MADE BY HAND`, the arrow running off the edge of the drawing.
- **Parallax:** the tail arrives one cake at a time on scroll, smallest last; a leader line then picks one out and labels it **YOURS**.
- **Copy beats**, under two headings — `WHAT IS ALREADY AUTOMATED` and `WHAT IS NOT`:
  - The cakes everybody orders were automated long ago — payroll, invoices, the month-end report. Someone wrote that recipe once, and the whole building presses the button.
  - What's left is **your** cake. Odd shape, twice a month, wanted by nine people. Still done by hand, still eating your Thursday.
  - Nobody built it because it was never important enough. There are only so many engineers, and they go to the cakes with the most people waiting.
  - **And that will not change.** IT will never have enough people to build everyone's cake.
- **Margin note:** *"nobody said no to your cake. there were just never enough people who wanted it."*
- **Landing line:** *So it stays hand-made — unless the people who want it can bake it themselves.*
- **Why it's here:** it sets the *stakes* before S3 explains the *mechanism*. Without it, "you can now change the system yourself" is a capability with no problem attached. With it, the reader already knows which cake of theirs is sitting in the tail, and that nobody is coming to bake it.

### S-REV — REVISION B   ← NEW (separator)
> *A breath, not a scene. The hinge between "nobody is coming to bake it" and "you can bake it yourself."*

- **Visual:** A drafting **revision block**, dead centre on bare paper. A thin dimension rule with the standard revision triangle at its middle, carrying the letter **B**. Nothing else on the page.
- **Parallax:** the triangle fades up first, then the rule draws outward from it in both directions at once.
- **Copy — three lines, and no more:**
  - `AGENTIC AI` (mono, accent, wide-tracked)
  - *AI that does not just answer questions. It does the work.* — **this line is the page's definition of "agentic"**, and the only place the term is explained. It replaced a more literary line ("the scarce ingredient stopped being engineers") because a reader who does not work in tech needs the definition more than the callback.
  - `REV. B — DRAWING 001 REPLACED` (mono, faint)
- **Height:** ~58svh. Deliberately shorter than a full scene so it reads as a beat, not an argument.
- **Carries the palette switch.** Act I's sepia holds until the triangle passes screen centre, then the page snaps to blueprint around the still-visible revision block. The snap is deliberate — a revision is a reissue, not a dissolve.
- **Why it's here:** S-TRAY ends on a dead end — the tail will never be resourced. S3 then explains the unlock in full. This marks the moment *between* them without spending it: it names the invention, pays off the hero's `STATUS: SUPERSEDED` title block, and lands the callback to "engineers are the scarcest ingredient in the building." It states **that** the constraint moved, and leaves **how** to S3.

### S3 — THE TICKET YOU NO LONGER FILE
> *The recipe card used to be behind glass.*

- **Split across two palettes.** Everything up to and including the glass case sits inside the **aged cutting** — sepia, rotated, pasted on. `NOW` and the line that follows it sit on the blueprint page itself, in cyan. The scene argues by colour before it argues by words: the past is a thing stuck to the page, the present is the page.
- **Visual:** A recipe card locked in a glass display case, with the ticket stack scattered over it — `RECEIVED · QUEUE POSITION 47`, `REOPENED · "not what I meant"`. Each ticket's scatter angle lives on an inner layer so the parallax transform can't overwrite it.
- **Parallax:** glass pane on its own layer with a specular sheen tracking the cursor. Ticket stack falls away fast.
- **Copy beats:**
  - For thirty years, if the system didn't do what you needed, you couldn't change it. You **described** it — to someone who could.
  - You filed a ticket. You waited. You explained it twice. You got back something adjacent to what you meant.
  - The gap between *knowing what you needed* and *being allowed to build it* was a person, a queue, and a language you didn't speak.
  - Natural language closed that gap. **The people who use the system can now shape the system.**
- **Margin note:** *"the requirements were never the hard part. the translation was."*

### S4 — THE BATCH DECIDES   ← NEW
> *You don't write a recipe to bake one cake. You bake it.*

- **Visual:** `FIG. 4 — BREAK-EVEN BATCH.` A technical cost chart, drawn line by line as you scroll.
  - **Doing it yourself:** a straight diagonal from the origin. Ten cakes, ten times the hours. No leverage, ever.
  - **Teaching an agent:** a tall vertical setup cost, then a near-flat line running right across the page.
  - The two lines cross. The crossing point is marked with a dimension arrow and labelled `BREAK-EVEN`. Scroll past it and the flat line just keeps going, off the edge of the drawing.
- **Parallax:** the chart's x-axis extends as you scroll, so the flat line visibly outruns the diagonal — the argument is made by the motion, before anyone reads a word.
- **Copy beats:**
  - Teaching costs more than doing — **once.** That is not a flaw in the deal. That *is* the deal.
  - Three things justify the setup: **volume** (many cakes), **recurrence** (the same cake every Tuesday), and **absence** (it must be baked when you are not there).
  - A cake is a variable cost. **A recipe is a fixed cost that keeps paying.**
  - The two mistakes are mirror images. Automating a one-off is fun and wasteful. Hand-baking the same cake four hundred times feels like honest work and costs the most of all.
  - The one you should notice: nobody files a ticket about the second kind. It looks like being busy.
- **Margin note:** *"the first cake through the new process is always slower. that's setup, not failure."*
- **Honest beat:** *And some cakes should never be automated. The one you make for your kid's birthday — the making of it is the point. Know which cakes those are.*
- **Why it's here:** it gates everything after it. Without this scene the three points read as "always do this." With it, they read as "here is what to do once you've decided it's worth it" — which is the version people actually trust.

### S5 — CHAPTER CARD
- **Visual:** Three pencil marks in the blueprint margin, `FIG. 5.1 / 5.2 / 5.3`, counting in on entry.
- **Copy:** `Three things you now own.`

---

### S6 — POINT ONE · THE PHOTO ON THE BOX
> *You must know what "done" looks like.*

- **Visual:** The cake starts as a rough construction sketch — guide circles, crossed-out attempts, no detail. Scroll resolves it into a finished rendered drawing. Focus-pull via linework density, not blur.
- **Copy beats:**
  - An agent always produces *something*. It never comes back empty-handed.
  - Without a target, "something" is your result.
  - You cannot outsource a standard you never wrote down.
- **Failure beat:** an immaculate second drawing slides in — perfectly executed, and wrong. Blue frosting on a wedding cake. Stamp: `AS SPECIFIED.`
- **Margin note:** *"'make it nice' is not an acceptance criterion. it's a hope."*

### S7 — POINT TWO · THE RECIPE
> *You must be able to break it down.*

- **Visual:** The cake explodes into an exploded-assembly diagram — flour, butter, eggs, heat, time — numbered with leader lines, then reassembling into a numbered method.
- **Parallax:** each exploded part carries its own scroll speed, so the assembly separates and re-converges.
- **Copy beats:**
  - "Make a cake" is a wish. "Cream butter and sugar, 4 minutes, medium" is an instruction.
  - **Mise en place:** everything measured and laid out *before* the heat goes on. The professional's whole advantage is front-loaded.
  - Sequence is not decoration. You cannot ice a hot cake.
  - **Checkpoints:** every good recipe says *"until golden brown."* That is a test. The toothpick is a cheap check that tells you the expensive step worked — before you commit to the next one.
- **Interactive — the granularity dial:** a slider styled as a measuring jug: `"Bake a cake"` → `"180°C, 25 min"` → `"Rotate the tray 90° at minute 22"`. Too coarse and it invents. Too fine and you're baking by hand, through a translator. **The skill is the middle.**

### S8 — POINT THREE · THE KITCHEN
> *You must give it the tools.*

- **Visual:** An unlabelled blueprint floor plan. Scroll lights each station in cyan with a callout:
  - Mixer → **APIs / actions**
  - Oven → **compute — the thing that actually executes**
  - Scale → **access to real data**
  - Timer → **monitoring & logs**
  - Pantry → **context: your docs, your codebase, your standards**
- **Parallax:** the plan rotates toward perspective as you scroll — the drawing stands up into a room.
- **Copy beats:**
  - The best baker alive, with no oven, produces batter.
  - Agents don't announce the wall they hit. They improvise around it. That is worse.
  - **The oven that was never switched on.** Everything looks right until you cut it open. Most agent failures are this shape.
- **Permissions beat:** one cupboard drawn with a padlock, hatched out. `Some doors stay locked. That's a decision, not an oversight.`

---

### S9 — THE FAILURE GALLERY
- **Visual:** Three specimen drawings pinned side by side, horizontal scroll, each red-stamped `REJECTED`.
  1. Beautiful, wrong cake → **no end goal**
  2. Raw in the middle → **no breakdown**
  3. A perfect bowl of batter → **no tools**
- **Interaction:** hover/tap peels a flap to reveal the diagnosis in handwriting.
- **Why:** the screenshot scene, and it retro-proves the three points are exhaustive rather than arbitrary.

### S10 — THE TASTE TEST
- **Visual:** One fork. A bite missing from an otherwise perfect technical drawing — drawn as a jagged tear in the paper itself.
- **Copy:** *You still have to taste it. Judgment is the one thing that doesn't delegate — and it is exactly why you still need to know how to bake.*
- **Extra beat:** the taste test, done properly, has a name: **evals.** Same judges, same score sheet, every batch. One person's opinion once is not quality control.
- **Margin note:** *"the head chef who hasn't made a genoise in five years can no longer tell when it's wrong."*

### S11 — THE PROMOTION
> *Nobody applied for this job. Everybody got it.*

- **Visual:** A blueprint org chart. One box: **YOU**. Scroll, and boxes branch beneath — four, then eight — each an agent with a station assignment. Your box stays the same size. Your title changes.
- **Parallax:** the chart grows downward faster than the page scrolls, so it outruns you. Deliberate — that's the actual feeling.
- **Copy beats:**
  - You were an individual contributor. Your value was your output.
  - You now have a team. Your value is your team's output.
  - Everything that was ever hard about management is now your problem: **defining done. Splitting the work. Unblocking. Checking quality. Knowing when to just do it yourself.**
  - Which is the whole argument, arriving late: those three things you now own are not three tips. **They are a job description.** Setting expectations. Delegating. Resourcing your team.
  - Nobody sent you on the course. **We are all being promoted to manager — of agents.**
  - It is the best promotion most of us will ever get. It just didn't come with the training. So here it is.
- **Margin note:** *"an IC with ten agents is a manager who still has to know how the work is done."*
- **Honest ledger — two columns, old crossed out in pencil:**
  - **Lost:** flow. Craft. The smell of it. Knowing in your hands when the dough is ready.
  - **Gained:** ten cakes instead of one — and the ability to bake things you were never trained to bake.

### S12 — CLOSE
- **Visual:** The full drawing, now a warm stained annotated recipe card. Coffee ring. Thumbprint. The floor plan behind it, every station lit.
- **Copy:** `You didn't stop baking. You started running the kitchen.`
- **Landing line, smaller:** *The kitchen changed. The question was never whether you can still bake. It's whether you've rethought how you work in it.*
- **The Monday card** — the CTA, three lines, deliberately small enough to actually do:
  1. Pick one thing you do every week. Not the hardest thing — the most repeated thing.
  2. Write down what "done" looks like. In sentences. Before you touch anything.
  3. Write the recipe once. Then stop baking that cake by hand.
- **Footer:** the three points as a clean takeaway card, built to be screenshotted.

### S13 — APPENDIX · THE REFERENCE WALL
- **Visual:** A cork wall of pinned index cards, each one an analogy. Scattered, slightly rotated, browsable. Click a card to flip it.
- **Placement:** *after* the close, clearly marked as extra. The essay ends at S12; this is the reference you come back for.
- **Selection rule:** the wall shows the glossary below, minus duplicates — 58 cards across 7 groups. The main narrative uses only the starred (★) ones. Density is fine here and nowhere else.
- **The `G` array is the source of truth**, not the table below it. It is a nested JS literal: each group ends `]]],` and the last ends `]]]`. Editing it line-by-line breaks those terminators — rebuild the array rather than deleting rows in place.

---

## THE GLOSSARY — every AI concept, in the kitchen

### The baker itself
| Kitchen | AI |
|---|---|
| A baker who has read every cookbook ever written but never worked in *your* bakery | ★ the base model |
| Culinary school graduate vs. someone trained in your house style | base model vs. fine-tuned |
| The apprentice vs. the head pastry chef — you don't put the apprentice on the wedding cake | model selection by capability |
| You don't use a stand mixer to whisk one egg | right-sizing model to task; cost & latency |
| How much the baker is allowed to improvise — "follow it exactly" vs. "chef's interpretation" | ★ temperature / sampling |
| Two bakers, same recipe, two slightly different cakes. Same baker, different days, same story. | non-determinism |
| Confidently produces a durian cake having never seen one, and never mentions it | ★ hallucination |
| Reads the whole recipe and plans before touching the dough | reasoning / extended thinking |
| Can look at the photo you brought in, not just read your description | multimodality |
| Brilliant, tireless, fast — and has never been in this kitchen before | the honest one-line summary of an agent |

### What it knows
| Kitchen | AI |
|---|---|
| The size of your workbench — everything has to be laid out on it at once | ★ context window |
| A cluttered bench: the vanilla is on there somewhere, under the flour bags | context rot / lost-in-the-middle |
| A bigger bench does not make a better baker | why context length isn't capability |
| The notebook kept between shifts, vs. amnesia every morning | memory / statelessness |
| The pantry index — reaching for the right cookbook instead of memorising all of them | RAG / retrieval |
| Months of training in your house style: expensive, permanent, hard to undo | fine-tuning |
| The laminated card on the wall — "unsalted butter always, never fondant, allergen protocol X" | ★ system prompt |
| Showing three cakes you liked rather than describing them | few-shot examples |
| "Here is our actual house recipe" vs. "make it how you think it's done" | grounding |
| It knows baking. It does not know that we stopped using supplier B in March. | the knowledge/context gap |

### The work
| Kitchen | AI |
|---|---|
| The order ticket | the prompt |
| Writing the ticket so the kitchen never has to guess | prompt engineering |
| ★ Mise en place — measured and laid out before the heat goes on | task decomposition |
| Mixing → proofing → oven → cooling rack → decorating | pipeline / chained steps |
| You cannot ice a hot cake | dependencies & ordering |
| Several bakers on several stations at once | parallel agents |
| A pastry section and a bread section, each with its own chef de partie | sub-agents |
| The head chef at the pass — calling the order, not touching the food | ★ orchestration |
| One oven load of twelve, not twelve loads of one | batching |
| Proving overnight. You don't stand and watch it. | async / long-running jobs |
| Run the recipe twice, get two cakes — not one cake baked twice | idempotency |
| A ninety-step recipe for toast | over-engineering |
| You asked for a cake and got a three-tier wedding display | scope creep |

### Knowing it worked
| Kitchen | AI |
|---|---|
| "Until golden brown" | an acceptance criterion |
| ★ The toothpick — a cheap check that the expensive step worked, before committing to the next | intermediate verification |
| The same five judges, the same score sheet, every batch | evals |
| Does the recipe still work now we've changed supplier? | regression testing |
| The head chef tastes before it leaves the pass | human in the loop |
| The allergen protocol: non-negotiable, checked every time, no exceptions | guardrails |
| The oven's temperature chart and the timer log — knowing *when* it went wrong, not just that it did | observability |
| ★ The oven that was never switched on. Looks perfect until you cut it open. | silent failure |
| A bad sack of yeast ruins every loaf downstream | cascading failure |
| The eggs are off — does it stop and ask, or substitute without telling you? | error handling & escalation policy |

### The kitchen
| Kitchen | AI |
|---|---|
| Handing over the mixer *and* saying what it's for | tool use |
| Every appliance takes the same plug | MCP / standard interfaces |
| The padlocked cupboard, the till, the keys to the front door | permissions & scopes |
| One oven, and a queue for it | rate limits |
| The gas bill and the ingredient cost — every bake costs something | tokens & compute cost |
| You cannot rush a proof | latency you can't engineer away |
| The test kitchen. You don't trial a new recipe during service. | sandbox / staging |

### The economics
| Kitchen | AI |
|---|---|
| ★ A cake is a variable cost. A recipe is a fixed cost that keeps paying. | the automation trade |
| The crossing point of the two lines | break-even batch size |
| The first cake through the new process is always slower | setup cost mistaken for failure |
| The recipe book, not any single cake, is what the bakery is worth | prompts & pipelines as durable assets |
| It bakes while you sleep | the absence case for automation |
| The birthday cake you make for your kid — the making of it *is* the point | work that shouldn't be automated |

### The people
| Kitchen | AI |
|---|---|
| ★ Baker → head chef | IC → manager of agents |
| Which bakers you check every time, and which you let run | trust calibration |
| The new baker needs to be told where everything is — every single morning, unless you write it down | why context and docs are the real work |
| You can't taste it for them. But you must taste it. | delegation without abdication |
| The head chef who hasn't made a genoise in five years can no longer tell when it's wrong | deskilling risk |
| The recipe outlives the baker who wrote it | institutional knowledge |

---

## RUNNING DEVICES

1. **Oven-timer scroll indicator** — a dial that fills with progress, not a bar.
2. **Flour-dust particle layer** across the whole page, cursor-reactive. One persistent physical element ties it together.
3. **Temperature colour system** — cold blueprint → warm recipe card. Nobody notices consciously; everybody feels it.
4. **One interactive per point** — focus-pull (P1), granularity dial (P2), station switches (P3), plus the break-even chart in S4 and the card wall in S13.
5. **Handwritten margin notes** — a second, dryer narrator. Two lines maximum, never restating the main text.
6. **Recurring baker silhouette** — S0, S5, S11, S12, different postures.
7. **Restraint rule** — one idea per scene, 30 words maximum. The glossary is the *only* dense surface, and it's behind the ending on purpose.
8. **`prefers-reduced-motion` + mobile** — degrades to a clean vertical read with fades.
