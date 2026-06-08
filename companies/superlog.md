# Superlog

- Slug: `superlog`
- Batch: Spring 2026
- Status: Active
- Classification: `copyable`
- Source: https://www.ycombinator.com/companies/superlog
- Website: https://superlog.sh/
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: Pending creation

## Public Description

Observability that installs itself and fixes the bugs it finds.

Sentry and Datadog dump a stream of alerts. Most are duplicates, most lack context, and you still have to solve the issue yourself. Superlog is AI-native observability that's meant not to be opened. A wizard scans your repo and installs proper OpenTelemetry instrumentation, then runs daily to keep up as you ship new code. When something breaks, Superlog groups the errors into a single incident, investigates with full context (logs, traces, recent deploys, past Slack threads), and posts one mergeable PR in Slack. You merge it, ignore it, or open it as a Claude Code session and modify it. Telemetry is vendor-neutral, so you keep every log, trace, and metric we install, even if you leave.

## Classification Rationale

Pure software product based on public description; a clean-room implementation can provide original UI, data model, and mocked/public integrations without copying proprietary assets or bypassing access controls.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

- Repository: `superlog-public`

## End-to-End Implementation Scope

Build an original web app that demonstrates observability that installs itself and fixes the bugs it finds: onboarding, workspace/project setup, core workflow screens, sample data, role-aware task/status management, and mocked external integrations where needed. Include seed data, tests, and clear clean-room documentation.
