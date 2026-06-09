# Lattice Health

- Slug: `lattice-health`
- Batch: Spring 2026
- Status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source: https://www.ycombinator.com/companies/lattice-health
- Website: https://www.latticehealthai.com/
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/103
- Implementation Repository: https://github.com/PalmerMichaels/lattice-health-public
- Implementation Commit: `6d1d0fe415a106b7a2f065ab165901ff4ea809ff`

## Public Description

Monitoring and governance for deployed medical imaging AI

Lattice Health monitors deployed medical imaging AI so hospitals can tell whether each model is still working, tracking agreement with the radiologist's read, drift, and performance across patient groups. It observes rather than controls and produces the evidence teams need for safety, governance and compliance.

## Classification Rationale

Pure software workflow can be implemented clean-room using synthetic/user-provided data, mock integrations, and clear non-regulated disclaimers. Sector context alone does not require regulated deliverables.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/lattice-health-public
- Commit: `6d1d0fe415a106b7a2f065ab165901ff4ea809ff`
- Notes: Implemented and pushed; local main matches origin/main.

## Proposed Public Repository

- Repository: `lattice-health-public`

## End-to-End Implementation Scope

Medical imaging AI monitoring/governance console; no diagnosis/treatment/triage, no PHI/real images, no clinical claims, no FDA/regulatory approval behavior, no medical-device behavior.
