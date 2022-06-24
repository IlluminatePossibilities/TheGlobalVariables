# ADR 0006 - Markdown

## Status

ACCEPTED

## Context

After discussion on the best method to implement markdown processing, it was decided to process markdown on the client side interfaces to better facilitate and reduce overheads on the backend API's. In particular, this removes the requirement that we need to transform markdown into HTML except on the client interface, and, when additional client types are added (eg, if a native mobile client is created instead of a web app), they can make direct use of the markdown output and local features without the requirement that we add additional interfaces on the backend application.

## Decision

- We **will** process and display markdown on the client side, without transformation on the backend(s)
- We **will** conform to a decided upon subset of markdown features, in particular those provided by markdown-it

## Consequences

Positive Impact:

- Based on CommonMark for easy compatibility
- Includes basic extensions/additional features that facilitate web client usage
- Easily extendable via plugins
- Wide range of client support given the available javascript library
- Easy compatibility with additional libraries
- Reduces complexity of architecture
- Extendable in the future

Negative Impact:

- Non-JavaScript compatible platform would require an intermediary processor and/or a compatible library
- Potential for extremely large documents to slow down on old (5/6 years+) devices, especially lower spec devices

## References

1. [https://aws.amazon.com/amplify/features/?nc=sn&loc=3&dn=5](https://github.com/markdown-it/markdown-it)](https://github.com/markdown-it/markdown-it)
