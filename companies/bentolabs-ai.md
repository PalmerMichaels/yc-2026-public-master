# BentoLabs AI

- Slug: `bentolabs-ai`
- Batch: Spring 2026
- Status: Active
- Classification: `copyable`
- Source: https://www.ycombinator.com/companies/bentolabs-ai
- Website: https://bentolabs.ai/
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/36

## Public Description

Monitoring and learning layer for long-running agents

BentoLabs is the monitoring and learning layer for long-running agents. We detect when agents silently fail or drift from the user's goal, system prompt, or tool contracts, show affected users and root cause, and suggest the prompt, skill, or harness fix. As more teams deploy agents, keeping them reliable in production becomes mission-critical. Bento sits directly in the production loop and gives teams the operational leverage required to scale agent ecosystems without scaling human firefighting alongside them. The result is a system that turns opaque agents into agents that can be monitored, debugged, and improved continuously. The founders learned this problem at Emergent (YC S24), where they built and operated production coding agents used by 5M+ users. Abhinav was hire #1 and helped Emergent hit SWE-Bench #1 and scale from $0 to $100M ARR in just 8 months. Kaushik was hire #2, led full-stack engineering at Emergent, and was key to building the infrastructure that made production agents reliable, observable, and debuggable. Bento's self-learning engine has also lifted ARC-AGI-3 (internal) by 2.6x and Terminal-Bench 2.0 (internal) from 42.2% to 52.4% pass@1 with the same model, tools, and budget.

## Classification Rationale

Pure software product based on public description; a clean-room implementation can provide original UI, data model, and mocked/public integrations without copying proprietary assets or bypassing access controls.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

- Repository: `bentolabs-ai-public`

## End-to-End Implementation Scope

Build an original web app that demonstrates monitoring and learning layer for long-running agents: onboarding, workspace/project setup, core workflow screens, sample data, role-aware task/status management, and mocked external integrations where needed. Include seed data, tests, and clear clean-room documentation.
