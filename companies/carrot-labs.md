# Carrot Labs

- Slug: `carrot-labs`
- Batch: Winter 2026
- YC status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source URL: https://www.ycombinator.com/companies/carrot-labs
- Website: https://superpenguin.ai/
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/147
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- Public Repository: https://github.com/PalmerMichaels/carrot-labs-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/60

## Public Description

AI Cost Management: Track and attribute AI spend across every provider

The problem: AI spend is scattered across multiple provider billing consoles that don't talk to each other. Teams can't answer simple questions like "which customer is driving our Anthropic bill?" or "is this feature profitable after AI costs?" without manually pulling data from each provider and stitching it together in a spreadsheet. What SuperPenguin does: SuperPenguin tracks AI spend across 14 providers (OpenAI, Anthropic, Deepgram, ElevenLabs, Modal, Cursor and more). Zero-code setup: connect an API key and costs sync automatically with model-level breakdowns, trends, and forecasts. Per-request attribution: add two lines of Python SDK to tag every AI call by customer, feature, or team. Slack alerts on budget thresholds and spend anomalies. Most teams are set up in under five minutes. We help companies see where their AI money goes and whether it's worth it.

## Classification Rationale

Pure software or software-demonstrable workflow; a public clean-room version can use original UI, synthetic data, mock integrations, and disclaimers without copying assets or performing regulated core deliverables.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/carrot-labs-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/60
- Commit: `be0eb9ae43fd5f6b23035aabb8ca0031c24dabec`
- Notes: Implemented and pushed; Scope verified: AI cost management across providers with synthetic provider/model/API usage, spend, project/team budgets, alerts, anomaly detection, optimization recommendations, provider/model comparison, and mocked billing/provider connectors. No startup/app ranking. Validation: npm test, npm start, and node dist/src/cli.js --json --provider openai-demo passed; stale-scope scan no startup terms. Worktree clean and HEAD == origin/main.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

`carrot-labs-public`

## End-to-End Implementation Scope

AI cost management across providers with synthetic provider/model/API usage, spend, project/team budgets, alerts, anomaly detection, optimization recommendations, provider/model comparison, and mocked billing/provider connectors. No startup/app ranking.
