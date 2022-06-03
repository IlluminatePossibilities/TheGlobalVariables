# ADR 0005 - Amplify

## Status

ACCEPTED

## Context

Given [ADR 0001](ADR%200001-Choice%20of%20Serverless.md) and [ADR 0002](ADR/ADR%200002-Choice%20of%20Cloud%20Provider.md), the need for a simple framework to build and deploy both the frontend and backend applications is required.

After some discussion, Amazon Web Services (AWS) Amplify will be used to deploy the application frontend, as well as the backend. Though you can utilize either the frontend or backend independently, including selected sub components of either, the use of both made sense for our use cases.

Amplify Hosting is a fully managed service for deploying and hosting fullstack applications. It includes CI/CD workflows for automating an applications release cycle. [1] Amplify Hosting supports popular frameworks such as React, Angular, Vue and Gatsby.

## Decision

- We **will** use AWS Amplify Hosting for the application frontend.
- We **will** use AWS Amplify Hosting for the application backend.

## Consequences

Positive Impact:

- Fully managed hosting service removes the need for a dedicated team to support and manage the application
- Fully managed continuous deployment automates application deployment on every commit from Git repositories
- Supports multiple popular web frameworks
- Leverages Amazon's fast and reliable infrastructure such as CloudFront, AppSync, DynameDB, and others.
- Highly scalable and resilient
- Extendable to multiple current use cases and future use cases that may arise.
- Usage based payment
- Built-in Analytics

Negative Impact:

- Constant changes to platform/libraries - developer needs to constant account for these changes
- Potentially higher learning curve with amplify libraries and serverless technologies
- Changing hosting providers is more difficult

## References

1. https://aws.amazon.com/amplify/features/?nc=sn&loc=3&dn=5
