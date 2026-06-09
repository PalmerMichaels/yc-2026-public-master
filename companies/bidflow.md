# Bidflow

- Slug: `bidflow`
- Batch: Winter 2026
- YC status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source URL: https://www.ycombinator.com/companies/bidflow
- Website: https://usebidflow.com
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/136
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- Public Repository: https://github.com/PalmerMichaels/bidflow-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/49

## Public Description

AI Takeoffs for Electrical

We use AI to help electricians speed up the time it takes to submit a competitive bid to a job. We do this by scanning complex CAD drawings and 10X-ing the time it takes to estimate a job. This involves using vision models to read and count complex symbols in large PDFs, which typically take hours (sometimes days) to do precisely. Every missed symbol can cost thousands, and our AI can count to 99% accuracy.

## Classification Rationale

Pure software or software-demonstrable workflow; a public clean-room version can use original UI, synthetic data, mock integrations, and disclaimers without copying assets or performing regulated core deliverables.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/bidflow-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/49
- Commit: `8c85709c73f973e1c673b08bf1944463224874bb`
- Notes: Implemented and pushed; local main matches origin/main. Scope verified: Synthetic electrical takeoff workflow; plan/package intake, electrical line-item extraction/review, dashboards, estimate comparisons, exceptions, mocked integrations. Validation: npm test and npm start -- --today=2026-06-09 passed.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

`bidflow-public`

## End-to-End Implementation Scope

Synthetic electrical takeoff workflow; plan/package intake, electrical line-item extraction/review, dashboards, estimate comparisons, exceptions, mocked integrations.
