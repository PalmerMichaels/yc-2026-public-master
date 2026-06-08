# Ruma Care

- Slug: `ruma-care`
- Batch: Winter 2026
- Status: Active
- Classification: `copyable`
- Implementation Status: `classified`
- Source: https://www.ycombinator.com/companies/ruma-care
- Website: https://rumacare.com
- GitHub Project: https://github.com/users/PalmerMichaels/projects/2
- GitHub Issue: Pending creation

## Public Description

The operations stack for biologic infusion clinics

Ruma Care automates all admin work for infusion clinics - starting with prior authorizations & copay assistance enrollment. Biologics are expensive medications that cost $80-$150K+ per year per patient, and often need to be administered in specific settings called infusion clinics. Medical providers buy these drugs up front to secure pricing deals and safer inventory - they are reimbursed for the cost of the medications through the patients’ insurance. Current medical workflows aren't built for infusion clinics. Inventory, storage, transport, and billing is still managed through paper and excel spreadsheets. And because they’re so expensive, these specialty medications are denied by insurers at a rate of 37% each year. When they are denied, when workflows fail, or patients are infused before paperwork is cleared, providers don’t get reimbursed for the medication and are left covering the costs. Ruma Care solves this so clinics get paid, patients get treated faster, and care teams spend less time fighting forms. We do this in three ways: 1. For each medication, diagnosis, and insurance combination, Ruma extracts the submission criteria required to get the drug approved by insurers. 2. We pull out the correct forms, then automate the form-filling for prior authorizations. 3. Lastly, we enroll patients in copay assistance programs, all in one workflow and platform. We turn a process that traditionally spans 70+ online portals, disparate paper forms, and manual phone calling into a single, streamlined platform. As we process prior authorizations, our models learn from denial patterns to understand exactly what insurers need to see to get a prior authorization approved.

## Classification Rationale

Pure software workflow can be implemented clean-room using synthetic/user-provided data, mock integrations, and clear non-regulated disclaimers. Sector context alone does not require regulated deliverables.

## Clean-Room Constraints

- Do not copy proprietary source, private data, trademarks, logos, branding, marketing copy, or assets.
- Do not bypass access controls or use non-public integrations.
- Implement only original public software based on public descriptions and observable behavior.

## Implementation Tracking

- Status: `classified`

## Proposed Public Repository

- Repository: `ruma-care-public`

## End-to-End Implementation Scope

Build an original web app demonstrating the operations stack for biologic infusion clinics: onboarding, workspace/project setup, core workflow screens, sample/synthetic data, role-aware task/status management, mock external integrations where needed, and clear clean-room/non-regulated disclaimers. Include seed data, tests, and documentation.
