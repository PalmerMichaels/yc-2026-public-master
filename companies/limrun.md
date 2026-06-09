# Limrun

- Slug: `limrun`
- Batch: Spring 2026
- Status: Active
- Classification: `copyable`
- Implementation Status: `in-progress`
- Source: https://www.ycombinator.com/companies/limrun
- Website: https://lim.run
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/106
- Implementation Repository: https://github.com/PalmerMichaels/limrun-public

## Public Description

Extend your cloud agent with XCode, Android and more

Coding agents in the cloud don't work for majority of teams who require native capabilities; they lack XCode for iOS, Emulator for Android, Unity for game development teams. We are on a mission to cloudify every local development utility so that regardless of where it runs, your agent can compose an ideal set of capabilities on the fly so you don't need to run it on your laptop. Today, we provide remote services such as XCode, iOS & Android simulators to enable coding agents running in any sandbox to be able to build and iterate over mobile apps, too. Replit, Rork, Momentic, Minitap and more agent companies have built mobile development and testing experiences on Limrun platform. Coconote (Quizlet), SorceJobs (W25) and more companies with mobile apps use Limrun with their cloud agents, merging PRs without having to check out the code locally.

## Classification Rationale

Pure software or software-demonstrable workflow; a public clean-room version can use original UI, synthetic data, mock integrations, and disclaimers without copying assets or performing regulated core deliverables.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Implementation Tracking

- Status: `in-progress`
- Repository: https://github.com/PalmerMichaels/limrun-public
- Notes: Implementation repository pre-created and worker launched by meta; public implementation in progress.

## Proposed Public Repository

- Repository: `limrun-public`

## End-to-End Implementation Scope

Cloud-agent extension workspace for Xcode/Android/tool connectors with synthetic build/device tasks and mocked repo/build/device/cloud integrations.
