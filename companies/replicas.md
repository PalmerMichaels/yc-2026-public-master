# Replicas

- Slug: `replicas`
- Batch: Spring 2026
- Status: Active
- Classification: `copyable`
- Source: https://www.ycombinator.com/companies/replicas
- Website: https://tryreplicas.com
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: Pending creation

## Public Description

Run any coding agent harness in the cloud

Replicas is a background coding agent that allows you to delegate tasks to Claude Code or Codex from Slack, Linear, GitHub, and more. Each task works inside of a sandboxed virtual machine, allowing teams to heavily parallelize work and burn through tickets. Replicas agents output higher quality PRs via feedback loops - each task automatically is notified and fixes CI failures and reads all code reviews. With Environments, engineering teams can configure agents to run their entire codebase locally, verify its work, and provide preview URLs.

## Classification Rationale

Pure software product based on public description; a clean-room implementation can provide original UI, data model, and mocked/public integrations without copying proprietary assets or bypassing access controls.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

- Repository: `replicas-public`

## End-to-End Implementation Scope

Build an original web app that demonstrates run any coding agent harness in the cloud: onboarding, workspace/project setup, core workflow screens, sample data, role-aware task/status management, and mocked external integrations where needed. Include seed data, tests, and clear clean-room documentation.
