# 4. eCommerce Launch Checklist (100+ Points)

Run this in full for any platform migration, replatform, or major relaunch. Organized so it can be split across owners and run in parallel during launch week. Copy into your PM tool of choice (Notion, Linear, GitHub Projects) as individual checkboxes.

## 4.1 Catalog & Inventory (14)

- [ ] All products migrated with correct titles, descriptions, images
- [ ] Product variants (size/color/etc.) map correctly
- [ ] Pricing matches source of truth, including sale prices
- [ ] Inventory counts reconciled against source system
- [ ] Out-of-stock products handled correctly (hidden or backorder, per policy)
- [ ] SEO metadata (title tags, meta descriptions) migrated
- [ ] Product categories/collections structure preserved or intentionally redesigned
- [ ] Related/upsell/cross-sell product links intact
- [ ] Bundled/kit products function correctly
- [ ] Digital products (if any) deliver correctly post-purchase
- [ ] Product reviews migrated or re-embedded
- [ ] Weight/dimensions present for shipping calculations
- [ ] Tax classes assigned correctly per product/category
- [ ] Barcode/SKU uniqueness validated (no duplicates)

## 4.2 Checkout & Payments (16)

- [ ] All payment methods tested in sandbox
- [ ] At least one live low-value transaction processed and refunded successfully
- [ ] Guest checkout works
- [ ] Account checkout works, including saved payment methods
- [ ] Discount codes/coupons apply correctly
- [ ] Gift cards (if supported) redeem correctly
- [ ] Currency conversion correct (if multi-currency)
- [ ] Tax calculated correctly for all applicable jurisdictions
- [ ] Shipping rates calculate correctly for all zones
- [ ] Free shipping thresholds trigger correctly
- [ ] Abandoned cart recovery flow reconnected
- [ ] Order confirmation emails send and render correctly
- [ ] Failed payment handling shows clear error, doesn't lose cart
- [ ] Fraud/risk screening tool reconnected (if used)
- [ ] Chargeback/dispute webhook endpoints re-verified
- [ ] PCI compliance scope reviewed with new platform/gateway

## 4.3 Customer Accounts & Data (10)

- [ ] Customer accounts migrated
- [ ] Password reset flow works (customers will need to reset on most migrations — communicate this)
- [ ] Order history visible to logged-in customers
- [ ] Saved addresses migrated
- [ ] Wishlists/saved items migrated (if applicable)
- [ ] Subscription/recurring orders (if applicable) continue without interruption
- [ ] Loyalty points/rewards balances migrated correctly
- [ ] GDPR/CCPA data handling reviewed for new platform
- [ ] Customer data export tested (right-to-access requests)
- [ ] Account deletion flow tested (right-to-erasure requests)

## 4.4 SEO & URLs (12)

- [ ] Full list of indexed URLs pulled from Google Search Console
- [ ] 301 redirect map created for every changed URL
- [ ] Redirect map tested with a crawler (Screaming Frog or equivalent) — zero 404s on old URLs
- [ ] XML sitemap regenerated and submitted
- [ ] robots.txt reviewed (staging noindex removed before go-live)
- [ ] Canonical tags correct on all pages
- [ ] Structured data (product schema, breadcrumbs) validates
- [ ] Google Search Console property updated/verified
- [ ] Google Analytics / GA4 tracking re-verified firing correctly
- [ ] Google Merchant Center feed updated for new URLs
- [ ] Backlink-heavy pages specifically spot-checked for correct redirect
- [ ] Page load speed benchmarked against old site (Core Web Vitals)

## 4.5 Marketing & Integrations (12)

- [ ] Email marketing platform (Klaviyo, Mailchimp, etc.) reconnected
- [ ] SMS marketing platform reconnected
- [ ] Marketplace integrations (Amazon, Mercado Libre, eBay) syncing correctly
- [ ] Social commerce (Instagram/Facebook shop) feed updated
- [ ] Affiliate/referral program tracking verified
- [ ] Ad platform pixels (Meta, Google, TikTok) firing correctly
- [ ] UTM tracking preserved for ongoing campaigns
- [ ] Live chat / support widget installed and tested
- [ ] Reviews platform (Yotpo, Judge.me, etc.) reconnected
- [ ] Blog/content pages migrated with formatting intact
- [ ] Popups/announcement bars reconfigured
- [ ] A/B testing tool (if used) reconnected

## 4.6 Infrastructure & Performance (10)

- [ ] Load test run at 3-5x expected peak traffic
- [ ] SSL certificate valid on all domains/subdomains
- [ ] DNS TTL lowered 48h before cutover
- [ ] CDN configured and caching correctly
- [ ] Mobile responsiveness tested on real devices (not just browser resize)
- [ ] Cross-browser testing complete (Chrome, Safari, Firefox, Edge)
- [ ] Error monitoring (Sentry or equivalent) connected
- [ ] Uptime monitoring configured with alerting
- [ ] Backup/rollback plan documented and tested
- [ ] Staging environment matches production configuration exactly

## 4.7 Legal & Compliance (7)

- [ ] Terms of service updated and linked in footer
- [ ] Privacy policy updated and linked in footer
- [ ] Cookie consent banner functional and compliant
- [ ] Return/refund policy visible and accurate
- [ ] Accessibility (WCAG) spot-check on key pages
- [ ] Age verification (if required by product category) functional
- [ ] Business registration/tax ID displayed if legally required

## 4.8 Team & Support Readiness (9)

- [ ] Customer support trained on new admin panel
- [ ] Support macros/canned responses updated for new platform terminology
- [ ] Internal runbook for common issues documented
- [ ] On-call coverage confirmed for launch day and following 72 hours
- [ ] Escalation path defined (who to call if X breaks)
- [ ] Warehouse/fulfillment team briefed on any process changes
- [ ] Finance team briefed on reconciliation changes
- [ ] Internal announcement sent to full team with go-live time
- [ ] External customer communication drafted (if downtime expected)

## 4.9 Go-Live Day (6)

- [ ] Final data sync completed and verified
- [ ] Old platform set to read-only / order-writes frozen
- [ ] DNS cutover executed
- [ ] Smoke test: place a real order end-to-end within 15 minutes of cutover
- [ ] Monitor error rates and support inbox for first 4 hours actively
- [ ] Sponsor notified of successful go-live with summary

## 4.10 Analytics & Reporting (6)

- [ ] Revenue reporting dashboard reconnected to new platform's data source
- [ ] Conversion rate tracking validated against a manual sample of orders
- [ ] Inventory/stock reports reconnected for warehouse team
- [ ] Customer lifetime value (CLV) reporting reconnected
- [ ] Finance reconciliation report (orders vs payment processor vs bank) run once pre-launch as a dry run
- [ ] Executive/sponsor dashboard updated with new platform's data

**Total: 102 items.**

## 4.11 Project-Specific Additions

| Item | Owner | Status |
|---|---|---|
| | | |

---
[⬅ Back to playbook index](./README.md)
