# ADR 0001 - Choice of Serverless

## Status

ACCEPTED

## Context

As a registered charity Diversity Cyber Council needs to be conscious of the TCO (Total Cost of Ownership) implications of all new infrastructure. 

Serverless Architectures/Infrastructure were proposed as a default choice whenever feasible for the "building blocks" of all component pieces of the talent pipeline.

## Decision

We **will** prioritize the choice of serverless components of solutions before choosing to run infrastructure.

## Consequences

Positive Impact:
- idle time running cost will trend downward as compared to peak.
- infrastructure maintenance costs will be lower.
- services are managed.
- operations team(s) are more able to focus on "value add" rather than running "services".

Negative Impact:
- staff need to understand serverless architectures and methodologies.
- staff need to be more aware of the cloud providers infrastructure elements (not as easily left to someone else).
- application diagramming looks more daunting since functions are exposed rather than "groups" of functions.
- changing providers is more difficult (not impossible).