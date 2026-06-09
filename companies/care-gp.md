# Care GP

- Slug: `care-gp`
- Batch: Summer 2026
- YC status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source URL: https://www.ycombinator.com/companies/care-gp
- Website: https://caregp.com.au/
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/145
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- Public Repository: https://github.com/PalmerMichaels/care-gp-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/58

## Public Description

AI agents to run primary healthcare operations

Care GP is building AI agents to run operations for primary healthcare clinics

## Classification Rationale

Pure software workflow can be implemented clean-room using synthetic/user-provided data, mock integrations, and clear non-regulated disclaimers. Sector context alone does not require regulated deliverables.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/care-gp-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/58
- Commit: `d6ba09cc32c781058999dc4b076785fc807353c7`
- Notes: Implemented and pushed; Scope verified: Primary healthcare operations/admin only; synthetic clinics/staff/admin tasks, scheduling, approvals, audit, mocked dry-run admin connectors. No clinical intake/routing/acuity/triage/diagnosis/treatment/PHI/medical advice/CDS/medical-device behavior. Validation: npm run build, npm run validate, npm test, npm run build && npm start passed; stale-scope scan no matches. Worktree clean and HEAD == origin/main.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

`care-gp-public`

## End-to-End Implementation Scope

Primary healthcare operations/admin only; synthetic clinics/staff/admin tasks, scheduling, approvals, audit, mocked dry-run admin connectors. No clinical intake/routing/acuity/triage/diagnosis/treatment/PHI/medical advice/CDS/medical-device behavior.
