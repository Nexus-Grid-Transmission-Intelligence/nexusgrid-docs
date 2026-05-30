# Example Scenarios

These scenarios describe the kinds of coordination questions Nexus Grid demonstrations are intended to support. They are examples for review and communication, not claims of production deployment or operational outcomes.

## Constrained Restoration

A modeled transmission area has multiple restoration steps, but not every step can proceed immediately. Some steps depend on topology paths, operating constraints, or prior recovery actions.

What a reviewer learns:

- Which steps are feasible early.
- Which steps are blocked by constraints.
- How the modeled recovery order changes as conditions evolve.
- Where sequencing visibility helps explain the recovery path.

## Sequencing Bottleneck

A modeled recovery sequence begins normally, then slows when one dependency becomes the limiting factor.

What a reviewer learns:

- Where the sequence begins to bottleneck.
- Which dependency shapes the next feasible step.
- Whether the bottleneck is local or affects a broader modeled area.
- How replay evidence supports the explanation.

## Dependency Chain Delay

Several modeled restoration actions depend on one another. A delay in an upstream dependency affects downstream recovery steps.

What a reviewer learns:

- How dependency chains influence recovery order.
- Which modeled actions are downstream of the delay.
- Why a final state alone may not explain the sequence.
- How trace evidence can show the relationship between steps.

## Recovery Plateau

Modeled recovery progresses for a period, then reaches a plateau where additional progress slows or stops.

What a reviewer learns:

- Where the plateau occurs.
- Which constraints or dependencies are associated with the slowdown.
- Whether the plateau reflects a coordination boundary.
- How intervention points can be discussed without claiming automated resolution.

## Replay Review Workflow

A modeled coordination run generates a structured trace. A reviewer uses the replay to inspect the event sequence after the run completes.

What a reviewer learns:

- What happened first, next, and last.
- Where recovery behavior changed.
- Which dependencies influenced sequence progression.
- How trace evidence supports operational accountability and review.
