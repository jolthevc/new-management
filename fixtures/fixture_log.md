# Fixture Calibration Log

Status: Empty until live testing begins

## Purpose

Track patterns across the five end-to-end fixtures so prompt changes solve system problems rather than overfitting one deal.

## Rules

For every change made during fixture testing, record:

- fixture;
- observed failure;
- stage where it appeared;
- governance, prompt, example, or schema file changed;
- exact change;
- expected effect;
- rerun result;
- whether the change affected another fixture.

Prefer the smallest file change that addresses the observed failure.

Do not reopen the conceptual framework unless a live fixture demonstrates an actual failure.

## Change log

| Date | Fixture | Stage | Failure | File changed | Change | Rerun result | Cross-fixture note |
|---|---|---|---|---|---|---|---|

## Patterns to watch

### Evidence
- inference leaking into fact;
- category assumptions becoming company claims;
- fake precision on thin listings.

### Investment thinking
- generic Business Physics;
- Quality Card score drift;
- weak normalization;
- value range disconnected from Year 0 economics;
- Bear Case attacking the wrong thesis.

### Value creation
- generic levers;
- gimmicky "differentiated" ideas;
- levers not tied to physics variables;
- value creation accidentally included in seller value.

### Writing
- negativity drift;
- institutional or HBR-like prose;
- walls of text;
- constant one-line paragraphs;
- template-visible structure;
- examples being copied too literally.

### Media
- article weaker than memo;
- new substance leaking from research;
- decorative rather than useful image briefs;
- score inflation.

## Exit criterion

Fixtures 4 and 5 should pass without prompt changes after fixture 3.

If they do not, record why before making another change.
