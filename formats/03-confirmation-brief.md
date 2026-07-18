# 03 – Confirmation Brief

The most underused format in delivery, and the one that converts contested changes into documented agreement. Use it when you need the customer to **validate your understanding before a consequential step**: retiring a legacy system, baselining a scope, committing to a migration plan.

The structure is a disciplined version of a simple move: *here is what we believe to be true, item by item; is this right?* It works because it gives the customer something concrete to correct instead of something abstract to fear.

## When to Reach for It

- A legacy system retirement where users doubt the replacement covers their needs
- Any "we think we understand your process; confirm before we build" moment
- Pre-baseline scope confirmation with a stakeholder group that wasn't in every session

The common thread: the risk isn't disagreement, it's *unsurfaced* disagreement. The confirmation brief is a machine for surfacing it while it's still cheap.

## Structure

### 1. Frame the moment
Two or three sentences on why this confirmation is happening now and what it unlocks. Name the exciting future plainly, then be explicit that this document handles the unglamorous prerequisite first.

### 2. State your understanding, item by item
List what you believe: the capabilities in actual use, the process as you've mapped it, the needs as you've captured them. Concrete, enumerated, and honest about its status as a *best current understanding*, not a verdict.

### 3. Ask the validation question directly
"Is this right?" in those words or close to them. Then structure both answers:

- **If not:** what's missing? Bound the question tightly (e.g., "we're asking only about capabilities in use today, not your entire process") so corrections stay on target.
- **If yes:** proceed immediately to the disposition list.

### 4. Disposition per item
For each validated item, state its status against the path forward, with dates where they exist and honest flags where they don't:

- Covered already (and where)
- Covered by [date / milestone]
- Not covered; needs further definition (and what question must be answered)
- Handled elsewhere (and by what)

This list is where trust is won or lost. One optimistic "covered" that turns out false costs more than five honest "needs further definition" flags.

### 5. The keystone question
End with the question that makes the decision real. For a retirement it has a fixed shape:

> "If we provide everything above, and we turn the old system off, can you still do your job?"

- **If yes:** name the next step explicitly (the formal plan gets drafted, the date gets set).
- **If no:** "what else do you absolutely need?" and the answers route into intake as first-class items, on the record.

## Why It Works

Three mechanisms:

1. **It converts fear into a checklist.** "They're taking our system away" is unanswerable. "Row 4 is wrong" is a Tuesday conversation.
2. **It makes the customer the author of the record.** Every correction they make is a line they now own. Agreement they helped write doesn't get relitigated the way agreement they were shown does.
3. **The branch structure removes the trap.** Both "yes" and "no" have dignified, pre-planned next steps, so nobody has to defend a position to avoid an ambush. People agree faster when agreeing isn't a corner.

Pair it with a capability crosswalk when the subject is a system retirement; the crosswalk is the evidence, the confirmation brief is the conversation. See the [Requirements Engineering Framework](https://github.com/grahamdeno/requirements-engineering-framework) for the crosswalk method, and this repo's [worked example](../examples/worked-example-sunset-decision.md) for the two together.
