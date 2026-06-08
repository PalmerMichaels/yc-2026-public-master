# Sonarly

- Slug: `sonarly`
- Batch: Winter 2026
- Status: Active
- Classification: `copyable`
- Source: https://www.ycombinator.com/companies/sonarly
- Website: https://sonarly.com
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: Pending creation

## Public Description

Makes software self-healing

We want software to improve itself. Sonarly connects to your monitoring stack - tools like Sentry, Datadog, and Grafana - and triages every alert to remove noise and duplicates. It then investigates logs, traces, metrics, and code to build a living map of your production system and find root cause. The result is either a ready-to-merge fix PR or a recommendation to update your alerting rules so the noise never comes back.

## Classification Rationale

Pure software product based on public description; a clean-room implementation can provide original UI, data model, and mocked/public integrations without copying proprietary assets or bypassing access controls.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

- Repository: `sonarly-public`

## End-to-End Implementation Scope

Build an original web app that demonstrates makes software self-healing: onboarding, workspace/project setup, core workflow screens, sample data, role-aware task/status management, and mocked external integrations where needed. Include seed data, tests, and clear clean-room documentation.
