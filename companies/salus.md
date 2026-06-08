# Salus

- Slug: `salus`
- Batch: Winter 2026
- Status: Active
- Classification: `copyable`
- Source: https://www.ycombinator.com/companies/salus
- Website: https://www.usesalus.ai/
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: Pending creation

## Public Description

Guardrails to validate your agent's actions before they execute

Your agent processed a refund without looking up the order ID, costing you thousands. You only found out three hours later from a support ticket. Evals, output scoring, and observability can reduce the likelihood of mistakes like these occurring - but there's no solution that inspects and prevents an action as it’s about to execute. Salus does that. We’ve built an API that wraps around your agent and checks its actions at run time, blocking incorrect ones and providing immediate feedback to guide retries. Kevin and Vedant were roommates at Stanford, where they both studied computer science.

## Classification Rationale

Pure software product based on public description; a clean-room implementation can provide original UI, data model, and mocked/public integrations without copying proprietary assets or bypassing access controls.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

- Repository: `salus-public`

## End-to-End Implementation Scope

Build an original web app that demonstrates guardrails to validate your agent's actions before they execute: onboarding, workspace/project setup, core workflow screens, sample data, role-aware task/status management, and mocked external integrations where needed. Include seed data, tests, and clear clean-room documentation.
