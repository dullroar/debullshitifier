# De-Bullshitifier

De-Bullshitifier translates institutional language into ordinary English.

## Why?

Important decisions are often wrapped in jargon, polished abstractions, and confident claims that make them sound clearer than they are. That language can hide the actual action being requested, the people responsible, the evidence behind a claim, and the costs or risks passed to someone else.

This project provides a reusable system prompt for examining that language without becoming a reflexive cynic. It asks an analyst to identify what a document is actually saying, distinguish facts from claims and promises, expose meaningful omissions, and preserve uncertainty where the evidence is incomplete.

The intended inputs include press releases, political statements, executive presentations, consultant decks, job descriptions, policies, mission statements, nonprofit appeals, product marketing, investor material, and public relations copy.

## What it is for

Use [prompt.md](prompt.md) as a system prompt for an LLM that needs to:

- translate jargon into concrete actions and consequences;
- separate supported facts from unsupported claims, promises, opinions, and fog;
- identify who benefits, who pays, and what tradeoffs are undisclosed;
- ask questions that force vague proposals to become testable;
- analyze political and institutional language by the same evidence-minded standard;
- avoid inventing motives, evidence, or conclusions that the source does not support.

## What it is not

De-Bullshitifier is not a lie detector, fact database, political partisan, or license to infer bad faith from awkward writing. A claim may be vague, spin-heavy, or unsupported without being demonstrably false. The prompt explicitly distinguishes those cases and encourages external verification only when reliable sources are available.

## Usage

Copy the contents of [prompt.md](prompt.md) into the system-prompt field of your preferred LLM, then provide the document or passage to analyze. For web pages, include the URL when browsing is available so the analyst can identify the author, sponsor, publisher, date, audience, and supporting sources.

The default response ends with a concise **Eyeroll verdict**: memorable enough to be useful, but not a substitute for the analysis.

## Status

This repository currently contains the system prompt and its rationale. The GitHub remote will be configured later.
