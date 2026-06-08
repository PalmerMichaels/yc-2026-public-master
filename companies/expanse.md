# Expanse

- Slug: `expanse`
- Batch: Spring 2026
- Status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source: https://www.ycombinator.com/companies/expanse
- Website: https://expanse.sh
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/57
- Implementation Repository: https://github.com/PalmerMichaels/expanse-public
- Implementation Commit: `0a22ee2d1b758a58ca9618ca6c210b9e5aef2484`

## Public Description

Unlock wasted GPU capacity.

Expanse unlocks wasted GPU capacity. We recover idle compute through three capabilities: resource prediction (right-sizing job submissions before they reach the scheduler), optimisation suggestions (code and config changes researchers can apply themselves), and failure prediction (catching jobs that will fail before they consume hours of GPU time). We’re four engineers. We ran HPC and GPU training workloads at the largest quant funds and national supercomputing centres. We faced this problem first hand and the only fix was to over-provision and burn millions. Ismaeel built the first multimodal HPC resource predictor as research at EPCC (Edinburgh’s Parallel Computing Centre), which beat every published baseline. This is the tool we wish we had.

## Classification Rationale

Pure software or software-demonstrable workflow; a public clean-room version can use original UI, synthetic data, mock integrations, and disclaimers without copying assets or performing regulated core deliverables.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/expanse-public
- Commit: `0a22ee2d1b758a58ca9618ca6c210b9e5aef2484`
- Notes: Implemented and pushed; local main matches origin/main.

## Proposed Public Repository

- Repository: `expanse-public`

## End-to-End Implementation Scope

Build an original web app demonstrating unlock wasted gpu capacity.: onboarding, workspace/project setup, core workflow screens, sample/synthetic data, role-aware task/status management, mock external integrations where needed, and clear clean-room/non-regulated disclaimers. Include seed data, tests, and documentation.
