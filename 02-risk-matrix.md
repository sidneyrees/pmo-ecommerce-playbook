# 2. Risk Matrix for eCommerce

Generic risk registers miss the failure modes that are specific to commerce platforms. This matrix is pre-populated with the risks that actually sink eCommerce launches, based on recurring patterns across migrations and rebuilds. Delete what doesn't apply, add what's project-specific, but start from this list — don't start from a blank page.

## 2.1 Scoring

- **Likelihood**: 1 (rare) – 5 (near certain)
- **Impact**: 1 (cosmetic) – 5 (revenue-stopping / data-loss)
- **Score** = Likelihood × Impact. Anything ≥ 15 gets a named owner and a mitigation plan before launch, no exceptions.

## 2.2 Pre-Populated Risk Categories

### Data & Migration

| Risk | L | I | Score | Mitigation | Owner |
|---|:-:|:-:|:-:|---|---|
| Product catalog data loss/corruption during migration | 3 | 5 | 15 | Full backup + dry-run migration to staging with row-count reconciliation | |
| Customer accounts/order history not migrated | 3 | 5 | 15 | Migrate in a rehearsal environment; verify a sample of accounts can log in and see past orders | |
| SKU/variant mapping mismatch causes inventory errors | 4 | 4 | 16 | Map SKUs in a spreadsheet before migration, not during | |
| Duplicate orders during platform cutover | 2 | 5 | 10 | Freeze order-writes on old platform before DNS cutover | |

### Payments & Checkout

| Risk | L | I | Score | Mitigation | Owner |
|---|---|---|---|---|---|
| Payment gateway misconfiguration blocks checkout | 2 | 5 | 10 | Test all payment methods in sandbox + one live $1 transaction pre-launch | |
| Tax calculation errors (new jurisdictions, nexus rules) | 3 | 4 | 12 | Validate tax engine against 5+ real order scenarios | |
| Abandoned cart/checkout flow regression vs old site | 3 | 4 | 12 | A/B or side-by-side checkout conversion comparison before full cutover | |

### Third-Party & Integrations

| Risk | L | I | Score | Mitigation | Owner |
|---|---|---|---|---|---|
| Vendor/agency delay or lock-in (like the emergency migration case) | 3 | 5 | 15 | Contract clause for data export rights; keep an internal admin login at all times | |
| Marketplace sync failure (Amazon, Mercado Libre, etc.) | 3 | 4 | 12 | Run parallel sync in read-only mode for 1 week before relying on it | |
| Email/SMS marketing platform disconnect post-migration | 2 | 3 | 6 | Re-verify API keys and webhook endpoints post-cutover | |

### Infrastructure & Performance

| Risk | L | I | Score | Mitigation | Owner |
|---|---|---|---|---|---|
| Site can't handle launch-day or sale-day traffic spike | 3 | 5 | 15 | Load test at 3-5x expected peak before any promoted launch | |
| DNS/SSL cutover downtime | 2 | 4 | 8 | Lower TTL 48h in advance; cutover during lowest-traffic window | |
| SEO ranking loss from URL structure changes | 4 | 4 | 16 | 301 redirect map for every indexed URL, verified with a crawl tool | |

### People & Process

| Risk | L | I | Score | Mitigation | Owner |
|---|---|---|---|---|---|
| Customer support unprepared for new admin/order flow | 4 | 3 | 12 | Dry-run training session 1 week pre-launch using staging | |
| Key vendor/developer unavailable at go-live | 2 | 5 | 10 | Confirm on-call coverage in writing 1 week out | |
| Scope creep pushes launch date without re-baselining budget | 4 | 3 | 12 | Every scope addition requires a written change request against the charter | |

## 2.3 Weekly Risk Review

Don't just fill this in once. Review scores weekly — likelihood typically rises as launch approaches for anything not yet mitigated. Track score trend, not just current state:

| Week | Risk | Previous Score | Current Score | Trend | Notes |
|---|---|---|---|---|---|
| | | | | ↑/↓/→ | |

---
[⬅ Back to playbook index](./README.md)
