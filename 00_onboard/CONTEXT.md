# 00_onboard: find out where they are, send them there

**Status: NOT STARTED.**

## The job

1 job: find out what the person already has, and open the product on the module they need.

This is the stage that makes BMC a journey instead of 3 tools in a trenchcoat.

## Inputs

- Reference (every run): `../_config/the-journey.md`, the 3 stages and the gate reasoning
- Reference (every run): `../_config/what-this-is.md`, the 2 avatars entering from opposite ends
- Reference (every run): `../_config/constraints.md`, banned vocabulary, especially the
  builder-facing never-use list

## Process

1. Ask whether they have something to sell. That is the only branching question.
2. Route to the module that answers their actual gap.
3. Leave the other 2 visible and reachable.

## Output

`output/` does not exist yet. When it does: the question set, the routing rules, the copy.

## The design constraint that decides this stage

**Route, do not lock.** Full reasoning in `../_config/the-journey.md`. Short version: the live
page already promises no enforced order, the eyebrow serves 2 avatars entering from opposite
ends, a lock can block something a member already paid for, and a bad offer is the lesson
rather than a blocker.

The stronger mechanism is a number: let them spar on day 1, then show them their $/call with
the offer they actually have. **A lock creates a refund. A number creates a purchase.**

## Done looks like

A person who has never sold anything and a person who has sold for 10 years both land
somewhere useful, and neither one is told "no."

## Human check

Ryan runs it as both avatars. If the closer who cannot build feels blocked, it is wrong.
