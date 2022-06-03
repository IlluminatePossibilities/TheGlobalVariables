# ADR 0002 - Choice of Cloud Provider

## Status

ACCEPTED

## Context

Given [ADR 0001](ADR%200001-Choice%20of%20Serverless.md), the choice of default provider becomes important.

Amazon Web Services (AWS) is the leading provider, particularly in the Serverless, particularly lambda space.

We have selected AWS as the default provider.

## Decision

- We **will** prioritize the use of Amazon Web Services (AWS) as a cloud provider.
- We **will** select other providers should the AWS offering be insufficient.

## Consequences

Positive Impact:

- Developers can specialize in a given cloud provider.
- "Single pane of glass" for viewing cloud properties.
- Largest provider should mean a larger talent pool to draw from.

Negative Impact:

- Developers may not be aware of better alternatives in other providers.
- AWS billing can be cryptic.
