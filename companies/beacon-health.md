# Beacon Health

- Slug: `beacon-health`
- Batch: Winter 2026
- YC status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source URL: https://www.ycombinator.com/companies/beacon-health
- Website: https://www.beaconhealth.ai/
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/135
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- Public Repository: https://github.com/PalmerMichaels/beacon-health-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/48

## Public Description

AI Employees for Primary Care

Beacon Health (YC W26) is building AI employees that double revenue for primary care practices while also reducing the total cost of care. Primary care is the primary source of care for over 200M Americans, but physicians don’t have the bandwidth to manage their patient panels. Beacon Health builds AI employees that automate tedious background workflows - preventative screenings, prior authorizations, referrals, and risk adjustment. We handle these workflows from start to finish, directly in their EHR. We’re on a mission is to bring joy back to primary care.

## Classification Rationale

Pure software workflow can be implemented clean-room using synthetic/user-provided data, mock integrations, and clear non-regulated disclaimers. Sector context alone does not require regulated deliverables.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/beacon-health-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/48
- Commit: `3c5c894c608f6313c252ae94e348c8ad357a6773`
- Notes: Implemented and pushed; local main matches origin/main. Scope verified: Non-clinical/admin-only synthetic operations console; intake admin, appointment/task coordination, staffing/coverage views, document checklist/status, mock admin assistant drafts. Explicitly no diagnosis/treatment/triage/PHI/medical advice/clinical decision support/medical-device behavior/real integrations. Validation: npm test, npm run validate, npm start passed.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

`beacon-health-public`

## End-to-End Implementation Scope

Non-clinical/admin-only synthetic operations console; intake admin, appointment/task coordination, staffing/coverage views, document checklist/status, mock admin assistant drafts. Explicitly no diagnosis/treatment/triage/PHI/medical advice/clinical decision support/medical-device behavior/real integrations.
