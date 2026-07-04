# 1. Project Charter Template

Use this at kickoff, before any development work starts. A charter's job is to force alignment on scope, risk, and success criteria *before* money and time are spent — not to document decisions that were already made informally.

## 1.1 Project Snapshot

| Field | Detail |
|---|---|
| Project name | |
| Sponsor / decision-maker | |
| Fractional CTO/PMO | |
| Start date | |
| Target launch date | |
| Budget ceiling | |
| Platform(s) | e.g. Shopify, WooCommerce, Medusa.js |

## 1.2 Problem Statement

*What breaks if we don't do this?* One paragraph, no jargon. Example:

> "Current platform (Magento 1) is EOL and unsupported. Site has had 3 security incidents in 6 months. Checkout conversion is 1.8% vs 3.1% industry benchmark, costing an estimated $40K/month in lost revenue."

## 1.3 Objectives (Measurable)

| # | Objective | Success Metric | Baseline | Target |
|---|---|---|---|---|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |

Rule of thumb: if an objective can't be measured, it's a hope, not an objective. Rewrite it.

## 1.4 Scope

**In scope:**
-
-

**Explicitly out of scope (this phase):**
-
-

Scope creep is the #1 killer of eCommerce launches. Anything not listed as "in scope" defaults to a change request, not a favor.

## 1.5 Stakeholders & RACI

| Name | Role | Responsible | Accountable | Consulted | Informed |
|---|---|:---:|:---:|:---:|:---:|
| | Sponsor | | ✅ | | |
| | Fractional CTO/PMO | ✅ | | | |
| | Dev lead / agency | ✅ | | | |
| | Marketing | | | ✅ | |
| | Customer support | | | | ✅ |

## 1.6 Key Risks (Top 3 Only)

Full risk matrix lives in [`02-risk-matrix.md`](./02-risk-matrix.md). List only the top 3 here so the sponsor reads them.

| Risk | Likelihood | Impact | Owner |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

## 1.7 Milestones

| Milestone | Target Date | Exit Criteria |
|---|---|---|
| Discovery complete | | Requirements signed off |
| Environment ready | | Staging matches prod config |
| Data migration dry run | | Discrepancy report < 1% |
| Feature freeze | | No new scope accepted |
| UAT sign-off | | Sponsor approves in writing |
| Go-live | | Launch checklist 100% complete |
| Post-mortem | | Report delivered |

## 1.8 Communication Cadence

| Cadence | Format | Audience |
|---|---|---|
| Weekly | Status report (see template) | Sponsor + core team |
| Daily (final 2 weeks pre-launch) | 15-min standup | Core team |
| Ad hoc | Immediate escalation for P0/P1 risks | Sponsor |

## 1.9 Sign-Off

| Role | Name | Signature/Date |
|---|---|---|
| Sponsor | | |
| Fractional CTO/PMO | | |

---
[⬅ Back to playbook index](./README.md)
