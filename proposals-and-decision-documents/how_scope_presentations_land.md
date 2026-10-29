# How scope presentations land

## Purpose

This is a reference on how scope and approval presentations are structured in industry, written as a lesson. It uses a recent project scope deck (from October, 2026) as a worked example. 

### Organization

File this under **Project management** > **Proposals and decision documents**. The organizing idea is _asking someone with authority to commit resources under uncertainty_, which applies far beyond phase transitions (e.g., new tools, headcount, process changes, etc). 

The A3 material (lesson 3) is also a thinking method.

## Lesson 1: What is a scope presentation?

A scope presentation is a request for a resource allocation under uncertainty. Someone with authority over money, people, or time is being asked to commit some of it to work whose outcome is not guaranteed. Everything about how these presentations are structured follows from the two elements that make this process difficult. 

1. **The decider knows less than you do.** They have not lived in the problem. Whatever you put in front of them has to let them reconstruct enough of your reasoning to trust it, fast.
2. **The decider is managing a portfolio.** Your request is one of many, competing for the same budget. They are not asking, "is this good?", but "is this better than the other things I could fund, and what is the risk?"

Every pattern in industry is a different answer to one question:

> _how do I compress my understanding so that a portfolio-minded reader can verify it?_

## Lesson 2: The universal skeleton

Before the families diverge, consider what they share. Almost every mature scope artifact has three parts, usually presented sequentially.

1. **The ask**: What you want decided, stated succinctly. It goes first because the reader's first question is always, "what do you want from me?". If they have to search or guess what that is, they read everything else with impatience instead of attention.
2. **Current condition**: Facts about today, not complaints (e.g., how long things take, how often they fail, who is affected). This is where the reader assesses how well you understand the problem. It is often skipped, but is the most diagnostic part.
3. **Proposed change, bounded**: What you will do and what you will not. Treat the "won't" list as a contract against future misunderstanding.
4. **What is costs and what depends on it**: Effort, time, personnel, decisions required from others.
5. **How you will know it worked**: Success criteria
6. **Riks and mitigations**
7. **Decisions required today**: A short list of concrete questions (ensure the meeting produces answers instead of discussion).

## Lesson 3: Four families

Think of these as four cultures that each answered the same question differently. Each one solves a specific failure of others, so picking one is actually picking which failure you fear most with your audience.

| Family | Artifact | Core insight | Failure it was built to fix | Weakness |
| --- | --- | --- | --- | --- |
| Narrative memo (Amazon "six-pager") | Prose, read silently in the meeting | Prose cannot hide gaps in reasoning the way a slide deck could | Slide-driven persuasion carrying weak arguments | Slow to write; assumes executives read |
| A3 (lean problem solving) | One page: current --> target --> gap --> countermeasure --> plan --> follow-up | Each section must be derivable from the one preceding it | Proposals built on unexamined assumptions | Easily reduced to a template to fill |
| Stage-gate review | Charter, scope statement, business case, risk register, gate decision | Irreversible decisions deserve ceremony | Costly, irreversible mistakes | Ceremony outlives its justification; slow for reversible work |
| Agile planning increment (SAFe PI, quarterly roadmap) | Features with sizes, dependencies, confidence votes, in a fixed time box | Fix time and team, and the only variable left is scope | Endless scope negotiation | Reframes approval as prioritization, which may not be the question |

### Narrative memo

- The artifact is prose, read silently at the start of a meeting, then discussed.
- The theory is that slides are the presenter's medium: a good speaker can carry a weak argument on bullet points and delivery.
- The memo is a forcing function on the writer's reasoning, not just a communication choice.
- IWhere it works, it works because the whole organization agreed to pay the writing cost. 

### A3

- One page, originally A3-sized paper at Toyota.
- The A3 is not primarily a persuasion tool; it is a thinking tool that happens to be shareable.
- The manager reviewing it acts as a coach, asking "how do you know that?" at each box, and the writer learns by being forced to answer.
- You cannot propose countermeasures without a gap, and you cannot state a gap without a measured current condition.
- In this culture, a proposal without a baseline is not wrong, but unfinished.

### Stage-gate review

- Born in capital-intensive industries where a wrong commitment costs millions and is irreversible.
- Work is divided into phases, each ending in a gate where sponsors decide go, kill, hold, recycle.
- The artifacts are formal.
- The weakness is that the ceremony gets applied to reversible software decisions, where it becomes cumbersome.

### Agile planning increment

- Scope is not expressed as "approve this project" but as "here is what fits in the next time box; let's agree on priority".
- If the time box and the team are fixed, the only variable is scope, so the conversation becomes about ordering rather than approval.
- This is the frame leadership is reaching for when they ask "what fits in Q1?" instead of "should we do this?".

## Lesson 4: Worked example

The audience favored lean methods, so the A3 was the native dialect. The deck borrowed from the other families where it helped.

| Deck element | Borrowed from | Why it is there |
| --- | --- | --- |
| Ask first, decisions-needed last | Narrative memo | Readable in two minutes by someone who only reads the first and last slide; some will |
| Baseline stated as facts | A3 | The credibility slide: proves you measured before you proposed |
| Identical template per requirement (definition, in/out, done-looks-like, effort, open question) | Reviewer's practice | The reader learns the layout once and then compares content; an empty box exposes a weak requirement |
| Timeboxed discovery with go/no-go for rate validation | Lean / modern practice | Converts an unknown into a small, bounded ask with a defined exit; a guessed number fails in the second meeting, not the first, and taints the other numbers |
| Effort as ranges with named swing factors | Epistemics, not formatting | A range with a reason tells the reader what you are unsure about and lets them judge whether it matters; a single number invites them to assume padding or naivety |
| Deliberately out of scope | Stage-gate | The scope contract, shrunk to the size the decision warrants |
| Sequence and checkpoints | Stage-gate, lean-sized | Reframes the ask: fund the next interval and agree on when to report back, a much smaller yes |

On over-detailing: detail is an attempt to pre-answer every question a reader might have. The skeleton already answers the questions that matter for the decision; the appendix and the requirements register hold the rest. The test for any sentence on a main slide is: *does the decision change if this is removed?* If not, it moves to the appendix.

## Lesson 5: Where practice is heading

Two drifts are worth knowing. First, toward shorter, prose-heavier pre-reads and shorter meetings: the memo culture spreading beyond Amazon, and decks collapsing toward one slide per decision. Second, toward treating scope approval as the first checkpoint in a series rather than a one-time blessing.

Both favor a lean artifact with a defined cadence of follow-ups. For a lean audience that is also the honest framing: you are not asking them to bless a plan, you are asking them to fund the next experiment and agree on when you will report back.

## Worksheet

Answer these in order and most of the artifact writes itself; each answer maps to a specific part of the skeleton. A question you cannot answer is a finding: either it does not matter for this decision (drop it), or you are not ready to present (go find out).

# | Stage | Question | What the answer becomes |
| --- | --- | --- | --- |
| 1 | Audience | Who decides, and what else is competing for the same money or people? | The size and tone of the ask |
| 2 | Audience | What do they already believe about today's situation? | How much of the baseline you must prove vs. restate |
| 3 | Audience | How do they prefer to decide: read a memo, discuss slides, rank priorities? | Which family you use (memo, A3, gate, increment) |
| 4 | Audience | Is this decision reversible, and how expensive is a wrong call? | How much ceremony and risk detail the artifact carries |
| 5 | Ask | In one sentence, what do you want them to say yes to, and by when? | The first slide |
| 6 | Ask | What is the smallest yes that lets work start? | Whether you ask for the whole phase or the next interval |
| 7 | Baseline | Which three or four measurable facts describe today? | The baseline slide |
| 8 | Baseline | Who is affected, and how do they experience the problem? | The human half of the baseline |
| 9 | Baseline | What did the last phase deliver, in the decider's terms? | Proof you have earned the next ask |
| 10 | Change | What are the agreed requirements, stated as they were agreed? | The scope-at-a-glance slide |
| 11 | Change | For each requirement: what does it mean now, what is in and out, what does done look like, what is the effort range and dependency, what is the one open question? | One slide per requirement, same template |
| 12 | Change | What is deliberately out, and why? | The out-of-scope slide, and the contract against drift |
| 13 | Uncertainty | What is known, and what still needs discovery? For each unknown, what timebox and what exit criterion? | The discovery slide with go/no-go gates |
| 14 | Uncertainty | What single factor would most change the effort estimate? | The swing-factor note beside every range |
| 15 | Uncertainty | What do you need from other people: decisions, access, time? | The dependencies and the decisions-needed list |
| 16 | Success | How will the decider see it working, without asking you? | Success criteria per requirement |
| 17 | Risk | What could go wrong, and what is the earliest signal that it is? | The risk slide, kept to signals and responses |
| 18 | Decision | What two to four yes/no questions do you need answered in this meeting? | The closing slide |
| 19 | Cadence | When is the next checkpoint, and what will you show at it? | The sequence slide, and the reason the yes is small |

Questions 1–4 are answered once per audience and rarely change. Questions 5–19 are answered per proposal. Anything you know that does not answer one of these questions goes to the appendix or the register, not the main deck.

## Check your understanding

1. A colleague's deck has a strong solution section but no baseline. Which family would call that "unfinished," and why does that matter to the reader?
2. Your manager says "just give me one number for effort." What do you lose by complying, and how would you give a single number without losing it?
3. Leadership shifts to asking "what fits in Q1?" Which family are they switching to, and what changes about how you present the same three requirements?

## Further reading

- John Shook, *Managing to Learn* — A3 thinking as a coaching and reasoning method; short and very readable.
- Colin Bryar and Bill Carr, *Working Backwards* — the first chapters cover Amazon's narrative-memo culture and why it replaced slides.
- 
