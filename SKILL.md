---
name: kickoff-brief
description: Use before significant product or workflow work to assess the need, hypotheses, alternatives, costs, and human go/no-go decision before building.
---

# Kickoff brief

Before starting significant work, stop and produce a short kickoff brief. Do not begin building merely because building is cheap. The brief replaces the decision-making purpose of a kickoff: establish what is known, what is assumed, what else could solve the need, and whether the work is worth doing.

## When to use

Use this for a new feature, a material product change, a new workflow, or an experiment that could affect users, create ongoing obligations, or shape future decisions. Be conservative: if you are unsure whether work is significant, write the brief.

Skip it for typo fixes, tightly scoped bug fixes with no product or workflow change, and work already covered by an approved kickoff whose scope and assumptions still apply. If the scope or assumptions have materially changed, write a new brief.

## What to include

State who is affected, the problem they face, and the evidence from prior research. Separate evidence from working hypotheses; do not present assumptions as findings. If the proposal asks users to switch tools, channels, or habits because the obvious path is technically hard, call out that behavior change as an unverified working hypothesis, not an established need. Define measurable signals that would show the hypotheses are wrong, and set a check date counted from when users can try the work end to end. Name the smallest end-to-end slice that can produce a real user signal; do not ship infrastructure, schemas, or abstractions ahead of the first testable user flow. Include at least one alternative, including whether to do less or not build.

Account for costs beyond implementation: the user attention an intervention consumes, the maintenance and ownership a live feature creates, the interpretation risk of experiments without explicit hypotheses, and the opportunity cost of higher-evidence work this would delay. An experiment is a good shortcut only when the question is narrow, its result can answer that question clearly, and it can be removed without leaving users or operators with a burden. Treat user attention as scarce; another experiment cannot give it back.

Recommend build, don't build, or do less, with a brief rationale. A named human owner must make the go/no-go decision. Do not start significant work until that decision is made. Record the decision and its date with the brief, and revisit the outcome on the check date, even if the work stalled or was dropped before users could try it.

A kickoff is useful for agent work for the same reason it is useful for human work: it creates a deliberate decision before action.

## Reusable brief

**Need and evidence:** Who is affected, what problem do they have, and what prior research supports this?

**Working hypotheses:** What do we believe, but have not established? Include any unverified behavior change if the proposal asks users to switch tools, channels, or habits.

**Smallest testable slice:** What is the smallest end-to-end slice that produces a real user signal, without shipping infrastructure, schemas, or abstractions ahead of the first testable user flow?

**How we could be wrong:** What measurable signals would disconfirm the hypotheses? Check date (N days after users can try it end to end):

**Alternatives:** What else could address the need, including doing less or not building?

**Costs beyond build:** User attention; live-feature maintenance and owner; interpretation risks; opportunity cost of higher-evidence work delayed:

**Recommendation:** Build / don't build / do less, and why:

**Human decision:** Named owner; go / no-go; decision date:

**Check-in:** On the check date, record status as shipped, stalled, or dropped, plus the outcome to revisit. Check in even if work stalled or was dropped before users could try it end to end:
