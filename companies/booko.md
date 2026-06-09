# Booko

- Slug: `booko`
- Batch: Winter 2026
- YC status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source URL: https://www.ycombinator.com/companies/booko
- Website: https://bookoapp.com
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/137
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- Public Repository: https://github.com/PalmerMichaels/booko-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/50

## Public Description

Dynamically pricing the whole economy.

Booko helps businesses that sell bookable time slots make more money by dynamically pricing their time. Unlike physical inventory, unsold time slots disappear forever, yet most time-slot-based businesses still rely on static pricing. We integrate with existing booking systems to adjust prices and incentives based on historical utilization, availability, and demand. Early customers see ~20% revenue uplift by selling time that would have otherwise gone unsold.

## Classification Rationale

Pure software or software-demonstrable workflow; a public clean-room version can use original UI, synthetic data, mock integrations, and disclaimers without copying assets or performing regulated core deliverables.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/booko-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/50
- Commit: `8065db8bc3980e2e2137c721eb3a95b91e501659`
- Notes: Implemented and pushed; local main matches origin/main. Scope verified: Dynamic pricing workflow only; product/service catalog, synthetic demand/supply signals, pricing recommendations, scenario simulation, approval flows, audit history, mocked integrations. No real commerce/payment execution/credentials/live marketplace integrations/real customer or pricing data. Validation: npm test passed; npm run start passed; stale reading/club TypeScript references removed.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

`booko-public`

## End-to-End Implementation Scope

Dynamic pricing workflow only; product/service catalog, synthetic demand/supply signals, pricing recommendations, scenario simulation, approval flows, audit history, mocked integrations. No real commerce/payment execution/credentials/live marketplace integrations/real customer or pricing data.
