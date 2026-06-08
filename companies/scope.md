# Scope

- Slug: `scope`
- Batch: Spring 2026
- Status: Active
- Classification: `copyable`
- Source: https://www.ycombinator.com/companies/scope
- Website: https://tryscope.app
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: Pending creation

## Public Description

The infra layer for AI agent experience.

Scope is the system companies use to measure and improve how agents discover, interact and use their product. As more products gets used through AI agents like Claude Code, Codex, Cursor, and similar agents, agents are starting to influence which tools get chosen, how they get set up, and whether they keep getting used. Most companies still cannot see that process clearly. We run real workflows across agents and show teams when the agent picks them versus a competitor, where it breaks, where docs or product surfaces confuse the agent, and what to change to get better results and a better agent experience. I started Scope after working on interpretability research for closed-source models at Princeton and later as an ML engineer in GEO/AEO. I kept seeing the same pattern: these systems were shaping real product discovery and usage, but companies had very little visibility into what the model was actually doing. We are starting with products that agents can directly interact with, especially APIs, infra products, CLIs, and MCP servers.

## Classification Rationale

Pure software or software-demonstrable workflow; a public clean-room version can use original UI, synthetic data, mock integrations, and disclaimers without copying assets or performing regulated core deliverables.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

- Repository: `scope-public`

## End-to-End Implementation Scope

Build an original web app demonstrating the infra layer for ai agent experience.: onboarding, workspace/project setup, core workflow screens, sample/synthetic data, role-aware task/status management, mock external integrations where needed, and clear clean-room/non-regulated disclaimers. Include seed data, tests, and documentation.
