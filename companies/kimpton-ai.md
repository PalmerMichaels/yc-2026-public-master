# Kimpton AI

- Slug: `kimpton-ai`
- Batch: Spring 2026
- Status: Active
- Classification: `copyable`
- Implementation Status: `in-progress`
- Source: https://www.ycombinator.com/companies/kimpton-ai
- Website: https://kimpton.ai
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/93
- Implementation Repository: https://github.com/PalmerMichaels/kimpton-ai-public

## Public Description

AI-Native Investment Research

Kimpton is the AI-native investment research platform for portfolio managers. Agents do the research and propose the trades. It was built by two ex-Goldman engineers and an ex-Vistra Energy engineer who left to start a quantitative systematic hedge fund with $10M raised from a family office at the ages of 21 and 22 years old. They scaled it to $35M at peak over four years, and productized the technology stack they ran it on. Portfolio managers spend most of their day on work that isn't investing: filings, earnings prep, 13Fs, peer benchmarking, thesis validation, trade writeups. Kimpton runs all of it autonomously and delivers structured Trade Proposals with full rationale, written as diffs to the portfolio and fitted to each manager's mandate and strategy. It is built to disagree. Most AI flatters the user, and consensus is poison for investment decisions. Kimpton is grounded in the firm's own mandate, thesis, and positions, so it surfaces breaches and risks the PM would otherwise miss instead of telling them what they want to hear. Risk profile, style, and constraints live in plain-text mandate.md and strategy.md files that drive every analysis the system performs. The rest of the desk sits alongside: Deep Research cited to source, natural-language Dashboards, Agentic Charting and Backtests, scheduled Skills for recurring workflows, and auto-generated Reports. Coverage includes FactSet pricing, fundamentals, estimates, transcripts, ownership, and M&A data, plus live prediction markets from Polymarket. Humans make the decisions. AI does everything else.

## Classification Rationale

Pure software workflow can be implemented clean-room using synthetic/user-provided data, mock integrations, and clear non-regulated disclaimers. Sector context alone does not require regulated deliverables.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Implementation Tracking

- Status: `in-progress`
- Repository: https://github.com/PalmerMichaels/kimpton-ai-public
- Notes: Implementation repository pre-created and worker launched by meta; public implementation in progress.

## Proposed Public Repository

- Repository: `kimpton-ai-public`

## End-to-End Implementation Scope

Build an original web app demonstrating ai-native investment research: onboarding, workspace/project setup, core workflow screens, sample/synthetic data, role-aware task/status management, mock external integrations where needed, and clear clean-room/non-regulated disclaimers. Include seed data, tests, and documentation.
