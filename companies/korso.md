# Korso

- Slug: `korso`
- Batch: Spring 2026
- Status: Active
- Classification: `copyable`
- Implementation Status: `in-progress`
- Source: https://www.ycombinator.com/companies/korso
- Website: https://korsoai.com/
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/98
- Implementation Repository: https://github.com/PalmerMichaels/korso-public

## Public Description

The Intelligence Layer for Manufacturing.

Korso builds AI agents that handle the operational work manufacturers still do manually, including processing RFQs, following up on quotes, coordinating with suppliers, and keeping production on track when things go wrong. Our agents plug into your existing ERP and CRM, understand your workflows, and act on your behalf: triaging incoming requests, chasing delayed orders, notifying customers, and escalating when human judgment is needed. We built Korso around the reality that enterprise systems cannot afford mistakes. Every agent action passes through verification layers, tools are scoped, and critical operations go through dry-run validation and secondary review. Full audit trails mean you can see exactly what was done, why, and when. Most AI automation breaks down at the ERP integration layer. Korso's orchestration is built for the messiness of real manufacturing systems, with long-running workflows that span weeks and checkpointing that never loses progress. Instead of replacing your systems, Korso makes them work harder, so your team spends less time on coordination and more time on the work that actually matters.

## Classification Rationale

Pure software or software-demonstrable workflow; a public clean-room version can use original UI, synthetic data, mock integrations, and disclaimers without copying assets or performing regulated core deliverables.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Implementation Tracking

- Status: `in-progress`
- Repository: https://github.com/PalmerMichaels/korso-public
- Notes: Implementation repository pre-created and worker launched by meta; public implementation in progress.

## Proposed Public Repository

- Repository: `korso-public`

## End-to-End Implementation Scope

Build an original web app demonstrating the intelligence layer for manufacturing.: onboarding, workspace/project setup, core workflow screens, sample/synthetic data, role-aware task/status management, mock external integrations where needed, and clear clean-room/non-regulated disclaimers. Include seed data, tests, and documentation.
