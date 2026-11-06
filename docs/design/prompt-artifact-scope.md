---
gist: "Read when: considering runtime code, API dependencies or a model-specific wrapper, or judging whether the repository is an application or a fact-checker."
---

# Prompt artifact, not an application

**Decision.** The repository is a reusable prompt artifact, not an application or a factual-verification service. README.md explains when to use it; `prompt.md` is the deliverable. Keeping the prompt in plain Markdown makes it portable across chat products and versionable without tool-specific configuration.

**Contradicted by.** A change in the repository's purpose. Without one, do not add runtime scaffolding, API dependencies, or a model-specific wrapper; the prompt must stay easy to inspect, copy, and adapt.
