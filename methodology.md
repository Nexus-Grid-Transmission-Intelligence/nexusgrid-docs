# Methodology

Nexus Grid uses modeling concepts to make transmission coordination behavior easier to review. The current public framing focuses on restoration sequencing, replay visibility, dependency-aware coordination, propagation modeling, and constrained recovery behavior.

## Restoration Sequencing Concepts

Restoration sequencing describes the order in which modeled recovery steps occur.

In a constrained transmission environment, the next restoration step may depend on:

- Which infrastructure elements are available.
- Which dependencies must be restored first.
- Which topology paths remain connected.
- Which operating constraints limit recovery.
- Whether the modeled sequence has reached a plateau.

Nexus Grid demonstrations use sequencing to show how recovery behavior can progress, slow, or change as constraints emerge.

## Replay Visibility Concepts

Replay visibility means being able to review a modeled event after it runs.

A replay can help answer questions such as:

- What sequence occurred?
- Which step happened before another step?
- Where did the recovery path slow?
- What dependencies shaped the next feasible action?
- What trace evidence supports the review?

Replay visibility is not a claim that the system is reconstructing a real utility event. It is a way to inspect modeled behavior and structured runtime traces.

## Dependency-Aware Coordination Concepts

Dependency-aware coordination means the model accounts for relationships between infrastructure elements or restoration steps.

For example, one modeled recovery action may depend on another modeled condition being available first. A dependency can affect:

- Recovery order.
- Propagation behavior.
- Coordination boundaries.
- Plateau points.
- Review of why a sequence changed.

The goal is to make these relationships visible enough for review and discussion.

## Propagation Modeling Concepts

Propagation modeling describes how a modeled operational effect moves through connected infrastructure relationships.

In Nexus Grid demonstrations, propagation may show:

- Where modeled recovery progresses.
- Where the effect remains local.
- Where a dependency chain delays recovery.
- Where coordination boundaries appear.
- Where a plateau forms.

Propagation modeling is not the same as full physical grid simulation. It is focused on coordination behavior and sequencing visibility.

## Structured Runtime Evidence

Structured runtime evidence refers to traces generated during a modeled run.

Those traces can support:

- Replay review.
- Sequence reconstruction.
- Plateau identification.
- Dependency review.
- Discussion of coordination boundaries.

Trace generation is useful because it gives reviewers something more concrete than a final state alone.

## Assumptions

Public Nexus Grid demonstrations assume:

- A modeled infrastructure topology is available.
- Dependencies can be represented in the demonstration environment.
- Recovery steps can be sequenced.
- Constraints can influence progression.
- Replay traces can be generated from the modeled run.

## Limitations

The methodology does not currently claim:

- Live operational control.
- Full grid physics.
- Production reliability validation.
- Utility-specific outcome guarantees.
- Predictive forecasting.
- Automated operator decision replacement.

The methodology is intended for demonstration, review, and communication of coordination behavior.
