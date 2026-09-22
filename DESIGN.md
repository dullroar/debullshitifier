# DESIGN.md

# De-Bullshitifier Design

## Boundary

This repository is a reusable prompt artifact, not an application or a factual-verification service. README.md explains when to use it; `prompt.md` is the deliverable.

## Core decisions

- The prompt asks a language model to identify vague, inflated, evasive, or unsupported language while preserving the underlying claim where possible.
- It is intentionally opinionated about clarity, but it does not claim to establish truth. A polished answer is not treated as evidence.
- Keeping the prompt in plain Markdown makes it portable across chat products and versionable without tool-specific configuration.

## Constraints

Do not add runtime scaffolding, API dependencies, or a model-specific wrapper unless the repository’s purpose changes. The prompt itself should remain easy to inspect, copy, and adapt.


