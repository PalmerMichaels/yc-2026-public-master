# Archal

- Slug: `archal`
- Batch: Summer 2026
- YC status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source URL: https://www.ycombinator.com/companies/archal
- Website: https://www.archal.ai/
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/127
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- Public Repository: https://github.com/PalmerMichaels/archal-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/40

## Public Description

The eval platform for autonomous software

Archal lets you test agents and code that touch third-party APIs without hitting the real services. We build working clones of popular SaaS platforms that hold state across requests and behave like the originals, so you catch bugs before your agent does something irreversible in production.

## Classification Rationale

Pure software or software-demonstrable workflow; a public clean-room version can use original UI, synthetic data, mock integrations, and disclaimers without copying assets or performing regulated core deliverables.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/archal-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/40
- Commit: `e01105e6d74ca1b1fd109e532210627382b176f4`
- Notes: Implemented and pushed; Public repo, default branch main, clean worktree, local HEAD == origin/main, parity 0 0. Validation: npm run validate:data passed; npm test passed; npm run build passed.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

`archal-public`

## End-to-End Implementation Scope

Build an original web app demonstrating the eval platform for autonomous software: onboarding, workspace/project setup, core workflow screens, sample/synthetic data, role-aware task/status management, mock external integrations where needed, and clear clean-room/non-regulated disclaimers. Include seed data, tests, and documentation.
