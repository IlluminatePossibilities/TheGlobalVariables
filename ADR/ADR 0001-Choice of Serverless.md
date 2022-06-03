# ADR 0001 - Choice of Serverless

## Status

ACCEPTED

## Context

As a registered charity Diversity Cyber Council needs to be conscious of the TCO (Total Cost of Ownership) implications of all new infrastructure.

The choice of serverless means that third-party hosted services will be selected as the default choice whenever feasible for the "building blocks" of all component pieces of the talent pipeline.

### Serverless Style

The use of Serverless Architecture implies a development style that is primarily event-triggered or event-driven.

Microservices tend to be thought of as a single deployable piece of code. In the serverless realm, this doesn't hold true. Functions in a (Functions-as-a-Service) FaaS platform are independently deployable. A serverless microservice is a collection of these independently deployed functions that are all related withing a single "domain".

## Decision

We **will** prioritize the choice of serverless components of solutions before choosing to run infrastructure.

## Consequences

Positive Impact:

- Idle time running cost will trend downward as compared to peak.
- Reduced operational cost compared to dedicated infrastructure.
- Scaling costs are reduced - no need to prepare infrastructure for estimated peak-load.
- Services are managed.
- Operations team(s) are more able to focus on "value add" rather than running "services".
- Easier separation of concerns.
- Code is written in smaller pieces.

Negative Impact:

- Staff need to understand serverless architectures and methodologies.
- Serverelss solutions require better monitoring.
- Staff need to be more aware of the cloud providers infrastructure elements (not as easily left to someone else).
- Serverless applications have "more moving pieces" and diagrams look more daunting since functions are exposed rather than "groups" of functions.
- Changing providers is more difficult (not impossible).
