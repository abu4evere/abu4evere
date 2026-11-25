### Hi, I'm Abdurashid 👋

I build learning agents and test them like experiments. I'm based in New York, and looking for AI/ML engineering,
research or AI training roles.

**Contact:** [LinkedIn](https://www.linkedin.com/in/abdurashid-khudayberdiyev)

**The question I work on:** can a small artificial mind learn to live in a world it was never built for, and keep
what it learned when it moves to the next one? No language models inside the agents: everything they know, they
learned from their own lives and from each other.

**What I work on**
- **Learning agents:** small neural planners that learn from their own feelings (hunger, tiredness, curiosity), from
  a parent, and from what their actions do.
- **Agent-based simulation:** an artificial society whose nature is programmed and whose culture is left to emerge.
- **Research rigour in code:** pre-registered, frozen plans; analysis written before the data; sham controls; held-out
  replications; and every key number recomputed blind by an independent session before a result is called final.

### Featured projects

**[Mind Lab](https://github.com/abu4evere/mindlab-brain)** · Python, NumPy
A workbench for growing a brain: a 236-parameter neural planner (value iteration with a learned "can I step here?"
filter), trained by actor-critic in procedurally generated grid worlds.
- 45 pre-registered studies so far. Findings include: a long childhood with a parent who fades out is one of the
  strongest levers found; an inborn sleep reflex cut deaths from exhaustion by more than half where reward shaping did not; the
  best brain solves detours and survives about 99% of held-out lands even with its reflexes switched off.
- **An outside exam in [Crafter](https://github.com/danijar/crafter)** (Hafner 2021), with no training there: given hand-
  labelled meanings the brain scored 0.56%; when its eyes instead **learned within each life** what blocks, feeds and
  waters it, it scored **1.51%**, far above the hand-labelled version and about level with Crafter's random agent
  (1.54%). Being told made it rigid; finding out made it explore. A 3x confirmation run on new seeds is under way.
- Each study plan is reviewed by three different LLMs acting as critics (GPT, Gemini, DeepSeek), and every claim they
  make is checked against the code.

**[Artificial Civilization Laboratory](https://github.com/abu4evere/artificial-civilization-laboratory)** · Python, NumPy, SciPy
An agent-based simulation of a small prehistoric people. Their nature (bodies, drives, memory, learning) is
programmed; their culture is left to emerge, and to be measured.
- About 190 logged studies (controlled experiments, read-only audits, evidence reviews), each pre-registered and frozen
  before it runs; every result traces to a committed script.
- **The final exam for Mind Lab's brain:** raised for 300 lives inside the society, it caught up with the society's
  hand-written decision rules (27.8 vs 26.7 years of life on 150 new worlds; difference +1.2, 95% CI −2.5 to +4.7) and
  lived 8 years longer than the untrained brain.
- Bit-exact replays guarded by 72 tests, including property-based tests that found a real flaw in the model's rules.
- A book written from the experiments' results: [*The World That Nobody Wrote, Part One*](https://github.com/abu4evere/artificial-civilization-laboratory/releases/tag/book-part-one) (226 pages).

**[Unstuck](https://github.com/abu4evere/council)** · Python, Docker, Fly.io
Asks several AI models the same question with conflicting instructions, merges what survives, then runs a
drafter / critic / judge debate. Runs entirely on free API tiers.

### Tools
Python · NumPy · SciPy · reinforcement learning (actor-critic, value iteration) · statistics (paired bootstrap,
pre-registration, multiple-comparison control) · LLM APIs · Docker · Linux cloud VMs · GitHub Actions (CI) · HTML/JS
