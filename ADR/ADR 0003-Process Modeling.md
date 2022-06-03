# ADR 0003 - Process Modeling

## Status

ACCEPTED

## Context

The brief outlines several business processes that will require code based models/proxies.

The use of code based mechanisms to model the processes that will be required.

A variety of tools were examined, three were considered:

- Camunda (BPMN and serverless platform, expensive)
- Activiti (BPMN code generator, FOSS)
- AWS Step Functions (AWS State Language, pay per use)

It was decided that the processes were sufficiently simple to not warrant integration of a tool.

## Decision

- We **will NOT** use a process modelling tool to model the required processes.
- We **will** consider using one should the need arise at a later time.
- We **will** code with the previous point in mind.

## Consequences

Positive Impact:

- No need to learn a process modeling tool.

Negative Impact:

- Code will need to be written to handle interations.
