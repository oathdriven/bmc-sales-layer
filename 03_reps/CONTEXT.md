# 03_reps: CLOSE · they leave with reps and a number

**Status: THE V1 WEDGE, in build.**

## The cold call reps are the front door, and they are the new build

**v1 builds COLD CALL reps, not close reps.**

| | Cold call reps | Close reps |
|---|---|---|
| Built? | new build | 4 tuned personas, live |
| Who needs it | **every beta user** | far fewer, and downstream |
| Length | 2 to 5 min | 20 to 30 min |
| COGS at $0.101/min | **~$0.30 a rep** | $2 to $3 a rep |

That cost gap is what makes a low tier survivable. It is a margin fact, not a guess.

**Why it is a real build:** the 4 existing personas explicitly start *"on a booked sales
call."* Cold calling is the step before, and it needs a character that did not exist:
**the gatekeeper.** What carries over is the architecture (voice assistant + prompt + tier +
safeword + grading schema, dialed to a real phone), which is the expensive half and is proven.

**The spec source is confirmed doctrine:** `../_reference/curriculum/cold-call.md` (the
gatekeeper, the 2-part opener, the 2 fixed parts, booking the 15 minute call, never say AI,
the awareness ladder running backwards).

The confirmation pass added something the raw capture did not have. **The weeds law:**

> *"As soon as they get into the weeds of their offer on a cold call, they've lost. All they
> have done is created more questions and objections from a stranger that wasn't looking to
> be sold."*

**The objective of a cold call is to gauge interest in FIXING THE PROBLEM**, which is what
earns the 15 minutes. Not to explain the solution. "Never say AI" turned out to be 1
instance of this larger law.

The sim teaches it by consequence rather than by rule: every owner asks a technology
question, and if the caller answers it in the weeds, **the owner generates escalating
questions and objections until the call dies of its own weight.**

**Nothing already built gets wasted.** Close reps unlock downstream when appointments land.
They were just never the front door.

---

## The job

1 job: someone has a calendar and no confidence, and leaves with reps, a scorecard, and a
$/call number they can point at.

**This module carries the beta's whole burden.** The 10 testers are also the first case
studies, so this is where the attributable result comes from.

## What carries over from the earlier build

| What | Status |
|---|---|
| The 4 AI personas, the lie catalog, the trust meter, the 10-point rubric | the strongest asset in the salvage, tuned against real calls |
| The grader, model-agnostic | built |
| The $/call math and its spec | the only tested code in the org |
| Ryan's verbatim lines | private workspace, verbatim-only |
| The provisioned voice assistants and the spar number | private workspace inventory, never rebuild |

## Inputs

- Working: the offer from `../01_offer/` and the plan from `../02_gameplan/`
- Reference: the table above

## Output

`output/` does not exist yet in this copy. The build spec lives in the private workspace.

## Done looks like

A beta tester can say a sentence like *"my $/call went from X to Y, here is the scorecard."*
Not *"I liked it."*

## Human check

Ryan closes a live prospect, then watches a beta tester try. If the scorecard does not
explain the gap between the 2 runs, the grader is not done.
