# Bidflow

- Slug: `bidflow`
- Batch: Winter 2026
- Status: Active
- Classification: `copyable`
- Source: https://www.ycombinator.com/companies/bidflow
- Website: https://usebidflow.com
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: Pending creation

## Public Description

AI Takeoffs for Electrical

We use AI to help electricians speed up the time it takes to submit a competitive bid to a job. We do this by scanning complex CAD drawings and 10X-ing the time it takes to estimate a job. This involves using vision models to read and count complex symbols in large PDFs, which typically take hours (sometimes days) to do precisely. Every missed symbol can cost thousands, and our AI can count to 99% accuracy.

## Classification Rationale

Pure software product based on public description; a clean-room implementation can provide original UI, data model, and mocked/public integrations without copying proprietary assets or bypassing access controls.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

- Repository: `bidflow-public`

## End-to-End Implementation Scope

Build an original web app that demonstrates ai takeoffs for electrical: onboarding, workspace/project setup, core workflow screens, sample data, role-aware task/status management, and mocked external integrations where needed. Include seed data, tests, and clear clean-room documentation.
