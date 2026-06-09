# Alt-X

- Slug: `alt-x`
- Batch: Winter 2026
- YC status: Active
- Classification: `copyable`
- Implementation Status: `implemented`
- Source URL: https://www.ycombinator.com/companies/alt-x
- Website: https://alt-x.co
- GitHub Issue: https://github.com/PalmerMichaels/yc-2026-public-master/issues/125
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- Public Repository: https://github.com/PalmerMichaels/alt-x-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/38

## Public Description

Automation for institutional-grade financial modeling in Excel

Alt-X is building the AI-native liquidity layer for private markets. Private markets have created trillions of dollars in value, yet remain fragmented, illiquid, and inaccessible. While public markets benefit from exchanges, market makers, brokerages, and data infrastructure, private markets still rely on brokers, spreadsheets, and manual workflows to connect buyers and sellers. Alt-X uses AI to automate the core functions required to make private assets liquid. We streamline diligence, valuation, investor matching, and transaction execution, reducing the friction that makes private-market transactions slow, expensive, and opaque today. Our initial focus is venture-backed secondaries. We source opportunities from founders, employees, and early investors while building a network of accredited investors seeking exposure to the world's most valuable private companies. Over time, we believe every private asset—from startup equity to private credit and alternative investments—will require modern liquidity infrastructure. Building trusted infrastructure for private markets is difficult. Transactions involve complex diligence, fragmented information, transfer restrictions, and significant compliance requirements. Alt-X is focused on creating systems that can support real transactions at scale, not just marketplace listings. Ryan Samadi (Stanford CS/AI, former Citadel commodities trader) and Michael Wachsman (Cornell CS, infrastructure engineer) are building Alt-X because they believe ownership of innovation should be more liquid, transparent, and accessible. Today, Alt-X has sourced over $1.5 million in transaction opportunities and assembled a network of 40 accredited investors representing hundreds of millions of dollars in investable assets. Our mission is to democratize ownership of innovation by building the financial infrastructure that private markets have never had.

## Classification Rationale

Pure software workflow can be implemented clean-room using synthetic/user-provided data, mock integrations, and clear non-regulated disclaimers. Sector context alone does not require regulated deliverables.

## Implementation Tracking

- Status: `implemented`
- Repository: https://github.com/PalmerMichaels/alt-x-public
- Public GitHub Project: https://github.com/users/PalmerMichaels/projects/38
- Commit: `57192277e57d8dd8d06691c6930664666cfdef59`
- Notes: Implemented and pushed; local main matches origin/main. Validation: npm run validate passed (4 tests, 0 failures); npm start passed with synthetic underwriting summary. Clean-room limitations: Synthetic data only; no Alt-X code/UI/branding/assets/private data/proprietary workflows; no real Excel plugin, AI calls, third-party services, credentials, KYC, investor outreach, transaction execution, or investment advice.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Proposed Public Repository

`alt-x-public`

## End-to-End Implementation Scope

Build an original web app demonstrating automation for institutional-grade financial modeling in excel: onboarding, workspace/project setup, core workflow screens, sample/synthetic data, role-aware task/status management, mock external integrations where needed, and clear clean-room/non-regulated disclaimers. Include seed data, tests, and documentation.
