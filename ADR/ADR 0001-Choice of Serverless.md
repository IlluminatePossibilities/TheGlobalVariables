# ADR 0001 - Choice of Serverless as an Architectural Style

## Status

ACCEPTED

## Context

As a registered charity Diversity Cyber Council needs to be conscious of the TCO (Total Cost of Ownership) implications of all new infrastructure. As a "greenfield" service offering, there is much benefit to be gained from the use of serverless services as a means of delivering the Spotlight Platform.

Particularly:

- Lesser maintenance requirements meaning less additional staff required.
- Less operational maintenance required as this is performed by the cloud platform provider.
- Functions-as-a-Service (FaaS) means that code written is done so in smaller, more easily digested pieces making code maintenance easier and reducing "cognitive load".

The choice of serverless means that third-party hosted services will be selected as the default choice whenever feasible for the "building blocks" of all component pieces of the talent pipeline.

### Serverless Style

The use of Serverless Architecture implies a development style that is primarily event-triggered or event-driven.

Microservices tend to be thought of as a single deployable piece of code. In the serverless realm, this doesn't hold true. Functions in a (Functions-as-a-Service) FaaS platform are independently deployable. A serverless microservice is a collection of these independently deployed functions that are all related withing a single "domain".

### Lock-In

No discussion of serverless as an architectural style goes without a discussion of lock-in.

Lock-in cost is often touted as a rationale for creating systems that require using products (usually open source and containerized) as the building blocks. This often results in implementations where queues, messaging systems, and potentially databases are all run alongside code in self-managed infrastructure (i.e. Kubernetes or managed Kubernetes). For the case of Diversity Cyber Council, we feel this is unnecessary. Running infrastructure like that incurs a cost and results in a higher TCO when many of the services are available as service offerings within the chosen provider. Building solutions this way, while understood, requires extra time in addition to the cost.

The true cost of "lock-in" is:

```diff
(Cost of Change) X (likelihood of change)
```

It is our opinion that the "cost" of choosing/managing/"coding for" an open-source (containerized) solution (for example like `RabbitMQ`) is not beneficial when compared with the opportunity cost gained by moving faster using the cloud provider's solution (not to mention people opportunity cost gained by not having to manage a solution).

It is our team's opinion that the use of Serverless architecture allows Diversity Cyber Council to maximize opportunity gain and will provide a faster time to market.

As such, we have concluded that serverless options should be explored as a default unless a product offering provides more value.

## Decision

![Architecture Styles Worksheet](../docs/architecture-styles-worksheet.png)

Using the Architectural Characteristics that we have prioritised, as well as the Architecture Styles Worksheet created by [Mark Richards](https://www.developertoarchitect.com/downloads/worksheets.html), we noticed that serverless (which is a combination of microservices and event driven architecture) is the most suit ble architectural style. The only downside is cost, which seems to be a drawback with both the microservices and event driven architecture styles. This, however, is mitigated with the fact that serverless typically involves the use of third-party hosted services, which reduces operational and infrastructure costs.

We **will** prioritize the choice of serverless components of solutions before choosing to run infrastructure.

## Consequences

Positive Impact:

- Idle time running cost will trend downward as compared to peak.
- Reduced operational cost compared to dedicated infrastructure.
- Scaling costs are reduced - no need to prepare infrastructure for estimated peak-load.
- Services are managed.
- Operations team(s) are more able to focus on "value add" rather than running "services".
- Easier separation of concerns.
- Code is written in smaller pieces - reducing cognitive load.

Negative Impact:

- Staff need to understand serverless architectures and methodologies.
- Serverless solutions require better monitoring.
- Staff need to be more aware of the cloud providers infrastructure elements (not as easily left to someone else).
- Serverless applications have "more moving pieces" and diagrams look more daunting since functions are exposed rather than "groups" of functions.
- Changing providers is more difficult (not impossible).
