# New Management

Prompt, governance, schema, and fixture repository for the New Management v1 acquisition-analysis and media system.

## Product flow

Incoming listing → cheap screen → James chooses → public research → investment analysis → verified memo → James approves → article → claim check → media quality score → James approves → publish.

The system is intentionally simple.

**The system is boring. The outputs are sophisticated.**

## Editorial philosophy

**Rules protect truth. Frameworks organize thought. Examples demonstrate quality. Formatting creates pace.**

New Management aims for serious investment thinking that feels approachable, curious, and enjoyable to read.

Dense ideas, light reading.

## Repository map

### governance/

Canonical standards.

- 00_constitution.md
- 01_investment_standard.md
- 02_evidence_and_uncertainty.md
- 03_editorial_standard.md
- 04_devices_and_metrics.md
- 05_quality_card_anchors.md
- 06_memo_and_article_anatomy.md
- 07_media_quality_rubric.md
- 08_value_creation_standard.md

### prompts/

Runtime prompts used by n8n.

- 01_extract_listing.md
- 02_screen_card.md
- 03_research.md
- 04_investment_analysis.md
- 05_memo_writer.md
- 06_memo_verifier.md
- 07_media_writer.md
- 08_article_claim_checker.md
- 09_media_scorer.md

### examples/

Quality references. These are intentionally important to the writing system.

- prose_gold_standard.md
- screen_card_examples.md
- swing_question_examples.md
- under_new_management_examples.md

### schemas/

Structured model-to-model interfaces.

- listing_extract.schema.json
- screen_card.schema.json
- research_plan.schema.json
- research_pack.schema.json
- investment_analysis.schema.json
- memo_verification.schema.json
- memo_sources.schema.json
- article_claim_check.schema.json
- media_score.schema.json

### fixtures/

Five live end-to-end tests plus an aggregate calibration log.

The fixture files are not sample data. They are debugging records used to identify which governance, prompt, example, or schema file should change when a live run fails.

## Build philosophy

Do not create one giant master prompt.

Each runtime stage loads only the governance and examples it needs.

If a failure appears:

- fix evidence problems in evidence governance;
- fix analytical problems in the investment standard or Stage B prompt;
- fix generic value creation in the value-creation standard or examples;
- fix prose in the editorial standard or gold examples;
- fix unstable interfaces in schemas.

The five live fixtures are the calibration mechanism.

Further architecture changes should come from an observed fixture failure, not more theoretical design.


## Runtime sentinel

The media writer has one plain-text control contract for n8n:

- if output begins exactly with `KICKBACK:`, n8n routes the item upstream for analytical repair and does not treat the output as article content.

This remains intentionally simpler than adding another schema solely for one exceptional branch.
