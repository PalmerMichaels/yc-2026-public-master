# ClaimGlide

- Slug: `claimglide`
- Batch: Winter 2026
- YC status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source URL: https://www.ycombinator.com/companies/claimglide
- Website: https://claimglide.com/
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/154
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- Public Repository: https://github.com/PalmerMichaels/claimglide-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/67

## Public Description

AI automated prior-auths for private medical practices

We automate the entire end-to-end prior-authorization process for private practices for cheaper, and more accurately than they're doing today.

## Classification Rationale

Pure software workflow can be implemented clean-room using synthetic/user-provided data, mock integrations, and clear non-regulated disclaimers. Sector context alone does not require regulated deliverables.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/claimglide-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/67
- Commit: `74deb7cb096b6a2106f3b01bd2d557f95621e4a6`
- Notes: Implemented and pushed; Validation: npm test, npm start -- overview, npm start -- case PA-1001 --json, npm start -- review PA-1002 approve-package --actor=staff-review-1, npm start -- queue --queue=staff_review, and npm start -- sync --json passed; clean ## main...origin/main; HEAD == origin/main.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

`claimglide-public`

## End-to-End Implementation Scope

Prior-authorization admin workflow for private medical practices with synthetic patients/cases/documents, mocked payer/EHR-like connectors, checklist/status/task queues, staff review/audit flows, validation/tests, docs, and clean-room/non-clinical disclaimers. No diagnosis, treatment, triage, PHI, medical advice, clinical decision support, claim submission to real payers, real EHR/payer integrations, medical-device behavior, or regulated medical behavior.
