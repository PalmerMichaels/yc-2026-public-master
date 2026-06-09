# Aurorin CAD

- Slug: `aurorin-cad`
- Batch: Winter 2026
- YC status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source URL: https://www.ycombinator.com/companies/aurorin-cad
- Website: https://aurorincad.com
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/129
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- Public Repository: https://github.com/PalmerMichaels/aurorin-cad-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/42

## Public Description

Claude code for Mechanical Engineers

There are 2 problems: The first, CAD software is slow and the second, designing with it is a tedious process with many steps. Aurorin solves both of these problems by being a CAD software built from the ground up on a modern tech stack with AI at its heart. Building the CAD kernel lets us fully leverage AI while modernizing execution speed. Almost all existing CAD software (Solidworks, NX, Creo, Catia, Fusion 360, Onshape etc) use the same couple of underlying CAD kernels built in the 80's. It's common for these programs to take 4 hours to open a file. Aurorin uses a custom parametric and B-Rep driven CAD Kernel built to take full advantage of modern CPUs and GPUs and be AI native.

## Classification Rationale

Pure software or software-demonstrable workflow; a public clean-room version can use original UI, synthetic data, mock integrations, and disclaimers without copying assets or performing regulated core deliverables.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/aurorin-cad-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/42
- Commit: `cee5e74b13ced3751b471e5f49a5ef9f54425b4a`
- Notes: Implemented and pushed; Public repo, default branch main, clean worktree, local HEAD == origin/main, parity 0 0. Validation: npm test passed, 6 tests; npm run validate passed with clean-room validation.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

`aurorin-cad-public`

## End-to-End Implementation Scope

Build an original web app demonstrating claude code for mechanical engineers: onboarding, workspace/project setup, core workflow screens, sample/synthetic data, role-aware task/status management, mock external integrations where needed, and clear clean-room/non-regulated disclaimers. Include seed data, tests, and documentation.
