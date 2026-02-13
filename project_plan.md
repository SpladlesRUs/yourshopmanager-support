# Project Plan — YourShopManager Support Documentation

## Goal
Create searchable, screenshot-rich documentation for store owners to operate YourShopManager effectively.

## Scope (Store Owner, Phase 1)
- Getting Started for Store Owners (account, login, navigation)
- Dashboard Overview (KPIs, recent activity, quick actions)
- Inventory Management Basics (add/edit products, categories)
- Trade-Ins Workflow (valuation rules, approvals, receipts)
- Rewards Program Setup (earn rules, redemption, balances)

## Repo Structure
- docs/
  - README.md (index)
  - store-owner/
    - getting-started-owner.md
    - dashboard-overview.md
    - inventory-basics.md
    - trade-ins-workflow.md
    - rewards-setup.md
  - _images/store-owner/<slug>-NN.jpg

## Iterations

### Iteration 1 — Core owner workflows (MVP)
Deliver the 5 core pages with 2–6 screenshots each, step-by-steps, tips, and FAQs.

### Iteration 2 — Money, customers, reporting (depth)
- pricing-rules-and-markups.md (examples, margins)
- customers-and-profiles.md (notes, history)
- store-credit-and-gift-balances.md (issue, apply, audit)
- reporting-and-analytics.md (sales, P&L, differentials)
- troubleshooting-and-faqs.md (error → fix mapping)

### Iteration 3 — Admin, teams, ecosystem
- store-settings.md (branding, taxes, locations, hours)
- users-and-roles.md (permissions matrix)
- integrations-and-exports.md (channels, exports)
- notifications-and-templates.md (triggers, customization)
- glossary.md (owner-friendly terms)

## Writing & Media Standards
- Each page: concise overview, ordered steps, callouts, and FAQs
- Screenshots: crop to relevant area, readable at 1200px width; annotate sparingly (numbers/arrows)
- Filenames: `docs/_images/store-owner/<slug>-NN.jpg`
- Cross-links between related pages

## Workflow
- Work on feature branch per iteration (e.g., `docs/owner-iteration-1`)
- Small, frequent commits; push after each batch of screenshots/edits
- PR with description and checklist; reviewer verifies links, images, and copy

## Risks / Dependencies
- Browser relay stability for screenshot capture
- Demo data alignment with docs steps
- Changes to UI while drafting

## Out of Scope (Phase 1)
- Clerk/Manager user roles
- Deep POS/checkout flows
- Non-owner integrations

## Success Criteria
- All Iteration 1 pages published with clear steps and images
- Docs searchable and cross-linked
- Positive owner feedback; reduced support questions for covered topics
