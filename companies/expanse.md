# Expanse

- Slug: `expanse`
- Batch: Spring 2026
- Status: Active
- Classification: `copyable`
- Source: https://www.ycombinator.com/companies/expanse
- Website: https://expanse.sh
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/57

## Public Description

Unlock wasted GPU capacity.

Expanse unlocks wasted GPU capacity. We recover idle compute through three capabilities: resource prediction (right-sizing job submissions before they reach the scheduler), optimisation suggestions (code and config changes researchers can apply themselves), and failure prediction (catching jobs that will fail before they consume hours of GPU time). We’re four engineers. We ran HPC and GPU training workloads at the largest quant funds and national supercomputing centres. We faced this problem first hand and the only fix was to over-provision and burn millions. Ismaeel built the first multimodal HPC resource predictor as research at EPCC (Edinburgh’s Parallel Computing Centre), which beat every published baseline. This is the tool we wish we had.

## Classification Rationale

Pure software product based on public description; a clean-room implementation can provide original UI, data model, and mocked/public integrations without copying proprietary assets or bypassing access controls.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

- Repository: `expanse-public`

## End-to-End Implementation Scope

Build an original web app that demonstrates unlock wasted gpu capacity: onboarding, workspace/project setup, core workflow screens, sample data, role-aware task/status management, and mocked external integrations where needed. Include seed data, tests, and clear clean-room documentation.
