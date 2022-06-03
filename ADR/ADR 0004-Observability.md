# ADR 0004 - Observability

## Status

ACCEPTED

## Context

Given [ADR 0001](ADR%200001-Choice%20of%20Serverless.md), the choice of an observability platform is important for viewing where issues can arise.

After some discussion, Amazon Web Services (AWS) standard observability tools will suffice. CloudWatch, X-Ray and other basic AWS tools will be used.

## Decision

- We **will** use AWS observability tools.

## Consequences

Positive Impact:

- Developers can specialize in a given cloud provider.
- "Single pane of glass" for viewing cloud properties.
- Largest provider should mean a larger talent pool to draw from.

Negative Impact:

- Other tools may have more in-depth offerings that may need to be considered in future.
- Particular care needs to be placed on retention of logs.
- AWS billing can be cryptic.
