# Research — sources to build the three points on

Gathered Aug 2026. Organised by where it strengthens the page.

---

## POINT 1 — Know what done looks like
### The idea has a name now: spec-driven development

- **"The specification, not the code, is where human intent lives."** SDD inverts the workflow: the spec is the source of truth, code is a generated or verified secondary artifact. This is a much stronger claim than "write down what done looks like" — it says the spec *is* the new source code.
- Founding talk: **Sean Grove, "The New Code"**, AI Engineer World's Fair 2025. By 2026 every major tool ships a flavour: GitHub **Spec Kit**, AWS **Kiro**, OpenSpec, BMAD, Tessl, Google Antigravity.
- **Three levels of rigour** — spec-first, spec-anchored, spec-as-source. You pick the level the job deserves. Maps directly onto the granularity dial.
- Addy Osmani, *How to write a good spec for AI agents*:
  - **"Most agent files fail because they're too vague."**
  - Six things a spec must cover: commands, testing, project structure, code style, git workflow, boundaries.
  - **Three-tier boundaries: ✅ Always / ⚠️ Ask first / 🚫 Never.** Excellent for the bakery — the house rules card on the wall. Also ties straight to the locked-cupboard beat.
  - **"The curse of instructions"** — too many simultaneous requirements and the model follows none of them well. A real counterweight to "more detail is always better."
  - "Minimal does not necessarily mean short."

Sources: https://en.wikipedia.org/wiki/Spec-driven_development · https://github.blog/ai-and-ml/generative-ai/spec-driven-development-with-ai-get-started-with-a-new-open-source-toolkit/ · https://addyosmani.com/blog/good-spec/ · https://arxiv.org/abs/2602.00180

---

## POINT 2 — Break it down
### Anthropic's Building Effective Agents gives the patterns names

Five named patterns, each of which is a kitchen station:
- **Prompt chaining** — the production line.
- **Routing** — the pass deciding which section takes the order.
- **Parallelisation** — several bakers on several stations.
- **Orchestrator–workers** — a central model breaks the task down, delegates, synthesises. Crucially *"subtasks aren't pre-defined — they're determined by the orchestrator based on the input."* That is literally the head chef.
- **Evaluator–optimiser** — one model generates, another critiques, in a loop. *"Particularly effective when it uses clear evaluation criteria."* Ties point 2's checkpoints to the taste test.

**The fork worth stealing:** *workflows* are systems where models and tools run through **predefined code paths**; *agents* are systems where the model **directs its own process**. In the metaphor: some cakes need a recipe, some need a chef. Knowing which you are writing is the actual skill.

Source: https://www.anthropic.com/research/building-effective-agents

---

## POINT 3 — Give it the tools
### This is the best-documented of the three, and it confirms the kitchen mapping

From Anthropic, *Writing effective tools for AI agents*:
- **"More tools don't always lead to better outcomes."** A kitchen crammed with gadgets is worse than five good ones.
- **Consolidate:** one `schedule_event` beats `list_users` + `list_events` + `create_event`. The stand mixer, not a whisk plus a bowl plus a stand.
- **"Think of how you would describe your tool to a new hire."** That is the entire thesis of the page, written by someone else.
- **Namespacing** (`asana_projects_search` vs `asana_users_search`) — labelled drawers, so nobody reaches into the wrong one.
- **Errors must be "specific and actionable, rather than opaque error codes."** The oven that beeps versus the oven that just goes quiet — this is the silent-failure beat, confirmed.
- Return meaningful names, not UUIDs. Paginate and truncate.

From Anthropic, *Effective context engineering for AI agents*:
- **"Find the smallest possible set of high-signal tokens that maximise the likelihood of the desired outcome."** That is mise en place stated formally.
- **Context rot** — performance *degrades* as token count grows; attention is a finite budget, n² pairwise relationships stretch focus thin. The cluttered-bench analogy has a real name and a real mechanism.
- **"The right altitude"** for a system prompt — the sweet spot between brittle over-specification and vague guidance. **This is the granularity dial, and it is a named concept.** Strongest single find.
- **Just-in-time retrieval** — agents hold lightweight identifiers and load data at runtime, "mirroring human cognition: we index information externally rather than memorising everything." The pantry index, confirmed.
- Long-horizon techniques: **compaction** (summarise and restart), **note-taking** (persistent memory outside the window), **sub-agents** (specialists returning condensed summaries).

Sources: https://www.anthropic.com/engineering/writing-tools-for-agents · https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents

---

## THE TASTE TEST — evals have a method
Hamel Husain & Shreya Shankar:
- **"Look at your data."** Start with error analysis, not imagined metrics.
- Read **50–100 real traces** yourself and find the most common ways it fails.
- **Write evaluators for errors you discover, not errors you imagine** — otherwise you build metrics with no impact on quality.
- Generic metrics (BERTScore, ROUGE, cosine similarity) are useless for most applications.
- Cost-benefit each eval before building it.

In the metaphor: taste the batch *before* you write the score sheet. You cannot design the score sheet from an armchair.

Sources: https://hamel.dev/blog/posts/evals-faq/ · https://maven.com/parlance-labs/evals

---

## THE BATCH SCENE — a real number for "the first cake is slower"
**METR randomised controlled trial (July 2025).** 16 experienced open-source developers, 246 real tasks, in codebases they already knew well (~5 years' familiarity).
- They were **19% slower** with AI tools.
- They had predicted **24% faster** beforehand.
- Afterwards, having actually been slower, they still estimated they had been **20% faster**.

**The perception gap is the story, not the slowdown.** It is the single best argument for the taste test: you cannot feel whether this is working, so you have to measure it.

Handle honestly — the caveats are what make it credible:
- Tools were those available Feb–Jun 2025; the field moved fast afterwards.
- METR was explicit it does *not* show AI fails to speed up most developers, or in other domains.
- In Feb 2026 METR published an update: later results showed *some* evidence of speedup, but selection effects made the central estimate unreliable, and they changed the study design.

Sources: https://metr.org/blog/2026-02-24-uplift-update/ · https://arxiv.org/abs/2507.09089

---

## THE PROMOTION SCENE — independent confirmation
- Demand for engineering managers is **surging** in the agentic coding era (LeadDev).
- *"Engineering managers are becoming elite ICs, because delegation, context-setting and task breakdown map perfectly onto overseeing agents."* — the exact argument of S11, arrived at independently.
- *"As generating software becomes cheaper, verification becomes more valuable. The bottleneck is no longer writing code — it's knowing what to trust."* This is the strongest one-line justification for the taste-test scene.

Sources: https://leaddev.com/career-development/demand-for-engineering-managers-is-surging-in-the-agentic-coding-era · https://www.greaterwrong.com/posts/aTst2RJMFra4zsdzz/every-engineer-a-manager
