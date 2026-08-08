# BMC, Task Router (public copy)

Match your task to a row, go to that 1 home, load what the row names, then stop and work.

## Route by intent

| I want to... | Go to (the 1 home) |
|---|---|
| Know what the product is | `_config/what-this-is.md` then `_config/the-journey.md` |
| Write anything customer-facing | `_config/constraints.md` first, always |
| Work on the onboarding gate | `00_onboard/CONTEXT.md` |
| Work on offer building (BUILD) | `01_offer/CONTEXT.md` |
| Work on the marketing plan (MARKET) | `02_gameplan/CONTEXT.md` |
| Work on practice + reps (CLOSE) | `03_reps/CONTEXT.md` |
| Know what sales is and what it isn't, FIRST | `_reference/curriculum/the-hat.md` (the opening lesson) |
| Consult the cold call doctrine | `_reference/curriculum/cold-call.md` (canon) |
| Consult the 7-stage sales framework | `_reference/curriculum/sales-framework.md` (canon-track, pass pending) |
| Consult the 3 objection handlers | `_reference/curriculum/objection-handlers.md` (canon-track, pass pending) |
| Consult the advanced close | `_reference/curriculum/advanced-close.md` (canon) |

## The pipeline (one direction)

```
_config/  ->  00_onboard  ->  01_offer  ->  02_gameplan  ->  03_reps
  (the rules)   (the gate)     (BUILD)      (MARKET)         (CLOSE)
```

Nothing flows backwards. If a stage needs something changed upstream, change it in `_config/`
first, then forward again.

## Stages

| Stage | Job | Status |
|---|---|---|
| `00_onboard` | Ask if they have an offer, route them to the module they need | not started |
| `01_offer` | They leave with an offer and a price | not started |
| `02_gameplan` | They leave with a plan and traffic | 1 slice in v1: the cold call plan |
| `03_reps` | They leave with reps and a scorecard | the v1 wedge, in build |

An absent `output/` folder is the status "not started." Do not scaffold empty ones.

## Note on this copy

The live workspace carries a rolling state log, a decision log, and a content ledger. They
are stripped from this public copy (see `START-HERE.md`), so this router only routes to what
exists here.
